# yusub
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
- cat target | yusub | httpx > result.txt
