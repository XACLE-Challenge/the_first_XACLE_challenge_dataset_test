# XACLE Challenge 2026 dataset test set

## Contents

This dataset consists of the following componets:

- Audio–text pairs

	This dataset includes 3,000 audio–text pairs.
	Each text is written in English.
	All audio samples was converted to mono 16-bit 16 kHz format.

- 11-point semantic-alignment scores between audio and text (per listener)

	This dataset includes subjective evaluation scores for semantic alignment between audio and text.
	The semantic-alignment score is on a an 11-point scale from 0 ("does not match at all") to 10 ("matched exactly").
	Each audio–text pair is evaluated by four native English-speaking .

- Average semantic-alignment scores
	
	This dataset includes average semantic-alignment scores for each audio–text pair.

- Listener IDs

	This dataset includes listener IDs of those who scored the semantic alignment between audio and text.

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

-  test.csv: There are 4 columns in the csv file.
   	- wave_file_name: The file name of audio.
	- text: The text's corresponding audio.
	- 11-point semantic-alignment score: The evaluation scores for semantic alignment between audio and text by each listener.
	- listener_id: The listener ID who scored the sematic-alignment scores.
   
- test_average.csv: There are 3 columns in the each csv file.
	- wave_file_name: The file name of audio.
	- text: The text's corresponding audio.
	- average_semantic_alignement_score: The average semantic-alignment scores of each audio-text pair.


## Directory structure

The directory structure of this dataset is as follows:

```
XACLE_test_data
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
```

## Citation

Please cite the paper that will be uploaded to arXiv in early November, 2025.

## Acknowledgment

The work was supported by JSPS KAKENHI Grant Number 24K23880, 25K21221, JST Moonshot Grant Number JPMJMS2237.

