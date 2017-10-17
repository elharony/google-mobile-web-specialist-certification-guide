# Google Mobile Web Specialist Certification Guide
If you are looking for becoming a Mobile Web Specialist by Google, this guide will be your best friend in your journey

## The exam content:
1. Basic Website Layout and Styling
2. Front End Networking
3. Accessibility
4. Progressive Web Apps
5. Performance Optimization and Caching
6. Testing and Debugging
7. ES2015 Concepts and Syntax
8. Mobile Web Forms

> Each part will be covered with some resources to prepare for it

## 1) Basic Website Layout and Styling
Users expect responsive and visually engaging websites regardless of the device. A web
application's layout and styling must respond to the current display, while continuing to provide
intuitive functionality. You'll be asked to show you can use HTML, CSS, and JavaScript to build
a web application’s responsive layout and style that includes:

- DOM elements that are accessed and manipulated using only JavaScript without the
overhead of libraries or frameworks (such as jQuery)
- Appropriate document type declaration and viewport tags
- A responsive grid-based layout using CSS
- Media queries that provide fluid breakpoints across different screen sizes
- Multimedia tags to display video or play audio
- Responsive images that adjust for the dimensions and resolution of any mobile device
- Touch and mouse events that contain large hit targets on the front end and work
regardless of platform

