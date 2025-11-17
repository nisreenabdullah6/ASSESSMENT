## a. Solution description:

use Large Language Model (LLM) with a
custom dataset, enabling users to ask questions and receive answers sourced
directly from the dataset.
## b. Data description:

The metadata provided appears to be related to healthcare encounters or hospital records. It includes various fields that contain information about the encounter, patient, doctor, hospital, insurance provider, medical condition, admission details, billing, medication, test results, and length of stay. Here's a breakdown of each field:

encounter_id: A unique identifier for the healthcare encounter or hospital record.
patient_id: A unique identifier for the patient associated with the encounter.
name: The name of the patient.
Gender: The gender of the patient.
doctor_id: A unique identifier for the doctor or healthcare professional involved in the encounter.
doctor_name: The name of the doctor or healthcare professional.
hospital_id: A unique identifier for the hospital where the encounter took place.
hospital_name: The name of the hospital.
insurance_provider_id: A unique identifier for the insurance provider associated with the encounter.
insurance_provider_name: The name of the insurance provider.
MedicalCondition: The medical condition or diagnosis associated with the encounter.
admission_date: The date and time of admission for the encounter.
discharge_date: The date and time of discharge for the encounter.
billing_amount: The amount billed for the encounter, typically in a specific currency.
admission_type: The type of admission, such as emergency, elective, or urgent.
medication: Information about medications prescribed or administered during the encounter.
test_results: Results of medical tests conducted during the encounter.
Length_of_Stay: The length of stay in the hospital for the encounter, typically measured in days.
These metadata fields provide important information about a healthcare encounter, allowing for record keeping, analysis, and tracking of patients, doctors, hospitals, insurance providers, medical conditions, and associated details.

from https://www.kaggle.com/datasets/mohammedalsubaie/medical-claims

## c. How to install required libraries and run this project:

pip install pandas
pip install numpy
pip install openai
pip install faiss
pip install SentenceTransformer
