[avalanche](../README.md) › [src/utils](../modules/src_utils.md) › [OperationError](src_utils.operationerror.md)

# Class: OperationError

## Hierarchy

  ↳ [AvalancheError](src_utils.avalancheerror.md)

  ↳ **OperationError**

## Index

### Constructors

* [constructor](src_utils.operationerror.md#constructor)

### Properties

* [errorCode](src_utils.operationerror.md#errorcode)
* [message](src_utils.operationerror.md#message)
* [name](src_utils.operationerror.md#name)
* [stack](src_utils.operationerror.md#optional-stack)

### Methods

* [getCode](src_utils.operationerror.md#getcode)

## Constructors

###  constructor

\+ **new OperationError**(`m`: string): *[OperationError](src_utils.operationerror.md)*

*Overrides [AvalancheError](src_utils.avalancheerror.md).[constructor](src_utils.avalancheerror.md#constructor)*

*Defined in [src/utils/errors.ts:141](https://github.com/ava-labs/avalanchejs/blob/8c220c6/src/utils/errors.ts#L141)*

**Parameters:**

Name | Type |
------ | ------ |
`m` | string |

**Returns:** *[OperationError](src_utils.operationerror.md)*

## Properties

###  errorCode

• **errorCode**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[errorCode](src_utils.avalancheerror.md#errorcode)*

*Defined in [src/utils/errors.ts:45](https://github.com/ava-labs/avalanchejs/blob/8c220c6/src/utils/errors.ts#L45)*

___

###  message

• **message**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[message](src_utils.avalancheerror.md#message)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1023

___

###  name

• **name**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[name](src_utils.avalancheerror.md#name)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1022

___

### `Optional` stack

• **stack**? : *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[stack](src_utils.avalancheerror.md#optional-stack)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1024

## Methods

###  getCode

▸ **getCode**(): *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[getCode](src_utils.avalancheerror.md#getcode)*

*Defined in [src/utils/errors.ts:52](https://github.com/ava-labs/avalanchejs/blob/8c220c6/src/utils/errors.ts#L52)*

**Returns:** *string*
