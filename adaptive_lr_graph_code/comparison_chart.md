| optim.lr_scheduler | Train Accuracy | Validation Accuracy | Test Accuracy | Epochs | Initial LR |        Hyperparams        |
|:------------------:|:--------------:|:-------------------:|:-------------:|:------:|:----------:|:-------------------------:|
|  CosineAnnealingLR |     90.976%    |       85.620%       |    91.340%    |   50   |    1e-2    |         T_max=200         |
|      LinearLR      |     87.342%    |       82.680%       |    88.500%    |   50   |    1e-2    |             -             |
|       StepLR       |     81.193%    |       80.080%       |    85.650%    |   50   |    1e-2    |        step_size=5        |
|      CyclicLR      |     91.198%    |       85.500%       |    90.440%    |   50   |    1e-2    | base_lr=1e-2, max_lr=1e-1 |