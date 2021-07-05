A/ Ce document vous permet d'installer votre environnement virtuel et lancer le notebook avec Jupyter

Au sein du terminal windows Ms-dos, lancer les commandes suivantes:

virtualenv P3env

.\P3env\Scripts\activate

pip install ipykernel

python -m ipykernel install --user --name=P3env

pip install –r requirements.txt


requierements.txt contient: 
	numpy==1.20.2
	pandas==1.2.4
	matplotlib==3.4.1
	seaborn==0.11.1
	folium==0.12.1
	scikit-learn==0.24.2
	voila==0.2.9
	streamlit==0.81.0
	jupyter_contrib_nbextensions
	plotly==4.14.3

Vous pourrez ensuite lancer:  jupyter notebook P3_01_notebook.ipynb


B/ Installation du notebook interactif

création d'un nouveau repository sur GitHub en associant une license (exemple: License MIT)
copier les livrables dans un nouveau repository GitHub (principalement P3_02_dashboard.ipynb, functions.py, requirements.txt)

apres avoir fait un commit, lier les informations sur mybinder.org

lancer le deployement sur binder

puis cliquer sur voila du notebook en ligne

partager le lien avec vos collaborateurs


--------------------
Les livrables sont: 
Readme.txt
requirements.txt
P3_01_notebook.ipynb
P3_02_dashboard.ipynb
P3_03_Presentation.pptx
functions.py
data/PGclean_data.csv
data/images/Sante-publique-France-logo.jpg

