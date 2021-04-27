bands = ['korn', 'metalica', 'slayer']
for band in bands: 
	print(band.title() + ", fucking rules!")
	print(" I can't wait to see you're next show " + band.title() + ".\n")
	
print(" Thank you for coming everyone! " ) 

pizzas = [ 'italian' , 'hawaiian' , 'meat lovers']
for pizza in pizzas:
	print( " I really like " + pizza.title() + " pizza." + "\n") 
	
for pizza in pizzas: 
	print( " I adore " + pizza.title() + " pizza." + "\n")

print( " I really love pizza ! " + "\n") 


felines = ['cats' , 'tigers' , 'lions' , 'cougers', 'panthers']
for feline in felines:
	print(  feline.title() + " are my preferred feline  " + "\n") 
	print( feline.title() + " Would make great pets" + "\n")
	
for value in range(1,777):
	print(value)

numbers = list(range(1,777))
print(numbers)

print( "Here are the first three felines on my list:" + "\n")
for feline in felines[:3]:
	print(feline.title())

print("Here are three items from the middle of my felines list:" + "\n")
for feline in felines[1:]:
	print(feline.title())

print("Here are the last three items in my list:" +"\n") 
for feline in felines[-3:]:
	print(feline.title())

pizzas.append('pepperoni')
my_pizzas = pizzas
friends_pizza = my_pizzas[:]
friends_pizza.append('dip deish pizza')
print(friends_pizza)
print(my_pizzas)
print(" My favorite pizzas are: " + "\n")
for pizzas in my_pizzas:
	print(pizzas)

print("My friends favorite pizzas are:"  + "\n")
for pizzas in friends_pizza:
	print(pizzas)
	print(pizzas)
