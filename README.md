# Pneumonia-Severity-Infection
Detecting severity infection of pneumonia types with other factor to determine final decision for real diagnoses 
##########################################
## Abstract
In March 2020, theWorld Health Organization (WHO) declared the SARS-CoV-2 virus
(Covid-19) a global pandemic. Since the emergence of this pandemic, many scientific
methods and research have contributed to speeding up and automating the process
of diagnosing patients who are carriers of the virus. In particular, many research
efforts rely on analyzing and diagnosing the virus by employing artificial intelligence
technology in radiological chest images using either X-rays or CT scans. Medical and
health regulations over CT recommended X-rays as the first line of diagnosis for many
reasons, including the safety of spreading the virus, less cost, and faster results. Thus,
extensive research efforts used deep learning methods to detect Covid-19 and types of
pneumonia. Despite these efforts yielding high-performance results, their diagnosis
has several concerns and limitations regarding the reliability, robustness, and quality
of the trained model. Radiology images are not adequate in the early stage of infection.
Also, Several research efforts used overlapped images of common diseases, improper
images, and a combination of inconsistent image sources. Moreover, most studies
ignored the severity of infection but concentrated on classifying the types of pneumonia.
In this regard, the contribution of the current study is threefold. First, introducing
a cleaned and consistent dataset with the help of radiologists who re-annotated an
existing public dataset. Second, it presents a hybrid framework based on merging a
convolutional neural network (CNN) with a fuzzy system. The CNN-based model
consists of two stacked layers of CNN-based models used to differentiate normal
versus types of pneumonia. Third, the fuzzy system receives numerical laboratory

tests and the classification results of the CNN model to decide the degree of severity.
Experimental results on the proposed cleaned dataset using different CNN models
demonstrate that the VGG16 model achieved 92% and 84% specificity and accuracy,
respectively, in classifying viral and bacterial pneumonia. Moreover, the fuzzy part
is evaluated using twelve real medical case cases. The experimental results show
that the suggested fuzzy inference engine accurately identifies the patients with the
recommended severity and allows decision-makers specialists to quantify the severity
of viral pneumonia using scores.


![Final_Model_](https://github.com/gsamueil/Pneumonia-Severity-Infection/assets/31563545/d4b75e03-cacd-4815-9141-c1803b0e4b6c)

