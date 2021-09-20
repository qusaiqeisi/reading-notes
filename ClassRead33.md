# <Login /> and <Auth />.
![](https://docs.oracle.com/cd/E17802_01/j2ee/j2ee/1.4/docs/tutorial-update2/doc/images/security-formBasedLogin.gif)


## Why is the Context API useful?

> The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application. 

![](https://res.cloudinary.com/practicaldev/image/fetch/s--YxjWiLSY--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://www.carlrippon.com/static/0d1f722d0fe4c2bc4c3d71595dbe67dd/ca682/prop-drilling-v-context.png)

## Can a component outside of a provider get its context? 
> To access a React context outside of the render function, we can use the useContext hook. We create the UserContext by calling the React. createContext method with a default context value. Then in the Users component, we call the useContext hook with UserContext to accxess the current value of UserContext.

## What are some common use cases for using the Context API? 
> Some sample use cases where the Context API proves helpful are: Theming — Pass down app theme. i18n — Pass down translation messages. Authentication — Pass down current authenticated user.

> Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.

## Describe “Context Hell” ?

> the React Context hell is the nasty code you get taking advantage of the React Context API.
![](https://miro.medium.com/max/1400/1*fA8Hp1Veki6asxUOcvFf3Q.png)

## Document the following Vocabulary Terms .
- global state
> Context provides a way to pass data through the component tree without having to pass props down manually at every level, managing state in multiple components that are not directly connected. ... Enough talking about it.

- global context
>  designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component: class App extends React.

- provider
>  The <Provider> component makes the Redux store available to any nested components that need to access the Redux store. Since any React component in a React Redux app can be connected to the store, most applications will render a <Provider> at the top level, with the entire app's component tree inside of it.

- consumer 
> A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. Requires a function as a child. The function receives the current context value and returns a React node.



**so the thing is what you abeal to do and achive to undersatnd your coworker team**

for more info please visit my github

**[qusaiqeisi](https://github.com/qusaiqeisi)**
 
 ***best regard*** 