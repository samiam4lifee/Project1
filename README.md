# Project 1: Sorting Algorithms

#Overview
This project is designed to test the efficiency of the most common sorting algorithms with data sets ranging from 1,000 up to 10,000,000. The algorithms are:
  -Insertion
  -Bubble
  -Merge
  -Quick
  -Radix

#Features
This code tests multiple sorting methods, generates multiple data sets, times how long each one takes per sorting method, and proceeds to terminate if the run time of the code exceeds 20 minutes to reduce the time it takes to fully run the code.

#Installation
  1. Download the Python Code
  2. Have Python 3 installed
  3. Ensure access to the random, time, and multiprocessing modules
      -If you have them, proceed to next step. If not, go ahead and install
  4. Run the script

#Useage
Run the script. You should have an outcome that looks like the following for each of the data set sizes:

Data Size: 100000
Insertion Sort: 186.68 seconds
Bubble Sort: 371.16 seconds
Merge Sort: 0.22 seconds
Quick Sort: 0.19 seconds
Radix Sort: 0.28 seconds

This will take some time as Insertion sort and Bubble sort are not designed to handle large segments of code and will take 20 minutes to run them for the 1,000,000 and 10,000,000 data sets each. 

#Experiment
To test the accuracy of the code, it was ran 5 times with all of the scores being documented. The lowest score out of all 5 runs were dropped, and the remaining 4 were averaged together in order to see if the code lined up with the expected outcomes based on the O-notation of each sorting method.

  -Insertion: O^2 -> Will run fine for smaller datasets but struggle with larger ones
  -Bubble: O^2 -> Will run fine for smaller datasets but struggle with larger ones
  -Merge: O(nlogn) -> Can handle both smaller and larger datasets
  -Quick: O(nlogn) -> Quite efficient with all datasets
  -Radix: O(nk) -> Can handle smaller datasets but more efficient with larger ones

After dropping the lowest scores from the 5 tests, this was my results
![image](https://github.com/user-attachments/assets/d79dfc0b-1344-4259-82d4-4f2d2d0cf0f5)


