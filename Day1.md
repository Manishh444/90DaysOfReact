# Introduction to React.js

## The birth of React.js

<li> React is a JavaScript library for building User interfaces. It was developed by facebook.
<li> It just blew up in a short span of time is because :
  <ol><br>
    <li> **Don't touch DOM I'll(React) do it :** JavaScript manipulates the DOM everytime. Manipulating the DOM is an expensive operation it has two operations **repaint** and **reflow**. <br/>
          Repaint are those changes that modify the skin of the elements and not the layout. Examples include changing visibility etc. <br />
          Reform are those changes that require layout manipulation. So, manipulating DOM takes time and is sometimes slower. 
          <br />
          **What React did to slow this problem :** React came up with a nobel concept of being more Declarative (you just tells the compiler what needs to be done) approach rather than the older imperative approach (you specify a sequence of steps for the computer to follow). A great article about declarative and imperative programming language is: https://www.freecodecamp.org/news/imperative-vs-declarative-programming-difference/
          In an imperative paradigm you directly change individual components present at the DOM level.
          It becomes difficult to see relations between these components and for edge cases. React just asks for the state of the page and renders the page accordingly.
    <li> **Built the site like lego blocks :** React uses reusable components to build the UI. Components are nothing but small Javascript function we write and reuse them again and again.
      <li> **It has a unidirectional flow :** Suppose we have a web application it has a state. State is nothing but a JavaScript object. A component is also there it is nothing but a function. It is sometimes referred to as JSX. This will create a React library function which will contains the state and the component as the parameters. This will generate a virtual DOM  which will act as
        a blueprint for the actual DOM. So, in the actual DOM will refer to this blueprint and compare the two DOMs. This process is called as **reconciliation** and is achieved with the help something called as a diffing algorithm react modifies that particular component only. More on diffing algorithm can be found out here: (https://www.geeksforgeeks.org/what-is-diffing-algorithm/#:~:text=React%20uses%20a%20heuristic%20algorithm,not%20need%20to%20be%20checked.)
    <li> To understand this I have created diagram for the same:<br/>
    <img src="https://user-images.githubusercontent.com/68496657/179281845-0a2d41e6-6d7d-41f3-bd67-c88e89c7755b.png" alt="React Architecture" />
      
      
    
        
        
        
        
