[@redhat-cloud-services/vulnerabilities-client](../README.md) › [Globals](../globals.md) › [MetaVulnerabilitiesOut](metavulnerabilitiesout.md)

# Interface: MetaVulnerabilitiesOut

**`export`** 

**`interface`** MetaVulnerabilitiesOut

## Hierarchy

* [Meta](meta.md)

  ↳ **MetaVulnerabilitiesOut**

## Index

### Properties

* [business_risk_id](metavulnerabilitiesout.md#business_risk_id)
* [cvss_from](metavulnerabilitiesout.md#cvss_from)
* [cvss_to](metavulnerabilitiesout.md#cvss_to)
* [data_format](metavulnerabilitiesout.md#data_format)
* [filter](metavulnerabilitiesout.md#filter)
* [impact](metavulnerabilitiesout.md#impact)
* [limit](metavulnerabilitiesout.md#limit)
* [offset](metavulnerabilitiesout.md#offset)
* [page](metavulnerabilitiesout.md#page)
* [page_size](metavulnerabilitiesout.md#page_size)
* [pages](metavulnerabilitiesout.md#pages)
* [public_from](metavulnerabilitiesout.md#public_from)
* [public_to](metavulnerabilitiesout.md#public_to)
* [show_all](metavulnerabilitiesout.md#show_all)
* [sort](metavulnerabilitiesout.md#sort)
* [total_items](metavulnerabilitiesout.md#total_items)

## Properties

###  business_risk_id

• **business_risk_id**: *string | null*

*Defined in [packages/vulnerabilities/api.ts:893](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L893)*

Filter based on business risk IDs.

**`memberof`** MetaVulnerabilitiesOut

___

###  cvss_from

• **cvss_from**: *number | null*

*Defined in [packages/vulnerabilities/api.ts:899](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L899)*

Filter based on cvss score, starting from the value.

**`memberof`** MetaVulnerabilitiesOut

___

###  cvss_to

• **cvss_to**: *number | null*

*Defined in [packages/vulnerabilities/api.ts:905](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L905)*

Filter based on cvss score, up to the value.

**`memberof`** MetaVulnerabilitiesOut

___

###  data_format

• **data_format**: *string*

*Inherited from [Meta](meta.md).[data_format](meta.md#data_format)*

*Defined in [packages/vulnerabilities/api.ts:704](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L704)*

Format of the output data, either JSON (default) or CSV.

**`memberof`** Meta

___

###  filter

• **filter**: *string | null*

*Inherited from [Meta](meta.md).[filter](meta.md#filter)*

*Defined in [packages/vulnerabilities/api.ts:656](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L656)*

Full text filter

**`memberof`** Meta

___

###  impact

• **impact**: *string | null*

*Defined in [packages/vulnerabilities/api.ts:929](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L929)*

Filter based on impact IDs.

**`memberof`** MetaVulnerabilitiesOut

___

###  limit

• **limit**: *number*

*Inherited from [Meta](meta.md).[limit](meta.md#limit)*

*Defined in [packages/vulnerabilities/api.ts:662](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L662)*

Maximum number of paginated results.

**`memberof`** Meta

___

###  offset

• **offset**: *number*

*Inherited from [Meta](meta.md).[offset](meta.md#offset)*

*Defined in [packages/vulnerabilities/api.ts:668](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L668)*

First record of paginated response.

**`memberof`** Meta

___

###  page

• **page**: *number*

*Inherited from [Meta](meta.md).[page](meta.md#page)*

*Defined in [packages/vulnerabilities/api.ts:674](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L674)*

Page number of paginated response.

**`memberof`** Meta

___

###  page_size

• **page_size**: *number*

*Inherited from [Meta](meta.md).[page_size](meta.md#page_size)*

*Defined in [packages/vulnerabilities/api.ts:680](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L680)*

Number of records per page of paginated response.

**`memberof`** Meta

___

###  pages

• **pages**: *number*

*Inherited from [Meta](meta.md).[pages](meta.md#pages)*

*Defined in [packages/vulnerabilities/api.ts:686](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L686)*

Total number of pages of paginated response.

**`memberof`** Meta

___

###  public_from

• **public_from**: *string | null*

*Defined in [packages/vulnerabilities/api.ts:917](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L917)*

Filter CVEs based on their published date, starting from the date.

**`memberof`** MetaVulnerabilitiesOut

___

###  public_to

• **public_to**: *string | null*

*Defined in [packages/vulnerabilities/api.ts:923](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L923)*

Filter CVEs based on their published date, up to the date.

**`memberof`** MetaVulnerabilitiesOut

___

###  show_all

• **show_all**: *boolean | null*

*Defined in [packages/vulnerabilities/api.ts:911](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L911)*

Show all known vulnerabilities, regardless of number of affected systems.

**`memberof`** MetaVulnerabilitiesOut

___

###  sort

• **sort**: *string | null*

*Inherited from [Meta](meta.md).[sort](meta.md#sort)*

*Defined in [packages/vulnerabilities/api.ts:692](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L692)*

Sorting filter.

**`memberof`** Meta

___

###  total_items

• **total_items**: *number*

*Inherited from [Meta](meta.md).[total_items](meta.md#total_items)*

*Defined in [packages/vulnerabilities/api.ts:698](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L698)*

Total number of records.

**`memberof`** Meta
