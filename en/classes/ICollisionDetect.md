## `ICollisionDetect` Class



Module: [cc.primitive](../modules/cc.primitive.md)
Parent Module: [cc](../modules/cc.md)


Collision detect



### Index



##### Methods

  - [`raycastClosest`](#raycastclosest) Ray cast, and return information of the closest hit.
  - [`raycast`](#raycast) Ray cast against all bodies.



### Details




<!-- Method Block -->
#### Methods


##### raycastClosest

Ray cast, and return information of the closest hit.

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">boolean</a> 
| Defined in | [cocos2d/core/3d/physics/spec/i-physics-world.ts:59](https://github.com/cocos-creator/engine/blob/d0482bb5bc3819110e43cdd03a3459bd80914b74/cocos2d/core/3d/physics/spec/i-physics-world.ts#L59) |

###### Parameters
- `worldRay` Ray 
- `options` <a href="../classes/IRaycastOptions.html" class="crosslink">IRaycastOptions</a> 
- `out` <a href="../classes/PhysicsRayResult.html" class="crosslink">PhysicsRayResult</a> 


##### raycast

Ray cast against all bodies. The provided callback will be executed for each hit with a RaycastResult as single argument.

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">boolean</a> 
| Defined in | [cocos2d/core/3d/physics/spec/i-physics-world.ts:69](https://github.com/cocos-creator/engine/blob/d0482bb5bc3819110e43cdd03a3459bd80914b74/cocos2d/core/3d/physics/spec/i-physics-world.ts#L69) |

###### Parameters
- `worldRay` Ray 
- `options` <a href="../classes/IRaycastOptions.html" class="crosslink">IRaycastOptions</a> 
- `pool` RecyclePool 
- `resultes` <a href="../classes/PhysicsRayResult.html" class="crosslink">PhysicsRayResult[]</a> 


