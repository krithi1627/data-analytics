\#### single variable

1\. integer :a=1,2,3

2.float:a=3.46

3.boolean:a=true or false

4\. complex :a=3+7p

5\. string :a=hi







\#### multiple variable

1.list:a=\["apple", "mango",]

2.tuple:a=("apple", "mango")

3.set:a={"apple", "mango"}

4.dictionary :a={name= " Kritika" ,age="19"







\#### operators

\*\*1. arithmetic operators:\*\*

\\\*Addition e.g.: X+Y

\&#x20;8

\\\* subtraction

\\\* multiple

\\\* divide

\\\*modulus(%)

\\\*exponential(\\\*\\\*)

\\\*floor division(//)

\&#x20;

&#x20;\*\*2.assignment operators:\*\*

\\\*=e.g.: X=5 X=5

\\\*+=e.g.: X+=3 X=X+3

\\\*\\\_ =

\\\*\\\*=

\\\*/=

\\\*%=

\\\*//=

\\\*\\\*\\\*=

\\\*\\\&=

\\\*/=

\\\*^=

\\\*>>=

\\\*<<=

\\\*:=e.g.: print(X:=) X=3

\&#x20;              print(X)

\&#x20;               3



\*\*3.comparison operators :\*\*

\\\* Equal==  e.g.: x==y

\\\*Not Equal!= e.g.: x!=y

\\\*Greater than e.g.: x>y

\\\* less than e.g.: x<y

\\\*greater than or equal to e.g.: x>=y

\\\* less than or equal to e.g.: x<=y



\*\*4.logical operators:\*\*

\\\* And(Returns True if both statements are true) e.g. : x<5 And x<10

\\\* or(returns true if one of the statements is true) e.g.: x<5 or x<4

\\\* Not(Reverse the result, returns false if the result is true)e.g.: not(x<5 and x<10)



\*\*5.identical operators:\*\*

\\\*is ( Returns True if both variables are the same object) e.g.: x=\\\["apple", "banana"]

\&#x20; y=\\\[" apple", "banana"]

\&#x20; z=x

\&#x20;print(x is z)

\&#x20; false

\\#returns false because x is not the same object as y ,even if they have the same content



\\\* is not(Returns True if both variable are not same object)

e.g.: x=\\\["apple" ,"banana"]

\&#x20;    y=\\\["apple", "banana"]

\&#x20; z=x

\&#x20; print(x is not z)

\\# returns false because z is the same object as x

&#x20;print(x is not y)

\\# returns True because x is not the same object as y , even if they have the same content

&#x20;print(x!=y)

\\# to demonstrate the difference between " is not" and "!=": this comparison returns false because x is equal to y



\*\* 6.membership operators:\*\*

\\\* in ( Returns True if a sequence with the specified value is present in the object)

&#x20;x=\\\["apple", "banana"]



print(" banana" in x)



\\# returns true because a sequence with the value " banana" is in the list



\\\* not in( returns true if a sequence with the specified value is not present in the object)

x=\\\[" apple", "banana"]

print (" pineapple" not in x)

\\# returns true because a sequence with the value " pineapple" is not in the list

\*\*7.bitwise operators:\*\*

Decimal number and their binary values :

0=0000000000000000

1=0000000000000001

2=0000000000000010

3=0000000000000011

4=0000000000000100

5=0000000000000101

6=0000000000000110

7=0000000000000111

\\\*and(\\\&) (sets each bit to 1 if both bits are 1)

print (6\\\&3)



"""

&#x20;The\\\& operators compares each bit and set it to 1 if both are 1, otherwise it is set to o



6=0000000000000110

3=0000000000000011



\\------------------

2=0000000000000010

\\\*OR(/)(Sets each bit to 1 if one of two bits is 1)

&#x20;print(6|3)





"""

The | operator compares each bit and set it to 1 if one or both is 1, otherwise it is set to 0:



6=0000000000000110

3=0000000000000011



\\-----------------

7=0000000000000111



\\\*XOR(^)(Sets each bit to 1 if only one  of two bits is 1)

\\# The ^ operator compares each bit and set it to 1 if only one is 1, otherwise it is set to 0



\\# 6=0110

\\# 3=0011

\\#-------

\\#5=0101



print(6^3)

\&#x20;  5



\\\* Not (\\\~) (Inverts all the bits)

print(\\\~3)







"""

&#x20;The operator inverts each bit (0 becomes 1 and 1 becomes 0).





Inverted 3 becomes -4:



\&#x20; 3=0000000000000011

\\-4=1111111111111100



\\\*Zero to fill left shift (<<)( shift left by pushing zeros in from the right and let the leftmost bits fall  off)





print(3<<2)

\&#x20:



"""

The<< operators inserts the specified number of 0`s ( in this case 2) from the right and let the same amount of leftmost bits fall off:



If you push 00 in from the left :

\&#x20;3=0000000000000011

becomes

12=0000000000001100



\\\* signed right  shift (>>) ( shift right by pushing copies of the leftmost bit in from the left , and let the rightmost bits fall off)



print(8>>2)



""" The>> operators moves each bit the specified number of times to the right . Empty holes at the left are filed with 0`s.



If you moves each bit 2 times to the right, 8 becomes 2:

&#x20;

becomes

\&#x20;2=0000000000000010

