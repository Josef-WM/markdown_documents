## Databases Mandatory Assignment - A2

### **Social-Network Query Exercises**
### Q1
Find the names of all students who are friends with someone named Gabriel. \
![{0783603C-4726-41AF-9DD8-A2F824637B7A}](https://github.com/user-attachments/assets/3e8bc346-6ddf-47e0-b666-f6a1358d0e1a)
![{AE6F3469-E7D1-4CDB-8379-E6CD7F4FA5AF}](https://github.com/user-attachments/assets/fedc9361-e972-4bee-aed3-a74be5c13711)

### Q2
For every student who likes someone 2 or more grades younger than themselves, return that student's name and grade, and the name and grade of the student they like. \
![{77160096-1A8D-4E18-80FB-80C46B273E2D}](https://github.com/user-attachments/assets/91745829-2d35-4fbd-9f42-ebc41e8dcc00)
![{9EC21346-86BA-40CB-A20B-A404B30F9660}](https://github.com/user-attachments/assets/dcf9d2bf-80e0-450e-97ed-5d740752639d)

### Q3
For every pair of students who both like each other, return the name and grade of both students. Include each pair only once, with the two names in alphabetical order. \
![{43E96B34-B7F7-468C-B58B-217B33981524}](https://github.com/user-attachments/assets/76626cc3-603e-47ae-92ec-c8cd340adb14)
![{9539403F-77F0-4141-B799-C1E2B52AD6BD}](https://github.com/user-attachments/assets/68cf9673-9f36-4926-9c5f-1b9ce529f4ed)

### Q4
Find all students who do not appear in the Likes table (as a student who likes or is liked) and return their names and grades. Sort by grade, then by name within each grade. \
![{27690CED-4914-4780-B68E-527DCDDED1BF}](https://github.com/user-attachments/assets/2acfaab2-f090-4a62-b313-950028fb583f)
![{DAE9D26E-CCE2-4698-9693-720D6BC64A5C}](https://github.com/user-attachments/assets/e395ea72-32fd-4afb-94ce-83091124c3cf)

### Q5
For every situation where student A likes student B, but we have no information about whom B likes (that is, B does not appear as an ID1 in the Likes table), return A and B's names and grades. \
![{4184510C-C2E3-42E1-852C-4C8460032AAB}](https://github.com/user-attachments/assets/517e7be5-103f-466a-98ca-5fda1d4f6bb6)
![{56890297-98FA-4260-ACDF-9BE0A6B34F81}](https://github.com/user-attachments/assets/6a8d713c-e29b-4768-8e53-46d146af3785)

### Q6
Find names and grades of students who only have friends in the same grade. Return the result sorted by grade, then by name within each grade. \
![{B5674170-BEE4-403A-84F2-95BFDEBA41C9}](https://github.com/user-attachments/assets/e447cff9-c22e-4b10-973c-7372a7314f6c)
![{D448901F-1724-4B15-8650-2C5C3571A41D}](https://github.com/user-attachments/assets/e9d08e87-bbcf-403d-b1b1-20e034380718)

### Q7
For each student A who likes a student B where the two are not friends, find if they have a friend C in common (who can introduce them!). For all such trios, return the name and grade of A, B, and C. \

### Q8
Find the difference between the number of students in the school and the number of different first names.
![{D19F1211-874E-4972-AAB3-BCB1C054A763}](https://github.com/user-attachments/assets/c7979c55-fa72-483f-b397-e7f1bc9c9b33)
![{5647B421-37E7-424B-8199-B8D3F82BED69}](https://github.com/user-attachments/assets/a8d77572-4cee-47a9-8311-a12c6316a473)

### Q9
Find the name and grade of all students who are liked by more than one other student.
![{699A365D-7341-42A3-A728-92A295A1C1EC}](https://github.com/user-attachments/assets/1e3fa83a-fa44-4fb8-bcf8-24a79201d3d5)
![{BD471C34-B614-4747-AECE-16B085476A71}](https://github.com/user-attachments/assets/669674a7-ed7a-472c-b011-e50aa626fafc)


### **Social-Network Query Exercises Extras**
### Q1
For every situation where student A likes student B, but student B likes a different student C, return the names and grades of A, B, and C. \
![{3ACCDAEF-26BE-40D7-A26F-1DFCC2994E71}](https://github.com/user-attachments/assets/42e8189c-db7c-4ca5-ad09-d79eb4ddda85)
![{4C08484C-6958-402E-B610-B827760FC892}](https://github.com/user-attachments/assets/04f99705-bddc-44d6-88a1-955075383d63)

### Q2
Find those students for whom all of their friends are in different grades from themselves. Return the students' names and grades. \
![{8B63E70E-0177-4DEB-AF8E-759B96606BF3}](https://github.com/user-attachments/assets/53443620-415e-4c32-93a7-1c2ceb41bb9a)
![{81294962-396D-4349-B7E7-5E6C019404F0}](https://github.com/user-attachments/assets/495fa803-15cd-4a4f-a294-26988a4d3d70)

### Q3
What is the average number of friends per student? (Your result should be just one number.) \
![{E0DA1BD0-B9BC-4CA4-805A-06638C59C4BB}](https://github.com/user-attachments/assets/3eb3db26-6f44-4cc2-805a-61373f0ee263)
![{D28EC3EE-A6B0-47E5-8754-D886FC397133}](https://github.com/user-attachments/assets/deb50461-220d-4471-b952-e36042f6e6ff)

### Q4
Find the number of students who are either friends with Cassandra or are friends of friends of Cassandra. Do not count Cassandra, even though technically she is a friend of a friend. \
![{FF060C69-6BEE-441E-9AF7-D0A6EB16E7D8}](https://github.com/user-attachments/assets/b2d5f5bc-793f-464a-a3b3-b89d6b9020f0)
![{700ACAB3-9FB5-4FE2-99E6-D9A4787145C3}](https://github.com/user-attachments/assets/08f3fb71-7aea-44d5-92dd-3c6060160da8)


### Q5
Find the name and grade of the student(s) with the greatest number of friends. \
![{8601F3AD-F2D9-469D-9DEF-03E8B3396376}](https://github.com/user-attachments/assets/129270ce-670d-4bd6-b9aa-966520420bc4)
![{87FC06E2-8F69-4448-A427-68D5AD894E63}](https://github.com/user-attachments/assets/3f720f1a-1d32-4213-be84-d26c8a1e6005)
