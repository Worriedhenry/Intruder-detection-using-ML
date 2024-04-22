
# Intruder detection using Machine Learning
### By Ankit Sharma  

The world is a dynamic place and is full of opportunities, surprises and threats.
Suspicious activity is any observed behavior that could indicate a person may be involved in
a crime or about to commit a crime. Each of us might think of different things when it comes
to what appears suspicious. Specially when it comes to activities of intruders at our places.
The domain of the project is computer vision with a fine intersection with security
.Computer vision provides eyes to computers , which focuses on enabling machines to
interpret and understand visual information from the real world . It aims to replicate the human
visual system by teaching computers to extract meaningful insights and make decisions based
on visual data. In the realm of security, computer vision plays a vital role in enhancing
surveillance and monitoring capabilities. By leveraging advanced algorithms and machine
learning techniques, security systems can automatically analyze visual data to detect and
respond to potential threats in real-time.

While these traditional methods are effective to some extent, they often rely heavily on human
intervention and may have limitations in scalability, coverage, and responsiveness. Integrating
machine learning and AI technologies into security systems can complement these traditional
methods by providing advanced analytics, automation, and real-time threat detection
capabilities.
Our solution will use something known as Convolution Neural Network often called as CNN.
The provide our system capabilities to understand and extract information from visual data and
process it. Our model will majorly will work on three distinctions
* Mask Detection: This component of your project involves training a CNN to recognize whether individuals in the captured images are wearing masks or not. This makes sure the person entering the premises are properly identified
* Weapon Detection: Authorization Detection: This component involves determining whether individuals have the authorization to access the premises. The CNN is trained to recognize certain attributes or features that signify authorized personnel.
* Authorization Detection: This component involves determining whether individuals have the authorization to access the premises. The CNN is trained to recognize certain faces of authorized person.

## Dependecies
The project is mostly uses basic machine learning library like pytorch , matplotlib and numpy.
In addition to these , i am also using following Dependecies
-  OpenCV --> Open computer vision library provides us capablity to work with real time vision data and multiple haar cascade such as frontal face which we have also used in our project
- GunCascade xml --> I am using pretrained gun detection haar cascade which is publicly available on GeekForGeeks article .Link of the same is https://www.geeksforgeeks.org/gun-detection-using-python-opencv/

- matplotlib --> I have used matplotlib to visualize our output in a user friendly manner.


## Setup and usage guide
#Setup in your local system
- Make sure your local system have python installed.
- Run the following commands to install necessary dependecies
` pip install pytorch matplotlib numpy opencv-python `

- After setting up python , open the zip folder / code files attached and open them in any editor such as vs code along with zupiter extension.

- Start with executing top cells for importing dependecies and initialising model classes

- If you want to train the model on your own data you can achieve it by creating dictionary of your images path/urls as key and label as value.The current image paths/urls may not work as some of them are private images ans not avilable publicly.
- To convert the image to tensor from paths use transform_image function and for urls use fetch_and_transform_images .
- Else if you want to use pretrained model for mask detection you can just load the model by running respective cells.
- To train and test model the specific model run the code cells with similar headings.
- To visualise the output or small sample of it , use the visulization code for the same. Make sure all the varialbles have correct names.
- To use the live camera feed , a cells with the same heading is provided , make sure you have provided all the required access.Press "q" on keyboard to exit the python window 
- To use pre-Recorded video , use the cell with such heading . Make sure you provide correct path to input data.


