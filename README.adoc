[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18830476)
# c3b-template
c3b - GitHub Repository for HPC Training
This repository serves as the template used by GitHub Classroom to generate personalized development environments for HPC training sessions. It is pre-configured with the tools and libraries needed for MPI application development and testing.

Overview
The c3b-template repository is designed to:

Provide every trainee with an identical, reproducible development setup.

Facilitate hands-on exercises in MPI application development.

Include essential software such as:

Ubuntu 24.04 as the base environment

MPI libraries (e.g., OpenMPI)

CMake, Ninja, and G++ for building applications

Python3 and associated development tools

Boost libraries for testing and serialization

Getting Started
For Trainees
When you accept an assignment via GitHub Classroom, a personalized repository is created based on this template. Then:

Open Your Codespace: Click the Code button in your repository and choose Open with Codespaces. Your development environment will be automatically set up with all required tools.

Compile and Test the Code: Follow the instructions below to compile and run tests.

For Instructors
Uniform Environment
Use this template to ensure all trainees receive a consistent environment.

Customization
Modify the repository as needed to include additional examples or exercises tailored to your training session.

Integration
GitHub Classroom automates repository creation from this template, simplifying distribution and management.

Building and Testing the Code
This repository uses CMake with preset configurations for building and testing the MPI application.

Compiling the Code
To compile the code locally, follow these steps:

# Configure the build system using CMake presets
cmake --preset default

# Build the project using CMake presets
cmake --build --preset default
Running the Tests
After building the code, you can run the tests to verify that everything is working correctly:

# Run tests using CTest with the preset configuration
ctest --preset default
The testing framework integrated in this repository ensures that the MPI application behaves as expected.

Additional Resources
GitHub Classroom Documentation

GitHub Codespaces Documentation

CMake Presets Documentation

OpenMPI Documentation

Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. For major changes, open an issue first to discuss your ideas.

License
This repository is licensed under the BSD License. See the LICENSE file for details.