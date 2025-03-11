# Travel&Track

Travel&Track is a React application that allows users to explore cities from around the world. It provides information about various cities, including their locations on a map, details about each city, and the ability to create and delete cities.

## Screenshots

## Features

- View a list of cities and their locations on a map.
- Click on a city marker to see detailed information about the city.
- Create a new city by providing its details.
- Delete a city from the list.

## Prerequisites

Before running the Travel&Track application, ensure you have the following dependencies installed:

- [Node.js](https://nodejs.org) (version 14 or higher)

## Installation

1. Clone the repository:

```shell
git clone https://github.com/youssefarag2/Travel-Track-React-WebApp.git
```

2. Change into the project directory:

```shell
cd Travel-Track-React-WebApp
```

3. Install the dependencies:

```shell
npm install
```

## Configuration

The Travel&Track application uses a JSON server to provide city data. By default, the server is configured to run on `http://localhost:8000`. If you need to change the server URL, modify the `BASE_URL` constant in the `CitiesContext` component located in `src/contexts/CitiesContext.jsx`.

## Usage

1. Start the JSON server to serve the city data:

```shell
npm run server
```

2. Start the development server:

```shell
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000` to access the Travel&Track application.

## Authentication

The Travel&Track application includes authentication functionality. You can log in using the following credentials:

- Email: `jack@example.com`
- Password: `qwerty`

## Available Scripts

In the project directory, you can run the following scripts:

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the application for production.
- `npm run preview`: Serves the production build locally for preview.
- `npm run server`: Starts the JSON server to serve city data.


## Contributing

Contributions are welcome! Feel free to open issues and submit pull requests to help improve the Travel&Track application.

## Acknowledgements

The Travel&Track application uses the following open-source libraries:

- [React](https://reactjs.org)
- [React Router](https://reactrouter.com)
- [Leaflet](https://leafletjs.com)
- [React Leaflet](https://react-leaflet.js.org)
- [React DatePicker](https://github.com/Hacker0x01/react-datepicker)
- [JSON Server](https://github.com/typicode/json-server)
- [ESLint](https://eslint.org)


Thank you for using Travel&Track!
