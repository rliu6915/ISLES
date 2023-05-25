# Image Segmentation of Skin Cancer Lesion
  Skin cancer is a major public health problem, with over 5,000,000 newly diagnosed cases in the United States every year. Among all skin cancers, Melanoma is the deadliest form of skin cancer, responsible for an overwhelming majority of skin cancer deaths. Although the mortality is significant, when detected early, melanoma survival exceeds 95%. Therefore, it would be very beneficial for patients that could detect their lesion at an early stage. We try to go further to solve the “confusion image” of skin cancers given the fact that even doctors cannot distinguish various types of skin cancer at the first glance. So here comes the use of image segmentation and classification techniques, which would help the doctors to identify the lesion and give a suggestion of whether it is a cancer or not. Besides that, on our side, it is also a chance for us to look into the application of deep learning on medical imaging, which all of us are quite interested in.
  In this project, we propose to segment and classify the skin cancer lesion from dermoscopy images. We are using the dataset from the International Skin Imaging Collaboration Challenge 2016, which contains a set of original images and their ground truth mask for segmentation. For the segmentation task, our model segments the region of skin cancer lesion from any given dermoscopy image, and also generates a mask to show where the lesion is; and for the classification task, our trained model could give a prediction of whether the lesion is benign or malignant. Our model will be evaluated by the accuracy of prediction on the testing data.
