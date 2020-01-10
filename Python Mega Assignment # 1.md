
# Python Mega Assignment # 1

## Muhammad Arslan Akhtar   (PIAIC61773)
 1. Which of the following terms are related to dictionaries?
    a. value 
    b. item 
    c. index 
    d. keyAnswer:    a. value 
    b. item 
    d. key2. Just like lists, + operator is used to extend dictionaries? 
    a. True 
    b. False Answer    b. False3. To access items from a dictionary, we specify the index of that item within [] like myDict[0]? 
    a. True 
    b. False Answer    a. False4. When we use [] to access the value from a dictionary which does not exist in that dictionary….? 
    a. Value within [] is added to the dictionary 
    b. Value None is returned 
    c. New dictionary is created
    d. None of aboveAnswer    d. None of above5. What does return the pop method of a dictionary? 
    a. list 
    b. tuple containing the pair of last item of the dictionary 
    c. dictionary 
    d. value of the key, if it exists in the dictionaryAnswer     c. dictionary 6. What does return popitem method return? 
    a. dictionary 
    b. tupple containing the pair of last item of the dictionary  
    c. list 
    d. value of key, if it exists in the dictionaryAnswer    a. dictionary 7. Which of the following 2 methods can be used to iterate through the items of a dictionary? 
    a. items() 
    b. values() 
    c. indexes() 
    d. keys()Answer    a. items() 
    b. values() 8. Which one of the following is used to enclose a dictionary? 
   a. () parenthesis 
    b. {} curly brackets 
    c. [] square brackets 
    d. “” quotation marks Answer    b. {} curly brackets 9.  Write Python Program add key-value pair in dictionary and check if a Given Key or Value or Both Exists in a Dictionary or Not. Answerdictionary = {
    "Name" : "Arslan",
    "course" : "A.I"
}
keyval = input("Enter key or value ")

x = dictionary.keys()

y = dictionary.values()

if keyval in x or keyval in y:
    print("yes present")
else:m
    print("not present")
10. Write a Python Program to Count the Frequency of Words Appearing in a String Using a Dictionary and print only the words having Even (divisible by 2) frequency. Answerprint("***Python Program to Count the Frequency of Words Appearing in a String Using a Dictionary***")
print("_____________________________________________________________________________________________")
for t in range(1,3):
    print("case :", t )
    val=input("Enter string:")
    list1=[]
    list1=val.split()
    print(list1)
    count_word_freq=[list1.count(t) for t in list1] 
    print(dict(zip(list1,count_word_freq)))
exit()11. X = ["Feb", "Apr", "Mar", "May", "Jun", "Jul", "Aug", "Jan"]. What will be output of following? 
    X[0:3] 
    X[2:8] 
    X[4:9] 
    X[1:7:2] 
    X[-1:-7] 
    X[-7:7] 
    X[-1:-8:-2] 
    X[:4] AnswerX[0:3] output is ['Feb','Apr','Mar']
X[2:8] output is ['Mar', 'May', 'Jun', 'Jul', 'Aug', 'Jan']
X[4:9] output is ['Jun', 'Jul', 'Aug', 'Jan']
X[1:7:2] output is ['Apr', 'May', 'Jul']
X[-1:-7] output is []
X[-7:7] output is ['Apr', 'Mar', 'May', 'Jun', 'Jul', 'Aug']
X[-1:-8:-2] output is ['Jan', 'Jul', 'May', 'Apr']
X[:4] output is ['Feb', 'Apr', 'Mar', 'May']12. Remove the correct number from the list X 
X = [ 9,2,8,4,5] 
X__?__ 
print (X) 
Output: [2,8,4,5] 
    1) .delete(9) 
    2) .rm(9) 
    3) .remove(9) Answer    3) .remove(9) 13. p = 3 
      q = 'hello! ' 
      print( q __?__ p)  
      hello! hello! hello! 
      1) * 
      2) ** 
      3) + Answer      1) * 14.  y = "this is a random sentence" 
