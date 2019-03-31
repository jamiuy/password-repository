import string,random

def generatePassword(num):
    password = ''

    for n in range(num):
        x = random.randint(10,34)
        password += string.printtable[x]
        return password



print generatePassword(16)


# please read this comment->#number 13 line there is something wrong but some applications they say something is wrong in this line
