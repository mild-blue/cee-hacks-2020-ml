To run the notebook and see the results you need to have anaconda installed

(anaconda.com)

and then run:

```
conda env create -f conda.yml --name ceehacks
conda activate ceehacks
pip install pip-tools
pip-sync
pre-commit install

```

also you need to have the data in the root folder of the project
in folder data.

we expect you to have data:
```
hackathon_low_cardiac_output.csv
hackathon_low_cardiac_output_test_set.csv
hackathon_low_mixed_venous_oximetry.csv
hackathon_low_mixed_venous_oximetry_test_set.csv
```

after that you can open the notebook `final_results.ipynb` 
and see for yourself the results.
