# test2
# *** PhoneBook ***
#
# tel - номер телефона, строка
# first_name - имя, строка
# last_name - фамилия, строка
# patronymic - отчество, строка
# address - адрес, строка
# {tel: [last_name, first_name, patronymic, address]}

import PhoneBool_lib

def  input_data()
    tel = input("Введите номер телефона: ")
    first_name = input("Введите имя: ")
    last_name = input("Введите фамилию: ")
    patronymic = input("Введите отчество: ")
    address = input("Введите адрес: ")
    temp.append(last_name)
    temp.append(first_name)
    temp.append(patronymic)
    temp.append(address)
    return TEMP


phone_book = dict()

print("***PhoneBook v0.1 ***")
print("******")
print("Режим работы: ")

tel = input("Введите номер телефона")
value = list()

phone_book[tel] = value

print(phone_book)
