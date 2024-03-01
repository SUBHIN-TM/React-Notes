# CDN (CONTENT DELIVERY NETWORK) 
* It's a system of distributed servers (network) that deliver pages and other web content to a user based on the geographic locations of the user. CDNs are designed to take the load off of the original server by caching content in multiple locations around the world, thus improving site performance and speed, reducing load times, and ensuring content is more readily available and stable during high traffic periods or internet congestion. They are widely used for delivering webpages, streaming videos, games, and other online content efficiently to users around the globe.

* When a user requests content from the website, the CDN dynamically determines the user's location and routes the request to the nearest server in the network. Then the server delivers the content to the user,

* in react cdn act as a bridge between the corefiles with browser



 # Same-Origin Policy (SOP)
Isolation: SOP prevents malicious websites from accessing sensitive data from another site. For example, if you're logged into your bank's website, SOP stops other websites you might visit simultaneously from making requests to the bank's website and accessing or manipulating your banking information.

# Cross-Origin Resource Sharing (CORS)
* Controlled Sharing: CORS provides a way for servers to control how their resources are shared across origins. By specifying which origins are allowed to access a resource, servers can expose data to some origins while keeping it restricted from others.

* In summary, the management of cross-origin requests through SOP, CORS, and other security measures is crucial for preventing cross-site scripting (XSS), data theft, and other web-based attacks, ensuring that the web remains a secure environment for users and developers.