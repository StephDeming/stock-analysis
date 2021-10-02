# stock-analysis
**#Overview**

Helping a client with a more efficient data colletion for a large dataset spanning two years(2017 and 2018). The goal was to loop through the dataset once and resive a faster result than with the initial coding.  

**#Comparison**


I dont't understand the stock market or what a lot of the terms mean. However, the returns for 2017 seem remarkably high compared to 2018. in 2017 "DQ"(the initial stock that we were watching) had a return of 199.4%, in 2018 it dropped to -62.6%.  "ENPH" seemed to hold value relatively well with a return of 129.5% in 2017  and 81.9% in 2018. There were some drastic changes, as evidenced by "RUN" who went from a 5.5% return in 2017 to a 84% return in 2018. The outcomes of both years are shown below. 
![2017_stocks](https://user-images.githubusercontent.com/90067477/135732705-3bb43c21-c7f6-48c9-80cc-a03ee57084cb.png)
![2018_stocks](https://user-images.githubusercontent.com/90067477/135732706-f269bfdb-ecfc-4b18-9ee6-059b1588dd39.png)

The initial code had this loop 

![initial_loop_code](https://user-images.githubusercontent.com/90067477/135732731-df5434ff-72dd-474e-b695-c5e3d4134324.png)

which ran in .71875 seconds for 2017 and .7148438 for 2018

![VBA_2017_initial](https://user-images.githubusercontent.com/90067477/135732030-63792d4d-e988-41b0-a11c-d9aea9d76c3c.png)
![VBA_2018_initial](https://user-images.githubusercontent.com/90067477/135732034-bea40482-5a48-4542-8a20-b2fa4129cfd0.png)

The refactored loop

![refactored_loop](https://user-images.githubusercontent.com/90067477/135733191-286b7a1e-fc39-484a-bd50-5ddb7a335faa.png)

was much more efficient and the textboxes more informational as they included the year. 2017 ran in .4257813 seconda and 2018 in .4765625 seconds. 
 
![VBA_Challenge_2017](https://user-images.githubusercontent.com/90067477/135732038-057f1bcc-79e8-47e5-a250-16f18b4f4361.png)![VBA_Challenge_2018](https://user-images.githubusercontent.com/90067477/135732042-18264566-722d-4592-bb93-d31acaf9d05b.png)

##Summary
After spending the time and doing this work I understand that refactoring code is important. However, the old adage of "if it ain't broke, don't fix it" also comes to mind. The initial code ran through the arrray and did the job it was supposed to.

Refactoring the code gave more efficient variables to use and made the loops easier to understand. I can see that once you have experience and really understand what you're doing that it would be a very valuable skill. And the output time was cut in almost half, which was suprising and very useful in the right circumstance.

Pro's and cons boil down to a sunk time equation here. If it's a huge range of data and is a clunky or hard to understand code then making it streamlined is the efficient thing to do. it it doesn;t need it, I'd just leave it alone. 
