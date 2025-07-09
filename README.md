# _ALL_
Install all packages in PharmaForest.

~~~sas
%installPackage(
	OncoPlotter sashash sas_dataset_json SASPACer misc
	sas_faker saslogchecker sas_compare rtfcreator,
	sourcePath=https://github.com/PharmaForest/_ALL_/raw/main/
)
~~~
