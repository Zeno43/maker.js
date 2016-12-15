# Module MakerJs
Root module for Maker.js.Example: get a reference to Maker.js```var makerjs = require('makerjs');```

## Index

### Modules
* [angle](modules/makerjs.angle.md)
* [chain](modules/makerjs.chain.md)
* [exporter](modules/makerjs.exporter.md)
* [importer](modules/makerjs.importer.md)
* [kit](modules/makerjs.kit.md)
* [measure](modules/makerjs.measure.md)
* [model](modules/makerjs.model.md)
* [models](modules/makerjs.models.md)
* [path](modules/makerjs.path.md)
* [paths](modules/makerjs.paths.md)
* [point](modules/makerjs.point.md)
* [solvers](modules/makerjs.solvers.md)
* [units](modules/makerjs.units.md)

### Classes
* [Collector](classes/makerjs.collector.md)

### Interfaces
* [IBezierRange](interfaces/makerjs.ibezierrange.md)
* [IChain](interfaces/makerjs.ichain.md)
* [IChainCallback](interfaces/makerjs.ichaincallback.md)
* [IChainLink](interfaces/makerjs.ichainlink.md)
* [ICollection](interfaces/makerjs.icollection.md)
* [ICollectionKeyComparer](interfaces/makerjs.icollectionkeycomparer.md)
* [ICombineOptions](interfaces/makerjs.icombineoptions.md)
* [IFindChainsOptions](interfaces/makerjs.ifindchainsoptions.md)
* [IFindLoopsOptions](interfaces/makerjs.ifindloopsoptions.md)
* [IKit](interfaces/makerjs.ikit.md)
* [IMeasure](interfaces/makerjs.imeasure.md)
* [IMeasureMap](interfaces/makerjs.imeasuremap.md)
* [IMetaParameter](interfaces/makerjs.imetaparameter.md)
* [IModel](interfaces/makerjs.imodel.md)
* [IModelMap](interfaces/makerjs.imodelmap.md)
* [IModelPathCallback](interfaces/makerjs.imodelpathcallback.md)
* [IPath](interfaces/makerjs.ipath.md)
* [IPathArc](interfaces/makerjs.ipatharc.md)
* [IPathArcInBezierCurve](interfaces/makerjs.ipatharcinbeziercurve.md)
* [IPathBezierSeed](interfaces/makerjs.ipathbezierseed.md)
* [IPathCircle](interfaces/makerjs.ipathcircle.md)
* [IPathDirectional](interfaces/makerjs.ipathdirectional.md)
* [IPathFunctionMap](interfaces/makerjs.ipathfunctionmap.md)
* [IPathIntersection](interfaces/makerjs.ipathintersection.md)
* [IPathIntersectionBaseOptions](interfaces/makerjs.ipathintersectionbaseoptions.md)
* [IPathIntersectionOptions](interfaces/makerjs.ipathintersectionoptions.md)
* [IPathLine](interfaces/makerjs.ipathline.md)
* [IPathMap](interfaces/makerjs.ipathmap.md)
* [IPathOriginFunctionMap](interfaces/makerjs.ipathoriginfunctionmap.md)
* [IPoint](interfaces/makerjs.ipoint.md)
* [IPointMatchOptions](interfaces/makerjs.ipointmatchoptions.md)
* [IRefModelInModel](interfaces/makerjs.irefmodelinmodel.md)
* [IRefPathIdInModel](interfaces/makerjs.irefpathidinmodel.md)
* [IRouteOffset](interfaces/makerjs.irouteoffset.md)
* [ISimplifyOptions](interfaces/makerjs.isimplifyoptions.md)
* [ISlope](interfaces/makerjs.islope.md)
* [IWalkModel](interfaces/makerjs.iwalkmodel.md)
* [IWalkModelCallback](interfaces/makerjs.iwalkmodelcallback.md)
* [IWalkModelCancellableCallback](interfaces/makerjs.iwalkmodelcancellablecallback.md)
* [IWalkOptions](interfaces/makerjs.iwalkoptions.md)
* [IWalkPath](interfaces/makerjs.iwalkpath.md)
* [IWalkPathBooleanCallback](interfaces/makerjs.iwalkpathbooleancallback.md)
* [IWalkPathCallback](interfaces/makerjs.iwalkpathcallback.md)

