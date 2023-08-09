# All-Language-OCRs
Model checkpoints are uploaded [here](https://csciitd-my.sharepoint.com/:f:/g/personal/agarai_cstaff_iitd_ac_in/EpB6Cr98expDnB78qsdb4WEBTF1-MzKDqZvc-ARkaug9Wg?e=ADBnhb)

All models currently support **Printed Text** datasets. run.py can be modified to execute on multiple images.

## Models that are currently available:
1. **Kannada OCR**</br>
2. **Tamil OCR**</br>
      
## Convert mdb files to images
check_lmdb_to_jpg.py file can be used to convert mdb files to images. (Path to mdb folder consists of data.mdb and lock.mdb files)

## Test the model
```
python run.py --model_path /path/to/model.ckpt --image_path /path/to/image.jpg
```
