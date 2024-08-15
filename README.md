# MSc_AI_Capstone_Project
Capstone Project for Masters of Science in Artificial Intelligence at the University of Galway

Vision-driven soccer analysis has become a keen interest in recent years as the technology to broadcast and record these games has improved. Detecting players from game footage has become very essential as these allow for better player tracking, which leads to enhanced monitoring of player's vitals, better game strategies, and improved viewer experience. There are various methods for identifying players like facial recognition or via body appearances, among which identifying players based on their jersey numbers is a highly effective and reliable option. To address these issues, the project here aims to build a system for recognising jersey numbers from short video tracklets of players. To build such a system, I propose to use a Video Vision Transformer (ViViT) model, which is a transformer-only spatio-temporal network, on the widely available SoccerNet dataset. The final experimental results demonstrate that there is potential in using a pure-transformer-based model for jersey number recognition, although there is a scope for improvement with further refinement.

SoccerNet-v3 dataset was used for this project. The dataset was sourced from SoccerNet, a comprehensive and large-scale dataset designed for soccer video understanding. The dataset consists of a few hundred frames long sequences of players' tracking videos on the soccer field.
A sample of the dataset is given inside the 'Dataset' directory. The complete dataset can be accessed from https://www.soccer-net.org/data#h.b1lf96jmxlcc

The code for this project is in two parts:

<ul>
  <li>Dataset_Preparation.ipynb contains the code for loading and saving the data into a single Numpy array for further processing and training</li>
  <li>MSc_Final_Capstone_Project.ipynb contains the main code for training the Video Vision Transformer (ViViT) for the task of jersey number recognition</li>
</ul>
