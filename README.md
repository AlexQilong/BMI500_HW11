# BMI500_HW11
Code and Analysis for BMI500 11th homework.

Author: Qilong Zhao

Email: qilong.zhao@emory.edu

Q2: Agent-Based Modeling of Pandemic Spread

## Key Insights

- **Spread of Infection**: The infection spreads quickly and reaches similar levels regardless of social distancing strength. However, stronger social distancing (lower movement) slightly delays the infection spread and recovery.
- **Effect of Social Distancing**: When movement is limited, people interact less, which slightly flattens the infection curve and delays recovery. This reflects real-world expectations, where social distancing can help reduce the strain on healthcare systems.
- **Recovery Patterns**: The total number of people who recover by the end is similar across different social distancing levels. This suggests that while distancing may delay infections, it doesn’t drastically reduce the overall number of infections in a closed group.

## Comparative Model Performance

- Higher movement rates lead to faster, more immediate infection peaks with quick recovery.
- Lower movement rates slow down the spread, creating a gentler infection curve and a more gradual recovery.

## Relevance to Model-Based Machine Learning

This simulation is a basic example of using model-based machine learning for understanding disease spread. It relies on probabilities to simulate how people change states (from susceptible to infected to recovered) and can be useful in public health planning by testing different scenarios.

## Ideas for Future Improvements

1. **Realistic Movement Patterns**: Adding realistic movement, like clustering or quarantine zones, could improve how accurately the model reflects real-life spread.
2. **Varying Recovery Times**: Allowing recovery chances to change over time could add depth to recovery patterns.
3. **More Health States**: Adding more states, like “Exposed,” could represent latent (hidden) infections and simulate more complex spreading scenarios.
4. **Networked Interactions**: Replacing the grid with a network (e.g., small-world networks) could better represent real social connections.

*Disclaimer: ChatGPT 4o was/were used to complete HW 2.A to Building the Base Model.*
