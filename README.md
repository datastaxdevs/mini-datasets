# Mini datasets

Small datasets for use in demos, quickstarts and so on.

## Example usage (Python)

```
import requests

philo_dataset = requests.get(
    "https://raw.githubusercontent.com/"
    "datastaxdevs/mini-datasets/refs/heads/main/datasets/"
    "philosopher-quotes.json"
).json()

print("An example entry:")
print(philo_dataset[16])
```