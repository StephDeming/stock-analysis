# stock-analysis
Overview of Project: Explain the purpose of this analysis.
Helping a client with a more efficient data colletion for a large dataset spanning two years(2017 and 2018). The goal was to loop through the dataset once and resive a faster result than with the initial coding.  

Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
I dont't understand the stock market or what a lot of the terms mean. However, the returns for 2017 seem remarkably high compared to 2018. in 2017 "DQ"(the initial stock that we were watching) had a return of 199.4%, in 2018 it dropped to -62.6%.  "ENPH" seemed to hold value relatively well with a return of 129.5% in 2017  and 81.9% in 2018. There were some drastic changes, as evidenced by "RUN" who went from a 5.5% return in 2017 to a 84% return in 2018. The outcomes of both years are shown below. 
![2017_stocks](https://user-images.githubusercontent.com/90067477/135732705-3bb43c21-c7f6-48c9-80cc-a03ee57084cb.png)

![2018_stocks](https://user-images.githubusercontent.com/90067477/135732706-f269bfdb-ecfc-4b18-9ee6-059b1588dd39.png)

The initial code had this loop 
![initial_loop_code](https://user-images.githubusercontent.com/90067477/135732731-df5434ff-72dd-474e-b695-c5e3d4134324.png)
which ran in .7304688 seconds for 2017 and .738281 for 2018
![VBA_2017_initial](https://user-images.githubusercontent.com/90067477/135732030-63792d4d-e988-41b0-a11c-d9aea9d76c3c.png)
![VBA_2018_initial](https://user-images.githubusercontent.com/90067477/135732034-bea40482-5a48-4542-8a20-b2fa4129cfd0.png)

The refactored loop seemed tp be less efficient when running in 2017 at .7421875

![VBA_Challenge_2017](https://user-images.githubusercontent.com/90067477/135732038-057f1bcc-79e8-47e5-a250-16f18b4f4361.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/90067477/135732042-18264566-722d-4592-bb93-d31acaf9d05b.png)

Summary: In a summary statement, address the following questions.
What are the advantages or disadvantages of refactoring code?
How do these pros and cons apply to refactoring the original VBA script?
