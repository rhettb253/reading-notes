# class-03.md

##Learn HTML
###Ordered and Unordered lists.

- When should you use an unordered list in your HTML document?

You should use unordered lists when you dont want numbers to segment your list items.

- How do you change the bullet style of unordered list items?

With the css style: 'list-style-type' followed by a value like 'square'.

- When should you use an ordered list vs an unorder list in your HTML document?

You should use ordered lists when you want numbers to segment your list items. Ex: show steps in a recipe or an order of operations for warehouse safety protocol.

- Describe two ways you can change the numbers on list items provided by an ordered list?

You can make the numbers turn into roman numerals with <ol type="i">. Also, you can make the numbers start at a later number with <ol start="4">.

##Learn CSS
###The Box Model.

- Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Hi! My name is Margin. I'm like the property lines around your yard that keep your dirty neighbors from encroaching on the land around your house. Meet my friend Padding, she's kind of like me as she likes to create space, but she focuses more on making sure the yard around your house is proportioned correctly.

- List and describe the four parts of an HTML elements box as referred to by the box model.

  - content: The area where your content is displayed.
  - padding: The padding sits around the content as white space.
  - border: The border box wraps the content and any padding.
  - margin: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements.
  
## Learn JS
### Arrays. Operators and Expressions. Conditionals. Loops.

- What data types can you store inside of an Array?
  
  All data types can be stored inside of an array.
  
- Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
  
  Yes this is a valid array. Many of the values nested inside of it were typed incorrectly hence they will output as undefined. We can access the values by using people[#]. 
  
- List five shorthand operators for assignment in javascript and describe what they do.
  
  - x += y This will add the value of y to x. 
  - x -= y This will subtract the value of y to x. 
  - x %= y This will add the remainder value of expression y to x. 
  - x *= y This will multiply the value of y to x.
  - x /= y This will divide the value of y into x.
  
- Read the code below and evaluate the last expression and explain what the result would be and why.
 let a = 10;
 let b = 'dog';
 let c = false;
 // evaluate this
 (a + c) + b;
  
- (10 + false) + 'dog' --The result would essentially be the same thing since you can't add different data types to eachother.
  
- Describe a real world example of when a conditional statement should be used in a JavaScript program.

  You could use a conditional statement in JavaScript if you need the program to make an execution based on a previous value or input placed by the user. 
  
- Give an example of when a Loop is useful in JavaScript.

  A loop is useful when you need the program to continuously run through repetative tasks.

