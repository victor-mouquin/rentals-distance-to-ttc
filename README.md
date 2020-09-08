# rentals-distance-to-ttc
Effect of the distance to the closest TTC station on the rent in Toronto


Using the Python library beautiful soup I scrapped rental ads from the Kijiji Toronto website. Using the Google Maps API I computed for every ad in the database the walking time to the closest TTC station. I then used basic linear regression to analyse the effect of the walking time to the closest TTC station on the rent. 

The main conclusion is that being close to a TTC station indeed raise the price of rent. 
