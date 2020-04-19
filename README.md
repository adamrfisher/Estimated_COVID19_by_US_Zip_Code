# Estimated_COVID19_by_US_Zip_Code
Estimated Covid-19 case and death counts as reported by the New York Times by County for the top Zip Codes within the US

Using daily data extraced from https://github.com/nytimes/covid-19-data I am taking the county level data and estimating
case counts and death counts distributed by population concentration to the known zip codes among the counties where the NYT
reports at least 1,000 cases on any day since Jan 21, 2020.  

At a high level this captures data for over 30,000 Zip codes.

The thinking here is that most people know there US Zip Code and not their County FIPS Code!

Specials thanks to Simplemaps for providing the baselie zip code mappings to FIPS code as well as population numbers at the zip code level.  It's been built from the ground up using authoritative sources including the U.S. Postal Service™, U.S. Census Bureau, National Weather Service, American Community Survey, and the IRS.

https://simplemaps.com/data/us-zips
