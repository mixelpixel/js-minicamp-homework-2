# Homework #2

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.

	* for loop
		- an initialized state is modified until a condition is met and the loop terminated:
		```
		for (initialization prior to loop; test condition controls loop; incremental step after loop body action)  
			action;
		```
	* && || !
		- logical operators
		- **&&** has the same logical operation as **and** such that
			- Only True && True === True
		- **||** has the same logical operation as **or** (inclusive) such that
			- Only False || False === False
		- **!** has the same logical operation as **not** such that
			- !True === False && !False === True
	* Array
		- mutable data structure, ordered list of items, position starting at 0 to array (length -1)
		- [ [0], [1], [2], ... [array length - 1] ]
		- or, if n = array length] where "length" = total number of items in array (or "list"), then:
		- [ [0], ... [n - 1 ]
		- array positions may be any type: ints, strings, floats, etc. including nesting arrays.
	* git
		- version control management software
	* GitHub
		- online hosting site for git repositories
		- **DONE**

2. Install git.  https://git-scm.com/downloads
	- Already installed
		- **DONE**

3. Fork and clone this repo.  When you need to commit use the following commands.

	* git status
	* git add --all
	* git status
	* git commit -m "your commit message"
	* git push origin master

		- NOTE: instead of forking and cloning, I forked and submoduled.  
		- Per: https://git-scm.com/book/en/v2/Git-Tools-Submodules  
		- **DONE**

4. Make the tests pass!
	- `npm install`
		- **Struggling with prime numbers...**


#### Congratulations on finishing Homework #2!

<details><summary> Click here for more about Lambda School</summary><p>

Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com

</p></details>
