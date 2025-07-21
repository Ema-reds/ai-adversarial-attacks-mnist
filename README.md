Adversarial Attacks on MNIST using FGSM
This project demonstrates a basic image classification pipeline on the MNIST dataset using a simple MLP (multi-layer perceptron) classifier, and then applies the Fast Gradient Sign Method (FGSM) to perform adversarial attacks.

🧠 What It Does
Loads and visualizes the MNIST dataset (handwritten digits)

Builds a neural network to classify digits 0–9

Achieves over 94% accuracy on clean test data

Applies FGSM to generate adversarial examples

Shows that small, imperceptible perturbations can cause the model to misclassify

Measures accuracy degradation under attack

⚔️ Adversarial Technique
FGSM (Fast Gradient Sign Method):
Adds perturbation in the direction of the gradient of the loss with respect to input pixels.
The result is a nearly identical image that fools the classifier.

📊 Results
Test Scenario: Clean Images → Accuracy: ~94.65%
Test Scenario: Adversarial (ε = 0.2) → Accuracy: ~XX% (to be filled based on your run)

🖼️ Example (Adversarial Confusion)
3 → 8
1 → 7
2 → 6

📁 Files
main.ipynb – Notebook with full pipeline and attack

requirements.txt – Python packages used

.venv/ – (not included in GitHub, local environment)

✅ How to Run
pip install -r requirements.txt
jupyter notebook main.ipynb

Tested on macOS with Python 3.10+ and PyTorch.

🔐 Author
Emanuele Rossi – AI Red Teaming project portfolio.

