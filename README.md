# [Teach Old Dog New Tricks - Train Facial identification model to understand Facial Emotion](https://www.dlology.com/blog/teach-old-dog-new-tricks-train-facial-identification-model-to-understand-facial-emotion/)

### Download the dataset
You can download the [fer2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) dataset from Kaggle. Each picture is 48x48 pixel grayscale images of faces.

After download, decompress it to directory datasets so we have `./datasets/fer2013/fer2013.csv`
### Install keras_vggface package
Since we are going to turn Keras model to TF Estimator, so use my modified version of **keras_vggface** model.
We are importing **keras** from **tensorflow** package.

```
git clone https://github.com/Tony607/keras_vggface
cd keras_vggface
python3 ./setup.py install
```
Run the `jupyter notebook` as usual.

Post your comments and questions in my [blog](https://www.dlology.com/blog/teach-old-dog-new-tricks-train-facial-identification-model-to-understand-facial-emotion/) and stay tuned for future practiacl deep learning experiences.
Happy coding!