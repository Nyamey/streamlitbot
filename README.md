# streamlitbot

Membre 1 : EKIYABE NYAMEY KAREN HILARY
Membre 2 : KOUAMI KOSSI ALEXANDRE
Membre 3 : DOUAKOUTCHE CHARAF

L'application est un clone de ChatGPT qui permet aux utilisateurs d'interagir avec différents modèles GPT d'OpenAI. Elle offre les fonctionnalités suivantes :
Sélection du modèle GPT à utiliser parmi plusieurs options
Ajustement du nombre maximum de tokens générés
Interface de chat pour poser des questions et recevoir des réponses
Affichage de l'historique des conversations

suivez ces étapes :
1 - Clonez le dépôt Git (si vous ne l'avez pas déjà fait) :
git clone [URL_DU_DEPOT]

2 - Naviguez vers le répertoire du projet :
cd [NOM_DU_REPERTOIRE]

3 - Vérifier que Python est correctement installé sur votre ordinateur :
python --version
ou 
python3 --version

4 - Vérifier que pip est installé correctement en utilisant les commandes suivates:
pip --version
ou
pip3 --version

5 - Ensuite exécutez la commande suivante pour créer un environnement virtuel:
python -m venv stenv
ou 
python3 -m venv stenv

6 - Pour utiliser un environnement python que nous venons de créer et qui s'appelle stenv, entrez ce qui suit dans la ligne de commande :
source stenv/bin/activate 
ou 
source stenv/Scripts/activate 

7 - Créez un fichier .gitignore dans votre projet et ajoutez les lignes suivantes et sauvegardez le fichier.
# Python venv 
stenv
.gitignore

8 - Assurez-vous d'avoir openai et Streamlit installés :
pip install streamlit openai

9 - Verifiez que Streamlit est correctement installé en exécutant la commande suivante:
streamlit hello

10 - Exécutez l'application Streamlit :
streamlit run chatbotgpt.py