print (y__?__) 
Output: THIS IS A RANDOM SENTENCE 
1) .upper() 
2) .upcase() 
3) .capitalize() Answer    1) .upper() 15. p = True 
       q = True 
       r = 2 
       r = 2.0 
print(type(p)) 
print(type(q)) 
print(type(r)) 
print(type(s))Answer<class 'bool'>
<class 'bool'>
<class 'float'>

print(type(s))-- NameError: name 's' is not defined16. What are the optional arguments to the function? 
function_1(R1, q, p=None, R2= None) 
1) q and R2 
2) p and R2 
3) p and R1 
4) R1 and q  Answer    2) p and R2 17. Which command invokes method X() of the object p? 
1) X(p) 
2) p$x() 
3) X().p 
4) p.X() Answer4) p.X() 18. X=4 , Y= 2 
print(X % Y) 
print(X / Y) 
print(X // Y) 
print(Y % X) Answerprint(X % Y) ---- 0
print(X / Y) ---- 2.0
print(X // Y) --- 2
print(Y % X) ---- 219. x = [[4, 1, 1], [5, 9, 0]] 
 for i in __?__: 
     for j in  __?__: 
        ? 
 Output:  4 
   1 
   1 
   5 
   9 
   0 
   
   
   
   
x = [[4, 1, 1], [5, 9, 0]] 
 for i in __?__: 
     for j in  __?__: 
        ? 
 Output:  4 5 
   1 9 
   1 0 
   
   
   
   
   
x = [[4, 1, 1], [5, 9, 0]] 
 for i in __?__: 
     for j in  __?__: 
        ? 
 Output:  4 1 1 5 9 0 
 
 
 
 
x = [[4, 1, 1], [5, 9, 0]] 
 for i in __?__: 
     for j in  __?__: 
        ? 
 Output:  4 1 1 
   5 9 0 Answera) for i in range(2):
           for i in range(3)

              print(x[i][j])20. q = [10.62, 16.14, 6.45, 17.11] 
 for __?__, z in enumerate (q) : 
     print( ‘Item ‘ + str( j ) + ‘  - ‘, str ( z )) 
 Output:  Item 0 – 10.62 
   Item 1 – 16.14 
   Item 2 – 6.45 
   Item 3 – 17.11 
1) z 
2) i 
3) j 
4) x 
5) k 
6) yAnswer    3) j 21. Which of these about a dictionary is false? 
a) The values of a dictionary can be accessed using keys 
b) The keys of a dictionary can be accessed using values 
c) Dictionaries aren’t ordered 
d) Dictionaries are mutable Answer    b) The keys of a dictionary can be accessed using values 22. What is the output of the following: 
D = dict()  
for i in range (3):  
    for j in range(2):  
        D[i] = j  
a. {0: 1, 1: 1, 2: 1} 
b. {1: 0, 1: 1, 1: 2} 
c. {0: 1, 1: 2, 2: 3} 
d. {1: 2, 1: 1, 1: 0}Answera. {0: 1, 1: 1, 2: 1} 23. You are writing a function that increments player score in a soccer game 
  If no value is specified for points, then point must start with 1 
  If no value is specified for bonus, then bonus should be True 
  01   def increment_score ( bonus , score , points ): 
  To meet the first requirement line 01 must be change to 
 def increment_score ( bonus , score , points = 1 ):           (True or False) 
To meet the second requirement line 01 must be change to 
 def increment_score ( bonus = True , score , points = 1 ):   (True or False) 
 Once a parameter is defined with default value, any parameter to the right must also be defined with default values:  (True or False) Answer def increment_score ( bonus , score , points = 1 ):           (False) 
 def increment_score ( bonus = True , score , points = 1 ):   (False) 
 Once a parameter is defined with default value, any parameter to the right must also be defined with default values:  (True) 24. What will be output? 
  def avg ( x , y , z = 50 ): 
 adding = x + y + z 
 avg_value = adding / 3 
 return avg_value 
  y = avg ( x = 5 , y = 9 , z = 20 ) 
  print(y) Answer11.33333333333333425. What will be output? Describe it with reason and logic behind. Do multiple experiments with arguments / parameters to remove error, if occurs. 
