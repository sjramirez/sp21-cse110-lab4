# Answers for part 1 
### Part 1a
1. 20 is printed to the console on line 9
2. 20 is printed to the console on line 13
3. 20 is printed to the console on line 9
4. at line 13 there is an error and this is because the variable result is only in the scope of the if statement so result is undefinded outside of that 
5. the code returns an error when trying to reassign the value of result since it is a const type it can not be redefined so when we tried to redefine it we encountered an error
6. same as 5
### Part 1b
1. at line 12 it will print 3 to the consile and this is because i was instanciated with a var keyword so its scope is not just limited to the for loop and can be acsessed after the for loop has terminated and the for loop terminated hen i = 3 so it stayed at that value
2. at line 13, the console will print 150 and this is because discountedPrice was instanciated with a var keyword and can be acesssed outside of the for loop and the last thing it was assigned to was 300 * 0.5 and that equals 150 so that is hwat will be printed.
3.  at line 14 150 will be printed to the console since finalPrice was instanciated with the var keyword so it can be acsessed outside the for loop and the last this it was assigned to was to round 150 which would still be 150.
4.  this function will return an array with the newly discounted prices so in this case it would be an array of [50,100,150] and this is because for each item in the list that was passed in the discount was applied and added to the new list.
5.  This will cause a runtime error since i was instanciated with let, it can not be acsessed outside of the for loop so trying to acesss it outside of that loop will cause it to not be definedd creating an error.
6.  this will cause a runtime error since disocuntedPrice is instanciated with a let keyword inside the for loop you can not acsess it outside of that for loop and trying to do so will result in a runtime error
7.  This will print 150 and that is because finalPrice is instanciated outside of the for loop so it can be acsessed outside of it and will still be assigned to the last thing that it was assigned to which was to roud 150 so it will still be 150
8.  This function will return an array of the discounted prices so in this case it will be [50,100,150] the changing of the keyword from var to let does not affect the functionality of this function at all
9.  this will result in a runtime error for the same reason at #5 that is was instanciated in a for loop with a let keyword so trying to acsess it outside of that for loop will cause an error
10. This will print 3 as it is the length of this list as it was passed in and the const keyword does not restrict its acsess as long as its value is not changed
11. this will return a list of the newly discoutned prices in this ccase those are [50,100,150] and this is prefectly valid since we are never redefining and constant keywords and the one that we do do inside the for loop is okay because every iteration that variable is destroyed and created again.
12. Question 12
    1. a) student.name
    2. b) student["Grad Year"] 
    3. c) student.greeting()
    4. d) student["Favorite Teacher"].name
    5. e) student.courseLoad[0] 
13. Question 13
    1. a) '32' this is turned into a string concatination and concatinates the strings '3' and '2'
    2. b) 1 this instead turns the strng into an int and does normal subtraction
    3. c) 3 null is just iterpreted as zero so it is the same as 3 + 0
    4. d) '3null' this time since a string is first null is turned into a string and concatinated with the 3 string
    5. e) 4 true is interpreted as a 1 and added to 3
    6. f) 0 these are both interpreted as zeros so it is the same as zero plus zero
    7. g) '3undefined' similar to null undefined is concerted to a string and concatinated to the 3
    8. h) NaN this results in it being undefined so the output is NaN or undefined
 14. Question 14
     1.  a) true this is because '2' is converted to integer and then the comparison is done
     2.  b) false since these are both strings then they are compared in dictionary order making it false
     3.  c) true the string 2 is converted to an integer and then they are compared returning true
     4.  d) false for this it is a direct comparison that will not convert the string to an integer
     5.  e) false this is because true is converted to 1 and then compared and these are not the same 
     6.  f) true the boolean class will return a number that is greater than zero as the boolean true so then it is comparing true to true 

15.  the difference between the == and the === operator is that the == operation will type convert the argument and do a comparison after that while the === operation will not change the type and is instead a strict comparison without type changing.
16.  written in file part1b-question16.js
17.  So this function will return an array with all the elements of the previous array being doubled. I arrived at this conclusion for a few reasons. so starting off we are passing in two parameters one called array and the other called callback. then we are in the for loop iterating over the elements in a and applying the parameter callback to them. So looping at what we passed in as callback which was our function doSomething and that function doubles the numebr that was passed into it. so therefore we are itterating over all the elements in array and doubleing them by applying callback to them.
18.  written in file part1b-question18.js
19.  The output of the above code is 1 3 4 2 this is because the printing of the number 2 is delayed by one second so the other functions occur first and print their numbers then 2 prints after the tieout of one second.