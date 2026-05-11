# SearchRequestExtract

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | Pointer to **int32** | Number of search results to extract content from. Must be between 1 and 10. | [optional] 
**Timeout** | Pointer to **float32** | Timeout in seconds for extraction of each page. If omitted, uses the default timeout. This time budget is in addition to the allocated top-level search timeout, so that you can control both independently. | [optional] 

## Methods

### NewSearchRequestExtract

`func NewSearchRequestExtract() *SearchRequestExtract`

NewSearchRequestExtract instantiates a new SearchRequestExtract object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestExtractWithDefaults

`func NewSearchRequestExtractWithDefaults() *SearchRequestExtract`

NewSearchRequestExtractWithDefaults instantiates a new SearchRequestExtract object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *SearchRequestExtract) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *SearchRequestExtract) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *SearchRequestExtract) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *SearchRequestExtract) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetTimeout

`func (o *SearchRequestExtract) GetTimeout() float32`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *SearchRequestExtract) GetTimeoutOk() (*float32, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *SearchRequestExtract) SetTimeout(v float32)`

SetTimeout sets Timeout field to given value.

### HasTimeout

`func (o *SearchRequestExtract) HasTimeout() bool`

HasTimeout returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