def avg ( *opt_values , name ): 
  
 avg_value = sum (opt_values) / len(opt_values) 
 print(‘name is: ’ + name + ‘Marks: ’ + str(avg_value)) 
avg ( 5 , 9 , 20, 34, 87, 112 , ‘Ali’ )Answername is: Ali Marks: 44.5

Explanation:

    When one parameter has asterick on it, it means that a list of arguments will be passed to the function. The sum method of a list adds all the elements present in a list and dividing that sum by the len method (which gives the total elements present in a list) gives the average marks.

To remove errors simply pass the name argument as a keyword argument rather tha positional argument, that is,  avg ( 5 , 9 , 20, 34, 87, 112 ,name = 'Ali' )26. Final output is not required. Just take copy pencil, think and write the output of each line, write down the link between parameters and arguments. Remove one or two ** from other_info and observe the output. 
def display_result(winner, score, **other_info): 
 print("The winner was " + winner) 
 print("The score was " + score) 
  display_result(winner=“Manchester", score="1-0", overtime ="yes", injuries="none")  AnswerIf we Remove either one or both * from other_info then the output will be 
TypeError: display_result() got an unexpected keyword argument 'overtime'

If we don't remove two ** from other_info then the output will be:
The winner was Manchester
The score was 1-027. The position of parameters and arguments is re-arranged. Just think and find the logic behind output or error. 
def display_result(winner, **other_info, score): 
 print("The winner was " + winner) 
 print("The score was " + score) 
display_result(winner=“Manchester", overtime ="yes", injuries="none“ , score="1-0“ )  Answer**otherinfo should be at the very end in paramter list beacuse optional arguments are placed at very end. This will remove the error and display the same output as in Q26. 


     The output is : 

     The winner was Manchester
     The score was 1-028. What will be the output of the following Python expression if X=123? 
 
print(“%06d”%X) 
a) 123000 
b) 000123 
c) 000000123 
d) 123000000Answer    b) 000123 29. What will be the output of the following Python expression if x=22.19? 
print("%5.2f"%x) 
a) 22.1900 
b) 22.00000 
c) 22.19 
d) 22.20 Answer    c) 22.19 30. What will be the output of the following Python code? 
'{0:f}, {1:2f}, {2:05.2f}'.format(1.23456, 1.23456, 1.23456) 
a) Error 
b) ‘1.234560, 1.22345, 1.23’ 
c) No output 
d) ‘1.234560, 1.234560, 01.23’Answer    b) ‘1.234560, 1.22345, 1.23’31. Write down the output of each line after each iterations. Do multiple experiments to change values 
i = 1 
while False: 
    if i%2 == 0: 
        break 
    print(i) 
    i += 2 AnswerOutput: The loop never runs because we have written false in it so the condition will never be true so no matter what the value of i nothing will be displayed
32. Write down the output of each line after each iterations. Do multiple experiments to change values 
x = "abcdef" 
i = "a" 
while i in x: 
    x = x[:-1] 
    print(i, end = " ") Answera a a a a a 33. Write down the output of each line after each iterations. Do multiple experiments to change values 
for i in ''.join(reversed(list('abcd'))): 
    print (i) Answeroutput will be:
d
c
b
a
Explanation:
The list() constructor returns a mutable sequence list of elements. The iterable argument is optional. You can provide any sequence or collection (such as a string, list, tuple, set, dictionary, etc). If no argument is supplied, an empty list is returned
reverse() is an inbuilt method in Python programming language that reverses objects of list in place. Returns: The reverse() method does not return any value but reverse the given object from the list
The join() is a string method which returns a string concatenated with the elements of an iterable. The join() method provides a flexible way to concatenate string. It concatenates each element of an iterable (such as list, string and tuple) to the string and returns the concatenated string.34. Flow of the program. Write the output of each line after every iteration of ‘i’ 
for i in range(10): 
    if i == 5: 
        break 
    else: 
        print(i) 
else: 
    print("Here")Answerfor i in range(10):
