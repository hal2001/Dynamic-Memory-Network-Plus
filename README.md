# Dynamic Memory Network Plus
[DMN+](https://arxiv.org/abs/1603.01417) implementation in Pytorch for question answering on the bAbI 10k dataset.

Input Module for DMNPlus
![image](https://raw.githubusercontent.com/foamliu/Dynamic-Memory-Network-Plus/master/images/inputModule.png)

## Usage
### Download data 
Run the included shell script to fetch the data :
```bash
$ chmod +x fetch_data.sh
$ ./fetch_data.sh
```

### Train
```bash
$ python train.py
```

## Results
| Task ID | This Repo | Xiong et al |
| :---: | :---: | :---: |
| 1 | 100% | 100% |
| 2 | 95.6% | 99.7% |
| 3 | 85.0% | 98.9% |
| 4 | 100% | 100% |
| 5 | 99.5% | 99.5% |
| 6 | 100% | 100% |
| 7 | 98.8% | 97.6% |
| 8 | 100% | 100% |
| 9 | 100% | 100% |
| 10 | 100% | 100% |
| 11 | 100% | 100% |
| 12 | 100% | 100% |
| 13 | 100% | 100% |
| 14 | 98.6% | 99.8% |
| 15 | 100% | 100% |
| 16 | 48.0% | 54.7% |
| 17 | 87.9% | 95.8% |
| 18 | 97.0% | 97.9% |
| 19 | 99.7% | 100% |
| 20 | 100% | 100% |

### Demo
Download pre-trained DMN+ [Model](https://github.com/foamliu/Dynamic-Memory-Network-Plus/releases/download/v1.0/) then run:
```bash
$ python demo.py
```

## Reference
1. [Dynamic Memory Network for Visual and Textual Question Answering](https://arxiv.org/abs/1603.01417). 
2. https://github.com/dandelin/Dynamic-memory-networks-plus-Pytorch