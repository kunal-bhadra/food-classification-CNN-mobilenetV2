
# Food Recognition with CNN

This is a project built while participating in the AIcrowd KIIT(AI) Mini Blitz Challenge and is the second one out of the three challenges given. We are given a train and test set and the objective is to detect the what food item is presen in the given image. This task only concerns with recognition and not localization, since we assume that there's one food class per image. For this, I went with CNNs and worked with about 9000+ datapoints. 


  
## 🚀 The Result

I was able to score a **F1 of 0.529** on the test set and secured the first place for this specific puzzle as of now. 
 

## ✏ Tech Stack for Project Development

- Python
- Numpy
- Pandas
- Plotply
- Seaborn
- Scikit-learn
- Tensorflow

  
## 🧠 The Approach

 We used a Convolutional Neural Network with a pretrained model of **Mobilenet_V2** and added two dense Keras layers on top which would, fine-tune it based on our specific dataset. For training, we trained for only 7 epochs and implemented early stopping to be efficient. At the end, the predictions on approximately 500 unlabelled images were submitted to get the above score. 

  

## 🔗 Connect with me:
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.polywork.com/kunal_bhadra)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kunal-bhadra-cs/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/kunal_kaun)

  