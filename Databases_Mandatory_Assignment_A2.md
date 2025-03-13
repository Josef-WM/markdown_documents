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


### **Movie-Rating Query Exercises Extras**
### Q1
Find the names of all reviewers who rated Gone with the Wind. \
![{AA3F3894-92E5-4296-AC5F-EE2F91282182}](https://github.com/user-attachments/assets/e422eb54-b016-44b3-bef8-536e18f563c6)
![{8A7E3215-9E4B-44C6-883E-2BA49E35856E}](https://github.com/user-attachments/assets/718e2b98-3142-46c8-9aae-2c067696ff95)

### Q2
For any rating where the reviewer is the same as the director of the movie, return the reviewer name, movie title, and number of stars. \
![{FBD5436B-E17E-461E-B4E5-280EA10870B9}](https://github.com/user-attachments/assets/c1804475-dc64-4d2d-bc0d-f2ef6084acd9)
![{82351243-6783-4180-A2A8-20849459144E}](https://github.com/user-attachments/assets/b12fb8c5-93f1-4192-b4ea-af194dd1a6d5)

### Q3
Return all reviewer names and movie names together in a single list, alphabetized. (Sorting by the first name of the reviewer and first word in the title is fine; no need for special processing on last names or removing "The".) \
![{6881C641-40E6-432E-8B5D-2EE1D9DC3617}](https://github.com/user-attachments/assets/09bf164c-5f51-4288-bb51-49bd4a28bab1)
![{C8D73019-A06E-44D0-B1BD-0089A559B3BE}](https://github.com/user-attachments/assets/0503d30e-ccae-43f5-9cf3-1e8e8525b429)

### Q4
Find the titles of all movies not reviewed by Chris Jackson. \
![{53B65157-A334-4302-81B4-11BCCD5CB2D1}](https://github.com/user-attachments/assets/f8a5b079-584d-4ffc-8897-96a34f5341b8)
![{F3867530-C930-42A6-85BA-2F5F271738E9}](https://github.com/user-attachments/assets/414406b3-ee94-4d74-8b18-475029d259ed)

### Q5
For all pairs of reviewers such that both reviewers gave a rating to the same movie, return the names of both reviewers. Eliminate duplicates, don't pair reviewers with themselves, and include each pair only once. For each pair, return the names in the pair in alphabetical order. \
![{95A38CF9-C661-493C-8C4F-84339CA04484}](https://github.com/user-attachments/assets/abe4c260-aeea-4a5c-a437-4187ba6683e1)
![{B3833011-7F36-4074-8030-3D84CCBEEB75}](https://github.com/user-attachments/assets/c1410dc7-97c5-44ca-b84d-7658e4c695de)

### Q6
For each rating that is the lowest (fewest stars) currently in the database, return the reviewer name, movie title, and number of stars. \
![{872D34C6-8DAE-4AFD-9902-1B605E07206C}](https://github.com/user-attachments/assets/c999c45f-d652-49ae-8cfd-a7b8e375364a)
![{68E0AEA9-C800-4EA8-97AD-CE980FDDAA6A}](https://github.com/user-attachments/assets/80c20db6-48e5-4eef-b598-416b0a66109d)

### Q7
List movie titles and average ratings, from highest-rated to lowest-rated. If two or more movies have the same average rating, list them in alphabetical order. \
![{B6013CB5-5E10-48D2-A366-3E172489DAFF}](https://github.com/user-attachments/assets/24f44ca8-ecf7-40f2-8392-4b259dfa41d2)
![{FF401217-2F5A-4174-9DAA-AFBEED62B440}](https://github.com/user-attachments/assets/b3cde660-7c6c-4103-9556-a500928b6705)

### Q8
Find the names of all reviewers who have contributed three or more ratings. (As an extra challenge, try writing the query without HAVING or without COUNT.) \
![{1CD3F042-33A1-493F-B856-62192190B1E9}](https://github.com/user-attachments/assets/70ad2c9e-4fd6-4528-9f82-af165b969222)
![{81C4F3E6-ABA0-4213-A63B-E547E573AE73}](https://github.com/user-attachments/assets/d8a30d5d-2a3a-46bf-a0ed-1859fcdb786b)

### Q9
Some directors directed more than one movie. For all such directors, return the titles of all movies directed by them, along with the director name. Sort by director name, then movie title. (As an extra challenge, try writing the query both with and without COUNT.) \
![{B229C352-CC4B-460B-B7D2-6C701967117D}](https://github.com/user-attachments/assets/bea45d9d-6a45-4aaf-9cab-862f6dc7c166)
![{86083ED1-F90C-4697-93F2-9A49B7822EC8}](https://github.com/user-attachments/assets/80352439-7dde-4e78-a721-168d31cccd9b)


### Q10
Find the movie(s) with the highest average rating. Return the movie title(s) and average rating. (Hint: This query is more difficult to write in SQLite than other systems; you might think of it as finding the highest average rating and then choosing the movie(s) with that average rating.) \
![{6A054E07-332B-4197-BD73-0759773F713B}](https://github.com/user-attachments/assets/8beb5a68-076a-4716-85cc-442dc1f75b19)
![{9DCA6884-4547-4A10-8107-A13CA09BBC7D}](https://github.com/user-attachments/assets/b196bed5-43b2-4ee1-9380-07e621ee282e)

### Q11
Find the movie(s) with the lowest average rating. Return the movie title(s) and average rating. (Hint: This query may be more difficult to write in SQLite than other systems; you might think of it as finding the lowest average rating and then choosing the movie(s) with that average rating.) \
![{40C15730-2B78-4DB7-A130-594B3265A569}](https://github.com/user-attachments/assets/a1d2a01f-f669-4bf8-b516-2a14c6b632ac)
![{01864EE3-F772-4EE8-9382-C63A6201C09C}](https://github.com/user-attachments/assets/8f4d9c2c-4ea0-4ccc-a5b2-f2e6f1516110)

### Q12
For each director, return the director's name together with the title(s) of the movie(s) they directed that received the highest rating among all of their movies, and the value of that rating. Ignore movies whose director is NULL. \
![{84A6B1BA-51EC-4D2E-9894-7708D14A1588}](https://github.com/user-attachments/assets/3ac84d5a-060d-45d3-ab77-153698be46bb)
![{CBA1D3C7-609C-4D62-AAE3-91E1CD6DC7B7}](https://github.com/user-attachments/assets/d114d9b6-007c-472c-9ad4-532ec6e53b69)
