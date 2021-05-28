# prcrypttome-for-aws-lambda

Use prcrypttome on AWS lambda is a so annoying.

Here is my Crypto build folder that is working on the AWS lambda on Python 3.6 and 3.7.
Feel free to use it.



1. Copy Crypto to folder.
    Structure:
   
        -----
   
        | - Crypto
   
        | - lambda_hander.py
   
2. import Crypto to file
    <code>
   
        from Crypto.Cipher import AES
   
        aes = AES.new(key, AES.MODE_CBC, iv)
   
        data = aes.decrypt(payload)
    </code>


Enjoy it!