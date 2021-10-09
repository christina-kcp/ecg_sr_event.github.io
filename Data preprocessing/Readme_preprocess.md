The notebook here shows how the data-preprocessing has been carried out from the CPSC2018 dataset.
This dataset can be downloaded from the URL: http://2018.icbeb.org/Challenge.html .
In the woring directory of the project, this downloaded set can be stored. Here, as I have done the complete
work in Google Colaboratory GPU, I have stored the downloaded datasets in my Google Drive. Each patient record has
three Cardiac Arrhythmia labels, here only first label is considered for the whole system.
The CPSC-2018 Dataset originally consists 12-lead data of 6877 patients. So, in all total 
6877x12 = 82524 ECG tracings are present in the ground-truth dataset. Now, this dataset is imbalanced in the proportion 
of the cardiac arrhythmias labels and eventually channels(or leads) too. So, there is a requirement to create a balanced dataset 
from this ground-truth dataset.
Hence, the final leadwise and event-wise balanced dataset comprises of 21816 ECG tracings in total. 
