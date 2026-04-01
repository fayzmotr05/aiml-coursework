# Deep Learning Notebooks

A collection of Jupyter notebooks covering foundational deep learning topics, built with PyTorch and NumPy. Notebooks follow the lab order from the course.

## Contents

| Lab | Notebook | Topic |
|-----|----------|-------|
| —   | `00_index.ipynb` | Index / placeholder |
| 2A  | `01_numpy_matplotlib_review.ipynb` | NumPy and Matplotlib refresher |
| 2B  | `02_perceptron_intro.ipynb` | The perceptron from first principles |
| 3   | `03_pytorch_tensors.ipynb` | PyTorch tensor basics |
| 4   | `04_nn_from_scratch_xor.ipynb` | A small NN learning XOR (forward/backward in NumPy) |
| 5   | `05_rnn_lstm_gru_text_gen.ipynb` | Character-level text generation with RNN / LSTM / GRU |
| 6   | `06_hyperparameter_tuning.ipynb` | Hyperparameter search and regularization |
| 7   | `07_cnn_image_classification.ipynb` | CNNs for image classification |
| 8   | `08_transfer_learning_tutorial.ipynb` | Transfer learning walkthrough (VGG16 / ResNet50 on CIFAR-10) |
| 8   | `09_transfer_learning_lab.ipynb` | Transfer learning practice exercises |
| 9   | `10_attention_mechanisms.ipynb` | Attention mechanisms |

## Getting started

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install numpy matplotlib torch torchvision jupyter tqdm
jupyter lab
```

GPU is recommended for labs 5, 7, 8, and 9. On Colab, enable **Runtime → Change runtime type → GPU**.

## Notes

Cell outputs are intentionally cleared so the notebooks open cleanly in version control. Run them top-to-bottom to reproduce the results.
