# Image Steganography using LSB Technique
A web-based steganography application that allows users to hide and retrieve secret messages in images using the Least Significant Bit (LSB) technique. The backend is built with Python (Flask), while the frontend uses HTML, CSS, and JavaScript.

📂 Project Structure
graphql
Copy
Edit
📦 Image-Steganography  
 ┣ 📂 static/  
 ┃ ┣ 📜 script.js         # JavaScript logic  
 ┃ ┗ 📜 styles.css        # Stylesheet for UI  
 ┣ 📂 templates/  
 ┃ ┗ 📜 index.html        # Main web page  
 ┣ 📂 uploads/            # Uploaded images (input & encoded)  
 ┃ ┣ 🖼 input.png         # Original uploaded image  
 ┃ ┗ 🖼 encoded_image.png # Image with hidden message  
 ┣ 📜 LICENSE             # License file  
 ┣ 📜 app.py              # Flask application (backend logic)  
 ┣ 📜 requirements.txt     # Dependencies for the project  



## ✨Features

🔒 Secure Encryption

Hides a secret message inside an image using LSB steganography.

Encrypts the message with a user-provided key for enhanced security.

Saves the encoded image for later retrieval.

🔓 Reliable Decryption

Extracts the hidden message from an encoded image.

Requires the correct decryption key to access the original text.

🖥 Intuitive User Interface

Web-based UI built with HTML, CSS, and JavaScript for a smooth experience.

Supports drag-and-drop image upload and real-time encryption/decryption feedback.

📂 Secure & Efficient Storage

Uses metadata headers to store message length, ensuring precise extraction.

Keeps encrypted data intact without affecting the image’s visual quality.


## ⚙️Installation & Setup

### Prerequisites

Ensure you have Python 3.x installed.

1️⃣ Clone the Repository

git clone https://github.com/lalithanjaliaruna123/image-steganography.git
cd image-steganography

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Flask Server

python app.py

The server will start at http://127.0.0.1:5000/.


## 🚀Usage

## 1️⃣ Open the Web Interface

Navigate to http://127.0.0.1:5000/ in your browser.

## 2️⃣ Encode a Message

Upload an image.

Enter the secret message and a security key.

Click "Encode" to generate the steganographic image.

## 3️⃣ Decode a Message

Upload the encoded image.

Enter the correct security key.

Click "Decode" to reveal the hidden message.


## 🛠Tech Stack

Backend: Flask (Python)

Frontend: HTML, CSS, JavaScript

Libraries: OpenCV, NumPy, Pillow


## 📜License

This project is licensed under the MIT License.


## 🤝Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 👩‍💻Author

Sahithi Maddala
🔗 GitHub: https://github.com/Sahithi-Maddala
