### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 15-05-2026
### Name: RAMYA R
### Reg No: 212223230169
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">
Sentiment Analysis is a text mining technique used to identify and classify opinions, emotions, and attitudes expressed in textual data as positive, negative, or neutral. In this project, sentiment analysis is performed using RapidMiner on an Excel dataset. The process involves importing the dataset using the Read Excel operator, preprocessing the data, and generating sentiment attributes using the Generate Attributes operator with the VADER sentiment analysis algorithm. VADER evaluates the polarity of text and assigns sentiment scores based on the emotional tone of the content. The generated results can then be visualized and exported to an Excel file for further analysis. This project helps in understanding public opinion and extracting meaningful insights from textual datasets efficiently.
### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
<img width="1152" height="879" alt="image" src="https://github.com/user-attachments/assets/b9ad62f8-ee21-4be2-ae78-de48641d6f29" />

<img width="1033" height="865" alt="image" src="https://github.com/user-attachments/assets/4f8aa294-4c49-4c2f-bd32-2d31575e56c0" />


### Result:
Thus,a project is created for Sentimental Analysis on Any Dataset a Using Rapidminer.
