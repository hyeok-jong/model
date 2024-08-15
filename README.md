# model

nn.module로 되어있는건 나오는데, nn.functional은 안나옴



```
def get_unique_modules(model):
    unique_modules = set()
    for module in model.modules():
        unique_modules.add(type(module).__name__)
    return unique_modules
```
