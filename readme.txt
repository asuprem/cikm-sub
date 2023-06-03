Files:
1. ContrastiveSmoothness.py
	Regularizer for semantic masking training
2. FastKMeansProxy.py
	Compute high density sets
3. HFGenerator.py
	Torch Generator and Dataset class with semantic masking
4. SofttripleLoss.py
	Softtriple loss implemented from https://github.com/idstcv/SoftTriple, presented for completeness
5. Semantic_Masking.ipynb
	Notebook implementing workflow for semantic masking, temporal weighting, and indexing. Note that notebook requires access to datasets, without which the workflow will not work. As such, it is only provided as a review aid.



Additional notes:
	Code is implemented with an experimentation framework (https://ednaml.org); as such, it relies on some imported boilerplate classes (e.g. ednaml.Loss, ednaml.Generator, etc)