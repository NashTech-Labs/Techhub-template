Techhub-template
What is Tech-Hub Template
Knoldus Tech Hub is the one-stop solution to all your development requirement. You can learn and kickstart your development with these pre-built templates in no time. We have showcased all the technologies that are being used at knoldus and templates that can make a good getting started experience for developers.

Purpose of this project
We've created this project, so that we can store all the Tech-Hub Templates contributed by knolders at this single place. You can find all the Tech-Hub Templates here only.

How to add Tech-Hub Template by using submodule
Step 1 - Clone the Techhub Template Repository
git clone https://github.com/knoldus/Techhub-template.git

Step 2 - Create & Checkout to new branch using
git checkout -b <branchname>

Step 3 - You have to create a directory in your newly created branch and . For example
a. java for Java Application

mkdir java && cd java
b. scala for Scala Application

mkdir scala && cd scala
c. angular for Angular Application

mkdir angular && cd angular

Step 4 - Now, create a submodule under this directory.
git submodule add <Your template repository URL>

Step 5 - Push your changes to the code.
git add.
git commit -m "your message"
git push -u origin <branchname>

Step 6 - Raise a Pull Request from your branch to main branch.

Step 7 - Now, Click on git Actions to check your build.

Languages Used
Java
Scala
Angular
Build Tools Used
Maven
Gradle
SBT
Note:- As of now we are using JDK Version 11 as default. If you want to use another version of java you will required to create a file named as :-
cat >java-version.txt

8

Now save the changes and whatever jdk version you want to use, mention in java-version.txt file as shown above like 8, Nothing else.
You can use the following jdk versions
8

11

13

15

17

You've to fullfil the criteria to merge a Pull Request
Make sure init job should be running successfully.
Make sure specific build job should be running successfully.
Rest jobs should be skipped.