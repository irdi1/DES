A simple DES Implementation 
- The script can encrypt and decrypt a text or an image using the DES standard
To run you need two libraries numpy and Pillow
- _test_des()_ will run a ready made test
- _DESWithImages_ takes an input for the key you want to encrypt
  - _des.encrypt_image("cat.jpg", "encrypted.jpeg")_ takes an input of the image and outputs an encrypted image file 
  - _des.decrypt_image("encrypted.jpeg", "decrypted.jpeg")_ takes an input of a encrypted image a outputs a decrypted image  
