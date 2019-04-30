The raw dataset is ProstateX2 dataset, from: 
https://wiki.cancerimagingarchive.net/display/Public/SPIE-AAPM-NCI+PROSTATEx+Challenges#28fc5437b58e4846b2684de7e00d1eaf

ProstateXRegister.ipynb takes in the raw dataset, preprocess them and churn out prostateX-Register-chopedcropped-60-4channels.

ProstateX-Register-chopedcropped-60-4channels can be downloaded from our google drive following rhe codes in MultiparametricMRI.ipynb. MultiparametricMRI.ipynb takes in prostateX-Register-chopedcropped-60-4channels, splits the train, validate set, train a 3D CNN model and predicts on the validate set.