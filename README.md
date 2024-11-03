# Object3D

Object3D is a simple 3D rendering demo built using Java Swing. The project displays a rotating 3D object composed of colored triangles that can be manipulated using horizontal and vertical sliders.

## Features

- **3D Object Rendering:** The application renders a simple 3D object composed of triangles.
- **Rotation Controls:** Users can rotate the object horizontally and vertically using sliders.
- **Z-Buffer Implementation:** Proper depth calculation using a z-buffer to ensure correct triangle rendering.

## Project Structure

- **Main Class:**
  - `Object3D`: The entry point of the application that sets up the JFrame, sliders, and the render panel.
  
- **Supporting Classes:**
  - `Matrix3`: A class for 3x3 matrices, used for transforming the vertices of the 3D object.
  - `Vertex`: Represents a point in 3D space.
  - `Triangle`: Represents a triangle in 3D space, composed of three vertices and a color.

## How to Run

1. **Clone the Repository:**

    ```bash
    [git clone https://github.com/rajtilak-2020/Object3D.git
    cd Object3D](https://github.com/rajtilak-2020/Java_Based_3D-Renderer.git)
    ```

2. **Compile the Java Files:**

    Use any Java compiler or IDE of your choice to compile the source files. 

    For example, using `javac`:

    ```bash
    javac Object3D.java
    ```

3. **Run the Application:**

    After compiling, run the `Object3D` class:

    ```bash
    java Object3D
    ```

    A window should open, displaying a 3D object that can be rotated using the sliders.

## Usage

- **Horizontal Rotation:** Use the bottom slider to rotate the object around the vertical axis.
- **Vertical Rotation:** Use the right-side slider to rotate the object around the horizontal axis.

## Dependencies

- **Java SE:** This project uses standard Java libraries and does not require any external dependencies.

## Contributing

If you want to contribute to this project, feel free to submit a pull request. You can also open issues for any bugs or feature requests.
