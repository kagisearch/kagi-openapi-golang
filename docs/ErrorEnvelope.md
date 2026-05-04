# ErrorEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Meta** | [**Meta**](Meta.md) |  | 
**Data** | Pointer to **[]interface{}** | Empty data array when error occurs | [optional] 
**Error** | [**[]ErrorDetail**](ErrorDetail.md) | Array of error detail objects describing what went wrong | 

## Methods

### NewErrorEnvelope

`func NewErrorEnvelope(meta Meta, error_ []ErrorDetail, ) *ErrorEnvelope`

NewErrorEnvelope instantiates a new ErrorEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorEnvelopeWithDefaults

`func NewErrorEnvelopeWithDefaults() *ErrorEnvelope`

NewErrorEnvelopeWithDefaults instantiates a new ErrorEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeta

`func (o *ErrorEnvelope) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ErrorEnvelope) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ErrorEnvelope) SetMeta(v Meta)`

SetMeta sets Meta field to given value.


### GetData

`func (o *ErrorEnvelope) GetData() []interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ErrorEnvelope) GetDataOk() (*[]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ErrorEnvelope) SetData(v []interface{})`

SetData sets Data field to given value.

### HasData

`func (o *ErrorEnvelope) HasData() bool`

HasData returns a boolean if a field has been set.

### SetDataNil

`func (o *ErrorEnvelope) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *ErrorEnvelope) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetError

`func (o *ErrorEnvelope) GetError() []ErrorDetail`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ErrorEnvelope) GetErrorOk() (*[]ErrorDetail, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ErrorEnvelope) SetError(v []ErrorDetail)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


