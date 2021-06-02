## COVID-19 data extracted from BMC's COVID-19 Response War Room Dashboard


BMC publishes daily updates in the form of 40 pages of tables, graphs and maps detailing various aspects of the COVID-19 situation in Mumbai [here](https://stopcoronavirus.mcgm.gov.in/key-updates-trends). One of the earliest references to this dashboard's availability is from early June last year on [Twitter](https://twitter.com/AshwiniBhide/status/1268604886930857985). 

As the official portal allowed access to only the most recent report, we have archived past reports from June 13, 2020 and extracted data to create time-series datasets of cases, containment, health infrastructure, etc.

[Click here](https://www.idfcinstitute.org/projects/state-capacity/covid-19-city-databases) to go to the project on IDFC Institute's website where you can find detailed posts about the datasets and relevant analyses.

### This list contains datasets extracted and published so far and will be updated as new datasets are added.


## Age-wise mortality : [View/download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data/blob/main/data/mumbai_c19_age_wise_mortality.csv)

The 100+ age group, available in reports from June to September 2020 was reported as 90+ from September 2020. We have standardised it using 90+ throughout.

## Tests by type : [View/download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data/blob/main/data/mumbai_c19_tests_by_type.csv)

This dataset contains 

* the number of daily RT-PCR tests (rounded up to 100s) 
* the number of daily antigen tests (rounded up to 100s, available from July 7, 2020) 
* the total number of daily tests (rounded up to 100s, with minor mismatches when compared to RT-PCR + Antigen, possibly due to the rounding up)
* the total number of daily tests
* the total number of daily *positive* tests
