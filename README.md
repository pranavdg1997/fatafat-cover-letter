# Fatafat Cover Letter
This app lets you speed up making your custom cover letter. You can customize & replace Company name and Position in your cover letter. You can also keep track of the companies you have aplied so far.

<div align="center">
  <a href="https://www.youtube.com/watch?v=-io-9ec6zdU&"><img src="https://github.com/pranavdg1997/fatafat-cover-letter/blob/main/screenshot.JPG" alt="IMAGE ALT TEXT"></a>
</div>

# Step-by-step
Clone the repository, then proceed to install the requirements with - 
```sh
pip install -r requirements.txt
```
After this, edit & set the values in  the config.yml file as follows
- parent_filepath: path to the input docx file
- output_filepath: path at which the output docx file will be saved
- history_file: Path to the csv where previous submission will be saved
- replace_text: Here put the text for the introductory paragraph which contains the company name & profile name. Replace company name with {0} and profile name with {1}. 

Please refer to samples files as well as these sample values for the config.yml file
```sh
parent_filepath: '/Cover_Letter_Sample.docx'
output_filepath: '/Cover_Letter_Sample_op.docx'
history_file: 'sample_history.csv'
replace_text: "I am writing regarding the {1} opportunity at {0}. I am due for graduation in May 2021 with a Master's in Data science from XYZ University. As a candidate with over 2 years of experience in the field, as well as a skill-set coherent with the requirements, I believe myself to be a suitable candidate and submit my application for review."
```
Open a terminal and run the following command inside the directory of the repo. Your app should be running.\


Please let me know of any issues and contact me on pgujarat@iu.edu for any feedback/suggestions.

