## Databases Mandatory Assignment - A1

### **Movie-Rating Query Exercises**
### Q1
Find the titles of all movies directed by Steven Spielberg.
![{F2232B31-8B0B-4013-9AAF-BBE94D18E927}](https://github.com/user-attachments/assets/1f8f18f9-97a4-4f41-8536-2c6f7d81b680)
![{1927F23E-A500-4998-B96B-95E25EA85EF8}](https://github.com/user-attachments/assets/b5b27411-c338-4167-a53b-3856886233e1)

### Q2
Find all years that have a movie that received a rating of 4 or 5, and sort them in increasing order. \
![{3C51B64A-871E-4AD5-9942-AAE3C71D3CD2}](https://github.com/user-attachments/assets/15afb1ee-99f0-44ad-af89-7b00c17dbec7)
![{1E917D81-BB61-4F44-B855-FA6383A43C0C}](https://github.com/user-attachments/assets/d02bb3ac-25ee-4074-bedd-3839f55b3d45)

### Q3
Find the titles of all movies that have no ratings.
![{1A7F2F42-5C6E-4FCB-93E3-EEF2D7A24C92}](https://github.com/user-attachments/assets/2cc370b6-4414-49bd-af01-f263732c317c)
![{174F6A54-11D6-495A-A179-1EA25904DC5A}](https://github.com/user-attachments/assets/0c69585f-6f9c-483e-b729-3b92f18c412a)

### Q4
Some reviewers didn't provide a date with their rating. Find the names of all reviewers who have ratings with a NULL value for the date.
![{B54C4FF7-49EE-4CAD-907D-C02D14D60C1C}](https://github.com/user-attachments/assets/970cdbb7-4e10-4ebb-8d18-fd22cb4bdeba)
![{75C9E522-C8D8-4C79-9F16-41DDEBFB2CE7}](https://github.com/user-attachments/assets/a86e9400-5505-47c5-afaf-f35099fd8518)

### Q5
Write a query to return the ratings data in a more readable format: reviewer name, movie title, stars, and ratingDate. Also, sort the data, first by reviewer name, then by movie title, and lastly by number of stars.
![{820C6B42-387D-47FB-A908-2D4E34E5B410}](https://github.com/user-attachments/assets/f3b499e5-7632-43c1-9f40-b087850c21cc)
![{1AE6EC7B-FFCA-440F-95C6-74CD9640ADD4}](https://github.com/user-attachments/assets/c86a0928-9617-48df-bbde-0094ef61013a)

### Q6
For all cases where the same reviewer rated the same movie twice and gave it a higher rating the second time, return the reviewer's name and the title of the movie.
![{B2B484B9-CB78-4D5F-B042-DD21A612F96F}](https://github.com/user-attachments/assets/79f564f2-154b-4b12-aa36-0cadc830b2c3)
![{4FA287E5-37F8-4879-A97C-BDA9A7276DDB}](https://github.com/user-attachments/assets/24dc7db7-2a98-4255-bc9e-513d5363affd)

### Q7
For each movie that has at least one rating, find the highest number of stars that movie received. Return the movie title and number of stars. Sort by movie title. \
![{A5A5FE41-BE96-485A-A0A5-3D013AF8DEEB}](https://github.com/user-attachments/assets/be863be5-e0c6-406d-a803-6b5ba1362f92)
![{8A4BA352-26DD-4492-9B81-952047EA323C}](https://github.com/user-attachments/assets/e4d13062-bd14-4d0d-bc48-30dc07a60ddb)

### Q8
For each movie, return the title and the 'rating spread', that is, the difference between highest and lowest ratings given to that movie. Sort by rating spread from highest to lowest, then by movie title. \
![{558739B6-7EE3-4D21-87D7-A6C3A4D81E12}](https://github.com/user-attachments/assets/8ba1ae82-4bb0-47aa-9b71-db56d4e4ad18)
![{F408EE73-ACC3-46BC-8958-F5EDD1D28D85}](https://github.com/user-attachments/assets/9f3c94eb-98f9-40ce-8992-ba0d8bc7a82b)

### Q9
Find the difference between the average rating of movies released before 1980 and the average rating of movies released after 1980. (Make sure to calculate the average rating for each movie, then the average of those averages for movies before 1980 and movies after. Don't just calculate the overall average rating before and after 1980.)
![{686764B1-5355-4331-AE74-DB371F411712}](https://github.com/user-attachments/assets/c8ee065d-d03e-42ef-8b8d-21edc88ccc6e)
![{584E48E4-93A0-4E02-8526-692980297606}](https://github.com/user-attachments/assets/a4136eed-6922-484a-99d5-d3d548cd87b8)




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
