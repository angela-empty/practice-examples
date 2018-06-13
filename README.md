# practice-examples
A collection of practice statements and loops I use for quick examples and review

First project added is a dictionary test example populated by pokemon and their types. The finall loops 
will be able to pull pokemon from the dictionary based on type and effective battle attacks

poke_type = ['Normal', 'Fighting', 'Flying', 'Poison', 'Ground', 'Rock', 'Bug', 'Ghost', 'Steel', 'Fire', 'Grass', 'Water', 'Electric', 'Psychic', 'Ice', 'Dragon', 'Dark','Fairy']

poke_dictionary = {'mewtwo': ['psychic', 'none'], 'dragonite': ['dragon', 'flying'],
"snorlax":["normal", 'none'], 'tyranitar': ['rock', 'dark']}



#practice adding items to a dictionary

poke_dictionary ["kabutops"] = ["water", "rock"]

#practice creating a loop that if a poke is not in the dictionary it is added

if 'gengar' not in poke_dictionary:
    print('gengar' in poke_dictionary)
    poke_dictionary['gengar'] = ['poison', 'ghost']
    
#practice using get method
    
print(poke_dictionary)
