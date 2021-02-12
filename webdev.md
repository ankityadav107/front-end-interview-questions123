<div align="center">
<h1>General Questions</h1>
</div>
<ol>
<li>A/B testing</li>

<details><summary>Answer</summary><p>

A/B testing (also known as split testing) is a process of showing two variants of the same web page to different segments of website visitors at the same time and comparing which variant drives more conversions.

</p></details>

<li>A11y: ARIA</li>

<details><summary>Answer</summary><p>

Accessible Rich Internet Applications (ARIA) is a set of attributes that define ways to make web content and web applications more accessible to people with disabilities.

The following gives no indication to assistive technologies that it is a custom checkbox:

```html
<li tabindex="0" class="checkbox" checked>
  Receive promotional offers
</li>
```

We can improve it by using the `role` and `aria-checked` attributes:

```html
<li tabindex="0" class="checkbox" role="checkbox" checked aria-checked="true">
  Receive promotional offers
</li>
```

</p></details>

<li>A11y: examples of best practices</li>

<details><summary>Answer</summary><p>

- Providing alternative text for images and icon fonts
- Making all functionality of the site available using a keyboard
- Avoiding blinking or flashing elements
- Ensuring all ARIA roles and properties are valid
- Ensuring sufficient contrast between elements
- Avoiding the use of color as the sole means of communication information
- Avoiding the use of CSS pseudo-elements for non-decorative content

</p></details>

<li>A11y: How can we make a form more accessible? (interview)</li>
<li>A11y: skip links What benefit(s) do they provide some of their limitations</li>
<li>A11y: some of the tools available to test the accessibility of a website or web application</li>
<li>A11y: WCAG the differences between A, AA, and AAA compliance</li>
<li>Acceptance testing</li>
<li>AJAX</li>
<li>Ansible</li>
<li>API</li>

<details><summary>Answer</summary>
<p>

An application programming interface (API) is a set of clearly defined methods of communication among various components.

An API simplifies programming by abstracting the underlying implementation and only exposing objects or actions the developer needs.

