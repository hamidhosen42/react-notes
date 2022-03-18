### react-notes

### Netlify react live commend ->then build file push netlify= npm run build

## Api থেকে  data load করার জন্য
```
১. প্রথমে state ডিক্লেয়ার করবো।

২. useEffect ডিক্লেয়ার করবো

৩.  fetch ব্যবহার করে ডাটা লোড করতে হবে

৪. State ব্যবহারের মাধ্যে ডাটাগুরো সেট করতে হবে

৫. Dynamically  ডাটা গুলো দেখাতে হবে
```


## React Install:
```
npx create-react-app my-app
cd my-app
npm start
44-0 Milestone overview
```

MODERN FRONT-END CORE CONCEPTS
```
1.	Web component
2.	Dynamic create HTML elements
3.	Single Page Application(SPA)
4.	Routing, Route parameter
5.	Destructuring and props
6.	Website state
7.	Folder structure
```
React Core Concept:
```
1.	Core concepts Discussion
2.	Working with JSX, Dynamic content, Dynamic Style
3.	Pass Dynamic data to components, props
4.	Create multiple components
5.	State, component state hook and set state
6.	Load dynamic data , API call useEffect integrate state
```
HOW REACT WORKS
```
1.	What is JSX, React Component, babel transpiler
2.	Components and how props works
3.	Unidirectional data flow
4.	How states works, asynchronous
5.	How React Hook works
6.	Props vs state
7.	Properties vs attributes
8.	What Is React, when to use it
9.	Render, virtual dom, diff algorithm
10.	React component lifecycle
```

YOU WILL ALSO LEARN
```
1.	ES6 Modules
2.	Import, Expart, Default
3.	Relative Path
4.	Create and Load Fake data
5.	Array reduce
6.	Local storage functionality
7.	Good UI vs bad UI
8.	Themeforestm, freepik, flaticon, unsplash
9.	Add or remove key to an object
10.	Wrap event handler with arrow function
11.	Local stortage with more functionalites
```

USESTATE()

- USESTATE হলো একটি DYNAMIC STORAGE বা DATABASE . যেগুলো আমাদের COMPONENTS এর ভিতর DATA STORE করে রাখার জন্য থাকতে পারে।

USEEFFECT()

-যখন কোন COMPONENTS CREATE , UPDATE অথবা REMOVE হয় তখন এ ফাংশনগুলো কল হয়। এ সকল কিছু USEEFFECT নামক হুক দিয়ে ম্যানেজ করা হয়। এ USEEFFECT হুক এর ভিতরে প্রথম ARGUMENTS টা RUN হয় যখন আপনার PAGE এ প্রথম COMPONENTS টা CREATE হয়। এরপর আর কখন কখন RUN হবে তা নির্ভর করবে ২য় ARGUMENTS এর উপর। ২য় ARGUMENTS কে আমরা বলে দিব যে, STATE এর কোন জিনিসটি CHANGE হলে এই UESEFFECT ফাংশনটি আবার RUN করবে। এটাকে TRIGGER ও বলা হয়। এবং FINALLY এই COMPONENTS থেকে আমরা চাইলে আর একটা ফাংশন রিটার্ন করিয়ে দিতে পারি যখন আমাদের COMPONENTS টা PAGE থেকে UNMOUNT আর DELETE হবে, তখন এই ফাংশনটা RUN করেবে।
-এটা REACT এর SIDE EFFECT হিসাবে কাজ করে।
