# Assignments
- กำหนดส่งภายในวันที่ 7/Sep/2020
- ส่งผลงานในรูปแบบ Jupyter Notebook บน Google Colab หรือ Github


### Remote Sensing Data Specialist
Download และ pre-process ภาพถ่ายดาวเทียม Sentinel-2A โดยมีรายละเอียดดังต่อไปนี้
 - Download ภาพถ่ายดาวเทียม Sentinel-2A ของ index "48QUD" ณ วันที่ 7/Jul/2020 จาก Public dataset ของ Google
   (ศึกษารายละเอียดเพิ่มเติมได้ที่ https://cloud.google.com/storage/docs/public-datasets/sentinel-2)
 - คำนวณค่า NDVI
 - ทำการ Reproject ดังนี้ 
    - EPSG:32648 - WGS 84 / UTM zone 48N
    - 293985.0, 30.0, 0.0, 1874415.0, 0.0, -30.0
 - บันทึกภาพเก็บไว้ในรูปแบบ GeoTIFF และ แสดงผลภาพภายใน notebook

ทั้งนี้สามารถตั้งต้นงานจาก Notebook ที่เตรียมไว้ได้
https://github.com/surasakcho/crop_insurance_recruit/blob/master/Assignment_Remote_Sensing_Data_Specialist.ipynb


