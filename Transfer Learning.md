# Transfer Learning

- An ML technique where a model trained on one task is used as a starting point for a related task.
- The skills or relationship/pattern learned in one task can be applied and adapted to another.

### Example: Image Classification

Dog vs. Cat Classification
- A model is trained on a dataset of thousands of dog and cat images.
- The model learns to identify features like ears, tails, and fur patterns distinguishing dogs from cats.

Breed Identification
- Instead of training a new model from scratch for breed identification, we can use the pre-trained model.
- The model's ability to recognize general dog and cat features is a good starting point.
- We fine-tune the model on a dataset of various dog breeds.
- The model adapts its learned features to differentiate between specific breeds.

### Why Transfer Learning?
- **Saves time and resources:** Training a model from scratch requires a massive dataset and significant computational power.
- **Improves performance:** A pre-trained model often better understands general patterns, leading to improved accuracy on related tasks.
- **Enables learning with limited data:** When datasets are small, transfer learning can help by providing a strong foundation.

### Key Concepts
- **Pre-trained model:** A model that has already been trained on a large dataset.
- **Fine-tuning:** The process of adjusting the pre-trained model's weights to specialize it for a new task.
- **Feature extraction:** The process of extracting meaningful features from the input data.
