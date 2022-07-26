# CS-361-Microservice-for-partner

# A. How to request data
Data is requested by inputting in the checbox id values of the shark images that are being requested into sharks_to_view.txt.
Sample input would be a list of [1, 2, 3] which would correspond to great white, bull, and tiger shark images, respectively.

# B. How to receive data
Links to the requested shark images are sent into links.txt. These links are sent as a list so this way proceeding files know which link corresponds to which input. 
For example for the sample input of [1, 2, 3],  links.txt would return: ['https://upload.wikimedia.org/wikipedia/commons/5/56/White_shark.jpg', 'https://upload.wikimedia.org/wikipedia/commons/8/83/Carcharhinus_leucas%2C_Koh_Phangan.jpg', 'https://upload.wikimedia.org/wikipedia/commons/f/f6/Similan_Dive_Center_-_great_whale_shark.jpg']

# C.UML Sequence Diagram
![image](https://user-images.githubusercontent.com/86273426/180916150-720925b0-27e4-4aa1-b8a0-0ac3fa643545.png)
