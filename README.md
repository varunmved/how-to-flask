A basic mockup of what a flask app should look like, this is basically a hodgepog of different sources on how to structure flask operations

1. Make sure have python, you can test this by typing ~~~python~~~ in your command line, if bash doesn't recognize it as a valid command, you'll want to download it

  1.1 In the event you do not have python, I'd recommend downloading and installing it through [homebrew](http://brew.sh/), then typing ~~~brew install python~~~ if you're on a Mac, or just use ~~~sudo apt-get install python~~~ if you're on a nix box.

2. Clone this repository, this is as easy as typing ~~~git clone https://github.com/varunmved/how-to-flask.git~~~. Then simply type ~~~git init~~~ and you have a git repo setup, wohoo!!!

3. Once you have this cloned, you'll want to set up ~~~pip~~. Pip is a way to install and manage python packages. You'll use external packages so you have to code less and to be more productive.

  3.1 To install pip if you don't have it on your machine, just type ~~~sudo easy_install pip~~~.

4. Now that you have pip, let's install ~~~virtualenv~~~, a tool to create virtual enviroments to manage a project. Type ~~~pip install virutalenv~~~.

5. Now that ~~~virtualenv~~~ is installed, we'll want to create a virtualenv instance. We do this by typing ~~~virtualenv venv~~~ which will create a virtual enviorment inside of the venv folder.
   We'll then want to activate that instance by typing ~~~source venv/bin/activate~~~. Now you'll notice a ~~~(venv)~~~ before your shell information inside of bash. 

6. Now we need to install the required packages, to do this run ~~~pip install -r requirements.xt~~~. This will install all the pacakges defined in ~~~requirements.txt~~~.

7. As you scale your projects with more external code, you can just type ~~~pip install (package name)~~~ and it'll be installed. To overwrite the existing requirements.txt just type ~~~pip freeze > requirements.txt~~~.

8. You'll notice a ~~~.gitignore~~~ file at the root of the directory. The purpose of this file is to ignore files you don't want to be commited on git, as well as your ~~~venv/~~~ folder which can get really large!

9. I'll have more instructions on what each file does in detail below in the README, but for now, happy hacking! 
