# Written description for Python visualization

> What software did you use to create your data visualization? 

The data visualization was created using Python, specifically the pandas library for data manipulation and matplotlib for plotting. Python was selected because it supports transparent, script-based workflows that enable reproducibility, precision, and analytical control.


> Who is your intended audience? 

The intended audience includes students, researchers, and policy-oriented audiences with an interest in crime trends and regional disparities in Canada. The visualization is designed to be interpretable by non-technical readers while retaining analytical rigor for academic use.


> What information or message are you trying to convey with your visualization? 

The visualization communicates how the Crime Severity Index (CSI) changed over time (2008–2012) across selected Canadian geographies. By comparing the northern territories with large provinces, the plot highlights persistent regional disparities in crime severity while also showing broader temporal declines. The core message is that aggregate national or provincial trends can obscure structurally higher crime severity in certain regions, particularly the territories.


> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

Several design principles informed the visualization. A line chart was chosen because the data are temporal and annual, making trend comparison central. Colour and line weight were used to differentiate geographies without overwhelming the viewer; territories with consistently higher CSI values were visually emphasised using thicker lines. Axis labels, a clear title, and a restrained colour palette were applied to reduce cognitive load and avoid misinterpretation. The y-axis scale was kept consistent to preserve proportional differences across regions.


> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

Reproducibility was ensured by using a fully script-based workflow. All data cleaning, transformation, and visualization steps were documented in Python code, and the cleaned dataset was saved as a UTF-8 CSV file. Because Python visualizations can be regenerated directly from code and data, the visualization is fully reproducible. If a non-reproducible tool were used, this would limit transparency and make it difficult to verify or update results.


> How did you ensure that your data visualization is accessible? 

Accessibility was addressed by avoiding colour schemes that rely on red–green contrast, using clear labels, and ensuring sufficient line thickness and font size for readability. The visualization does not rely solely on colour to convey meaning, making it more accessible to viewers with colour-vision deficiencies.


> Who are the individuals and communities who might be impacted by your visualization? 

The visualization may impact communities represented in the data, particularly those in northern and Indigenous-majority regions where crime severity is persistently high. Care was taken to present the data descriptively rather than stigmatically, focusing on structural patterns rather than attributing blame.


> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

Only a subset of geographies was included to avoid overplotting and scale distortion. Selection was based on average CSI values, ensuring that inclusion was empirically justified rather than arbitrary.


> What ‘underwater labour’ contributed to your final data visualization product?

Significant “underwater labour” contributed to the final product, including resolving encoding errors, restructuring the dataset into tidy format, diagnosing header and delimiter issues, validating data types, and making defensible analytical decisions about inclusion and scale. This preparatory work was essential to producing a valid and interpretable visualization.
