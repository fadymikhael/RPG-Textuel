
# Projet RPG Textuel 

Bienvenue dans **RPG Textuel**, un jeu de rôle immersif et interactif joué directement dans la console. Créez votre personnage, explorez un donjon rempli de monstres et d'obstacles, et utilisez vos capacités spéciales pour survivre et trouver la sortie.


## Prérequis

Pour exécuter ce projet, vous aurez besoin de :
- Java Development Kit (JDK) 8 ou version supérieure ☕️
- Un IDE Java (IntelliJ, Eclipse, etc.) ou un terminal avec `javac` et `java` configurés ⚙️

## Installation 

1. Clonez le dépôt du projet sur votre machine locale :
   ```bash
   git clone https://github.com/votre-utilisateur/rpg-textuel.git
   ```

2. Accédez au répertoire du projet :
   ```bash
   cd rpg-textuel
   ```

3. Compilez les fichiers Java :
   ```bash
   javac -d bin src/cours3/*.java
   ```

4. Exécutez le programme :
   ```bash
   java -cp bin cours3.Main
   ```

## Fonctionnalités 

- **Création de personnage** ✨ : Choisissez parmi trois classes – Sorcier, Elfe ou Guerrier – chacune avec des capacités spéciales uniques.
- **Exploration du donjon** 🗟️ : Une carte générée aléatoirement remplie de monstres, d'obstacles et d'une sortie mystérieuse.
- **Combat et stratégie** ⚔️ : Rencontrez des monstres, subissez des dégâts et utilisez vos pouvoirs spéciaux pour survivre.
- **Gestion des ressources** ⛏ : Gagnez de l'or et de l'XP en battant des monstres et en surmontant des obstacles.

## Gameplay

1. **Début du jeu** ▶️ :
   - Le joueur commence par entrer le nom de son personnage et choisir sa classe.
   - Le joueur peut acheter des armes au magasin et voir ses statistiques de base.

2. **Exploration du donjon** ➕ :
   - Se déplace dans le donjon en choisissant des directions (“haus”, “bas”, “gauche”, “droite”).
   - Rencontre aléatoire avec des monstres (inflige des dégâts et donne de l'XP) et des obstacles.

3. **Sorts spéciaux** ✨ :
   - Chaque classe a des sorts spéciaux qui coûtent du mana.
   - Par exemple, le Sorcier peut lancer une boule de feu, l'Elfe se régénère, et le Guerrier entre en rage.

4. **Objectif** 🚪 :
   - Trouver la sortie tout en gérant la santé, le mana et les ressources.

## Structure du projet 

Voici un résumé des classes principales :

- **`Main`**     🖥️ : Point d'entrée du jeu, gère l'interaction utilisateur et la boucle de jeu.
- **`Player`**   👤 : Représente le joueur avec ses attributs, inventaire et capacités spéciales.
- **`Weapon`**   🗡️ : Classe abstraite de base pour toutes les armes.
- **`Dungeon`**  🏰 : Gère la carte du donjon et les interactions de déplacement.
- **`Monster`**  👹 : Représente un monstre avec sa santé et ses actions.
- **`Obstacle`** 🧱 : Représente un obstacle destructible dans le donjon.
