# mnist-mlflow-tracking
Tracking MNIST digit-classification experiments with MLflow on DagsHub. A baseline dense neural network (Flatten → Dense 128 ReLU → Softmax, Adam, batch size 64, 50 epochs) is compared against variants with different depths, widths, optimizers, batch sizes and epoch counts. Built with TensorFlow/Keras, with autologged metrics.
