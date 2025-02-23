# dui_co_gazette
Deaths in impaired driving incidents rose 41% in Colorado from 2013 to 2023 while arrests/case filings dropped by about 30% in that same time period.

# Data file paths:
- DOT: Contains impaired driving fatality reports and archive according to the Colorado Department of Transportation.
- Statewide: Has data and information on impaired driving cases in Colorado courts besides Denver. Denver has a separate system and required merging and cleaning to get the databases to talk to each other.
- CBI: Colorado arrest data, as reported by each agency to the Colorado Bureau of Investigation.
- FBI: Tally of law enforcement employees as reported by each law enforcement agency to the bureau.

# Mapping:
I converted the ArcGIS map to GeoJSON to map in DataMapper using EsriDump. Hat tip to Cody Winchster for the advice. 

https://colab.research.google.com/drive/1GgKBJ9QJcqEQRmHCr72oGDOxutqA-QET?usp=sharing&authuser=1#scrollTo=vTPa8x4BxYD-
Documentation: https://github.com/openaddresses/pyesridump
