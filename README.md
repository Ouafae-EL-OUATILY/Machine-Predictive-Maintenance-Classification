# Machine-Predictive-Maintenance-Classification
I have cleaned the dataset, remove non meaningfull columns and remove null and duplicated rows, 
i have applied some visualizations to show the distribution of classes
i have preprocessed the given data, by balancing my dataset(generalization), this step because i observed that for example the target variable(i choose Failure Type) the value 'No Failure' exists more than other labels, and applying encoding for enabling the model to learn and make accurate predictions based on the provided inputs
i ve applied data augmentation by adding noise to numerical columns to perform the training of the model
model architecture:
the implementation of the neural network for multiclass classification includes label encoding, the definition of a simple feedforward neural network, a training loop running for 30 epochs, and evaluation on a test set to monitor training and assess the model's accuracy and loss over epochs
results after training:
In the 30-epoch training process, the model demonstrated significant improvement. The training loss steadily decreased, reaching 0.5084, indicating effective learning. On the test set, the loss decreased from 1.6677 to 0.5494, reflecting successful generalization, the accuracy on the test set increased
