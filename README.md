# Running
- I used Google Colab and I recommend you to do the same
- Download dataset from https://zenodo.org/record/4042126#.Y0k2JexBw-R and store on your Google Drive (warning: it's about 6Gb)
- Run create_dataset.ipynb
- Run main_notebook.ipynb
# Notes
- If you don't want to use Google Drive, you need to modify variables that I marked with comment about it, or use [these](https://drive.google.com/drive/folders/1MZVLAzaFIKuG3oGrUtkIPiVFVfM1EcPS?usp=sharing) csv files and skip third step (but you still need to change variable dir in main_notebook.ipynb)
- I used V100 GPU, it took about 4 hours for hyperparameter search and 30 minutes for training and still I didn't use whole dataset, so run carefully
# Conclusion
- Test dataset showed about 97% accuracy, real datasets showed about 90% of accuracy
