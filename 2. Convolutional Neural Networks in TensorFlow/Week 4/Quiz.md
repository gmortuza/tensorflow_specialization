1. The diagram for traditional programming had Rules and Data In, but what came out?

    - [x] Answers
    - [ ] Binary
    - [ ] Machine Learning
    - [ ] Bugs

2. Why does the DNN for Fashion MNIST have 10 output neurons?

    - [ ] To make it train 10x faster
    - [ ] To make it classify 10x faster
    - [ ] Purely Arbitrary
    - [x] The dataset has 10 classes

3. What is a Convolution?

    - [ ] A technique to make images smaller
    - [ ] A technique to make images larger
    - [x] A technique to extract features from an image
    - [ ] A technique to remove unwanted images

4. Applying Convolutions on top of a DNN will have what impact on training?

    - [ ] It will be slower
    - [ ] It will be faster
    - [ ] There will be no impact
    - [x] It depends on many factors. It might make your training faster or slower, and a poorly designed Convolutional layer may even be less efficient than a plain DNN!

5. What method on an ImageGenerator is used to normalize the image?

    - [ ] normalize
    - [ ] flatten
    - [ ] rezize()
    - [x] rescale

6. When using Image Augmentation with the ImageDataGenerator, what happens to your raw image data on-disk.

    - [ ] A copy will be made, and the copies are augmented
    - [ ] A copy will be made, and the originals will be augmented
    - [x] Nothing
    - [ ] The images will be edited on disk, so be sure to have a backup

7. Can you use Image augmentation with Transfer Learning?

    - [ ] No - because the layers are frozen so they can't be augmented
    - [x] Yes. It's pre-trained layers that are frozen. So you can augment your images as you train the bottom layers of the DNN with them

8. When training for multiple classes what is the Class Mode for Image Augmentation?

    - [ ] class_mode='multiple'
    - [ ] class_mode='non_binary'
    - [x] class_mode='categorical'
    - [ ] class_mode='all'
