# Credit Card Fraud Detection
A project built by Team-DSC01 as a part of [The Uplift Project](https://upliftproject.tech/#/)

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Mentors
* [Archisha Chandel](https://github.com/archisha-chandel)
* [Ujjwal](https://github.com/BellatrixLestrangee)
* [Mohit](https://github.com/radadiyamohit81)

## Downloading Data for the Project from Kaggle
Download the dataset from [here](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## 3 Month Plan for Data Science Skill Enhancement:

#### Plan of action for first 15 days till 15 June 2020 

•	Basic work of theme finalize <br>
•	Software Setup <br>
•	Little Brief about tools <br>
•	Task 1: Basic of Data Science Why use, when use, where use in detail. <br>

#### Plan of action for first month till 30 June 2020

•	Task 2: Learn about How Visualize Data, Libraries used for Visualization (Matplotlib, Numpy, Pandas) <br>
•	Task 3: Learn about Linear Algebra, Statistics and Probability (Basics)<br>

#### Plan of action for 1 month 15 days till 15 July 2020

•	Task 1: Learn about getting data(Web Scraping, Reading files), working with data(Cleaning, munging, manipulating data, rescaling, dimensionality reduction) <br>
•	Task 2: Learn about Basic understanding about ML and its model(Regression Analysis, Decision Tree, Clustering, etc.) <br>

#### Plan of action for second month till 30 July 2020

•	Project 1: Case study for ice cream sales data. <br>
•	Project 2: Loan Prediction <br>

#### Plan of action for second month 15 days till 15 August 2020

•	Final Project: Fraud Detection on Banking Data

#### Plan of action for third month till 30 August 2020

•	Finalization of idea<br>
•	Collect Mockup n everything<br>
•	Presentation for this project<br>

## Contribution Guidelines
Please start with solving the issues and create a pull request when done. It will
be carefully reviewed by the mentors and feedbacks will be given.

#### Getting started with GitHub

The git/GitHub open-source workflow can be rather confusing if you haven't used
it before. To make a contribution to the project, the general steps you need to
take are:

- Install [git](https://git-scm.com/downloads) on your computer
- Fork the repo on Github (ie. make your own personal copy)
- Clone your fork to your local computer
- Set remote origin (https://github.com/<_user_>/data-science.git) and upstream (https://github.com/The-Uplift-Project/data-science.git)
- Create a new branch for every issue or new work that you do.
(To avoid merge conflicts keep your work in a separate folder in the same branch if it contains more than a few files.)
- Commit changes locally on your computer
- Push your changes to your fork on Github
- Submit a pull request (PR) against the main repo from your fork.

A few commands to start with everytime you work with a GIT repository:
- `git fetch upstream master`
- `git checkout FETCH_HEAD -b <new_branch_name>`
- Make changes
- `git status`
This will show the files that have been modified, deleted or created
- `git add .` (To add all the modified files)
	OR
  `git add <file_name>` (To add a specific file)
- `git commit -m '<commit_message>'`
- `git push`
If you get an error message on executing the above command, enter the suggested `git push` command.

Now, click on the link that you see once the `push` command is executed to create a Pull Request. While creating a Pull Request do mention `[ Fixes: #<issue_number> ]` in the description. This will link the issue to the Pull Request for which the latter is created.

Once your Pull Request is merged do `git pull --rebase upstream master`. This will update your fork with local changes and the ones made from upstream. This is to ensure there are no file conflicts.

Here are some resources to learn more about parts of this workflow you are
unfamiliar with:

- [GitHub Guides](https://guides.github.com/)
    * In particular, the [git handbook](https://guides.github.com/introduction/git-handbook/) explains some of the basics of the version control system
    * There is a [page](https://guides.github.com/activities/forking/)
      explaining the forking/pull request workflow you will be using to
      contribute.
- The [Git Book](https://git-scm.com/book/en/v2) is much more detailed but a good reference
    * The [Getting Started](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) section is worth reading
    * There are also some [videos](https://git-scm.com/videos) on getting set up
- This [repo](https://github.com/aSquare14/Git-Cheat-Sheet) by a previous
  Outreachy contributor lists many other resources and tutorials.
- This [video tutorial series](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGAKWClAD_iKpNC0bGHxGhcx) on Youtube may also be helpful
- [First Contributions](https://github.com/firstcontributions/first-contributions#first-contributions) is a good place to actually practise and put your understanding to test. Feel free to make mistakes as you go along learning to make your first contribution. 
