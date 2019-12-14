ExplainGAN.ipynb is the old notebook, before I started to split up code into single files

ExplainGANcompact.ipynb is the recent version of the main notebook. It clones this github repository and accesses and runs the single code modules. This makes the notebook smaller and makes orientation easier. 

The folder "tests" contains several code snippets from the original old notebook that I wanted to take out of the clean notebook, but that I didn't want to delete for good. They usually use variables from the notebook, so they cannot be called with the %run command in the notebook. Instead, copy them back into a regular cell in the notebook if you want to use them again.
