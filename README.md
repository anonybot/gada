## Dependencies

```python
numpy==1.14.1
scikit_image==0.13.1
scipy==1.0.0
tensorflow_gpu==1.6.0
tensorbayes==0.4.0
```

## Download Data

Download scripts for MNIST and SVHN provided in `./data/`.

## Run code

### Training
```
python main.py --datadir data --run 0 --src mnist --trg svhn
```

Tensorboard logs will be saved to `./log/` by default.
