# TransactionControl
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**agencyCode** | [**String**](string.md) | Agency code of the standards body that defines the schema of this record | [optional] [default to null]
**channelId** | [**String**](string.md) | Channel identifier. Required for new records, otherwise read-only | [optional] [default to null]
**createdAt** | [**Date**](DateTime.md) |  | [optional] [default to null]
**industryCode** | [**String**](string.md) | Industry identifier (implementation version) of the standard | [optional] [default to null]
**lastControlNumber** | [**Long**](long.md) | The previous control number used for outbound data. Defaults to &#x60;0&#x60; for new records. | [optional] [default to null]
**release** | [**String**](string.md) | Release (sub-version) of the standard | [optional] [default to null]
**title** | [**String**](string.md) |  | [default to null]
**updatedAt** | [**Date**](DateTime.md) |  | [optional] [default to null]
**uuid** | [**String**](string.md) |  | [optional] [default to null]
**version** | [**String**](string.md) | Version of the standard | [default to null]
**groupControlId** | [**String**](string.md) | Group control identifier. Required for new records directly tied to a group control record, not used otherwise | [optional] [default to null]
**interchangeControlId** | [**String**](string.md) | Interchange control identifier. Required for new records directly tied to an interchange control record, not used otherwise | [optional] [default to null]
**type** | [**String**](string.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

