---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Kaggle-AI Model Prediction"
date: 2023/11
published: true
labels:
  - Competition
  - AI Algorithm
  - GitHub
summary: "A competition that explores optimization objectives and methods for AI algorithms. we chose to use a Graph Convolutional Network (GCN) model to address this challenge. Initially, we perform embedding encoding on the operation codes (node_opcode) and node configuration features (node_config_feat) to capture the latent representations of these discrete attributes. These encodings, combined with other node features (node_feat), serve as inputs to the nodes in the GCN model. In terms of model architecture, we use GCN convolution layers (GCNConv) to process the graph structure, facilitating the flow and integration of information between nodes. For the training objective of the model, we utilize the ListMLE loss function, a common choice in list-wise learning, suitable for addressing sorting or priority-related problems. Finally, we opt to train the model using the Adam optimizer.

3.The performance of a single model is often limited by its structure and parameters. To further enhance the accuracy of predictions, we decided to employ model fusion on the aforementioned model. Specifically, we combined the prediction results of multiple models through weighted fusion, then sorted and output these results. This strategy effectively reduces the model's bias and enhances its robustness.
"
---

<img class="img-fluid" src="../img/cotton/cotton-header.png">

Cotton is a horror-style text-based adventure game I developed using the functions and macros built from The Wizard's Game in [Conrad Barski's Land of Lisp](http://landoflisp.com/). Slightly more interesting and convoluted! (It is not that scary.)

To give you a flavor of the game, here is an excerpt from one run:

<hr>

<pre>
You open your eyes, and you are greeted by an unfamiliar ceiling.
Startled, you get to your feet and quickly scan your surroundings. It's
dark except for the stream of light coming from a crack on the only boarded
window in the room. You try to peek through the crack, but you cannot see
anything. You wonder where you are and who could have possibly brought you here.

<--------------------help------------------------>
Enter quit or one of the following commands -
Weld light look walk pickup inventory help h ?
<------------------------------------------------>

look
The room is a picture of decay with only a faded number identifying it as room-4. The bed you were
 lying on is stained with what looks like dried blood. Could it be your blood? No - it is not. The
 only way out of the room aside from the door to the corridor is a window that is boarded shut. It
 looks like it has been like that for decades. There is a door going west from here. You see a candle
 on the floor. You see a match on the floor.

pickup candle
- you are now carrying the candle -

pickup match
- you are now carrying the match -

light match candle

The candle is now lit. It illuminates everything in the room.

walk west
The corridor is lit with the candle. It is so long that you cannot see to the end. You notice that
 there are words written on the wall. There is a door going east from here. There is a way going north
 from here. There is a door going south from here.
</pre>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
