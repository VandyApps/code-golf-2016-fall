# Code Golf


### Overview
This competition focuses on short and succinct code. 
The challenge is to produce answers to the provided problems with as little code as possible.
Your score for each problem will be the file size of your source code for that problem. Your code will not be run,
nor will it be checked for correctness. We will assume that your code runs and produces the correct output.
However, we will have the 1st, 2nd, and 3rd place contestants run their code live for proof that
it runs and proof that it produces the correct output.
* **The actual code you submit cannot be generated text**
* Your code cannot call any external processes
* Your code must be able to be run independently of any other personal files (i. e. you can use standard libraries and other modules but you can't write code in another file and simply call it in your submission file)

### Submission
You will need to submit the source code for each question, so there will be a total of 6 files to submit.
Make a GitHub repository for these six files, and just copy and paste your repository link [here](https://docs.google.com/a/vanderbilt.edu/forms/d/e/1FAIpQLSfRFw3QpcDT8isA3lH1iNk3xvMhMzqeA6-FPLrShLZVs4VrSg/viewform)
* each file must have the problem number somewhere in its name
* you should only submit your source code files and nothing else
* there should be no dots ("." charachters) in your filename except before the extension
* the file size of your file will be evaluated with the python function [os.path.getzise](https://docs.python.org/2/library/os.path.html?highlight=os.path.getsize#os.path.getsize) on an Ubuntu OS. Make sure this is not problematic for your source code.
* **you cannot compress your files** you must submit your raw source code

#### Sample Valid Filenames:
* prob_1.py
* prob1.py
* 1.java
* jibberish1jibberish.cpp

#### Sample Invalid Filenames:
* i_dont_contain_a_number.py
* x.java
* get.ridOfThatExtraDot.cpp
* .filename.java

### Questions

1. Write code that lists all of the years since 0 CE that have been prime and a palindrome.
2. Produce this ASCII art:

        |_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|
        /*_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*
        |_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|
        /*_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*
        |_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|
        /*_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*
        |_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|
        /*_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*
        |_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|
        /*_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*
        |_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|_/*\_|
        /*_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*/_|_\*

3. Print out Vanderbilt's phone number, 1 (615) 322-7311, without using any numbers in your source code
4. Print out all 50 US capital cities in order of their latitude
5. Print out a flattened version of this array (i. e. bring all the elements out into one flat list containing only integers at each index):

        
        [[94, 78, 73, 19, 99, 23, 45, 98, 44, 4], [[6, 60, 20], [75, 34], [12, 10], [53, 34], [99, 100, 51], [1, 18], [23, 6], [4, 100], [55, 25], 73, 94, 49, 66, 2, 11, 14, 84, 21, 68, 100, 81, 75, 29, 37], [[6, 25, 59, 33], [15, 96, 66, 85], [33, 76, 22, 18, 16], [[88, 19], [46, 22, 3], [85, 42], [50, 36, 29], 63, 15, 85, 8], [[12, 68], [10, 59, 27], [74, 90], [86, 75], [83, 55, 64], [100, 32], [76, 69], [15, 70], 43, 88], [84, 75, 42, 36, 96, 6], [64, 85, 94, 76, 5], [[69, 40, 69, 45], [68, 72], [20, 71], [87, 18], 14, 26, 28], 83, 74, 60, 31, 94, 20, 67, 1], [[3, 52, 72, 14], [38, 93], [41, 86, 90, 61], [100, 89, 40], 59, 8, 62, 45, 67, 13, 33, 100, 79, 23, 86, 57, 34], [11, 48, 66, 93, 28, 29, 47, 10, 1], [76, 68, 100, 60, 38, 100, 37, 75, 8, 7, 27], [77, 12, 25, 82, 90, 47, 87, 95, 71], [[100, 69, 90, 88], [[37, 52], [5, 5, 65], [93, 31, 35], [51, 35, 84, 19], 47, 46, 36, 78, 48, 76, 10, 39, 21], [95, 9, 29, 79, 16, 53, 88, 38, 20, 93], [18, 42, 50, 58], [[38, 14], [60, 6, 100], [69, 77, 68, 4], [7, 59], 82, 75, 17, 61, 90], [45, 67, 31, 50, 33, 32, 98, 6], [[66, 88, 67], [16, 93], [85, 87, 24], [46, 69, 53], 26, 40, 51, 18, 47, 41, 17], [21, 79, 31, 77], [73, 53, 83, 54], [49, 35, 46, 43], [40, 77, 68, 70, 53], [84, 20, 70, 51], [91, 34, 100, 41, 98, 24, 66], [39, 6, 80, 70, 72, 70, 61, 72], [10, 28, 37, 31, 55], [100, 67, 99, 68, 9, 7, 50, 69, 89, 34], [70, 51, 65, 94, 24, 96, 34], 29, 72, 55, 68, 18, 7, 29, 10, 5], [[62, 16, 24, 71, 41], [23, 2, 65, 31], [45, 6, 91, 61, 18], [28, 31, 52, 25, 79, 62, 75, 58], [30, 69, 7, 42, 43, 99, 75], [5, 4, 52, 60], [69, 2, 83, 67, 88, 94], [15, 94, 78, 2, 24], [52, 100, 3, 24, 69, 42], [91, 11, 41, 27], [37, 38, 87, 84, 66, 22], [29, 81, 4, 10, 73, 51, 30, 63, 84], [95, 80, 30, 18], 97, 72, 51, 6, 69, 18, 39, 26, 42, 16], [[30, 79, 43], [65, 4, 100, 10, 18, 50, 51, 71], [18, 29, 51], [58, 60, 37, 70, 40, 23, 62], [8, 49, 20], [90, 38, 92, 2, 24], [7, 51, 56], 98, 33, 9, 97, 63, 36, 99, 33], [56, 69, 70, 26, 69, 73, 8, 36, 73], [[13, 44, 40, 85], [2, 63, 50, 77, 34, 24, 87, 81, 32, 36], [96, 90, 75, 15, 58, 23, 4, 5], [37, 49, 89, 27], [89, 3, 83, 71, 40, 47], [51, 11, 11, 63], [66, 45, 57, 17, 7, 56], [32, 53, 32, 43, 51, 69], [100, 3, 10], [52, 100, 81, 66], [71, 68, 28], [75, 96, 83, 73], [27, 49], 73, 58, 7, 50, 98, 15, 14, 68], [[59, 68, 19, 34], [32, 93, 1, 31, 26, 68], [35, 86, 48, 95, 91, 85, 83, 18, 31, 34, 66, 27], [48, 93, 55, 10, 96, 71, 81], [32, 59, 45, 7, 4], [99, 46, 77, 79], [39, 24, 16, 45, 14, 62, 71], [46, 23, 18, 74, 94, 11, 60, 77, 75, 87, 47], 99, 42, 45, 65, 21, 38, 92, 33, 7], [[66, 91], [1, 62], [46, 2, 9, 89], [51, 25, 89, 67], 98, 56, 13, 63, 36, 84, 53, 13, 83, 12, 43, 49, 97], [92, 37, 99, 30, 99, 90, 34, 79, 81, 9, 71, 31], [[64, 8, 96, 23, 41], [9, 83, 34, 26, 73, 48, 95], [[78, 53, 41], [62, 39], [63, 48], [50, 4], 35, 63, 66, 15, 33, 64], [78, 76, 66, 62, 18], [[52, 35, 96, 97], [30, 17], [5, 62, 53], [83, 38, 97, 18], 17, 2, 40, 47, 99, 79, 43], [[66, 16], [1, 9, 44], [33, 81], [36, 34], [53, 57, 95], [64, 34], [31, 94, 16, 46], [23, 69], 40, 47, 19, 78, 72], [[21, 70], [4, 58], [67, 9], [12, 1], 23, 80, 85], [47, 49, 69, 18, 76, 24, 91, 13, 3], 57, 98, 35, 23, 84, 96, 65, 18], [50, 97, 71, 82, 100, 71, 36, 36, 48, 38, 94, 3], [18, 3, 50, 1, 48, 76, 79, 30, 34], [84, 22, 81, 77, 26, 17, 96, 86, 23], [98, 9, 1, 95, 95], [[27, 79, 81], [6, 63], [7, 29], [54, 75, 46, 56], 42, 3, 2, 48, 33, 25], [72, 68, 65, 23, 35, 41, 95, 91], [5, 78, 41, 54, 45, 44, 2, 58, 43, 55, 40, 38], [[66, 64, 77], [71, 29, 12], [40, 63, 41], [25, 34, 59, 63], 90, 97, 26, 87, 13, 54, 100, 85], [27, 6, 63, 47, 99, 56, 78, 82], [[79, 69, 99, 4], [37, 37], [13, 1], [38, 23], [53, 78, 40], [71, 30], [60, 12, 65, 88], [54, 3, 14], [38, 33], [23, 55, 48, 84], [45, 65], [88, 38], [24, 98, 7], 84, 96, 26, 62], [[45, 48, 87], [54, 82, 60], [63, 3, 71, 64], [42, 48, 4], 9, 55, 93, 86], [91, 9, 63, 71, 5], 20, 36, 84, 21, 23, 53, 94, 42, 27, 81, 9, 20, 50, 6, 58, 5, 66, 79, 61, 40, 87, 32, 98, 20, 53, 95, 3, 43]

6. Print out, in chronological order, each world series victor's name, the year, and then the product of the year and the length of their team name. For example:

        Boston Braves, 1914, 24882

    because length('Boston Braves') = 13, and 13 * 1914 = 24882
