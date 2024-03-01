# CDN (CONTENT DELIVERY NETWORK) 
* It's a system of distributed servers (network) that deliver pages and other web content to a user based on the geographic locations of the user. CDNs are designed to take the load off of the original server by caching content in multiple locations around the world, thus improving site performance and speed, reducing load times, and ensuring content is more readily available and stable during high traffic periods or internet congestion. They are widely used for delivering webpages, streaming videos, games, and other online content efficiently to users around the globe.

* When a user requests content from the website, the CDN dynamically determines the user's location and routes the request to the nearest server in the network. Then the server delivers the content to the user,

* in react cdn act as a bridge between the corefiles with browser



 # Same-Origin Policy (SOP)
Isolation: SOP prevents malicious websites from accessing sensitive data from another site. For example, if you're logged into your bank's website, SOP stops other websites you might visit simultaneously from making requests to the bank's website and accessing or manipulating your banking information.

# Cross-Origin Resource Sharing (CORS)
* Controlled Sharing: CORS provides a way for servers to control how their resources are shared across origins. By specifying which origins are allowed to access a resource, servers can expose data to some origins while keeping it restricted from others.

* In summary, the management of cross-origin requests through SOP, CORS, and other security measures is crucial for preventing cross-site scripting (XSS), data theft, and other web-based attacks, ensuring that the web remains a secure environment for users and developers.

# Popular Bundlers for React
* Webpack: One of the most popular bundlers, offering a wide range of plugins and loaders to handle different types of assets.
* Parcel: Known for its zero-configuration approach, Parcel is user-friendly and can automatically handle many tasks that require plugins in other bundlers.
* Rollup: Focused on producing efficient bundles for libraries and applications, and it's known for its tree-shaking capabilities.
* Vite: A modern build tool that leverages native ES Modules for serving code and uses Rollup for production builds. It offers extremely fast cold server start and hot module replacement.

# Why we need bundlers
* Bundlers play a crucial role in React application development and deployment for several reasons. Their necessity stems from both the nature of modern web development practices and the technical requirements of browsers. Here are the key reasons why bundlers are needed in React

## JSX and Modern JavaScript Support
* React often uses JSX syntax, which allows HTML to be written within JavaScript code, browsers can't directly interpret JSX or some of the latest JavaScript (ES6+) features used in React development. Bundlers like Webpack, Parcel, or Vite, in combination with transpilers like BABEL, convert JSX and modern JavaScript into plain JavaScript code that browsers can understand.
BABEL CONVERT THE CODE TO REACT UNDERSTANDLE OBJECT JS CODE BY WRITING HTML LIKE SYNTAX THROUGH JSX

## Module Bundling
 * React applications are typically built using a modular architecture, with components and utilities split across multiple files and directories. Modern JavaScript modules (using import and export syntax) aren't fully supported in all browsers, especially in more complex scenarios. Bundlers compile these modules into a single file or a few chunks, ensuring the code can be executed in the browser efficiently.

## Performance Optimization
 * Minification: Reducing file size by removing unnecessary characters (like whitespace) from code without changing its functionality.
* Tree Shaking: Eliminating unused code from the final bundle, reducing load times and improving app performance.
* Code Splitting: Splitting code into various bundles that can be loaded on demand or in parallel, improving the initial load time of the application.

## Environment Variables
* Bundlers allow developers to use environment variables  enabling more secure and flexible configuration management.

## Asset Management
* React applications often include various assets like CSS, images, and fonts. Bundlers can process these assets by incorporating them directly into the JavaScript bundle.

##  Development Experience
* Hot Module Replacement (HMR): Allows modules to be updated in real-time without needing a full page refresh, speeding up development.
* Source Maps: Provide a way to map the code within a compressed file back to its original position in a source file, simplifying debugging.
* Dev Servers: Local development servers that can serve assets dynamically, provide live reloading capabilities, and more.

* In summary, bundlers are essential in React development for transforming, optimizing, and packaging web applications into formats that are efficient, manageable, and browser-compatible, significantly impacting both the development process and the performance of the final application.