# Virtual World
This application allows users to upload GLTF/GLB files from either local storage or Firebase and view them in the scene. It includes controls for manipulating light, offering 4 types of lights with options to change their position and color. Scene properties can be adjusted, such as showing the wireframe of the entire model, enabling autorotation, changing the background color, and displaying a grid with customizable size and divisions. Users can view the dimensions and mesh hierarchy of the model, play and pause animations, and interact with specific meshes. Upon selecting a mesh, users can see the mesh name and manipulate it by changing its color, wireframe, transparency, and adjusting its position, rotation, and scale along the x, y, and z axes. Edited models can be exported back to local storage or Firebase. Additionally, users can select and play animations in the scene and view the modified model in AR by loading it from Firebase.

## Tech Stack Used

- **React:** A JavaScript library for building user interfaces, providing a declarative and component-based architecture.
- **Three.js:** A powerful library for creating 3D graphics in the browser, used for rendering 3D models and scenes.
- **@react-three/fiber:** A React renderer for Three.js, enabling the creation of 3D scenes using React components.
- **@react-three/drei:** A collection of useful helpers and abstractions built on top of `react-three-fiber`, simplifying 3D development.
- **@google/model-viewer:** A web component that allows users to view and interact with 3D models in AR.
- **Firebase:** A comprehensive backend service providing real-time database, authentication, and storage solutions.
- **emailjs-com:** A JavaScript library for sending emails directly from the client-side, without the need for a backend.



## Clone the Repository
## Getting Started

To get a local copy of the project up and running, follow these steps:

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (which includes npm)

### Installation

1. **Clone the Repository:**

   Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/Mahanthb/virtual-world-project.git
2. **Navigate to the Project Directory:**
   Change into the project directory:

   ```bash
   cd virtual-world-project
3. **Install Dependencies:**
   Install the necessary dependencies using npm:

   ```bash
   npm install
4. **Start the Development Server:**
   Once the installation is complete, start the development server:

   ```bash
   npm start
5. **View the Application:**
   The application should automatically open in your default web browser. If it doesn't, go to http://localhost:3000 to view it.


## Contributors
#### Mahanth Kumar B
#### Nipunn



## Organization Contributor
**Fabrik** is an immersive technology company using AR/VR capabilities to solve machine simulation and installation/downtime challenges for enterprises. Fabrik aggregates knowledge and represents them visually for individuals or teams to resolve complex problems quickly and cost-effectively. We help customers transition from obsolete 2D interactions to 3D immersive experiences.
