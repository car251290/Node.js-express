# Node.js-express

## node writing the request 


Registers functions to be called for different lifetime events of each async operation.

The callbacks init()/before()/after()/destroy() are called for the respective asynchronous event during a resource's lifetime.

All callbacks are optional. For example, if only resource cleanup needs to be tracked, then only the destroy callback needs to be passed. The specifics of all functions that can be passed to callbacks is in the Hook Callbacks section.


Terminology#

An asynchronous resource represents an object with an associated callback. This callback may be called multiple times, such as the 'connection' event in net.createServer(), or just a single time like in fs.open(). A resource can also be closed before the callback is called. AsyncHook does not explicitly distinguish between these different cases but will represent them as the abstract concept that is a resource.


Registers functions to be called for different lifetime events of each async operation.

The callbacks init()/before()/after()/destroy() are called for the respective asynchronous event during a resource's lifetime.

All callbacks are optional. For example, if only resource cleanup needs to be tracked, then only the destroy callback needs to be passed. The specifics of all functions that can be passed to callbacks is in the Hook Callbacks section.
