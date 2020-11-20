# Face-Recognition
**Model summary and Novelty**<br />
Single identity face recognition works even for obscured faces i.e for a face covered with a face mask. The model makes use of Harr's Cascade Classifier for face detection which is one of the strongest classifiers for face detection since it maks use of Ada Boost. For model training, the model takes a live sample of 100 images which is stored in the local repository as the training images. The training images and their labels get updated and is saved as "Model trained successfully". When the web cam is enabled, face detection takes place after which the model makes predictions on the captured face from frame. The model calculates the user confidence which if greater than a certain threshold value recognizes the registered candidate and in case an unregistered candidate it displayes "Screen Locked". When no face is detected from screen it displays "User Not Found".
  The model novels in the fact that it is able to provide accurate recognition results inspite of the face being half-covered.<br />
  
  Usages: OpenCV for computer vision. <br />
  
**Model Constraints**<br />
The only constraint for this recognition model is that it stores its database for recognition for one person only and thus cannot perform  multiple identity recognition.<br />

**Application**<br />
The model can find its application in the face recognition systems in our electronic devices which will be able to recognize the registered user without them having to remove their face mask which is very helpful in these pandemic times.









