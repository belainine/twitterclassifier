# twitterclassifier
Dans les services des réseaux sociaux comme Facebook ou Twitter, les utilisateurs peuvent se laisser submerger par les données brutes.  Une solution proposée à ce problème est la classification des messages Twitter (tweets). Les textes courts, comme les tweets, ne fournissent pas assez de mots.  
Alors que,  les méthodes de classification qui utilisent des approches traditionnelles telles que les sacs de mots ont des limites.  Car, les textes des réseaux sociaux sont généralement courts et contient des argots riches en abréviation qui sont  suggérés par des utilisateurs, tels les métadonnées spécifiques aux tweets. Outre que ces textes sont riche en entités nommées pour designer des noms spécifiques comme les noms  d'organisations, les personnalités ou les lieux.
Pour résoudre ce problème, nous avons proposé une approche intuitive pour catégoriser les classes.  En se basant sur des collections des tweets construites à base des requêtes Twitter. Ces requêtes enrichies par des mots d'un domaine spécifique afin de collecter des textes qui représentent particulièrement ce domaine, tels que la politique, l'économique, le sport et le domaine médical. 
Nous avons en plus proposer un prétraitement spécifique aux textes des médias sociaux dans le but d'extraire le maximum d'information.  Aussi, élargir les sacs de mots, toute en se basant  sur la désambigüisation des acronymes et les entités nommes à l'aide de WordNet et de la segmentation des hashtags. 
Nous avons présenté aussi une approche intuitive, en utilisant les théories des graphes,  pour regrouper les mots extraits de WordNet et les tweets. toute en se basant  sur les composantes connexes. Chaque composante relier les mots qui partagent un contexte commun selon leurs existence dans WordNet qui vont être représenté par un mot. Ce mot unique surnommée "Représentant" va symbolisé une composante dans le sacs de mots. 
Nous avons classé les tweets entrants par ordre de catégories génériques, telle la politique, l'économique, le sport et le domaine médical. En effet, nous croyons que ces catégories sont diverses et couvrent la plupart des sujets que les gens s'échangent habituellement.
Postérieurement, nous allons permettre aux utilisateurs des médias sociaux en l'occurrence Twitter, de créer de nouvelles formes de catégories en rapport avec leurs intérêts. Sachant aussi que  la précision se dégrade avec l'augmentation du nombre de classes. Alors, nous avons proposé également aux utilisateurs d'ajouter de nouveaux types de filtrage par catégories grammaticales de mots et par les entités nommées. 
Les résultats expérimentaux montrent que, le filtrage par catégorie grammaticale avec l'utilisation des entités nommées utilisé augmente la précision de la classification jusqu'à  83.1%.
Au même temps, la segmentation des hashtags participes à cette ambiance d'augmentation. 



##Installation
Télécharger [NetBeans 8.0.1 et SDK 1.8](https://netbeans.org/downloads/start.html?platform=windows&lang=en&option=all).  
Voici les [instructions](https://netbeans.org/community/releases/80/install.html) d'installation à suivre.  
Aller à Team->Git->Clone.                                                                
![netb0.png](http://www.gafitescu.ro/wp-content/uploads/2012/02/netbeans-team-git-clone.png) (http://www.eschrade.com/wp-content/uploads/2011/11/netbeans-git-clone.gif)  
Taper le "Repository URL".                                                               
![netb1.png] (http://www.eschrade.com/wp-content/uploads/2011/11/netbeans-git-clone.gif)  
Séléctinner la branche "master".                                                        
![netb1.png](https://netbeans.org/images_www/articles/74/ide/git/github-branches.png)     
Clicker sur le bouton "finish", le message suivant apparaitera indiquant que le projet a bien été cloné.     
                            
Ouvrir le projet qui se trouve dans le panel gauche "Projects".        
  




