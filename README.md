# simaR
Simulation of functional response experiments.

simaR is composed by six core functions used sequentially:
---------------------------------------------------------------------


simData() -> Simulation of datasets.

newTests() -> Discrimination between type-II or type-III functional response.

getFitData() -> Simulated data fitting to the selected functional response type.

plotCurves() -> Visulatization of simulated replicates.

Max_attackRates() -> Calculation of the maximum attack rate for each simulated functional response experiment.

MARbootstrapping() -> Bootstrapping of the mean of maximum attack rate and calculation of its confidence interval.

---------------------------------------------------------------------
Download the "simaR.rar" file, unzip it, and place it into your R directory of libraries
---------------------------------------------------------------------

See how to deal with outliers at the help source using ?Max_attackRates

---------------------------------------------------------------------

Reference:
Benhadi-Marín, J., Pereira, J.A., Barreales, D., Sousa, J.P. & Santos, S.A.P., 2018. A simulation-based method 
to compare the pest suppression potential of predators: A case study with spiders. Biological Control, 123: 87-96.
