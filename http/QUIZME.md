# HTTP

---
Status code `200` meaning is:

1. Internal Server Error
1. * OK
1. Bad Request

---
HTTP requests can be initiated by:

1. server only
1. * client only
1. both

---
Which of these URL's are invalid?

1. https://developer.mozilla.org
1. https://developer.mozilla.org/en-US/docs/Learn/
1. https://developer.mozilla.org/en-US/docs/Learn
1. * https://developer.mozilla.org?q=URL/en-US/search

---
Why `https` instead of `http` of must be used?

1. communication over `http` is encrypted
1. * communication over `https` is encrypted
1. * `https` improves search engine ranking
1. `https` is faster than `http`

---
What is the correct usage of query parameters?

1. * `...?key1=value1&key2=value2`
1. `...?key1=value1?key2=value2`
1. `...&key1=value1&key2=value2`
1. `...&key1=value1?key2=value2`

---
Which of the following are not going to be sent to the server?

`https://codelex.io/path?key=value#anchor`

1. `path`
1. `key=value`
1. * `anchor`
1. url is invalid

---
Which of these are not request methods?

1. GET
1. * UPDATE
1. * INSERT
1. HEAD

---
What is the purpose of HTTP request methods?

1. to send headers properly
1. to get response status code
1. * to indicate desired action on the resource

---
What are `1xx` status code group?

1. * Information responses
1. Successful responses
1. Redirection messages
1. Client error responses
1. Server error responses

---
What are `2xx` status code group?

1. Information responses
1. * Successful responses
1. Redirection messages
1. Client error responses
1. Server error responses

---
What are `3xx` status code group?

1. Information responses
1. Successful responses
1. * Redirection messages
1. Client error responses
1. Server error responses

---
What are `4xx` status code group?

1. Information responses
1. Successful responses
1. Redirection messages
1. * Client error responses
1. Server error responses

---
What are `5xx` status code group?

1. Information responses
1. Successful responses
1. Redirection messages
1. Client error responses
1. * Server error responses

---
What is the meaning of `500` status code?

1. Not Implemented
1. Bad Request
1. I'm teapot
1. * Internal Server Error

---
What is the meaning of `400` status code?

1. Found
1. * Bad Request
1. No Content
1. Internal Server Error

---
Header `user-agent` is passed:

1. from server to client
1. * from client to server
1. in both directions
1. there is no such header

---
Headers are used to:

1. * pass additional information in both directions
1. store cookies
1. pass additional information from client to server

---
HTTP is:

1. * `stateless`
1. `stateful`
1. both
1. none

---
Which of these can be solved by using `cookies`?

1. * Session management - logins, shopping carts, game scores, or anything else the server should remember
1. * Personalization - user preferences, themes, and other settings
1. * Tracking - recording and analyzing user behavior

---
How server can store cookie on the client?

1. by sending response header: `Cookie: {cookie-name}={cookie-value}`
1. by sending request header: `Set-Cookie: {cookie-name}={cookie-value}`
1. * by sending response header: `Set-Cookie: {cookie-name}={cookie-value}`
1. by sending request header: `Cookie: {cookie-name}={cookie-value}`

---
What is the meaning of `HttpOnly` cookie?

1. sent over only http
1. sent over only https
1. * inaccessible to JavaScript

---
What will be the output?

```javascript
document.cookie = "yummy_cookie"; 
document.cookie = "tasty_cookie=strawberry"; 
console.log(document.cookie);
```

1. `"tasty_cookie=strawberry"`
1. * `"yummy_cookie; tasty_cookie=strawberry"`
1. runtime error will be thrown
