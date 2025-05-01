# Engine Design (fluid)
This document will lay out the way in which I want to architect the engine. This document will change during development.

## Overall Architecture
The engine should be written targeting flexibility and performance in C++.

Window management and input will be handled by SDL. Rendering will be done with Vulkan.

 The engine will utilize an entity component system.

The engine should be seperate of a project. A project may make changes to the engine by creating a branch of it. These changes could then possibly be merged with the main engine.