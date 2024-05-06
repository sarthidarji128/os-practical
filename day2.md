Question 1> write a shell script thats print shell scripting is fun on the screen
Answer: echo "Shell scripting is a Fun"

<img width="554" alt="Screenshot 2024-05-06 at 4 40 48 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/ffe16329-e04c-4d5a-a75b-85f4716eef39">


Question 2> write a shell script for modify the shell script , variable holds the contain of the msg shell script is nice 
Answer :
vi s.sh

name="shell script is nice"
         
echo "$name"


         
<img width="545" alt="Screenshot 2024-05-06 at 4 55 57 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/8dd0c932-43e4-4c54-b6fb-ccf568b6dd8d">



Question 3> Exercise_3 - Store the output of the command “hostname” in a variable. Display “This script is running on _.” where “_” is the output of the “hostname” command.



host=$(hostname)

echo "This script is running on $host."


<img width="457" alt="Screenshot 2024-05-06 at 5 07 00 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/b79b4311-379a-4869-b273-6d57ec2a9e44">


Question 4> Exercise_4 - Write a shell script to check to see if the file “file_path” exists. If it does exist, display “file_path passwords are enabled.” Next, check to see if you can write to the file. If you can, display “You have permissions to edit “file_path.””If you cannot, display “You do NOT have permissions to edit “file_path””



Answer: 

file="p4.sh"
echo "$file"
if [ ! -f "$file" ]; then
        echo "file does not exist $file"
else
        echo "file found $file"
fi

<img width="554" alt="Screenshot 2024-05-06 at 5 17 06 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/9ddbfa30-86c6-4494-a239-5f40f4e9850b">


question 5>Write a shell script that displays “man”,”bear”,”pig”,”dog”,”cat”,and “sheep” on the screen with each appearing on a separate line. Try to do this in as few lines as possible.

Answer : 

name="man"
echo "$name"
echo
name="bear"
echo "$name"
echo
name="dog"
echo "$name"
echo
name="cat"
echo "$name"
echo
name="sheep"
echo "$name"
echo



<img width="549" alt="Screenshot 2024-05-06 at 5 52 08 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/3670d0c9-b2b4-4d4b-ae5d-4cc241b48d03">






