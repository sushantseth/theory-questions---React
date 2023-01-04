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
     
What is NPM?

Ans: NPM is a package manager. It helps us install various packages to run our web application in more efficient manner.

What is `Parcel/Webpack`? Why do we need it?

Ans: Parcel or Webpack are bundler. We need these bundler for optimization of our web application. It provides a lot of functionality like minification, image compression, hot module replacement,cleaning our code, etc.

What is `.parcel-cache`?

Ans: Parcel uses parcel-cache files to actually perform various functionalities like minification, image compression, hot module replacement,cleaning our code, etc.

What is `npx` ?

Ans: This is just a command we use to execute the npm packages.

What is difference between `dependencies` vs `devDependencies`?

Ans: Dev dependencies are the packages which are required by the project in its development environment. They might not be there in the production environment. Whereas, the in dependencies, the packages are installed in the production env as well.

What is Tree Shaking?

Ans: Parcel analyse all the imports and exports from the modules and removes everything else that is not required. That is tree shaking.

What is Hot Module Replacement?

Ans: HMR is basically instantly updating everything on the UI if there is any change in the code. It does it by file watcher algorithm it uses in the background.

List down your favourite 5 superpowers of Parcel and describe any 3 of them in your
own words.

Ans: 1st - Hot module replacement
          HMR is basically instantly updating everything on the UI if there is any change in the code. It does it by file watcher algorithm it uses in the                       background.
     2nd - Image compression
          Images are one of the heaviest items while loading a web application and parcel compresses the media files for faster loading time.
     3rd - minification
          Parcel minifies the entire code and stores the minified version of the code in /dist folder.
     4th - Caching while development
          Parcel once build once, caches all the files so the subsequent build time reduces drastically.
     5th - compatible with older versions of browsers
          It uses polyfills in the background and this helps parcel to make our app compatible
          
 What is `.gitignore`? What should we add and not add into it?
 
 Ans: gitignore is a file which contains info regarding the folder/files in our app which should not be committed and pushed to prod. node_modules/dist/parcel-cache are such examples.
 *Basically anything which can be re-installed in the production server should not be commited and thus should be added to our gitignore.
 
 What is the difference between `package.json` and `package-lock.json`
 
 Ans: package-lock contains information of our current app configuration whereas package.json contains the original information of all the configurations of our app. With the help of package-lock.json we can reinstall all our node-modules to our production server.
 
 Why should I not modify `package-lock.json`?
 
 Ans: Package-json shows the exact version we have of our project and locks the version. If we modify in our package-lock it can create differences in the prod and local server.
 
 What is `node_modules` ? Is it a good idea to push that on git?
 
 Ans: node_modules contains all the packages which are required for our project. It should never be pushed on git because it can be installed anytime using our package-lock.json file
 
 What is the `dist` folder?
 
 Ans: dist folder contains the minfied version of our project which is used in the build version of parcel. It also compresses our code and stores information of only the imported/exported modules of our app for faster loading of our application
 
 What is `browserlists`
 
 Ans: browserlists is a dependency which can be mentioned in the package.json which allows us to mention the list of all the previous versions of browsers which needs to be compatible with our app. Parcel then uses polyfill in the background to make it compatible.
 
 
     

