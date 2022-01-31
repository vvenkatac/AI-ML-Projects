<h1> Ensemble Techniques - Parkinsons Disesase Screening </h1>
<h2> OVERVIEW/CONTEXT: </h2>
Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.
<br> <br>
Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician

<h2> ABOUT THE DATA: </h2>
<h4>SOURCE: </h4>
The dataset was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, who recorded the speech signals. The original study published the feature extraction methods for general voice disorders.
<h4> DATASET INFORMATION: </h4>
This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD.
<br> <br>
The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording. There are around six recordings per patient, the name of the patient is identified in the first column.For further information or to pass on comments, please contact Max Little (littlem '@' robots.ox.ac.uk).
<h4> ATTRIBUTE INFORMATION: </h4>
<ol> <li>name Subject Name and recordign number </li>
 <li>MDVP:F0 (Hz) Average vocal fundamental frequency  </li>
 <li>MDVP:Fhi (Hz) Maximum vocal fundamental frequency  </li>
<li>MDVP:Flo (Hz) Minimum vocal fundamental frequency </li>
<li>MDVP:Jitter(%) MDVP jitter in percentage </li>
<li>MDVP:Jitter(Abs) MDVP absolute jitter in ms </li>
<li>MDVP:RAP MDVP relative amplitude perturbation </li>
<li>MDVP:PPQ MDVP five-point period perturbation quotient </li>
<li>Jitter:DDP Average absolute difference of differences between jitter cycles </li>
<li>MDVP:Shimmer MDVP local shimmer </li>
<li>MDVP:Shimmer(dB) MDVP local shimmer in dB </li>
<li>Shimmer:APQ3 Three-point amplitude perturbation quotient </li>
<li>Shimmer:APQ5 Five-point amplitude perturbation quotient </li>
<li>MDVP:APQ11 MDVP 11-point amplitude perturbation quotient </li>
<li>Shimmer:DDA Average absolute differences between the amplitudes of consecutive periods </li>
<li>NHR Noise-to-harmonics ratio </li> 
<li>HNR Harmonics-to-noise ratio </li>
<li>RPDE Recurrence period density entropy measure </li>
<li>D2 Correlation dimension </li>
<li>DFA Signal fractal scaling exponent of detrended fluctuation analysis </li>
<li>Spread1 Two nonlinear measures of fundamental </li>
<li>Spread2 Frequency variation </li>
<li>PPE Pitch period entropy </li> </ol>

<h2> OBJECTIVE </h2>
Goal is to classify the patients into the respective labels using the attributes from their voice recordings to help and identify Parkinson's affected from Healthy people.
Load and Visualize the data
<ol> <li> Conduct an Exploratory Data Analysis </li>
<li> Preparing the data to train a model </li>
<li> Training/Predicting using classification models and observing accuracy </li>
<li> Train a Metaclassifier and observe accuracy on data </li>
<li> Train one Ensemble model and note accuracy </li>
<li> Compare all models and pick the best </li> </ol>
