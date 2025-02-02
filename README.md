# X-Ray_Classification-CDAC

X-Ray classification deals with identifying the disease i.e. pneumonia in a person.The objective of this project is to make the work of medical professionals easier  and quicker than earlier to detect pneumonia in a person's body. To fulfill the objective of this project, we need the datasets so as to train the model about the differences between normal person and a person having pneumonia.

## Dataset for project: 

Link- https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/download

Before running training dataset program download the dataset from the link and place the *chest_xray* folder, containing *train*, *test* and *val* folders, inside *X-Ray_Classification-CDAC* folder.

## Install process:
	git clone https://github.com/prateeksarangi/X-Ray_Classification-CDAC/
	cd X-Ray_Classification-CDAC
	
## Create and activate virtual environment:
	pip install virtualenv
	virtualenv <env_name>
	source <env_name>/bin/activate
	
## Installing required packages:
	pip install -r requirements.txt

## Training dataset on local system: 
	python TunedNN.py

## Runnning the prediction model:
	python ServerSide.py

## Running the webapp:
	python exec.py

After executing *exec.py*, open *localhost:5000* in web browser.

# Springer Paper Link
**SCI-2020 -** https://link.springer.com/chapter/10.1007/978-981-16-1502-3_59

# Reference
	@incollection{sarangi2021early,
	  title={Early Detection of Pneumonia from Chest X-Ray Images Using Deep Learning Approach},
	  author={Sarangi, Prateek and Priyadarshan, Pradosh and Mishra, Swagatika and Rath, Adyasha and Panda, Ganapati},
	  booktitle={Smart Computing Techniques and Applications},
	  pages={595--604},
	  year={2021},
	  publisher={Springer}
	}
