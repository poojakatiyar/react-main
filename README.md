# Namaste React 🚀


# Parcel
- Dev Build
- Local Server
- HMR = Hot Module Replacement
- File Watching Algorithm - written in C++
- Caching - Faster Builds
- Image Optimization
- Minification
- Bundling
- Compress
- Consistent Hashing
- Code Splitting
- Differential Bundling - support older browsers
- Diagnostic
- Error Handling
- HTTPs
- Tree Shaking - remove unused code
- Different dev and prod bundles



# Namaste Food


/**
 * Header
 *  - Logo
 *  - Nav Items
 * Body
 *  - Search
 *  - RestaurantContainer
 *    - RestaurantCard
 *      - Img
 *      - Name of Res, Star Rating, cuisine, delery tie
 * Footer
 *  - Copyright
 *  - Links
 *  - Address
 *  - Contact
 */



 Two types of Export/Import


- Default Export/Import

export default Component;
import Component from "path";


- Named Export/Import

export const Component;
import {Component} from "path";


# React Hooks
 (Normal JS utility functions)
- useState() - Superpowerful State Variables in react
- useEffect()



#  2 types Routing in web apps
 - Client Side Routing /single page application
 - Server Side Routing




 # Redux Toolkit
  - Install @reduxjs/toolkit and react-redux
  - Build our store
  - Connect our store to our app
  - Slice (cartSlice)
  - dispatch(action)
  - Selector


# Types of testing (devloper)
 - Unit Testing
 - Integration Testing
 - End to End Testing - e2e testing

# Setting up Testing in our app
 - Install React Testing Library
 - Installed jest
 - Installed Babel dependencies
 - Configure Babel 
 - Configure Parcel Config file to disable default babel transpilation 
 - Jest  - npx jest --init
 - Install jsdom library
 - Install @babel/preset-react - to make JSX work in test cases
 - Include @babel/preset-react inside my babel config
 - npm i -D @testing-library/jest-dom
 

 -------------My notes--------------
class base component 

--> passing data in class component 
and receving data is with constructor 
  constructor(props) {
    super(props);

    this.state = {
      count:2
    };

    render(
      <p this.state({
        count: this.state.count + 1
      })></p>this.props.count
    )
    
  }

->functional component
props 
#componentDidMount()ß


useeffect once 
unmount- 


=================JS=========
https://www.linkedin.com/in/pooja-patel-576a54123/


m
y day today shedule is getting req from productMang and creating design doc taking approval des doc
then finalize the api signature which needs to be integrated and verify with backend team post which
i start my devel  which consist of  integrating  api creating UI
used of caching - web works
  
a funtion with lexical scope performs clouser

a cclouser is combination of function and lexical scope a bundel together 

function abc()
{
    let a = 10;
    function inner()
    {
        console.log(a)
    }
    return inner;
}
abc()();

reduce - take aray and given a single value 
filter - filter to array with according to ur condition

#undefine- x value is present in memory but not intilize
#not define- x is not present in scope memory  .
if function is aroow function it behave like diff function name variable in that case also called undefine
hositing - we can invoke the function before intilize the function in top first (diff case will come -define,undefine)

#syntax error -> if we write a variable without assign a value [ const a;] bcz const expect some value or if you try to redecalare let variable [let a =10;a =200]
#type error -> yor are trying to  assign any other value to constatnt variable [const a =10; a=300;]
#refrence error -> when js engine tryies to find out a specific varaible  inside the memory space and you can't acces it [ console.log(a); let a =10 ] a is in tempral zone
let/const (more strict)

#callback issue - callback hell,inversion of control

#promises - promises is nothing just a object . when we used promises we have surity function will execute only one will give the result , just take example 
funtion 1 work independlty they gave blank object with some undefine data in promise, now once callback finesh any time they fill the pronise with some 
data. both function works indepnedlty no one waiting to complete their . or also we don't he is completing work or not for this issue we use pronise
const promisData - createorder(cart); --> this line means the function return some promise state(fulfill,pending,rejected)
promis.then(function(orderidcomingfrompromis) {
  proceedToPayment(orderidcomingfrompromis)
  console.log(responsedata of create data)
})












# react-main
