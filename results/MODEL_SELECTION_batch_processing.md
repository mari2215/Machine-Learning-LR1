# Звіт про вибір моделі: batch_processing

**Основна модель:** HistGradientBoosting
**Резервна модель:** LogisticRegression

## Рейтинг
|   rank | model                |   norm_cv_f1_mean |   norm_cv_roc_auc_mean |   norm_latency_p95_ms |   final_score |
|-------:|:---------------------|------------------:|-----------------------:|----------------------:|--------------:|
|      1 | HistGradientBoosting |          0.748366 |               0.552202 |              0.869443 |      0.701624 |
|      2 | LogisticRegression   |          0.59526  |               0.556488 |              0.898424 |      0.613945 |
|      3 | RandomForest         |          0.638082 |               0.607314 |              0.371029 |      0.602146 |
|      4 | DecisionTree         |          0.320824 |               0.280518 |              0.930377 |      0.369687 |

## Відхилені моделі
