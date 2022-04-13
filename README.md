# neat Dino AI

- All required modules (pygame; neat-python) and their used versions are found in "requirements.txt"
- This is loosely based on a video and program by "Code Bullet" (www.youtube.com/c/CodeBullet)

# This is an AI that learns to play the Google Chrome Dinosaur Game using the 'NEAT' algorythm by Kenneth O. Stanley.

The AI learns to play a simplified receation of the Google Chrome Dinosaur Game.


Each generation consists of 15 Individuals.


There are two input-layers, one output-layer and no hidden layers. The evolution parameters are carefully chosen to be as visual as possible.


I played around with decreasing fitness on death but I came to the conclusion that not doing that leads to ideal and very visual results. Instead, every Dino receives fitness equal to its score once it collides with an object.

The "Best Score" display shows the highest score achieved over all generations.

<img src=screenshot.png>
