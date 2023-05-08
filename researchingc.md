# Researching Commands

## Command Grep

### 1st interesting commands(grep -r)

<img width="464" alt="Screen Shot 2023-05-07 at 10 26 18 PM" src="https://user-images.githubusercontent.com/130090548/236741207-5933e531-b20b-4fe4-8707-3d2b73657762.png">

From the picture we are using the command grep -r that searches for the string "base paif" in all files under the derictory of both technical/biomed and technical/plos and count the number of lines that containt this specific string. It is useful because it allows you to search for a specific string or pattern in all files under a directory, including subdirectories.

 [Credit ](https://www.gnu.org/software/grep/manual/grep.html).
### 2nd interesting commands ( grep -c)

<img width="927" alt="Screen Shot 2023-05-07 at 10 46 49 PM" src="https://user-images.githubusercontent.com/130090548/236743845-66f08227-2d59-4c0c-bdbf-c38fa872eee1.png">
 
From the picture we are using the command grep -c that essentially counts the number of occurences of a specific string or pattern in a file or directory. THis is is useful because you might use this command to count the number of lines in a log file that contain a particular error message, or to count the number of instances of a specific word in a large text file.

 [Credit ](https://www.gnu.org/software/grep/manual/grep.html).


### 3rd interesting commands ( grep -B)

<img width="914" alt="Screen Shot 2023-05-07 at 10 50 40 PM" src="https://user-images.githubusercontent.com/130090548/236745123-9b45a06d-63d8-47ae-afb6-dcb6fd1e94c1.png">

<img width="1512" alt="Screen Shot 2023-05-07 at 10 54 42 PM" src="https://user-images.githubusercontent.com/130090548/236745129-735c9ea2-d678-475f-a168-55cad19b8563.png">


 [Credit ](https://www.gnu.org/software/grep/manual/grep.html).

From the picture we are using the command grep -B that shows before the match and will print out not only the line containing the matching string, but also the 2 lines before the matching line. For example, if you are searching for instances of the string "RNA" in a large file, you may want to see the surrounding lines to get a better idea of the context in which "RNA" appears.

### 4th interesting commands( grep -v)

<img width="1512" alt="Screen Shot 2023-05-07 at 11 03 53 PM" src="https://user-images.githubusercontent.com/130090548/236746846-3f53ec54-b772-470a-866d-a56c06eaf387.png">

<img width="1512" alt="Screen Shot 2023-05-07 at 11 06 40 PM" src="https://user-images.githubusercontent.com/130090548/236746862-fe8c45fa-ad95-4f48-8444-ea5f45d8e60e.png">


 [Credit ](https://www.gnu.org/software/grep/manual/grep.html).

From the picture we are using the command grep -v. This command uses the -v option to print out all lines that do not match the specified string "RNA" in the file. This is useful because if you have a large file with a lot of information, you might want to filter out certain lines that are not relevant to your needs.
