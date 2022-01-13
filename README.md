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
  1. java for Java Application 
  </br>	
         ```mkdir java```
  </br>    
   2. scala for Scala Application
  </br> 
  	    ```mkdir scala```
  </br>    
   3. angular for Angular Application
  </br>
  	    ```mkdir angular```
  	
Step 4 - Now, create a submodule under this directory.
</br>
	```git submodule add <Your repo URL, where you have uploaded you template>```
	
Step 5 - Push your changes to the code.
</br>
	``` git add.```
</br>
	```git commit -m "your message"```
</br>
	```git push -u origin <branchname>```

Step 6 - Raise a Pull Request from your branch to main branch.

Step 7 - Now, Click on git Actions to check your build. 