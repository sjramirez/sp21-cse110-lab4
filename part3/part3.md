# Answers to part 3

### Debugging 
1. The bug in this program was that instead of doing integer addition, the script was running string concatination since the variabels were never changed to ints they remained strings.
2. I fixed this by using the parseInt function to convert the strings to ints before adding them together.


### Networks
3. The file thaet appeared is caller citylots.json
4. part2.js was the file that called for citylots.json to be downloaded
5. citylots.json is 11.7 MB
6. citylots.json took 94ms to download
7. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36
8. Apache
9. Tue, 26 Jan 2021 22:14:13 GMT
10. application/json
11. The method inside the js file that retrieved the data was fetchData and that was triggered from the onClick ebent inside the HTML file.