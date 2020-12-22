# project_20
import time
email=input("Enter your eMail(it can be fake :)")
if "@" not in email:
    print("This is a invalid email")
else:
    print("Splitting...")
#splitting the email
split=email.split("@")
time.sleep(1)
print(split)
