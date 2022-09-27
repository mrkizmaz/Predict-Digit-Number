> This repo, it is an artificial intelligence application that can predict numbers drawn on the screen interactively with Support Vector Machines from Machine Learning Algorithms.

* All about Support Vector Machine :point_right: [SVM][svm]
* For the datasets used in this project: [MNIST][mnist_sets]
* The application interface was designed with [PyQt5][pyqt].

APPLICATION STEPS
* [MNIST Extractor][mnist_extractor]: After the related data sets were downloaded, resized (28x28) as they are not in any standard image format. Then this files extracted and saved as `pickle` format.
* [MNIST Trainer][mnist_trainer]: Datasets in pickle format were fitted with `sklearn` in this file and the classification report was tested. Then the model is saved in pickle format for use in the interface.
* [Interface][design]: In this file, the application interface was designed with `PyQt5` by integrating the model saved.

<h3 align="center">Releated Pictures</h3>
<p align="center">
<img src="https://github.com/mrkizmaz/Predict-Digit-Number/blob/master/images/pdn_1.png" width="100" height="100"> 





[svm]: https://scikit-learn.org/stable/modules/svm.html
[mnist_sets]: http://yann.lecun.com/exdb/mnist/
[pyqt]: https://zetcode.com/gui/pyqt5/
[mnist_extractor]: https://github.com/mrkizmaz/Predict-Digit-Number/blob/master/mnist_extractor.py
[mnist_trainer]: https://github.com/mrkizmaz/Predict-Digit-Number/blob/master/mnist_trainer.py
[design]: https://github.com/mrkizmaz/Predict-Digit-Number/blob/master/interface.py

