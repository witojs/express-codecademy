# express-codecademy
Challenge Project express js

## Challenge Project
Challenge project from codecademy express js section.
- Making route for GET /api/quotes/random, this route should send random quote data with response body
```
{
  quote: {/* quote object */}
}
```
- Making route for GET /api/quotes, this route should return all quotes said by the same person. For instance, the data set has multiple quotes for Grace Hopper, so GET /api/quotes?person=Grace Hopper should return an array of only those quotes. If there are no quotes for the requested person, send back an empty array.
```
{
  quotes: [ /* Array of requested quotes */ ]
}
```
- Making route for  POST /api/quotes, New quotes will be passed in a query string with two properties: quote with the quote text itself, and person with the person who is credited with saying the quote. This route should verify that both properties exist in the request query string and send a 400 response if it does not.
```
{
  quote: {/* new quote object */}
}
```
