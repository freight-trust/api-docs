# AcknowledgementJSONInterchange
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**agencyCode** | [**String**](string.md) |  | [optional] [default to null]
**controlReference** | [**String**](string.md) |  | [optional] [default to null]
**errors** | [**List**](AcknowledgementJSONSegmentError.md) |  | [optional] [default to null]
**industryCode** | [**String**](string.md) |  | [optional] [default to null]
**release** | [**String**](string.md) |  | [optional] [default to null]
**version** | [**String**](string.md) |  | [optional] [default to null]
**groups** | [**List**](AcknowledgementJSONGroup.md) | Present only when the submitted interchange contains functional groups | [optional] [default to null]
**receiver** | [**AcknowledgementJSONAddressee**](AcknowledgementJSONAddressee.md) |  | [optional] [default to null]
**sender** | [**AcknowledgementJSONAddressee**](AcknowledgementJSONAddressee.md) |  | [optional] [default to null]
**transactions** | [**List**](AcknowledgementJSONTransaction.md) | Present only when the submitted interchange contains transactions directly within the interchange | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

