# Notes on BC Data Vis Challenge




## Useful links:

  * [The suggested data sets](https://github.com/bcgov/housing-data-visualization-project/blob/master/data-sets-list.md)
  * [The Challenge Overview](http://bcic.ca/wp-content/uploads/2016/12/Data-Visualiation-Challenge-Overview.pdf)
  * [Our Letter of Intent](https://docs.google.com/document/d/1tix5g2nCKlqDX8YXevZBIUNOA55Hhq7xYyri_y07BCA/edit)
  
## Some thoughts

The app should obviously have some drill-down capabilities, where users can see overall trends, then zoom-in to reveal detailed information for specific region(s). However, as Figure \@ref(fig:regions) shows, there are many types of regions!

<div class="figure" style="text-align: center">
<img src="regions.png" alt="Different types of regions available in the forecast of households." width="337" />
<p class="caption">(\#fig:regions)Different types of regions available in the forecast of households.</p>
</div>

Eventually it may be useful to alter the type of region(s), but for now, it seems "regional districts" is the best default type. 

## Suggested data by region

This is a list of the [suggested data](https://github.com/bcgov/housing-data-visualization-project/blob/master/data-sets-list.md), with additional information about granularity (w.r.t. geography and time) and links to the (possibly cleaned) data.

#### BC Stats

* [Population Estimates](http://www.bcstats.gov.bc.ca/StatisticsBySubject/Demography/PopulationEstimates.aspx) ([sample](data/population.csv))
    * yearly/quarterly for all of BC, yearly for any type of region by sex and age group
* [Population Projections](http://www.bcstats.gov.bc.ca/StatisticsBySubject/Demography/PopulationProjections.aspx) ([sample](data/population-projections.csv))
    * Same as for population estimates
* [Households](http://www.bcstats.gov.bc.ca/StatisticsBySubject/Demography/Households.aspx) ([sample](data/households.csv))
  * yearly for any type of region

#### DataBC Catalogue

* [DataBC Catalogue](https://catalogue.data.gov.bc.ca/dataset?download_audience=Public)

* [Property Transfer Tax data](https://catalogue.data.gov.bc.ca/dataset/property-transfer-tax-data)

#### City of Vancouver 

- [City of Vancouver Open Data catalogue](http://vancouver.ca/your-government/open-data-catalogue.aspx)

#### Teranet & National Bank of Canada

- [Teranet - National Bank National Composite House Price Index ™](http://www.housepriceindex.ca/)

#### TransLink

- [SkyTrain: travel times between stations](http://www.translink.ca/site-info/document-library-result.aspx?id={0F4E7466-A7AB-4D17-8241-D9D01C23EE9A}|{72FCB85B-D728-4710-BF91-C4F8D308107E}|{B11A2FC3-956F-403F-8FCC-2F1F9D44EE1A}&ref={FFCD8EFA-A8B3-47FA-97D3-4523903C5195})

#### Statistics Canada

- [2011 Census of Canada: Topic-based tabulations](http://www12.statcan.gc.ca/census-recensement/2011/dp-pd/tbt-tt/Index-eng.cfm)

- [2011 National Household Survey: Data tables](http://www12.statcan.gc.ca/nhs-enm/2011/dp-pd/dt-td/Index-eng.cfm)

   - [Income and Housing](http://www12.statcan.gc.ca/nhs-enm/2011/dp-pd/dt-td/Lp-eng.cfm?LANG=E&APATH=3&DETAIL=0&DIM=0&FL=A&FREE=0&GC=0&GID=0&GK=0&GRP=0&PID=0&PRID=0&PTYPE=105277&S=0&SHOWALL=0&SUB=0&Temporal=2013&THEME=98&VID=0&VNAMEE=&VNAMEF=)
       - A variety of data tables are available, each summarizing different dimensions of housing and income-related data

   - [Commuting to work](http://www12.statcan.gc.ca/nhs-enm/2011/as-sa/99-012-x/99-012-x2011003_1-eng.cfm)
   
      - [Journey to Work Reference Guide](https://www12.statcan.gc.ca/nhs-enm/2011/ref/guides/99-012-x/99-012-x2011008-eng.cfm)

- [Residential and Non-Residential Property Assessment Values](http://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=318595)

- [Tables by subject: Residential construction](http://www.statcan.gc.ca/tables-tableaux/sum-som/l01/ind01/l3_2162_2166-eng.htm?hili_cpis04)

   - [Building permits, values by activity sector](http://www5.statcan.gc.ca/cansim/a26?lang=eng&retrLang=eng&id=0260003&&pattern=&stByVal=1&p1=1&p2=37&tabMode=dataTable&csid=)
   
   - [Housing starts, by province](http://www.statcan.gc.ca/tables-tableaux/sum-som/l01/cst01/manuf05-eng.htm)

   - [New Housing Price Index (NHPI)](http://www.statcan.gc.ca/tables-tableaux/sum-som/l01/cst01/manuf12-eng.htm)


### Geography

#### ParcelMap BC

- [ParcelMap BC Parcel Fabric](https://catalogue.data.gov.bc.ca/pt_BR/dataset/parcelmap-bc-parcel-fabric) at DataBC Catalogue

   - [ParcelMap BC at BC Land Titles & Survey Authority](https://ltsa.ca/online-services/parcelmap-bc)

   - [parcelMap BC at International Cadastral Information Society (ICIS)](http://www.icisociety.ca/parcelmap-bc/parcelmap-bc/)



