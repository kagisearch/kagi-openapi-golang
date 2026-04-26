# SearchRequestPersonalizationsDomainsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | Pointer to **string** | The domain to personalize (e.g., \&quot;example.com\&quot;). | [optional] 
**Bias** | Pointer to **float32** | Bias value to apply to results from this domain. | [optional] 

## Methods

### NewSearchRequestPersonalizationsDomainsInner

`func NewSearchRequestPersonalizationsDomainsInner() *SearchRequestPersonalizationsDomainsInner`

NewSearchRequestPersonalizationsDomainsInner instantiates a new SearchRequestPersonalizationsDomainsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestPersonalizationsDomainsInnerWithDefaults

`func NewSearchRequestPersonalizationsDomainsInnerWithDefaults() *SearchRequestPersonalizationsDomainsInner`

NewSearchRequestPersonalizationsDomainsInnerWithDefaults instantiates a new SearchRequestPersonalizationsDomainsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *SearchRequestPersonalizationsDomainsInner) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *SearchRequestPersonalizationsDomainsInner) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *SearchRequestPersonalizationsDomainsInner) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *SearchRequestPersonalizationsDomainsInner) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetBias

`func (o *SearchRequestPersonalizationsDomainsInner) GetBias() float32`

GetBias returns the Bias field if non-nil, zero value otherwise.

### GetBiasOk

`func (o *SearchRequestPersonalizationsDomainsInner) GetBiasOk() (*float32, bool)`

GetBiasOk returns a tuple with the Bias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBias

`func (o *SearchRequestPersonalizationsDomainsInner) SetBias(v float32)`

SetBias sets Bias field to given value.

### HasBias

`func (o *SearchRequestPersonalizationsDomainsInner) HasBias() bool`

HasBias returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


