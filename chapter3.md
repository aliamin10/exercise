# 3-1. Names: Store the names of a few of your friends in a list called names. Print
# each person’s name by accessing each element in the list, one at a time.
friends = ['ahmed','sameh','mohamed']
# print(friends[0])
# print(friends[1])
# print(friends[2])

# 3-2. Greetings: Start with the list you used in Exercise 3-1, but instead of just
# printing each person’s name, print a message to them. The text of each message
# should be the same, but each message should be personalized with the
# person’s name.
# msg = print('hello ' + friends[0].title() + ' hope you doing well !' )
# msg = print('hello ' + friends[1].title() + ' hope you are fine  !' )
# msg = print('hello ' + friends[2].title() + ' hope you the best  !' )


# 3-3. Your Own List: Think of your favorite mode of transportation, such as a
# motorcycle or a car, and make a list that stores several examples. Use your list
# to print a series of statements about these items, such as “I would like to own a
# Honda motorcycle.”
# cars = ['audi','bmw','tesla']
# car = print( "i'd like to own a " + cars[0].title() + ' ' )
# car = print( "i'd like to own a " + cars[1].title() + ' ' )
# car = print( "i'd like to own a " + cars[2].title() + ' ' )
#############################################################################

# 3-4. Guest List: If you could invite anyone, living or deceased, to dinner, who
# would you invite? Make a list that includes at least three people you’d like to
# invite to dinner. Then use your list to print a message to each person, inviting
# them to dinner.
# friends = ['ahmed','sameh','mohamed']
# invite = friends[0].title()
# print(invite + ' , please come to the dinner')

# invite = friends[1].title()
# print(invite + ' , please come to the dinner')

# invite = friends[2].title()
# print(invite + ' , please come to the dinner')
# 3-5. Changing Guest List: You just heard that one of your guests can’t make the
# dinner, so you need to send out a new set of invitations. You’ll have to think of
# someone else to invite.
friends = ['ahmed','sameh','mohamed']
invite = friends[0].title()
# print(invite + ' , please come to the dinner')

# invite = friends[1].title()
# print(invite + ' , please come to the dinner')

# invite = friends[2].title()
# print(invite + ' , please come to the dinner')
# print('\n sorry ' + friends[2].title() + ' can not come for the dinner ')
# del (friends[2])
# friends.append('hady')
# invite = friends[2].title()
# print(invite + ' , please come for the dinner')

# • Start with your program from Exercise 3-4. Add a print statement at the
# end of your program stating the name of the guest who can’t make it.
# • Modify your list, replacing the name of the guest who can’t make it with
# the name of the new person you are inviting.
# • Print a second set of invitation messages, one for each person who is still
# in your list.
# 3-6. More Guests: You just found a bigger dinner table, so now more space is
# available. Think of three more guests to invite to dinner.

# friends = ['ahmed','sameh','mohamed']
# invite = friends[0].title()
# print(invite + ' , please come to the dinner')

# invite = friends[1].title()
# print(invite + ' , please come to the dinner')

# invite = friends[2].title()
# print(invite + ' , please come to the dinner')
# print('\n sorry ' + friends[2].title() + ' can not come for the dinner ')
# del (friends[2])
# friends.append('hady')
# invite = friends[2].title()
# print(invite + ' , please come for the dinner')

# print('we got bigger table , so we have to invite more .. !')
# friends.insert(1 , ' farida ')
# friends.insert(2 , 'john')
# friends.append('hany')
# invite = friends[1].title()
# print( invite + ' please come to the dinner')
# invite = friends[2].title()
# print( invite + ' please come to the dinner ')
# invite = friends[5].title()
# print( invite + ' please come to the dinner')
# • Start with your program from Exercise 3-4 or Exercise 3-5. Add a print
# statement to the end of your program informing people that you found a
# bigger dinner table.
# • Use insert() to add one new guest to the beginning of your list.
# • Use insert() to add one new guest to the middle of your list.
# • Use append() to add one new guest to the end of your list.
# • Print a new set of invitation messages, one for each person in your list.


# 3-7. Shrinking Guest List: You just found out that your new dinner table won’t
# arrive in time for the dinner, and you have space for only two guests.
# • Start with your program from Exercise 3-6. Add a new line that prints a
# message saying that you can invite only two people for dinner.
# • Use pop() to remove guests from your list one at a time until only two
# names remain in your list. Each time you pop a name from your list, print
# a message to that person letting them know you’re sorry you can’t invite
# them to dinner.
# • Print a message to each of the two people still on your list, letting them
# know they’re still invited.
# • Use del to remove the last two names from your list, so you have an empty
# list. Print your list to make sure you actually have an empty list at the end
# of your program.
# print('\n sorry we can not make it , i have just invitation for only tow :( ')
# invite = friends.pop()
# print( invite + ' sorry i have only room for tow')
# invite = friends.pop()
# print( invite + ' sorry i have just room for tow')
# invite = friends.pop()
# print( invite + ' sorry i have just room for tow')
# invite = friends.pop()
# print( invite + ' sorry i have just room for tow')
# invite = friends[0].title()
# print( invite + ' please come i have set')
# invite = friends[1].title()
# print( invite + 'please come you got what you want')

############################################

# 3-8: Seeing the World
# Think of at least five places in the world you’d like to visit.

# Store the locations in a list. Make sure the list is not in alphabetical order.
# Print your list in its original order. Don’t worry about printing the list neatly, just print it as a raw Python list.
locations = ['macca' , 'maldiv' , 'hawai', 'alexandria', 'palermo']
# print('oreginal orders: ')
# print(locations)

# print('\n alphabetical :')
# print(locations)

# print('\n sorted list :')
# locations.sort()
# print(locations)

# print('\n reverse list : ')
# locations.reverse()
# print(locations)

# print("\nReverse alphabetical:")
# print(sorted(locations, reverse=True))



# Use sorted() to print your list in alphabetical order without modifying the actual list.
# Show that your list is still in its original order by printing it.
# Use sorted() to print your list in reverse alphabetical order without changing the order of the original list.
# Show that your list is still in its original order by printing it again.
# Use reverse() to change the order of your list. Print the list to show that its order has changed.
# Use reverse() to change the order of your list again. Print the list to show it’s back to its original order.
# Use sort() to change your list so it’s stored in alphabetical order. Print the list to show that its order has been changed.
# Use sort() to change your list so it’s stored in reverse alphabetical order. Print the list to show that its order has changed.