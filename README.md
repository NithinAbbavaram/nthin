# nithin
usercommits = [
	("nithin","01-01-2020"),
	("nithin","01-01-2020"),
	("naresh","01-01-2020"),
	("nithin", "01-01-2020"),
	("nithin", "02-02-2020"),
    ("archana", "03-03-2020"),
    ("archana", "08-08-2020"),
    ("naresh", "09-09-2020"),
    ("naresh", "09-09-2020"),
	("nithin","09-09-2020")
]
result={}
usercommits_unzipped=list(zip(*(usercommits)))
for name in usercommits_unzipped[0]:
   if(result.get(name)==None):
       result[name]=1
   else:
       result[name]=result[name]+1
print(result) 
commits= 0
user_name = None
for k in result:
    if result[k] >commits:
        commits = result[k]
        user_name = k

print("The most commits done by ",user_name)
print("The commits done by "+user_name+ " are ",commits)
#for most_commits, user_name in result.items(): 
 #   print(most_commits, ":", user_name) 
usercommits = [
	("nithin","01-01-2020"),
	("nithin","01-01-2020"),
	("naresh","01-01-2020"),
	("nithin", "01-01-2020"),
	("nithin", "02-02-2020"),
    ("archana", "03-03-2020"),
    ("archana", "08-08-2020"),
    ("naresh", "09-09-2020"),
    ("naresh", "09-09-2020"),
	("nithin","09-09-2020")
]
result={}
usercommits_unzipped=list(zip(*(usercommits)))
for name in usercommits_unzipped[0]:
   if(result.get(name)==None):
       result[name]=1
   else:
       result[name]=result[name]+1
print(result) 
commits= 0
user_name = None
for k in result:
    if result[k] >commits:
        commits = result[k]
        user_name = k

print("The most commits done by ",user_name)
print("The commits done by "+user_name+ " are ",commits)
#for most_commits, user_name in result.items(): 
 #   print(most_commits, ":", user_name) 
usercommits = [
	("nithin","01-01-2020"),
	("nithin","01-01-2020"),
	("naresh","01-01-2020"),
	("nithin", "01-01-2020"),
	("nithin", "02-02-2020"),
    ("archana", "03-03-2020"),
    ("archana", "08-08-2020"),
    ("naresh", "09-09-2020"),
    ("naresh", "09-09-2020"),
	("nithin","09-09-2020")
]
result={}
usercommits_unzipped=list(zip(*(usercommits)))
for name in usercommits_unzipped[0]:
   if(result.get(name)==None):
       result[name]=1
   else:
       result[name]=result[name]+1
print(result) 
commits= 0
user_name = None
for k in result:
    if result[k] >commits:
        commits = result[k]
        user_name = k

print("The most commits done by ",user_name)
print("The commits done by "+user_name+ " are ",commits)
counter = 0
num = usercommits_unzipped[1] 
for i in usercommits_unzipped[1]: 
    curr_frequency = usercommits_unzipped[1].count(i) 
    if(curr_frequency> counter): 
        counter = curr_frequency 
        num = i 
print("The more commits done by "+user_name+" in a single day is on ",num)


 
 
 

 
 
 
