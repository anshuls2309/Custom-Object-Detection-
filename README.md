# Custom-Object-Detection Python -

In this project, i used python's new module called detecto for object detection using my own custom images/dataset which detects tennis balls in images.

You can put your own object images and labels and train the model to detect those objects in the image

The detecto library can be found here : https://pypi.org/project/detecto/

For training a model, you will need a GPU so that the process can me made faster, i had used Google Collab to run my python scripts and used the GPU option provided to faster the process.

I used a couple of python scripts to do this. 

1) First i downloaded some images from the internet of tennis ball with 10 only exclusive tennis balls and other 10 images with tennis balls along with other objects(eg - bat, racquet)
2) I then resized all the images using python script so that i can label the images propely.
3) I used LAbelImg for labelling the images. ( https://github.com/tzutalin/labelImg)
4) I made a folder Detecto Tutorial in my google drive and further 2 folders in that folder named labels and images
  ( images were saved in images folder and labels in labels folder)
5) I then installed detecto using (!pip install detecto) in google collab to install the library 
6) I then mounted the google drive using a python script
7) Then i trained the model and finally run the python script to detect tennis balls

