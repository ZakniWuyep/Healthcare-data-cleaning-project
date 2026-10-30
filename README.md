**Cleaning a Synthetic Health Dataset in Excel**

**Summary**

I cleaned a synthetic dataset of 200 health records in excel. I determined the data problems myself such as inconsistencies, numbers entered as text, mistake in spellings etc., fixed them on a copy, and recorded every decision I made in a leaning log, including what I observed, what I did, and where the original value is kept.

**About the data**

The dataset is synthetic. It was generated for practice, with errors deliberately planted, it contains no real patient information, so nothing here reflets real world results. It has 200 rows and 13 columns originally, and 194 rows after I removed 6 duplicate rows.

**What’s in the project**

 •	Raw Data: This sheet contains the original messy dataset (200 rows, 13 columns) left unchanged.
 
 •	Clean Data: This sheet contains the cleaned copy (194 rows) with additional columns ending in “Suspect”, and an “ID missing” column. These mark values that were blanked or could not be verified.
 
•	Cleaning Log: This sheet lists each problem found, what I did and the original’s location.

**Limitations**

 •	Blood glucose values that were invalid or possibly in a different unit (999, text entries, values below 20) were blanked, not converted, because the unit could not be confirmed.

 •	Medication cost entries reading “Free” and negative cost were blanked, because their meaning could not be verified.
 
 •	“Chest infection” and “Entries fever” were kept as separate categories and not merged with Pneumonia or Typhoid Fever, as no documentation confirms they mean the same.

 •	Some discharge dates are earlier than the admission dates, which is not possible. Both values were left unchanged and the rows were flagged (Data Suspect= Yes), because the data does not show which date is wrong and this may affect any calculation of length of stay.
 
 •	Six patients appear in two rows each (repeat visits, with different admission dates) and were kept as separate rows. One row therefore represents one visit, not one patient.

 •	Five rows have no Patient ID, so repeat visits among them could not be identified.
 
 •	The dataset is synthetic so none of the leaning decisions were hiked against a real source.

