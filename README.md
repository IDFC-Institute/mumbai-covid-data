## Data from BMC's COVID-19 Response War Room Dashboard


BMC publishes daily updates in the form of 40 pages of tables, graphs and maps detailing various aspects of the COVID-19 situation in Mumbai [here](https://stopcoronavirus.mcgm.gov.in/key-updates-trends). One of the earliest references to this dashboard's availability is from early June last year on [Twitter](https://twitter.com/AshwiniBhide/status/1268604886930857985). 

As the official portal allowed access to only the most recent report, we have archived past reports from June 13, 2020 and extracted data to create time-series datasets of cases, containment, health infrastructure, etc.

[Click here](https://www.idfcinstitute.org/projects/state-capacity/covid-19-city-databases) to go to the project on IDFC Institute's website where you can find detailed posts about the datasets and relevant analyses. For queries, please reach out to harsh.pachisia@idfcinstitute.org or sridhar.ganapathy@idfcinstitute.org. 

**Note: All data provided as-is from BMC's COVID-19 response War Room Dashboard and may contain errors or be incomplete.**


### This list contains datasets extracted and published so far and will be updated as new datasets are added.


## Age-wise mortality : [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_age_wise_mortality.csv&sort=Date%2Casc&stickyColumnName=Date)

[A blog](https://www.idfcinstitute.org/blog/2021/may/covid-19-mortality-data-for-mumbai/) that provides insights on the mortality data with interactive visualisations. 

The 100+ age group, available in reports from June to September 2020 was reported as 90+ from September 2020. We have standardised it using 90+ throughout.

## Tests by type : [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_tests_by_type.csv&sort=Date%2Casc&stickyColumnName=Date)

[A blog](https://www.idfcinstitute.org/blog/2021/june/covid-19-tests-data-for-mumbai/) that provides insights on the testing data with interactive visualisations. 

This dataset contains 

* the number of daily RT-PCR tests (rounded up to thousands, available from May 28, 2020) 
* the number of daily antigen tests (rounded up to thousands, available from July 7, 2020) 
* the total number of daily tests (rounded up to thousands, with minor mismatches when compared to sum of RT-PCR and Antigen test numbers, possibly due to the rounding up)
* the total number of daily tests (available from June 2020)
* the total number of daily *positive* tests (available from June 2020)

## Cases and containment by ward : [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_containment_by_ward.csv&sort=Date%2Casc&stickyColumnName=Date)

[A blog](https://www.idfcinstitute.org/blog/2021/june/covid-19-containment-strategies-in-mumbai/) that looks at the containment strategies data in detail.

This dataset contains 
* number of cases in each ward (available from June 2020)
* number of containment zones in slums and chawls in each ward (available from June 2020)
* number of sealed buildings (micro-containment zones) in each ward (available from June 2020)
* number of sealed floors in each ward (available from **March 2021**)


## Gender and age profile of cases : [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_cases_by_age_and_gender.csv&sort=Date%2Casc&stickyColumnName=Date)

[A blog](https://www.idfcinstitute.org/blog/2021/june/covid-19-impact-variations-by-age-and-gender/) that looks at the gender and age profile of COVID-19 cases in detail.

This dataset contains 
* number of cases for each age group (available from June 2020)
* gender split of cases for each age group (percentage, available from June 2020) 

## Hospital capacity and occupancy by bed type: [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_hospital_occupancy_by_bed_type.csv&sort=Date%2Casc&stickyColumnName=Date)

[A blog](https://www.idfcinstitute.org/blog/2021/july/covid-19-bed-management-in-mumbai/) that analyses hospital bed capacity for COVID-19 patients and bed occupancy trends in Mumbai.

This dataset contains 
* Total bed capacity and occupancy - sum of DCH, DCHC and CCC2 bed counts (available from June 2020)
* DCH + DCHC bed capacity and occupancy (available from June 2020)
* CCC2 bed capacity and occupancy (available from June 2020)
* ICU, O2 and ventilator bed capacity and occupancy - ICU Beds are a subset of O2 Beds and Ventilators are a subset of ICU Beds as per note on April 18, 2021 (available from June 2020)

## Case severity and contact tracing: [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_cases_severity_and_contact_tracing.csv&sort=Date%2Casc&stickyColumnName=Date)

[A blog](https://www.idfcinstitute.org/blog/2021/august/vaccine-uptake-equity-and-covid-19/)that analyses COVID-19 case severity as vaccination progresses in Mumbai.

This dataset contains 
* Total number of cases - symptomatic, asymptomatic and critical (available from June 2020)
* Number of low and high risk contacts traced each day (available from June 2020)

## Private hospital capacity and occupancy by bed type: [View and download](https://flatgithub.com/IDFC-Institute/mumbai-covid-data?filename=data%2Fmumbai_c19_priv_hospital_occupancy_by_bed_type.csv&sort=Date%2Casc&stickyColumnName=Date)

[A blog](https://www.idfcinstitute.org/blog/2021/august/a-shortage-of-private-covid-beds-in-mumbai/) that analyses the role of private hospitals in the COVID-19 response.

This dataset contains 
* Private hospital overall bed capacity and occupancy (available from July 2020)
* Normal, ICU, O2 and ventilator bed capacity and occupancy (available from July 2020)
