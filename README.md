# data_science_praktik
Assignment for Jyllands Postens Data Science praktik

Fork this repo and create data visualization from the pokemon.zip dataset contained in this repository. The assignment is meant to be open and it is the responsibility of student to figure out the best way of visualizating the data to create the most meaning of it (Grouping of pokemon type or something entirely different)

The solution should be programmed in any of the following languages:
- Java
- Scala
- Python

The visualization could be directly in a Jupyter Notebook or exported to third party graph delivered as either jpeg, png or pdf. 

The interview will be about the solution for this assignment and general talk about the data science team at Jyllands Posten. 

Please handin a url to the forked repo containing programming solution, all visualizations and a small file contained a small writeup of the ideas used on the solution.

## Ref: Kaggle pokemon dataset

This data set includes 721 Pokemon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed. It has been of great use when teaching statistics to kids. With certain types you can also give a geeky introduction to machine learning.

This are the raw attributes that are used for calculating how much damage an attack will do in the games. This dataset is about the pokemon games (NOT pokemon cards or Pokemon Go).

The data as described by Myles O'Neill is:

#: ID for each pokemon
Name: Name of each pokemon
Type 1: Each pokemon has a type, this determines weakness/resistance to attacks
Type 2: Some pokemon are dual type and have 2
Total: sum of all stats that come after this, a general guide to how strong a pokemon is
HP: hit points, or health, defines how much damage a pokemon can withstand before fainting
Attack: the base modifier for normal attacks (eg. Scratch, Punch)
Defense: the base damage resistance against normal attacks
SP Atk: special attack, the base modifier for special attacks (e.g. fire blast, bubble beam)
SP Def: the base damage resistance against special attacks
Speed: determines which pokemon attacks first each round
The data for this table has been acquired from several different sites, including:

pokemon.com
pokemondb
bulbapeida
One question has been answered with this database: The type of a pokemon cannot be inferred only by it's Attack and Deffence. It would be worthy to find which two variables can define the type of a pokemon, if any. Two variables can be plotted in a 2D space, and used as an example for machine learning. This could mean the creation of a visual example any geeky Machine Learning class would love.
