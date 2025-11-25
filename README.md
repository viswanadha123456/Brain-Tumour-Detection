# Brain-Tumour-Detection
projects
**Deep Learning-Based Brain Tumor Classification Using MRI Images (ResNet & InceptionV3)**
This project presents an intelligent Brain Tumor Detection System using transfer learning with ResNet50 and InceptionV3, 
designed to accurately classify MRI images as tumor or non-tumor. Leveraging deep learning, the model achieves 90% accuracy,
making it suitable for real-world medical screening assistance.
A dataset of 8,000+ MRI images from Kaggle was preprocessed using techniques such as data augmentation, 
normalization, and class balancing, resulting in a 12% improvement in precision and recall. Transfer learning layers were fine-tuned to extract advanced spatial features crucial for tumor identification.
The trained model is deployed with Flask, enabling real-time MRI image classification through a simple web interface. This setup makes the solution scalable, user-friendly, 
and ready for integration into healthcare applications or diagnostic tools.

**Introduction**
The detection of brain tumors is a critical task in medical diagnosis, as it significantly impacts patient outcomes. However, 
the complexity of the brain's structure and the need for substantial image data make the detection process challenging. Additionally, 
the reluctance of healthcare institutions to share data further complicates model training. To address these challenges, 
this study proposes a novel approach to brain tumor detection using deep  learning integrated with the Raspberry Pi Pico. 
By leveraging the compact yet powerful Raspberry Pi Pico, we aim to develop an efficient and accessible solution for early detection of brain tumors. 
This approach combines the benefits CNN algorithm of VGG16 model with the portability and affordability of the Raspberry Pi Pico, 
making it suitable for real-time applications and remote healthcare settings. The model's performance, privacy preservation, 
and potential for decentralized data utilization are emphasized, offering a promising direction for enhancing 
brain tumor detection capabilities while ensuring data security and collaboration across healthcare institutions
**Types Of tumour**
** Glioma Glioma is a tumor that starts in the brain or spinal cord, formed  by cells resembling healthy glial cells, and can cause symptoms  based on the affected area. 
**Meningioma** is a slow-growing tumor from the meninges that surrounds the brain and spinal cord, often pressing on nearby tissues, 
 causing symptoms and potential disability.
** Pituitary tumors** are benign growths in the pituitary gland that can affecthormone production, typically growing slowly without spreading to other parts of the body.

**Conclusion**
 This project highlights the effectiveness of deep learning in classifying brain tumors from MRI scans. Among the models evaluated— VGG16,ResNet-50,  and DenseNet excelled in processing time and accuracy, making it the optimal choice for efficient tumor classification. While VGG16 achieved 95% accuracy and the other models higher computational time limits their practical use in real-time diagnostics. Thus, VGG16 offers a balanced solution, ensuring fast and reliable tumor detection for timely medical decision-making and intergraion with raspberry pi pico microcroller.

**References**

https://www.sciencedirect.com/science/article/pii/S2665917422000745

https://journals.scholarpublishing.org/index.php/JBEMi/article/view/1732

https://www.sciencedirect.com/science/article/pii/S001048251630155X

https://pmc.ncbi.nlm.nih.gov/articles/PMC6807560/

https://pubmed.ncbi.nlm.nih.gov/32289646/

https://www.sciencedirect.com/science/article/pii/S0208521620300784

https://pmc.ncbi.nlm.nih.gov/articles/PMC9854739/

https://www.researchgate.net/publication/361410747_Brain_tumour_classification_a_comprehensive_systematic_review_on_various_constraints





