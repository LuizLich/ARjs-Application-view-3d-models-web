# 3D Model Visualization on the Web with AR.js

This project utilizes the AR.js, A-Frame, and A-Frame Extras libraries for visualizing 3D models in AR (augmented reality) on the web, using a camera pointed at an image (HIRO).

## ⚙️Features

- Visualize different 3D models with Augmented Reality
- Web-compatible with any device that has camera access
- Switch between available models using a dropdown
- Fullscreen mode
- Customizable code available

## 🧠How to Use

### 📦Requirements

To use this application, you will need:

- A web browser with camera access (e.g., Chrome, Firefox, Safari)
- An internet connection to load the necessary libraries and models
- The HIRO marker image, which can be found in the repository or downloaded [here](https://raw.githubusercontent.com/LuizLich/ARjs-Application-view-3d-models-web/refs/heads/main/HIRO.jpg).

### 🔳Other 3D Models from Sketchfab

Sketchfab is a platform for publishing, sharing, and discovering 3D content. You can find a vast collection of 3D models there, many of which are available for download and can be integrated into this project. When searching for models, look for those with licenses that permit commercial or personal use, depending on your needs.

### Adding Other 3D Models to the Project

To add your own 3D models to this project, follow these steps:

1.  **Prepare your 3D model**: Ensure your model is in a web-friendly format such as GLTF (.gltf or .glb) or OBJ (.obj with .mtl). GLTF is generally recommended for its efficiency and PBR (Physically Based Rendering) support.
2.  **Place the model files**: Create a new folder within the `models` directory (or a similar structure) in your project and place your model files there.
3.  **Update `index.html`**: Open the `index.html` file and locate the A-Frame `<a-entity>` tags that define the 3D models. Add a new `<a-entity>` for your model, specifying its path and any desired properties (e.g., scale, position, rotation).
4.  **Update dropdown (optional)**: If you want your new model to be selectable via the dropdown menu, you'll need to modify the JavaScript code that populates the dropdown. This typically involves adding an option to the HTML `<select>` element and updating the event listener to load your model when selected.

## 💬Use Cases

This project can be used for various augmented reality applications, including:

-   **Educational purposes**: Visualize anatomical models, historical artifacts, or complex machinery in an interactive AR environment.
-   **Product showcasing**: Allow customers to preview products in their own space before purchasing, such as furniture or home decor.
-   **Interactive art installations**: Create dynamic and engaging art experiences that blend digital content with the physical world.
-   **Gaming and entertainment**: Develop simple AR games or interactive experiences.
-   **Training and simulation**: Provide hands-on training for tasks that require spatial understanding, like operating machinery or performing medical procedures.

## ❕Implementation Differences

This project is based on the reference implementations from AR.js-org. While it leverages the core functionalities of AR.js, A-Frame, and A-Frame Extras, there might be specific implementation choices or customizations made in this repository. These differences could include:

-   **Specific model loading mechanisms**: How 3D models are loaded and managed within the A-Frame scene.
-   **User interface elements**: Custom dropdowns or buttons for model selection and fullscreen toggling.
-   **Performance optimizations**: Any specific techniques applied to improve rendering performance or reduce latency.
-   **Custom A-Frame components**: Development of unique A-Frame components to extend functionality beyond the standard offerings of A-Frame Extras.

For detailed insights into the implementation, it is recommended to review the source code, particularly `index.html` and any associated JavaScript files.

## ✔️Conclusion

This project provides a straightforward and effective way to implement augmented reality experiences on the web using open-source technologies. By combining the power of AR.js for AR capabilities, A-Frame for declarative 3D scene creation, and A-Frame Extras for additional components, developers can quickly build interactive AR applications that are accessible directly through a web browser. The flexibility of these libraries allows for easy integration of custom 3D models and adaptation to various use cases, making it a valuable starting point for anyone interested in web-based augmented reality.

## 📱Contact me
<a href="https://discord.com/channels/@LuizLich#5096"><img img width = '32px' align= 'center' src="https://logodownload.org/wp-content/uploads/2017/11/discord-logo-7-1.png"></a>
<a href = 'https://www.github.com/LuizLich'> <img width = '32px' align= 'center' src="https://icon-library.com/images/github-icon-white/github-icon-white-6.jpg"/></a>
<a href = 'https://www.instagram.com/luiz.lewiss/'> <img width = '32px' align= 'center' src="https://www.freepnglogos.com/uploads/instagram-icon-png/instagram-icon-suzem-limited-make-known-20.png"/></a>
<a href = 'https://www.linkedin.com/in/luiz-felipe-terra-da-silva/'> <img width = '32px' align= 'center' src="https://cdn-icons-png.flaticon.com/512/179/179330.png"/></a> 
<a href = 'https://br.pinterest.com/luizlewiss/_saved/'> <img width = '32px' align= 'center' src="https://cdn-icons-png.flaticon.com/512/145/145808.png"/></a>

<p>📫 Email: luiz.terrasilva27@gmail.com</p>
