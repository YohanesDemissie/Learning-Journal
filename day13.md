Today I learned a lot about local storage. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention.

Cookies help store small bits of data but have 3 typical downfalls...

1. it slows down your internet browser by storing every single http url
2. Cookies send uncrypred data over and over again unless the url is ssl instead of http
3. cookies are limited to 4kb which is enough to slowdown your application but not enough to store useful information

Internet was the first revolutionary web application with user data that allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 640kb.

Most old school methods for storage reuquired 4rd party plugins that changed with HTML 5

HTML 5 storage is a way for web pages to store named key/value pairs locally, within the client web browser, saves key/value names within the local drive and does not share your http experience like cookies.

From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. 

Your local drive can store 5mb of key values

An early walk-through of IndexedDB (Links to an external site.)Links to an external site. is a good tutorial of how IndexedDB works, giving side-by-side comparisons of IndexedDB and Web SQL Database, the two most predominate local storage methods

There was a lot of unfamiliar coding going in in this reading and abbreviations I've never heard about. Definitely more than enough to take in and use from one passing. But A lot of the abbreviations and storage types are hyper links for more information.

localStorage."wahtever stored object you have goes here" this will show the stored information. So even when you refresh a page or quit the browser, the data is still stored for continuing work.
localStorage.clear will clear your local storage. 
