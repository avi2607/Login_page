import random
n = 4
password = 'Avi'
entered_password = input("Enter your password:")


if password == entered_password:
    print("Successfully Login to your Account")
else:
    while password != entered_password:
            print("Password Does not Match...!")
            entered_password = input("Enter your password again:")
            if password == entered_password:
                print("Successfully Login to your Account")
                break
            else:
                print("Forget Password...!")
                otp = random.randint(1000,9999)
                print("your OTP is:",otp)
                ot = int(input("Enter your OTP:"))
                if otp == ot:
                    change_password = input("Enter the new Password:")
                    password = change_password
                    print("Your Password Changed Successfully...")
                    break
                else:
                    while n > 0:
                        print("You entered incorrect OTP..")
                        ot = int(input("Enter your OTP again!:"))
                        print("you left only {} Chances".format(n))
                        n = n - 1

