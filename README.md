rrys webUI

Install
replace /DOWNLOAD_DIR save data Run command below

docker run -d \
--name rrys \
-p 3001:3001 \
-v /DOWNLOAD_DIR:/opt/work/store \
#rrys
Open http://serverip:3001 for rrys
