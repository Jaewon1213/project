# Project Proposal

## Scientific Questions

How many ozone extreme events are contributed to stratosperic intrusion of ozone and are there seasonality in it? Also, are there regional dependecy on the events and stratospheric origin ozone around the world?

## Links to the data
I will use Copernicus Atmosphere Monitoring Service (CAMS) Reanalysis data by European Centre for Medium-Range Weather Forecasts (ECMWF). Specifically, I use 3hourly global surface level (bottom model level) ozone and stratospheric origin ozone (ozone concentration from stratosphere at surface) from 2003 to 2020 for the analyze.

Question with the data: Total storage of my data is about 25GB, and I cannot upload it in the git repository. Could you help me deal with this relatively large data? Shall I restrict spatial and temperal domain even more?

[CAMSRA description](https://www.ecmwf.int/en/research/climate-reanalysis/cams-reanalysis)

[CAMSRA data download](https://ads.atmosphere.copernicus.eu/cdsapp#!/dataset/cams-global-reanalysis-eac4?tab=form)

## Brief blueprint
First, I will display climatology and anomaly of both variables to briefly show the structure of the data. Next, based on the criteria for the extreme ozone and stratospheric ozone, I will show where are the hotspots for each variables. Finally, analyze frequency of the stratospheric ozone contributed ozone extreme events on the surface and look at seasonal and regional dependency of it.

## limitation with the data
In this data, ozone and stratrospheric ozone have different calculation within the model. stratospheric ozone does not include direct interaction with surface, but only process in the atmosphere. So, it should not be compared with ozone at surface by one to one. However, since if still give us information about how strong, where, and when the intrusion happens and we could guess from that it highly affected surface ozone level.