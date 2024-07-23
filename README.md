## KAN applications: AI model for physics

author: Luca Manzi

```bash
pip install git+https://github.com/KindXiaoming/pykan.git  # For Bleeding edge GitHub installation
# or
pip install pykan

## requirements available in
pip install -f requirements.txt
```

The suggested way to explore this project is to go trought:
manual_fit -> automatic_fit -> anderson_localization


```
project/
│
├── manual_fit.ipynb                    # gives an introduction about KAN
│
├── automatic_fit.ipynb                 # Autofit and automatic grid point optimization
├── utils2.py                           # Auto generating random functions
│
├── alice_anderson_localization.ipynb   # Anderson localization, model creation, 
|                                       # classification using KAN, SVM and Deep Neural Networks
├── .gitignore              
├── README.md               
└── requirements.txt   
```

