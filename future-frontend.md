# Future of front end development

## Ideas in blog
* Threading
	* How threading will play a role in improving perceived performance 
* File sizes
	* How micro modules will play a role in optimizing for smaller overall bundles

## Threading
Web Workers provide a means of running scripts inside a new thread isolated from the Main/UI Thread, Allowing you to reduce overhead on the UI Thread. 
* TODO; Clean this up & Make it longer.

### Main/UI Thread
The Main/UI Thread is where you have access to all the goodies (In the browser, this would be DOM, Browser/Window etc), This is where you should be doing Events (click, form submission etc) & DOM Manipulation (like `element.innerText = 'hello'`).
* TODO; Clean this up & Make it longer.

### Background Thread
This is the thread you'd call to run logic that would take longer than a frame (EG. Asynchronous request to a server) & would also take longer to run than instantiating the thread itself (so a new thread just to compare strings would be a waste of resources)

* Todo; Make this longer.

### Utilizing Threads efficiently
* TODO;
  * Write how to utilize them efficiently
