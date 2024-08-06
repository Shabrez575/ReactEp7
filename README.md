Hooks In Details : - 

useEffect -
_When we put our useEffect() inside header component/ other component whenever the component render our useEffect is also render._

useState -
_Never use your useState outside of your component.
It is used to create local state variable inside your functional component. so always used inside your functional component_
_Never create useState inside a If Else Condition._
_It is a valid but it can create inconsistently in program._
_Never create inside for loop as well._

Routing Concept -
First of all install react router 
- npx i react-router-dom

Short way to write a component i.e rafce

Routing Home Page, About Us Page and Contact Us Page. 

If you try to access that route path which you dont have then react-router-dom will give you one error on browser side i.e 
https://2884a544-56de-4837-8647-130dd7aa9e6c-00-8emrd5uzfv6g.pike.replit.dev/shabrez

Output :
Unexpected Application Error!
404 Not Found
💿 Hey developer 👋

You can provide a way better UX than this when your app throws errors by providing your own ErrorBoundary or errorElement prop on your route.

If you want to give your own error page then 
create one component.

How to create children routes?
It will help to develop functionality in which we chnage the main component based on route like for 
/about -> Header
          About Page

Header is intact , my outlet is getting filled with the component that i passed as children into my parent (Here is AppLayout). I can have multiple parent & children but according to the route it will render and load the children route in place of outlet.
It will replace the outlet by <about /> according to the path.

* Now linking with nav item along with our route path.
* Home About Contact Card <login>

- On click of about us the about us page will be come in front of us.
- For that we are not going to use anchor tag bcz the whole page will be refreshed so that we are using link component which is given by "react-router-dom".
- In case of Anchor tag -> Reload the Page.
- In case Link Component -> It will refresh only the particular component.
- Thats why the react is able to create single page application.

- Two types of Routing in web apps.
- Client Side Routing
- Server Side Routing


