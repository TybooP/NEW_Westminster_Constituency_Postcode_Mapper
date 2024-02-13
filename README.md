## Westminster Constituency Postcode Mapper

This repository contains all the necessary code and data to update your list of postcodes to match the new Westminster constituency boundaries that will be used for the upcoming general election. The data includes every postcode along with its corresponding constituency and GSS code. Additionally, there's a Jupyter Notebook (`postcode_mapper.ipynb`) containing the code to add the information of constituency name and GSS code to the postcodes.

## How to Use

Follow these steps to run the code:

1. **Download the Files**: Create a folder on your computer to store these files. You can download the files in this GitHub repository manually or using the command line with `git clone`. If you haven't used GitHub before, you may need to initialize SSH keys before running the `git clone` command.

2. **Move the Files**: Once you have downloaded the files, move them to the folder you created earlier.

3. **Unzip the File**: If you downloaded a zip file, unzip it in the folder.

4. **Download Postcode List**: Download the list of postcodes for which you want to get the new constituency boundaries and codes.

5. **Prepare Data**: Make sure the file containing the list of postcodes is named `list_postcodes.csv` and is located in the same folder as the other files. Also, ensure that the column containing postcodes is named "Postcode".

6. **Run the Code**: Open the Jupyter Notebook file (`postcode_to_pconinfo.ipynb`) and execute the two cells. This process may take some time. The results will be saved as a CSV file named `postcodes_with_info.csv` in the same folder.

7. **Review Results**: After running the code, you will see the postcodes that couldn't be matched and the total number of unmatched postcodes. 

By following these steps, you should have successfully matched the postcodes with the new constituency boundaries and codes.
