---
Status code `200` meaning is:

a) Internal Server Error
b*) OK
c) Bad Request

---
HTTP requests can be initiated by:

a) server only
b*) client only
c) both

---
Which of these URL's are invalid?

a) https://developer.mozilla.org
b) https://developer.mozilla.org/en-US/docs/Learn/
c) https://developer.mozilla.org/en-US/docs/Learn
d*) https://developer.mozilla.org?q=URL/en-US/search

---
Why `https` instead of `http` of must be used?

a) communication over `http` is encrypted
b*) communication over `https` is encrypted
c*) `https` improves search engine ranking
d) `https` is faster than `http`

---
What is the correct usage of query parameters?

a*) `...?key1=value1&key2=value2`
b) `...?key1=value1?key2=value2`
c) `...&key1=value1&key2=value2`
d) `...&key1=value1?key2=value2`

---
Which of the following are not going to be sent to the server?

`https://codelex.io/path?key=value#anchor`

a) `path`
b) `key=value`
c*) `anchor`
d) url is invalid

---
Which of these are not request methods?

a) GET
b*) UPDATE
c*) INSERT
d) HEAD

---
What is the purpose of HTTP request methods?

a) to send headers properly
b) to get response status code
c*) to indicate desired action on the resource

---
What are `1xx` status code group?

a*) Information responses
b) Successful responses
c) Redirection messages
d) Client error responses
e) Server error responses

---
What are `2xx` status code group?

a) Information responses
b*) Successful responses
c) Redirection messages
d) Client error responses
e) Server error responses

---
What are `3xx` status code group?

a) Information responses
b) Successful responses
c*) Redirection messages
d) Client error responses
e) Server error responses

---
What are `4xx` status code group?

a) Information responses
b) Successful responses
c) Redirection messages
d*) Client error responses
e) Server error responses

---
What are `5xx` status code group?

a) Information responses
b) Successful responses
c) Redirection messages
d) Client error responses
e*) Server error responses

---
What is the meaning of `500` status code?

a) Not Implemented
b) Bad Request
c) I'm teapot
d*) Internal Server Error

---
What is the meaning of `400` status code?

a) Found
b*) Bad Request
c) No Content
d) Internal Server Error

---
Header `user-agent` is passed:

a) from server to client
b*) from client to server
c) in both directions
d) there is no such header

---
Headers are used to:

a*) pass additional information in both directions
b) store cookies
c) pass additional information from client to server

---
HTTP is:

a*) `stateless`
b) `stateful`
c) both
d) none

---
Which of these can be solved by using `cookies`?

a*) Session management - logins, shopping carts, game scores, or anything else the server should remember
b*) Personalization - user preferences, themes, and other settings
c*) Tracking - recording and analyzing user behavior

---
How server can store cookie on the client?

a) by sending response header: `Cookie: {cookie-name}={cookie-value}`
b) by sending request header: `Set-Cookie: {cookie-name}={cookie-value}`
c*) by sending response header: `Set-Cookie: {cookie-name}={cookie-value}`
d) by sending request header: `Cookie: {cookie-name}={cookie-value}`

---
What is the meaning of `HttpOnly` cookie?

a) sent over only http
b) sent over only https
c*) inaccessible to JavaScript

---
What will be the output?

```javascript
document.cookie = "yummy_cookie"; 
document.cookie = "tasty_cookie=strawberry"; 
console.log(document.cookie);
```

a) `"tasty_cookie=strawberry"`
b*) `"yummy_cookie; tasty_cookie=strawberry"`
c) runtime error will be thrown
