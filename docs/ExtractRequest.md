# ExtractRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pages** | [**[]PageInput**](PageInput.md) | Array of pages to extract content from. Must contain 1-10 URLs. Each URL must be a valid HTTPS URL.  | 
**Timeout** | Pointer to **float32** | Optional timeout in seconds for the extraction operation | [optional] 
**Format** | Pointer to **string** | **(EXPERIMENTAL)** Format to serialize the API response as. The exact contents and structure of markdown output is still being worked on - please send your feedback! | [optional] [default to "json"]

## Methods

### NewExtractRequest

`func NewExtractRequest(pages []PageInput, ) *ExtractRequest`

NewExtractRequest instantiates a new ExtractRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtractRequestWithDefaults

`func NewExtractRequestWithDefaults() *ExtractRequest`

NewExtractRequestWithDefaults instantiates a new ExtractRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPages

`func (o *ExtractRequest) GetPages() []PageInput`

GetPages returns the Pages field if non-nil, zero value otherwise.

### GetPagesOk

`func (o *ExtractRequest) GetPagesOk() (*[]PageInput, bool)`

GetPagesOk returns a tuple with the Pages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPages

`func (o *ExtractRequest) SetPages(v []PageInput)`

SetPages sets Pages field to given value.


### GetTimeout

`func (o *ExtractRequest) GetTimeout() float32`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *ExtractRequest) GetTimeoutOk() (*float32, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *ExtractRequest) SetTimeout(v float32)`

SetTimeout sets Timeout field to given value.

### HasTimeout

`func (o *ExtractRequest) HasTimeout() bool`

HasTimeout returns a boolean if a field has been set.

### GetFormat

`func (o *ExtractRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *ExtractRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *ExtractRequest) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *ExtractRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


