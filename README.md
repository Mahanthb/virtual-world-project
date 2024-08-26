# Virtual World
This application allows users to upload GLTF/GLB files from either local storage or Firebase and view them in the scene. It includes controls for manipulating light, offering 4 types of lights with options to change their position and color. Scene properties can be adjusted, such as showing the wireframe of the entire model, enabling autorotation, changing the background color, and displaying a grid with customizable size and divisions. Users can view the dimensions and mesh hierarchy of the model, play and pause animations, and interact with specific meshes. Upon selecting a mesh, users can see the mesh name and manipulate it by changing its color, wireframe, transparency, and adjusting its position, rotation, and scale along the x, y, and z axes. Edited models can be exported back to local storage or Firebase. Additionally, users can select and play animations in the scene and view the modified model in AR by loading it from Firebase.
## Tech stack used
React: For building the user interface.
Three.js: For rendering 3D models and scenes.
@react-three/fiber: A React renderer for Three.js.
@react-three/drei: A collection of useful helpers and abstractions for react-three-fiber.
@google/model-viewer: For AR model viewing and interactions.
Firebase: For backend services, including storage and real-time database.
emailjs-com: For sending emails directly from JavaScript.
## Clone the Repository
Open Terminal or Command Prompt:

On Windows: You can use Command Prompt, PowerShell, or Git Bash.
On macOS/Linux: Use the Terminal.
Navigate to the Desired Directory: Choose where you want to clone the repository on your local machine.

bash
Copy code
cd /path/to/your/directory
Clone the Repository:

Run the following command to clone the repository:

bash
Copy code
git clone https://github.com/Mahanthb/virtual-world-project.git
Navigate to the Project Directory:

After cloning, change into the project directory:

bash
Copy code
cd virtual-world-project
Install Dependencies:

Make sure you have Node.js and npm installed. Then, run the following command to install the necessary dependencies:

bash
Copy code
npm install
Start the Development Server:

After the installation is complete, start the development server:

bash
Copy code
npm start
Open the Project in Your Browser:

Once the server is running, the project should automatically open in your default web browser. If it doesn't, you can manually open it by navigating to http://localhost:3000 in your browser.
## Contributors
#### Mahanth Kumar B
Nipunn
## Organization Contributor
Fabrik is an immersive technology company using AR/VR capabilities to solve machine simulation and installation/downtime challenges for enterprises. Fabrik aggregates knowledge and represents them visually for individuals or teams to resolve complex problems quickly and cost-effectively. We help customers transition from obsolete 2D interactions to 3D immersive experiences.
