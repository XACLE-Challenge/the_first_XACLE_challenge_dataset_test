# The first XACLE challenge dataset

## Contents

This dataset consists of the following componets:

- Audio–text pairs

	This dataset includes 3,000 audio–text pairs.
	Each text is written in English.
	All audio samples was converted to mono 16-bit 16 kHz format.
	
## Download

To download the dataset, please send an email to dataset@xacle.org with “Download test data” in the subject line. 
You will receive an automated reply with the download link.
<b>If you don't receive a reply after a while, please check your spam folder. If the email fails to send or you still don't receive a reply, please contact the organizer at y-oka@g.ecc.u-tokyo.ac.jp.<b>


## Statistics

|  | Test |
| :--- | ---: |
| Audio–text pairs | 3,000 |
| Audio duration [s] | 30,000 |

## File format

-  test.csv: There are 2 columns in the each csv file.
	- wave_file_name: The file name of audio.
	- text: The text's corresponding audio.

## Directory structure

The directory structure of this dataset is as follows:

```
XACLE_dataset
├── meta_data
│   ├── test.csv   
│   
└── wav
    ├── test
        ├── 10500.wav
        ├── 10501.wav
        ├── 10502.wav
        ├──   .
        ├──   .
        └──   .

## Citation

Please cite the paper that will be uploaded to arXiv in early November, 2025.

## Acknowledgment

The work was supported by JSPS KAKENHI Grant Number 24K23880, 25K21221, JST Moonshot Grant Number JPMJMS2237.

