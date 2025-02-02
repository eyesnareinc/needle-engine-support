[com.needle.engine - v2.39.0-pre](../README.md) / DragControls

# Class: DragControls

## Hierarchy

- [`Interactable`](Interactable.md)

  ↳ **`DragControls`**

## Implements

- `IPointerDownHandler`
- `IPointerUpHandler`
- `IPointerEnterHandler`
- `IPointerExitHandler`

## Table of contents

### Constructors

- [constructor](DragControls.md#constructor)

### Properties

- [canGrab](DragControls.md#cangrab)
- [gameObject](DragControls.md#gameobject)
- [guid](DragControls.md#guid)
- [sourceId](DragControls.md#sourceid)
- [transformSelf](DragControls.md#transformself)

### Accessors

- [activeAndEnabled](DragControls.md#activeandenabled)
- [context](DragControls.md#context)
- [destroyed](DragControls.md#destroyed)
- [enabled](DragControls.md#enabled)
- [forward](DragControls.md#forward)
- [hideFlags](DragControls.md#hideflags)
- [isComponent](DragControls.md#iscomponent)
- [layer](DragControls.md#layer)
- [name](DragControls.md#name)
- [scene](DragControls.md#scene)
- [static](DragControls.md#static)
- [tag](DragControls.md#tag)
- [worldEuler](DragControls.md#worldeuler)
- [worldPosition](DragControls.md#worldposition)
- [worldQuaternion](DragControls.md#worldquaternion)
- [worldRotation](DragControls.md#worldrotation)
- [HasAnySelected](DragControls.md#hasanyselected)

### Methods

- [addDragEventListener](DragControls.md#adddrageventlistener)
- [addEventListener](DragControls.md#addeventlistener)
- [awake](DragControls.md#awake)
- [destroy](DragControls.md#destroy)
- [dispatchEvent](DragControls.md#dispatchevent)
- [earlyUpdate](DragControls.md#earlyupdate)
- [lateUpdate](DragControls.md#lateupdate)
- [onAfterRender](DragControls.md#onafterrender)
- [onBeforeRender](DragControls.md#onbeforerender)
- [onCollisionEnter](DragControls.md#oncollisionenter)
- [onCollisionExit](DragControls.md#oncollisionexit)
- [onCollisionStay](DragControls.md#oncollisionstay)
- [onDestroy](DragControls.md#ondestroy)
- [onDisable](DragControls.md#ondisable)
- [onEnable](DragControls.md#onenable)
- [onPointerClick](DragControls.md#onpointerclick)
- [onPointerDown](DragControls.md#onpointerdown)
- [onPointerEnter](DragControls.md#onpointerenter)
- [onPointerExit](DragControls.md#onpointerexit)
- [onPointerUp](DragControls.md#onpointerup)
- [onTriggerEnter](DragControls.md#ontriggerenter)
- [onTriggerExit](DragControls.md#ontriggerexit)
- [onTriggerStay](DragControls.md#ontriggerstay)
- [onValidate](DragControls.md#onvalidate)
- [removeEventListener](DragControls.md#removeeventlistener)
- [resolveGuids](DragControls.md#resolveguids)
- [setWorldPosition](DragControls.md#setworldposition)
- [setWorldQuaternion](DragControls.md#setworldquaternion)
- [setWorldRotation](DragControls.md#setworldrotation)
- [start](DragControls.md#start)
- [startCoroutine](DragControls.md#startcoroutine)
- [stopCoroutine](DragControls.md#stopcoroutine)
- [update](DragControls.md#update)

## Constructors

### constructor

• **new DragControls**()

#### Overrides

Interactable.constructor

## Properties

### canGrab

• **canGrab**: `boolean` = `true`

#### Inherited from

[Interactable](Interactable.md).[canGrab](Interactable.md#cangrab)

___

### gameObject

• **gameObject**: [`GameObject`](GameObject.md)

#### Inherited from

[Interactable](Interactable.md).[gameObject](Interactable.md#gameobject)

___

### guid

• **guid**: `string` = `"invalid"`

#### Inherited from

[Interactable](Interactable.md).[guid](Interactable.md#guid)

___

### sourceId

• `Optional` **sourceId**: `string`

#### Inherited from

[Interactable](Interactable.md).[sourceId](Interactable.md#sourceid)

___

### transformSelf

• **transformSelf**: `boolean` = `true`

## Accessors

### activeAndEnabled

• `get` **activeAndEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Interactable.activeAndEnabled

___

### context

• `get` **context**(): `Context`

#### Returns

`Context`

#### Inherited from

Interactable.context

• `set` **context**(`context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `Context` |

#### Returns

`void`

#### Inherited from

Interactable.context

___

### destroyed

• `get` **destroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Interactable.destroyed

___

### enabled

• `get` **enabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Interactable.enabled

• `set` **enabled**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `boolean` |

#### Returns

`void`

#### Inherited from

Interactable.enabled

___

### forward

• `get` **forward**(): `Vector3`

#### Returns

`Vector3`

#### Inherited from

Interactable.forward

___

### hideFlags

• `get` **hideFlags**(): [`HideFlags`](../enums/HideFlags.md)

#### Returns

[`HideFlags`](../enums/HideFlags.md)

#### Inherited from

Interactable.hideFlags

___

### isComponent

• `get` **isComponent**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Interactable.isComponent

___

### layer

• `get` **layer**(): `number`

#### Returns

`number`

#### Inherited from

Interactable.layer

___

### name

• `get` **name**(): `string`

#### Returns

`string`

#### Inherited from

Interactable.name

• `set` **name**(`str`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`void`

#### Inherited from

Interactable.name

___

### scene

• `get` **scene**(): `Scene`

#### Returns

`Scene`

#### Inherited from

Interactable.scene

___

### static

• `get` **static**(): `any`

#### Returns

`any`

#### Inherited from

Interactable.static

___

### tag

• `get` **tag**(): `string`

#### Returns

`string`

#### Inherited from

Interactable.tag

• `set` **tag**(`str`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`void`

#### Inherited from

Interactable.tag

___

### worldEuler

• `get` **worldEuler**(): `Euler`

#### Returns

`Euler`

#### Inherited from

Interactable.worldEuler

• `set` **worldEuler**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `Euler` |

#### Returns

`void`

#### Inherited from

Interactable.worldEuler

___

### worldPosition

• `get` **worldPosition**(): `Vector3`

#### Returns

`Vector3`

#### Inherited from

Interactable.worldPosition

• `set` **worldPosition**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `Vector3` |

#### Returns

`void`

#### Inherited from

Interactable.worldPosition

___

### worldQuaternion

• `get` **worldQuaternion**(): `Quaternion`

#### Returns

`Quaternion`

#### Inherited from

Interactable.worldQuaternion

• `set` **worldQuaternion**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `Quaternion` |

#### Returns

`void`

#### Inherited from

Interactable.worldQuaternion

___

### worldRotation

• `get` **worldRotation**(): `Vector3`

#### Returns

`Vector3`

#### Inherited from

Interactable.worldRotation

• `set` **worldRotation**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `Vector3` |

#### Returns

`void`

#### Inherited from

Interactable.worldRotation

___

### HasAnySelected

• `Static` `get` **HasAnySelected**(): `boolean`

#### Returns

`boolean`

## Methods

### addDragEventListener

▸ **addDragEventListener**(`type`, `cb`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `DragEvents` |
| `cb` | (`ctrls`: [`DragControls`](DragControls.md), `args`: `SelectArgs`) => `void` \| `Function` |

#### Returns

`void`

___

### addEventListener

▸ **addEventListener**(`type`, `listener`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | `EventListener` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[addEventListener](Interactable.md#addeventlistener)

___

### awake

▸ **awake**(): `void`

called once when the component becomes active for the first time

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[awake](Interactable.md#awake)

___

### destroy

▸ **destroy**(): `void`

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[destroy](Interactable.md#destroy)

___

### dispatchEvent

▸ **dispatchEvent**(`evt`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | `Event` |

#### Returns

`boolean`

#### Inherited from

[Interactable](Interactable.md).[dispatchEvent](Interactable.md#dispatchevent)

___

### earlyUpdate

▸ `Optional` **earlyUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[earlyUpdate](Interactable.md#earlyupdate)

___

### lateUpdate

▸ `Optional` **lateUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[lateUpdate](Interactable.md#lateupdate)

___

### onAfterRender

▸ `Optional` **onAfterRender**(): `void`

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[onAfterRender](Interactable.md#onafterrender)

___

### onBeforeRender

▸ `Optional` **onBeforeRender**(`frame`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frame` | ``null`` \| `XRFrame` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[onBeforeRender](Interactable.md#onbeforerender)

___

### onCollisionEnter

▸ `Optional` **onCollisionEnter**(`col`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `col` | [`Collision`](Collision.md) |

#### Returns

`any`

#### Inherited from

[Interactable](Interactable.md).[onCollisionEnter](Interactable.md#oncollisionenter)

___

### onCollisionExit

▸ `Optional` **onCollisionExit**(`col`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `col` | [`Collision`](Collision.md) |

#### Returns

`any`

#### Inherited from

[Interactable](Interactable.md).[onCollisionExit](Interactable.md#oncollisionexit)

___

### onCollisionStay

▸ `Optional` **onCollisionStay**(`col`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `col` | [`Collision`](Collision.md) |

#### Returns

`any`

#### Inherited from

[Interactable](Interactable.md).[onCollisionStay](Interactable.md#oncollisionstay)

___

### onDestroy

▸ **onDestroy**(): `void`

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[onDestroy](Interactable.md#ondestroy)

___

### onDisable

▸ **onDisable**(): `void`

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[onDisable](Interactable.md#ondisable)

___

### onEnable

▸ **onEnable**(): `void`

called every time when the component gets enabled (this is invoked after awake and before start)

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[onEnable](Interactable.md#onenable)

___

### onPointerClick

▸ **onPointerClick**(`_args`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_args` | [`PointerEventData`](PointerEventData.md) |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[onPointerClick](Interactable.md#onpointerclick)

___

### onPointerDown

▸ **onPointerDown**(`args`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | [`PointerEventData`](PointerEventData.md) |

#### Returns

`void`

#### Implementation of

IPointerDownHandler.onPointerDown

___

### onPointerEnter

▸ **onPointerEnter**(`evt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`PointerEventData`](PointerEventData.md) |

#### Returns

`void`

#### Implementation of

IPointerEnterHandler.onPointerEnter

___

### onPointerExit

▸ **onPointerExit**(`evt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`PointerEventData`](PointerEventData.md) |

#### Returns

`void`

#### Implementation of

IPointerExitHandler.onPointerExit

___

### onPointerUp

▸ **onPointerUp**(`args`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | [`PointerEventData`](PointerEventData.md) |

#### Returns

`void`

#### Implementation of

IPointerUpHandler.onPointerUp

___

### onTriggerEnter

▸ `Optional` **onTriggerEnter**(`col`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `col` | `ICollider` |

#### Returns

`any`

#### Inherited from

[Interactable](Interactable.md).[onTriggerEnter](Interactable.md#ontriggerenter)

___

### onTriggerExit

▸ `Optional` **onTriggerExit**(`col`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `col` | `ICollider` |

#### Returns

`any`

#### Inherited from

[Interactable](Interactable.md).[onTriggerExit](Interactable.md#ontriggerexit)

___

### onTriggerStay

▸ `Optional` **onTriggerStay**(`col`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `col` | `ICollider` |

#### Returns

`any`

#### Inherited from

[Interactable](Interactable.md).[onTriggerStay](Interactable.md#ontriggerstay)

___

### onValidate

▸ `Optional` **onValidate**(`prop?`): `void`

called when you decorate fields with the @validate() decorator

#### Parameters

| Name | Type |
| :------ | :------ |
| `prop?` | `string` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[onValidate](Interactable.md#onvalidate)

___

### removeEventListener

▸ **removeEventListener**(`type`, `listener`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | `EventListener` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[removeEventListener](Interactable.md#removeeventlistener)

___

### resolveGuids

▸ `Optional` **resolveGuids**(`guidsMap`): `void`

called on a component with a map of old to new guids (e.g. when instantiate generated new guids and e.g. timeline track bindings needs to remape them)

#### Parameters

| Name | Type |
| :------ | :------ |
| `guidsMap` | `GuidsMap` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[resolveGuids](Interactable.md#resolveguids)

___

### setWorldPosition

▸ **setWorldPosition**(`x`, `y`, `z`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |
| `z` | `number` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[setWorldPosition](Interactable.md#setworldposition)

___

### setWorldQuaternion

▸ **setWorldQuaternion**(`x`, `y`, `z`, `w`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |
| `z` | `number` |
| `w` | `number` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[setWorldQuaternion](Interactable.md#setworldquaternion)

___

### setWorldRotation

▸ **setWorldRotation**(`x`, `y`, `z`, `degrees?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `x` | `number` | `undefined` |
| `y` | `number` | `undefined` |
| `z` | `number` | `undefined` |
| `degrees` | `boolean` | `true` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[setWorldRotation](Interactable.md#setworldrotation)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Overrides

[Interactable](Interactable.md).[start](Interactable.md#start)

___

### startCoroutine

▸ **startCoroutine**(`routine`, `evt?`): `Generator`<`unknown`, `any`, `unknown`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `routine` | `Generator`<`unknown`, `any`, `unknown`\> | `undefined` |
| `evt` | [`FrameEvent`](../enums/FrameEvent.md) | `FrameEvent.Update` |

#### Returns

`Generator`<`unknown`, `any`, `unknown`\>

#### Inherited from

[Interactable](Interactable.md).[startCoroutine](Interactable.md#startcoroutine)

___

### stopCoroutine

▸ **stopCoroutine**(`routine`, `evt?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `routine` | `Generator`<`unknown`, `any`, `unknown`\> | `undefined` |
| `evt` | [`FrameEvent`](../enums/FrameEvent.md) | `FrameEvent.Update` |

#### Returns

`void`

#### Inherited from

[Interactable](Interactable.md).[stopCoroutine](Interactable.md#stopcoroutine)

___

### update

▸ **update**(): `void`

#### Returns

`void`

#### Overrides

[Interactable](Interactable.md).[update](Interactable.md#update)
