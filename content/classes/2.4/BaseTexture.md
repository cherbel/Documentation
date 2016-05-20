---
ID_PAGE: 25219
PG_TITLE: BaseTexture
PG_VERSION: 2.1
TAGS:
    - BaseTexture
---
## Description

class [BaseTexture](/classes/2.4/BaseTexture)

Create a new [BaseTexture](/classes/2.4/BaseTexture).
A tutorial about materials and textures can be found here

## Constructor

## new [BaseTexture](/classes/2.4/BaseTexture)(scene)

Create a new [BaseTexture](/classes/2.4/BaseTexture);
A tutorial about materials and textures can be found here : http://doc.babylonjs.com/tutorials/Materials

#### Parameters
 | Name | Type | Description
---|---|---|---
 | scene | [Scene](/classes/2.4/Scene) |    The scene which will contains the new base texture

## Members

### name : string

Name of the base texture.

### hasAlpha : boolean

True if the base texture has alpha ; False otherwise

By default : false

### getAlphaFromRGB : boolean

True if RGBA ; False otherwise

By default : false

### level : number

The render level

By default : 1

### coordinatesIndex : number

The coordinates index

By default : 0

### coordinatesMode : number

The coordinates mode

By default : Explicit_Mode

### wrapU : number

The texture repetition in U axis

### wrapV : number

The texture repetition in V axis

### anisotropicFilteringLevel : number

The level of the anisotropic filtering level

By default : 4

### isCube : boolean

True if the basetexture is a cube ; False otherwise

By default : false

### isRenderTarget : boolean

True if this is a render target ; False otherwise

By default : false

### animations : [Animation](/classes/2.4/Animation)[]

The animations of the base texture

### onDisposeObservable : [Observable](/classes/2.4/Observable)&lt;[BaseTexture](/classes/2.4/BaseTexture)&gt;

An event triggered when the texture is disposed.

@type {BABYLON.[Observable](/classes/2.4/Observable)}

### onDispose : () =&gt; void

Function to call on dispose

### delayLoadState : number

Delay to load

By default : no delay

### canRescale : boolean



## Methods

### toStringundefined &rarr; string


### getSceneundefined &rarr; [Scene](/classes/2.4/Scene)


### getTextureMatrixundefined &rarr; [Matrix](/classes/2.4/Matrix)


### getReflectionTextureMatrixundefined &rarr; [Matrix](/classes/2.4/Matrix)


### getInternalTextureundefined &rarr; WebGLTexture


### isReadyundefined &rarr; boolean


### getSizeundefined &rarr; ISize


### getBaseSizeundefined &rarr; ISize


### scaleundefined &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
undefined
### delayLoadundefined &rarr; void


### cloneundefined &rarr; [BaseTexture](/classes/2.4/BaseTexture)


### releaseInternalTextureundefined &rarr; void


### disposeundefined &rarr; void


### serializeundefined &rarr; any

