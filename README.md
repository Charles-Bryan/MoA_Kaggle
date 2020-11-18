# MoA_Kaggle
Data pipeline for Kaggle's Mechanisms of Action (MoAs) Competition

Python notebook used to work with Kaggle's MoA dataset and predict the MAchanisms of Action for the various drugs.

Top-level of steps taken in Main:

1. Environment Setup
2. Ensure Reproducibility
3. HyperParameters - All
4. Competition Supplied Data
5. Import Data
6. PreProcessing
7. Initial Filtering
8. Feature Engineering
9. Feature Reduction
10. CV Folds
11. PyTorch Setup
12. Training Process
13. Results
14. Prepare Submission File

Most recent Results:
5-seed Raw CV log_loss: 0.015840346076463094
Adj CV log_loss: 0.014598703743636634
Raw roc_score: 0.7908
Adj roc_score: 0.8104
Leaderboard: 0.01848
