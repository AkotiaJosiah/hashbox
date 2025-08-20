# Hashbox

Hashbox is a single-file offline toolkit for password hashing, encoding, decoding, and URL shortening.

## Features
- Text hashing (MD5, SHA-1, SHA-256, SHA-384, SHA-512)
- File hashing (MD5, SHA-1, SHA-256, SHA-384, SHA-512)
- HMAC with selectable algorithms
- Encoders and decoders (Base64, URL, Hex, ROT13, XOR with key, Binary)
- Hash detection and verification
- Local URL shortener with import/export and redirect support

## Usage

### On Windows
1. Clone or download the repository.  
2. Open the `hashbox` folder.  
3. Double-click `start.bat`.  

This opens `index.html` in your default browser.

### On Linux / macOS
Clone the repository and run the startup script:

```bash
git clone https://github.com/AkotiaJosiah/hashbox.git
cd hashbox
chmod +x start.sh
./start.sh
