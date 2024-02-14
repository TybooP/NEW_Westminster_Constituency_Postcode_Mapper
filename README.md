## Westminster Constituency Postcode Mapper

This repository contains all the necessary code and data to update your list of postcodes to match the new Westminster Parliamentary Constituency boundaries that will be used for the upcoming general election. The data includes every postcode along with its corresponding constituency and GSS code. Additionally, there's a Jupyter Notebook (`postcode_to_pconinfo.ipynb`) containing the code to add the information of constituency name and GSS code to the postcodes.

## How to Use

Follow these steps to run the code:

1. **Download the Files**: Create a folder on your computer to store these files, which will be in the top right corner and a zip file. You can download the files in this GitHub repository manually or using the command line with `git clone`. If you haven't used GitHub before, you may need to initialize SSH keys before running the `git clone` command. 

2. Install python and pandas to your environment

3. **Move the Files**: Once you have downloaded the files, move them to the folder you created earlier.

4. **Unzip the File**: If you downloaded a zip file, unzip it in the folder.

5. **Download Postcode List**: Download the list of postcodes you want to get the new constituency boundaries and codes.

6. **Prepare Data**: Make sure  you update the file path to point to the CSV file you want to match postcodes. Because this code is made for Action Network, I used  "zip_code" for the variable that has the postcodes, so change that according to the needs of your project.

7. **Run the Code**: Open the Jupyter Notebook file (`postcode_to_pconinfo.ipynb`) and execute the two cells. This process may take some time. My tests of 70+K postcodes ran within 10 seconds and correctly matched all valid and currently active postcodes. The results will be saved as a CSV file named `FINAL_postcodes_with_info.csv` in the same folder.

Following these steps, you should have successfully matched the postcodes with the new constituency boundaries and codes.
