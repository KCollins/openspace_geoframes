# openspace_geoframes
Assets for OpenSpace to illustrate physical coordinate systems used to map interactions in the Sun/Earth system.

The source for these transforms is Appendix 3 of Kivelson and Russell's [_Introduction to Space Physics._](https://archive.org/details/introductiontosp0000unse_w5p3)

Each coordinate system is defined with two quantities: the direction of one of the axes and the orientation of the other two axes in the plane perpendicular to this direction. 

| Frame    | Full Name | Axis Definition | Plane Definition | Used In: | K&R Appendix |
| -------- | ------- |------- |------- |------- |------- |
| Geocentric Equatorial Inertial System  | GEI    | X-axis from Earth toward the first point of Ares (position of Sun at vernal equinox)| Z-axis parallel to Earth's rotation, y = x × z| Astronomy and satellite orbit calculations | A.3.3.1 |
| Geographic Coordinates | GEO  | X-axis fixed with equatorial plane at 0 degrees longitude | Z axis parallel to rotation axis of the Earth | Ground coordinates | A.3.3.2 |
| Geomagnetic Coordinates | MAG  | Z-axis parallel to magnetic dipole axis | X axis from IGRF-85: 11.018 deg colatitude, -70.905 deg E longitude | Magnetic coordinates, magnetic local time | A.3.3.3 |
