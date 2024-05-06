# os-practical
To list all files and directories in the current directory:
ls
<img width="567" alt="Screenshot 2024-05-04 at 4 14 30 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/fedc9b26-a28d-40c4-857a-aca7ee0cdd66">





 
To include hidden files (those starting with a dot) in the listing:
ls -a
<img width="532" alt="Screenshot 2024-05-04 at 4 15 47 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/e7be5e8d-7ba2-49ca-a3e3-73c2d36056fd">






To display detailed information about files and directories (long format):
ls -l
<img width="571" alt="Screenshot 2024-05-04 at 4 17 42 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/ab7b059e-524c-4d87-a29b-bd7454eb5c07">






To sort files by their last modification time (most recent first):
ls -t
<img width="560" alt="Screenshot 2024-05-04 at 4 19 08 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/573a9cf3-ce3c-4297-9128-104f3e3ede9d">






To list files and directories recursively (including subdirectories):
ls -R
<img width="564" alt="Screenshot 2024-05-04 at 4 20 01 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/31965dc0-0b21-487c-8755-97540b6670f7">





To print file sizes in a human-readable format (e.g., 1K, 234M, 2G):
ls -h
<img width="563" alt="Screenshot 2024-05-04 at 4 21 12 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/ed0c1db6-c590-4001-9517-401e3fa0eb4a">






To list directories themselves (rather than their contents):
ls -d
<img width="559" alt="Screenshot 2024-05-04 at 4 22 42 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/5a9f4b1a-761a-4baa-b457-154ef7536472">






To move inside a subdirectory, use the following command:
cd [directory_name]
cd Documents
cd /
cd ~
cd ..
<img width="560" alt="Screenshot 2024-05-04 at 4 27 37 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/c055e895-4713-45bc-8864-9d5ff69fe4b1">






In Linux, the mkdir command is like a magic wand for creating folders easily. It stands for “make directory” and helps you organize your computer files by creating directories with just one command.
To create a single directory, use the following syntax:
mkdir [directory_name]
<img width="547" alt="Screenshot 2024-05-04 at 4 29 30 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/252c59d2-1267-4fc6-a53b-5a043e16aeda">





To remove an empty directory, use the following syntax:
rmdir [directory_name]
<img width="553" alt="Screenshot 2024-05-04 at 4 32 32 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/92ea89fe-4eca-4b43-9b03-fc96b23d9c85">





If you want to copy the contents of one file to another, use the following syntax:
cp source_file destination
<img width="548" alt="Screenshot 2024-05-04 at 4 34 49 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/7b4b0b7e-0d68-471e-a308-9378a9e130f7">





To remove a file, use the following syntax:
rm [file_name]
<img width="561" alt="Screenshot 2024-05-04 at 4 36 28 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/6d945451-2d79-42b1-b55a-eb16f911ffd4">





To rename a file, use the following syntax:
mv [source_file_name] [new_file_name]
<img width="525" alt="Screenshot 2024-05-04 at 4 39 27 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/39e08b03-db93-465f-a695-2a29ee625b5a">




To open a file using the more command, simply type:
more [file_name]
<img width="558" alt="Screenshot 2024-05-04 at 4 40 38 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/2296998c-4567-4c52-9aff-dae8fe0dd533">




To print a file to the default printer, use the following syntax:
lpr [path/to/file]
![Screenshot 2024-05-04 at 4 43 56 PM](https://github.com/sarthidarji128/os-practical/assets/142773841/43e7a679-0f44-4bef-ab16-2e3070fac688)





The man command is a powerful tool in the Linux operating system that allows users to access detailed information about various commands, utilities, and system calls. Let’s explore how to use it:
Syntax of the man Command:
The basic syntax of the man command is as follows:
man [option] [command]
<img width="589" alt="Screenshot 2024-05-04 at 4 46 42 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/ee780b89-1e18-4e49-b557-d9f83a870bdc">




The most straightforward usage of grep involves searching for a specific pattern within a single file. Here’s the syntax:
grep pattern file_name
<img width="676" alt="Screenshot 2024-05-04 at 4 50 10 PM" src="https://github.com/sarthidarji128/os-practical/assets/142773841/38685634-7b31-4d7b-8c6d-bf35c7e41119">






The sed command is a powerful text stream editor in Unix/Linux systems. It allows you to perform various operations on files, such as searching, finding and replacing, insertion, and deletion, all without opening the files directly. Let’s explore some common use cases for sed:
Replacing or Substituting Text: To replace a specific word or pattern in a file, you can use the following syntax:

$ sed 's/unix/linux/' geekfile.txt


