# TransactionsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**transactionsInboundPost**](TransactionsApi.md#transactionsInboundPost) | **POST** /transactions/inbound | Submit an EDI interchange for validation and conversion (Persistent)
[**transactionsOutboundPost**](TransactionsApi.md#transactionsOutboundPost) | **POST** /transactions/outbound | Submit an XML format interchange for conversion to EDI (Persistent)
[**transactionsTranslatorPost**](TransactionsApi.md#transactionsTranslatorPost) | **POST** /transactions/translator | Translate an EDI interchange (Persistent)
[**transactionsValidatorPost**](TransactionsApi.md#transactionsValidatorPost) | **POST** /transactions/validator | Validate an EDI interchange (Persistent)


<a name="transactionsInboundPost"></a>
# **transactionsInboundPost**
> Object transactionsInboundPost(body)

Submit an EDI interchange for validation and conversion (Persistent)

    Submit an EDI interchange for validation and conversion to a back-end application. This operation accepts a well-formed EDI interchange and (when successfully translated) responds with an EDI format corresponding to the input (e.g. an X12 &#x60;997&#x60;). The transformed interchange is written to local server storage (other other queuing system) to be retrieved by or forwarded to a back-end application for further processing. 

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **Object**| EDI payload in either X12 or EDIFACT format |

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/EDI-X12, application/EDIFACT
- **Accept**: application/EDI-X12, application/EDIFACT, text/plain, 

<a name="transactionsOutboundPost"></a>
# **transactionsOutboundPost**
> Object transactionsOutboundPost(body)

Submit an XML format interchange for conversion to EDI (Persistent)

    Submit an XML interchange for validation and conversion to EDI. This operation accepts a well-formed XML interchange and (when successfully translated) responds with an EDI format corresponding to the input. Information about the interchange (transaction control numbers, types of transactions, etc.) is persisted to the Fresno database for tracking and to support acknowledgement confirmation. 

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **Object**| XML payload to be converted to EDI |

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/xml
- **Accept**: application/EDI-X12, application/EDIFACT

<a name="transactionsTranslatorPost"></a>
# **transactionsTranslatorPost**
> Object transactionsTranslatorPost(body)

Translate an EDI interchange (Persistent)

    Translate an EDI interchange and persist meta information and validation status in history. This operation accepts a well-formed EDI interchange and (when successfully translated) responds with an XML representation of the interchange. The &#x60;Link&#x60; header includes a URI that may be used for retrieval of validation/status information pertaining to the interchange. 

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **Object**| EDI payload in either X12 or EDIFACT format |

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/EDI-X12, application/EDIFACT
- **Accept**: application/json, application/xml

<a name="transactionsValidatorPost"></a>
# **transactionsValidatorPost**
> Object transactionsValidatorPost(body)

Validate an EDI interchange (Persistent)

    Validate an EDI interchange and persist meta information and validation status in history. This operation accepts a well-formed EDI interchange and responds with either an EDI format corresponding to the input or a JSON format describing the result of validation. 

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **Object**| EDI payload in either X12 or EDIFACT format |

### Return type

[**Object**](../Models/object.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/EDI-X12, application/EDIFACT
- **Accept**: application/EDIFACT, application/EDI-X12, application/json, text/plain, 

