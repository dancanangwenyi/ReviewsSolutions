#K Means Clustering

Expected implementation:

    For the dataset, generate the dataset using built-in tools from the
    programming language. Use your preferred labels for the outputs.
    
    There should be two options to train the model: either train the model with
    defaults for the number of iterations and the “k” value or accept user input
    for the same values.

    Present your findings regarding the clusters, either using visualisations (for
    this, pick any library you see fit) or by printing them in a tabular format.
    Pick any evaluation metric(s) you see fit and report on your findings.
##Dataset Used
    In this implementation the iris dataset was used. The iris dataset is a standard 
    datset that is mainly used to test clustering algorithms. Hence I chose it to showcase 
    that the algorithm actually works as expected

##Visualisation
    To visualiuse the ouput from the clusterring you can run the make fil if working
    on a linux or mac machine. But if you are using windows, install the requirements 
    in the requirements.txt file and run the kMeans_Plot.py file to get the output in a 2d graph
## Files contained in the folder
    kMeans.py
    kMeans_Plot.py
    iris.txt
    Makefile
    Readme.md
    requirements.txt

## How to compile the program
	make
## How to activate the virtual environment
	source ./venv/bin/activate
## How to run the test program
	make run

## License
[MIT](https://choosealicense.com/licenses/mit/)
