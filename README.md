АлбахтинАГ_Java2_Lesson3_Collections

1) В классе ArrayWords создан массив слов, с помощью метода showNames() уникальные слова массива сохраняются в HashSet.
Все слова также сохраняются в HashMap, где ключом выступает само слово, а количество употреблений этого слова в качестве значения. 
Все это выводится в консоли. 

2) В классе PhoneBook, создается телефонаая книга на основе HashMap, где ключом выступает фамилия, а значением номер телефона.
При совпадении фамилий, номер добавляется к фамилии, таким образом под одной фамилией может сохранятся неограниченное количество номеров.
Метод add добавляет абонента и номер телефона в книгу. Метод get выводит на экран номера телефонов абонента, фамилию которого передали в метод. 