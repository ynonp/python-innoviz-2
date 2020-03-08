Python Labs

1. Write a program that takes a number from the 
   user and prints the sum of its digits

2. Write a program that takes a number and 
   print its value in binary

3. Write a program that takes a log file and print all the error messages from it (An error line is a one having 404 or 408 status). 
   Log file example:

```
167.86.115.113 - - [26/Dec/2019:00:25:59 +0200] "GET / HTTP/1.1" 200 1993 "-" "Mozilla/5.0 (Windows NT 5.1; rv:9.0.1) Gecko/20100101 Firefox/9.0.1"
167.86.115.113 - - [26/Dec/2019:00:26:01 +0200] "GET /HNAP1/ HTTP/1.1" 404 1772 "https://178.79.150.27/" "Mozilla/5.0 (Windows NT 5.1; rv:9.0.1) Gecko/20100101 Firefox/9.0.1"
167.86.115.113 - - [26/Dec/2019:00:26:01 +0200] "GET /hudson/script HTTP/1.1" 404 1772 "https://178.79.150.27/" "Mozilla/5.0 (Windows NT 5.1; rv:9.0.1) Gecko/20100101 Firefox/9.0.1"
167.86.115.113 - - [26/Dec/2019:00:26:02 +0200] "GET /script HTTP/1.1" 404 1772 "https://178.79.150.27/" "Mozilla/5.0 (Windows NT 5.1; rv:9.0.1) Gecko/20100101 Firefox/9.0.1"
84.110.208.186 - - [26/Dec/2019:00:37:57 +0200] "-" 408 5165 "-" "-"
77.124.5.143 - - [26/Dec/2019:01:32:58 +0200] "-" 408 543 "-" "-"
23.95.84.74 - - [26/Dec/2019:01:41:20 +0200] "-" 408 1373 "-" "-"
169.197.108.6 - - [26/Dec/2019:02:23:56 +0200] "GET / HTTP/1.1" 200 1814 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/60.0.3112.113 Safari/537.36"
52.41.211.72 - - [26/Dec/2019:04:23:07 +0200] "HEAD / HTTP/1.1" 200 1899 "-" "Go-http-client/1.1"
66.249.66.10 - - [26/Dec/2019:04:57:14 +0200] "GET / HTTP/1.1" 200 2406 "-" "Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5X Build/MMB29P) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2272.96 Mobile Safari/537.36 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)"
157.55.39.2 - - [26/Dec/2019:05:22:21 +0200] "GET /robots.txt HTTP/1.1" 404 2274 "-" "Mozilla/5.0 (compatible; bingbot/2.0; +http://www.bing.com/bingbot.htm)"
157.55.39.2 - - [26/Dec/2019:05:22:22 +0200] "GET /robots.txt HTTP/1.1" 404 2274 "-" "Mozilla/5.0 (compatible; bingbot/2.0; +http://www.bing.com/bingbot.htm)"
157.55.39.70 - - [26/Dec/2019:05:22:31 +0200] "GET / HTTP/1.1" 200 2495 "-" "Mozilla/5.0 (compatible; bingbot/2.0; +http://www.bing.com/bingbot.htm)"
35.175.224.215 - - [26/Dec/2019:07:00:51 +0200] "GET / HTTP/1.0" 400 0 "-" "-"
77.124.127.86 - - [26/Dec/2019:07:59:28 +0200] "-" 408 543 "-" "-"
77.124.127.86 - - [26/Dec/2019:07:59:28 +0200] "-" 408 543 "-" "-"
66.249.66.40 - - [26/Dec/2019:08:04:46 +0200] "GET / HTTP/1.1" 200 2406 "-" "Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5X Build/MMB29P) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2272.96 Mobile Safari/537.36 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)"
84.110.208.186 - - [26/Dec/2019:08:06:07 +0200] "-" 408 543 "-" "-"
169.197.108.38 - - [26/Dec/2019:08:44:04 +0200] "GET / HTTP/1.1" 200 1814 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/60.0.3112.113 Safari/537.36"
45.79.152.7 - - [26/Dec/2019:09:57:12 +0200] "GET / HTTP/1.0" 200 2977 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:00:20 +0200] "-" 408 156 "-" "-"
169.197.108.42 - - [26/Dec/2019:10:02:20 +0200] "GET / HTTP/1.1" 200 1814 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/60.0.3112.113 Safari/537.36"
84.110.208.186 - - [26/Dec/2019:10:03:56 +0200] "-" 408 543 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:05:09 +0200] "-" 408 543 "-" "-"
45.79.152.7 - - [26/Dec/2019:10:11:50 +0200] "HEAD / HTTP/1.1" 200 2065 "-" "Mozilla"
45.79.152.7 - - [26/Dec/2019:10:12:07 +0200] "HEAD / HTTP/1.1" 200 2065 "-" "Mozilla/5.0 (X11; U; Linux i686; en-US; rv:1.9a3pre) Gecko/20070330"
185.3.145.39 - - [26/Dec/2019:10:15:01 +0200] "-" 408 543 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:24:10 +0200] "-" 408 543 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:24:10 +0200] "-" 408 543 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:25:40 +0200] "-" 408 156 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:25:40 +0200] "-" 408 156 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:25:40 +0200] "-" 408 156 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:25:40 +0200] "-" 408 156 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:32:12 +0200] "-" 408 156 "-" "-"
185.3.145.39 - - [26/Dec/2019:10:32:19 +0200] "-" 408 543 "-" "-"
82.81.7.123 - - [26/Dec/2019:10:32:24 +0200] "-" 408 4720 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:34:22 +0200] "-" 408 543 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:34:22 +0200] "-" 408 543 "-" "-"
185.3.145.39 - - [26/Dec/2019:10:44:27 +0200] "-" 408 543 "-" "-"
84.110.208.186 - - [26/Dec/2019:10:46:26 +0200] "-" 408 543 "-" "-"
```

4. Write a python program that counts how many error 
   messages were in the log file
   
5. Find the log file with the most error messages 
    from all the files in current directory
    
6. Find word with the most vowels
7. Find word with the most consonants

