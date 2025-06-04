# OBIA-RF
# code for performingland cove classification using python orfeo toolbox

Before using this code, it is advisable to learn the basic of orfeo toolbox algorithm, concept in Object Based Image Classification(OBIA), machine learning and satellite image
OBIA: https://doi.org/10.1016/j.jag.2020.102263 ; https://doi.org/10.1016/j.isprsjprs.2017.06.001 ; https://doi.org/10.3390/rs14030646 ; https://doi.org/10.1186/s40965-017-0031-6
OTB: https://github.com/orfeotoolbox/OTB
python OTB: https://github.com/orfeotoolbox/pyotb

The Raw input dataset has been pre-processed for radiometric calibration (TOA-BOA) spatial co-registration and radiometric normalization. This step is crucial for time series analysis and change detection. the Norm input was surface reflectance normalize to 0-1 and added 4 spectral indices (NDVI, NDWI, BU2 and ISU)
Please refer to: https://doi.org/10.3390/rs9070676 ; https://doi.org/10.1016/j.compag.2019.104893 ; https://doi.org/10.1016/j.jag.2020.102290
if you use multitemporal image, please co-register the spatial geolocation using:https://github.com/GFZ/arosics/tree/main/docs. 
if you use multisensor image, please normalize the spectral radiometry using: https://github.com/latmperkmol/ts-norm; https://github.com/swegmueller/LORACCS_Mosaic_Correction (in Input Image is Planetscope)

# If you use this code, please cite our following paper: https://doi.org/10.1016/j.rsase.2024.101438 
