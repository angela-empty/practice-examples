# practice-examples
A collection of practice statements and loops I use for quick examples and review

First project added is a dictionary test example populated by pokemon and their types. The finall loops 
will be able to pull pokemon from the dictionary based on type and effective battle attacks

poke_type = ['Normal', 'Fighting', 'Flying', 'Poison', 'Ground', 'Rock', 'Bug', 'Ghost', 'Steel',
'Fire', 'Grass', 'Water', 'Electric', 'Psychic', 'Ice', 'Dragon', 'Dark','Fairy']

poke_dictionary = {'mewtwo':{'type':'psychic', 'secondary':'none', 'CP': 2790},
'dragonite':{'type':'dragon', 'secondary':'flying', 'CP': 2456},
"snorlax":{'type':"normal", 'secondary':'none', 'CP': 3245},
'tyranitar':{'type':'rock', 'secondary':'dark', 'CP': 3452}}



#practice adding items to a dictionary

poke_dictionary ["kabutops"] = ["water", "rock"]

#practice creating a loop that if a poke is not in the dictionary it is added

if 'gengar' not in poke_dictionary:
    print('gengar' in poke_dictionary)
    poke_dictionary['gengar'] = ['poison', 'ghost']
    
#practice using get method
    
print(poke_dictionary)

print(poke_dictionary.items())

# now practice adding to the original dictionary with a nest dictionary with more information
# about each type of pokemon

#practice accessing a list index inside a dictionary

print(poke_dictionary.values())
