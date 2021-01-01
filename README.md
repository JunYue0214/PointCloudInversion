# PointCloudInversion

C++ codes for "**Point Cloud Inversion: A Novel Approach for the Localization of Trees in Forests from TLS Data**" will be released soon after the publication.

This paper proposes a fast and easy-to-use method (Point Cloud Inversion, PCI) for localizing trees in TLS point clouds. The input for PCI is the raw point clouds and no other pre-processing steps (e.g., ground filtering, PCA-based features, noise-removal) are needed. The experimental results in the TLS-forest benchmark without (Original) and with (Enhanced) PCI are shown as follows,
<img src="https://github.com/GeoVectorMatrix/PointCloudInversion/blob/main/Images/ComCor.png" width="1400" height="350"/><br/>

Furthermore, PCI can also be treated as a plug-in module in data processing and may benefit other object localization tasks, such as extracting pole-like objects in urban areas.
