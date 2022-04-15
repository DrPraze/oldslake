export conda environment ..
conda env export | grep -v "^prefix: " > environment.yml

**Best approach**

Pip freeze > requirements.txt // writes the packages along with version

Pip install -r requirements.txt // installs packages recursively
