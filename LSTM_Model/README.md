# LSTM: 
## Model : 
- model = Sequential([
    LSTM(70, activation='relu', input_shape=(seq_length, 1)),
    Dense(256,activation='relu'),
    Dropout(0.2),
    Dense(1)
])

- Used early stopping , optimizer - ‘adam'

## Results
### Mean Squared Error (MSE): 1.2848783648084887
