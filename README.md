# MetalOxideSolubility
## Exercise in Data Science to predict solubility of Metal Oxides

This exercise was generated using Google Gemini to practice on a simple yet important Chemistry problem. I have asked Gemini to generate 100 data points. Such data points have been exported in a CSV file and are present in the repository for use. Asking Gemini to generate data is by the way an example of using Generative Artificial Intelligence (GAI) for the purpose of data analysis.

## The task assigned
I have asked Gemini to assign me the desired task for the problem without guiding me through it. 
This is the output:

1. Build a classification model that can predict the "Solubility Category" (Highly Soluble or Poorly Soluble) of a metal oxide based on its "Atomic Number," "Electronegativity," and "Ionic Radius."

2. Evaluate the performance of this model on unseen data using appropriate classification metrics (e.g., accuracy, precision, recall).

## Description of the dataset
It is always useful to have a description of the dataset for reference where each value is explained. Gemini has explained me the data as follows:

- Metal Cation: The specific metal ion we are considering.
- Atomic Number: The number of protons in the nucleus of the metal atom.
- Electronegativity (Pauling Scale): A measure of the tendency of an atom to attract a bonding pair of electrons.
- Ionic Radius (pm): The radius of the metal ion in picometers.
- Oxide Formula: The chemical formula of the metal oxide. (While included for context, you might not directly use this as a numerical feature in a basic model).
- Solubility Category: The target variable, indicating whether the metal oxide is "Highly Soluble" or "Poorly Soluble" in neutral water.

  I understand this dataset as I am  BSc, MSc and PhD in Chemistry/Materials Chemistry

## How to use the notebook
A method I have found since using GitHub "properly" for the first time is to use Git on you computer and make a copy of the whole repository with command *git clone <link>*.
I will  work on the offline copy and then upload the directory to my Git/GitHub account using the command *git push origin "branch name"*
Before finish the day, I assume it will be necessary to commit the changes which is different from simply uploading a file???? **YES**

Here is the workflow

1. *git clone <link>*                   Downloads the remote repository into the folder where command line open
2. *Work on files*
3. *git add .*                         Creates and index of files to be updated for the whole working folder (if . is used). Change . with specific filename to "queue" only specific files.
4. *git commit -m "COMMENT HERE"*      Commits changes. From modified to permanent change
5. *git push origin "branch name"*          Uploads the commited files as in index (see step 3) to the remote repository
