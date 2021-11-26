# Analysis-of-Hybrid-Approach-For-Voiceprint-Biometric-Template-protection

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

With the recent advancements in speech recognition or in general, biometric systems; their security becomes crucial. 
Before the content of this research paper can be accessed, we need to understand the need for template protection and existing methods for template protection.
There have been a number of template protection techniques, but there is always a trade of between security and performance.  
This research paper presents a hybrid approach that utilizes the benefits of both Template transformation and Biometric Cryptosystem.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

The MFCC.ipynb file : 
is the feature extraction process of the system. To convert audio to MFCC(Mel Frequency Cepstral Coefficients)
What is MFCC used for?
Image result for mfcc full form
The MFCC gives a discrete cosine transform (DCT) of a real logarithm of the short-term energy displayed on the Mel frequency scale.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

The final.ipynb file : 
manifests how the process is being done while using only 2 audios for testing. One for Enrollment Process and the other for Verification process.
This can later be extrapolated for datasets containing multiple audio queues.
The functions calculate the MFCC's for both the audios and project both of them to a same random matrix(as given in the paper)
Finally Linde-buzo gray a;gorithm was used to design codebook of desired size and the average distortion between the voices was calculated.
Still, the algorithm not complete and the binary indexing for the key is not implemented.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Anyone is open to use the code and make his/her improvements. Also, if you improve it inform me I would like to know you did that. Thanks!!!!
(Please mail me at itsub18@gmail.com for further queries or doubts or for explanation)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

Have a great day Fellas!! Peace >.<
