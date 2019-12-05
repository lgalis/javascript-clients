[@redhat-cloud-services/insights-client](../README.md) > [ResolutionRiskApi](../classes/resolutionriskapi.md)

# Class: ResolutionRiskApi

ResolutionRiskApi - object-oriented interface

*__export__*: 

*__class__*: ResolutionRiskApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ ResolutionRiskApi**

## Index

### Constructors

* [constructor](resolutionriskapi.md#constructor)

### Properties

* [axios](resolutionriskapi.md#axios)
* [basePath](resolutionriskapi.md#basepath)
* [configuration](resolutionriskapi.md#configuration)

### Methods

* [resolutionRiskList](resolutionriskapi.md#resolutionrisklist)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new ResolutionRiskApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, axios?: *`AxiosInstance`*): [ResolutionRiskApi](resolutionriskapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [api.ts:49](https://github.com/karelhala/javascript-clients/blob/master/packages/insights/api.ts#L49)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` axios | `AxiosInstance` |  globalAxios |

**Returns:** [ResolutionRiskApi](resolutionriskapi.md)

___

## Properties

<a id="axios"></a>

### `<Protected>` axios

**● axios**: *`AxiosInstance`*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#axios)*

*Defined in [api.ts:51](https://github.com/karelhala/javascript-clients/blob/master/packages/insights/api.ts#L51)*

___
<a id="basepath"></a>

### `<Protected>` basePath

**● basePath**: *`string`*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#basepath)*

*Defined in [api.ts:51](https://github.com/karelhala/javascript-clients/blob/master/packages/insights/api.ts#L51)*

___
<a id="configuration"></a>

### `<Protected>` configuration

**● configuration**: *[Configuration](configuration.md) \| `undefined`*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#configuration)*

*Defined in [api.ts:49](https://github.com/karelhala/javascript-clients/blob/master/packages/insights/api.ts#L49)*

___

## Methods

<a id="resolutionrisklist"></a>

###  resolutionRiskList

▸ **resolutionRiskList**(options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:2419](https://github.com/karelhala/javascript-clients/blob/master/packages/insights/api.ts#L2419)*

List all total risk values.

*__throws__*: {RequiredError}

*__memberof__*: ResolutionRiskApi

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___
