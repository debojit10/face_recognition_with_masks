# FACE RECOGNITION WITH OR WITHOUT MASKS ON 
recognizing masked faces

The pipeline is to create a custom face detector because existing face detection models fail to detect faces with masks. Then put masks on the faces of the subjects so our detector crops our area of interest. The classifier is trained on both masked and non masked faces of the same subjects. Masking the faces improves the classifer to recognize new faces without masks.

Link to face detector model https://github.com/aqeelanwar/MaskTheFace

Link to labeled faces to detect uncovered part of the face https://drive.google.com/file/d/1yI9U_5ESPiT99CkLGthc75LD7iCOT6EN/view?usp=sharing

Link to facenet model for generating face embedding https://drive.google.com/drive/folders/1pwQ3H4aJ8a6yyJHZkTwtjcL4wYWQb7bn?usp=sharing

Link to the [Colab_custom_object_detection_notebook](https://colab.research.google.com/drive/1oET1x69OSNiVFB3keA7-pro917qULM6c#scrollTo=9KNv1N_hUibE)
 
Link to the [Colab_inference_cv2_notebook](https://colab.research.google.com/drive/1se3MKnl01QI5WC3xSH7J8LZTZkpTyZ_J?authuser=1#scrollTo=9-WczWUGNQT2)

To replicate the results just add some custom faces to the faces_recognition folder and use [mask_the_face](https://github.com/aqeelanwar/MaskTheFace) to mask all the faces and remember to keep original. What it does that it helps the classifier to learn the features from the upper face part.
