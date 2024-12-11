
<div style="text-align:center;">
  <h1>Binary Prediction of Poisonous Mushrooms Playground Series - Season 4, Episode 8</h1>

</div>
<div class="row">
  <!-- Project Overview -->
  <div class="col-12 mb-4">
    <h3>Project Overview</h3>
    <p>
      In this project, a binary classification model was developed to predict whether a mushroom is poisonous or edible based on categorical features. The dataset used was derived from the UCI Mushroom Dataset, modified through a deep learning-generated dataset for the Kaggle Playground Series - Season 4, Episode 8. The model was implemented using an Artificial Neural Network (ANN) and achieved a training accuracy of 94% and a test accuracy of 96%.
    </p>
  </div>
  <!-- Dataset Description -->
  <div class="col-12 mb-4">
    <h3>Dataset Description</h3>
    <p>
      The dataset consists of several categorical features representing mushroom characteristics (such as cap color, odor, and gill size). The target class is binary:
    </p>
    <ul class="list-group">
      <li class="list-group-item"><strong>e:</strong> Edible</li>
      <li class="list-group-item"><strong>p:</strong> Poisonous</li>
    </ul>
  </div>

  <!-- Files Used -->
  <div class="col-12 mb-4">
    <h3>Files Used</h3>
    <ul class="list-group">
      <li class="list-group-item"><strong>train.csv:</strong> Training data with labels (edible or poisonous).</li>
      <li class="list-group-item"><strong>test.csv:</strong> Test data for making predictions.</li>
      <li class="list-group-item"><strong>sample_submission.csv:</strong> Sample submission format for predictions.</li>
    </ul>
  </div>
  <!-- Project Implementation Steps -->
  <div class="col-12 mb-4">
    <h3>Project Implementation Steps</h3>
    <h5>Data Preprocessing:</h5>
    <ul class="list-group mb-3">
      <li class="list-group-item">Handled categorical variables using one-hot encoding.</li>
      <li class="list-group-item">Identified and dealt with any anomalies or unseen categorical values in the test data.</li>
      <li class="list-group-item">Standardized feature distributions where necessary.</li>
    </ul>
    <h5>Model Architecture:</h5>
    <ul class="list-group mb-3">
      <li class="list-group-item"><strong>Input Layer:</strong> Matching the number of encoded features.</li>
      <li class="list-group-item"><strong>Hidden Layers:</strong> Two hidden layers with ReLU activation functions.</li>
      <li class="list-group-item"><strong>Output Layer:</strong> A single neuron with a sigmoid activation for binary classification.</li>
    </ul>
    <h5>Training and Validation:</h5>
    <ul class="list-group mb-3">
      <li class="list-group-item">Used the binary cross-entropy loss function.</li>
      <li class="list-group-item">Optimized the model using the Adam optimizer.</li>
      <li class="list-group-item">Implemented early stopping to prevent overfitting.</li>
    </ul>
    <h5>Evaluation:</h5>
    <ul class="list-group mb-3">
      <li class="list-group-item">Achieved 94% training accuracy and 96% test accuracy.</li>
      <li class="list-group-item">Assessed model performance using metrics like accuracy, precision, and recall.</li>
    </ul>
    <h5>Deployment:</h5>
    <ul class="list-group">
      <li class="list-group-item">Generated predictions on the test dataset and formatted them according to sample_submission.csv.</li>
    </ul>
  </div>
  <!-- Technologies Used -->
  <div class="col-12 mb-4">
    <h3>Technologies Used</h3>
    <ul class="list-group">
      <li class="list-group-item">Python</li>
      <li class="list-group-item">TensorFlow/Keras</li>
      <li class="list-group-item">Pandas & NumPy</li>
      <li class="list-group-item">Scikit-Learn</li>
      <li class="list-group-item">Matplotlib/Seaborn for visualization</li>
    </ul>
  </div>
  <!-- Key Takeaways -->
  <div class="col-12 mb-4">
    <h3>Key Takeaways</h3>
    <ul class="list-group">
      <li class="list-group-item">Successfully applied an ANN to a categorical dataset for binary classification.</li>
      <li class="list-group-item">Handled anomalies in categorical data and compared model performance with and without the original UCI dataset.</li>
      <li class="list-group-item">Demonstrated strong generalization with a 96% accuracy on unseen data.</li>
    </ul>
  </div>
</div>
