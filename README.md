# Lab Artificial Intelligence CS420

## Lab Assignment: Decision Tree

### Description
This assignment involves building decision trees on real-world datasets using `scikit-learn`.

### Datasets
1. **Binary Class Dataset**: [UCI Breast Cancer Wisconsin (Diagnostic) dataset](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
   - **Purpose**: Classify tumors as malignant (M) or benign (B).
   - **Size**: 569 samples.
2. **Multi-class Dataset**: [UCI Wine Quality dataset](https://archive.ics.uci.edu/dataset/186/wine+quality)
   - **Purpose**: Classify wine quality based on physicochemical properties.
   - **Size**: 4898 samples.
3. **Additional Dataset**: Chosen by the student, meeting these criteria:
   - Contains features and labels for supervised learning.
   - At least 300 samples.
   - Includes multiple classes or binary classes.

---

### Specifications
1. **Dataset Preparation**:
   - Split into training and testing sets with proportions: 40/60, 60/40, 80/20, and 90/10.
   - Perform stratified sampling and shuffle before splitting.
   - Visualize class distributions in original, training, and testing datasets.

2. **Building Decision Tree Classifiers**:
   - Train a `sklearn.tree.DecisionTreeClassifier` using information gain.
   - Visualize the decision tree using Graphviz.

3. **Evaluation**:
   - Use `classification_report` and `confusion_matrix`.
   - Provide insights into classifier performance.

4. **Depth and Accuracy**:
   - Experiment with `max_depth` values: None, 2, 3, 4, 5, 6, 7.
   - Visualize decision trees for each depth.
   - Report accuracy for each depth in a table and analyze.

5. **Repeat for Other Datasets**:
   - Perform all tasks for the Wine Quality and Additional datasets.
   - Group Wine Quality classes into three categories:
     - Low quality (0-4)
     - Standard quality (5-6)
     - High quality (7-10)
   - Analyze the effect of dataset characteristics on model performance.

---

### Requirements
1. **Report**:
   - Member information and task assignment table.
   - Self-evaluation of completion rate.
   - Include visualizations in `.ipynb` files and insights in the report.
   - Ensure well-formatted PDFs without cut-off figures.
   - Include references if applicable.

2. **Submission**:
   - Compress all files into `.zip`, `.rar`, or `.7z` format named as `StudentID1_StudentID2_etc`.
   - If the file exceeds 25MB, host large files on Google Drive and share a link.

---

### Assessment
- **Analysis of Datasets**:
  - Breast Cancer: 30%
  - Wine Quality: 30%
  - Additional Dataset: 30%
- **Comparative Analysis**: 5%
- **Notebook Quality**: 5%

---

### Notices
- This is a group assignment with 4 members.
- Duration: ~2 weeks.
- Plagiarism or dishonesty will result in a 0 grade.
