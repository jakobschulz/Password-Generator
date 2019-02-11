from random import randint
def random_password (): 
    password = ""
    password_length = 20
    characters = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j',
                  'k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8',
                  '9','0','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G',
                  'H','J','K','L','Z','X','C','V','B','N','-','_','+','=','/','?','!','@','#'] 
    while password_length != 0:
        char_choice = randint(0,69)
        password = password + characters[char_choice]
        password_length = password_length - 1
    print(password)
        
random_password()
