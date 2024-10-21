# Audio Dataset Processing with Google Cloud Storage

## Project Overview
This Jupyter Notebook is designed to help you work with the **Common Voice** audio dataset. The notebook demonstrates how to:
- Explore and list audio files from a locally downloaded dataset.
- Upload the audio files to a **Google Cloud Storage (GCS)** bucket.
- Play and verify audio files within the notebook.

## Dataset
The dataset used in this notebook is Mozilla’s **Common Voice** dataset, specifically the English version. The dataset includes thousands of voice samples and is used for various speech recognition projects.

You can download the dataset directly from Mozilla Common Voice: [Common Voice Datasets](https://commonvoice.mozilla.org/en/datasets)

## Requirements
To use this notebook, you need to have the following tools and libraries installed:

- Jupyter Notebook
- Google Cloud SDK (`google-cloud-storage` library)
- Python 3.x
- `requests` (for downloading files)
- `IPython.display` (for playing audio files)

You can install the necessary Python packages using the following commands:
```bash
pip install google-cloud-storage requests

## Google Cloud Storage Setup

## To upload the audio files to Google Cloud Storage (GCS), you need to:

	1.	Create a Google Cloud project and enable the Google Cloud Storage API.
	2.	Create a service account key and download it as a JSON file.
	3.	Set the GOOGLE_APPLICATION_CREDENTIALS environment variable to the path of your service account key.

## Example:
import os
os.environ['GOOGLE_APPLICATION_CREDENTIALS'] = '/path/to/your/service-account-key.json'

## Steps Covered in the Notebook

	1.	Loading and Inspecting the Dataset:
	•	Listing and exploring the audio files in the dataset.
	•	Playing audio files directly within the notebook.
	2.	Uploading Audio Files to Google Cloud Storage:
	•	Using google-cloud-storage to upload files from your local system to a GCS bucket.
	•	Organizing files in a folder structure within your GCS bucket.
	3.	Verifying Uploads:
	•	Verifying that the files have been uploaded to the correct GCS bucket by listing the files in the cloud.

## Usage

To use the notebook:

	1.	Clone or download this repository.
	2.	Open the Jupyter Notebook in your local environment.
	3.	Ensure you have the necessary libraries installed (see the Requirements section).
	4.	Run the notebook cells to explore the dataset and upload files to GCS.


### Explanation of Sections:
- **Project Overview**: A brief explanation of what the notebook does.
- **Dataset**: Describes the dataset being used and provides a link to download it.
- **Requirements**: Lists the Python packages and tools needed to run the notebook
For any issues or questions, please feel free to open an issue in the repository or contact me at your-email@example.com.
