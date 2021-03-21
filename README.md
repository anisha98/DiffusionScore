# DiffusionScore

The code present in the Cleaning_of_data_and_putting_it_together.ipynb represents the preprocessed data where we drop the null values and normalise the hindex and snip values which is then put together in various files(Norm.csv,journalwithsnip.csv,journalwithh_index.csv,journalconfwithh_index.csv,confwithh_index.csv) these are the input to the model which provide the source node heat value(Initial values)

Adjacency Matrix representation - rows indicates the source and the columns indicate the target

The Execution of 1 article(presented in paper).ipynb file shows the result of the model for the sample network present in the paper.

Heat values generation for new dataset.ipynb represents the file which contains the code to read each University folder and read the files one by one where each file represents the adjacency matrix for one article network where the name of the file indicates the name of the article.
