## Data from BMC's COVID-19 Response War Room Dashboard


BMC publishes daily updates in the form of 40 pages of tables, graphs and maps detailing various aspects of the COVID-19 situation in Mumbai [here](https://stopcoronavirus.mcgm.gov.in/key-updates-trends). One of the earliest references to this dashboard's availability is from early June last year on [Twitter](https://twitter.com/AshwiniBhide/status/1268604886930857985). 

As the official portal allowed access to only the most recent report, we have archived past reports from June 13, 2020 and extracted data to create time-series datasets of cases, containment, health infrastructure, etc.

[Click here](https://www.idfcinstitute.org/projects/state-capacity/covid-19-city-databases) to go to the project on IDFC Institute's website where you can find detailed posts about the datasets and relevant analyses.

Note: All data provided as-is from BMC's COVID-19 response War Room Dashboard and may contain errors or be incomplete. 

### This list contains datasets extracted and published so far and will be updated as new datasets are added.


## Age-wise mortality : [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_age_wise_mortality.csv&sort=Date%2Casc&stickyColumnName=Date)

The 100+ age group, available in reports from June to September 2020 was reported as 90+ from September 2020. We have standardised it using 90+ throughout.

## Tests by type : [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_tests_by_type.csv&sort=Date%2Casc&stickyColumnName=Date)

This dataset contains 

* the number of daily RT-PCR tests (rounded up to thousands, available from May 28, 2020) 
* the number of daily antigen tests (rounded up to thousands, available from July 7, 2020) 
* the total number of daily tests (rounded up to thousands, with minor mismatches when compared to sum of RT-PCR and Antigen test numbers, possibly due to the rounding up)
* the total number of daily tests
* the total number of daily *positive* tests
