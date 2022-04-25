# Image Cryptography Based on Rubix's Cube Principle

Implementation of image encryption and decryption using Rubix's Cube Principle. This algorithm is based on 
the paper which can be found at https://www.hindawi.com/journals/jece/2012/173931/


## Running 

1. To encrypt an image, give the name of the image in the file and then run it.
2. The encrypted image can be found at the in the same folder as the input image.       
The keys generated during encryption is stored in the ```keys.txt``` file.

3. To decrypt the image, give the name of the image in the file and then run it.
And Then enter the value of the Keys (Kr, Kc and ITER_MAX)  
The decrypted image can be found in the same folder as the encrypted image.     

## Example

1. Run the encryption program to encrypt the image ```naruto.png```
      Use ```python encrypt.py```

![](https://github.com/uD1Y/Image-Processing-Project/blob/main/Rubix's%20Cube/naruto.png)

The encrypted Picture can be found in the same folder
![](https://github.com/uD1Y/Image-Processing-Project/blob/main/Rubix's%20Cube/encrypted_naruto.png)

The keys are stored in ```keys.txt ```

2. Run the decrpytion program to decrypt the image, run and enter the key values (Kr, Kc and ITER_MAX)
      Use ```python decrypt.py```

The decrypted Picture can be found in the same folder
![](https://github.com/uD1Y/Image-Processing-Project/blob/main/Rubix's%20Cube/decrypted_naruto.png)


