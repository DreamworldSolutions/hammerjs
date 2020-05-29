# hammerjs
## Overview
- This is a wraper module of hammerjs (https://www.npmjs.com/package/hammerjs) which just export globle varialbe `Hammer`.

## Use cases

```javascript
import Hammer from  "@dreamworld/hammerjs";

var hammerInstance = new Hammer(element);
hammerInstance.get('pinch').set({ enable: true});

hammerInstance.on('pinch', function(ev) {
    //Write you code based on event
});

```