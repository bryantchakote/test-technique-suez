# Technical Test Data Science Suez

## 💪 Introduction 

You are in charge of an image classification task. This task closely mirrors some of the computer vision activities we conduct at Suez. 

You'll present your results in a `jupyter-notebook`  using `Python` with the libraries of your choice. We recommend using `numpy`, `pandas`, `matplotlib`, `scikit-learn`, and `PyTorch`. 

Feel free to develop the aspects you find most relevant. 

The goal here is not necessarily to achieve the best performance, but to demonstrate your ability to apply Data Science strategies to address real-world business problems. We place great importance on the methodology you implement and the clarity of your deliverable. Please also provide instructions on how to reproduce your results.

We are at your complete disposal should you have any questions. 

## 📝 Task Description

You need to classify, from an image, whether a trash garbage is clean or dirty, meaning whether it is properly filled or overflowing with trash on the ground.

<p align="center">
  <img src="train\with_label\clean\0e02598e-acbb-423e-912e-cf2b922b5bd7.jpeg" alt="A clean garbage." width="300"/>
  <br>
  <em>A clean garbage.</em>
</p>


<p align="center">
  <img src="train\with_label\dirty\59b578137fcbe.jpeg" alt="A dirty garbage." width="300"/>
  <br>
  <em>A dirty garbage.</em>
</p>


You will measure performance on a test set (`test/` folder).

You will train your algorithm using the images in the train set (`train/` folder).

## 📊 Data Description 

You have access to both training and testing datasets.

### Train 
- 20 images of clean garbages and 20 images of dirty garbages, respectively in `train/with_label/clean` and `train/with_label/dirty`
- An additional set of unlabeled images of garbages (clean or dirty) in `train/no_label`,  that you can use as you see fit.

### Test 
- Approximately 100 images of clean and dirty garbages are available (`test/`). These are unlabeled.

## 💥 Where to start?

To familiarize yourself with the data and the task, we suggest exploring the labeled data in train (`train/with_label/clean` and `train/with_label/dirty`), and then labeling the test set by moving the images from `test/` to the folders `test/clean` and `test/dirty`. 

---

I look forward to seeing your approach and results! If you have any questions or need assistance, feel free to reach out. Happy coding! 🚀