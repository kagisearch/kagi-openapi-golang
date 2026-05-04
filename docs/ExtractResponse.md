# ExtractResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Meta** | [**Meta**](Meta.md) |  | 
**Data** | [**[]PageOutput**](PageOutput.md) | Array of extracted page content | 
**Errors** | Pointer to [**[]ErrorDetail**](ErrorDetail.md) | Optional array of errors that occurred during extraction | [optional] 

## Methods

### NewExtractResponse

`func NewExtractResponse(meta Meta, data []PageOutput, ) *ExtractResponse`

NewExtractResponse instantiates a new ExtractResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtractResponseWithDefaults

`func NewExtractResponseWithDefaults() *ExtractResponse`

NewExtractResponseWithDefaults instantiates a new ExtractResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeta

`func (o *ExtractResponse) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ExtractResponse) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ExtractResponse) SetMeta(v Meta)`

SetMeta sets Meta field to given value.


### GetData

`func (o *ExtractResponse) GetData() []PageOutput`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ExtractResponse) GetDataOk() (*[]PageOutput, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ExtractResponse) SetData(v []PageOutput)`

SetData sets Data field to given value.


### GetErrors

`func (o *ExtractResponse) GetErrors() []ErrorDetail`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ExtractResponse) GetErrorsOk() (*[]ErrorDetail, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ExtractResponse) SetErrors(v []ErrorDetail)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ExtractResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


