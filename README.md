                                                                  калькулятор на Python
                                                                     
                                                                        ВВЕДЕНИЕ
                                                                        
 Программа состоит в том, чтобы складывать и решать простейшие примеры, на основе математической структуры. 
 
                                                                       РЕФЛЕКСИЯ
                                                                       
 Продемонстрируем первую функцию самогого калькулятора
 
 print("Ноль в качестве знака операции"
      "\nзавершит работу программы")
while True:
    s = input("Знак (+,-,*,/): ")
    if s == '0':
        break
    if s in ('+', '-', '*', '/'):
    
    Если пользователь ввел знак, который не является ни знаком арифметической операции, ни символом-"прерывателем" работы программы, то вывести сообщение о некорректном вводе.
    
     x = float(input("x="))
        y = float(input("y="))
        if s == '+':
        
        Если был введен один из четырех знаков операции, запросить ввод двух чисел.

В зависимости от знака операции выполнить соответствующее арифметическое действие.

 print("%.2f" % (x+y))
        elif s == '-':
            print("%.2f" % (x-y))
        elif s == '*':
            print("%.2f" % (x*y))
        elif s == '/':
            if y != 0:
                print("%.2f" % (x/y))
            else:
            
            Если было выбрано деление, необходимо проверить не является ли нулем второе число. Если это так, то сообщить о невозможности деления.
                                                                 
                                                                 
