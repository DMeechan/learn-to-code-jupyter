# learn-to-code
Learn to Code Challenges

## Installing the notebooks

Here's how to get the notebooks running on your computer:

1. Open up `Terminal` on your Mac

2. Paste in this command: `cd ~/Desktop`

3. Then paste in: `git clone https://github.com/DMeechan/learn-to-code`

4. Then type in: `cd learn-to-code`

Now you should have the `learn-to-code` project files downloaded to your desktop. Next, we have to install `Anaconda` (which installs Python and Jupyter for us)

1. Click [here](https://repo.continuum.io/archive/Anaconda3-5.1.0-MacOSX-x86_64.pkg) to start downloading Anaconda

2. When the download is complete (this may take a while; it's a big file), run it and install Anaconda

3. When the installation is done, close Terminal, and then open up a new Terminal window

4. Type in: `cd ~/Desktop/learn-to-code`

5. Type in: `jupyter notebook`

If it all works well, it should look roughly like:

```bash
[I 11:03:10.559 NotebookApp] [nb_conda_kernels] enabled, 6 kernels found
[I 11:03:11.886 NotebookApp] [nb_anacondacloud] enabled
[I 11:03:11.892 NotebookApp] [nb_conda] enabled
[I 11:03:11.951 NotebookApp] ✓ nbpresent HTML export ENABLED
[W 11:03:11.951 NotebookApp] ✗ nbpresent PDF export DISABLED: No module named 'nbbrowserpdf'
[I 11:03:11.982 NotebookApp] Serving notebooks from local directory: /Users/daniel.meechanibm.com/Code/Python/learn-to-code
[I 11:03:11.982 NotebookApp] 0 active kernels
[I 11:03:11.983 NotebookApp] The Jupyter Notebook is running at:
[I 11:03:11.983 NotebookApp] http://localhost:8888/
[I 11:03:11.983 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
```

Now it will either open up a Jupyter tab in your browser, or you'll have to do that manually by clicking [here](http://localhost:8888/tree). 

You should see a list of all 3 notebooks:

```
Learn to Code - Challenge 1.ipynb
Learn to Code - Challenge 2.ipynb
Learn to Code - Challenge 3.ipynb
```

Click on one to get started.

## Making Changes

If you make any changes, first save the change in Jupyter.

Then go back to the `learn-to-code` folder in Terminal and type:

```bash
git add .
git commit -m "Changed notepad X"
git push -u origin master
```

For the git push to work, you'll need to be a collaborator on the GitHub repo. Message me on WhatsApp with your GitHub username.