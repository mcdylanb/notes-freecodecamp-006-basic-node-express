Routes:


> Middleware functions are functions that take 3 arguments: the request object, the response object, and the next function in the application’s request-response cycle.

Middleware
- we can return a response when particular condition meets
- to use it in the root level (aka the start of the script or the main loop)
```javascript
app.use(middlewareFunction)
```
- we can also use with http methods for example:
```javascript
app.post(middlewareFunction)
```
- when using middleware remember to use `.next()`
- 
# Questions:
What are applications request-response cycle?

Under middlewares what does root level stand for?

