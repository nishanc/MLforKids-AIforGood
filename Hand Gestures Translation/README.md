# Hand Gestures Translation

### First tryout the [Sign Language Recognition - TensorFlow For Poets Notebook](https://colab.research.google.com/drive/1fOwbi0iOb-7CtCcVcnsyJR5kPvLP86Q5?usp=sharing)

### Then try the below example with Teachable Machine

----
#### Teachable Machine - read the related blog post from here - [medium.com/@nishancw/image-classification-with-teachable-machine-ml5-js-and-p5-js](https://medium.com/@nishancw/image-classification-with-teachable-machine-ml5-js-and-p5-js-233fbdf48fe7)


* Install node.js LTS from [nodejs.org](https://nodejs.org/en/)
* Create your **image classification** model using [teachablemachine](https://teachablemachine.withgoogle.com), download it to your PC. Then put `metadata.json`, `model.json` and `weights.bin` into `public/model` folder.
* Open command prompt (`cmd`) inside `Hand Gestures Translation` folder.
* Execute command `npm install` to install dependancies.
* Execute command `node server.js` to start local web server.
* Then navigate to [http://localhost:3000](http://localhost:3000/)