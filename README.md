# Action-Menu
ASB- Dating Simulator.
#TBG Action Menu - Saaim Nadeem
#May 18, 2022

#Title code
print('ASB:Dating Simulator')
print('By:Saaim Nadeem')
print('.')

#Inventories
styles= ['Emo','Sigma','Kpop','Medieval']
waifus= ['Abid-senpai','Ashhad-kun','Hamim-san','Charlie-chan']

#Intro Questions
print('What is your name?')
name = input()
print('How old are you?')
age = input()
print('What is your gender?')
gender = input()
print('valid')
print('---------------------')

#Question One
print('It\'s your first day of school, how will you present yourself?')
for drip in styles:
    print('*' + drip)
appearance = input()
if appearance =='Emo':
    print('Good choice')
elif appearance =='Sigma':
    print('Grindset Activated')
elif appearance =='Kpop':
    print('mid but alright')
elif appearance =='Medieval':
    print('Onwards')
else:
    print('Not a choice, Try Again')
print('---------------------')

#Question Two
print('You enter your first class, Who do you sit beside?')
for homies in waifus:
    print('*' + homies)
decision = input()
if decision =='Ashhad-kun':
    print('You make small talk and he barely replies.')
elif decision =='Hamim-san':
    print('He is very nice and offers you some salmon')
elif decision =='Charlie-chan':
    print('He picks you up and throws you out the window, he must be shy')
elif decision =='Abid-senpai':
    print('You died')
else:
    print('Not and option, try again.')
