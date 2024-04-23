# Image Encryption Tool

This Python program demonstrates a simple image encryption and decryption tool using pixel manipulation. It uses XOR encryption to encrypt and decrypt images.

## Requirements

- Python 3.x
- Pillow library (install using `pip install Pillow`)

## Usage

1. Place the image you want to encrypt in the same directory as the script.
2. Modify the `image_path` variable in the script to point to your image file.
3. Run the script. It will encrypt the image and save the encrypted version as a new file.
4. To decrypt the image, use the `decrypt_image` function in the script.

## Example

```python
image_path = 'path_to_your_image.png'
key = 123
encrypted_image_path = encrypt_image(image_path, key)
print('Image encrypted and saved as', encrypted_image_path)

decrypted_image_path = decrypt_image(encrypted_image_path, key)
print('Image decrypted and saved as', decrypted_image_path)

##License

This project is licensed under the MIT License. See the LICENSE file for details.
