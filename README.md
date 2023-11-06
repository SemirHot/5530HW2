# 5530HW2

<h1>Part 1</h1>
I started out by taking out all the NA values from the dataset, i was trying to come up with a formula to get an accurate price that i can replace the NA value with but there are too many factors to take
into account when trying to get the value that was missing for us such as condition, availability of that specific car in the area, maintenance records, and so on, If i were to assume those said factors listed 
i could be mistaking the value by a large margin and making the data set not lose the integrity of it. I did all that and then i saved it into cleaneddata.csv, if you want to take a look at it it will be under the data folder above. 

![image](https://github.com/SemirHot/5530HW2/assets/70181745/a71a6b71-8a21-4266-922e-0cf525f8a232)


<h1>Part 2</h1>
I went through and took off all the labels off the rows that had them, i ended up missing one, the one that was Cr but i ended up catching it later in part 4 as you will see. 

![image](https://github.com/SemirHot/5530HW2/assets/70181745/93e849a1-28f5-461d-84ae-27cba2957378)

<h1>Part 3</h1>
I went through and one hot encoded the transmission column. 

![image](https://github.com/SemirHot/5530HW2/assets/70181745/3a5ae168-4395-4bf2-badd-da641ab182c4)

<h1>Part 4</h1>
I did a few different additions to my dataset, I first caught the one i missed that wasnt deleted, the Cr, I converted both of them to floats bc i thought that was the issue before i caught the Cr but i just left it there even though it was not needed. First addition i did was the price change, i just took the original price minus the new price. Then i did the current age, i just did 2023 minus the year. Next i did the amount they spent on gas, i just looked up the price of fuel in the area these cars in and just multiplied them by kilometers driven/milage to get the total fuel cost. Lastly i know here in the USA they measure engines by liter size so i just found the conversion and applied it to CC to get that value. All the values that would give me long decimal i rounded them to 2 decimal points to keep the data set clean. 

![image](https://github.com/SemirHot/5530HW2/assets/70181745/b8de5f9d-410b-4e92-ab99-372515ce9e39)

