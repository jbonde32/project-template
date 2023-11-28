OWNER: Jeremiah Bonde
Last Edit: 7/12/2023

# Introduction 
TODO: Give a short introduction of your project. Let this section explain the objectives/purpose behind this project. 

# To Use: 
TODO: Fork this repository and rename the project. Project names should be all lowercase and connected by a dash.

Folder Structure Conventions
============================

> Folder structure options and naming conventions for demo vehicle projects

### Top-level directory layout

    .
    ├── build                   # Compiled output files (alternatively `dist`)
    ├── doc                     # Documentation files (alternatively `docs`)
    ├── res                     # Static resource files
    ├── src                     # Source files (alternatively `lib` or `app`)
    ├── tests                   # Automated tests (alternatively `spec` or `test`)
    ├── tools                   # Service tools and utilities
    └── README.md

> Use short lowercase names at least for the top-level files and folders except
> `README.md`

### Source files

Place the files required from the demo project inside the
`src` folder. If a GUIDE project, this can be found in the "project view"

    .
    ├── ...
    ├── src                     # Source files (alternatively `lib` or `app`)
    │   ├── component1          # Folder containing component 1 files
    │   ├── component2          # Folder containing component 2 files (if needed)
    │   └── ...                 # ...
    └── ...

### Build files

Place the output of the compiled files inside the `build` folder. If using GUIDE this is found using project view and typically includes your .lhx file.

    .
    ├── ...
    ├── build                   # Compiled output files (alternatively `dist`)
    │   ├── component1.lhx      # Component 1 downloadable
    │   ├── component2.1hx      # Component 2 downloadable (if needed)
    │   └── ...                 # ...
    └── ...

### Tools and utilities

Place any service tools or utilities in the `tools` folder that was created or used in order to debug the demo.

### Static resource files

Place any static resources inside of the `res` folder. This typically includes your images.

### Documentation

Place any supporting docs inside the `docs` folder. This usually includes and FAQ, getting started docs, etc. Schematics and project files will still remain in sharepoint. A markdown cheatsheet is located in there currenlty to help with `README` files.

### Automated tests

Most likely not applicable to our demo vehicles
