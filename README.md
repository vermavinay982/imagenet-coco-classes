# ImageNet-1000 Classes, COCO 80+1 Background Classes

Click Copy Button - and use whereever you want. :innocent:

# JSON only allows key names to be strings. 
```python
import json

with open('coco_classes.json','r') as f:
    labels = json.load(f)
len(labels)
# OR if you have String
with open('imagenet_classes.json') as f:
    labels = json.load(f)
len(labels)
```

```python
with open('imagenet_classes.json','r') as f:
    text = f.read()
    labels = json.loads(text)
len(labels)
# OR if you have String
with open('coco_classes.json','r') as f:
    text = f.read()
    labels = json.loads(text)
len(labels)
```
