# CIFAR-100-Classification
#### Developed a simple Artificial Neural Network and a Convolutional Neural Network for CIFAR 100 dataset. Confusion Matrix, Heatmap and Classification Report is used for performance evaluation with performance metrics for training used is Accuracy.
#### This dataset is just like the CIFAR-10, except it has 100 classes containing 600 images each. There are 500 training images and 100 testing images per class. The 100 classes in the CIFAR-100 are grouped into 20 superclasses. Each image comes with a "fine" label (the class to which it belongs) and a "coarse" label (the superclass to which it belongs).

#### Here is the list of classes in the CIFAR-100:

### Superclass	
- aquatic mammals	
- fish	
- flowers	
- food containers	
- fruit and vegetables	
- household electrical devices	
- household furniture	
- insects	
- large carnivores	
- large man-made outdoor things	
- large natural outdoor scenes	
- large omnivores and herbivores	
- medium-sized mammals	
- non-insect invertebrates	
- people	
- reptiles	
- small mammals	
- trees	
- vehicles 1	
- vehicles 2	

### Classes
- beaver, dolphin, otter, seal, whale
- aquarium fish, flatfish, ray, shark, trout
- orchids, poppies, roses, sunflowers, tulips
- bottles, bowls, cans, cups, plates
- apples, mushrooms, oranges, pears, sweet peppers
- clock, computer keyboard, lamp, telephone, television
- bed, chair, couch, table, wardrobe
- bee, beetle, butterfly, caterpillar, cockroach
- bear, leopard, lion, tiger, wolf
- bridge, castle, house, road, skyscraper
- cloud, forest, mountain, plain, sea
- camel, cattle, chimpanzee, elephant, kangaroo
- fox, porcupine, possum, raccoon, skunk
- crab, lobster, snail, spider, worm
- baby, boy, girl, man, woman
- crocodile, dinosaur, lizard, snake, turtle
- hamster, mouse, rabbit, shrew, squirrel
- maple, oak, palm, pine, willow
- bicycle, bus, motorcycle, pickup truck, train
- lawn-mower, rocket, streetcar, tank, tractor

## How to use model:

- Importing libraries: Import necessary libraries such as:-
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn
  * Tensorflow
  * Keras
  * Warnings
  * Models, datasets, layers
  
- Loading Data: Then load the data using the already present cifar100 dataset in tensorflow. Use the syntax => datasets.cifar100.load_data()

- Training the model: You can train the model using a Convolutional Neural Network. Add the required loss and activation functions, performance metrics along with the optimizers. One can also apply an regularization technique to further optimize the model, such as using Drop Regularization, etc.

- Testing model: Test the model using unseen data and calculate the testing accuracy.

- Validating model: Validate or evaluate you model using a Confusion Matrix or Heatmap and calculate the accuracy, precision, recall, F1-Score, etc, according to your necessity.

**Since the dataset is extremely large, using a triditional neural network would not be fulfilling the correct classification criteria, rathar, using a CNN with many layers can be considered more apt in such a case to get correct predictions.**

