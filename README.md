# 1 closest neighbour matches between the BDBS and VVV surveys 
- ra, dec: each individual file contains the (ra, dec) of all the bdbs sources in the tile
- ra_vvv, dec_vvv: are the coordinates of the closest VVV match
- sep2d_arcsec: is the angular separation in arcseconds
- ejk: E(J-K) as in Simion et al. 2017; Ak = 0.482 x ejk and Aj = 1.351 x ejk
- Jmag, Ksmag: VVV magnitudes not corrected for extinction
- err_j, err_k: photometric errors for the Jmag and Ksmag

-----------------------------
Note: to find the matches, I recommend sep2d_arcsec < 1''. \\

In the crowded fields notice that sep2d_arcsec can be of the order of a degree or several degrees

