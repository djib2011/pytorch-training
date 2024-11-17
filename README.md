# PyTorch training

> Note: This is a fairly new repo and most of the material have not been proofread yet! If you encounter any errors or typos let me know so I can fix them!

## Scope

This training aims at teaching people the frameworks of PyTorch and Lightning from a technical standpoint. It is not meant to teach Neural Network or Machine Learning/Deep Learning concepts, instead it assumes some basic theoretical understanding of these.

## Structure:

### PT101

1. **Intro to Pytorch Lightning**
	- Basics. What is PyTorch? What is Lightning?
	- Defining models in Lightning
	- Model training and evaluation
	
2. **Customizing model architectures and training**
	- Model customization 
	- Different trainer options
	- Callbacks 
	- Saving/Loading models

3. **Practical aspects**
	- Logging to  Weights&Biases  
	- Hyperparameter Tuning

4. **Using pretrained models**
	- Basic principles. Why use pretrained models? Where to find pretrained models?
	- Using pretrained models out-of-the-box.
	- Fine-tuning

### PT102 (PoC)

*Note: these topics are still in a PoC-level. They will be refined when I start working on this section!*

1. **Vanilla PyTorch Training**
	- Creating and training a NN without Lightning
	- Advanced model engineering (multi-input/output models, embeddings, etc.)

2. **GPU logistics and computational graphs** 
	- Tensor placement and device management
	- Introduction to the computational graph
	- Gradient tracking and AutoGrad
	- Managing the computational graph 

3. **Data Handling**
	- Deeper look into Torch's TensorDataset and DataLoader
	- Data preprocessing with Transforms
	- Cleaner implementation with Lightning's DataModule
	- Data augmentation

4. **Advanced Concepts**
	- Advanced training concepts (gradient accumulation, clipping, mixed-precision training, etc.)
	- Distributed training (i.e. multi-GPU setups)
	- Model deployment and retraining
	- Model performance optimization (distillation, quantization, pruning, etc.)
	- Interpretability

