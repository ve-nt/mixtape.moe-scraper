# mixtape.moe-scraper
A script that tries randome URLs on https://mixtape.moe and writes them to a file if it exists

for usage try:
      `python3 mixtape_scraper.py -h`

##### Arguments:
      -h                show help message
      -v                verbose output
      -t <threads>      multithreading with <threads> being number of threads
      -p                use rotating proxies
     
##### Format Groups:
all     - all formats  
common  - common formats  
media   - video, audio and pictures  
text    - text, configs and data  
archive - archive files  
                
##### Examples:
  scrape for common formats with 24 threads and proxies  
      `python3 mixtape_scraper.py -t 24 -p common`  
  
  scrape for all formats with 12 threads  
      `python3 mixtape_scraper.py -t 12 all`  
  
  scrape for .wav formats with 1 thread  
      `python3 mixtape_scraper.py .wav`  
