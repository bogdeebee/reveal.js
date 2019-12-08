`(Slide title)`
Hello.
My name is Olga Bogdanova. I'm from Belarus. And next ten minutes we will talk about *React Native*.

I think, the first we must understand why is React Native needed us.

Let's imagine that we need to write a mobile application.

`(Slide 'We can to write mobile applications in several ways')`
We can make mobile application in the different ways:

* the first - we can write its in native. It is mean that we can write application for IOS in XCode or for Android in Android Studio or in different special IDE for each system.

* the second - we can write our application in WebView. WebView displays web content right inside your app. It’s as a browser is embedded in our application. 

* the third - we can write our application using cross-platform development. It mean that we can write code in one IDE and in one language for all system. 

We can write on Xamarin if we know C#, Flutter if we know Dart and etc. There is many options and one of them is the hero of our topic. It is React Native.

Ok. We understood why we need React Native. But what kind of beast is this?

`(Slide 'React Native')`
1. Appeared in 2015

2. Does not use WebView and HTML technology

3. Made on the basis of the React JS library developed by Facebook

4. Combines the best parts of native development with React, a best-in-class JavaScript library for building user interfaces. 

I will note that fourth point I found in official site. 

* I think I can say that React Native is like React, but it uses native components instead of web components as building blocks.

Oh. Three points note that React Native based onthe React and I can't get past this.

`(Slide 'What is React?' part 1)`
React is JavaScript library for building user interfaces. It lets us compose complex UIs from small and isolated pieces of code called “components”.

`(Slide 'What is React?' part 2 'basic principles')`
1. Declarative.
2. Component-Based
3. Learn Once, Write Anywhere

From that principles I want note Component-Based and 'Learn Once, Write Anywhere'. 

Component-Based.
It means that we can make a few small components and then compose them to make one large component and use it where we need and how we need.

Learn Once, Write Anywhere.
It mean that we can develop new features without touch existing code.

`(Slide 'How it works?')`
* We write React-component - React processes it - We get element of DOM

Lets return to React Native
* We write React-component - React Native processes it - We get element in our application on Android, on IOS, on anything we need.

We talk about component a lot of, but until don't know what is it. Time come change this.

`(Slide 'Components' part 1)`
* In its simplest form, this is a function
* Components can be reused, even in different projects
* We can compose a few small components and make one large component.

All of this similar to function but there are differences
* component name begins with an uppercase letter
* each component receives a list of attributes, as do HTML elements. In React, this list is called props.

`(Slide 'Components' part 2)`
Now you can see simple example: function Button return element button.
And what about next examples? Where is there component?
Yes, it is function CreateGreeting. 

Pay attention to the record of this component. Little later we will talk about it.

`(Slide 'Components' part 3)`
Components in React and React Native a little different. 
In React is components div, span and etc. which we always see in HTML.
In React Native is component View which replaces div, Text which replaces span and etc.

But it is not all. 

`(Slide 'Components' part 4)`
Components are general for all systems. It is View, Text and etc.

And components are special. They have ending "IOS" or "Android" and can used in the specified system. 

All components we can find in the official site.

`(Slide 'Components' part 5)`
But what if we did not find the necessary component?

We can make it ourself!

`(Slide 'JSX')`
Did you note strange sintaksis in second example component? Now we are talking about it.

It is JSX. It is syntax extension to JavaScript.

JSX allows us to develop React components using HTML-like syntax. And JSX can be used on its own. This is not part of React.

`(Slide 'CSS is not quite real' part 1)`
It is looks like loud headline in a yellow newspaper but it's true. If we want add style we must select one of three ways.

* CSS-In-JS or styled-component (It is the same)
* StyleSheet
* Style props

`(Slide 'CSS is not quite real' part 2 'CSS-In-JS or styled-component')`
It allows us to write normal CSS in JavaScript. It looks this:
* We write name component and assign styles to it.
* We can use this component. 

Lets see what make this code.

`(Slide 'CSS is not quite real' part 3 'StyleSheet')`
We can create javascript object which define the styles for our elements and then we can assign styles to the elements via their style prop.

`(Slide 'CSS is not quite real' part 3 ' Style props')`
We simply add style props to our element.

We saw three different ways adding styles with one result.
But there is another way of styling. It refers not to text, but to drawing shapes.

`(Slide 'CSS is not quite real' part 3 ' react-native-svg')`
We can used react-native-svg for create specific figure.

In the start we told that React Native is the one of way cross-platform development.
But now I must confess that this is not completely true.

`(Slide 'cross-platform')`
Interactive components (navigation, menus, ...) will be different on the mobile operation system. We already know that exist the special components. 
It mean the layout of the application may be different.

But I have good news. The logical components of the application will be the same. It mean that component "menu" will perform functional of menu at the any system. 

`(Slide 'IDE')`
Ok. And what about IDE? 
If we write native we must write application for IOS in XCode or for Android in Android Studio or in different special IDE for each system.

If you use React Native we can use our favorite development environment.

Sounds good, but...
It is true until we don't touch native code.
And if we want make compilation for example for IOS we must make this in special IDE which we can install only on products Apple.

`(Slide 'IDE')`
In the end, I would like to note that using React Native we can use any debuggers.

`(Slide 'You can learn more')`
In this slides I collected links which I used for creating this presentation.

There you can try to write code in React Native and see the result in the selected operating system.

And there I collected exaples of code which I had to insert like a pictures due to size. 

Thank you! 
I hope you found somethink helpfull for yourself.
Bye