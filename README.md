# 3DskyMap

## Description

3-D model of the distribution of all the stars in the Yale Bright Star Catalog. Here are the steps in the project:

- Read the Yale Bright Star Catalog and create a Pandas data frame object.

- Drop all objects that do not have a trigonometric parallax.

- Create a column called Distance that has the distance of the object in parsec. Remember that the inverse of the parallax in arc_seconds is the distance in parsec.

- Use the RA and Dec for the J2000.0 epoch for the next set of computations.
 
- Create three columns x, y, and z that will have the distances to the stars in parsecs in the equatorial frame of reference.

- Write a routine that will do a coordinate transformation from a spherical coordinate system to a Cartesian system.
  
- In this Cartesian system, the x-axis is pointing to the vernal equinox and the x-y plane is the plane of the celestial equator. The z-axis should be pointing to the north celestial pole. You can use the library Astropy for your work.
  
- Create a column called Color in your data frame. The colors could be named colors like red or blue. Or, the colors could be in hexadecimal format. Here is the color scheme according to spectral types - O (deepest blue), B (medium blue), A (light blue), F (green), G (yellow), K (orange), M (red), and any other star not having a spectral type black.
  
- Use Plotly to obtain the 3-D distribution of the stars.

- The stars should be color-coded.

- If you hover over a star, you should get the following information - HR Number, Distance in parsec, and Radial Velocity in km/s.  
