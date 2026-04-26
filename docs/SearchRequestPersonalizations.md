# SearchRequestPersonalizations

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domains** | Pointer to [**[]SearchRequestPersonalizationsDomainsInner**](SearchRequestPersonalizationsDomainsInner.md) | Domain-level personalization rules (maximum 1000 rules). Each rule can boost or lower the ranking of results from specific domains. | [optional] 
**Regexes** | Pointer to [**[]SearchRequestPersonalizationsRegexesInner**](SearchRequestPersonalizationsRegexesInner.md) | Regex-based personalization rules (maximum 1000 rules, max 1000 bytes per pattern). | [optional] 

## Methods

### NewSearchRequestPersonalizations

`func NewSearchRequestPersonalizations() *SearchRequestPersonalizations`

NewSearchRequestPersonalizations instantiates a new SearchRequestPersonalizations object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestPersonalizationsWithDefaults

`func NewSearchRequestPersonalizationsWithDefaults() *SearchRequestPersonalizations`

NewSearchRequestPersonalizationsWithDefaults instantiates a new SearchRequestPersonalizations object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomains

`func (o *SearchRequestPersonalizations) GetDomains() []SearchRequestPersonalizationsDomainsInner`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *SearchRequestPersonalizations) GetDomainsOk() (*[]SearchRequestPersonalizationsDomainsInner, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *SearchRequestPersonalizations) SetDomains(v []SearchRequestPersonalizationsDomainsInner)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *SearchRequestPersonalizations) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### GetRegexes

`func (o *SearchRequestPersonalizations) GetRegexes() []SearchRequestPersonalizationsRegexesInner`

GetRegexes returns the Regexes field if non-nil, zero value otherwise.

### GetRegexesOk

`func (o *SearchRequestPersonalizations) GetRegexesOk() (*[]SearchRequestPersonalizationsRegexesInner, bool)`

GetRegexesOk returns a tuple with the Regexes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegexes

`func (o *SearchRequestPersonalizations) SetRegexes(v []SearchRequestPersonalizationsRegexesInner)`

SetRegexes sets Regexes field to given value.

### HasRegexes

`func (o *SearchRequestPersonalizations) HasRegexes() bool`

HasRegexes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


