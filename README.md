# Multi-Modal Product Classification with BERT and ResNet-18
This repository's goal is to build a multi-modal classifier that categorizes fashion products by simultaneously processing both their visual images and textual descriptions.

🚀 Project Overview
In e-commerce, products are often described by both titles and images. This model leverages the power of:

Computer Vision: Using ResNet-18 to extract spatial features from product images.

Natural Language Processing: Using BERT (base-uncased) to capture the semantic meaning of product display names.

Feature Fusion: Combining these two modalities via concatenation to make a more informed final prediction.

🛠️ Technical Stack
Deep Learning Framework: PyTorch

Computer Vision: Pre-trained ResNet-18

NLP: Hugging Face Transformers (BERT)

Interface: Gradio

Analysis Tools: Python, Pandas, NumPy, Matplotlib

📊 Dataset & Performance
The model was trained on the Fashion Product Images Dataset.

Training Samples: 5,000 images and titles.

Performance Metric: Macro-F1 Score was used to evaluate the model, ensuring balanced performance across different product categories.

Evaluation Results: The model demonstrates high accuracy in identifying categories like Apparel, Footwear, and Accessories.
