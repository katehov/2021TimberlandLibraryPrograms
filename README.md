# 2021TimberlandLibraryPrograms
These datasets combine the Timberland Regional Library System's 2021 data on programs and cardholder ages. The intended audience is local and state policymakers, as well as library staff. The datasets were curated for a class on Data Curation at the University of Washington in Winter 2022. 


# Naming Convention
Dataset file naming should be as follows:  datasettype_yearDescription

Where datasettype indicates whether it is the raw data (raw) or the normalized data (normalized)

Where year is the year the data was collected

And where description is the short content description of the dataset. Descriptions include public program data (Programs) and active cardholder age date (ActiveCardholdersbyAge)

# Data Dictionary
| Variable  |  Variable Label      | Variable Type     |  Description       |
| --------- | ------------- |------------- |------------- |
| Library     | Library | String  | The name of the library branch hosting the program or the cardholder's primary branch. Events that were hosted online (not associated with a specific branch) are listed as "TRL ONLINE VIRTUAL."   |
| Event Month      | Month | Integer |The calendar month in which the event(s) took place. The data is entered as an integer to make chronological sorting easier, with 1 = January, 2 = February, 3 = March, etc.  |
| Category      | Category  | String | The type or focus of the event.   |
| Target Age Group     | Audience  | String  | The patron age group(s) the event was advertised to and/or aimed at.   |
| Number of Events     | Events| String | Number of events that month which fit the category, audience, and branch requirements in that row.  |
| Attendance      | Attendance  | Content Cell  | The recorded attendance at program events. Any event that did not have an attendance number listed is marked with an X.   |
| Number of Active Cardholders in Target Age Group     | ActiveCardholders  | Integer  | This is the number of Active Cardholders listed at the event branch in the target age group. |
| Age Group     | Age | Integer  | Age groups of individual active cardholders in 2021. The children and teens age groups were based on the age groups listed in the original programs dataset (Audience column).   |
| Number of Active Cardholders    | Cardholders  | Integer | The number of active cardholders at that branch in that age group during 2021 when the original dataset was created.   |

# Metadata
| Attribute     |  Value        |
| ------------- | ------------- |
| accessLevel   | Public |
| license       | Public Domain  |
| contactPoint  | Kate Hovda kmhovda@uw.edu |
| description   | These datasets combine the Timberland Regional Library System's 2021 programming and cardholder age datasets. The intended audience is local and state policymakers, as well as Timberland library staff. The datasets were curated for a class on Data Curation at the University of Washington in Winter 2022.  |
| downloadURL   | https://github.com/katehov/2021TimberlandLibraryPrograms/archive/refs/heads/main.zip  |
| format        | .CSV  |
| mediaType     | .CSV  |
| issued        | 2022-03-09  |
| keyword       | "public library", "timberland regional library system", "washington state libraries", "washington", "library events", "library programs" "timberland programs", "timberland libraries", "washington state" |
| landingPage   | https://data.wa.gov/d/yqsf-acee |
| language      | en-US  |
| modified      | 2022-03-09 |
| publisher     | Kate Hovda  |
| references    | https://catalog.data.gov/dataset/timberland-regional-library-active-cardholders-by-age https://catalog.data.gov/dataset/timberland-regional-library-programs |
| rights        | These data are freely availabe to the public, both in this repository and their original government repository |
| spatial       | Washington State, USA  |
| theme         | library programs, library cardholders, library use |
| title         | 2021 Timberland Library Programs  |

# License
These data are freely available for public use.

# Contact
Kate Hovda kmhovda@uw.edu
