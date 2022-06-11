# login-panel
import random



while True:
    a = input("Please Insert your name : ")
    b = input("Please Insert your last name : ")
    c = int(input("Please Insert your age : "))
    d = int(input("Please Insert your phone : "))
    
    length = 6
    random_pass_lower = 'abcdefghijklmnopqrs'
    random_pass_upper = 'ABCDEFGHIJKLMNOPQRS'
    random_pass_number = "123456789"
    all = random_pass_lower + random_pass_upper + random_pass_number
    
    password = ''.join(random.sample(all , length))
    user_name = f'Hi dear {a}. your username and password is.\nusername : {d} \npassword : {password}'
    print(user_name)
    if c < 18:
        print(f"hi dear {a}.you can not enter.")
        break
    
    
        


    
    

