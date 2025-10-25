# warp-core-sdk
This is the SDK for the [Warp Core](https://github.com/gordonmcvey/warp-core-php) microframework.  It allows for you to develop and package your own add-ons for it without having to rely on the entire core framework as part of your package.  

It includes a set of interfaces that cover the following:
* 💻 Controllers/Request Handlers
* 🏭 Controller Factories
* ⚠️ Error Handlers
* 🧰 Middleware and providers
* 🔀 Routers and strategies

It also includes the set of exceptions that are expected to be thrown in Warp Core.

If you implement code against these interfaces it should be able to plug into Warp Core without any further modifications.
