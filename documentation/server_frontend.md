Run the server:
1. download and install Node.js
2. go to the folder
- `cd Backend-Frontend`
3. nodemon index
- This command automatically compiles the code for the server once changes are saved, so no need to rerun the new code manually.
4. Open the file of index.html under the folder of public in chrome browser.
5. Change the address that get request is sent to the address that actually runs the server.
6. Add the chrome extension:Allow-Control-Allow-Origin https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?utm_source=chrome-app-launcher-info-dialog
- This extension enables cross origin resource sharing, so that resources provided by the server could be transmitted to the front end.  

- Attached is a link talking about this issue, and it could be solved in other ways.  https://www.html5rocks.com/en/tutorials/cors/

TODO: Retrieve the data from the database and show it dynamically in a chart. https://canvasjs.com/javascript-charts/