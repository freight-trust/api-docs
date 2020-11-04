# AdministrationApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**controlsChannelsGet**](AdministrationApi.md#controlsChannelsGet) | **GET** /controls/channels | Retrieve a list of channels, optionally filtering by name
[**controlsChannelsIdGet**](AdministrationApi.md#controlsChannelsIdGet) | **GET** /controls/channels/{id} | Retrieve a channel by unique identifier
[**controlsChannelsIdPut**](AdministrationApi.md#controlsChannelsIdPut) | **PUT** /controls/channels/{id} | Update a channel
[**controlsChannelsPost**](AdministrationApi.md#controlsChannelsPost) | **POST** /controls/channels | Create a new channel
[**controlsGroupControlsGet**](AdministrationApi.md#controlsGroupControlsGet) | **GET** /controls/group-controls | Retrieve an interchange control&#39;s group control list
[**controlsGroupControlsIdGet**](AdministrationApi.md#controlsGroupControlsIdGet) | **GET** /controls/group-controls/{id} | Retrieve a group control by identifier
[**controlsGroupControlsIdPut**](AdministrationApi.md#controlsGroupControlsIdPut) | **PUT** /controls/group-controls/{id} | Updates a group control
[**controlsGroupControlsPost**](AdministrationApi.md#controlsGroupControlsPost) | **POST** /controls/group-controls | Create a new group control record for an interchange control.
[**controlsInterchangeControlsGet**](AdministrationApi.md#controlsInterchangeControlsGet) | **GET** /controls/interchange-controls | Retrieve a channel&#39;s interchange controls
[**controlsInterchangeControlsIdGet**](AdministrationApi.md#controlsInterchangeControlsIdGet) | **GET** /controls/interchange-controls/{id} | Retrieve an interchange control by ID
[**controlsInterchangeControlsIdPut**](AdministrationApi.md#controlsInterchangeControlsIdPut) | **PUT** /controls/interchange-controls/{id} | Updates an interchange control
[**controlsInterchangeControlsPost**](AdministrationApi.md#controlsInterchangeControlsPost) | **POST** /controls/interchange-controls | Create a new interchange control record for a channel.
[**controlsTransactionControlsGet**](AdministrationApi.md#controlsTransactionControlsGet) | **GET** /controls/transaction-controls | Retrieve a transaction control list
[**controlsTransactionControlsIdGet**](AdministrationApi.md#controlsTransactionControlsIdGet) | **GET** /controls/transaction-controls/{id} | Retrieve a transaction control by ID
[**controlsTransactionControlsIdPut**](AdministrationApi.md#controlsTransactionControlsIdPut) | **PUT** /controls/transaction-controls/{id} | Update a transaction control
[**controlsTransactionControlsPost**](AdministrationApi.md#controlsTransactionControlsPost) | **POST** /controls/transaction-controls | Create a new transaction control record for an interchange control.


<a name="controlsChannelsGet"></a>
# **controlsChannelsGet**
> List controlsChannelsGet(name)

Retrieve a list of channels, optionally filtering by name

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **String**|  | [optional] [default to ]

### Return type

[**List**](../Models/Channel.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsChannelsIdGet"></a>
# **controlsChannelsIdGet**
> Channel controlsChannelsIdGet(id)

Retrieve a channel by unique identifier

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Channel ID | [default to null]

### Return type

[**Channel**](../Models/Channel.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsChannelsIdPut"></a>
# **controlsChannelsIdPut**
> Channel controlsChannelsIdPut(id, Channel)

Update a channel

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Record identifier | [default to null]
 **Channel** | [**Channel**](../Models/Channel.md)|  |

### Return type

[**Channel**](../Models/Channel.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="controlsChannelsPost"></a>
# **controlsChannelsPost**
> Channel controlsChannelsPost(Channel)

Create a new channel

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Channel** | [**Channel**](../Models/Channel.md)|  |

### Return type

[**Channel**](../Models/Channel.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="controlsGroupControlsGet"></a>
# **controlsGroupControlsGet**
> List controlsGroupControlsGet(interchangeControlId)

Retrieve an interchange control&#39;s group control list

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **interchangeControlId** | **String**| Interchange control ID | [optional] [default to null]

### Return type

[**List**](../Models/GroupControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsGroupControlsIdGet"></a>
# **controlsGroupControlsIdGet**
> GroupControl controlsGroupControlsIdGet(id)

Retrieve a group control by identifier

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Record identifier | [default to null]

### Return type

[**GroupControl**](../Models/GroupControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsGroupControlsIdPut"></a>
# **controlsGroupControlsIdPut**
> GroupControl controlsGroupControlsIdPut(id, GroupControl)

Updates a group control

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Record identifier | [default to null]
 **GroupControl** | [**GroupControl**](../Models/GroupControl.md)|  |

### Return type

[**GroupControl**](../Models/GroupControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="controlsGroupControlsPost"></a>
# **controlsGroupControlsPost**
> GroupControl controlsGroupControlsPost(GroupControl)

Create a new group control record for an interchange control.

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **GroupControl** | [**GroupControl**](../Models/GroupControl.md)|  |

### Return type

[**GroupControl**](../Models/GroupControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="controlsInterchangeControlsGet"></a>
# **controlsInterchangeControlsGet**
> List controlsInterchangeControlsGet(channelId)

Retrieve a channel&#39;s interchange controls

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **channelId** | **String**| Channel ID | [optional] [default to null]

### Return type

[**List**](../Models/InterchangeControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsInterchangeControlsIdGet"></a>
# **controlsInterchangeControlsIdGet**
> InterchangeControl controlsInterchangeControlsIdGet(id)

Retrieve an interchange control by ID

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Interchange control ID | [default to null]

### Return type

[**InterchangeControl**](../Models/InterchangeControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsInterchangeControlsIdPut"></a>
# **controlsInterchangeControlsIdPut**
> InterchangeControl controlsInterchangeControlsIdPut(id, InterchangeControl)

Updates an interchange control

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Interchange control ID | [default to null]
 **InterchangeControl** | [**InterchangeControl**](../Models/InterchangeControl.md)|  |

### Return type

[**InterchangeControl**](../Models/InterchangeControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="controlsInterchangeControlsPost"></a>
# **controlsInterchangeControlsPost**
> InterchangeControl controlsInterchangeControlsPost(InterchangeControl)

Create a new interchange control record for a channel.

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **InterchangeControl** | [**InterchangeControl**](../Models/InterchangeControl.md)|  |

### Return type

[**InterchangeControl**](../Models/InterchangeControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="controlsTransactionControlsGet"></a>
# **controlsTransactionControlsGet**
> List controlsTransactionControlsGet(groupControlId, interchangeControlId)

Retrieve a transaction control list

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **groupControlId** | **String**|  | [optional] [default to null]
 **interchangeControlId** | **String**|  | [optional] [default to null]

### Return type

[**List**](../Models/TransactionControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsTransactionControlsIdGet"></a>
# **controlsTransactionControlsIdGet**
> TransactionControl controlsTransactionControlsIdGet(id)

Retrieve a transaction control by ID

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Record identifier | [default to null]

### Return type

[**TransactionControl**](../Models/TransactionControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="controlsTransactionControlsIdPut"></a>
# **controlsTransactionControlsIdPut**
> TransactionControl controlsTransactionControlsIdPut(id, TransactionControl)

Update a transaction control

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Record identifier | [default to null]
 **TransactionControl** | [**TransactionControl**](../Models/TransactionControl.md)|  |

### Return type

[**TransactionControl**](../Models/TransactionControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="controlsTransactionControlsPost"></a>
# **controlsTransactionControlsPost**
> TransactionControl controlsTransactionControlsPost(TransactionControl)

Create a new transaction control record for an interchange control.

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **TransactionControl** | [**TransactionControl**](../Models/TransactionControl.md)|  |

### Return type

[**TransactionControl**](../Models/TransactionControl.md)

### Authorization

[APIKeyScheme](../README.md#APIKeyScheme), [OAuth2Scheme](../README.md#OAuth2Scheme)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

