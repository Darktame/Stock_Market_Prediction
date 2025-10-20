# Stock Market Prediction with Deep Learning

This project explores the use of various deep learning models to predict stock market prices. It includes implementations of Long Short-Term Memory (LSTM), Variational Autoencoders (VAE), and Diffusion models for time-series forecasting.

##  Dataset

This project uses the StockNet dataset, which contains historical stock prices.

* **Source:** [StockNet Dataset on GitHub](https://github.com/yumoxu/stocknet-dataset/tree/master/price/raw)

You should download the relevant CSV files and place them in a `data/` folder within the project directory.

##  Models Used

The repository contains Jupyter notebooks for the following models:
* **LSTM (`Quant_blog_LSTM.ipynb`)**: A popular recurrent neural network for time-series data.
* **Variational Autoencoder (`D_Va_Model_in_Tensorflow (1).ipynb`)**: A generative model used here for feature extraction or forecasting.
* **Diffusion Model (`Quant_blog_Diffusion_model.ipynb`)**: A state-of-the-art generative model adapted for forecasting tasks.

##  Installation

To run these notebooks, you'll need to set up your Python environment and install the required libraries.

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd <your-repository-name>
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

Once the installation is complete, you can start Jupyter Lab or Jupyter Notebook:

```bash
jupyter lab