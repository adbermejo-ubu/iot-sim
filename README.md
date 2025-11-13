# IoT-Sim

This repository contains the IoT-Sim project, which emulates the behavior of an IoT device network for attack detection using artificial intelligence.

## Requirements

To run the simulator, you need to have at least Node.js 18.19.1 or higher and Angular 20.0.0 or higher installed on your system.

You can install Angular CLI globally using the following command:

```bash
npm install -g @angular/cli
```

To install the necessary project dependencies, run:

```bash
npm install
```

Running the Simulator

To run the simulator, use the following command:

```bash
npm run start
```

This will start the development server, and you can access the simulator in your web browser at `http://localhost:4200`.

## Building for Production

If you want to build the project for production, you can use the following command:

```bash
npm run build
```

This will generate the production files in the `dist/` directory of the project, which can be deployed to a web server. It is necessary to update the server base URL in the scripts of the `package.json` file before building the project so that it points to the correct server address where the simulator will be deployed.
