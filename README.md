# Python_Basics
basic program practice for interview



'''#Using re.compile() + re.match() + re.groups()
import re
l="dev123*&%"
print("the original string is : " + str(l))
temp=re.compile("([a-zA-Z]+)([0-9]+)")
res=temp.match(l).groups()
print("splitted result: "+str(res))



import re
 
test_str = "Geeks4321"
 
# printing original string
print("The original string is : " + str(test_str))
 
# Using re.compile() + re.match() + re.groups()
# Splitting text and number in string
temp = re.compile("([a-zA-Z]+)([0-9]+)([~-*]+)")
res = temp.match(test_str).groups()

 
# printing result
print("The tuple after the split of string and number : "
       + str(res))



import array
m=[11,2,4,5,2,3,5,6]
print(m[-3:])



def cars(self,name):
    selfname=self.name
    #print(selfname)
c=cars("Honda")
print(c)


#number Revese operatrion
l=[1,2,3,4]
print(l[::-1])'''

#string reverse operation
d="jaraved"
print(d[::-1])
