[@iabtcf/core - API Documentation](../README.md) > [TCModelError](../classes/_iabtcf_core___api_documentation.tcmodelerror.md)

# Class: TCModelError

class for decoding errors

*__extends__*: {Error}

## Hierarchy

 `Error`

**↳ TCModelError**

## Index

### Constructors

* [constructor](_iabtcf_core___api_documentation.tcmodelerror.md#constructor)

### Properties

* [message](_iabtcf_core___api_documentation.tcmodelerror.md#message)
* [name](_iabtcf_core___api_documentation.tcmodelerror.md#name)
* [stack](_iabtcf_core___api_documentation.tcmodelerror.md#stack)
* [Error](_iabtcf_core___api_documentation.tcmodelerror.md#error)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new TCModelError**(fieldName: *`string`*, passedValue: *`any`*, msg?: *`string`*): [TCModelError](_iabtcf_core___api_documentation.tcmodelerror.md)

*Defined in [src/errors/TCModelError.ts:6](https://github.com/chrispaterson/iabtcf/blob/883c677/modules/core/src/errors/TCModelError.ts#L6)*

constructor - constructs an TCModelError

**Parameters:**

| Name | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| fieldName | `string` | - |  the errored field |
| passedValue | `any` | - |  what was passed |
| `Default value` msg | `string` | &quot;&quot; |

**Returns:** [TCModelError](_iabtcf_core___api_documentation.tcmodelerror.md)

___

## Properties

<a id="message"></a>

###  message

**● message**: *`string`*

*Inherited from Error.message*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:974*

___
<a id="name"></a>

###  name

**● name**: *`string`*

*Inherited from Error.name*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:973*

___
<a id="stack"></a>

### `<Optional>` stack

**● stack**: *`undefined` \| `string`*

*Inherited from Error.stack*

*Overrides Error.stack*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:975*

___
<a id="error"></a>

### `<Static>` Error

**● Error**: *`ErrorConstructor`*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:984*

___
