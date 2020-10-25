# lungCTClassifier
Kenneth Zhang - Policython CNN CT Scan Classifier



# Use of Artificial Intelligence as an Alternative to COVID-19 Screening

# Kenneth Zhang 
Ancaster High School (International Baccalaureate), kzhang138@gmail.com

# Jonathan He
Princess Anne High School (International Baccalaureate), jonathanhe12345678@gmail.com

# Faisal Al-Qahtani
Al Forsan International School, Riyadh, faisalalqahtanicollege@gmail.com




# Executive Summary 
This policy proposal centers around how healthcare and general testing centers can utilize contemporary Machine Learning (ML) methods to elevate the efficiency and effectiveness at which we screen the general public for COVID-19. As the early detection and diagnosis of patients for COVID-19 is crucially important for the prevention of further spread of infection, it is becoming increasingly more necessary to implement an expert system, such as an ML expert system, to be able to detect infected patients at a rapid rate, whilst maintaining exceptional diagnostic accuracies

#  Abstract
Fast diagnosis and screening need to be able to aid the prevention of the spread of pandemic disease, such as SARS-CoV-2, whilst being cost-effective and able to rapidly produce consistently accurate diagnoses. The development of an ML expert system can be used to augment the diagnosis and screening process of an identified patient alongside radio-imaging technology, such as Computed Tomography (CT). Traditional methods of using radiology images require a healthcare expert to analyze a CT scan and diagnose a patient based on those analyses. Unfortunately, such methods do not provide sufficient performance during the high outburst of the SARS-CoV-2 pandemic. Studies have shown that modern ML tools have the capability of producing much faster and valid methods of SARS-CoV-2 diagnosis using architectures such as Deep Convolutional Networks. Since familiarity with the usage of ML in screening and diagnosis of patients is still quite low, the proposal intends to provide a holistic approach for medical professionals and the general public to how the utilization of machine learning methods may overcome present-day screening issues. This policy proposal aims to comprehensively evaluate the validity of AI and ML as a necessary method of screening and diagnosis for the SARS-CoV-2 pandemic, whilst providing an experimental overview of an implementation of the expert system using valid methods of data gathering and evaluation. 






# Introduction
Traditional methods for the diagnosis and screening of COVID-19 alongside CT scans, as suggested in our abstract, are unable to produce rapid amounts of accurate diagnoses required for the current SARS-CoV-2 outbreak. Other methods, such as Coronavirus testing kits require specified durations of time in order for accurate results to return. Such individualized screenings require extensive amounts of time and risk the chance of human error. In order to efficiently and sufficiently handle the outburst of the novel Coronavirus, the development of an expert system for patient diagnoses is necessary. Evidence has shown that the training of Machine Learning models is able to achieve such accuracies in shorter periods of time. Through the development of expert systems powered by machine learning and artificial intelligence, these crucial problems may be eliminated, allowing for a much more cost-effective, rapid, and more accurate method of COVID-19 screening that can be deployed around the world.

# Details & Analysis
Two proposals to solutions for accurate and rapid diagnoses for COVID-19 have been proposed with the first being Coronavirus Testing Kits (swab kits). Coronavirus testing stops using these Coronavirus Testing Kits are conveniently located at highway exits, shopping centers, state borders, etc. Despite the convenience of Coronavirus testing kits, they are scarce during the outburst of COVID-19 and require specific conditions in order to be accurate. 
According to the Harvard Health Publishing of Harvard Medical School, 
	"Antibody tests can tell if someone has been infected with COVID-19. But the infected person doesn't begin producing antibodies immediately. It can take as long as three weeks for a blood antibody test to turn positive. That's why it is not useful as a diagnostic test for someone with new symptoms." - Harvard Health Publishing (Harvard Medical School), October 16, 2020.
An alternative solution proposal to the inaccuracy of testing kits are Computer Tomography (CT) scans. In a recent study conducted on 1014 patients, scientists in China reported that chest CT scans detected 97% of COVID-19 infections, whereas 48% of patients who had negative results on the swab test in fact had the disease, According to Sharon Begley at statnews.com. 



In addition, a study tested CT scans on a set and subset of patients, with chest CT scans performed 48 hours after the symptom's onset. CT scans, in the study, achieved 90.2% in all patients and 94% in the subset of patients conducted upon. The paper states, 
	"This interesting study reported an accuracy of 90.2% in all patients and 94% in the subset of patients with chest CT performed 48 hours after the symptom’s onset. "
			- Hooman Bahrami-Motlagh et al, May 27, 2020 
