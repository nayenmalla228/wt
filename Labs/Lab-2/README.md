# OBJECTIVE:  
To implement flow and positioned layout in CSS

# THEORY:
- CSS Flow Layout:-
  Normal Flow, or Flow Layout, is the way that Block and Inline elements are displayed on a page before any changes are made to their layout. The flow is essentially a set of things that are all working together and know about each other in your layout.  
- CSS Position Layout:-
  It is a CSS layout technique used to position an element on a web page. It allows us to take an element from the normal flow layout and position the element wherever we want it to be.  
  The position property takes five values. They are:  
  1)Static:  
    It is the default position value for HTML elements and will not affect anything.  
  2)Relative:  
    Elements using the property position relative remains within the normal flow of the webpage. But unlike static, we can use the left, right, top, bottom, and z-index properties to position the element in the webpage.  
  3)Absolute:  
    The absolute value position the element by default relative to its closest ancestor/parent element. If a parent element has been given a position value then it will be positioned in that context.  
    It removes the element from the document’s normal flow and the other elements will act as if the element doesn’t exist. The left, top, bottom and right properties determine the final position of the element.  
  4)Fixed:  
    An element with position: fixed is positioned relative to the viewport. The element is removed from the normal flow of the document and placed on the viewport. The left, top, bottom and right properties determine the final position of the element.It is similar to the position absolute except they are always positioned relative to the element. They’re not affected by scrolling so it always stays in the same place even if the page is scrolled.  
  5)Sticky:  
    Very few people use position: sticky. It is a mix of relative and fixed, it acts like a relatively positioned element until a scroll point, and then it sticks like a fixed positioned element.  
# CONCLUSION:  
We learnt to implement flow and position layout in CSS.
