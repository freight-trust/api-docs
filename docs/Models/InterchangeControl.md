# InterchangeControl
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
**componentSeparator** | [**String**](string.md) | Component element separator to be used for outbound interchanges. Default value is dialect specific (EDIFACT/X12) if not specified. | [optional] [default to null]
**decimalMark** | [**String**](string.md) | Decimal character to be used for outbound interchanges. Not supported for X12 | [optional] [default to null]
**elementSeparator** | [**String**](string.md) | Element separator to be used for outbound interchanges. Default value is dialect specific (EDIFACT/X12) if not specified. | [optional] [default to null]
**localId** | [**String**](string.md) | Used for the sender on output interchanges and the receiver on inbound interchanges | [default to null]
**localIdType** | [**String**](string.md) | Used for the sender on output interchanges and the receiver on inbound interchanges. Optional for EDIFACT, required for X12 | [optional] [default to null]
**releaseCharacter** | [**String**](string.md) | Release character to be used for outbound interchanges. Default value is dialect specific (EDIFACT/X12) if not specified. | [optional] [default to null]
**remoteId** | [**String**](string.md) | Used for the receiver on output interchanges and the sender on inbound interchanges | [default to null]
**remoteIdType** | [**String**](string.md) | Used for the receiver on output interchanges and the sender on inbound interchanges. Optional for EDIFACT, required for X12 | [optional] [default to null]
**repetitionSeparator** | [**String**](string.md) | Repetition separator to be used for outbound interchanges. Default value is dialect specific (EDIFACT/X12) if not specified. | [optional] [default to null]
**segmentTerminator** | [**String**](string.md) | Segment terminator to be used for outbound interchanges. Default value is dialect specific (EDIFACT/X12) if not specified. | [optional] [default to null]
**standard** | [**String**](string.md) | EDI standard | [default to null]
**testIndicator** | [**String**](string.md) | Test indicator to be used for outbound interchanges. Value is dialect specific (EDIFACT/X12). For example, X12 uses &#x60;P&#x60; and &#x60;T&#x60;, whereas EDIFACT uses &#x60;1&#x60; through &#x60;5&#x60;. | [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

