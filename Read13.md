# Local Storage

### LOCAL STORAGE HACKS BEFORE HTML5

In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called **DHTML Behaviors**, and one of these behaviors was called **userData**.

**User data** allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.) IE does not present any form of permissions dialog, and there is no allowance for increasing the amount of storage available.

### INTRODUCING HTML5 STORAGE

What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.”

**What is HTML5 Storage?**

 it’s a way for web pages to store named key/value pairs locally, within the client web browser.
 
 **Like cookies:** this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.
 
 **Unlike cookies:** this data is never transmitted to the remote web server (unless you go out of your way to send it manually).
 
Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.
 
Which browsers? Well, the latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer!

![](storage.PNG)

From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.

![](storage2.PNG)

Instead of writing this function yourself, you can use Modernizr to detect support for HTML5 Storage.

```
if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
```












