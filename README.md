dataset.zip contains the dataset used for my thesis. Extract this in the same folder as the Notebook files.

Thesis Slide-Paper Matching.ipyn contains the code that was used for the slide-paper matching part of my thesis.

Thesis Citation Network Analysis contains the code that was used for analysing the citation network. 

To save time when running the code, you can modify the amount of entries are loaded from the dataset. 
In the function "process_pdf_files(base_path, model, transform)", change the value 4984 in "for folder_num in tqdm(range(4984)):" to a lower number.
