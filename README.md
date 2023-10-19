# shop-shop

<!-- 

NOTES:


MAKE STRIPE PAYMENTS TO EXISITNG CODE BASE

MAKE COMPONENTS FUNCTIONS GLOBALLY TO AVOID PROP-DRILLING 

IMPROVE CODE BASE, ALWAYS ROOM FOR IMPROVEMENT 

ADD STRIDE.JS API


DEPLOY WITH CHANGES 

----

working with actions and reducers

using redux but not really just a component of redux thats not actually redux but something that provides the same type of functionality that reduxs uses thats compatible with React.

we are mananging the state of this application using actions and reducers

overall goal to to make it a gloabl state

which in turn will make it easire to add offline cabality

also easier to manage the state if the state was global

reducer updates the state by creating a new object, and using the old object's state within the new state object but only modifying what needs to be changed EXAMPLE:

// original state
const state = {
  name: 'Lernantino',
  email: 'lernantino@gmail.com' 
};

// create a new version of state by making a copy of the original state's data and updating only the part that has changed
const updatedState = {...state, email: 'lernantino99@gmail.com'};

global state functon set up needed


-->