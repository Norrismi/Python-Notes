# List practice

```python
ice_cream = ['Chocolate', 'vanilla', 'Rocy Road']

x,y,z = ice_cream

print(x)
print(y)
print(z)
print(ice_cream)

['cookie Dough', 'strawberry', 'chocolate']
['Vanilla', 3, ['Scoops', 'Spoon'], True]

ice_cream = ['cookie Dough', 'strawberry', 'chocolate']

ice_cream.append('salted Caramel')
ice_cream

ice_cream[0] = 'vanilla'
ice_cream

nested_list = ['Vanilla', 3, ['Scoops', 'Spoon'], True]
nested_list[2][1]

# Tuple - Biggest difference from List are Tuples can't be modified or change after creation
# Use when the data won't be changed, Ex. City, Country etc..

tuple_scoops = (1,2,3,2,1)
type(tuple_scoops)

tuple_scoops[0]

# Sets - Similar to Lists and Tuples, but Sets don't have duplicating elements
# Sets will only print the unique values

daily_pints = {1,2,3}

type(daily_pints)

# print(set | set) - returns the unique values between both Sets
# print(set & set) - returns the unique values in both Sets
# print(set - set) - returns the unique values that doesn't match
# print(set ^ set) - returns the unique values to each Set

# Dictionaries 
# Key/ Value Pair

Dcream = {'name': 'Alex Freberg', 'weekly intake': 5, 'favorite ice cream' : ["MCC", "Chocolate"]}

# Comparison Operators
10 == 10 #True

10 != 50 # True

'vanilla' == 'vanilla' # True

x = 'vanilla'
y = 'chocolate'

x != y  #True

10 <= 10 #True

50 >= 10 #True

# Logical Operators

(10 > 50) and (50 > 10) #False
(70 > 50) and (50 > 10) #True

(10 > 50) or (50 > 10) #True

# Membership Operators

ice_cream = 'I love chocolate icre cream'

'love' in 'I love chocolate icre cream' #True

scoops = [1,2,3,4,5,6]
wantedScoops = 8

7 in scoops #False
wantedScoops in scoops #False




```
