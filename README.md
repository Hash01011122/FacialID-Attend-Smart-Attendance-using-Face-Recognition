## Introduction: 
The human face holds significant importance in our social interactions as it serves as a primary means of conveying identity. The adoption of biometric face recognition technology has garnered considerable attention in recent years owing to its versatility across various applications, encompassing both law enforcement and non-law enforcement domains. In comparison to biometric systems utilizing fingerprints, palm prints, or iris recognition, face recognition stands out due to its non-intrusive nature. This method allows the capture of facial images from a distance without physical contact with the individual being identified, eliminating the need for direct interaction. Additionally, face recognition contributes to crime deterrence by enabling the retrieval and utilization of archived facial images for future identification purposes.

## Recognition Process: 
The Face Recognition Process consists of three distinct phases: Data Creation, Training Recognizer, and Detection.

## Data Creation Phase (2.1): 
In this initial phase, images are captured and stored within the Dataset Folder.

## Training Recognizer Phase (2.2): 
Subsequently, the dataset is utilized to train the LBPH Recognizer, a process that involves training the classifier.

## Detection Phase (2.3): 
In this concluding phase, the trained classifier analyzes new images and determines whether the image corresponds to known or unknown identities.

## Updating Attendance: 
Finally, the system updates attendance by cross-referencing the image names with their respective attendance records in an Excel sheet, comparing the current ID with the IDs recorded in the sheet.
