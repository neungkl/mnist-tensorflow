# MNIST tensorflow
Just an ordinary project for trying TensorFlow

MNIST is dataset that has been widely use for machine learning beginning (many said it is "hello world" for computer vision).
It is a single digit handwritten dataset that release since 1999.

More description [https://www.kaggle.com/c/digit-recognizer](https://www.kaggle.com/c/digit-recognizer)

<img src=".github/mnist-preview.png">

This is my first public GitHub project for trying TensorFlow with MNIST dataset.

## Usage

1. `docker-compose up`
2. After completed run the docker. It will show the correct path to open the python notebook.

Example (Your screen maybe different to this example)
```
tensorflow_1  |     Copy/paste this URL into your browser when you connect for the first time,
tensorflow_1  |     to login with a token:
tensorflow_1  |         http://localhost:8888/?token=abcdef
```

You just simply enter [http://localhost:8888/?token=abcdef](http://localhost:8888/) to your browser and have fun :D

## Architecture

Convolutional neural network with 2 layers and fully connected layer in the last one.<br>
Similar architecture in [TensorFlow tutorial](https://www.tensorflow.org/get_started/mnist/pros) but some paraters are changed (patch size, depth size).

## Result

Accuracy: 98.543%

## License

[MIT License](LICENSE) Copyright (c) 2017 Kosate Limpongsa