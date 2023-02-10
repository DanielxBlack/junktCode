# This will create wordlists for that PortSwigger Lab.
# https://portswigger.net/web-security/authentication/password-based/lab-broken-bruteforce-protection-ip-block

def createPWordLists():

    with open("./wordlist.txt", "r") as file:
        lines = file.read().splitlines()
        passwordList = open("passwordlist.txt", "w")
        for line in lines:
            passwordList.write(line + "\n" + "peter" + "\n")


def createUserList():
    with open("./passwordlist.txt", "r") as thePasswordList:
        userList = open("userNames.txt", "w")
        userLines = thePasswordList.read().splitlines()
        for line in userLines:
            if line == "peter":
                userList.write("wiener" + "\n")
            else:
                userList.write("carlos" + "\n")


createPWordLists()
createUserList()
