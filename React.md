#1) Simple List component
The simple List component is a React functional component that render a list of items with the option to select one item at a time.
The component has two sub-components:- SingleListItem and List.

**The SingleListItem component is responsible for rendering a single item of the list, and it receives the following props:**
<li>index: A number representing the index of the item in the list.</li>
<li>isSelected: A boolean indicating whether the item is currently selected or not.</li>
<li>onClickHandler: A function that will be called when the item is clicked. It receives the index of the item as an argument.</li>
<li>text: A string representing the text to be displayed in the item.</li>


**The List component is responsible for rendering the entire list of items using the SingleListItem component. It receives only one prop:**

<li>items: An array of objects representing the items to be displayed. Each object should have a "text" property that represents the text to be displayed in the item.</li>











