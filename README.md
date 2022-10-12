# JSON-Parser-with-python-paths

This tool parses a JSON file and create a clickable tree view that gives python paths of every key.

JSON parsing is a very common activity and JSON parsers help a lot. Personnaly I use a lot the online tool named JSON Path Finder.

This one parse JSON file an gives you the full path of a key you select in the results.  Then it is easy to go to python script and write parser.

I decided one day to write my own JSON parser. It was just a challenge.  And here is the result.


## Dependancies

You need to install the 2 following python modules :

- crayons
- ijson

## Installation

Clone the whole content of this repository into your Python Workstation.

    git clone https://github.com/pcardotatgit/JSON-Parser-with-python-paths.git

Install crayons and ijson 

    pip install crayons
    pip install ijson

And that's it

## Run the application


- Step 1 you must copy and paste a JSON file into the  **json_file** subfolder. This subfolder is supposed to contains only one JSON file. If several JSON files are located into this subfolder, only the last one will be computed.
- Step 2 Open a console terminal and go to the application directory into your laptop
- Step 3 run the **1-json_to_dtree_with_python_path.py** script

.

    python 1-json_to_dtree_with_python_path.py

## Result

The resulting file is the index.html file located into the **result** subfolder.

    ./result/index.html   just open it with your browser

Open it with your browser and the Tree Graph will appear 

