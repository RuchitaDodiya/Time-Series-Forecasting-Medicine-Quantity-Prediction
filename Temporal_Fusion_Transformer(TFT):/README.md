# Temporal Fusion Transformer (TFT)
## Reference 
[https://unit8co.github.io/darts/generated_api/darts.models.forecasting.tft_model.html#darts.models.forecasting.tft_model.TFTModel.fit]

## Model : 

input_chunk_length = 5

forecast_horizon = 1

model = TFTModel(

    input_chunk_length=input_chunk_length,
    
    output_chunk_length=forecast_horizon,
    
    hidden_size=64,
    
    lstm_layers=1,
    
    num_attention_heads=4,
    
    dropout=0.1,
    
    batch_size=16,
    
    n_epochs=100,
    
    add_relative_index=True,
    
    add_encoders=None,
    
    random_state=42,
)

## Results
### Mean Squared Error: 1.2936289
