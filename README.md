Independent projects in data and ML systems — evaluation-first, results reported as found.

## Recent work

- **[poshan-intelligence-pipeline](https://github.com/IpsitMohanty/poshan-intelligence-pipeline)** — ten source-specific ETL modules into a reconciled district-level data cube over monthly operational data; predictive models validated and reported only where they clear a leakage/robustness check.
- **[awc-operations-dashboard](https://github.com/IpsitMohanty/awc-operations-dashboard)** — anomaly/risk/alert scoring validated against a synthetic generator's ground-truth injection log; recall reported directly. 75 tests.
- **[course-recommender-system](https://github.com/IpsitMohanty/course-recommender-system)** — nine recommenders evaluated on held-out ranking; one beats a popularity baseline (0.1082 vs. 0.0964 Precision@10), the other five collaborative-filtering models score below it.
- **[cnn-vit-land-classification](https://github.com/IpsitMohanty/cnn-vit-land-classification)** — a 70% vs. 98.6% accuracy gap between identical Keras/PyTorch CNNs traced to one mismatched default (BatchNorm momentum, 0.99 vs. 0.1); an added ViT hybrid stage then measured 0.58pp worse at ~2x the parameters.
- **[rag-ingestion-evaluation](https://github.com/IpsitMohanty/rag-ingestion-evaluation)** — similarity score can't separate an answer from nothing across 24 tested configurations; a corrective agent loop recovers 0%→41.7% recall on the hardest queries with zero fabrications.
- **[cinegraph](https://github.com/IpsitMohanty/cinegraph)** — film discovery ranked by production relationships, not ratings. Pre-registered, labeled evaluation on 120 results across 12 seed films: baseline 60/120 interesting, 72/120 after tuning, 8/120 wrong.