### Resources
- [x] [Responsive Web Design](https://developers.google.com/web/fundamentals/design-and-ux/responsive/)
- [x] [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [x] [Using media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)
- [x] [Video and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- [x] [Responsive Images by Google](https://www.udacity.com/course/responsive-images--ud882)
- [x] [Supporting both TouchEvent and MouseEvent](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events/Supporting_both_TouchEvent_and_MouseEvent)
- [x] [Touch events](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)


## 2) Front End Networking
Because user engagement depends on reliable and effective network requests, you'll be asked
to show you can use JavaScript to set up reliable front end networking protocols by:

- Requesting data using fetch( )
- Checking response status, then parsing the data into usable format
- Rendering response data to a page
- Configuring POST requests to a database with method and body parameters
- Using correctly configured cross-origin resource sharing protocol (CORS) fetch
requests, depending on the server’s response headers
- Handling fetch( ) request errors with promise chaining
- Diagnosing network issues using debugging and development tools

### Resources
- [x] [Using fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [x] [Introduction to fetch()](https://developers.google.com/web/updates/2015/03/introduction-to-fetch)
- [x] [David Walsh's blog on fetch](https://davidwalsh.name/fetch)
- [x] [Jake Archibald's blog on fetch](https://jakearchibald.com/2015/thats-so-fetch/)
- [x] [JavaScript Promises: an Introduction](https://developers.google.com/web/fundamentals/primers/promises)
- [x] [HTTP access control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)


## 3) Accessibility
Web pages and applications should be accessible to all users, including those with visual,
motor, hearing, and cognitive impairments. Using HTML, CSS, JavaScript, you'll be asked to
show you can integrate accessibility best practices into your web pages and applications by:

- Using a logical tab order for tabbed navigation
- Using skip navigation links to bypass navbars and asides
- Avoiding hidden content on the page that impedes tab navigation
- Using heading tags that provide a logical page structure
- Using text alternatives to visual content, such as alt, <label>, aria-label, and
aria-labelledby
- Applying color contrast to all elements and following accessibility best practices
- Sending timely alerts for urgent messages using aria-live
- Using semantic markup to keep content and presentation separate when appropriate
  
### Resources
- [x] [Web Fundamentals – Accessibility](https://developers.google.com/web/fundamentals/accessibility/)
- [x] [Mobile Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Mobile)
- [x] [Using tabindex](https://developers.google.com/web/fundamentals/accessibility/focus/using-tabindex)
- [x] [Focus](https://developers.google.com/web/fundamentals/accessibility/focus/)
- [x] [Skip Navigation Links](http://webaim.org/techniques/skipnav/)
- [x] [ARIA](https://webaim.org/techniques/skipnav/)


## 4) Progressive Web Apps
Users expect native applications to be available offline and provide a feature-rich experience
that is launchable from their home page. You'll be asked to show that you can use service
workers, and HTML and JavaScript to build out progressive web application features similar to
native applications by:

- Creating a web app that is available offline, and that caches elements by routing
requests through a service worker
- Storing the default display orientation, theme color, display icon (add to home screen),
and splash screen in the web application manifest (or using meta tags)
- Separating critical application functionality and UI into an application shell that can be
loaded independently from the content
  
### Resources
- [x] [Progressive Web Apps](https://developers.google.com/web/fundamentals/accessibility/)
- [x] [Progressive Web Apps Training](https://developers.google.com/web/ilt/pwa/)
- [x] [Web Fundamentals - The App Shell Model](https://developers.google.com/web/fundamentals/architecture/app-shell)
- [x] [Your First Progressive Web App](https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/)
- [x] [Using Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)


## 5) Performance Optimization and Caching
Mobile users demand websites that load nearly instantly, despite poor or absent connectivity.
Because many users also face expensive data caps, you must minimize their application's data
footprint to reduce page load time as much as possible. You'll be asked to show you can carry
out performance audits on applications to reduce page load times and maintain responsive user
experiences by:

- Preventing main thread blocking with a dedicated web worker
- Providing an optimized critical rendering path using:
  - Compressed or minified JavaScript, HTML and CSS files to reduce render blocking
  - Inline CSS for essential styles on a specific page, with asynchronous loading for additional styles as necessary
  - Inline JavaScript files for initial rendering only where necessary (or otherwise eliminated, deferred, or marked as async)
  - Ordered loading of remaining critical resources and early download of all critical assets to shorten the critical path length
  - Reduced DOM depth to minimize browser layout/reflow
  - Your browser's developer tools to diagnose performance issues on mobile devices
- Prefetching files that load when resources are available, reducing the time to meaningful interaction
- Providing client storage that is appropriate to a web application’s data persistence needs, including:
  - Session state management
  - Asset caching based on their impact on load time and offline functionality
  - Using IndexedDB to store dynamic content in offline mode

### Resources
- [x] [Offline Web Applications by Google](https://www.udacity.com/course/offline-web-applications--ud899)
- [x] [Web Fundamentals - Performance](https://developers.google.com/web/fundamentals/performance/rail)
- [x] [The Offline Cookbook](https://jakearchibald.com/2014/offline-cookbook/)
- [x] [Cache - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Cache)
- [x] [Storage](https://developer.mozilla.org/en-US/docs/Web/API/Storage)
- [x] [Local Storage And How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
- [x] [IndexedDB API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
- [x] [Get Started with Analyzing Network Performance in Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/network-performance/)


## 6) Testing and Debugging
Developers typically work in highly iterative deployment environments, relying on extensive
testing and debugging to maintain functionality and code integrity. You'll be asked to show that
you can verify expected behaviors and diagnose common web application bugs by:

- Writing unit tests that first verify a function’s intended behavior, and then iteratively modifying its code until it passes those tests
- Setting breakpoints within a complicated function to determine exactly where it deviates from expected behavior
- Using console logs to output relevant debugging information
- Reproducing and fixing bugs based on user reported issues

### Resources
- [x] [Get Started with Debugging JavaScript in Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/javascript/)
- [x] [Diagnose and Log to Console](https://developers.google.com/web/tools/chrome-devtools/console/console-write)
- [x] [Debugging Service Workers](https://developers.google.com/web/fundamentals/codelabs/debugging-service-workers/)


## 7) ES2015 Concepts and Syntax
Web developers must stay current with the latest JavaScript features that promote simpler and more readable code. With polyfills enabling code written in ES2015 JavaScript to be used in unsupported browsers, there is a strong incentive for developers to begin using the new features and syntax. You'll be asked to show that you understand and can write ES2015 JavaScript code using:

- JavaScript promises with ES2015 syntax that create asynchronous functions and incorporate graceful error handling
- Variables that can be used with block scope, function scope, and made immutable depending on context using ```let, var```, and ```const```
- String literals that include string interpolation and multi-line strings
- Arrow functions that create anonymous functions and use an unbounded ```this```
- Default function parameters that initialize default values for a function when no argument or undefined is provided
- ```for...of``` loops that can iterate over any iterable object while running a custom function on each
- Maps that allow for arbitrary key and value pairs that are iterable and include non-string keys
- Sets that contain only unique, iterable elements where an array would degrade performance

### Resources
- [x] [JavaScript Promises: an Introduction](https://developers.google.com/web/fundamentals/primers/promises) *Just if you ignored it in "[2) Front End Networking](#front-end-networking)" part )*
- [x] [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [x] [Template literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
- [x] [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [x] [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)
- [x] [For...of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of)
- [x] [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
- [x] [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)


## 8) Mobile Web Forms
Filling out online forms, especially on mobile devices, can be difficult. To improve the user experience you'll be asked to show that you can use basic HTML5, JavaScript, and the HTML5 Constraint Validation API, to design efficient and secure HTML web forms with:

- Appropriate ```label``` tags associated with inputs
- Inputs with appropriate ```type, name``` and ```autocomplete``` attributes
- Inputs with large touch targets for mobile forms
- Suggestions for user input using the ```datalist``` element
- Front-end validation of inputs (e.g., ```pattern, maxlength, required```) and DOM elements, including:
  - Checking validation errors in real-time with pseudo-classes on inputs
  - Form validation prior to submission (Constraint Validation API)

### Resources
- [x] [HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms)
- [x] [Constraint Validation](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/Constraint_validation)
- [x] [Client-Side Form Validation with HTML5](https://www.sitepoint.com/client-side-form-validation-html5/)
- [x] [Data form validation](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms/Data_form_validation)
- [x] [Create Amazing Forms](https://developers.google.com/web/fundamentals/design-and-ui/input/forms/)
