# GroupControl
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
**interchangeControlId** | [**String**](string.md) | Interchange control identifier. Required for new records, otherwise read-only | [optional] [default to null]
**localId** | [**String**](string.md) | Used for the sender on output interchanges and the receiver on inbound groups | [default to null]
**localIdType** | [**String**](string.md) | Used for the sender on output interchanges and the receiver on inbound groups. Not used for X12 | [optional] [default to null]
**remoteId** | [**String**](string.md) | Used for the receiver on output interchanges and the sender on inbound groups | [default to null]
**remoteIdType** | [**String**](string.md) | Used for the receiver on output interchanges and the sender on inbound groups. Not used for X12 | [optional] [default to null]
**type** | [**String**](string.md) | Functional/message group type code | [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

