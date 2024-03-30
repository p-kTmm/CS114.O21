# THỰC HÀNH CS114-LAB01: HANDWRITTEN DIGIT CLASSIFICATION

## Download data
```bash
git clone https://github.com/likr/kplib
```


## Run
**Step 1:** Run ```testmaker.py``` script to determine the number of suitable files for execution. All these files will be stored in the ```MyTest``` folder.
```bash
python testmaker.py
```

**Step 2:** Execute ```knapsackOR.py``` to use Google's OR Tools for solving all test cases stored in the ```MyTest``` folder. The results will be saved in ```result.csv```.
```bash
python knapsackOR.py
```

## File Structure
```
Knapsack_OR/
│
├── testmaker.py
│
├── knapsackOR.py
│
├── kplib/
│   ├── (data)
│   ├── ...
│   └── ...
│
└── MyTest/
    ├── (All files are chosen)
    ├── ...
    └── ...
```

