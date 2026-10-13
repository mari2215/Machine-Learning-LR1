# Звіт про вибір моделі: realtime_edge

**Основна модель:** DecisionTree
**Резервна модель:** None

## Рейтинг
|   rank | model        |   norm_cv_f1_mean |   norm_latency_p95_ms |   norm_cv_roc_auc_mean |   final_score |
|-------:|:-------------|------------------:|----------------------:|-----------------------:|--------------:|
|      1 | DecisionTree |          0.320824 |              0.234144 |               0.280518 |      0.286759 |

## Відхилені моделі
| model                | violations                                                |
|:---------------------|:----------------------------------------------------------|
| LogisticRegression   | latency_p95_ms: above maximum (got 11.0560, need <= 10.0) |
| RandomForest         | latency_p95_ms: above maximum (got 63.2681, need <= 10.0) |
| HistGradientBoosting | latency_p95_ms: above maximum (got 13.9252, need <= 10.0) |