# Kannada Academy - Howtos Repo
How to guides for the common tasks that you need to perform to set up a school.

How to contribute to the collection of guides
----------------------------------------------
1. Create a feature branch using the following git command:
   > git checkout <your_branch_name>
2. Edit existing markdown files or add new files:
   > git add <modified_or_new_files_list>
   > git commit -m "<commit_message>"
3. Commit the changes and push it to your feature branch
   > git push origin <your_branch_name>
4. Create a Pull request on the github web interface to merge your feature branch
into the master branch.
5. Request a review for you pull request
6. Merge your pull request if all comments from the reviewer are addressed.

Testing your changes locally
----------------------------
1. Run `pipenv shell` to initialize the python viritual environment with the required packages.
2. Call sphinx to build HTMLs from the markdown files in the repo:
   sphinx-build -b html <source_dir_containing_md_files> <build_dir>
