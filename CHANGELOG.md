##1.1.3

* **Fixes Bugs:** 
 - margin positioning

##1.1.2

* **Fixes Bugs:** 
 - fixes: Service.Done() doesn't complete the progress if it wasn't trickling 
 - fixes: No Animation on IE, Edge 
    fixed by using css animation instead of angular animation (because it depends on the pollyfill web-animation-js)

##1.1.1

 - Use rxjs operators to imrpove code quality
 - Remove extra unnecessory subjects which been used in previous versions
 - Remove unnecessory style
 - Use single subject for update progress state
 - Move logic to the service and make components as dump as possible 
 - Improve animation
 - Support AOT

 **Breaking Changes:** 
 - Coloring animation is deprecated 
 - `[trickle]` input is deprecated 

##1.0.3

* **Improvement:** Uses `OnPush` change detection strategy on the outer component to improve performance.

##1.0.1

Stable release

* **New Feature:** Thicker size using the input `[thick]=true`.

* **Fixes Bug:** Adds transition for the spinner and the progress bar tail

*** 

##0.1.5

Initial release