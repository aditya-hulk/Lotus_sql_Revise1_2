
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
### Q) Hum existing table se temporary table kaise create kare?
- use concept of Select statement for creating temp table
- select * Into TempTableName from TableName
-  local temp table # lagake use karte.
    - select * Into #TempStud from Student_marks;
### Q) Kaha dikhta temporary table?
- Systeme Database -> TempDb-> temp table
### Q) problem with local temporary table?
- dusre session mein dikhta nahi
### Q) Advantage of temptable
- apne local temp table se data delete bhi kiya  
    Toh original table ko koyi fark nhi padta.
### Q) aapka local temp table drop kab honga?
- yadi connection close ho jave
- drop command
### Q) hum 2 taarah se local temp table create kar sakte?
- via select statement(copy existing table into temptable)
- via create statement
### Q) how to create global temporary table?
- use concept of ##
### Q)Advantage of global temp table?
- access from any session
### Q) Drop kab hota
-  via drop command
- jab sare session close ho jave.
### Q) when to use temprary table
- jab aapke pass kisi table ke rights nhi ho aur usse manipulate karna ho


