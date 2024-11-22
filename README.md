# Virtual Try-On: AR Sunglasses

This project enables users to virtually try on sunglasses using a webcam. It combines the power of TensorFlow.js, Three.js, and Next.js for an interactive augmented reality experience.

---

## Features

- Real-time face detection and landmarks.
- Dynamic sunglasses positioning and scaling based on face dimensions.
- Built using **Next.js**, **TensorFlow.js**, and **Three.js**.
- Responsive and interactive interface.

---

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm (comes with Node.js)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Istiak-A-Tashrif/virtual-sunglasses-try-on.git
   cd virtual-sunglasses-try-on
   npm install -f
   npm run dev

   ```

## File Structure

```
.
├── public/
│ └── images
├── src/
│ ├── components/
│ └── VirtualTryOn.tsx # Main AR component
├── README.md # Project documentation
├── package.json # Node.js project configuration
└── next.config.js # Next.js configuration
```

## Troubleshooting

### Image Loading Error

- Ensure the `sunglasses.png` file is located in the `public` folder.
- Verify the path by navigating to [http://localhost:3000/sunglasses.png](http://localhost:3000/sunglasses.png) in your browser.

### WebGL Errors

- Ensure your browser supports WebGL. Check compatibility [here](https://get.webgl.org/).

### Camera Permissions

- Allow your browser to access the camera when prompted.

---

## Technologies Used

- **Next.js**: Framework for building React applications.
- **TensorFlow.js**: Face detection and landmark estimation.
- **Three.js**: Rendering 3D models and textures.
- **Webcam.js**: Camera integration.

---

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

## Contribution

Feel free to open issues or submit pull requests for improvements or bug fixes.

---

## Author

**Istiak Ahmed Tashrif**: Developer passionate about AR/VR and web technologies.
