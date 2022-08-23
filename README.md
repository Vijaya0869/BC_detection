# Breast Cancer Detection using Digital Image Processing Techniques

![logo bc_detection](https://user-images.githubusercontent.com/109131720/182790612-aa69d125-5913-4fcb-b28f-fd03f77869ed.jpg)

# Introduction :
Breast cancer is a cancer that develops in the breast and spreads to other parts of the body. When cells proliferate out of control, cancer develops. Breast cancer cells typically form a tumor, which can be seen on x-rays or felt as a lump. It is one of the major causes of death in women and it is difficult to prevent breast cancer as the main reasons underlying breast cancer remain unknown. Characteristics of breast cancer, such as masses and microcalcifications visible in mammograms, can be employed for early diagnosis and hence are highly beneficial for women who may be at risk of developing malignant tumors.A mammogram is nothing but an x-ray of breast and it is used to look for any changes in the breast. A mammogram makes it easy to treat by finding and detecting breast cancer early, when the tumor is small and even before a lump can be felt.It's critical to remember that the majority of breast lumps are benign and not cancerous (malignant). Breast tumors that aren't cancerous are abnormal growths that don't spread outside of the breast. Although benign breast lumps are not life threatening, they can raise a woman's risk of developing breast cancer. Any lump or change in your breast should be evaluated by a health care specialist to see if it's benign or malignant (cancer) and if it'll alter your cancer risk in the future.
So,using Digital image processing techniques such as image pre-processing, image segmentation, feature extraction and image classification are applied in this project on the digital mammogram images to achieve early and automated detection of breast cancer.

# Datasets
Train dataset - 5724 mammograms
Test dataset -  1908 mammograms
The datasets contains breast mammography images(224,224,3). With labels of:
1. Benign :
![tumor_i1](https://user-images.githubusercontent.com/109131720/185968183-ba3e9bd9-4ceb-469b-832b-4508847d9c6f.jpg)

2. Malignant :
![tumor_i2](https://user-images.githubusercontent.com/109131720/185968604-dad391d2-15a1-49dd-a528-a86f4f01f412.jpg)

# Methodolody:

![methodology](https://user-images.githubusercontent.com/109131720/186214997-338d7a0d-7d82-4af2-b96e-d59252718280.jpg)
Detection of breast cancer in its early stages using image processing techniques includes four
parts. In the first part the digital images (mammograms) are pre-processed to remove any kind
noise. Then in the second part the images undergo the segmentation process to enhance the
tumor part. After this, in the third part, the important features in the segmented images are
extracted. Finally, in the fourth part, with the help of the extracted features, the images are
classified into normal, benign or malignant. Here, ‘normal’ represents the breast with no tumor,
‘benign’ represents the breast with non-cancerous tumor and ‘malignant’ represents breast with
cancerous tumor.

# Role Of Machine Learning In Detection Of Breast Cancer
A mammogram is an x-ray picture of the breast. It can be used to check for breast cancer in women who have no signs or symptoms of the disease. It can also be used if you have a lump or other sign of breast cancer.

Screening mammography is the type of mammogram that checks you when you have no symptoms. It can help reduce the number of deaths from breast cancer among women ages 40 to 70. But it can also have drawbacks. Mammograms can sometimes find something that looks abnormal but isn't cancer. This leads to further testing and can cause you anxiety. Sometimes mammograms can miss cancer when it is there. It also exposes you to radiation. You should talk to your doctor about the benefits and drawbacks of mammograms. Together, you can decide when to start and how often to have a mammogram.

Now while its difficult to figure out for physicians by seeing only images of x-ray that weather the tumor is toxic or not training a machine learning model according to the identification of tumour can be of great help.

# Results :
![finalop graph](https://user-images.githubusercontent.com/109131720/185975791-4650b319-ff66-4a78-884a-904a26801cba.jpg)


