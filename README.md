# CNN_MNIST - MNIST Classification

Compact CNN for 10-class digit recognition (28×28 grayscale).

## Performance
| Split | Accuracy |
|-------|----------|
| Train | 86.3% |
| Val   | 95.2% |
| **Test** | **95.35%** |

## Features
- **2-layer CNN** (18k params): Conv → Pool → Dropout → Dense
- MNIST dataset (60k train | 10k test)
- Data augmentation + SGD (lr=0.003, momentum=0.9)
- Early stopping, model checkpointing


## Files
- `CNN_MNIST.ipynb`: Complete training + evaluation
- `bestmdl.keras`: Best model (auto-saved)
