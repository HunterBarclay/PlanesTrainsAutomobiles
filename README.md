# Planes, Trains, and Automobiles
The goal of this project is to try not only learn WASI/WASM, but also understand it's short comings, where it can improve, and overall the path that still lies ahead.

## Objective
Create a project that is ultimately formed from three independent projects, each with it's own language, all sharing the same WIT.

The culmination will then be brought into a web-app, where all three projects can be used seemless both by the web-app, and each other.

## Tasks

### World Descriptor
- [ ] Describe Planes, Trains, and Automobiles inside of a World Interface Type (WIT) file. Use this the generate bindings for other projects.

### Planes - Go Project
- [ ] Create a Go project, describing a plane type. This would have specific traits and functionality, the details of which would exclusively be written in Go.
- [ ] Planes will be created with a Person's name for a sample of storing data. 
- [ ] Planes will have operations for "drive home" and "take the redline" (Portland reference) to convert from a Plane to another transportation method.

### Trains - Rust Project
- [ ] Create a Rust project, describing a train type. This would have specific traits and functionality, the details of which would exclusively be written in Rust.
- [ ] Trains will be created with a Person's name for the sample of storing data.
- [ ] Trains will have operations for "drive home" and "fly to denver" to convert from a Train to another transportation method.

### Automobile - C++ Project
- [ ] Create a C++ project, describing a automobile type. This would have specific traits and functionality, the details of which would exclusively be written in C++.
- [ ] Automobiles will be created with a Person's name for the sample of storing data.
- [ ] Automobiles will have operations for "take the redline" and "flying to denver" to convert from an Automobile to another transportation method.

### Web-App
- [ ] Create SPA to use Planes, Trains, and Automobiles in a simple JS site.

# Note from Author
This will likely be on hold for a little while, as I'm closing out my summer internship, starting up my senior year at BSU, and am currently in the process of remaking [Qirby](https://github.com/HunterBarclay/Qirby/) from the ground up.
