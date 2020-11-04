# Documentation for EDI Management API

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://localhost*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AdministrationApi* | [**controlsChannelsGet**](Apis/AdministrationApi.md#controlschannelsget) | **GET** /controls/channels | Retrieve a list of channels, optionally filtering by name
*AdministrationApi* | [**controlsChannelsIdGet**](Apis/AdministrationApi.md#controlschannelsidget) | **GET** /controls/channels/{id} | Retrieve a channel by unique identifier
*AdministrationApi* | [**controlsChannelsIdPut**](Apis/AdministrationApi.md#controlschannelsidput) | **PUT** /controls/channels/{id} | Update a channel
*AdministrationApi* | [**controlsChannelsPost**](Apis/AdministrationApi.md#controlschannelspost) | **POST** /controls/channels | Create a new channel
*AdministrationApi* | [**controlsGroupControlsGet**](Apis/AdministrationApi.md#controlsgroupcontrolsget) | **GET** /controls/group-controls | Retrieve an interchange control's group control list
*AdministrationApi* | [**controlsGroupControlsIdGet**](Apis/AdministrationApi.md#controlsgroupcontrolsidget) | **GET** /controls/group-controls/{id} | Retrieve a group control by identifier
*AdministrationApi* | [**controlsGroupControlsIdPut**](Apis/AdministrationApi.md#controlsgroupcontrolsidput) | **PUT** /controls/group-controls/{id} | Updates a group control
*AdministrationApi* | [**controlsGroupControlsPost**](Apis/AdministrationApi.md#controlsgroupcontrolspost) | **POST** /controls/group-controls | Create a new group control record for an interchange control.
*AdministrationApi* | [**controlsInterchangeControlsGet**](Apis/AdministrationApi.md#controlsinterchangecontrolsget) | **GET** /controls/interchange-controls | Retrieve a channel's interchange controls
*AdministrationApi* | [**controlsInterchangeControlsIdGet**](Apis/AdministrationApi.md#controlsinterchangecontrolsidget) | **GET** /controls/interchange-controls/{id} | Retrieve an interchange control by ID
*AdministrationApi* | [**controlsInterchangeControlsIdPut**](Apis/AdministrationApi.md#controlsinterchangecontrolsidput) | **PUT** /controls/interchange-controls/{id} | Updates an interchange control
*AdministrationApi* | [**controlsInterchangeControlsPost**](Apis/AdministrationApi.md#controlsinterchangecontrolspost) | **POST** /controls/interchange-controls | Create a new interchange control record for a channel.
*AdministrationApi* | [**controlsTransactionControlsGet**](Apis/AdministrationApi.md#controlstransactioncontrolsget) | **GET** /controls/transaction-controls | Retrieve a transaction control list
*AdministrationApi* | [**controlsTransactionControlsIdGet**](Apis/AdministrationApi.md#controlstransactioncontrolsidget) | **GET** /controls/transaction-controls/{id} | Retrieve a transaction control by ID
*AdministrationApi* | [**controlsTransactionControlsIdPut**](Apis/AdministrationApi.md#controlstransactioncontrolsidput) | **PUT** /controls/transaction-controls/{id} | Update a transaction control
*AdministrationApi* | [**controlsTransactionControlsPost**](Apis/AdministrationApi.md#controlstransactioncontrolspost) | **POST** /controls/transaction-controls | Create a new transaction control record for an interchange control.
*ConfigurationApi* | [**configJsGet**](Apis/ConfigurationApi.md#configjsget) | **GET** /config.js | Retrieve JavaScript module for front end configuration
*HistoryApi* | [**historyGroupsGet**](Apis/HistoryApi.md#historygroupsget) | **GET** /history/groups | Retrieve a list of functional groups for a particular interchange
*HistoryApi* | [**historyGroupsIdGet**](Apis/HistoryApi.md#historygroupsidget) | **GET** /history/groups/{id} | Retrieve a functional group by identifier
*HistoryApi* | [**historyInterchangesGet**](Apis/HistoryApi.md#historyinterchangesget) | **GET** /history/interchanges | Retrieve a list of interchanges
*HistoryApi* | [**historyInterchangesIdGet**](Apis/HistoryApi.md#historyinterchangesidget) | **GET** /history/interchanges/{id} | Retrieve an interchange by identifier
*HistoryApi* | [**historyInterchangesInterchangeIdRelationshipsAcknowledgementGet**](Apis/HistoryApi.md#historyinterchangesinterchangeidrelationshipsacknowledgementget) | **GET** /history/interchanges/{interchangeId}/relationships/acknowledgement | Retrieve an interchange acknowledgement by identifier
*HistoryApi* | [**historyTransactionsGet**](Apis/HistoryApi.md#historytransactionsget) | **GET** /history/transactions | Retrieve a list of transactions for a particular interchange, group, or date/time range
*HistoryApi* | [**historyTransactionsIdGet**](Apis/HistoryApi.md#historytransactionsidget) | **GET** /history/transactions/{id} | Retrieve a transaction by identifier
*SchemaMaintenanceApi* | [**schemasControlGet**](Apis/SchemaMaintenanceApi.md#schemascontrolget) | **GET** /schemas/control | 
*SchemaMaintenanceApi* | [**schemasGet**](Apis/SchemaMaintenanceApi.md#schemasget) | **GET** /schemas | Retrieve a list of transaction schemas known to the system
*SchemaMaintenanceApi* | [**schemasPost**](Apis/SchemaMaintenanceApi.md#schemaspost) | **POST** /schemas | Create a new transaction schema to be used for EDI validation
*SchemaMaintenanceApi* | [**schemasStandardTypeVersionFileDelete**](Apis/SchemaMaintenanceApi.md#schemasstandardtypeversionfiledelete) | **DELETE** /schemas/{standard}/{type}/{version}/{file} | 
*SchemaMaintenanceApi* | [**schemasStandardTypeVersionFileGet**](Apis/SchemaMaintenanceApi.md#schemasstandardtypeversionfileget) | **GET** /schemas/{standard}/{type}/{version}/{file} | 
*SchemaMaintenanceApi* | [**schemasTransactionGet**](Apis/SchemaMaintenanceApi.md#schemastransactionget) | **GET** /schemas/transaction | 
*TransactionsApi* | [**transactionsInboundPost**](Apis/TransactionsApi.md#transactionsinboundpost) | **POST** /transactions/inbound | Submit an EDI interchange for validation and conversion (Persistent)
*TransactionsApi* | [**transactionsOutboundPost**](Apis/TransactionsApi.md#transactionsoutboundpost) | **POST** /transactions/outbound | Submit an XML format interchange for conversion to EDI (Persistent)
*TransactionsApi* | [**transactionsTranslatorPost**](Apis/TransactionsApi.md#transactionstranslatorpost) | **POST** /transactions/translator | Translate an EDI interchange (Persistent)
*TransactionsApi* | [**transactionsValidatorPost**](Apis/TransactionsApi.md#transactionsvalidatorpost) | **POST** /transactions/validator | Validate an EDI interchange (Persistent)


<a name="documentation-for-models"></a>
## Documentation for Models

 - [AcknowledgementJSON](./Models/AcknowledgementJSON.md)
 - [AcknowledgementJSONAddressee](./Models/AcknowledgementJSONAddressee.md)
 - [AcknowledgementJSONElementError](./Models/AcknowledgementJSONElementError.md)
 - [AcknowledgementJSONGroup](./Models/AcknowledgementJSONGroup.md)
 - [AcknowledgementJSONInterchange](./Models/AcknowledgementJSONInterchange.md)
 - [AcknowledgementJSONSegmentError](./Models/AcknowledgementJSONSegmentError.md)
 - [AcknowledgementJSONTransaction](./Models/AcknowledgementJSONTransaction.md)
 - [Channel](./Models/Channel.md)
 - [Group](./Models/Group.md)
 - [GroupControl](./Models/GroupControl.md)
 - [InlineObject](./Models/InlineObject.md)
 - [Interchange](./Models/Interchange.md)
 - [InterchangeControl](./Models/InterchangeControl.md)
 - [SyntaxError](./Models/SyntaxError.md)
 - [Transaction](./Models/Transaction.md)
 - [TransactionControl](./Models/TransactionControl.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="APIKeyScheme"></a>
### APIKeyScheme

- **Type**: API key
- **API key parameter name**: X-FT-API-Key
- **Location**: HTTP header

<a name="OAuth2Scheme"></a>
### OAuth2Scheme

- **Type**: OAuth
- **Flow**: application
- **Authorization URL**: 
- **Scopes**: N/A

