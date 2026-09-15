# Seemon Kumawat

Spatial scientist working on remote sensing of invasive grasses in northern
Australian savannas. Master of Applied Spatial Science, Charles Darwin
University.

My research assistant work asks how well different platforms actually detect
Gamba Grass and Buffel Grass, two of the highest-priority invasive species in
the Northern Territory: UAV, LiDAR, Sentinel-2, Landsat and airborne imagery,
weighed against each other on spatial resolution, revisit frequency and cost.
It is a question with consequences, because these grasses change fuel loads and
fire behaviour across the Top End, so how accurately you can map them shapes how
the country is managed.

I work across the whole pipeline: field GPS collection and ground-truthing at
one end, supervised and unsupervised classification with accuracy assessment in
the middle, finished cartography at the other.

## Projects

**[savanna-burn-mapper](https://github.com/seemonkumawat1234-arch/savanna-burn-mapper)**
Burnt-area and severity mapping from Sentinel-2 using dNBR, with severity
breakpoints adjusted for savanna, where fast surface grass fires register far
lower than the forest fires the standard USGS table was derived from.

**[savanna-fire-history](https://github.com/seemonkumawat1234-arch/savanna-fire-history)**
Fire regime metrics from annual fire-scar rasters: frequency, return interval,
time since last fire, and the early versus late dry-season split that savanna
fire management under the ACCU Scheme actually turns on.

**[sentinel2-landcover](https://github.com/seemonkumawat1234-arch/sentinel2-landcover)**
Land cover classification with a random forest and k-means, using a
spatial-block train/test split. Splitting by random pixel over autocorrelated
imagery puts near-duplicate ground on both sides and inflates the reported
accuracy, which is why so many classifications claim the high nineties.

All three are CPU only, run on an ordinary laptop with no GPU and no cloud
account, and ship with tests that assert domain behaviour rather than just that
the code returns. Each includes a synthetic data generator so the test suite and
the demo run with nothing to download, and every synthetic output is labelled as
such, down to a tag in the GeoTIFF metadata.

## Tools

Remote sensing and GIS: ArcGIS Pro, QGIS, Google Earth Engine, Sentinel-2,
Landsat
Analysis: Python (rasterio, GeoPandas, scikit-learn, NumPy), R, Stata
Methods: image classification, accuracy assessment, change detection, spatial
analysis, terrain and hydrological analysis, thematic cartography

## Interests

Environmental monitoring and natural resource management, Earth observation,
savanna fire regimes, invasive species mapping, and work grounded in northern
Australian landscapes.

## Contact

[LinkedIn](https://www.linkedin.com/in/seemonkumawat/) ·
Seemonkumawat1234@gmail.com
