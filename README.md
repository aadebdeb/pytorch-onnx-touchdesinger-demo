# pytorch-onnx-touchdesigner-demo

1. Neural network for MNIST is trained using Pytorch.
2. Model of trained network is exported as ONNX format.
3. Exported model is used with OpenCV dnn module in TouchDesigner. 


## Usage

Run commands below to train and export neural network,

```
$ cd python
$ python -m venv .venv
$ . .venv/bin/activate
$ pip install -r requirements.txt
$ python train.py
```

then copy exported onnx file to `/touchdesigner/assets/onnx` and open ToudhDesigner file.


