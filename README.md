# 3D-OpenGL
A computer graphics final project for CS-330. This scene recreates a still life composition with a white ceramic vase, an orange, a book, and red mug on a wooden table. Features include custom texture mapping, multiple light sources, material properties, and interactive camera navigation (WASD + mouse controls).


# 3D Still Life Scene - Computer Graphics Project

## Overview
This project is a 3D still life scene recreated in OpenGL featuring a white vase, an orange, a book, and a red mug positioned on a wooden table with a brown wall background and soft lighting.

## How to Run
1. Extract the project folder
2. Open the solution file in Visual Studio
3. Ensure all texture files are in the correct "textures" folder
4. Build and run the project
5. Use the following controls to navigate:
   - **Q** - Move up
   - **E** - Move down
   - **W** - Move forward
   - **S** - Move backward
   - **A** - Move left
   - **D** - Move right
   - **Mouse** - Look around
   - **Scroll Wheel** - Adjust movement speed (scroll up to slow down, scroll down to speed up)

## Design Approach

### How do I approach designing software?
My approach to software design begins with understanding the end goal and breaking it down into manageable components. For this project, I started by analyzing a reference still life photograph and identifying the core elements needed: the objects themselves, their materials and textures, lighting, and camera controls. I believe in designing with modularity in mind so that each component can be developed, tested, and debugged independently before being integrated into the complete scene.

### What new design skills has your work on the project helped you to craft?
This project helped me develop several new design skills:
- **3D spatial reasoning**: Understanding how to position and scale objects in a three-dimensional space
- **Material design**: Creating realistic material properties like ceramic, glossy, and wood finishes
- **Texture mapping**: Applying 2D images to 3D surfaces and adjusting UV coordinates
- **Lighting design**: Arranging multiple light sources to achieve a natural, soft lighting effect
- **Complex shape construction**: Combining primitive meshes to form complex objects like the vase and mug

### What design process did you follow for your project work?
I followed an iterative design process:
1. **Planning**: Selected a reference image and identified required objects
2. **Proposal**: Outlined the scope and technical requirements
3. **Milestone 1**: Project Proposal
4. **Milestone 2**: Beginning a 3D Scene
5. **Milestone 3**: Interactivity in a 3D Scene
6. **Milestone 4**: Texturing Objects in a 3D Scene
7. **Milestone 5**: Lighting Complex Objects
8. **Final polish**: Final Project Submission

### How could tactics from your design approach be applied in future work?
The modular design approach I used—separating texture management, material definitions, lighting setup, and rendering into distinct functions—can be applied to any future graphics project or even general software development. Breaking complex problems into smaller, reusable components is a universal strategy that improves code maintainability and scalability. Additionally, the iterative milestone approach ensures steady progress and early detection of issues.

## Development Strategies

### How do I approach developing programs?
I approach program development with a focus on incremental progress and continuous testing. Rather than attempting to build everything at once, I prefer to implement one feature at a time, test it thoroughly, and then build upon it. This prevents overwhelming complexity and makes debugging more manageable.

### What new development strategies did you use while working on your 3D scene?
- **Modular function design**: Created specialized functions for textures, materials, lighting, and transformations
- **Resource management**: Implemented proper loading and cleanup of textures 
- **Shader-based rendering**: Utilized shader programs for flexible material and lighting control
- **Camera navigation system**: Developed intuitive keyboard and mouse controls for scene exploration

### How did iteration factor into your development?
Iteration was crucial to my development process. Each object went through multiple iterations:
- The **vase** required combining a torus, cylinder, tapered cylinders, and sphere, with each piece needing position adjustments
- The **mug** needed careful placement of the handle pieces to achieve the right angle and connection
- **Lighting** required multiple iterations to balance the directional light and point light for soft shadows
- **Textures** were adjusted multiple times to ensure proper scaling and alignment on objects

### How has your approach to developing code evolved throughout the milestones, which led you to the project's completion?
Initially, I approached each milestone as a separate task, but as the project progressed, I began to see how they interconnected. By the final milestone, I was thinking  about how lighting affects textures, how materials interact with light, and how camera positioning impacts the overall composition. My code evolved from simple, sequential instructions to a more organized structure with clear separation of concerns.

## Impact on Goals

### How can computer science help me in reaching my goals?
Computer science provides the foundational problem-solving skills and technical knowledge needed to bring creative ideas to life. Whether I pursue game development, simulation, or software engineering, the ability to break down complex problems, write efficient code, and create intuitive user experiences will be invaluable. This project specifically has strengthened my understanding of how mathematics, programming, and artistry intersect.

### How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?
Computational graphics have deepened my understanding of linear algebra (transformations, vectors, matrices) and physics (lighting, reflection) in practical ways. These concepts are fundamental to advanced computer science courses in areas like machine learning, computer vision, and simulation. The hands-on experience of implementing these mathematical concepts has solidified my understanding far more than theory alone could.


## Project Files
- Source code files (.cpp, .h)
- Texture images (/textures folder)
- Project documentation
- Screenshots of final render

## Acknowledgments
Course resources and weekly readings from CS-330 Computational Graphics and Visualization with professor Brian Battersby
