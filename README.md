# Scripts and Data summary
- Source codes for analyses used in **Kino et al. (2021, JGR) https://doi.org/10.1029/2021JD035397**
- Data (\*.npz and \*.nc) are available on https://doi.org/10.5281/zenodo.4733445

## Figure 1
- [Figure 1](Ant_proxy_DF2003.png)

### Script
- [Ant_proxy_DF2003.ipynb](Ant_proxy_DF2003.ipynb)
- [Ant_proxy_DF2003.html](Ant_proxy_DF2003.html)

### Inputs
- T2.npz
- prcp.npz
- prcp_d18O.npz

### Additional Data
- obs_DomeF.csv ([Fujita & Abe, 2006, GRL](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2006GL026936))

## Figures 2 and 3, and Tables S1, S2 and S3
- [Figure 2](correlation_spearman.png)
- [Figure 3](std.png)
- [Table S1](correlation.html#Table-S1)
- [Table S2](correlation.html#Table-S2)
- [Table S3](correlation.html#Table-S3)

### Script
- [correlation.ipynb](correlation.ipynb)
- [correlation.html](correlation.html)

### Inputs
- T2_anom.npz
- prcp.npz
- prcp_d18O_anom.npz
- sam.npz
- sam_jra25.npz

### Additional Data
- obs_DomeF.csv ([Fujita & Abe, 2006, GRL](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2006GL026936))

## Figures 4 and S7
- [Figure 4](z500_patterns.png)
- [Figure S7](z500_events.png)

### Script
- [z500_patterns.ipynb](z500_patterns.ipynb)
- [z500_patterns.html](z500_patterns.html)

### Inputs
- z500_anom.npz
- prcp_d18O_index.npz
- sam_pattern.npz

## Figure 5 and Figure S6
- [Figure 5](composite_moisture_JJA.png)
- [Figure S6](clm_moisture.png)

### Script
- [composite_moisture_JJA.ipynb](composite_moisture_JJA.ipynb)
- [composite_moisture_JJA.html](composite_moisture_JJA.html)

### Inputs
- sam.npz
- prcp_d18O_index.npz
- precw.npz
- vprecw.npz
- precw_d18O.npz

## Figure 6
- [Figure 6](Ant_DF1981-2010.png)

### Script
- [Ant_DF1981-2010.ipynb](Ant_DF1981-2010.ipynb)
- [Ant_DF1981-2010.html](Ant_DF1981-2010.html)

### Inputs
- prcp_d18O_anom.npz
- sammon.npz
- sam.npz

## Figure 7
- [Figure 7](composite_2DAnt_JJA.png)

### Script
- [composite_2DAnt_JJA.ipynb](composite_2DAnt_JJA.ipynb)
- [composite_2DAnt_JJA.html](composite_2DAnt_JJA.html)

### Inputs
- sam.npz
- T2_anom.npz
- prcp_d18O_anom.npz
- prcp.npz

## Figure 8
- [Figure 8](composite_DomeF_JJA.png)

### Script
- [composite_DomeF_JJA.ipynb](composite_DomeF_JJA.ipynb)
- [composite_DomeF_JJA.html](composite_DomeF_JJA.html)

### Inputs
- sam.npz
- T2_anom.npz
- prcp_d18O_anom.npz
- prcp.npz

## Figure S1
- [Figure S1](global_model-data_comparison.png)

### Script
- [global_model-data_comparison.ipynb](global_model-data_comparison.ipynb)
- [global_model-data_comparison.html](global_model-data_comparison.html)

### Inputs
- [jra25.gndg_miroc5-iso_last30yrs_timmean.iso.nc](jra25.gndg_miroc5-iso_last30yrs_timmean.iso.nc)
- [jra25.gndg_miroc5-iso_last30yrs_yseasmean.iso.nc](jra25.gndg_miroc5-iso_last30yrs_yseasmean.iso.nc)

### Additional Data
- GNIP_world_2010_timemean_TPd18oD_12mon.csv
- SISALv1b_d18O_carb_MH_anom_20190402.csv
- IceCores_6k_PI.csv
- ERA40.1961.1990.t2m.stl1.stl4.timmean.nc

## Figure S2, S3, and S4
- [Figure S2](Ant_proxy_DC2008.png)
- [Figure S3](Ant_proxy_DC2009.png)
- [Figure S4](Ant_proxy_DC2010.png)

### Script
- [Ant_proxy_DC2008-2010.ipynb](Ant_proxy_DC2008-2010.ipynb)
- [Ant_proxy_DC2008-2010.html](Ant_proxy_DC2008-2010.html)

### Inputs
- T2.npz
- prcp.npz
- prcp_d18O.npz

### Additional Data
- obs_DomeC.csv ([Stenni et al., 2016, Cry.](https://doi.org/10.5194/tc-10-2415-2016))

## Figure S5
- [Figure S5](monthly_reconst.png)

### Script
- [monthly_clm_DF.ipynb](monthly_clm_DF.ipynb)
- [monthly_clm_DF.html](monthly_clm_DF.html)

### Inputs
- T2.npz
- prcp_d18O.npz
- prcp.npz

###
# References for Additional Data
- Atsawawaranunt, Kamolphat, Harrison, Sandy and Comas-Bru, Laia (2019): SISAL (Speleothem Isotopes Synthesis and AnaLysis Working Group) database version 1b. University of Reading. Dataset. http://dx.doi.org/10.17864/1947.189
- Cauquoin, A., Werner, M., & Lohmann, G. (2019). Water isotopes ??? climate relationships for the mid-Holocene and preindustrial period simulated with an isotope-enabled version of MPI-ESM. Climate of the Past, 15(6), 1913???1937. https://doi.org/10.5194/cp-15-1913-2019
- Fujita, K., & Abe, O. (2006). Stable isotopes in daily precipitation at Dome Fuji, East Antarctica. Geophysical Research Letters, 33(18). https://doi.org/10.1029/2006GL026936
- IAEA/WMO. (2018). GNIP. Global Network for Isotopes in Precipitation [Data set]. IAEA: International Atomic Energy Agency/World Meteorological Organization. Retrieved from https://nucleus.iaea.org/wiser
- K??llberg, P., Simmons, A., Uppala, S., & Fuentes, M. (2004). The ERA-40 archive.[Revised October 2007], Shinfield Park. Reading, (17). Retrieved from https://www.ecmwf.int/node/10595
- Onogi, K., Tsutsui, J., Koide, H., Sakamoto, M., Kobayashi, S., Hatsushika, H., et al. (2007). The JRA-25 Reanalysis. Journal of the Meteorological Society of Japan. Ser. II, 85(3), 369???432. https://doi.org/10.2151/jmsj.85.369
- Stenni, B., Scarchilli, C., Masson-Delmotte, V., Schlosser, E., Ciardini, V., Dreossi, G., et al. (2016). Three-year monitoring of stable isotopes of precipitation at Concordia Station, East Antarctica. The Cryosphere, 10(5), 2415???2428. https://doi.org/10.5194/tc-10-2415-2016

Kanon Kino (kanon[at]aori.u-tokyo.ac.jp)
