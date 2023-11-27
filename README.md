# Neuro Divergent AI Analyser
 Autism Prediction Using GNN


# Prerequisites Installation

1. Before running the project, you need to install the following Python packages:

pip install nilearn
pip install networkx
pip install sklearn
pip install torch_geometric
pip install fastdtw
pip install numpy
pip install pandas
pip install matplotlib
pip install tqdm
pip install pprint
pip install torch
pip install seaborn



2. The execute the following code to download the dataset and save the output in the desired directory.

from nilearn.datasets import (
    fetch_abide_pcp,
    fetch_coords_power_2011,
)

abide = fetch_abide_pcp(
            data_dir=r"/Users/vinoth/PycharmProjects/paper_implementation/Dataset/source/mri_images",
            pipeline="cpac",
            quality_checked=True,
            #SITE_ID="PITT",
        )

3. The main model notebook is located inside the folder “DTW_Final_Model_Submission”.
	Replace the directories name to desired location to save the outputs.
	Replace the source of phenotypic csv and mri image to place where the orginal dataset is downlaoded.
	Running the notebook is straight forward by clicking run all.
	The outputs will be displayed in the notebook.
4. The base mode notebook is located inside the folder “Base_Line_Model”.
	Replace the directories name to desired location to save the outputs.
	Replace the source of phenotypic csv and mri image to place where the orginal dataset is downlaoded.
	Running the notebook is straight forward by clicking run all.
	The outputs will be displayed in the notebook.