
### Question 1 Usage:

```
git clone git@github.com:are-prabhu/assessment.git
cd assessment/question1	
vagrent init
vagrent up
```


### Question 2 Usage:

```
git clone git@github.com:are-prabhu/assessment.git
cd assessment/question2
chmod +x custom_mtr.py
pip3 install -r requirement.txt	

python3.4 custom_mtr.py -c 50 google.com
finding latency to google.com (172.217.7.238), 30 hops max
	hops name			ip			 average latency
 1  ip-10-0-13-100.ec2.internal	 (10.0.13.100)			0.770 ms 
 2  * * * 
 3  * * * 
 4  * * * 
 5  * * * 
 6  * * * 
 7  100.65.10.193	 (100.65.10.193)			3.360 ms 
 8  205.251.244.215	 (205.251.244.215)			1.919 ms 
 9  54.239.111.58	 (54.239.111.58)			8.826 ms 
10  54.239.108.213	 (54.239.108.213)			4.523 ms 
11  72.14.212.130	 (72.14.212.130)			4.148 ms 
12  108.170.246.65	 (108.170.246.65)			6.365 ms 
13  216.239.48.201	 (216.239.48.201)			3.068 ms 
14  iad23s58-in-f14.1e100.net	 (172.217.7.238)			5.024 ms 

``

