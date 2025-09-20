# CiP-CAFE
The Chemicals in Products - Comprehensive Anthropospheric Fate Estimation (CiP-CAFE) model

**Release Date:** January, 2022

We are excited to introduce **Version 2.0** of the *Chemicals in Products - Comprehensive Anthropospheric Fate Estimation* model for tracking chemicals in products. This update enhances the model's capabilities, making it more versatile and user-friendly for environmental scientists, researchers, and practitioners.


## Installation and Usage Instructions
- Download both the spreadsheet (`CiP-CAFE_2.0.xlsm`) and the "Gridding" folder from the latest **Release**.
- Place them in the same directory on your local machine to ensure proper functionality.
- Trust the model file:
   - After downloading `CiP-CAFE_2.0.xlsm`, right-click the file in your file explorer.
   - Select **Properties** from the context menu.
   - In the **General** tab, check **Unblock** and click **OK** to mark the file as trusted.
- Use Microsoft Excel 2016 or later versions.
- Enable Macros in Microsoft Excel:
   - Open `CiP-CAFE_2.0.xlsm` in Microsoft Excel.
   - If prompted with a security warning about macros (e.g., "Macros have been disabled"), click **Enable Content** or **Enable Macros** in the yellow Message Bar at the top of the Excel window.
   - If no prompt appears, go to **File** > **Info** > **Enable Content** > **Enable All Content** to allow macros to run.
- Contact the model developer to obtain a new license key if you see a warning that the license has expired. Once received, place the license file in the same folder as the spreadsheet to activate the model.


## Determine Your Mode of Calculation

*Non-steady-state single-chemical calculation*: CiP-CAFE performs time-variant dynamic simulations of stocks, flows, and multimedia emissions of a single chemical substance in products/articles across the global human socioeconomic system, which comprises seven geographic regions, over a simulation period of up to 200 years. To run the model, you need to specify the start and end years of the simulation and provide time-variant data on annual production, export, and/or import for different geographic regions. You also need to provide detailed key parameters about the products/articles involved, distribution ratios across up to five applications, emission factors for different lifecycle stages and environmental media, and international trade of both products and waste.

*Steady-state batch calculation*: CiP-CAFE performs time-invariant steady-state simulations of stocks, flows, and multimedia emissions of an unlimited number of chemicals within a single geographic region. To run the model, you need to provide a single commercial tonnage value (either a minimum and maximum range or a central estimate) for each chemical to indicate the average production or use over multiple years. You must also specify each chemical's "functional use category", based on which CiP-CAFE automatically searches its built-in databases to populate key parameters about the products/articles involved, distribution ratios across up to five applications, emission factors for different lifecycle stages and environmental media, and international trade of both products and waste. 

