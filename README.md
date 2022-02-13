# yusub
<img src="73b8307b2db44c617f4e8515ce67dd39.png">
just subdomain enumeration from yuyu scanner 
## installation 
- pip install -r requirements.txt
- chmod +x yusub
- sudo mv yusub /usr/local/bin
## usage
- yusub target.com 
- cat targetlist.txt | yusub | some program u wanna run
- yusub target.com | some program u wanna run

## example
- cat targetlist.txt | yusub | httpx > result.txt
- yusub target.com | httpx > result.txt
