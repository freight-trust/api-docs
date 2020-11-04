# SchemaMaintenanceApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**schemasControlGet**](SchemaMaintenanceApi.md#schemasControlGet) | **GET** /schemas/control | 
[**schemasGet**](SchemaMaintenanceApi.md#schemasGet) | **GET** /schemas | Retrieve a list of transaction schemas known to the system
[**schemasPost**](SchemaMaintenanceApi.md#schemasPost) | **POST** /schemas | Create a new transaction schema to be used for EDI validation
[**schemasStandardTypeVersionFileDelete**](SchemaMaintenanceApi.md#schemasStandardTypeVersionFileDelete) | **DELETE** /schemas/{standard}/{type}/{version}/{file} | 
[**schemasStandardTypeVersionFileGet**](SchemaMaintenanceApi.md#schemasStandardTypeVersionFileGet) | **GET** /schemas/{standard}/{type}/{version}/{file} | 
[**schemasTransactionGet**](SchemaMaintenanceApi.md#schemasTransactionGet) | **GET** /schemas/transaction | 


<a name="schemasControlGet"></a>
# **schemasControlGet**
> Object schemasControlGet(standard, version)



### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **standard** | **String**|  | [optional] [default to null]
 **version** | **String**|  | [optional] [default to null]

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/schema+json

<a name="schemasGet"></a>
# **schemasGet**
> schemasGet()

Retrieve a list of transaction schemas known to the system

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="schemasPost"></a>
# **schemasPost**
> schemasPost(standard, agencyCode, version, release, industryCode, transactionCode, senderIdType, senderId, receiverIdType, receiverId, file)

Create a new transaction schema to be used for EDI validation

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **standard** | **String**|  | [optional] [default to null]
 **agencyCode** | **String**|  | [optional] [default to null]
 **version** | **String**|  | [optional] [default to null]
 **release** | **String**|  | [optional] [default to ]
 **industryCode** | **String**|  | [optional] [default to ]
 **transactionCode** | **String**|  | [optional] [default to null]
 **senderIdType** | **String**|  | [optional] [default to ]
 **senderId** | **String**|  | [optional] [default to ]
 **receiverIdType** | **String**|  | [optional] [default to ]
 **receiverId** | **String**|  | [optional] [default to ]
 **file** | **File**|  | [optional] [default to null]

### Return type

null (empty response body)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

<a name="schemasStandardTypeVersionFileDelete"></a>
# **schemasStandardTypeVersionFileDelete**
> schemasStandardTypeVersionFileDelete(file, standard, type, version)



### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | **String**|  | [default to null]
 **standard** | **String**|  | [default to null]
 **type** | **String**|  | [default to null]
 **version** | **String**|  | [default to null]

### Return type

null (empty response body)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="schemasStandardTypeVersionFileGet"></a>
# **schemasStandardTypeVersionFileGet**
> Object schemasStandardTypeVersionFileGet(file, standard, type, version)



### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | **String**|  | [default to null]
 **standard** | **String**|  | [default to null]
 **type** | **String**|  | [default to null]
 **version** | **String**|  | [default to null]

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/xml, application/json

<a name="schemasTransactionGet"></a>
# **schemasTransactionGet**
> Object schemasTransactionGet(standard, type, version)



### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **standard** | **String**|  | [optional] [default to null]
 **type** | **String**|  | [optional] [default to null]
 **version** | **String**|  | [optional] [default to null]

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/schema+json

