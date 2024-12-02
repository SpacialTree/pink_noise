# Code for comparing various 1/f removal methods for JWST observations

1/f noise, also known as pink noise, is an issue affecting infrared detectors where stripes appear across the outputted images. 

In an effort to find the best removal strategy for pink noise for Cloud c JWST 2221 NIRCam data. This data was observed toward the Galactic Center dust ridge, a zone with high stellar density and complex extended structure in emission and extinction. Of the strategies tested, only Massimo Robberto's (private communication) destriping method, with adjustments made to add back extended structure, was the most effective. 

See `notebooks/compare_residuals.ipynb` for a full comparison between strategies. 

See also [NIRCam 1/f Noise Removal Methods](https://jwst-docs.stsci.edu/known-issues-with-jwst-data/nircam-known-issues/nircam-1-f-noise-removal-methods#gsc.tab=0) from JDocs. 

