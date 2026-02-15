### Lab 5 

### Methadology 
    1 - Face Detection - Done using the Haar-cascades dataset (built into the OpenCV toolkit).
    2 - Feature Extraction - Extracted images were converted from BGR to the HSV colourspace. The features extracted were the mean hue and saturation of each face.
    3 - Clustering - was done with the KMeans clustering algorithm with a value of K = 2 .
    4 - Template Matching - A template image was processed using the same pipeline and assigned to the cluster to the centroid of which it was clostest to.


### Results

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/573f5c54-696c-4b57-ac59-835e278752df" />

### Clustering with means

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/089db5c1-eae0-428c-9059-18f4d32675e9" />

### With template

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/21fd20c4-61f8-46eb-bab0-832fc1f3df8b" />

### Assigning a cluster to the given photo of Shashi Tharoor.

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/8da76b4f-6aee-4b28-ada5-9f1cef8f38b2" />