![API visual](../../blob/master/images/api.png)  
Image credit: [https://learn.g2.com/api](https://learn.g2.com/api)

</p></details>

<li>Apollo</li>
<li>AWS</li>
<li>AWS Lambda</li>
<li>Babel</li>
<li>BDD vs. TDD</li>
<li>Bootstrap vs. Bulma</li>
<li>Bootstrap vs. Materialize</li>
<li>Caching</li>
<li>Continuous Integration (CI) vs. Continuous Delivery (CD)</li>

<details><summary>Answer</summary><p>

**Continuous Integration** is merging all code from all developers to one central branch of the repo many times a day trying to avoid conflicts in the code in the future.

**Continuous Deployment** ensures that every change that is made is ready to be deployed to production.

CI helps development teams avoid "integration hell" where the software works on individual developers' machines, but it fails when all developers combine (or "integrate") their code. Continuous Delivery goes one step further to automate a software release, which typically involves packaging the software for deployment in a production-like environment. The goal of Continuous Delivery is to make sure the software is always ready to go to production, even if the team decides not to do it for business reasons.

</p></details>

<li>CLI</li>
<li>CMS</li>
<li>Concurrency vs. Parallelism</li>
<li>Content strategy</li>
<li>CORS</li>

<details><summary>Answer</summary><p>

CORS (Cross-Origin Resource Sharing) is a security mechanism that prevents a malicious site from reading or modifying another site's data.

A request for a resource (like an image or a font) outside of the origin is known as a cross-origin request. CORS manages cross-origin requests. With CORS, a server can specify who can access its assets and which HTTP request methods are allowed from external resources.

</p></details>

<li>Cross Site Scripting (XSS)</li>
<li>CRUD</li>
<li>Data binding</li>
<li>Database sharding</li>
<li>Databases: ACID properties of a transaction</li>
<li>Deadlocks & Mutex</li>
<li>Dependency injection</li>
<li>DevTools: some ways that Chrome DevTools can help us with finding ways to improve our sit</li>performance  
<li>DNS</li>
<li>Docker</li>
<li>Elasticsearch</li>
<li>Extreme Programming (XP)</li>
<li>Flash of Unstyled Content (FOUC). How do you avoid FOUC?</li>
<li>Flutter</li>
<li>Forms: some best practices when designing a form</li>
<li>Four pillars of OOP</li>
<details><summary>Answer</summary><p>

1. **Abstraction**:  
hiding the inner workings of a class and just allowing the necessary portions be visible.

2. **Encapsulation**:  
a process of binding data members (variables, properties) and member functions (methods) together. In object oriented programming language we achieve encapsulation through Class.  

3. **Inheritance**:  
the process of creating the new class by extending the the existing class.  

4. **Polymorphism**:  
functions with same name but different arguments, which will perform differently. That is function with same name, functioning in different way. Or, it also allows us to redefine a function to provide its new definition.
</p></details>

<li>Functional programming. How does it differ from object oriented programming?</li>
<li>GraphQL</li>
<li>How would you go about accepting payments via Credit cards or PayPal for a shopping car</li>feature you are developing for a client  
<li>HTTP: How does a 403 differ from 404 error</li>
<li>HTTP: HTTP vs HTTPS</li>
<li>HTTP: Is HTTP the same as REST</li>
<li>HTTP: List some of the HTTP methods that you are familiar with.</li>
<li>HTTP: Purpose of a HTTP header</li>
<li>HTTP: some best practices for a 404 page</li>
<li>HTTP: some causes of a 500 error</li>
<li>HTTP: Status codes</li>
<li>HTTP: What happens behind the scenes when you enter a URL into the browser and press enter</li>
<li>Imperative vs. Declarative Programming</li>
<li>JIRA</li>
<li>JPEG vs. PNG vs. GIF</li>
<li>jQuery</li>
<li>jQuery: Why has jQuery become less popular in recent years?</li>
<li>JSON vs. XML</li>
<li>JSONP</li>

<details><summary>Answer</summary><p>

JSONP (JSON with Padding) is a simple way to overcome browser restrictions when sending JSON responses from different domains from the client.

JSONP wraps up a JSON response into a JavaScript function and sends that back as a Script to the browser. A script is not subject to the Same Origin Policy and when loaded into the client, the function acts just like the JSON object that it contains.

```js
// an example of JSON
 {"weapon":"nunchucks","headband":"yellow"}

 // an example of JSONP
 myCallback({"weapon":"nunchucks","headband":"yellow"});
 ```

</p></details>

<li>Kubernetes</li>
<li>Lazy loading</li>

<details><summary>Answer</summary><p>

Lazy loading is an optimization technique used in web applications. Its goal is to improve the time it takes for a web page or application to load by loading only the required sections and delaying the remaining non-blocking resources (such as images the user has not scrolled to yet) until they are needed by the user.

</p></details>

<li>Library vs. framework</li>
<li>Linters</li>
<li>Load Balancer and its advantages</li>
<li>Low-fidelity vs. High-fidelity prototyping</li>
<li>Microservices and how do they differ from monoliths</li>
<li>Middleware</li>
<li>MVC</li>

<details><summary>Answer</summary><p>

Model-View-Controller or MVC is a design pattern used to separate user-interface (view), data (model), and application logic (controller). Controller acts as a liaison between the Model and the View, receiving user input and deciding what to do with it.

![MVC](../../blob/master/images/mvc.png)

</p></details>

<li>MVC: Are MVCs and frameworks the same</li>
<li>MVC: some pros and cons of using an MVC</li>
<li>MVVC</li>
<li>Native vs. Hybrid apps</li>
<li>Nginx</li>
<li>Node.js</li>
<li>NPM & Yarn</li>
<li>ORM</li>
<li>Performance: CDN and the benefit of using one</li>
<li>Performance: domain pre-fetching and how does it help with performance</li>
<li>Performance: How many resources will a browser download from a given domain at a time th</li>exceptions  
<li>Performance: Is it better to perform animations on a webpage using CSS or JavaScript</li>
<li>Performance: Minifying Is it always a good idea to minify</li>
<li>Performance: Name 3 ways to decrease page load (perceived or actual load time).</li>
<li>Performance: some things you can do to make a website compatible with some earlier versions o</li>IE  
<li>Performance: some ways to improve performance of a page</li>
<li>Performance: some ways to increase code maintainability</li>
<li>Performance: some ways to optimize an image for web</li>
<li>Performance: What does it mean for an image to be optimized for web</li>
<li>Polyfill</li>
<li>Progressive enhancement vs. graceful degradation</li>
<li>Progressive rendering</li>
<li>PUT vs. PATCH methods in RESTful APIs</li>
<li>PWA</li>
<li>React</li>
<li>React: Is it always a better idea to use React than Vanilla JavaScript in a project</li>
<li>React: Is React a framework Why or why not</li>
<li>React: some advantages of using React over Vanilla JavaScript</li>
<li>ReactNative</li>
<li>Redis</li>
<li>Redux</li>
<li>REPL</li>
<li>REST</li>

<details><summary>Answer</summary><p>

REST is acronym for REpresentational State Transfer. It is an architectural style that developers follow when they create their RESTful APIs.

</p></details>

<li>REST vs. SOAP APIs</li>
<li>RESTful API (6 constraints)</li>

<details><summary>Answer</summary>
<p>

In order to be a true RESTful API, a web service must adhere to the following six REST architectural constraints:

1. **Client-Server based**:  
The client and the server should be separate from each other and allowed to evolve individually and independently.

2. **Use of a uniform interface (UI)**:  
The key to the decoupling client from server is having a uniform interface that allows independent evolution of the application without having the application’s services, models, or actions tightly coupled to the API layer itself. The uniform interface lets the client talk to the server in a single language, independent of the architectural backend of either.

3. **Stateless operations**:  
Meaning that requests can be made independently of one another, and each request contains all of the data necessary to complete itself successfully. A REST API should not rely on data being stored on the server or sessions to determine what to do with a request, but rather solely rely on the data that is provided in that request itself. Identifying information is not being stored on the server when making requests. Instead, each request has the necessary data in itself, such as the API key, access token, user ID, etc.

4. **Caching**:  
A REST API should be designed to encourage the storage of cacheable data on the client side in order to reduce the number of interactions with the API. This means that when data is cacheable, the response should indicate that the data can be stored up to a certain time (expires-at), or in cases where data needs to be real-time, that the response should not be cached by the client.

5. **Layered system**:  
REST allows for an architecture composed of multiple layers of servers. The requesting client need not know whether it’s communicating with the actual server, a proxy, or any other intermediary.

6. **Code on demand (optional)**:  
Most of the time, a server will send back static representations of resources in the form of XML or JSON. However, when necessary, servers can send executable code to the client.

</p></details>

<li>RESTful APIs are stateless. What does this mean?</li>

<details><summary>Answer</summary>
<p>

It means that API requests can be made independently of one another, and each request contains all of the data necessary to complete itself successfully.

</p></details>

<li>RESTful web service request (its four components)</li>
<li>SaaS vs. PaaS</li>
<li>Scrum</li>
<li>Scrum artifacts</li>
<li>Scrum ceremonies</li>
<li>Scrum vs. Kanban</li>
<li>Selenium</li>
<li>SEO: best practices</li>
<li>Server side rendering and why would you want to do it</li>
<li>Server side rendering vs. Client side rendering</li>
<li>Serverless architecture</li>
<li>Shadow DOM</li>
<li>Software Development Life Cycle (SDLC)</li>

<details><summary>Answer</summary><p>

In software engineering, the SDLC is a process for planning, creating, testing, and deploying an information system.  

![SDLC](../../blob/master/images/sdlc.png)  

</p></details>

<li>SOLID principles</li>

<details><summary>Answer</summary><p>

In object-oriented computer programming, SOLID is a mnemonic acronym for five design principles intended to make software designs more understandable, flexible, and maintainable.

**Single-responsibility principle**  
Every module, class or function should only have a single responsibility.

**Open–closed principle**  
Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification; that is, we should be able to add new functionality without touching the existing code for the class. This is because whenever we modify the existing code, we are taking the risk of creating potential bugs. So we should avoid touching the tested and reliable (mostly) production code if possible.

**Liskov substitution principle**  
Given that class `B` is a subclass of class `A`, we should be able to pass an object of class `B` to any method that expects an object of class `A` and the method should not give any weird output in that case.  
This is the expected behavior, because when we use inheritance we assume that the child class inherits everything that the superclass has. The child class extends the behavior but never narrows it down.

**Interface segregation principle**  
The principle states that many client-specific interfaces are better than one general-purpose interface. Clients should not be forced to implement a function they do no need. For example an interface for an ATM which handles all requests such as a deposit request or a withdrawal request, needs to be segregated into individual and more specific interfaces.

**Dependency inversion principle**  
It states that our classes should depend upon interfaces or abstract classes instead of concrete classes and functions.

</p></details>

<li>SPA</li>
<li>SPA: When would you not want to use a Single Page Application</li>
<li>SQL injection: As front-end developers, do we need to worry about SQL injections? (interview)</li>
<li>SQL vs. NoSQL databases</li>
<li>SSH</li>
<li>SSL</li>
<li>Static site</li>
<li>Static site: Gatsby vs. Jekyll</li>
<li>Storage: Cookie vs. SessionStorage vs. LocalStorage.</li>
<li>Storage: Cookies vs. Sessions</li>
<li>Storage: the lifetime of local storage</li>
<li>Svelte</li>
<li>SVG</li>
<li>TC39</li>
<li>TCP vs. UDP</li>

<details><summary>Answer</summary><p>

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are both network protocols that transfer data over the internet from a device to a web server. Both UDP and TCP divide data into smaller units called data packets.

- TCP is a connection-oriented protocol, whereas UDP is a connectionless protocol.
- The speed for TCP is slower while the speed of UDP is faster.
- TCP does error checking and also makes error recovery. UDP performs error checking, but it discards erroneous packets.
- TCP messages make their way across the internet from one computer to another. UDP is not connection-based, so one program can send lots of packets to another.
- TCP rearranges data packets in the specific order. UDP protocol has no fixed order because all packets are independent of each other.
- TCP is reliable as it guarantees delivery of data to the destination router.The delivery of data to the destination can't be guaranteed in UDP.
- UDP is a great option if you are gaming, streaming or using VoIP services. It may lose a packet or two but it won’t have a huge impact on your overall connection.

![TCP](../../blob/master/images/tcp.gif)  
![UDP](../../blob/master/images/udp.gif)

</p></details>

<li>TCP/IP</li>
<li>Templating languages</li>
<li>Unit testing vs. functional/integration testing</li>
<li>URL vs. URI</li>
<li>URL: Clean URL</li>
<li>Usability testing</li>
<li>UX</li>
<li>UX personas</li>
<li>UX user journey maps</li>
<li>Vector vs. raster images</li>
<li>Virtual DOM</li>
<li>Visual hierarchy</li>
<li>VMs vs. Containers</li>
<li>Web 2.0</li>
<li>Web components</li>
<li>Web workers</li>
<li>Web workers vs. Service worker</li>
<li>WebAssembly (WASM)</li>
<li>WebPack</li>
<li>WebSockets</li>
<li>Wireframe: are you familiar with any wireframing tools?</li>
<li>WordPress</li>
<li>WordPress vs. Drupal vs. Joomla</li>