# GRU: 
## Model : 
- model = Sequential([
GRU(50, activation='relu', input_shape=(seq_length, 1)),
Dense(1)
])

- Used early stopping , optimizer - ‘adam'

## Results
### Mean Squared Error (MSE): 1.1596662278743528
