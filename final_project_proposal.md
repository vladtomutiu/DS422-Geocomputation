# DS 422 Geocomputation – Final Project Proposal

**Name: Vlad Tomutiu**

**Date: 11/17/2026**

------------------------------------------------------------------------

Fill this out before you start on your analysis. Write your answers under each question. A few sentences is fine for most of them. Be specific, though: "I'll look at land use" is too vague, but "I'll compare sugar land change across Maui from 2001 to 2021" is better.

Download this file and add it to your DS422 Repository, then edit right in the github browser.

------------------------------------------------------------------------

## 1. My research question

What do you want to find out? Phrase it as a question. Mention the place and time period if they are relevant.

**Do lower-income neighborhoods in San Francisco and Alameda County have better or worse access to transit and to jobs by transit than higher-income neighborhoods?**

------------------------------------------------------------------------

## 2. The dataset(s) I will use to approach my research question

List each dataset and where it comes from (agency, website, link). Note the format (shapefile, raster, CSV with coordinates, etc.) and the spatial and temporal coverage if you know it.

-   **American Community Survey (ACS) 5-year estimates: median household income and population**

-   **Census tract boundaries**

-   **LEHD Origin-Destination Employment Statistics (LODES), WAC table: jobs by workplace**

-   **Transit schedules (GTFS) for Muni, BART, and AC Transit**

-    **OpenStreetMap street network extract**

------------------------------------------------------------------------

## 3. The specific geocomputation techniques I will use to answer my research question

What methods will you actually run? For example, image segmentation, spatial statistics, time series analysis etc.

-   **Cartographic visualization**

-   **Statistical comparison**

-   **Spatial data preparation and joins**

-   **Network-based transit routing and accessibility analysis**

-   **Walking-distance service areas (isochrones)**

------------------------------------------------------------------------

## 4. 3-5 peer-reviewed publications or news articles surrounding my research question

Give the link below. Add a sentence or two on why each source is relevant to your project.

1.  **Alam, M. S., & Alam, B. M. (2026). “In(equity) in accessibility to low-wage jobs by public transit in the fifteen largest cities in the United States.” *Cities*, Vol. 176.**\
    [trid.trb.org/View/2706623](https://trid.trb.org/View/2706623)\
    This article gives information on transit job access for census tracts with a cumulative-opportunity method and compares it across household income and other vulnerability factors. It includes San Jose, which is in the bay area and close to the area my research question is in.

2.  **TransitCenter. “The San Francisco-Oakland Story” (Transit Equity Dashboard).**\
    [dashboard.transitcenter.org/story/sf](https://dashboard.transitcenter.org/story/sf)\
    Study that shows that Black, Asian, and other BIPOC residents have less access to jobs and services than white residents, and that the average resident can reach far more jobs by car than by transit within 45 minutes.

3.  **Pereira, R. H. M., Saraiva, M., Herszenhut, D., Braga, C. K. V., & Conway, M. W. (2021). “r5r: Rapid Realistic Routing on Multimodal Transport Networks with R5 in R.” *Findings*.**\
    [doi.org/10.32866/001c.21262](https://doi.org/10.32866/001c.21262) (package intro: [r5r vignette](https://ftp.fau.de/cran/web/packages/r5r/vignettes/r5r.html))\
    Paper that explains the use of the r5r package. It explains how to compute travel-time matrices and accessibility to opportunities from GTFS and OpenStreetMap data.

4.  **Streetsblog California (June 17, 2021). “Report: Here’s where people of color can’t access opportunity without a car.”**\
    [cal.streetsblog.org/2021/06/17/report-heres-where-people-of-color-cant-access-opportunity-without-a-car](https://cal.streetsblog.org/2021/06/17/report-heres-where-people-of-color-cant-access-opportunity-without-a-car)\
    This news article covers the TransitCenter equity findings for the Bay Area and other regions. Has some good visualizations

------------------------------------------------------------------------
