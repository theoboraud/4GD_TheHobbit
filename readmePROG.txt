----------------------

Groupe :
BAUDRY Oscar, BLENGINO Thomas, BORAUD Théophile, MC VEIGH Alexander

Classe :
4GD (Game Design, 4ème année)

Date de rendu :
12 septembre 2021

Nom du jeu :
"The Hobbit"

Oeuvre originale :
"The Hobbit" (J.R.R. Tolkien, 1937)

----------------------

Mécaniques et éléments de gameplay principaux :
Le joueur voit apparaitre devant lui un texte au sein duquel il peut récupérer et conserver des mots-clés, pour ensuite pouvoir les utiliser
dans des champs d'entrée pour faire avancer le récit. L'histoire étant séparée en plusieurs rencontres, qui correspondent chacune à des lieux importants
de la région d'Eriador où se déroule l'action, le joueur peut à la fin d'une d'elles se déplacer vers un nouveau lieu et donc déclencher une nouvelle
rencontre, en fonction des différentes issues narratives.

Intentions principales du prototype :
Le joueur doit pouvoir lire l'intégralité de l'étape de rencontre dans laquelle il se situe. Le texte se sépare en plusieurs pages, constituées de mots
classiques (pas interactifs), des mots-clés mis en valeur dans le texte via un effet RichText (interactifs) et des champs d'entrée où les mots-clés
viendront s'insérer pour passer à l'étape suivante. Actuellement, aucun choix par défaut n'a été développé, aussi seulement certaines options peuvent être
utilisées (sans quoi le joueur reste bloqué tant qu'il n'utilise pas un mot adapté).
Une fois la rencontre terminée, le joueur est invité à se déplacer sur la carte en 3D. Cette dernière autorise à se déplacer n'importe où dans l'unique but
de montrer l'intégralité du niveau développé.

Intentions pour la soutenance :
Le texte doit pouvoir avancer peu importe le mot utilisé à chaque étape. Un ou plusieurs choix par défaut doivent donc être offerts au joueur afin de ne pas bloquer le récit si ce dernier n'utilise pas un mot précis. Il doit également pouvoir obtenir un choix par défaut en cas de réponse absurde.
Le jeu doit aussi inclure la barre d'engouement des enfants à qui Bilbo raconte son histoire.
Enfin, un certain nombre de polish devra être effectués, tant au niveau des transitions, des feedbacks et du son que de l'affichage.

Bugs à fix :
- Les alinéas ne s'affichant une fois le premier paragraphe passé
- Les mots clés laissant parfois un espace après leur widget
