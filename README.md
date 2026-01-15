This repo contains the scripts and datasets for modeling streamflow at gaged sites in SSI's Delta project (2025-27).
Please contact Jessica Herrmann (jessica@sierrastreamsinstitute.org) with any questions.
		
Notes on units of measure –
Depths and measurements are in cm.
Average velocity has been converted from m/s to cm/s.
Angle measurements are in radians.


CONTENTS

Scripts
    (1) ChannelGeometryCalculator_01.08.26_JH.Rmd – Rmd script for calculating model constants
    (2) ManningsQCalculator_01.07.26_JH.Rmd – Rmd script for modeling streamflow using channel geometry and stage data
Datasets
    (1) CatCrk_FacsimileTestData.csv – CSV file containing facsimile data for testing ManningsQCalculator script
    (2) Delta_ChannelGeometry_InitialValues_RAW.csv – CSV with raw hand-calculated channel geometry measurements
    (3) Delta_ChannelGeometry_InitialValues_FINAL.csv – CSV with all final model constants; output of the ChannelGeometryCalculator script.
    Use this with the ManningsQCalculator script.
    