#To loop through a set of code a specified number of times, we can use the range() function,
The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and ends at a specified number.
Note that range(10) is not the values of 0 to 10, but the values 0 to 9.
    
    
    if i == 5: 
#check the condition if i is equal to 5 
        break 
#breaks when i is equal to 5
    else: 
        print(i) 
#print values 0 to 4
else: 
    print("Here")35. What is the output? And understand the functionality of lambda function 
y = 6 
z = lambda x: x * y 
print (z(8)) Answer4836. Write output and give proper logic of whatever the output comes. 
i=0 
def change(i): 
   i=i+1 
   return i 
change(1) 
print(i) Answer0Question 37, 38, 39 are not given40. What will be output? Define this output clearly 
def change(one, *two): 
   print(type(two)) 
   print(two) 
change(1,2,3,4) Answer<class 'tuple'>
(2, 3, 4)41. What will be output? Define this output clearly 
def find(a, **b): 
   print(type(b)) 
find('letters',A='1',B='2') Answer<class 'dict'>42. Write output and define each line’s output for each iteration of ‘i’ 
def foo(i, x=[]): 
    x.append(i) 
    return x 
for i in range(3): 
    print(foo(i)) Answer[0]
[0, 1]
[0, 1, 2]43. Evaluate the following Python arithmetic expression: and write which segment will execute first? (Brackets, Exponents, Multiplication, Addition / Subtraction, Left to right rule) 
(3*(1+2)**2-(2**2)*3)Answer(3*(1+2)**2-(2**2)*3)
1. 	Parentheses
(3*3**2-4*3)
2. 	Exponent
(3*9-4*3)
3. Multiplication
(27-12)
4. Subtraction
15

15 is the answer44.You are creating a function that manipulates a number. The function has the following requirements: 
 A float is passed into the function 
 The function must take the absolute value of the float  
 Any decimal points after the integer must be removed 
  A. math.fmod(x) 
  B. math.frexp(x) 
  C. math.floor(x) 
  D. math.ceil(x) 
  E. math.fabs(x) Answer    E. math.fabs(x) 45. You are writing code that generates a random integer with a minimum value of 5 and a maximum value of 11. 
Which two functions should you use? Each correct answer presents a complete solution. (Choose two.) 
A. random.randint(5, 12) 
B. random.randint(5, 11) 
C. random.randrange(5, 12, 1) 
D. random.randrange(5, 11, 1) AnswerB. random.randint(5, 11)46. Write a program that receives marks from user and check the grade. 
  Marks greater than equal to 90 then A grade 
  Marks between 80 to 90, B grade 
  Marks between 70 to 80, C grade 
  Marks between 60 to 70, D grade 
  Marks less than equal to 60 then E grade Answer

```python
choice = False
while True:
    print(str.upper("***student grading system***"))
    print("____________________________")
    physics = float(input("Enter Marks Of Physics: "))
    english = float(input("Enter Marks Of English: "))
    math = float(input("Enter Marks Of Mathematics: "))
    computer = float(input("Enter Marks Of Computer: "))
    chemistry = float(input("Enter Marks Of Chemistry: "))
    average = float((physics + english + math + computer + chemistry)/5)
    print("\nYour average is : ",average)

    if(average >= 90):
        grade = 'A'
    elif(average >= 80 and average < 90):
        grade = 'B'
    elif(average >= 70 and average < 80):
        grade = 'C'
    elif(average >= 60 and average < 70):
        grade = 'D'
    elif(average < 60):
        grade = 'E'

    if(average >= 60):
        print("Congratulations, Your Grade is ",grade,"\n\n")
        print("____________________________________")
    elif(average < 60):
        print("Better luck next time. Your grade is: ",grade,"\n\n")
        print("________________________________________")
        
        
    opt=str(input("Do you want to continue (y/n):"))
    print("_______________________________")
    print("\n\n") 
    if(opt=='y' or opt=='Y'):
        choice==True
    if(opt == 'n' or opt =='N'):
        print("\nThank you and hope to see you again :)")
        print("_____________________________________")
        break    
exit()
```
