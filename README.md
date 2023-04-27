# eQuest *.SIM Parsing #

### Installing ###

Download and extract the source ZIP or clone the repository into a local folder.
Open your python command line, change to the folder install the required packages:

```
pip install -r requirements.txt
```

### Parsing and using the SIM file ###

Place the .SIM file into the same folder (e.g., eQSimParsing) with the .PY and .IPYNB files, and remove any other .SIM files. Then run the command line script or notebook script. Either script will write outputs to files “PV-A.csv” and “SV-A.csv”. Command line syntax is simple:

```
python eqsimparsing.py
```

As of today, will correctly parse the SV-A, PV-A, BEPS (for unmet hours) and the PS-B report.

Included in this repository is the `eqsimparsing.py` where the functions are defined.

The IPython Notebook is provided as an example of how to use it (with an example *.SIM file and the two .csv outputs).
