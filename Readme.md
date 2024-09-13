# The Base code of React 🚀

NPM is known as package manager and it does not have any full form like 'node package manager'.

Our React project is based on several external packages which are located in Node Modules are manages by 'NPM'.

'BUNDLERS' ignites our app, they bind all the files and make our app production ready. There are many type of bundlers like webpack, vite, parscal. We are using parscal.

There are 2 type of dependencies 
    1. Normal dependencies (npm install ....)
    2. Dev dependencies (npm install -D ....) (used for development of app)

'package.json' keeps the track of what version of packages are installed and can be edited.
'package-lock.json' keeps the trach the dependencies are installed correctly in all environments and it can not be edited. 

'Node_modules' is like a database that contain all the data of dependencies. 

If we have 'package.json' and 'package-lock.json' we can re create all our 'node_modules'.

'NPM' is used for installing a package, while 'NPX' is used for executing a package.

# PARCEL:
    - Dev build
    - Local Server
    - HMR = Hot Module Replacement
    - File Watching Algorithm - written in C++
    - Caching - Faster Builds
    - Image Optimization 
    - Minification
    - Bundling
    - Compress
    - Code splitting
    - Consistent Hashing
    - Differential Bundling - support older browsers
    - Diagnostic
    - Error Handling
    - HTTPS 
    - Tree Shaking  - remove unnecessary files
    
React.createElelemnt creates a object , When the object is rendered to DOM it becomes a html createElelemnt
 [React.createElelemnt => Object => HTML Element]

 JSX not means HTML into JavaScript OR JavaScript into HTML. JSX have HTML or XML like syntax.

'BABEL' takes the code and convert it into the code in which JavaScript Browsers understands.

BABEL coverts all the JSX code into React.createElelemnt creates a object , When the object is rendered to DOM it becomes a html createElelemnt
 [JSX code => React.createElelemnt => Object => HTML Element]

 Elements in React are plain JSX Code.
 Components in React are used to return the Element inside our React Code. 

 Component composition is to merge a component into another component.

 JSX sanitizes our data coming from an external source like ans external API and prevent our code from crosss site scripting attacks.

 Props are just argument to a function(React component).