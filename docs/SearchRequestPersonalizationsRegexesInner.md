# SearchRequestPersonalizationsRegexesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Regex** | Pointer to **string** | The regex pattern to match. | [optional] 
**Replacement** | Pointer to **string** | The replacement string to apply when the pattern matches. Will preserve paths and query parameters if not overwritten. You can refer to capture groups with \&quot;$1\&quot;, \&quot;$2\&quot;, etc. | [optional] 

## Methods

### NewSearchRequestPersonalizationsRegexesInner

`func NewSearchRequestPersonalizationsRegexesInner() *SearchRequestPersonalizationsRegexesInner`

NewSearchRequestPersonalizationsRegexesInner instantiates a new SearchRequestPersonalizationsRegexesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestPersonalizationsRegexesInnerWithDefaults

`func NewSearchRequestPersonalizationsRegexesInnerWithDefaults() *SearchRequestPersonalizationsRegexesInner`

NewSearchRequestPersonalizationsRegexesInnerWithDefaults instantiates a new SearchRequestPersonalizationsRegexesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegex

`func (o *SearchRequestPersonalizationsRegexesInner) GetRegex() string`

GetRegex returns the Regex field if non-nil, zero value otherwise.

### GetRegexOk

`func (o *SearchRequestPersonalizationsRegexesInner) GetRegexOk() (*string, bool)`

GetRegexOk returns a tuple with the Regex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegex

`func (o *SearchRequestPersonalizationsRegexesInner) SetRegex(v string)`

SetRegex sets Regex field to given value.

### HasRegex

`func (o *SearchRequestPersonalizationsRegexesInner) HasRegex() bool`

HasRegex returns a boolean if a field has been set.

### GetReplacement

`func (o *SearchRequestPersonalizationsRegexesInner) GetReplacement() string`

GetReplacement returns the Replacement field if non-nil, zero value otherwise.

### GetReplacementOk

`func (o *SearchRequestPersonalizationsRegexesInner) GetReplacementOk() (*string, bool)`

GetReplacementOk returns a tuple with the Replacement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacement

`func (o *SearchRequestPersonalizationsRegexesInner) SetReplacement(v string)`

SetReplacement sets Replacement field to given value.

### HasReplacement

`func (o *SearchRequestPersonalizationsRegexesInner) HasReplacement() bool`

HasReplacement returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


