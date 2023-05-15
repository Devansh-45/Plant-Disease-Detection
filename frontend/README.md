# Plant Disease Detection

🌱🔍🍅

![Germany, Stuttgart, Magical orange sunset sky above ripe grain field nature landscape in summer Germany, Stuttgart, Magical orange sunset sky above ripe grain field nature landscape in summer farm stock pictures, royalty-free photos & images](https://media.istockphoto.com/id/1280715716/photo/germany-stuttgart-magical-orange-sunset-sky-above-ripe-grain-field-nature-landscape-in-summer.jpg?s=612x612&w=0&k=20&c=TukToGq-LkmpxvEXEomC3d11prf_hDRSwA7pYsLYG50=)

## Introduction
This project focuses on detecting diseases in potato, pepper, and tomato plants using computer vision techniques. The goal is to develop a model that can accurately identify and classify plant diseases based on images.

## Dataset
The project utilizes the Plant Village dataset available on Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/arjuntejaswi/plant-village). It contains a collection of images depicting healthy plants as well as plants affected by various diseases.

## Dependencies
The following libraries and tools were used in this project:
- NumPy 🧮
- Pandas 🐼
- Seaborn 🌊
- Matplotlib 📊
- Kaggle API 📁
- Convolutional Neural Networks (CNN) 🧠
- Flask 🌐
- PyTorch 🔥
- FastAPI 🚀
- Postman 📮

## Methodology
1. Data Preparation: The dataset was downloaded from Kaggle using the Kaggle API and preprocessed to create training and testing sets. Data augmentation techniques, such as random rotations and flips, were applied to increase the robustness of the model.

2. Model Training: A Convolutional Neural Network (CNN) architecture was employed to train a plant disease detection model. Transfer learning using pre-trained models, such as ResNet or VGG, was also explored to leverage their learned features.

3. Model Evaluation: The performance of the model was evaluated using appropriate evaluation metrics such as accuracy, precision, recall, and F1 score. The model's ability to correctly classify plant diseases was assessed on the testing set.

4. Deployment: The model was deployed as a web application using FastAPI. Users can submit plant images through the web interface or using tools like Postman to receive predictions on whether the plant is healthy or affected by a disease.

## Usage
1. Clone the repository:

2. Clone the repository:
   ```shell
   git clone https://github.com/Devansh-45/Plant-Disease-Detection
3.  Install the required dependencies:
    
    `pip install -r requirements.txt`

4. Download the Plant Village dataset from Kaggle and place it in the project directory.

5. Train the model:
	```shell
	main.py

This will train the plant disease detection model on the dataset.

5. Run the FastAPI web application:
	```shell
	uvicorn main:app --reload

Access the web application at `http://localhost:3000` in your web browser or use tools like Postman to interact with the API.

Feel free to customize the project or modify the code to suit your specific needs. If you encounter any issues or have questions, please don't hesitate to reach out for support.

## Results
The Plant Disease Detection model aims to accurately identify and classify diseases in potato, pepper, and tomato plants. By leveraging computer vision techniques, the model assists in early disease detection, allowing for timely intervention and better plant health management.

![](https://lh3.googleusercontent.com/pBtPUQyMNDYjQuTTyP1HS4cRDG9v1Rpi8MXUYRUUMbLRmJARNN6cnYbDWPLKaNbOmSrOY6iCdfCruEPoX76BW6At1knFYc1hJjUmbG9oQ5H-ycL88ko4mo-AWlHH59AnQqrRMMqOv8EyWdGcNBg9GG0Cb-FIR_KgPbds452bZte4KaQ9Er3zfkvudcvCpSC-cKlL5JkoZ0VVogEDXNlTA0qXFKGyWC2ghO6EUvOctzsqjA8--GBLglIFjIrzbxyfCp0t48x5urWCqf4-w3s7DYmITrzQpwjF1SaMUcxlR4lsSMVW1W7oSMvpPRycG7KH6JuS_ngIlihrFSrWmMydoMDCDxCvqKVQXBXFnviY1dd0XPtg8n8aBv5EDzi-1jrJCL4igTMVC-8t8ZYGOr01IxgXeqynDFxKXctD_5x_SVz79o68_4yaSU-JpCEVOw3uBlE0rr_vvT_csCz4eppJYnEiCln6QInWwG043uDMfSxvwP5JrYhLJSZkrjAiWTI2jDBBvctRzfbDujfuQErIFsHrfZ9oTriUXaAMLAgOGaaUMm5ZBDyrztTf-jK7mngmBisKaLi1eSDM338IwFV5ccbB94aI_yIqcVV07umaNRTK4DLC4XtQklhyVTsS3zzrpnTIUC7kTFS_ueD_UKOZG1p-JvXLqn8FtqJ2QJAuo2QSsAstrxmSkgNXHlhj4Bz-mVLe0i7K60zuUmERKHypXAUt1KDYf-zEhZGjiIIY1aw4vgJpNivHE_Tu0mf75gPCeHRXx8QlcShg-XnxxU__rh_WAjy2d20aGJGYNCnsAW6aPVkIislAa3M51yEFNLSKULCgGgVt11quKBY5w7TyWM0zWWbWakBhfkPjFePmGqSXbH8dahscZUaojGIcc99Nj86UsNzX-IK_mMOezdKfPm82ILN5a8XBh1-fknDX18eLaIocB2Z1hUaU2RqWgUy-TrLQ9zrl-KkxknLeXg=w1330-h672-s-no?authuser=0)
## Future Enhancements
Here are some ideas to further enhance the project:

- Implement an image segmentation approach to localize and classify individual lesions or affected areas within a plant.
- Incorporate additional plant species and diseases into the dataset to improve the model's versatility.
- Deploy the web application on a cloud platform to make it accessible online.

## Contributors
- [Devansh Desai](https://github.com/Devansh-45)

Contributions to this project are welcome. Feel free to open
