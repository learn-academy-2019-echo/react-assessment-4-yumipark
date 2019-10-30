# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications (TRUE)
- React will only render on the server using Node.js (FALSE)
- React is a full stack framework for modern web applications (FALSE)
- React is a flexible library that plays the role of V in an MVC framework (TRUE)
- You should always update a component's state directly using this.state (FALSE)
- React is made up of encapsulated components that manage their own state (TRUE)
- React components render HTML (TRUE)

1b. Add an interesting TRUE fact about React to the list.

- React

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: Smart components have state(s). Dumb components have no state(s).

  Researched answer: A component without state is a 'dumb component'. It's merely presentational. A component with state is called a 'smart component'. It keeps track of state and cares about how the app works.

3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: I don't know.

  Researched answer: Yarn is adding a package to your dependencies. This will always update package.json and yarn.lock.

4. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: State is the initial setting of the state. Data can be passed into child components via props.

  Researched answer: "State - This is data maintained inside a component. It is local or owned by that specific component. The component itself will update the state using the setState function.

  Props - Data passed in from a parent component. props are read-only in the child component that receives them. However, callback functions can also be passed, which can be executed inside the child to initiate an update."

5. How would you explain state to a friend who doesn't know code?

  Your answer: A state represents the visual display of a webpage. Everytime the display updates, the state is being updated to reflect the change.