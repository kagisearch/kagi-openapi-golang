# SearchRequestPersonalizationsDomainsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** | Domain pattern to personalize (e.g., \&quot;example.com\&quot;). Can also be a tld suffix like \&quot;.co.uk\&quot;. | 
**Kind** | **string** | Handling mode for this domain pattern | 

## Methods

### NewSearchRequestPersonalizationsDomainsInner

`func NewSearchRequestPersonalizationsDomainsInner(domain string, kind string, ) *SearchRequestPersonalizationsDomainsInner`

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


### GetKind

`func (o *SearchRequestPersonalizationsDomainsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *SearchRequestPersonalizationsDomainsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *SearchRequestPersonalizationsDomainsInner) SetKind(v string)`

SetKind sets Kind field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


