# Advanced QR Code Generator

A feature-rich web application for creating customized QR codes with various styling options, including colors, borders, icons, and different dot and corner styles. Users can save their QR codes for later use, download them in multiple formats, and manage their saved QR codes.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Customizable QR Codes**:
  - Choose from different sizes (Small, Medium, Large, Extra Large).
  - Select file formats (PNG, JPEG, SVG).
  - Customize foreground and background colors.
  - Apply various dot styles (Square, Dots, Rounded).
  - Customize corner styles (Square, Rounded, Extra Rounded).
  - Add decorative borders (Solid, Dashed, Dotted, Double, Groove, Ridge) with customizable color and width.
  - Embed emojis or custom icons in the center of the QR code with adjustable size.

- **Save and Manage QR Codes**:
  - Save generated QR codes to local storage with custom names.
  - View, load, download, or delete saved QR codes.
  - Persistent storage of QR code configurations for easy reuse.

- **User Interface**:
  - Responsive design for desktop and mobile devices.
  - Dark and light theme support with automatic detection based on system preferences.
  - Intuitive tabbed interface for generating and managing QR codes.
  - Tooltips for better user guidance.
  - Loading indicators and success feedback for actions.

- **Accessibility**:
  - Semantic HTML and ARIA attributes for improved accessibility.
  - Keyboard navigation support.

## Demo
Try the live demo [here](https://your-demo-link.com) (replace with your deployed link).

## Installation
To run the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/advanced-qr-code-generator.git
   cd advanced-qr-code-generator
   ```

2. **Serve the Application**:
   Since this is a static web application, you can serve it using any local server. For example, using Python's HTTP server:
   ```bash
   python -m http.server 8000
   ```
   Alternatively, use a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code.

3. **Open in Browser**:
   Navigate to `http://localhost:8000` in your web browser.

No additional dependencies or build steps are required, as the project uses CDN-hosted libraries.

## Usage
1. **Generate a QR Code**:
   - Navigate to the "Generate QR" tab.
   - Enter a URL or text in the content field.
   - Customize the QR code using the available options (size, format, style, colors, border, icon).
   - Click "Generate QR Code" to create the QR code.
   - Optionally, save the QR code by providing a name and clicking "Save QR Code".
   - Download the QR code in your preferred format by clicking "Download".

2. **Manage Saved QR Codes**:
   - Switch to the "Saved QR Codes" tab to view all saved QR codes.
   - Use the "Load" button to populate the generator with a saved QR code's settings.
   - Use the "Download" button to download a saved QR code.
   - Use the "Delete" button to remove a saved QR code.

3. **Toggle Theme**:
   - Click the theme toggle button (top-right corner) to switch between light and dark modes.

## Technologies
- **HTML5**: For the structure of the application.
- **CSS3**: For styling, including custom properties, responsive design, and animations.
- **JavaScript**: For interactivity and QR code generation logic.
- **QRCode.js**: Library for generating QR codes ([qrcodejs](https://github.com/davidshimjs/qrcodejs)).
- **Font Awesome**: For icons ([Font Awesome](https://fontawesome.com)).
- **Local Storage**: For persisting saved QR codes.

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them with a descriptive message:
   ```bash
   git commit -m "Add your feature description"
   ```
4. Push your changes to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request with a detailed description of your changes.

Please ensure your code follows the project's coding style and includes appropriate tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
