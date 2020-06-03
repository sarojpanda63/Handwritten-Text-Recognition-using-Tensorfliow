# Handwritten-Text-Recognition-using-Tensorflow-in-Jupyter-Notebook
This Repository shows the workdone of Harald Scheidl in Jupyter Notebook. 
Some documents are directly imported from githubharald/SimpleHTR a github account of Herald Scheidl
(https://github.com/githubharald/SimpleHTR)
## Data Set:
Get IAM dataset
1. Register at: http://www.fki.inf.unibe.ch/databases/iam-handwriting-database
2. Download words.tgz 
3. Download words.txt
4. Put words.txt into this dir
5. Create subdir words
6. Put content (directories a01, a02, ...) of words.tgz into subdir words

Check if dir structure looks like this:

            data
            --test.png
            --words.txt
            --words
            ----a01
            ------a01-000u
            --------a01-000u-00-00.png
            --------...
            ------...
            ----a02
            ----...
## File Management Structure:
![htr](./File Hierarchy.PNG)
