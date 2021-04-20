_your zenodo badge here_

# khan-etal_2021_NatureScientificData

**A global gridded monthly water withdrawal dataset for multiple sectors from 2015 to 2100 at 0.5° resolution under a range of socioeconomic and climate scenarios**

Zarrar Khan<sup>1\*</sup>, Neal Graham<sup>1</sup>, Min Chen<sup>2</sup>, Chris Vernon<sup>3</sup> Tom Wild<sup>1</sup><sup>4</sup>  Katherine Calvin<sup>1</sup>

<sup>1 </sup> Joint Global Change Research Institute (JGCRI), Pacific Northwest National Laboratory (PNNL), 5825 University Research Ct, College Park, MD 20740

<sup>2 </sup> University of Wisconsin – Madison, Forest & Wildlife Ecology, Russell Labs, 1630 Linden Drive, Madison, WI 53706

<sup>3 </sup> Pacific Northwest National Laboratory (PNNL), 902 Battelle Blvd, Richland, WA 99354

<sup>4 </sup> Earth System Science Interdisciplinary Center (ESSIC), University of Maryland, 5825 University Research Ct suite 4001, College Park, MD 20740


\* corresponding author:  zarrar.khan@pnnl.gov

## Abstract
Future sectoral-specific water withdrawals at a temporal resolution capable of representing patterns in seasonality and a commonly used spatial resolution are an important factor to consider for energy, water, land and environmental research.  Projected water withdrawals that are harmonized with assumptions for alternate futures that capture socioeconomic and climatic variation are critical for many modeling studies on future global and regional dynamics. Here we generate a novel global gridded water withdrawals dataset by coupling Global Change Analysis Model (GCAM) with a land use spatial downscaling model (Demeter), a global hydrologic framework (Xanthos) and a water withdrawal downscaling model (Tethys) for the five Shared Socioeconomic Pathways (SSPs) and four Representative Concentration Pathways (RCPs) scenarios. The dataset provides sectoral monthly data at 0.5° resolution for years 2015 to 2100. The presented dataset will be useful for both global and regional analysis looking at the impacts of socioeconomic, climate and technological futures as well as in characterizing the uncertainties associated with these impacts.

## Journal reference
To be Added.

## Code reference

- Tethys Code Reference to go here.

- Calvin, Katherine, Patel, Pralit, Clarke, Leon, Asrar, Ghassem, Bond-Lamberty, Ben, Yiyun Cui, Ryna, … Wise, Marshall. (2020, March 17). crvernon/gcam-core: gcam-v4.3.chen (Version gcam-v4.3.chen). Zenodo. http://doi.org/10.5281/zenodo.3713432

## Data reference

### Input data
- Graham N.T. et al.,(2020). GCAM v4.3 SSP-RCP-GCM Output Databases [Data set]. DataHub. https://data.pnnl.gov/dataset/13224 
- Graham N.T., M.I. Hejazi, M. Chen, E. Davies, J.A. Edmonds, S.H. Kim, and S. Turner, et al. 2020. "Humans drive future water scarcity changes across all Shared Socioeconomic Pathways." Environmental Research Letters 15, no. 1:Article No. 014007. PNNL-SA-151297. doi:10.1088/1748-9326/ab639b
- Chen, M. and C.R. Vernon (2020). GCAM-Demeter land use dataset at 0.05-degree resolution [Data set]. DataHub. https://dx.doi.org/10.25584/data.2020-07.1357/1644253

### Output data
Reference for each minted data source for your output data.  For example:
- Tethys Outputs to go here.

## Contributing modeling software
| Model | Version | Repository Link | DOI |
|-------|---------|-----------------|-----|
| Demeter | v1.chen | https://github.com/crvernon/demeter/tree/v1.chen | http://doi.org/10.5281/zenodo.3713378 |
| GCAM | gcam-v4.3.chen | https://github.com/crvernon/gcam-core/tree/gcam-v4.3.chen | http://doi.org/10.5281/zenodo.3713432 |
| component 1 | version | link to code repository | link to DOI dataset |

## Reproduce my experiment
Fill in detailed info here or link to other documentation that is a thorough walkthrough of how to use what is in this repository to reproduce your experiment.


1. Install the software components required to conduct the experiement from [Contributing modeling software](#contributing-modeling-software)
2. Download and install the supporting input data required to conduct the experiement from [Input data](#input-data)
3. Run the following scripts in the `workflow` directory to re-create this experiment:

| Script Name | Description | How to Run |
| --- | --- | --- |
| `step_one.py` | Script to run the first part of my experiment | `python3 step_one.py -f /path/to/inputdata/file_one.csv` |
| `step_two.py` | Script to run the last part of my experiment | `python3 step_two.py -o /path/to/my/outputdir` |

4. Download and unzip the output data from my experiment [Output data](#output-data)
5. Run the following scripts in the `workflow` directory to compare my outputs to those from the publication

| Script Name | Description | How to Run |
| --- | --- | --- |
| `compare.py` | Script to compare my outputs to the original | `python3 compare.py --orig /path/to/original/data.csv --new /path/to/new/data.csv` |

## Reproduce my figures
Use the scripts found in the `figures` directory to reproduce the figures used in this publication.

| Script Name | Description | How to Run |
| --- | --- | --- |
| `generate_figures.py` | Script to generate my figures | `python3 generate_figures.py -i /path/to/inputs -o /path/to/outuptdir` |
