# Potato Leaf Disease Detection

This project involves detecting diseases in potato leaves using a machine learning model. The model is trained using a dataset, and the frontend is implemented in `app.py`, which can be deployed on Streamlit for easy access.

## Prerequisites

Before running the project, make sure you have the following installed:

- Python 3.6 or higher
- Streamlit
- TensorFlow
- Keras
- Other dependencies from `requirements.txt`

You can install the dependencies using the following:

```bash
pip install -r requirements.txt
Setup
1. Train the Model
To train the model, follow these steps:

Open the Jupyter notebook potato_leaf_disease_detection.ipynb.
Run the notebook to train the model.
The model will be saved as a .keras file after training.
Make sure the .keras file is uploaded to your Google Drive, or ensure the correct path is provided in the app.py.

2. Modify app.py
In the app.py, you need to modify the path to the .keras model file. Replace the current Google Drive link with your own file's path.

python
Copy
Edit
# Example of loading the model
model_path = "your_google_drive_link_to_model_file"
model = keras.models.load_model(model_path)
3. Deploy on Streamlit
After modifying the app.py, you can deploy it on Streamlit by following these steps:

Upload the app.py to GitHub.
Go to Streamlit's website and log in to your account.
Click "New App" and paste the GitHub URL of your app.py.
Streamlit will automatically deploy your app.
4. Running Locally
To run the app locally, simply run the following command in your terminal:

bash
Copy
Edit
streamlit run app.py
This will start a local Streamlit server, and you can access the app at http://localhost:8501.

Project Structure
potato_leaf_disease_detection.ipynb: Jupyter notebook used to train the model.
app.py: Streamlit frontend for disease detection.
requirements.txt: List of required Python packages.
Contributing
Feel free to fork this repository and make contributions. If you find any issues or have suggestions, open an issue in the repository.
