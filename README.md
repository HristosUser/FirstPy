# FirstPy
Project 
def sareizinat_ar_divi (x):
    return x * 2

print (sareizinat_ar_divi(6))


def say_hello(name):
    print(f"Hello {name}, labu brīvdienas!")

say_hello('Riko')
say_hello('Anna')
say_hello('Aaron')

def say_something():
    print('Something')

say_something()

def sum_two_number(num1, num2):
    return num1 + num2

print(sum_two_number(5, 8))


def convert_to_celsis(farinheit):
    return(farinheit - 32) * 5/9

print(convert_to_celsis(98))

def convert_to_celsis():
    user_value = float(input('Temperature in F: '))
    return(user_value - 32) * 5/9

print(convert_to_celsis())


name_user = input("Меня зовут Пайтон. Как тебе зовут? ")
print('Приятно познакомиться,', name_user)
user_lang = input("Какой твой любимый язык программирования? ")
print("О, я не знал, что ты любишь-", user_lang)
