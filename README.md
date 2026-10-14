<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0F2027,50:203A43,100:2C5364&height=240&section=header&text=ANDREA%20BABSKA&fontColor=ffffff&fontSize=64&fontAlignY=40&stroke=36BCF7&strokeWidth=1&desc=Engineering%20Graduate%20%C2%B7%20Machine%20Learning%20%C2%B7%20Biomedical%20Data&descSize=18&descAlignY=62&descColor=36BCF7" alt="Andrea Babska" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3500&pause=800&color=36BCF7&center=true&vCenter=true&width=700&lines=Machine+learning+for+biomedical+problems;Implementing+neural+networks+%26+GNNs;From+data+to+trained+models" alt="Typing animation" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/andreababska"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/andreababska?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/></a>
</p>

---

## 🧬 About me

I recently finished my master's in *Automation and Informatization in Chemistry and Food Industry* at **STU Bratislava**. My thesis was about predicting molecular docking scores with **graph neural networks**, and that's where I got properly into machine learning for biomedical problems. I started in a lab (PCR, ELISA) and moved towards code, so I like working on problems where the data comes from real biology. I'm open to ML and biomedical projects where I can keep learning by building and training models.

- 🔬 Background in the lab (PCR, ELISA) and in code, a handy combination for biomedical ML
- 🖥️ Hands-on experience with high-performance computing on the **SAV HPC Devana** supercomputer
- 🌍 English (working language) · German (learning)
- 📚 Currently expanding my ML knowledge with online courses (latest: *Machine Learning with Python* by IBM on Coursera)

---

## 🛠️ Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge" alt="Matplotlib"/>
</p>
<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>
<p>
  <img src="https://img.shields.io/badge/PCR-2E8B57?style=for-the-badge" alt="PCR"/>
  <img src="https://img.shields.io/badge/ELISA-2E8B57?style=for-the-badge" alt="ELISA"/>
  <img src="https://img.shields.io/badge/Lab%20data%20analysis-2E8B57?style=for-the-badge" alt="Lab data analysis"/>
</p>


<details>
<summary><b>🧠 Machine learning toolbox</b></summary>

- Neural networks and graph neural networks (DimeNet++, GemNet)
- SOAP descriptors for molecular structure
- Hyperparameter optimisation with Hyperopt
- HPC workflows (Devana)

</details>

<details>
<summary><b>🌐 Web development</b></summary>

Semester project: migrated a department web application from procedural PHP to **Laravel** (MVC), with full CRUD operations, searchable and sortable DataTables, and export to Excel, CSV and PDF.

</details>

<details>
<summary><b>🔬 Laboratory background </b></summary>

Bachelor's in *Food, Nutrition and Cosmetics* at **STU Bratislava**. My thesis dealt with the production of staphylococcal enterotoxins in *S. aureus* isolates. I worked hands-on with **PCR** and **ELISA** and learned to interpret complex, sometimes inconsistent laboratory data.

</details>

---

## 🚀 Featured project

### 🧪 [GNN Docking Score Prediction](https://github.com/andreababska/gnn-docking-score-prediction)

My master's thesis: predicting **molecular docking scores** at the active site of the **SARS-CoV-2 main protease**. I **implemented and benchmarked** two graph neural network architectures against a classical SOAP descriptor + neural network baseline.

| Model | Idea |
|---|---|
| **SOAP + NN** | Atomic-environment descriptors fed into a fully connected network (Keras) |
| **DimeNet++** | Directional message passing over distances and angles (PyTorch Geometric) |
| **GemNet** | Geometric message passing with triplet interactions |

⚙️ Hyperparameters tuned with **Hyperopt (TPE)**, large-scale runs on the **Devana HPC**.

<details>
<summary><b>🔎 Click to see how the pipeline works</b></summary>

1. Molecules are loaded from `.xyz` files (positions, atomic numbers, docking score as the target)
2. Data is split into train and validation sets with a fixed seed
3. Hyperopt searches the architecture space for each model (50 epochs per trial, Adam, MSE loss)
4. The best configurations are trained with 5-fold cross-validation
5. Final evaluation runs on an independent in vitro dataset that was never used during training or tuning

</details>

---

<p align="center">
  💬 Open to interesting ML and biomedical projects, from implementation to evaluation. Feel free to reach out via LinkedIn!
</p>
