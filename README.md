# Polling_Analysis
Python3

Basic concepts:
    
    Data types: 
        integers, floatin-point deicmal, strings, boolean (capitalized)
            * to determine type use function type(____)
    
    Variables: name that represent a stored value
        Declare by tying name followed by equal sign and reference the value afterwards
            e.g.:   num_cakes = 3
                    winning_percentage = 73.81
			        baker = "Diane"
			        won_cake_competition = True
            * naming convention is alphanumeric (A-Z, a-z, 0-9, and _)
    
    Aritmethic Operators: +,-,*,/,%,//,**
        * order of precedence follows basic math rules.

    Data Structures: 
        Data types are stored in data structures. The most common formats are lists, tuples and dictionaries.

        1. Lists:
            A list is an array that contains multiple data items
            Three Important Properties:
				a.1) index: position in an array; starts at 0; last item is n-1
                    negative indexing: position of items realtive to the end of list. 
                        e.g.: >>> print(baker[-1])
                                    Diane
                a.2)slicing: used to get a specific items from lists.
                    e.g.: list[start : end]
                b) dynamic structure: items can be added or removed
                    to add:
                        list.append(object)
                    to add in a specific index place:
                        list.insert(index, object)
                    list.remove(object)
                    list.pop(object)
                To create an empty list that has not been declared, use list_name = [], or use function list_name = list()
                c) mutable: contents can be changed. 
                    e.g.:   list[index] = "______"
        2. Tuples:
            Similar to lists but are immutable, only possible to retrieve items.
            To create an empty tuple use my_tuple = (), or my_tuple = tuple()
        
        3. Dictionaries:
            Are objects that store collections of data (in computer's memory).
            This objects are based on a key-value pair, enclosed in sets of curly braces {}. The syntax is {key : value}
                Values in a dictionary can be objects of any type
                Keys must be immutable objects, cannot be lists or any other type of mutable object.
            To initialize an empty dictionary use my_dictionary = {}, or use built-in method my_dictionary = dict()
            To add a key-value pair use my_dictionary["key_name"] = value
                *remember to use single or double quotes and inside brackets.
            To get all keys and values: my_dictionary.items()
            To get All the Keys: dict_name.keys()
		    To get All the Values: dict_name.values()
    		To get a specific value, 2 methods:
			    dict_name.get("key_name")
			    dict_name['key_name']
    
    Decision Statements
        If statements
            Comparison Statements
        If-Else Statements
        Nested If-Else Statements (if-elif-else)
    