# Deep Learning Labs

Coursework notebooks covering foundational deep learning topics in PyTorch and NumPy.

## Lab index

| Lab | Notebook | Topic |
|-----|----------|-------|
| 2A  | [`lab2a_numpy_matplotlib.ipynb`](lab2a_numpy_matplotlib.ipynb) | NumPy & Matplotlib refresher |
| 2B  | [`lab2b_perceptron.ipynb`](lab2b_perceptron.ipynb) | The perceptron from first principles |
| 3B  | [`lab3b_pytorch_exercises.ipynb`](lab3b_pytorch_exercises.ipynb) | PyTorch fundamentals — exercises |
| 5   | [`lab5_xor_neural_net.ipynb`](lab5_xor_neural_net.ipynb) | NN from scratch in NumPy (XOR) |
| 6   | [`lab6_hyperparam_tuning.ipynb`](lab6_hyperparam_tuning.ipynb) | Hyperparameter tuning & regularization |
| 7   | [`lab7_cnn_image_classification.ipynb`](lab7_cnn_image_classification.ipynb) | CNNs for image classification |
| 8   | [`lab8_transfer_learning.ipynb`](lab8_transfer_learning.ipynb) | Transfer learning — walkthrough + exercises (VGG16 / ResNet50) |
| 9   | [`lab9_rnn_lstm_gru.ipynb`](lab9_rnn_lstm_gru.ipynb) | RNN / LSTM / GRU for text generation |
| 10  | [`lab10_attention.ipynb`](lab10_attention.ipynb) | Attention mechanisms |
| 12  | [`lab12_gans.ipynb`](lab12_gans.ipynb) | Implementing GANs — vanilla GAN on MNIST |

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install numpy matplotlib torch torchvision jupyter tqdm
jupyter lab
```

GPU recommended for labs 7–10. On Colab, enable **Runtime → Change runtime type → GPU**.

## Notes

Cell outputs are cleared so the notebooks open cleanly in version control. Run them top-to-bottom to reproduce results.
