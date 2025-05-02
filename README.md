# python5
# dictionary operations
person={'name':'ABHIRAM','age':22,'city':'Vijayawada'}
print(person)
print("accessing and modify the person age:")
person["age"]=22
print(person)
print("Adding and removing items")
person['email']='mvabhiram221@gmail.com'
print(person)
del person['city']
print(person)
print("All keys & values")
print(person.keys())
print(person.values())
print(person.items())
print(person.get("age"))
