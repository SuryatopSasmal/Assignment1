# Assignment_1: Basic Git Workflow
**Objective:** Learn fundamental Git commands and the basic workflow.

**Tasks:**
1.	Initialize a local Git repository
<pre>
  git init
</pre>
<img alt="image" src="https://github.com/user-attachments/assets/6ba1747d-7e03-48e3-bc61-04d6c302abdd"/>

2.	Create a simple text file with 5-10 lines of content
   
<pre>
  vim HelloWorld.txt
</pre>
![image](https://github.com/user-attachments/assets/708c5501-5fcf-4bce-b0f0-06999dc1a69a)
![image](https://github.com/user-attachments/assets/1ebc4869-4ecf-412f-91bb-8ac142c40c31)

3.	Add the file to staging and make an initial commit
<pre>
  git add. //use to add all file in stage area in the project
  git add 'HelloWorld.txt'
  git commit -m 'about myself -first commit'
</pre>
![image](https://github.com/user-attachments/assets/4ba4bc9a-c988-4c90-8ad3-8462555bea36)
![image](https://github.com/user-attachments/assets/f04c889e-f36f-4c9b-9f0d-c5e04127ba4e)

4.  Make 3 separate meaningful changes to the file, committing each change with a proper commit message following Conventional Commits format
</br>
First Change:</br>
-In first commit i add one week training timeline.
<img alt="image" src="https://github.com/user-attachments/assets/f8112276-91df-44aa-9f4a-df5a01cc8cb8">
  Second Change:
-In Second commit i add my assignment.
<img alt="image" src="https://github.com/user-attachments/assets/19cd7747-aad1-42bc-a40d-65a4423773b6">
<img alt="image" src="https://github.com/user-attachments/assets/e39f9c3e-83f5-4c0c-bec5-22e2ecd40e37">
  Third Change:
-In Third commit i add detail of assignment.
<img alt="image" src="https://github.com/user-attachments/assets/fb4f7cc5-7378-44fe-b419-5e71ff6d6dcc">
6. 	Use git log to view the history of changes
<pre>
  git log
</pre>
<img alt="image" src="https://github.com/user-attachments/assets/5474580d-9b57-4618-bb11-72040e621c7e">
6.	Use git diff to examine differences between commits
<pre>
  git diff <hash_id1></hash_id2>(or)
  git diff HEAD~1 // difference recent commit with just previous commit
</pre>
<img alt="image" src="https://github.com/user-attachments/assets/a080d242-5e2e-4a98-a850-591b8c22d85f">
(OR)
<img alt="image" src="https://github.com/user-attachments/assets/c909058d-0d53-4c1d-a8bf-9017a39ed8bd">











