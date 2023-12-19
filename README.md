In summary, this code creates a simple REST API using Node.js and Express.js to interact with the Star Wars API (SWAPI). It includes endpoints for searching and sorting data in different categories (people, planets, starships). The code is organized with helper functions to handle data formatting and API requests. It provides JSON responses with organized and readable data based on the specified categories and sorting parameters.
How to run code in local:
Step 1: Enter node index.js in terminal
Step2: Open chrome and enter different url for search and sort result.
Example: For Sort: http://localhost:3000/sort?category=planets&field=climate
         For Search: http://localhost:3000/search?category=people&q=luke
         For Search and Sort: http://localhost:3000/search?category=people&q=luke&sort=name
