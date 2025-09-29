# -Forecasting-with-Prophet
Ce projet consiste à prévoir la demande sur une série temporelle de 6 ans et à proposer des solutions d’optimisation logistique.
## Méthodologie
- Prétraitement des séries temporelles (EDA, stationnarité, décomposition, détection des outliers)
- Modélisation avec Prophet + régresseurs custom + Fourier hebdomadaire
- Optimisation des hyperparamètres avec Optuna
- Validation croisée et métriques : MAE, RMSE

## Résultats
- MAE = 0.0373, RMSE = 0.0466
- Graphiques de tendance, saisonnalité et résidus
- Amélioration de la prédiction par rapport à baseline
