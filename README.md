create a folder 
create a git hub repo
clone in that folder using #https link
move one folder inside cd End-mlproject1
create template.py
create setup.py
main.py edit(from src.mlproj.config import configuration)
install pip ---requirements.txt

create logging folder in src./__init__.py(open folder)
check the logger in main.py
In research folder(expriment.ipynb - loading the csv file)
In SRC folder (utlis/common.py-update)
SRC folder (config/configuration.py-update)
SRC folder (constant/__init__.py-update) #[where the path to all yaml files]
Research folder (Data-ingestion update)
    



# How to work
1.conda create -n mlproj python=3.8 -y 
2.conda activate mlproj
3.pip install -r requirements.txt

# WORK FLOWS:
1. update config.yaml
2. update schema.yaml
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the app.py