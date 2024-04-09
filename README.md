
# 5.Identity Column
#### Q) Identity column na use karne ke disadvantage?
####  Q) How to use Identity column.
####  Q)How to insert data in identity column?
####  Q) How to insert explicitly value in Identity column?
- use concept of Identity_Insert 
####  Q) How to reset your current identity to desired Identity?
- Use concept of DBCC checkIdent(TableName,Reseed,Value)
#### Q)
***Current session mein  
 Regardless of tables  
 Regardless of scope  
Yadi hume last Identity konsi update hue hai, ye pata karna ho tab?***
-	Use concept of @@Identity 
####  Q) 
***Current Session mein  
         Regardless of scop  
           Regardless of execution   
Yadi hume Scope ki latest identity value dekhni hai?***
-	Use concept of Scope_Identity();
####  Q)
 ***Regardless of connection  
         Regadless of current session  
         Regarless of everyting  
If you want Idnetity value for particular table?***
-	Use concept of Ident_Current(‘TableName’);

# 6. Different Keys
### Q) Super Key
- single aur multiple ke unique combination 
### Q) Candidate key
- unique  rehti
- aur null allow nhi karti
### Q) Primary key
- unique
- single
-  null not allowed
- remaining uniqe key called alternate/candidate keys
### Q) Unique key
- multiple
- null allowed but only once
### Q) Composite key
- combination of col (so that uniqueness maintain)
### Q) Foreign key
- Relation ship
- master-details / parent-child
# 7. Temporary table  in sql


