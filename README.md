This project is a Demo APP using React, Typescript, ASP.net Core 3 and webpack to retrive a list of events or single event from EONET API

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).


## Available Scripts

In the project directory, you can run:

### `Start the Project`

In the project folder 
run 'dotnet run' will start the asp.net core API server

In the ClientAPP folder 
run 'npm run start' will start the webpack-dev-server

Open [http://localhost:3000] for the client side
Open [http://localhost:5000] to start the server side.


### `API end point`

http://localhost:5000/api/ListEvents  Returns a list of events
http://localhost:5000/api/GetEvent?link=[eventlink]       Returns a single event detail given the event link

### `Functionalities includes`
1. Retrive a list events from [https://eonet.sci.gsfc.nasa.gov/docs/v2.1#eventsAPI] includes both closed and open events
   Display the list events in the React-Table
2. Retive a single event when click a row in the Table. The event detail will be displayed on top of the table.
3. If the event is closed, the particular row will be grey out.
4. You can sort each table column
4. You can filter Category by input box on top of the displayed table.
