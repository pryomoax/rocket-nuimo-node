[Rocket Nuimo - v1.2.1](../README.md) / NuimoDeviceCommunicationError

# Class: NuimoDeviceCommunicationError

Class of error related to device communication errors with a known device

## Hierarchy

- [NuimoError](nuimoerror.md)

  ↳ **NuimoDeviceCommunicationError**

## Table of contents

### Constructors

- [constructor](nuimodevicecommunicationerror.md#constructor)

### Properties

- [code](nuimodevicecommunicationerror.md#code)
- [id](nuimodevicecommunicationerror.md#id)

## Constructors

### constructor

• **new NuimoDeviceCommunicationError**(`code`, `id`, `message?`)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `code` | [NuimoDeviceCommunicationErrorCode](../enums/nuimodevicecommunicationerrorcode.md) | connection error code |
| `id` | `string` | device ID for the connection error |
| `message?` | `string` | - |

#### Overrides

[NuimoError](nuimoerror.md).[constructor](nuimoerror.md#constructor)

## Properties

### code

• `Readonly` **code**: [NuimoDeviceCommunicationErrorCode](../enums/nuimodevicecommunicationerrorcode.md)

Device error code

___

### id

• `Readonly` **id**: `string`

Device identifier
