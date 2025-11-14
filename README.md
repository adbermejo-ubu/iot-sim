# IoT-Sim: An Interactive Platform for Designing and Securing Smart Device Networks

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Version](https://img.shields.io/badge/Version-v1.0.4-blue.svg)

IoT-Sim is a lightweight, modular, and open-source tool designed to create, configure, and test attack detection models for Internet of Things (IoT) networks. It provides an interactive, client-side simulation environment that runs entirely in your browser, with no dedicated backend server required.

This platform was developed to address the lack of flexible, accessible simulation environments that allow researchers and students to replicate IoT scenarios and evaluate machine learning models under controlled, realistic conditions.

## Live Demo

You can access a running instance of the simulator here:

- **IoT-Sim Live Application:** [https://adbermejo-ubu.github.io/iot-sim/](https://adbermejo-ubu.github.io/iot-sim/)

## Key Features

- **Visual Network Design:** Interactively create and configure IoT network topologies. Add, edit, connect, and remove nodes like **Routers**, **IoT Devices**, and **PC Attackers**.
- **Traffic Simulation:** Simulate benign network traffic flows between connected devices.
- **Attack Generation:** Inject controlled cyberattacks, such as **Denial of Service (DoS)**, to test network resilience and detection models.
- **AI-Based Intrusion Detection:** Load your own pre-trained **TensorFlow.js** models to analyze network traffic in real-time and visualize intrusion detections.
- **Configurable Network Conditions:** Introduce network variability, such as **latency** and **bandwidth limitations**, to evaluate model performance under realistic conditions.
- **Client-Side Architecture:** Runs entirely in the user's browser, making it highly accessible and eliminating the need for expensive hardware or complex server deployments.
- **Extensible:** Users can import external scripts to add new custom commands or attack types, extending the simulator's capabilities.

## Getting Started

### Prerequisites

To run the simulator locally, you will need the following software installed:

- **Node.js:** `v18.19.1` or higher
- **Angular CLI:** `v20.0.0` or higher

You can install the Angular CLI globally using npm:

```bash
npm install -g @angular/cli
```

### Installation & Running

1. **Clone the repository:**

```bash
git clone https://github.com/adbermejo-ubu/iot-sim.git
cd iot-sim
```

2. **Install dependencies:**

```bash
npm install
```

3. **Run the development server:**

```bash
npm run dev
```

4. **Access the simulator:** Open your web browser and navigate to `http://localhost:4200`.

### Building for Production

If you want to build the project for a production environment, run:

```bash
npm run build
```

This command generates the production-ready files in the `dist/` directory.

> Before deploying, you may need to update the server base URL in the package.json scripts to point to the correct server address.

## Technical Stack

The simulator is built using the following technologies:

- **Core Framework:** Angular
- **Languages:** TypeScript, HTML, CSS
- **AI Models:** TensorFlow / TensorFlow.js
- **UI Styling:** Tailwind CSS , Spartan UI
- **Build System:** Node.js, npm, Angular CLI

To prepare your own AI models, you will need a separate environment with Python (>= 3.10, < 3.12) and TensorFlow (>= 2.15.0). Models must be converted to TensorFlow.js format (>= 4.22.0) using the tensorflowjs converter tool to be compatible with the simulator.

## Contributing

This is an open-source research project. Contributions are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

This publication is part of the **AI4SECIoT project** ("Artificial Intelligence for Securing IoT Devices"), funded by the National Cybersecurity Institute (INCIBE) of Spain.

This initiative is carried out within the framework of the Recovery, Transformation and Resilience Plan funds, financed by the **European Union (Next Generation)**.
