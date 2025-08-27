1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Answer:
getElementById selects a single element by its unique id.
getElementsByClassName returns a live collection of all elements with a specific class name.
querySelector selects the first element that matches a css selector.
querySelectorAll returns a static list of all elements that match a css selector.

2.How do you create and insert a new element into the DOM?
Create a new element using document.createElement(), set its properties or attributes,and then insert it into the dom using methods like appendChild, append, prepend, or insertBefore.

3. What is Event Bubbling and how does it work?
Event bubbling is the process where an event starts from the target element and then propagates upward through its parent elements until it reaches the root of the DOM tree.

4. What is Event Delegation in JavaScript? Why is it useful?
Event delegation is a technique where a single event listener is added to a parent element to manage events on its child elements. It is useful because it improves performance, reduces the number of event listeners, and works well with dynamically created elements.

5. What is the difference between preventDefault() and stopPropagation()?
preventDefault() stops the browser’s default behavior for an event.
stopPropagation() stops the event from moving further through the event flow (bubbling or capturing).
