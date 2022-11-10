# SteganoClassifier

This project is a stenography classifier that uses three different machine learning method's.

## Usage

This project uses docker and uses the TensorFlow data science image.

Pull TensorFlow image

```bash
docker pull jupyter/tensorflow-notebook:latest
```

Run in the root of the the project

```bash
docker run -it --rm -p 8888:8888 -v "${PWD}":/home/jovyan/work jupyter/tensorflow-notebook:latest
```
