# synthea_medical_dataset
Repository to directly download csv files from the Synthea Medical Dataset https://synthea.mitre.org/downloads

```python
import pandas as pd

# Load in Synthea synthetic FHIR datasets
all_prevalences_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/all_prevalences.csv")
allergies_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/allergies.csv")
careplans_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/careplans.csv")
claims_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/claims.csv")
conditions_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/conditions.csv")
encounters_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/encounters.csv")
immunizations_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/immunizations.csv")
medications_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/medications.csv")
observations_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/observations.csv")
patients_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/patients.csv")
procedures_df = pd.read_csv("https://zclarke.dev/synthea_medical_dataset/procedures.csv")

# Now you have all the dataframes defined

# Example usage:
print(all_prevalences_df.head())

```
