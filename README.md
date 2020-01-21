This project is a Demo APP using React, Typescript, ASP.net Core 3 and webpack to retrive a list of events or single event from EONET API



## Available Scripts


### `Build the Project`
In the Project folder EventAPI
Run 'dotnet build' to build the asp.net core api project

In the ClientApp folder
Run 'npm install' to install all the packages from package.json

Run 'npm start build' to build client app

### `Start the Project`

In the project folder 
run 'dotnet run' will start the asp.net core API server

In the ClientAPP folder 
run 'npm run start' will start the webpack-dev-server

Open [http://localhost:3000] for the client side
Open [http://localhost:5000] to start the server side.


### `API end point`

http://localhost:5000/api/ListEvents  Returns a list of events
http://localhost:5000/api/GetEvent?link=https://eonet.sci.gsfc.nasa.gov/api/v2.1/events/EONET_4557      Returns a single event detail given the event link

### `Functionalities includes`
1. Retrive a list events from [https://eonet.sci.gsfc.nasa.gov/docs/v2.1#eventsAPI] includes both closed and open events
   Display the list events in the React-Table
2. Retive a single event when click a row in the Table. The event detail will be displayed on top of the table.
3. If the event is closed, the particular row will be grey out.
4. You can sort each table column
5. You can filter Category by input box on top of the displayed table.
