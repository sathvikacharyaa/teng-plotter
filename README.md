# TENG Plotter

TENG Plotter is a web-based tool for quickly plotting, analyzing, formatting, and exporting Triboelectric Nanogenerator (TENG) measurement data.

The application allows users to upload CSV files obtained from TENG measurements and generate frequency-response or force-response plots without using Origin or writing plotting code manually.

## Live Website

[Open TENG Plotter](https://teng-plotter.vercel.app/)

## Project Overview

After performing TENG measurements, the experimental data is usually saved as CSV files. To analyse this data, users often need to import it into Origin or write code using Python, MATLAB, or another programming language.

This process can be repetitive and time-consuming, particularly when measurements are performed for several frequencies or applied forces.

TENG Plotter simplifies this workflow. Users can upload their CSV files, select the required response type, generate the plot, customize its appearance, view the peak-to-peak voltage values, and export the final graph.

## Why I Designed This Website

I designed TENG Plotter because TENG measurement data usually requires repeated processing before it can be presented in a useful form.

For every new measurement, researchers may need to:

- Open and organize CSV files.
- Import the data into Origin.
- Write or modify plotting code.
- Generate frequency-response or force-response plots.
- Calculate peak-to-peak voltage values.
- Format the graph manually.
- Export the final figure for a report or research paper.

These steps take time and may require specialized software or programming knowledge.

TENG Plotter provides a faster and more convenient alternative. Users only need to upload the CSV files and format the plot according to their requirements. The graph and peak-to-peak voltage table can then be generated quickly.

The website is mainly useful for students and researchers working in:

- Triboelectric nanogenerators.
- Energy harvesting.
- Nanomaterials.
- Materials science.
- Experimental physics.
- Sensor and nanogenerator research.

## Main Objectives

The main objectives of TENG Plotter are:

- To simplify the plotting of TENG measurement data.
- To reduce dependence on Origin and manual plotting code.
- To process multiple CSV files quickly.
- To generate frequency-response and force-response plots.
- To calculate peak-to-peak voltage values automatically.
- To provide detailed graph-formatting options.
- To help users prepare figures for reports, presentations, and research papers.
- To make TENG data analysis more accessible to students and researchers.

## Features

### 1. CSV File Upload

Users can upload CSV files containing TENG measurement data.

This avoids the need to manually copy data into plotting software or create a separate plotting script for every measurement.

### 2. Frequency-Response Plotting

The website can generate frequency-response plots for measurements performed at different frequencies while maintaining a constant force.

This helps users study how the TENG output changes with operating frequency.

Typical frequency-response analysis includes:

- Frequency on the X-axis.
- Peak-to-peak voltage on the Y-axis.
- Separate data corresponding to different measurement conditions.

### 3. Force-Response Plotting

The website can generate force-response plots for measurements performed at different forces while maintaining a constant frequency.

This helps users investigate the effect of applied force on the TENG output.

Typical force-response analysis includes:

- Force on the X-axis.
- Peak-to-peak voltage on the Y-axis.
- Separate data corresponding to different applied forces.

### 4. Automatic Peak-to-Peak Voltage Calculation

The website calculates the peak-to-peak voltage from the uploaded measurement data.

This allows users to obtain the voltage response for each frequency or force condition without calculating it manually.

### 5. Peak-to-Peak Voltage Table

The calculated peak-to-peak voltage values are displayed in a table.

The table allows users to:

- View the calculated voltage values.
- Compare different frequencies or forces.
- Copy the values.
- Download the table.
- Use the values in reports and further analysis.

### 6. Plot Preview

Users can preview the plot before exporting it.

The preview helps users check:

- The overall graph layout.
- The visibility of the data.
- The axis labels.
- The title.
- The annotation position.
- The Y-axis scale.
- The colors of the peak lines.

### 7. Custom Plot Title

Users can change the title of the graph according to the measurement or analysis being performed.

### 8. Title Size Adjustment

Users can change the font size of the graph title.

### 9. Axis Label Customization

Users can change the labels of the X-axis and Y-axis.

### 10. Axis Label Size Adjustment

The size of the axis labels can be changed to improve readability and match the requirements of different documents.

### 11. Tick for Bold

Users can modify the text to make it bold for the title, Axis Labels and annotations.

This helps maintain readability when the graph is resized or exported.


### 12. Annotation Position Control

The annotation can be moved to a suitable position inside the graph.

This prevents the annotation from covering:

- Data lines.
- Peak lines.
- Axis labels.
- Important regions of the plot.

### 14. Y-Axis Scale Adjustment

Users can change the Y-axis scale according to the range of their data.

This helps users:

- Improve the visibility of small variations.
- Remove unnecessary empty space.
- Focus on the important data range.
- Compare multiple plots consistently.
- Present the data more clearly.

### 15. Peak-Line Color Customization

Users can change the colors of the different peak lines.

Different colors make it easier to distinguish between measurements performed at different:

- Frequencies.
- Forces.
- Samples.
- Experimental conditions.

### 16. Plot Export

The final plot can be exported in several formats:

- JPG.
- PNG.
- SVG.
- PDF.

These formats can be used for different purposes:

| Format | Suitable use |
|---|---|
| PNG | Reports, presentations, and general use |
| JPG | Quick sharing and lightweight images |
| SVG | Scalable graphics and further editing |
| PDF | Research papers, printing, and documentation |


## Typical Workflow

The basic workflow of the website is:

1. Perform the TENG measurement.
2. Save the experimental data as CSV files.
3. Open TENG Plotter.
4. Upload the CSV files.
5. Select frequency-response or force-response analysis.
6. Generate the plot.
7. View the peak-to-peak voltage table.
8. Customize the title, labels, font sizes, colors, and annotations.
9. Adjust the Y-axis scale.
10. Preview the final plot.
11. Copy or download the data table.
12. Export the plot in JPG, PNG, SVG, or PDF format.

## Example Use Case

Suppose a TENG is measured at several frequencies while the applied force is kept constant.

The user can upload the CSV files corresponding to those measurements. TENG Plotter processes the files, generates the frequency-response plot, and calculates the peak-to-peak voltage for each frequency.

The user can then:

- Set the X-axis label to `Frequency (Hz)`.
- Set the Y-axis label to `Peak-to-Peak Voltage (V)`.
- Add a suitable graph title.
- Adjust the title and label sizes.
- Change the colors of the peak lines.
- Add experimental information as an annotation.
- Move the annotation to a suitable position.
- Adjust the Y-axis range.
- Export the final graph as a PDF or image.

The same workflow can be used for force-response measurements.

## Target Users

TENG Plotter is intended for:

- Triboelectric nanogenerator researchers.
- Physics students.
- Materials-science students.
- Nanotechnology researchers.
- Energy-harvesting researchers.
- Undergraduate project students.
- Postgraduate project students.
- Researchers performing repeated TENG measurements.
- Users who want to visualize TENG data without writing code.

## Applications

The website can be used for:

- Frequency-response analysis.
- Force-response analysis.
- Comparison of different TENG devices.
- Comparison of different materials.
- Peak-to-peak voltage analysis.
- Laboratory reports.
- Research papers.
- Thesis and dissertation work.
- Conference presentations.
- Research posters.
- Quick inspection of experimental data.


## How to Use the Website

1. Open the TENG Plotter website.
2. Upload the required CSV files.
3. Select the required response type.
4. Generate the plot.
5. Check the peak-to-peak voltage table.
6. Modify the graph title.
7. Change the title and label sizes.
8. Edit the X-axis and Y-axis labels.
9. Add and position annotation text.
10. Adjust the Y-axis scale.
11. Change the colors of the peak lines.
12. Preview the graph.
13. Copy or download the table.
14. Export the graph in the required format.

## Future Improvements

Possible future improvements include:

- Automatic CSV-format validation.
- Support for additional CSV file structures.
- Direct Excel-file upload.
- Batch processing of multiple datasets.
- Automatic detection of experimental conditions.
- Additional graph types.
- Error-bar plotting.
- Uncertainty analysis.
- Curve fitting.
- Statistical analysis.
- RMS voltage calculation.
- Average voltage calculation.
- Automatic maximum-output detection.
- Data smoothing and filtering.
- Comparison of multiple samples.
- Saving and loading plot templates.
- Dark mode.
- Improved mobile support.
- Export to LaTeX-compatible formats.

## Project Significance

TENG Plotter demonstrates how a web application can solve a practical problem in experimental physics.

Instead of repeatedly moving between CSV files, Origin, and programming scripts, researchers can complete the basic plotting and formatting workflow in one place.

This makes the process faster, more convenient, and easier to reproduce. It also helps users prepare clear and consistent figures for research communication.

## Author

B G Sathvik Acharya

GitHub: [@sathvikacharyaa](https://github.com/sathvikacharyaa)

## License

This project is developed for educational and research purposes.
