# Written description for Tableau visualization

> What software did you use to create your data visualization? 

This data visualization was created using Tableau Public, a web-based data visualization platform designed for interactive and exploratory analysis. Tableau Public was selected for its strong capabilities in rapidly producing interactive, multi-line time-series visualizations and for its accessibility to non-technical audiences through web-based sharing.


> Who is your intended audience? 

The intended audience includes members of the general public, students, journalists, and policy stakeholders who may not have programming expertise but are interested in understanding regional crime trends in Canada. Tableau Public enables this audience to interact with the data through legends and tooltips without requiring statistical or coding knowledge.


> What information or message are you trying to convey with your visualization? 

The visualization aims to convey how the Crime Severity Index (CSI) evolved between 2008 and 2012 across selected Canadian geographies, including provinces, territories, and sub-provincial regions. By plotting all selected jurisdictions on a single chart, the visualization highlights stark disparities in crime severity—particularly the consistently elevated CSI values in the northern territories—while also showing that most regions experienced a general decline over time.


> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

Several design principles guided the visualization. A line chart was chosen to preserve temporal continuity and enable comparison across years. Colour encoding was used to distinguish geographies, supported by a clear legend rather than direct labels to reduce visual clutter. Gridlines and axis labels were kept minimal to maintain readability, while the consistent y-axis scale ensured that differences between high- and low-CSI regions were not visually distorted. Tableau’s default smoothing and layout features were deliberately avoided to preserve fidelity to the underlying data.


> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

Reproducibility was partially addressed through consistent use of the same cleaned dataset and documented transformations (pivoting and filtering) within Tableau. However, Tableau Public is not fully reproducible in the same way as code-based tools, as transformations are embedded in the workbook rather than expressed as executable scripts. This limits exact replication without access to the original workbook file, highlighting a trade-off between accessibility and methodological transparency.


> How did you ensure that your data visualization is accessible? 

Accessibility was considered by using a clear, high-contrast colour palette and avoiding reliance on colour alone to communicate meaning; users can also identify lines through legend interaction and tooltips. The visualization is web-based, allowing screen magnification and browser-level accessibility features, although Tableau Public has limitations for screen-reader compatibility.


> Who are the individuals and communities who might be impacted by your visualization? 

The visualization represents communities across Canada, particularly those in northern and remote regions where crime severity is persistently high. These communities may be impacted by how the data are interpreted; therefore, the visualization is presented descriptively, focusing on structural patterns rather than individual or community blame.


> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

Geographies were included based on analytical relevance and data availability, with the intent of illustrating variation across territorial, provincial, and local scales. While this introduces scale differences, inclusion was purposeful in order to foreground inequality that might otherwise be obscured by aggregation.


> What ‘underwater labour’ contributed to your final data visualization product?

Significant “underwater labour” informed the final visualization, including cleaning a structurally inconsistent dataset, resolving encoding and delimiter issues, pivoting data into long format, validating geographic labels, and making deliberate decisions about inclusion to balance analytical clarity with completeness.
