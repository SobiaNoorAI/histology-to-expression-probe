**fig1_pooled_vs_within**

Pooled Pearson mixes differences between samples with spatial signal; within-sample Pearson is computed inside each sample and then averaged. Genes are chosen from training data only. The random-spot split was run for the HER2 study only; there the within-sample score is 0.20 for a random split vs 0.12 for a patient split.

**fig2_model_differences**

Filled blue = interval excludes 0; hollow gray = inconclusive. Differences are small (about 0.015-0.023 Pearson). The Integrating -> HER2 comparison with ResNet-50 is inconclusive; it has only 8 test patients. Intervals reflect variation across test patients only.

**fig3_top_genes**

Only genes chosen among the 50 most variable genes in at least 100 sample-level evaluations are shown. Top genes are mostly stromal / extracellular-matrix and immune-related, consistent with tissue structure being visible on H&E (a hypothesis, not tested here).

