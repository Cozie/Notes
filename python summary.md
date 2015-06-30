

## Variable

	type(a) # int, float, str, bool, dict ...

Data type conversion:

	float(5)  # 5.0
	str(a)
	int(4.6)  # 4

Maths:

	5.0/2    # 2.5
	5.0//2   # 2.0
	5**2     # 25
	5%2      # 1

Logical operators: and, or


## Function

> By default, all the functions return 'None'. Those who return values are called 'Fruitful Function'. 

Define a function

	def function(x):

Invoke a function:

	func(16)

Use Build-In function: import

	import math
	math.sqrt(4.0)

	import random
	random.randint(0,100)

Anonymous Function: lambda

	total = lambda num1, num2: num1 + num2
	total(1,2)  # 3

## if/else

	if:
	elif:
	else:

nested if/else

	if:
		if:
		else:
	else:
		if:
		else:

## range()

	range(10)          # 0-9
	range(5, 10)       # 5-9
	range(2, 10, 2)    # 2,4,6,8

## Loop

> break: early termination. Exit the while block and move on to the next statement after while

> continue: skip certain iteration. Skip the rest of statement within the while block.

for loop

	for i in a:

while loop

	while (i>2):

-------------------
-------------------

## String (immutable) a=' '

	a=''
	a='hello'

	a.split()   # slice string into list, interval is space

	a.captalize()
	a.upper()
	a.lower()

	a.replace('e','a')

	a.startwith('h')   # check a[0]
	a.endwith('a')     # check a[-1]
	a.isdigit()

	a.find('wo')       # return index, output is -1 if not found
	a.index('woo')     # return index, output is error if not found
	
----------------
## List (mutable)  a=[ ]

	a=[]
	a=[3, 6, 'a', 'hello']

	a.remove(6)  # remove item from the list
	a.pop()   # remove the last item
	a.append(10)  # add 10 to the end of the list
	a.sort()
	a.reverse()
	a.count(5)   # the frequence of 5 in the list
	max(a)
	min(a)
	len(a)

	a[1]=5   # change the 2nd item into 5

--------------
## Dictionary a={ } / a=dict( )

	a={}
	a=dict()

	a={'b':'boy', 'c':'cat, 'd':'dog'}

Input/change data:

	b['john']=10
				   <==>  b={'john':10, 'mary':20}
	b['mary']=20
	
Convert from tuples:

	c=[('a',1),('b',2),('c',3)]
	d=dict(c)    # d={'a':1, 'b':2, 'c':3}

Access in dict:

	a['x']    # value
	a.get('x')	# value
	a.has_key('x')  # check if
	a.key     # output just key name
	a.items   # output everything

	a.clear   # empty dict

	del a     # delete dict
	del a['x']   # delete 'x' and its value

----------------

## Tuple (immutable) a=( ,)

> Tuple is immutable, can't change items

	t=() # empty tuple
	t=(5,)  # tuple with one element
	t=('a','b','c')
	t= 1,2,3,4,5

Access tuple:

	a[0]

Useful:
	
	len(a)
	max(a)
	min(a)
	a.count('x')
	
---------------
---------------



	

