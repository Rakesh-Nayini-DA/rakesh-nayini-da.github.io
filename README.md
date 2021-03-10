### Reference 1: [freecodecamp blog](https://www.freecodecamp.org/news/hosting-on-github-pages-with-git-submodules-36815856c3f1/)
### Reference 2: [stackoverflow](https://stackoverflow.com/questions/8191299/update-a-submodule-to-the-latest-commit)

## GitHub GUI:

	1. Create a new Home Repo (rakesh-nayini-da.github.io)
	2. Setup Home page with Jekyll files
	3. Create a sub repo 1 (NetSuite-API)
	4. Create a sub repo 2 (NetSuite-Wizard)

## GitHub CLI:

	1. Clone a Home Repo
	2. Open CLI with Home Repo Path
	3. cmd: git init
	4. cmd: git submodule add https://github.com/Rakesh-Nayini-DA/NetSuite-API.git
	5. cmd: git submodule add https://github.com/Rakesh-Nayini-DA/NetSuite-Wizard.git
	6. cmd: git commit -m "added submodules for API and Wizard" 
	7. cmd: git remote add origin https://github.com/Rakesh-Nayini-DA/rakesh-nayini-da.github.io.git #check required or not
	8. cmd: git push origin main

	Now, submodules updated to MAIN Branch HOME Repo (like NetSuite-API @ 797c7f6...)



## Setup API docs on sub repo 1 (NetSuite-API) using GitHub for Desktop:

	1. Clone repo to the local and commit required changes directly to MAIN Branch
	2. the Only folder of API needed files (not required entire Jekyll files)


## Setup API docs on sub repo 2 (NetSuite-Wizard) using GitHub for Desktop:

	1. Clone repo to the local and commit required changes directly to MAIN Branch
	2. the Only folder of API needed files (not needed entire Jekyll files)




## Getting Changes of submodules to Home repo using GitHub CLI):

#### Updating Recent Changes for API:
	
	1. Navigate to submodule path (eg: \rakesh-nayini-da.github.io\NetSuite-API)
	2. cmd: git pull origin main
	3. cmd: cd .. (return to Home Repo)
	4. cmd: git status
	5. cmd: git add NetSuite-API
	6. cmd: git commit -m "Getting updtes from API"
	7. cmd: git push origin main

#### Updating Recent Changes for Wizard:
	
	1. Navigate to submodule path (eg: \rakesh-nayini-da.github.io\NetSuite-Wizard)
	2. cmd: git pull origin main
	3. cmd: cd .. (return to Home Repo)
	4. cmd: git status
	5. cmd: git add NetSuite-Wizard
	6. cmd: git commit -m "Getting updtes from Wizard"
	7. cmd: git push origin main
