# Self-driving car simulation using CNN (Pytorch)

## Training:
- Generate data using simulator
- Modify the model in models.regressor, output can be steering angle (and throttle)
- Run train.py

```
python train.py
```

## Inference:
- Start simulation in autonomous mode
- Load model checkpoint
- Run command:

```
python drive.py
```
## Results
![Alt Text](results/result.gif)
