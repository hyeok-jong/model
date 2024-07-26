# model


```
def get_unique_modules(model):
    unique_modules = set()
    for module in model.modules():
        unique_modules.add(type(module).__name__)
    return unique_modules
```
