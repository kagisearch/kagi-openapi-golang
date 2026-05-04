# ErrorDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | Namespaced error code | 
**Url** | **string** | URL to error documentation | 
**Message** | Pointer to **NullableString** | Human-readable error message | [optional] 
**Location** | Pointer to **NullableString** | Field location where the error occurred | [optional] 

## Methods

### NewErrorDetail

`func NewErrorDetail(code string, url string, ) *ErrorDetail`

NewErrorDetail instantiates a new ErrorDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorDetailWithDefaults

`func NewErrorDetailWithDefaults() *ErrorDetail`

NewErrorDetailWithDefaults instantiates a new ErrorDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ErrorDetail) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ErrorDetail) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ErrorDetail) SetCode(v string)`

SetCode sets Code field to given value.


### GetUrl

`func (o *ErrorDetail) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ErrorDetail) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ErrorDetail) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetMessage

`func (o *ErrorDetail) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ErrorDetail) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ErrorDetail) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ErrorDetail) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *ErrorDetail) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *ErrorDetail) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetLocation

`func (o *ErrorDetail) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ErrorDetail) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ErrorDetail) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ErrorDetail) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *ErrorDetail) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *ErrorDetail) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


