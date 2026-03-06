# Retroarch Shader Editor

Retroarch Shader Editor is an online WebGL editor for creating and testing RetroArch shaders directly in your browser. It allows you to import a game screenshot, preview effects in real-time, and easily manipulate shader parameters defined via pragmas.

---

## Features

- Live editing of GLSL shaders (fragment and vertex).
- Import images to test your shaders on screenshots.
- Support for #pragma parameter to automatically create sliders for your parameters.
- Real-time visualization on a WebGL canvas.
- Compatible with RetroArch shaders using `VERTEX`, `TextureSize`, `InputSize`, and `MVPMatrix`.

---

## Installation / Usage

1. Clone the repository

```bash
git clone https://github.com/<votre-username>/Retroarch-Shader-Editor.git
cd Retroarch-Shader-Editor
```

2. Open in a browser

Open `index.html` in a modern browser (Chrome, Firefox, Edge).

3. Import an image

Click "Import Image" to load a texture to test your shader.

4. Edit the shader

Modify the GLSL code in the textarea.

Parameters defined with `#pragma parameter` will automatically appear as sliders.

5. Compile and view the result
- Click “Compile” or use live compilation with auto-update.