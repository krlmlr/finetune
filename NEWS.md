# finetune (development version)

# finetune 0.1.0

* A check was added to make sure that `lme4` or `BradleyTerry2` are installed (#8)

* Added `pillar` methods for formatting `tune` objects in list columns. 

* Fixed bug in `random_integer_neighbor_calc()` to keep values inside range (#10)

* `tune_sim_anneal()` now retains a finalized parameter set and replaces any existing parameter set that was not finalized (#14)

* A bug in win/loss racing was fixed for cases when one tuning parameter had results that were so bad that it broke the Bradley-Terry model (#7)

# finetune 0.0.1

* First CRAN release
