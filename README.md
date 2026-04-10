# StegoSafe: Invisible Digital Watermarking

### 🚀 Project Overview
StegoSafe is an Open Innovation project built for **VIbehacks 2.0**. It addresses the issue of digital art theft by embedding invisible, encrypted copyright data directly into image pixels using **LSB (Least Significant Bit) Steganography**.

Unlike traditional metadata (which can be stripped), StegoSafe modifies the actual binary data of the image, making the watermark an intrinsic part of the file.

### 🛠️ Tech Stack
- **Backend:** Python 3.10+
- **Algorithm:** Custom LSB Bitwise Manipulation
- **Framework:** Flask (Server-side rendering)
- **Image Processing:** Pillow (PIL)
- **Frontend:** HTML5, Tailwind CSS, JavaScript

### ⚙️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kartikeysingh2727-beep/StegoSafe-OpenInnovation.git
   cd StegoSafe-OpenInnovation
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python main.py
   ```

4. **Open in browser:**
   Visit `http://127.0.0.1:5000` in your web browser.

### 🎯 How to Use

1. **Access the Terminal:** Click "ACCESS TERMINAL" on the opening page
2. **Encrypt Data:** Upload an image and enter your secret message, then click "ENCRYPT DATA"
3. **Decrypt Data:** Upload the encrypted image to extract the hidden message

### 🔮 Future Scope

- AES-256 Encryption for the hidden text
- Support for Audio Steganography (.wav files)
- Blockchain integration for immutable ownership proof
- Mobile app version
- Batch processing capabilities

### 📁 Project Structure

```
StegoSafe-OpenInnovation/
├── main.py                 # Flask application with steganography logic
├── requirements.txt        # Python dependencies
├── README.md              # Project documentation
├── .gitignore             # Git ignore rules
├── templates/             # HTML templates
│   ├── opening.html       # Landing page
│   └── terminal.html      # Main application interface
└── uploads/               # Temporary file storage (auto-created)
```

### 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


Built with ❤️ for VIbehacks 2.0
