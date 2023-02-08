# Model Selection
In exploring models for this prediction. I'm using helpful exploratory tool that called **Lazypredict**. This tool helps with baseline and sanity check.

Basicly this tool helped you Run 30 Machine learning algorithms with 1 line of code :rocket:. it automates all the fit and predict process.

Let's try this library :point_down: 
- first step, install lazypredict `!pip install lazypredict`

- Next step, just see this Screenshoot below!!:point_down:
    - ![lp tut](https://user-images.githubusercontent.com/112558588/212098275-af3acba8-1462-42e6-8047-bc5ac6467e3d.png)


### CAUTION 
- **It's NOT meant for product choice. It is meant for exploration of all models**

## This is also my first time trying this tool. Despite the controversies surrounding it, I believe this tool can be very helpful if used in the right way.  

If you're curious about the model I picked and the steps I took to make a <b>Breast cancer prediction model</b>, check out my <b>[Colab notebook](https://github.com/Nataalfa/Model-For-Breast-Cancer-Prediction/blob/main/Breast_cancer_prediction_model.ipynb)</b>. I go into detail on everything I did. For this project i choose scoring with recall on predicted the **Cancer** because on medical test recall is more important.
Because **It is okay to classify** a healthy person as having cancer and following up with more medical tests, 
**but** it is **definitely not okay** to **miss identifying** a cancer patient or classifying a cancer patient as healthy **since the person’s life is at stake**.
If you want to read more details about when to use Recall or Precision 
Check out this <b>[Article](https://medium.com/analytics-vidhya/precision-recall-tradeoff-for-real-world-use-cases-c6de4fabbcd0)</b> written by **Lavanya Gupta**

### And This is the Visualization of The Confusion matrix :point_down:
![Screenshot 2023-02-08 115407](https://user-images.githubusercontent.com/112558588/217437358-3f7a3fd2-7f4d-4be5-ac9d-95a42814b7d2.png)

**Thanks!:grimacing:**
