# Pancreatic Cancer Grading (Deep Learning) Project


This is a project to classify four classes of pancreatic cancer grade from a pathology image using deep learning and CNN. This repository contains the source codes used for this project. The source codes for training deep learning models and also for the back-end of the web appliction were developed using [Google Colab], a Google's version of Jupyter Notebook. The [GUI] for the web application was developed using [Anvil]. All source codes were written in Python language.

Sourcecode was developed and tested with: 
- Python - 3.6.9
- Keras - 2.3.0
- TensorFlow - 2.3.0

| Source code | Descriptions|
| ------ | ------ |
| Colab - Training | Algorithms for transfer learning, model development, data augmentation, training and evaluating deep learning models.|
| Colab - Web Application (Back-end) | Algorithms for fetching and sending image from Anvil application via Anvil Uplink. Also contains algorithm used for slicing and stitching image, and making prediction using a deep learning model.  |
| Anvil - Web Application (GUI)| Python code that defines the layout of the web application. |




## _Instruction for running web application_
1. Open [Anvil Web App GUI].
2. Load **System_web_app_(Backend).ipynb** python notebook into Google Colab.
3. In Colab, goto __"Load Model"__ section. Edit the _model_directory_ to the directory of the the model in Google Drive (/content/gdrive/MyDrive/...). Rename the _model_name_ to the file name of your model.
4. In Anvil, goto setting(gear icon) > Uplink. Copy the uplink key.
5. In Colab, goto __"Main"__ section. Make sure the string of _uplink_key_ is similar to the one in Anvil. If not paste the new key.
6. In Anvil, click run.
7. In Colab, run the __"Library"__, __"Load Model"__ and __"Main"__ sections. The __"Main"__ section will run forever waiting for interaction in Anvil.
8. DONE!

[Anvil]: https://anvil.works/build#clone:FBM5VHPXV3N7HNS4=RS2U5JK5G5K7UCQUGXPI46PD
[GUI]: https://anvil.works/build#clone:FBM5VHPXV3N7HNS4=RS2U5JK5G5K7UCQUGXPI46PD
[Anvil Web App GUI]: https://anvil.works/build#clone:FBM5VHPXV3N7HNS4=RS2U5JK5G5K7UCQUGXPI46PD
[Google Colab]: https://colab.research.google.com/

##### _by Mahir Sehmi_
