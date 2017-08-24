# shot-caller

Today we're going to create an API that lets us keep track of a list of kids and a list of items, and allows us to keep track of which items have been 'called' by a child. The API should allow the following actions:

- List out all children
- List out all items, including which child has called it (if any)
- Reserve / 'call' an item
- Unreserve an item (for the generous youngster)

An item cannot be 'called' by more than one child at a time, and if an item has already been 'called' then additional calls will have no effect.

Your goal is to create a JSON-based API that provides the above features, and to build a simple frontend that makes use of the API. Your application should include:

1. Create four separate Hapi routes that provide the functionality specified above (one for each bullet).
2. Enable cors on all routes (see here).
3. Store your list of children and items in MongoDB using Mongoose.
4. Create an HTML and JS frontend that uses AJAX to GET and POST data to the API -- think fetch here.
5. Your frontend should display a list of all children, as well as a list of all items (the latter including which child if any has reserved it).
6. Create some way for children to reserve and unreserve items from the frontend.

Hard Mode: 
Automatically update the screen every five seconds.
