# React.js Conf 2015 Keynote - Introducing React Native
[YouTube Link](https://www.youtube.com/watch?v=KVZ-P-ZI6W4)

[Tom Occhino](tomocchino)

### Where did React come from?
Initially it came from Facebook Ad team! When they wanted to make the Ads Panel of Facebook they figure out they break lots of things each time they make changes!

They were using MVC models and each time a Model is changed the whole View is rerendered. But that's not the best way! The apps was getting more and more Complicated and as they added members to team development got slower. Something changed down in the tree was causing rerendering of the main view! Cascading updates.

The code was unpredictable. Actually the chat body list was like that for lots of time. Whenever someone came online the whole list was rerendered! Jordon Walke (@jordwalke) created the prototype to fix that issue. Inside facebook everyone thought it's so fun even if it's too slow. They replaced like and comment app part of facebook using this prototype. And they got positive feedback.

First time they released the syntaxes and showed JSX (A new type of markup for JS) lots of people said it was a Huge step backwards! But they were using XHP inside facebook for a while.

What makes React so powerful?
- Virtual DOM
- Server rendering
- Descriptive warning
- Custom events system
- **React wraps an imperative API with a declarative one.**

declarative -> predictable -> confidence -> reliability

The ads feature didn't break anymore and they sped up in case of feature development.

### React-Native
Web apps like Cordova, PhoneGap, Ionic were not good enough! You cannot have native experience with webviews. 

We didn't have these in web apps:
- Ability to parallelize work
- Sophisticated gesture handling
- Access to native capabilities (You cannot access MapKit for instance)

But you need to make the same app with different technologies for different platforms. Two teams for Android and iOS.

React native is basically something that Facebook was working on so you can use Native Components but control all the logic using JavaScript! So the whole code is written in JavaScript but the elements you see in the app are Native Components!

The JavaScript layer is Async! The UI is always running and the JS is running in background async so no frame is dropped! It's not a "Write once run anywhere" framework but it's a "Learn once, write anywhere". iOS and Android needs different UX, navigation, etc. But you need to learn one language and build everything using React! And you can reuse lots of the code.

