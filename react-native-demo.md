# React.js Conf 2015 Keynote 2 - A Deep Dive into React Native
[YouTube Link](https://www.youtube.com/watch?v=7rDsRXj9-cU)
[Christopher Chedeau](https://twitter.com/vjeux)

React gets the best parts from Native and best parts from Web.

Native
- Touch Handling
- Native Components: Implementing web version of native components doesn't feel as good.
- Style & Layout: Layouts are very different in Android and iOS.

Web
- Developer experience
- Imperative Mutative API
- Compile time, linking time

Setting the views are all done in main thread.
Logic is pushed to main thread.

React.js doesn't convert JavaScript code to iOS. It runs the JavaScript file.

You can open debugger in Chrome. There is a websocket connection between Chrome and iOS Simulator. You can put debugger in Chrome!

You can even use remote JS engine for lowend devices!

For styling, CSS has problems! In React-Native we are putting CSS in the JS file!

Problems of CSS are:
- Global Namespace
- Dependencies
- Dead Code Elimination
- Minification
- Sharing Constants
- Non-deterministic Resolution
- Isolation

You use inline styles! BUT, you pass the JavaScript object to the style! This way you can use function, variables or even modules in your styling!

It uses flexbox!

The rebuild time is amazing!

In react we have warnings with very good description! And the errors are not hidden in console, they will be visible right in your face! :)