Therefore, we need an expert system to be able to complete all such steps with high-accuracy and efficiency. Evidence has shown that the architectures and methodologies for training machine learning models to such an extent are possible. A more rational approach trained and developed a Deep Neural Network-based on a DarkNet neural network. The resulting Deep Neural Network, the "DarkCovidNet" [3], was based on the previously proven DarkNet Deep Neural Network, developed for image classification, object detection, etc. The resulting "DarkCovidNet" achieved an accuracy of 98.08% for binary classes and an accuracy of 87.02% for multi-class cases. Our trained Convolutional Neural Network (CNN) achieved an accuracy of 99.11% for multi-classification cases and a 100% accuracy for binary classes. The training set consisted of 19685 CT scans of patient lungs, while the validation contained 5905 CT scans. Figure 1 shows the evaluation accuracies for the CNN we trained. 

Figure 1. Kenneth Zhang et al, CNN for COVID-19 Screening





# Implementation of Our Proposal

Stage 1 - Preliminary Requirement Analysis (PRA): Determining which hospitals and medical centers are in need of a more efficient, effective, and accurate method of patient screening, while also receiving feedback in regards to the concept of our proposal.

Stage 2 - Adjustments and Component Analysis (ACA): Take feedback and considerations into account, and adjust the original concept according to the feedback received.

Stage 3 - Data Gathering and Necessary PreProcessing (DG and NP): Gather reliable data and other necessary files, such as preliminary statistical data of patients, to understand the demographics and statistics of the dataset of images. Preprocessing of the images, such as image resizing and image normalization, as well as splitting training, validation, and test sets are also to be done in this stage. 

*Note - Data must NOT contain private/classified patient data as maintaining patient confidentiality and privacy is of top priority. 


Stage 4 - Identification and Proofs (IPs): Identity up to 10 potential machine learning architectures capable of doing multi-classification, real-time object detection, and binary classification on larger datasets. This will allow for a more rational approach to developing and constructing a reliable and proven machine learning expert system. (i.e. UNet Architecture, VGG-16 Architecture, Resnet-101, DarkNet, etc.). Then, derive mathematical proofs to show the selected architecture is ideal for our scenario and will fulfil such conditions. 

Stage 5 - Training and Transforming the Selected ML Architecture into the Expert System: Using the gathered data, train the selected ML architecture. Continuously train the architecture over a series of days, using a plethora of methods, such as distributed learning, to determine which method of training provides the best accuracy. In addition, consider how the duration of time the model takes to make predictions on new scans.

#Conclusion
In conclusion, it can be deduced that the implementation and deployment of a machine learning expert system have the potential to be a valid alternative/replacement for the current methods of screening. The rapid rate at which such expert systems can produce diagnoses, the accuracy at which they produce the diagnoses at, as well as the increased convenience of simply scanning and receiving an assessment instantaneously, displays machine learning expert systems as a competitive candidate for more efficient screening methods.








# References

1. Daily Testing Trends in the US - Johns Hopkins. (n.d.). Retrieved October 24, 2020, from https://coronavirus.jhu.edu/testing/individual-states
2. Lalmanawama, S., Hussain, J., & Chhakchhuak, L. (2020, June 25). Applications of machine learning and artificial intelligence for Covid-19 (SARS-CoV-2) pandemic: A review. Retrieved October 23, 2020, from https://pubmed.ncbi.nlm.nih.gov/32834612/
3. Ozturk, T., Talo, M., Yildirim, E., Baloglu, U., Yildirim, O., & Rajendra Acharya, U. (2020, June). Automated detection of COVID-19 cases using deep neural networks with X-ray images. Retrieved October 24, 2020, from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7187882/
4. Publishing, H. (n.d.). If you've been exposed to the coronavirus. Retrieved October 25, 2020, from https://www.health.harvard.edu/diseases-and-conditions/if-youve-been-exposed-to-the-coronavirus
5. Soltan, A., Kouchaki, S., Zhu, T., Kiyasseh, D., Taylor, T., Hussain, Z., . . . Clifton, D. (2020, January 01). Artificial intelligence driven assessment of routinely collected healthcare data is an effective screening test for COVID-19 in patients presenting to hospital. Retrieved October 25, 2020, from https://www.medrxiv.org/content/10.1101/2020.07.07.20148361v1
6. Sun, L., Song, F., Shi, N., Liu, F., Li, S., Li, P., Zhang, W., Jiang, X., Zhang, Y., Sun, L., Chen, X., & Shi, Y. (2020). Combination of four clinical indicators predicts the severe/critical symptom of patients infected COVID-19. Journal of clinical virology : the official publication of the Pan American Society for Clinical Virology, 128, 104431. https://doi.org/10.1016/j.jcv.2020.104431

