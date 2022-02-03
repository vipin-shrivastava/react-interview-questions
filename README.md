Que1. How React JS index.js file contacting index.html for id references?

Ans. React is one of the best JS libraries out there. It simplifies the development process without cluttering the implementation details explicitly. The index.html and index.js get linked during runtime when you start the script. React uses webpack under the hood where the entry for the webpack is index.js and when it is run(after all the conversions) it injects the javascript code in the HTML file which is index.html. And you can see this injected code in the index.html when you build the bundle inside the build folder.  

https://stackoverflow.com/questions/41738421/how-react-js-index-js-file-contacting-index-html-for-id-references