### Variables
* [clone](index.md#clone)
* [environment](index.md#environment)
* [version](index.md#version)
* [x](index.md#x)

### Functions
* [cloneObject](index.md#cloneobject)
* [createRouteKey](index.md#createroutekey)
* [detectEnvironment](index.md#detectenvironment)
* [extendObject](index.md#extendobject)
* [hasNamedProperty](index.md#hasnamedproperty)
* [isFunction](index.md#isfunction)
* [isModel](index.md#ismodel)
* [isNumber](index.md#isnumber)
* [isObject](index.md#isobject)
* [isPath](index.md#ispath)
* [isPathArc](index.md#ispatharc)
* [isPathArcInBezierCurve](index.md#ispatharcinbeziercurve)
* [isPathCircle](index.md#ispathcircle)
* [isPathLine](index.md#ispathline)
* [isPoint](index.md#ispoint)
* [reflectName](index.md#reflectname)
* [round](index.md#round)

### Object literals
* [environmentTypes](index.md#environmenttypes)
* [pathType](index.md#pathtype)
* [unitType](index.md#unittype)

## Variables

### Private clone: any

* Defined in [core/maker.ts:108](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L108)


### environment: string
Current execution environment type, should be one of environmentTypes.
* Defined in [core/maker.ts:50](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L50)


### version: string
Version info
* Defined in [core/maker.ts:16](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L16)


### Private x: [IPath](interfaces/makerjs.ipath.md)

* Defined in [core/maker.ts:176](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L176)


## Functions

### cloneObject<T>(objectToClone: T): T
Clone an object.  
* Defined in [core/maker.ts:116](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L116)


#### Type parameters

* #### T

#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| objectToClone | T| The object to clone. |

#### Returns: T
A new clone of the original object.


### createRouteKey(route: string[]): string
Create a string representation of a route array.  
* Defined in [core/maker.ts:90](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L90)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| route | string[]| Array of strings which are segments of a route. |

#### Returns: string
String of the flattened array.


### Private detectEnvironment(): string
  
* Defined in [core/maker.ts:31](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L31)

#### Returns: string

### extendObject(target: Object, other: Object): Object
Copy the properties from one object to another object.Example:```makerjs.extendObject({ abc: 123 }, { xyz: 789 }); //returns { abc: 123, xyz: 789 }```  
* Defined in [core/maker.ts:132](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L132)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| target | Object| The object to extend. It will receive the new properties. |
| other | Object| An object containing properties to merge in. |

#### Returns: Object
The original object after merging.


### Private hasNamedProperty(p: [IPath](interfaces/makerjs.ipath.md), value: any): boolean
  
* Defined in [core/maker.ts:191](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L191)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| p | [IPath](interfaces/makerjs.ipath.md)|  |
| value | any|  |

#### Returns: boolean

### isFunction(value: any): boolean
Test to see if a variable is a function.  
* Defined in [core/maker.ts:149](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L149)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| value | any| The object to test. |

#### Returns: boolean
True if the object is a function type.


### isModel(item: any): boolean
Test to see if an object implements the required properties of a model.  
* Defined in [core/maker.ts:692](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L692)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| item | any|  |

#### Returns: boolean

### isNumber(value: any): boolean
Test to see if a variable is a number.  
* Defined in [core/maker.ts:159](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L159)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| value | any| The object to test. |

#### Returns: boolean
True if the object is a number type.


### isObject(value: any): boolean
Test to see if a variable is an object.  
* Defined in [core/maker.ts:169](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L169)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| value | any| The object to test. |

#### Returns: boolean
True if the object is an object type.


### isPath(item: any): boolean
Test to see if an object implements the required properties of a path.  
* Defined in [core/maker.ts:272](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L272)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| item | any| The item to test. |

#### Returns: boolean

### isPathArc(item: any): boolean
Test to see if an object implements the required properties of an arc.  
* Defined in [core/maker.ts:355](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L355)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| item | any| The item to test. |

#### Returns: boolean

### isPathArcInBezierCurve(item: any): boolean
Test to see if an object implements the required properties of an arc in a bezier curve.  
* Defined in [core/maker.ts:404](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L404)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| item | any| The item to test. |

#### Returns: boolean

### isPathCircle(item: any): boolean
Test to see if an object implements the required properties of a circle.  
* Defined in [core/maker.ts:324](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L324)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| item | any| The item to test. |

#### Returns: boolean

### isPathLine(item: any): boolean
Test to see if an object implements the required properties of a line.  
* Defined in [core/maker.ts:298](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L298)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| item | any| The item to test. |

#### Returns: boolean

### isPoint(item: any): boolean
Test to see if an object implements the required properties of a point.  
* Defined in [core/maker.ts:217](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L217)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| item | any| The item to test. |

#### Returns: boolean

### Private reflectName(value?: any): any
  
* Defined in [core/maker.ts:181](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L181)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| value? | any|  |

#### Returns: any

### round(n: number, accuracy = 1e-7: number): number
Numeric roundingExample: round to 3 decimal places```makerjs.round(3.14159, .001); //returns 3.142```  
* Defined in [core/maker.ts:79](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L79)


#### Parameters

| Name | Type | Description |
| ---- | ---- | ---- |
| n | number| The number to round off. |
| accuracy = 1e-7 | number| Optional exemplar of number of decimal places. |

#### Returns: number

## Object literals

### environmentTypes: object
Enumeration of environment types.
* Defined in [core/maker.ts:21](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L21)


### BrowserUI: string

* Defined in [core/maker.ts:22](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L22)


### NodeJs: string

* Defined in [core/maker.ts:23](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L23)


### Unknown: string

* Defined in [core/maker.ts:25](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L25)


### WebWorker: string

* Defined in [core/maker.ts:24](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L24)


### pathType: object
String-based enumeration of all paths types.Examples: use pathType instead of string literal when creating a circle.```var circle: IPathCircle = { type: pathType.Circle, origin: [0, 0], radius: 7 };   //typescriptvar circle = { type: pathType.Circle, origin: [0, 0], radius: 7 };   //javascript```
* Defined in [core/maker.ts:439](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L439)


### Arc: string

* Defined in [core/maker.ts:442](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L442)


### BezierSeed: string

* Defined in [core/maker.ts:443](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L443)


### Circle: string

* Defined in [core/maker.ts:441](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L441)


### Line: string

* Defined in [core/maker.ts:440](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L440)


### unitType: object
String-based enumeration of unit types: imperial, metric or otherwise.A model may specify the unit system it is using, if any. When importing a model, it may have different units.Unit conversion function is makerjs.units.conversionScale().Important: If you add to this, you must also add a corresponding conversion ratio in the unit.ts file!
* Defined in [core/maker.ts:60](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L60)


### Centimeter: string

* Defined in [core/maker.ts:61](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L61)


### Foot: string

* Defined in [core/maker.ts:62](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L62)


### Inch: string

* Defined in [core/maker.ts:63](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L63)


### Meter: string

* Defined in [core/maker.ts:64](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L64)


### Millimeter: string

* Defined in [core/maker.ts:65](https://github.com/Microsoft/maker.js/blob/gh-pages/src/core/maker.ts#L65)



Generated using [TypeDoc](http://typedoc.io)
