# Super Hexagon 

 - Based on reinforcement learning 
 - Beats all six levels easily end to end (i. e. from pixel input to action output)
   - A level counts as beaten if one survives at least 60 seconds
 



<div align="center">
<img src="images/Screenshot 2024-05-04 173901.png" width="50%">

### About The Game
 - Super Hexagon is a fast-paced twitch game in which the player controls a triangle on a hexagonal grid in the center while walls come from the edges of the screen. The controls are simple: the player must pivot their triangle left or right into an opening in order to survive.
<div align="center">
<img src="images/Screenshot 2024-05-04 171117.png" width="50%">



<div align="center">
<img src="images/a_compressed.gif" width="47%">
&nbsp;
<img src="images/b_compressed2.gif" width="47%">
</div>



### Evaluation
In order to run the AI, first download the pretrained network [super_hexagon_net](https://github.com/polarbart/SuperHexagonAI/releases/tag/v1.0)
and place it in the main folder (i. e. the folder where `eval.py` is located).

Then, start the game in windowed mode and execute the `eval.py` script, both with admin privileges.

The level being played as well as other parameters can be adjusted within the script.

