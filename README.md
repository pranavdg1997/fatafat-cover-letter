
# Fatafat Cover Letter
(*fatafat* : Indian slang which means 'quick & easy')\

QUICK DISCLAIMER : This app needs you to have Python on your system and some very basic programming background to be able to use it seamlessly. It opens in your browser but runs on your machine, hence a functioning computer is necessary. If you feel this should be hosted online, and made available to non-programmers, the FREE solutions that exist do not guarantee privacy standards, albeit that with some investment it can be made into a successfull app.

This app lets you speed up making your custom cover letter. You can replace Company name and Position in your cover letter, then proceed to save it to an output file with 1 click.\
You can also keep track of the companies you have applied so far with timestamp of application.
The app has options for multiple future features, however that all depends on feedback and requirements.

<div align="center">
  <a href="https://www.youtube.com/watch?v=-io-9ec6zdU&"><img src="https://github.com/pranavdg1997/fatafat-cover-letter/blob/main/demo-fast.gif" alt="IMAGE ALT TEXT"></a>
</div>

## Step-by-step setup
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
parent_filepath: 'Cover_Letter_Sample.docx'
output_filepath: 'Cover_Letter_Sample_op.docx'
history_file: 'sample_history.csv'
replace_text: "I am writing regarding the {1} opportunity at {0}. I am due for graduation in May 2021 with a Master's in Data science from XYZ University. As a candidate with over 2 years of experience in the field, as well as a skill-set coherent with the requirements, I believe myself to be a suitable candidate and submit my application for review."
```
Open a terminal and run the following command inside the directory of the repo. Your app should start running in your browser.\
```sh
streamlit run cover_letter_app.py
```
## Usage
 - As per the video, enter company name and profile in the appropriate boxes, press on the button and your new cover letter will be saved to destination as per the config file settings.
 - Please try to build your cover letter based on the template from the sample, it will easier to read.
 - You may need to adjust slider so that the original text and text to be replaced is the same, except for the company_name & profile.
 - When not using the app, you can refer to the history csv file anytime you need to check your previous applications, it will updated constantly every time you use the app.

## Possible future features
I thought about various features that can be added, since the current ones seem pretty basic. However anything I could think of became too user specific and only applicable for certain cases. Some of these are - 
 - Customize which paragraphs to include or not
 - Copy elements to clipbaord (basically you can pre-set different elements to directly copy to your clipboard with a single click)
 - upload/download cover letter instead of using config file
 - Pipe in key words
 - Similar tool for Resume(will be lot of work though)

Please let me know of any issues and contact me on pgujarat@iu.edu for any feedback/suggestions.

