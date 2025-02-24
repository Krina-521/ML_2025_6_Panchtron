# ML_2025_6_Panchtron

### Group member details:
| Member Name | Email Id | Enrollment No |
| ------------|----------|---------|
| Krina Khakhariya | krina.k@ahduni.edu.in | AU2444005 |
| Urjit Mehta | urjit.m@ahduni.edu.in | AU2444007 |
| Brijesh Munjiyasara | brijesh.m@ahduni.edu.in | AU2444011 |
| Khushi Agrawal | khushi.a2@ahduni.edu.in | AU2444006 |
| Jafri Syed Mujtaba | jafri.h@ahduni.edu.in | AU2120119 |

## 6. Modelling and Prediction of Athletic Readiness based on Sleep and Recovery Patterns

- **Problem Statement:** In collegiate basketball, the athletes get fatigued due to frequent
games, travel, regular training, and academic and social commitments. Fatigue leads to a
disrupted sleep schedule and slow recovery. The objective of this project is to assess the
impact of athlete sleep patterns on their performance (readiness) and thereby predict
RSImod (readiness measure).

- **Milestones / Deliverables:**
  - Fill in the missing values in the dataset using data appropriate technique.
  - Analyze the relationship between sleep and recovery features and RSImod.
  - Train a model to predict the RSImod based on the sleep and recovery features.
  - Explain your model outcomes using xAI techniques.
  - Report your findings, whether generic or cluster-based.
 
- **Dataset:** Athlete Dataset


# Developer Guidelines  

1. All code must be written in a **.ipynb (Jupyter Notebook)** file with proper markdown explanations and comments. Files should be placed in the correct folder with meaningful names.  

2. Use **Python 3** and **pip3** for installing and running any libraries.  

3. Every developer **must create a virtual environment** inside the project folder before starting work.  

4. The virtual environment **must be named** `venv` (no other name is allowed).  

5. When installing a new library, developers **must run the following command inside the virtual environment** before pushing any changes to Git:  
   ```
   pip3 freeze > requirements.txt
   ```  

6. To install all required libraries from `requirements.txt`, use:  
   ```
   pip3 install -r requirements.txt
   ```  

7. **Use Git Properly**  
   - Pull the latest changes from the main branch before starting work.  
   - Commit frequently with meaningful commit messages.  
   - Before pushing code, test it to ensure everything runs smoothly.
   - Developers **must work in their own branch**, named after their **first name** (e.g., `john`).  
   - **Direct merging into the main branch is not allowed.** All code must be reviewed and approved by **Krina Khakhariya** before merging.  

8. **Follow Clean Code Practices**  
   - Use meaningful variable and function names.  

9. **Security Best Practices**  
   - Do not commit sensitive data (API keys, passwords, etc.).  
   - Use `.gitignore` to exclude unnecessary or sensitive files.  

10. Write docstrings for functions and classes to explain their purpose and usage.  