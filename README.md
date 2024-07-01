 import random
import string

def generate_captcha(length=5):
    characters = string.ascii_letters + string.digits
    captcha = ''.join(random.choice(characters) for _ in range(length))
    return captcha

print("Generated Captcha: ", generate_captcha())


#link of the file
#[generate captcha task1.txt](https://github.com/user-attachments/files/16051241/generate.captcha.task1.txt)

