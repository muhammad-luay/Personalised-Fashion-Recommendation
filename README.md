# Personalized Fashion Recommendation

This project aims to provide personalized fashion recommendations based on image recognition using the ResNet50 deep learning model.


 ![image](https://github.com/muhammad-luay/Personalised-Fashion-Recommendation/assets/62732628/be092821-3fdf-41dc-8e9d-5d13c88edf95)

 ![image](https://github.com/muhammad-luay/Personalised-Fashion-Recommendation/assets/62732628/e4d7597f-64ba-4511-a902-73178847dd01)

 ![image](https://github.com/muhammad-luay/Personalised-Fashion-Recommendation/assets/62732628/1c874c64-7be3-48c8-9b15-5d23a800b42b)





## How It Works

1. We use a pre-trained ResNet50 model to extract features from fashion images.
2. These features are then used to train a nearest neighbors model, which allows us to find the most similar images to a given input.
3. Users can either input a specific image to get recommendations or use the random sampling function to explore similar items for random samples.

## Dependencies

- TensorFlow
- Scipy
- Pandas
- Glob
- Matplotlib
- Pillow (PIL)
- Scikit-learn

## Usage

To use the recommendation system:

1. Ensure all dependencies are installed.
2. Load your fashion images in the specified directory structure.
3. Run the provided Jupyter notebook or Python script to initialize the model and explore recommendations.

## Future Work

- Explore other pre-trained models or customize the ResNet50 architecture for better performance.
- Implement a user interface for easier interaction and exploration.

## License

This project is open-sourced under the MIT license.

