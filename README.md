Pixel Manipulation Image Encryption
This project implements a basic image encryption and decryption tool using pixel manipulation techniques. The tool allows users to securely encrypt and later decrypt images using a secret key.

Features
Encryption: Applies a mathematical operation (XOR) to each pixel of the input image using a user-provided key.
Decryption: Reverses the encryption process to recover the original image.
User Interface: Simple command-line interface for easy interaction.
Implementation Details
Language: Python
Libraries: Pillow (PIL) for image processing, NumPy for efficient array operations
Encryption Method: XOR operation between image pixels and a repeating key
How It Works
The user provides an input image path, output image path, and a numeric key.
The program reads the image and converts it to a NumPy array.
The key is expanded to match the size of the image data.
An XOR operation is performed between the image data and the expanded key.
The resulting data is saved as a new image (encrypted or decrypted).
Usage
Enter 'e' to encrypt, 'd' to decrypt, or 'q' to quit: e
Enter the path to the input image: /path/to/input/image.jpg
Enter the path for the output image: /path/to/output/encrypted_image.jpg
Enter the encryption/decryption key (a string of numbers): 123 45 67 89
Image encrypted successfully!
Instructions for a Beginner
Setup
Install Python:

Ensure you have Python installed on your computer. If not, download and install it from python.org.
Open Command Prompt or Terminal:

On Windows, open Command Prompt. On Mac or Linux, open Terminal.
Install Required Libraries:

Type the following command and press Enter:
pip install Pillow numpy
Create the Script
Open a Text Editor:

Use any text editor like Notepad, VS Code, or Sublime Text.
Copy and Paste the Provided Code:

Copy the code provided above into the text editor.
Save the File:

Save the file as image_encryption.py in a location you can easily access.
Prepare Your Image
Choose an Image:

Select an image you want to encrypt.
Note the Full Path:

Write down or remember the full path to this image.
Run the Script
Navigate to the Script Directory:

In the command prompt or terminal, navigate to the directory where you saved image_encryption.py.
cd path_to_directory
Run the Script:

Type the following command and press Enter:
python image_encryption.py
Using the Tool
Choose an Operation:

You'll be prompted with: "Enter 'e' to encrypt, 'd' to decrypt, or 'q' to quit:"
Type 'e' for encryption or 'd' for decryption and press Enter.
Enter Paths and Key:

Input Path: Enter the full path to your input image.
Output Path: Enter the full path where you want to save the output image.
Key: Enter a series of numbers separated by spaces (e.g., "123 45 67 89").
Encrypting an Image
Choose 'e' When Prompted:

Type 'e' and press Enter.
Enter Paths and Key:

Enter the path to your original image.
Enter a path for the encrypted image (use a different name from the original).
Enter your chosen key.
Encryption Complete:

The program will create an encrypted version of your image and save it to the specified path.
Decrypting an Image
Choose 'd' When Prompted:

Type 'd' and press Enter.
Enter Paths and Key:

Enter the path to your encrypted image.
Enter a path for the decrypted image.
Enter the same key you used for encryption.
Decryption Complete:

The program will recover your original image and save it to the specified path.
Quitting the Program
Exit:
Type 'q' when prompted to exit the program.
By following these steps, you can securely encrypt and decrypt images using pixel manipulation techniques.
