# Deep Learning Project: Online Encyclopedia of Integer Sequences (OEIS).

Two competing experimental design approaches are considered in determining how to best utilize recurrent neural networks (RNNs) in integer sequence learning using sequences from the Online Encyclopedia of Integer Sequence (OEIS). In particular, predicting specifically the tenth sequence value from the first nine can be achieved by fitting a model on different sequences at the corresponding sequence values or on the same sequences at earlier sequence values. Generalizability is better achieved using the former of these, meaning in this instance the fixed time-step under consideration potentially encodes usable information.

The data files are located in the "Data" folder with only oeisvals.csv used in the code but oeisnames.csv is also provided as a reference to provide context to the integer sequences. The ipynb file is self-contained and downloads the data from a public Google Drive folder. Alternatively the data can be downloaded at this link https://davidbieber.com/snippets/2020-06-28-oeis-download/.

The Jupyter notebook of the work and video presentation slides are also found here.
