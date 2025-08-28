# Seasonal Spread & Breakeven Plot

Below is the generated plot illustrating the seasonal spread over time. The breakeven and trigger levels (based on storage fee, inject/withdraw cost and loss percentage) are drawn as horizontal lines. Today’s expected carry P&L per MWh (spread minus total costs) is highlighted on the curve.

<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/763c92e6-023a-4d1f-ac85-5956337d5a54" />

The table generated below shows the net carry per MWh under baseline conditions and under ±10 % moves in the winter price. A higher winter price increases the spread but also the value lost through storage losses, so the net benefit is not linear. Adjust the configuration in config.yaml to explore other storage fees, injection/withdrawal costs or loss percentages.

<img width="341" height="142" alt="image" src="https://github.com/user-attachments/assets/49a96580-f2ba-4b93-8f3c-cb33f61b0621" />
