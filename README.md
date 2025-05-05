# ImGui Project Template

This is a starter template for projects using [Dear ImGui](https://github.com/ocornut/imgui).

## Features

- Pre-configured build system (update as needed)
- Example ImGui window
- Easy to extend

## Rendering Backend

This template uses **OpenGL3 + SDL2** as the rendering backend for Dear ImGui.
You can change the backend by modifying the source and build configuration as needed.

## Getting Started

1. **Clone the repository:**
   ```
   git clone <your-repo-url>
   ```

2. **Install dependencies:**
   - Make sure you have a C++ compiler and CMake installed.
   - Compilation was tested on **Windows** using the **x64 MSVC compiler**.

3. **Build the project:**
   ```
   mkdir build
   cd build
   cmake ..
   cmake --build .
   ```
   - The MSVC compiler will create a `Debug` folder inside `bin` containing the executable.

4. **Copy SDL2.dll:**
   - Copy `bin/SDL2.dll` to the `bin/Debug` folder before running the executable.

5. **Run the application:**
   - The executable will be in the `bin/Debug` directory.

## Customization

- Edit the source files in `src/` to add your own ImGui windows and logic.

## License

This template is provided as-is. Add your own license as appropriate.
