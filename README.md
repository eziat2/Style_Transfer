# Style Transfer

Tony Sinn |  University of Toronto SCS3546 (Deep Learning) | Professor: Sina Jamshidi | Aug 2, 2022

## Possible Business Use Cases
1) Commercial art -  From poetry to artwork to music. (eg. https://www.christies.com/features/A-collaboration-between-two-artists-one-human-one-a-machine-9332-1.aspx)
2) Photo and video editors - One of the most clear applications of style transfer is in photo and video editing software
3) Virtual reality - While the applications with style transfer in VR are still largely in the research phase, the possibilities are exciting and promising. Facebook touts the potential of style transfer to radically alter the ways VR developers tell visual stories through their applications, games, films, and more.

## Prerequisites
Python 3.7

Tensorflow 2

Jupyter Notebooks

Google Drive

## How to run
Colab Jupyter Notebook - with GPU and High-RAM

Open

Run all Cells

## Contents
README.md: This file, explaining the project

Final_project_presentation_v2.pptx: Project presentation in Power Point format

Project_NeuralStyleTransfer.ipynb

Project_ArbitaryStyleTransfer.ipynb


## Stylized Images
![image](https://user-images.githubusercontent.com/32421212/181109158-78a890b6-fcb5-47e7-943e-d014a211b251.png)
![image](https://user-images.githubusercontent.com/32421212/181109100-eb1d97e1-cc7e-4a2f-b517-a9dfae8c99c7.png)

### Arbitary Style Transfer 
![image](https://user-images.githubusercontent.com/32421212/180916069-4e9116ca-db7b-4fae-b844-92d8312c99de.png)
![image](https://user-images.githubusercontent.com/32421212/180916152-1eb0c140-ba84-411c-8738-3339c5b641ca.png)
![image](https://user-images.githubusercontent.com/32421212/180916182-b1391b32-50cb-45c5-acba-7493edbc51af.png)
![image](https://user-images.githubusercontent.com/32421212/180916212-9f71eb77-c696-4fc8-bc6e-c832abe99218.png)
![image](https://user-images.githubusercontent.com/32421212/180916228-f985faae-6a27-46bc-be9d-1f6c0a143cab.png)
![image](https://user-images.githubusercontent.com/32421212/181006643-0a6279a4-9d32-4211-8a9f-05e52e0b46c4.png)

### Style Transfer with Tensorflow lite
![image](https://user-images.githubusercontent.com/32421212/181101385-915ba603-6bf6-438c-9688-a0fa19cea774.png)
![image](https://user-images.githubusercontent.com/32421212/181101439-535a8c74-a0df-478e-a951-6c00fb194abf.png)

### Style Transfer using VGG19 - Transfer Learning

![image](https://user-images.githubusercontent.com/32421212/181125561-03bb533d-6872-49b6-b5b9-90c9ab868d76.png)
![image](https://user-images.githubusercontent.com/32421212/181125620-e906e654-5e1b-4d1d-96e6-cb74836a34a6.png)


## Lesson Learned
1. Neural Style Transfer using VGG19 and Transfer Learning – It takes a lot of time to train the model and get the stylized image but you can have better control on the features you may want to emphasis. (E.g. Texture, contrast or color)

2. With Arbitrary Style Transfer the stylized images got generated very fast style. Whether the style is Escher, Van Gogh and Monet.

3.With Tensor flow lite model the model can be load on the device to generate image.

4.In the future we can try style transfer for video using the Arbitrary Style Transfer


## References
Articles / Paper
https://www.christies.com/features/A-collaboration-between-two-artists-one-human-one-a-machine-9332-1.aspx
https://www.fritz.ai/style-transfer/#part-uses
https://arxiv.org/pdf/1703.06868.pdf
Code
https://colab.research.google.com/drive/1amO7FjN_qE0KdvSyF_gamrwDYCiCTpTa
https://www.tensorflow.org/hub/tutorials/tf2_arbitrary_image_stylization
https://www.tensorflow.org/tutorials/generative/style_transfer
https://towardsdatascience.com/tensorflow-and-vgg19-can-help-you-convert-your-photos-into-beautiful-pop-art-pieces-c1abe87e7e01
https://github.com/xunhuang1995/AdaIN-style
Video
https://youtu.be/e718uVAW3KU
https://www.techleer.com/articles/466-insight-into-fast-style-transfer-in-tensorflow/
https://github.com/xunhuang1995/AdaIN-style
