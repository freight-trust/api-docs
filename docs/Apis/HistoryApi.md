# HistoryApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**historyGroupsGet**](HistoryApi.md#historyGroupsGet) | **GET** /history/groups | Retrieve a list of functional groups for a particular interchange
[**historyGroupsIdGet**](HistoryApi.md#historyGroupsIdGet) | **GET** /history/groups/{id} | Retrieve a functional group by identifier
[**historyInterchangesGet**](HistoryApi.md#historyInterchangesGet) | **GET** /history/interchanges | Retrieve a list of interchanges
[**historyInterchangesIdGet**](HistoryApi.md#historyInterchangesIdGet) | **GET** /history/interchanges/{id} | Retrieve an interchange by identifier
[**historyInterchangesInterchangeIdRelationshipsAcknowledgementGet**](HistoryApi.md#historyInterchangesInterchangeIdRelationshipsAcknowledgementGet) | **GET** /history/interchanges/{interchangeId}/relationships/acknowledgement | Retrieve an interchange acknowledgement by identifier
[**historyTransactionsGet**](HistoryApi.md#historyTransactionsGet) | **GET** /history/transactions | Retrieve a list of transactions for a particular interchange, group, or date/time range
[**historyTransactionsIdGet**](HistoryApi.md#historyTransactionsIdGet) | **GET** /history/transactions/{id} | Retrieve a transaction by identifier


<a name="historyGroupsGet"></a>
# **historyGroupsGet**
> List historyGroupsGet(interchangeId)

Retrieve a list of functional groups for a particular interchange

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **interchangeId** | **String**| Interchange identifier | [default to null]

### Return type

[**List**](../Models/Group.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="historyGroupsIdGet"></a>
# **historyGroupsIdGet**
> Group historyGroupsIdGet(id)

Retrieve a functional group by identifier

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Record identifier | [default to null]

### Return type

[**Group**](../Models/Group.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="historyInterchangesGet"></a>
# **historyInterchangesGet**
> List historyInterchangesGet(page)

Retrieve a list of interchanges

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| Page number | [default to 1]

### Return type

[**List**](../Models/Interchange.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="historyInterchangesIdGet"></a>
# **historyInterchangesIdGet**
> Interchange historyInterchangesIdGet(id)

Retrieve an interchange by identifier

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [default to null]

### Return type

[**Interchange**](../Models/Interchange.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="historyInterchangesInterchangeIdRelationshipsAcknowledgementGet"></a>
# **historyInterchangesInterchangeIdRelationshipsAcknowledgementGet**
> Object historyInterchangesInterchangeIdRelationshipsAcknowledgementGet(interchangeId)

Retrieve an interchange acknowledgement by identifier

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **interchangeId** | **String**|  | [default to null]

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/EDIFACT, application/EDI-X12, application/json

<a name="historyTransactionsGet"></a>
# **historyTransactionsGet**
> List historyTransactionsGet(dateFrom, dateThru, groupId, interchangeId)

Retrieve a list of transactions for a particular interchange, group, or date/time range

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dateFrom** | **Date**|  | [optional] [default to null]
 **dateThru** | **Date**|  | [optional] [default to null]
 **groupId** | **String**|  | [optional] [default to null]
 **interchangeId** | **String**|  | [optional] [default to null]

### Return type

[**List**](../Models/Transaction.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="historyTransactionsIdGet"></a>
# **historyTransactionsIdGet**
> Transaction historyTransactionsIdGet(id)

Retrieve a transaction by identifier

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Record identifier | [default to null]

### Return type

[**Transaction**](../Models/Transaction.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

