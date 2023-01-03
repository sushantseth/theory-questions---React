# theory-questions---React
Theory questions of React


What is Emmet? 

Ans: Emmet is  a free add-on to your text editor. It allows you to write shortcuts to your code which is then expanded into full piece of code.

Difference between a Library and Framework?

Ans: Major difference between library and framework is the inversion of control. Library gives the control to developer to choose when to call it. However, Framework is the charge of the flow of the code. It provides some place for you to plug in your code but decides when to call it.

What is CDN? Why do we use it?

Ans: Content delivery network is a geographically distributed network of servers to deliver faster internet content.(quick transfer of assets for loading internet content)
We use CDN for following purpose: 
1 - To prevent Distributed denial of service attack (DDOS)
2 - for content availability - even if there is heavy traffic, content will be available.
3 - Reducion in the content loading time.
4 - decrease in the bandwidth cost on the origin server.

Why is React known as React?

Ans: Because when any data is changed/updated in the component, react reacts to this by re-rendering the component. 

What is crossorigin in script tag?

Ans: crossorigin makes the mode of the request an HTTP request. Crossorigin means trying to access the contents from one server to another. 

What is diference between React and ReactDOM

Ans: React is actually responsible for creating views/elements whereas ReactDOM is responsible for rendering them on the browser.

What is difference between react.development.js and react.production.js files via CDN?

Ans: react.production.js files via CDN are the minified and compressed version of react.development.js for faster loading in the production env.

What is async and defer?

Ans: normal  - html file is parsed until sript tag comes. Then request will be made to fetch the file and execute the file. After which html parsing will continue
     async  - html file is parsed and simultaneously file is also downloaded. Once the downloading is done, html parsing haults and script is executed and then parsing continues.
     defer - html file is parser and simultaneously script file is also processed/downloaded. But only after the html parsing is completed, the script is actually executed. defer also makes sure the scripts are executed exactly in the order they appear in the doc.
     


