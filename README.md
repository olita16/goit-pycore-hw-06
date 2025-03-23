Розробіть систему для управління адресною книгою.

Сутності:

Field: Базовий клас для полів запису.
Name: Клас для зберігання імені контакту. Обов'язкове поле.
Phone: Клас для зберігання номера телефону. Має валідацію формату (10 цифр).
Record: Клас для зберігання інформації про контакт, включаючи ім'я та список телефонів.
AddressBook: Клас для зберігання та управління записами.


Функціональність:

AddressBook:Додавання записів.
Пошук записів за іменем.
Видалення записів за іменем.
Record:Додавання телефонів.
Видалення телефонів.
Редагування телефонів.
Пошук телефону.