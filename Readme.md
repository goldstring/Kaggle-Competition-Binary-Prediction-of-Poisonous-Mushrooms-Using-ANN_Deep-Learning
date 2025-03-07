<h1>🍄Kaggle Competition:- Mushroom Classification (Score : 0.93423)</h1>
    <p>A binary classification model was developed to predict whether a mushroom is <strong>poisonous</strong> or <strong>edible</strong> based on categorical features.</p>
    <h2>📌 Project Overview</h2>
    <ul>
        <li>Used the <strong>UCI Mushroom Dataset</strong> (modified via deep learning-generated dataset from Kaggle Playground Series - Season 4, Episode 8).</li>
        <li>Implemented an <strong>Artificial Neural Network (ANN)</strong> achieving:</li>
        <ul>
            <li>Training Accuracy: <strong>94%</strong></li>
            <li>Test Accuracy: <strong>96%</strong></li>
            <li>Competition Score: <strong>0.93419</strong></li>
        </ul>
    </ul>
    <h2>📂 Dataset Description</h2>
    <p>The dataset consists of categorical features representing mushroom characteristics (e.g., cap color, odor, and gill size). The target labels:</p>
    <ul>
        <li><code>e</code>: Edible</li>
        <li><code>p</code>: Poisonous</li>
    </ul>
    <h3>📁 Files Used:</h3>
    <ul>
        <li><code>train.csv</code>: Training data with labels.</li>
        <li><code>test.csv</code>: Test data for predictions.</li>
        <li><code>sample_submission.csv</code>: Sample submission format.</li>
    </ul>
    <h2>🚀 Implementation Steps</h2>
    <h3>1️⃣ Data Preprocessing</h3>
    <ul>
        <li>Applied <strong>One-Hot Encoding</strong> to categorical variables.</li>
        <li>Handled anomalies and unseen categorical values in test data.</li>
        <li>Standardized feature distributions where necessary.</li>
    </ul>
    <h3>2️⃣ Model Architecture</h3>
    <ul>
        <li><strong>Input Layer:</strong> Matching the number of encoded features.</li>
        <li><strong>Hidden Layers:</strong> Two layers with ReLU activation.</li>
        <li><strong>Output Layer:</strong> A single neuron with Sigmoid activation.</li>
    </ul>
    <h3>3️⃣ Training & Validation</h3>
    <ul>
        <li>Used <strong>Binary Cross-Entropy</strong> as the loss function.</li>
        <li>Optimized using the <strong>Adam Optimizer</strong>.</li>
        <li>Implemented <strong>Early Stopping</strong> to prevent overfitting.</li>
    </ul>
    <h3>4️⃣ Model Evaluation</h3>
    <ul>
        <li>Training Accuracy: <strong>94%</strong></li>
        <li>Test Accuracy: <strong>96%</strong></li>
        <li>Metrics: Accuracy, Precision, Recall.</li>
    </ul>
    <h3>5️⃣ Deployment</h3>
    <ul>
        <li>Generated predictions on <code>test.csv</code>.</li>
        <li>Formatted submission as per <code>sample_submission.csv</code>.</li>
    </ul>
    <h2>🛠 Technologies Used</h2>
    <ul>
        <li>Python</li>
        <li>TensorFlow/Keras</li>
        <li>Pandas & NumPy</li>
        <li>Scikit-Learn</li>
        <li>Matplotlib/Seaborn (for visualization)</li>
    </ul>
    <h2>📌 Key Takeaways</h2>
    <ul>
        <li>Successfully applied an ANN to a categorical dataset.</li>
        <li>Handled anomalies in categorical data.</li>
        <li>Compared model performance with the original UCI dataset.</li>
        <li>Achieved strong generalization with a <strong>96% accuracy</strong> on unseen data.</li>
    </ul>
