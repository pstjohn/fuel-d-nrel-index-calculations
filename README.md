# Calculation of the NREL index for Fuel D blends

## Files

* `compound_properties.csv`: A set of compounds (with SMILES strings) found in the DHA analysis. HoVs are estimated from critical properties using the  Pitzer−Carruth−Kobayashi method, while vapor pressures were estimated using the Lee-Kesler method (at 443K). Yield sooting indices were either taken from experimental results (pred_type=experimental) or estimated using a YSI group contribution model (ysi.ml.nrel.gov).

* `fueld_properties.csv`: A table of bulk fuel properties for the Fuel D blends

* `fueld_dhas.csv`: DHAs for all fuel D blends. sample_id corresponds to the column header in `fueld_properties.csv`.

* `epa.csv`: NREL index calculations and PM measurements for the EPAct/V2 dataset, used to determine slope parameters for each term.

* `fuel_c_values.csv`: NREL index calculations for Fuel C blends as comparison
