# 3D Reconstruction Pipeline

This project provides a Python notebook to perform 3D reconstruction. Running the notebook launches a Gradio web interface where you can upload files and generate a 3D model output.

## How to Run

Follow these steps to set up and run the project:

### 1. Open in Google Colab
* Upload the provided Python notebook (`.ipynb`) to [Google Colab](https://google.com).
* Ensure your runtime is set to an **A100 GPU** for optimal processing:
  * Go to `Runtime` > `Change runtime type` > Select **A100 GPU** > Click `Save`.
  * *Note: Accessing the A100 GPU requires a Google Colab Pro/Pro+ subscription.*

### 2. Run the Notebook
* Execute all the cells in the notebook sequentially.
* The notebook will automatically install the required dependencies and build the model environment.

### 3. Launch the Gradio Demo
* After the final cells run successfully, a public or local **Gradio link** (e.g., `https://gradio.live`) will appear in the output.
* Click the link to open the web demo interface.

### 4. Generate the 3D Model
* Inside the Gradio interface, **manually upload** your required input images
* Click the submit/process button.
* Wait for the model to finish processing to view and download your **3D model output**.
