# Node.js-express

## node writing the request 


Registers functions to be called for different lifetime events of each async operation.

The callbacks init()/before()/after()/destroy() are called for the respective asynchronous event during a resource's lifetime.

All callbacks are optional. For example, if only resource cleanup needs to be tracked, then only the destroy callback needs to be passed. The specifics of all functions that can be passed to callbacks is in the Hook Callbacks section.
