[@ai16z/eliza v0.1.6-alpha.4](../index.md) / Action

# Interface: Action

Represents an action the agent can perform

## Properties

### similes

> **similes**: `string`[]

Similar action descriptions

#### Defined in

[packages/core/src/types.ts:404](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L404)

***

### description

> **description**: `string`

Detailed description

#### Defined in

[packages/core/src/types.ts:407](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L407)

***

### examples

> **examples**: [`ActionExample`](ActionExample.md)[][]

Example usages

#### Defined in

[packages/core/src/types.ts:410](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L410)

***

### handler

> **handler**: [`Handler`](../type-aliases/Handler.md)

Handler function

#### Defined in

[packages/core/src/types.ts:413](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L413)

***

### name

> **name**: `string`

Action name

#### Defined in

[packages/core/src/types.ts:416](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L416)

***

### validate

> **validate**: [`Validator`](../type-aliases/Validator.md)

Validation function

#### Defined in

[packages/core/src/types.ts:419](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L419)
