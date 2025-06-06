# Generative Adversarial Network (GAN)
This project contains an implementation of a Generative Adversarial Network (GAN) from scratch, designed to generate synthetic data that mimics real-world input distributions. This repository includes training logic, visualization, and insights into GAN behavior, developed in a Jupyter Notebook format.

# 📁 Project Structure
.<br>
├── Generative_Adversarial_Network.ipynb  # Main implementation of GAN  <br>
├── README.md                             # Project documentation <br>

# 🧠 About GANs
### A Generative Adversarial Network consists of two neural networks:
#### Generator: Learns to produce data similar to the real dataset.  
#### Discriminator: Learns to distinguish between real and fake data.

### These networks are trained in opposition to each other, resulting in a generator that creates increasingly realistic data.

# 🛠️ Features
#### Generator and discriminator built from scratch  
#### Custom training loop  
#### Custom Callback Function to save generated images after 10 epochs
#### Loss visualization over epochs  
#### Data generation and output visualization  
##### Easily extendable architecture for different datasets  

# 🧪 Dependencies
#### Make sure to install the following libraries:
##### pip install numpy matplotlib tensorflow numpy  

# ▶️ How to Run
## Clone the repository:
##### git clone https://github.com/yourusername/Generative_Adversarial_Network.git  
##### cd Generative_Adversarial_Network  

## Launch Jupyter Notebook:
##### jupyter notebook  
##### Open the Generative_Adversarial_Network.ipynb and run all cells to train and visualize the GAN.

# 📊 Sample Output
##### Once trained, the notebook visualizes how generated data evolves over time. Sample images/data are plotted for each epoch to illustrate training progress of the generator.

# 📌 Also TODO
##### Support for different datasets (e.g., MNIST, CIFAR-10) – Currently trained on random noise mapped to 2D Gaussian blobs.  
##### Add evaluation metrics like Inception Score or FID – Not included yet.  
##### Hyperparameter tuning section – Basic setup with learning rates and batch size; no extensive tuning done yet.  

##### Export trained models – Not implemented in this version, but can be added with `model.save()` from TensorFlow/Keras.

📜 License  
This project is open-source and available under the MIT License.

🤝 Contributing  
Pull requests are welcome! If you’d like to contribute, please fork the repository and submit a PR with a clear description of your changes.
