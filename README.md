# Estimated_COVID19_by_US_Zip_Code
Estimated Covid-19 case and death counts as reported by the New York Times by County for the top Zip codes within the US

Using daily data extraced from https://github.com/nytimes/covid-19-data I am taking the county level data and estimating
case counts and death counts distributed by population concentration to the known Zip codes among the counties where the NYT
reports cases since Jan 21, 2020.  

At a high level this captures data for over 30,000 Zip codes.

The thinking here is that most people know more about their own US Zip code and much less about their County FIPS Code!

Specials thanks to Simplemaps for providing the baseline zip code mappings to FIPS code as well as population numbers at the Zip code level.  It's been built from the ground up using authoritative sources including the U.S. Postal Service™, U.S. Census Bureau, National Weather Service, American Community Survey, and the IRS.

https://simplemaps.com/data/us-zips
