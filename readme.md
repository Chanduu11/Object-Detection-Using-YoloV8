
Vehicle Detection and Tracking using Heatmap
install pytorch with cpuonly

```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```
or
```
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```

install requirements

```
pip install -r requirements.txt
```

test heatmap
    
```
python heatmap_det.py
```

run main script

```python
python tracker.py
```

