# Skin Disease Classification
### This Project was developed for Solving For India (a hackathon organized by GFG in collaboration with Google Cloud and AMD). 
In this project, the goal is to build a skin disease classification system that can identify various skin conditions from input images. The project utilizes the popular VGG16 pre-trained model, known for its excellent performance in image recognition tasks, as the backbone for the classification process. The VGG16 model has been fine-tuned to suit the specific requirements of the skin disease classification problem.

To train and validate the model, an Image Data Generator is employed. The Image Data Generator allows the augmentation of training data, which helps enhance the model's ability to generalize and improve accuracy. Data augmentation techniques like random rotations, flips, and zooming are applied to generate diverse training samples from the available data, thus mitigating overfitting issues.

After training, the model achieves an accuracy of 54% on the validation dataset. While this accuracy might not be as high as desired, it serves as a baseline for further improvements. Possible ways to improve accuracy include increasing the amount of training data, adjusting hyperparameters, or exploring more sophisticated architectures.

On the implementation side, the skin disease classification model is integrated into a FastAPI backend. FastAPI is a high-performance web framework that enables efficient handling of HTTP requests and responses. By deploying the model with FastAPI, the system can efficiently classify skin disease images in real time through API endpoints.

The system's frontend can be developed using any suitable technology, allowing users to interact with the model via a user-friendly interface. Users can upload skin disease images through the frontend, and the FastAPI backend will process the images through the VGG16 pre-trained model to provide classification results.

In conclusion, the project successfully builds a skin disease classification system using a pre-trained VGG16 model with data augmentation. While the current accuracy is 54%, it lays the groundwork for future improvements. The FastAPI backend ensures efficient and responsive classification, making the system suitable for real-world applications in the field of dermatology and healthcare.
