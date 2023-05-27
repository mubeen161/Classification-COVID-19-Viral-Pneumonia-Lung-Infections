# Classification COVID-19 Viral Pneumonia Lung Infections

Automated detection of COVID-19 in real time can greatly help clinicians to handle increasing number of cases for preliminary screening. Deep CNN models trained with sufficiently large datasets may become best candidates to meet the purpose.Automated detection and classification of COVID-19 and viral pneumonia diseases by applying deep CNN model using chest X-ray images. The proposed model performs multiclass classification to meet the purpose.The proposed model is built on top of VGG16 architecture with pretrained ImageNet weights. The model was fine-tuned using additional custom layers to deliver better performance specific to the target.

A total of 15,153 samples are used in this work. These samples include chest X-ray images of COVID-19, viral pneumonia, and normal cases. The entire dataset was split into train and test sets, with a ratio of 80:20 before training the model. To enhance important image features, image preprocessing and augmentation were applied before feeding the image batches to the model.

The proposed classification model may be highly useful for the preliminary diagnosis of COVID-19 and viral pneumonia cases, especially during heavy workloads and large quantities.
