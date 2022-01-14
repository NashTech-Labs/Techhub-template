# Techhub-template

### What is Tech-Hub Template 
 Knoldus Tech Hub is the one-stop solution to all your development requirement. You can learn and kickstart your development with these pre-built templates in no time. We have showcased all the technologies that are being used at knoldus and templates that can  make a good getting started experience for developers.
 
###  Purpose of this project
We've created this project, so that we can store all the Tech-Hub Templates contributed by knolders at this single place. You can find all the Tech-Hub Templates here only. 

### How to add Tech-Hub Template by using submodule

Step 1 - Clone the Techhub Template Repository
</br>
  ``` git clone https://github.com/knoldus/Techhub-template.git```
  
Step 2 - Create & Checkout to new branch using 
</br>
  ```git checkout -b <branchname> ```
  
Step 3 - You have to create a directory in your newly created branch. 
For example
</br>
a. java for Java Application 
</br>

  ```mkdir java && cd java```    
b. scala for Scala Application
</br>

  ```mkdir scala && cd scala```    
c. angular for Angular Application
</br>

  ```mkdir angular && cd angular```
  	
Step 4 - Now, create a submodule under this directory.
</br>
	```git submodule add <Your template repository URL>```
	
Step 5 - Push your changes to the code.
</br>
	``` git add.```
</br>
	```git commit -m "your message"```
</br>
	```git push -u origin <branchname>```

Step 6 - Raise a Pull Request from your branch to main branch.

Step 7 - Now, Click on git Actions to check your build. 


### Languages Used 
1. Java
2. Scala
3. Angular

### Build Tools Used 
1. Maven
2. Gradle
3. SBT

#### Note:- As of now we are using JDK Version 11 as default. If you want to use another version of java you will required to create a file named as :-

```cat >java-version.txt```
</br>

```8```
#### Now save the changes and whatever jdk version you want to use, mention in ```java-version.txt``` file as shown above like 8, Nothing else.

### You can use the following jdk versions
8
</br>
11
</br>
13
</br>
15
</br>
17

### You've to fullfil the criteria to merge a Pull Request
1. Make sure ```init job``` should be running successfully.
2. Make sure specific ```build job``` should be running successfully.
3. Rest jobs should be skipped.


