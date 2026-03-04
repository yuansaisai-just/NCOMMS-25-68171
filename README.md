# NCOMMS-25-68171
Single-molecule sensing by deep-learning-decoded intermolecular interactions enabling sub-attomolar, second-scale detection

## Dependencies

- Python: **3.8.18**
- Required packages:

  - numpy==1.23.5  
  - pandas==2.0.3  
  - matplotlib==3.7.2  
  - seaborn==0.13.1  
  - scipy==1.10.1  
  - scikit-learn==1.3.0  
  - torch==2.1.0  
  - nptdms==1.8.0  

Install via:

```bash
pip install -r requirements.txt
```

## Code / Notebooks

### Data Preprocessing
- **File:** `Data-Preprocesing.ipynb`  
- **Description:** Data preprocessing pipeline for deep learning experiments.

### Benchmark Method
- **File:** `SpectrumClustering.ipynb`  
- **Description:** Spectral clustering analysis as a benchmark method.

### Deep Learning Classifiers
- **Files:**  
  - `Classifier(CuP+CAF).ipynb`  
  - `Classifier(CuP+PTX).ipynb`  
  - `Classifier(CuP+TPH).ipynb`  
  - `Classifier(FP+CAF).ipynb`  
- **Description:** Training and evaluating deep learning classifiers, and presenting the results.

### Supplementary Experiments
- **Files:**  
  - `G0-shift robustness experiment.ipynb`  
  - `Occlusion Sensitivity Analysis.ipynb`  
  - `Random background truncation experiment.ipynb`  
- **Description:** Robustness and interpretability experiments (G0-shift, occlusion sensitivity, and random truncation).

### Ablation Experiments
- **Files (Time + Frequency):**  
  - `Ablation experiment-both(CuP+CAF).ipynb`  
  - `Ablation experiment-both(CuP+PTX).ipynb`  
  - `Ablation experiment-both(CuP+TPH).ipynb`  
  - `Ablation experiment-both(FP+CAF).ipynb`  
- **Files (Frequency only):**  
  - `Ablation experiment-Onlyfreq(CuP+CAF).ipynb`  
  - `Ablation experiment-Onlyfreq(CuP+PTX).ipynb`  
  - `Ablation experiment-Onlyfreq(CuP+TPH).ipynb`  
  - `Ablation experiment-Onlyfreq(FP+CAF).ipynb`  
- **Files (Time only):**  
  - `Ablation experiment-Onlytime(CuP+CAF).ipynb`  
  - `Ablation experiment-Onlytime(CuP+PTX).ipynb`  
  - `Ablation experiment-Onlytime(CuP+TPH).ipynb`  
  - `Ablation experiment-Onlytime(FP+CAF).ipynb`  
- **Description:** Ablation studies comparing time-only, frequency-only, and time–frequency fusion.

## Data

The `data/` folder contains the complete CuP and CuP+CAF datasets. 
Other datasets are not included in this repository due to file size limitations.

## Authors

- Ziyang Wang 
- Saisai Yuan (yuansaisai@just.edu.cn)
- Zhichao Pan (panzhichao@guet.edu.cn)
