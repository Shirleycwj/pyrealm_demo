# pyrealm_demo

This repository included three demostration of how Pyrealm (python) package works on different spatial and temporal scales. The Pyrealm package is developed for the P model, an vegetation production model (Wang et al., 2017; Stocker et al., 2020) based on eco-evolutionary optimality (EEO) principle (Harrison et al., 2021). It has previously been tested on site and global scale against FLUXNET2015 and state-of-the-art TRENDY models (Cai and Prentice, 2020), and further a subdaily version (Mongoli et al., 2022) was developed to account for the fast and slow acclimation of photosynthesis within a day. 

### Demo1
This demo adopted the standard P model based on Stocker et al. (2020), with daily data extracted from FLUXNET2015 dataset. The effect of soil moisture was additionally considered using SPLASH model v1 (Davis et al., 2017).

### Demo2
This demo used subdaily setting which assumed vegetation acclimated to noon-time condition. A 1-hour wide window was therefore set at noon. Hourly data also from FLUXNET2015 was applied to this demo, and soil moisture effect from demo 1 were applied to daily GPP which was summed from subdaily hourly GPP.

Both demo used data from same example site so audience would be able to compare daily GPP from daily/subdaily version of P model against site observations. For demo example data, please download from Figshare: https://figshare.com/s/a1d2c1a91b6f8b507a38.

For the source code of Pyrealm, please refer to https://github.com/ImperialCollegeLondon/pyrealm. If you have further questions regarding the setting of these damos, please contact Wenjia Cai (w.cai17@imperial.ac.uk).

