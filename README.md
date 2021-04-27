friends= [ 'Anthony', 'Jose', 'Gael', 'Skeletor' ]
print(friends[0] + "\n")
print(friends[1] + "\n")
print(friends[2] + "\n")
print(friends[3] + "\n")

message= ' Lets meet at the malt shop tomorrow at 7 pm '

print(friends[0] + message + "\n")
print(friends[1] + message + "\n")
print(friends[2] + message + "\n")
print(friends[3] + message + "\n")


transportation = [ 'car', 'boat', 'plane', 'train']

print( " I'd love to have a " + transportation[0] + " of my own " + "\n"  )
print( " Travel by " + transportation[1] + " is far to slow for me " + "\n" ) 
print(  transportation[2] + " travel is expensive and dangerous " + "\n" ) 
print( " The only " + transportation[3] + " i'd get on, is the Hogwarts Express " + "\n" ) 

guest_list = [ 'david foster wallace', 'elon musk', 'steven pinker' ] 

message= ' You are invited to wine and dine with none other then Ricardo Aguayo. Please arrive at 11 sherwood dr, 7 pm sharp ' 


print(guest_list[0].title() + "," + message + "\n")
print(guest_list[1].title() + "," + message + "\n")
print(guest_list[2].title() + "," + message + "\n")
print(guest_list[0].title() + ' Cannot make it'  + "\n") 


guest_list[0] = ' kip thorne' 


print(guest_list[0].title() + "," + message + "\n")
print(guest_list[1].title() + "," + message + "\n")
print(guest_list[2].title() + "," + message + "\n")
print(" Guys!. I've found a bigger table. So we're expecting an extra three tonight. " )

guest_list.insert(0, 'loanrdo decaprio')
guest_list.insert(4, 'sylvester stalone')
guest_list.insert(2, 'jamees franco')

print(guest_list[0].title() + "," + message + "\n")
print(guest_list[1].title() + "," + message + "\n")
print(guest_list[2].title() + "," + message + "\n")
print(guest_list[3].title() + "," + message + "\n")
print(guest_list[4].title() + "," + message + "\n")
print(guest_list[5].title() + "," + message + "\n")
print(" Guy's im sorry to say my new dinner table wont arrive as planned, Therefore only james franco and kip thorne can make it ")

popped_guest_list = guest_list.pop()
message1 = ( " sorry Mr. Stalone. I had to shorten my guest list due to an unpresdented event " ) 
print("\n" + message1)

popped_guest_list = guest_list.pop()

message2 = ( " Sorry Mr. Pinker I've had to shorten my guest list due to unpresdented events " ) 
print("\n" + message2)

popped_guest_list = guest_list.pop()
message3 = ( " Sorry Mr. Elon I've had to shorten my guest list due to an unpresedented event " ) 
print("\n" + message3)

popped_guest_list = guest_list.pop()
message4 = ( " Sorry Mr.Franco I've had to shorten my guest list due to an unpresdetened event " ) 
print("\n" + message4)

message5 = ( " Im still inviting you " + "," ) 

print("\n" + message5 + " " + guest_list[0].title() + ".")
print("\n" + message5 + " " + guest_list[1].title() + ".")

del guest_list[1]
del guest_list[0]
print(guest_list)
 
        # Sorted Lists # 
        
        
places = [ 'hawaii', ' south korea', 'japan', 'china', 'amsterdam' ] 
print(places)
print(sorted(places))
print(places)
places.sort(reverse=True)
print(places)
places.sort(reverse=False)
print(places)

# Length of a list # 


languages = [ 'python' , 'c++' , 'java' , 'javascript', ] 
print("\n" + languages[0].title()) # accessing elements in a list # 

message = " My favorite language is " + languages[0].title() + "." # Using individual values from a list# 
print("\n" + message)

languages[1] = 'HTML' # Modifying elements in a list # 
print(languages)

languages.append('c++') # Appending elements to the end of a list # 
print(languages)

languages.insert(0, 'SQL') # Inserting elements in a list in any position # 
print(languages)

del languages[0] # Removing elements from a list in any position # 
print(languages)

popped_languages = languages.pop() # Removing elements from a list but still being able to work with removed item # 
print(languages)
print(popped_languages)

languages.pop(0) # Removing element from a list in any position while still being able to work with " popped elements" #
print(languages)

languages.remove('java') # Removing an element from a list without knowing position of element in list # 
print(languages)

languages.append ( 'c++')
languages.append ( 'java')
languages.append ( 'python')
print(languages)

languages.sort() # Sorting a list in alphabetical order # 
print(languages)

print(sorted(languages)) # Sorting a list temporarily # 

languages.reverse() # Printing a list in reverse order # 
print(languages)

len(languages)
