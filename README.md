#AI-Fantasy-Manager-Squad-Optimiser

Goal: Create an assistant that recommends the strongest fantasy team, transfers, captain, and starting lineup.

Build plan
1. Ingest player prices, historical fantasy points, fixtures, and availability.
2. Engineer recent-form, opponent-strength, and expected-minutes features.
3. Predict future fantasy points using regression models.
4. Use integer linear programming to select a team within budget and squad constraints.
5. Implement transfer recommendations and captain selection.
6. Backtest decisions against previous gameweeks.
7. Build a dashboard showing expected points and alternative strategies.
Suggested stack: Python, LightGBM, PuLP or OR-Tools, FastAPI, Streamlit.

Module practice: Regression, prediction, preprocessing, model evaluation, cloud deployment.

Evaluation: MAE for points predictions, cumulative simulated fantasy points, and performance against simple baseline managers.

Extension: Use Monte Carlo simulations to recommend transfers across a rolling 4–6 gameweek horizon.

Data: Fantasy Premier League public data, subject to current access and usage rules.
