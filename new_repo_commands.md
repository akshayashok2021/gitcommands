## Create your first repository

### Steps: 
1) Create a empty folder on your desktop
2) Create a text file with filename "workshop" inside the created folder
3) After Creating the file Execute the below commands 

Command | Description  
--- | --- 
git init | Initializes the repository as git repository
git config user.name "Replace_with_your_github_username" | add username to git configuration
git config user.email "Replace_with_your_github_email"   | add email to git configuration
git config --list                                        | view the git configuration 
git add "workshop.txt"                                   | add your file 
git commit -m "Added workshop file"                      | Commit your changes to git


### Configure SSH key

1) #### Go to Settings of your repository
![image](https://user-images.githubusercontent.com/84670431/120062427-f6448f80-c07f-11eb-97a6-b8cfd66f2f40.png)

2) #### Click on SSH and GPG keys
![image](https://user-images.githubusercontent.com/84670431/120062496-31df5980-c080-11eb-94e4-7ba8c0953008.png)

3) #### Edit the below command and insert your github email and Run the below command in your command prompt 
``` 
ssh-keygen -t ed25519 -C "your_email@example.com" 
``` 

4) #### If you already have a SSH key in your system you will be prompted to overwrite you can type "y" and hit enter
5) #### You will be prompted to "enter a passphrase", you can press enter 
6) #### You will be prompted to "enter same passphrase again", you can press enter again  
7) #### Copy the directory where the key is stored into
![image](https://user-images.githubusercontent.com/84670431/120062943-4b81a080-c082-11eb-9c6b-77f913c741d6.png) 
8) Go to the directory and you must be able to see the new ssh key

