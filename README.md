# pycraft
Python tips and tricks - beginner series 

Range function can start at another number, or to specify a different increment (even negative; sometimes this is called the ‘step’):
for item in range(len(items)-1, -1, -1):
  //something

Tuple unpacking or multiple assignment:
s[left], s[right] = s[right], s[left]

Converting Integer to a String using Splice
str(x)[::-1]  
Above, the [::-1], the first semi colon indicates the start of the splice, next indicates, the end, and -1 provides the different increamant, in descending order.

