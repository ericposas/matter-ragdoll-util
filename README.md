### To use:

- expects one argument, scale amount (0 through 1)
- relies on import of main matter.js physics engine
```
import Matter from 'matter-js'
import { createRagdoll } from 'matterjs-ragdoll'
```

- then, in your main program call..
```
createRagdoll([size int])
```

- createRagdoll(1) returns a Matter.Composite of the ragdoll
