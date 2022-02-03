### 1. SSR vs CSR
- **SSR (Server Side Rendering)** : request new page to server and refresh the page every request

    - faster initial loading
    - lot of pressure to server

- **CSR (Client Side Rendering)** : manages the routing dynamically without refreshing the page every time the client requests a different route
    - rich interaction
    - not suitable for SEO


#### Difference
- main difference between CSR and SSR is **where** the page is rendering.

![ssr_vs_csr](/arwensookim/img/ssr_and_csr_3.png)


***
### 2. How Backend and Frontend communicate?
- front-end and back-end communicate with each other via **Http Requests**. Front-end will entered data to the backend and the back-end might then again validate that data and finally sotred it in some database. 
    - user enters a URL(makes the browser go and requiet it)
    - browser reads the incoming HTML -> request HTML request (it happens while loading a website)
    - user clicks on link, webpage is loaded and rendered. The browser knows that they need to navigate to new page and requests the corresponding URL.
    - JavaScript is executed on the site, and want sto have some data loaded in the background. Requests are being made, doesn't reload the whole page(AJAX). 


***
### 3. Difference between _Functional Component_ and _Class Component_?
- **Functional Components**: Simply Javascript functions. Hooks are used in Functional Component to use/manage state and other React features. Stateless component with no render function.
- **Class Component**: require us to extend from React. **MUST** have render() methods to return.

***
