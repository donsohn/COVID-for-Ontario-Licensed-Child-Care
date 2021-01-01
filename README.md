# COVID for Toronto Licensed Child Care

Under construction

Whether you're a parent, caregiver, or other interested party; COVID is likely a factor in your decision whether or not to send your child to child care.

Using Python I will attempt to build some visualizations using this data as the foundation but more specifically for Toronto region.

Please do not accept these visualizations as the final truth, but rather as a tool to aid you in further research, to ultimately make your own informed decision.

As at 2020/12/30:

![](barchart.jpeg?raw=true)

Year to Date 2020/12/30:
(Note: Interactive map in the Jupyter Notebook using ArcGIS)

![](map.jpeg?raw=true)

### Data Sources

Ontario COVID cases in Licensed Childcare Centres:<br>
https://data.ontario.ca/dataset/5bf54477-6147-413f-bab0-312f06fcb388/resource/eee282d3-01e6-43ac-9159-4ba694757aea/download/lccactivecovid.csv

Toronto Licensed Childcare Centres (for addresses + longitude/latitude coordinates):<br>
https://data.ontario.ca/dataset/5bf54477-6147-413f-bab0-312f06fcb388/resource/eee282d3-01e6-43ac-9159-4ba694757aea/download/lccactivecovid.csv

### Roadmap

- multiple records of same LCC name in Toronto LCC data
- mismatch of LCC name between Ontario COVID LCC data and Toronto LCC data; unfortunately there is no other unique identifier/key
- finding limit of 1000+ locations can be mapped on ArcGIS - need to investigate this further
- work on adding a "slider" that changes the date reported on the map
