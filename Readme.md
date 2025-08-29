1.Answere to the quwstion hare`s:
    The difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAl,


        getElementById → single element by id.

        getElementsByClassName → live list by class.

        querySelector → first element by any CSS selector.

        querySelectorAll → all elements by any CSS selector, static list.



2.Answere to the quwstion hare`s:
    create and insert a new element into the DOM,
     
   #Create the element into the DOM:
            Use document.createElement() to create any HTML element.
            example: 
                let newDiv = document.createElement("div");
                newDiv.textContent = "Hello World";
    #Insert the element into the DOM:
            To append it at the end of a parent element:
            example:
                document.body.appendChild(newElement);
            Insert as the first child of a parent:
            example:
                parentElement.prepend(newElement);
                
3.Answere to the quwstion hare`s:
    #Event Bubbling,
            Event Bubbling is a JavaScript event mechanism where an event starts from the innermost element (child) and then propagates up through its parent elements sequentially.

    #Event Bubbling is works,
            When an event occurs on a child element  it first triggers on that element.
            Then the event “bubbles up” to its parent, grandparent, and eventually to the document element.
            This means the same event can also trigger listeners on parent elements if they exist.

4.Answere to the quwstion hare`s:
    #Event Delegation,
           Event Delegation is a technique in JavaScript where you attach a single event listener to a parent element instead of multiple child elements. The parent listens for events that bubble up from its children and can handle them based on the event target.
    #it is useful because,
            Reduces memory usage by avoiding multiple event listeners
            Works even for elements added to the DOM later, without adding new listeners.
            Easier to maintain than adding/removing listeners for each child.


5.Answere to the quwstion hare`s:
   The difference between preventDefault() and stopPropagation() methods,
       preventDefault()
            Stops the default action of an element from happening.
       stopPropagation()
            Stops the event from bubbling up or capturing down the DOM tree