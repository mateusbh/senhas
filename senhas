import random
import string

def generate_password (size=15):
    characters = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(characters) for c in range (size))

    return password

random_password = generate_password()

print ('A nova senha é:', random_password)
