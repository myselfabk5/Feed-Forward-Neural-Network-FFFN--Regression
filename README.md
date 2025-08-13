# Feed-Forward-Neural-Network-FFNN (Regression)

**Data Loading & Preprocessing** – Reads housing price data, selects relevant numeric features, checks for missing values, and standardizes them using z-score normalization.

**Train–Test Split & Tensor Conversion** – Splits the dataset into training (80%) and testing (20%) sets, then converts them into PyTorch tensors and loads them into a DataLoader for batching.

**Neural Network Definition** – Implements a feed-forward regression model (FFNNRegression) with one hidden layer (16 neurons, ReLU activation) and one output neuron.

**Model Training** – Trains the network for 20 epochs using the Adam optimizer and MSE loss, tracking and plotting the training loss over epochs.

**Model Evaluation** – Predicts on the test set, computes the R² score (~0.72).
