# Objectif Du Projet Se Projet 
Se projet est Realiser dans le but de permettre au service d'une   structure hospitalière en particulier de signaler les cas d'urgence rencontrer dans la structure nous pouvons citer entre autre les cas d'urgence tel que les accidents ,les accouchements et bien d'autre .au niveau du personnel de l'hopital il peuvent également signaler le manque de personnels dans un service ou le manque de materiel en demandant de l'aide directement a un service de la structure .
# Fonctionnalité principale 
l'application pourra ainsi donc nous permettre de :
- signaler un probème 
-publier une informations
-publier le programmes mensuel ou annuel dans un service precis
-Ajouter et gerer les types d'utilisateur
-Ajouter un service de la structure
-gerer la connection et l'authentification pour la sécurité de l'applications
-Crypter les informations censsibles telsque les mots de passe
-Elle pourra permettre a l'administrateur qui est une personne de la structure de générer des rapports tels que la liste de tout les personnels ,service et problèmes signaler
 
 # Technologie Utilisée 
 le Langage utiliser est Le C# en utilisant une architecture 3-tiers  ce Qui permet de diviser le projet en 3parties :
 -la couche d'access aux donnees permettant d'implementer les differentes methodes (Ajout ,Suppression etModification) en  recuperant les informations dans la base de donnée a l'aide des requetes Sql.
 -la couche Metier : permettant ainsi de declarer en public  tout les attributs des differentes classe pour acceder dans tout le programme notamment (couche Metier et Access Au donnees)
 -Couche Presentation Cette couche est contituer des different formulaire creer a partir de windows forms pour permettre a l'utilisateur de pourvoir manipuler les informations de la base de donnees a l'aide des controles.
 # type de base de donnees 
 Se projet de Gestion des urgences a éte realiser en utilisant une base de donnée  Sql local  ce qui a permit la création des tables Prisonniers,prison,personnel,cellule,activites,visite et delit.