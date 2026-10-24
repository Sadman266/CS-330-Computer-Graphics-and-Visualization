# CS-330-Computer-Graphics-and-Visualization

## How do I approach designing software?

When I design software, I like to break a larger problem into smaller pieces that I can work on individually. This project helped me apply that approach visually because I had to look at a 2D reference image and determine which basic 3D shapes could represent each object. I started with the cup and saucer and later added the table, notebook, pages, and pen. Thinking about objects as combinations of simpler shapes helped me understand how planning before coding can make a complicated problem more manageable.

My design process also involved a lot of experimentation. The cup and saucer were the most challenging because my first attempts did not look the way I expected. I tried different shapes, scales, rotations, and positions before finding a combination that worked better. Instead of trying to finish the entire scene at once, I worked on one part, tested it, and then continued. I can use this same approach in future projects by creating smaller components first and gradually combining them into a complete application.

## How do I approach developing programs?

One development strategy that became especially important during this project was iteration. I learned that getting code to compile successfully did not necessarily mean the visual result was correct. I frequently had to build the project, examine the rendered scene, adjust transformation values, and test again. This was especially useful when positioning the cup, saucer, handle, notebook, and pen.

My approach also became more organized as the milestones progressed. Instead of putting everything into one function, I used functions such as LoadSceneTextures(), DefineObjectMaterials(), SetupSceneLights(), and SetTransformations() to separate different responsibilities. This follows the DRY (Don't Repeat Yourself) programming principle because common operations can be reused instead of rewriting the same logic for every object. By the end of the project, I was thinking more about keeping the code modular and maintainable instead of only trying to make the final scene work.

## How can computer science help me in reaching my goals?

Computational graphics gave me another perspective on how programming can be used to create interactive applications. Before this course, much of my programming experience focused on areas such as application logic, data structures, testing, and software design. Working with C++ and OpenGL helped me better understand transformations, textures, lighting, shaders, cameras, and real-time user input. 

These skills can help me in future courses because I now have more experience working with a larger C++ project and debugging problems where the code may run correctly but the output still needs improvement. Professionally, the concepts from this course could apply to areas such as game development, simulation, visualization, interactive software, and other applications involving graphical interfaces. Even if I do not specialize in graphics development, understanding how 3D applications render scenes and respond to user input gives me a broader foundation as a software developer.
