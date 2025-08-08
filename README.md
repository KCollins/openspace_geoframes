# openspace_geoframes
Assets for OpenSpace to illustrate physical coordinate systems used to map interactions in the Sun/Earth system.

The source for these transforms is Appendix 3 of Kivelson and Russell's [_Introduction to Space Physics._](https://archive.org/details/introductiontosp0000unse_w5p3)

Each coordinate system is defined with two quantities: the direction of one of the axes and the orientation of the other two axes in the plane perpendicular to this direction. 

| Frame    | Full Name | Axis Definition | Plane Definition | Used In: | K&R Appendix |
| -------- | ------- |------- |------- |------- |------- |
| Geocentric Equatorial Inertial System  | GEI    | X-axis from Earth toward the first point of Ares (position of Sun at vernal equinox)| Z-axis parallel to Earth's rotation, y = x × z| Astronomy and satellite orbit calculations | A.3.3.1 |
| Geographic Coordinates | GEO  | X-axis fixed with equatorial plane at 0 degrees longitude | Z axis parallel to rotation axis of the Earth | Ground coordinates | A.3.3.2 |
| Geomagnetic Coordinates | MAG  | Z-axis parallel to magnetic dipole axis — (0.06252,-0.18060, 0.98157) in geographic coordinates | X axis from IGRF-85: 11.018 deg colatitude, -70.905 deg E longitude. Y axis is perpendicular to geographic poles | Magnetic coordinates, magnetic local time | A.3.3.3 |
| Geocentric Solar Ecliptic | GSE  | X-axis pointing from Earth to Sun | Y-axis in ecliptic plane pointing toward dusk (opposing planetary motion); z-axis parallel to ecliptic pole | Interplanetary magnetic field, solar wind velocity data | A.3.3.4 |
| Geocentric Solar Equatorial | GSEQ  | X-axis pointing from Earth to Sun | Y-axis parallel to the sun's equatorial plane (which is inclined to the ecliptic) | Interplanetary magnetic field data | A.3.3.5 |
| Geocentric Solar Magnetospheric | GSM  | X-axis pointing from Earth to Sun | Y-axis perpendicular to Earth's magnetic dipole, so that the x-z plane contains the dipole axis; Z-axis in same sense as Earth's magnetic pole | Magnetospheric stuff | A.3.3.6 |
