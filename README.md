# Transfer-Learning-with-MobileNetV2-for-Cats-vs-Dogs-Image-Classification
This project is an image classification project based on a transfer learning approach using with MobileNetV2 architecture.

This project is an improvement on a [previous project](https://github.com/mohamedamine99/Keras-CNN-cats-vs-dogs-image-classification) in which we built and trained a custom deep CNN from the ground up.

Finally, this project demonstrates the power of transfer learning; in fact, we achieved a model **accuracy of 97%** using only **50% of the train dataset**, whereas the previous project only achieved **92% accuracy** using all available data.

The main approach during this project was to use gradual transfer learning where for each training of the 3 phases we defined, we fine-tuned the model by incrementally unfreezing a certain number of layers and decreasing the learning rate (I've used the Adam optimizer).

You can find a link provided by microsoft to the dataset used in ths project [here](https://www.microsoft.com/en-us/download/details.aspx?id=54765) .

You can find the model weights and history logs [here](https://github.com/mohamedamine99/Transfer-Learning-with-MobileNetV2-for-Cats-vs-Dogs-Image-Classification/tree/main/model%20weights)

### Confusion matrix

<div align="center">  
<table style="margin: 0 auto; border-style: none; width:100%">
  <tr>
    <td><img src="https://github.com/mohamedamine99/Transfer-Learning-with-MobileNetV2-for-Cats-vs-Dogs-Image-Classification/blob/main/model%20weights/confusion%20matrix%202.PNG"></td>
  </tr>
</table>
</div>
 
