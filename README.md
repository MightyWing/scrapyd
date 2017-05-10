# scrapyd
docker run -d --restart always --name scapyd --link postgres:postgresdb --link rabbit:rabbitdb   -p 6800:6800  
