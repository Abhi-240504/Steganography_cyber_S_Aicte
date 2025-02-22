# Steganography_cyber_S_Aicte
Image Steganography in Java

Overview

A Java-based image steganography tool that enables secure hiding and retrieval of messages within digital images. It modifies pixel values while preserving image quality and enforces access control through passcode protection.

Features

Secure Message Encoding & Decoding via RGB pixel modifications.

Supported Formats: PNG (recommended), JPG (lossy compression may affect accuracy).

Passcode Protection to restrict unauthorized access.

Robust Error Handling for incorrect passcodes, unsupported formats, and message length constraints.

Cross-Platform Compatibility for Windows and Linux.

Technologies Used

Language: Java

Libraries: Java AWT, Swing, BufferedImage

Encryption: Pixel-based RGB encoding

Installation & Usage

Ensure JDK is installed.

Compile and execute the program:

javac ImageSteganography.java && java ImageSteganography

Encoding: Select an image, enter a message and passcode to create an encrypted image.

Decoding: Load the encrypted image and input the correct passcode to reveal the message.

Future Enhancements

Least Significant Bit (LSB) Encoding for enhanced security.

Support for Additional Image Formats beyond PNG and JPG.

Advanced Encryption & GUI Integration for a user-friendly experience.

Improved Steganalysis Resistance to avoid detection.

Contributors

[Your Name] - Developer

License

Licensed under the MIT License.
