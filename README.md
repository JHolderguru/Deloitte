```python
print('welcome to my function please press q to quit! ')
userinput = str(input('press y to continue: '))
if userinput == 'y':

        while True:
            numberinput = (input('please enter a number: '))

            if numberinput == 'q':
                break

            number = int(numberinput)


            if number % 3 == 0 and number % 5 == 0:
                print('PlingPlang')

            elif number % 3 == 0 and number % 7 == 0:
                print('PlingPlong')

            elif number % 5 == 0 and number % 7 == 0:
                print('PlangPl0ng')

            elif number % 3 == 0:
                print('Pling')

            elif number % 5 == 0:
                print('Plang')

            elif number % 7 == 0:
                print('Plong')

            elif number < 36:
                print(number)


            else:
                print(number)
