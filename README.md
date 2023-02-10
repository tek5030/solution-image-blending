# Image blending with OpenCV
This is our proposed solution for the lab ["Image blending with OpenCV"](https://github.com/tek5030/lab-image-blending) in the computer vision course [TEK5030](https://www.uio.no/studier/emner/matnat/its/TEK5030/) at the University of Oslo.

Please see the [lab guide](https://github.com/tek5030/lab-image-blending/blob/master/README.md) for more information.

## Prerequisites
- [Ensure Conan is installed on your system](https://tek5030.github.io/tutorial/conan.html), unless you are not on a lab computer.
- Install project dependencies using conan:

   ```bash
   # git clone git@github.com:tek5030/solution-image-blending.git
   # cd solution-image-blending

   conan install . --install-folder=build --build=missing
   ```
- When you configure the project in CLion, remember to set `build` as the _Build directory_, as described in [lab_intro](https://github.com/tek5030/lab-intro/blob/master/cpp/lab-guide/1-open-project-in-clion.md#6-configure-project).
