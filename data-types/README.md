

### Lists


#### Lists are mutual that we can change values
```
nums = [10,17,56,89,11,20] # eliments/ Index values  [0,1,2,3,4,5,6]
print(nums)
```
#### print specific element
```
print (nums[5])
```
#### print some from specific eliment to end
```
print ("print some from specific eliment to end")
print (nums[3:])
```
#### print float string and intiger
```
values = [10.5, 'prashanthGR', 100]
print(values)
```
#### list of lists
```
mil = [nums, values]
print(mil)
```
#### Operates in List
   
```
nums.append(1000) # apend value to list
print (nums)

nums.insert(3,105) # Inset value at 3 index / inbetween of list
print (nums)

nums.remove(1000) # remove value from list , value is 1000print (nums)
print (nums)

nums.pop(3) # remove value from list Using its Inedex value
print(nums)

nums.pop() # remove last value from the list
print(nums)

del nums[3:] # delete multiple valuse starting from 3rd Index
print(nums)

nums.extend ([2000,4000,500]) # append multiple values to the list
print(nums)
```

#### List Inbuilt Fuctions
```

print (nums.sort())  # sort valumes from list

print (min(nums)) # find minimum value from list

print (max(nums)) # find maximum value from list

print (sum(nums)) # find sum of total from the list

print (nums.sort())
```

#### Tupel And Set
```
# tuple is immutable and we cant chang the values 


tup = (10, 5 , 45, 87, 2)

print(tup)

print(tup[1]) # print value of 1st index
```
#### Set is colletion of uniq elements and not sort 
##### set will not support Index value 
```
s = {10, 1, 22, 5, 7, 1, 22}
print(s)

s.update({100}) # update values
print(s)
```

#### Dictionary
```

data = {1:'prashanthGR', 2:'Potti', 3:'Rebel'}
print(data[3]) # print value which is in 3rd key from Dictonary
print(data.get(4, 'Key not found')) # Print something in case key is missing

# Create Dictionary with the help of Lists

keys = ['prashanth', 'pavi', 'Rebel']
vaules = ['python', 'java', 'perl']

data = dict(zip(keys,vaules))
print(data)
print(data['pavi']) # print value of pavi key

data['parvati'] = 'CS' # add key and values to Dictionary
print(data)

del data['parvati'] # Delete values using keys
print(data)

#Using List Inside Dictionary and Dictionary in Dictionary

programs = {'JS': 'Atom', 'CS': 'VS' , 'Python': ['Pycharm','sublime','Visual Coe'], 'JAVA': {'JSE': 'Netbeans','JEE': 'Eclips'}}
print(programs)

print(programs['Python']) # from list in Dictionary

print(programs['JAVA'])

print(programs['JAVA']['JSE']) # from Dictinary in Dictinary
```
