EventTarget error handling#
When a registered event listener throws (or returns a Promise that rejects), by default the error is treated as an uncaught exception on process.nextTick(). This means uncaught exceptions in EventTargets will terminate the Node.js process by default.

Throwing within an event listener will not stop the other registered handlers from being invoked.

The EventTarget does not implement any special default handling for 'error' type events like EventEmitter.

Currently errors are first forwarded to the process.on('error') event before reaching process.on('uncaughtException'). This behavior is deprecated and will change in a future release to align EventTarget with other Node.js APIs. Any code relying on the process.on('error') event should be aligned with the new behavior.

Class: Event#
History
The Event object is an adaptation of the Event Web API. Instances are created internally by Node.js.

event.bubbles#
Added in: v14.5.0
Type: <boolean> Always returns false.
This is not used in Node.js and is provided purely for completeness.

event.cancelBubble()#
Added in: v14.5.0
Alias for event.stopPropagation(). This is not used in Node.js and is provided purely for completeness.

event.cancelable#
Added in: v14.5.0
Type: <boolean> True if the event was created with the cancelable option.
event.composed#
Added in: v14.5.0
Type: <boolean> Always returns false.
This is not used in Node.js and is provided purely for completeness.

event.composedPath()#
Added in: v14.5.0
Returns an array containing the current EventTarget as the only entry or empty if the event is not being dispatched. This is not used in Node.js and is provided purely for completeness.

event.currentTarget#
Added in: v14.5.0
Type: <EventTarget> The EventTarget dispatching the event.
Alias for event.target.

event.defaultPrevented#
Added in: v14.5.0
Type: <boolean>
Is true if cancelable is true and event.preventDefault() has been called.

event.eventPhase#
Added in: v14.5.0
Type: <number> Returns 0 while an event is not being dispatched, 2 while it is being dispatched.
This is not used in Node.js and is provided purely for completeness.

event.isTrusted#
Added in: v14.5.0
Type: <boolean>
The <AbortSignal> "abort" event is emitted with isTrusted set to true. The value is false in all other cases.

event.preventDefault()#
Added in: v14.5.0
Sets the defaultPrevented property to true if cancelable is true.

event.returnValue#
Added in: v14.5.0
Type: <boolean> True if the event has not been canceled.
This is not used in Node.js and is provided purely for completeness.

event.srcElement#
Added in: v14.5.0
Type: <EventTarget> The EventTarget dispatching the event.
Alias for event.target.

event.stopImmediatePropagation()#
Added in: v14.5.0
Stops the invocation of event listeners after the current one completes.

event.stopPropagation()#
Added in: v14.5.0
This is not used in Node.js and is provided purely for completeness.

event.target#
Added in: v14.5.0
Type: <EventTarget> The EventTarget dispatching the event.
event.timeStamp#
Added in: v14.5.0
Type: <number>
The millisecond timestamp when the Event object was created.

event.type#
Added in: v14.5.0
Type: <string>
The event type identifier.
