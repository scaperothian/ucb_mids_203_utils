# UCB MIDS DATASCI 203 Useful things<br>

Dear Future Self.  Here is how I created a instance of RStudio locally.
```
docker run -d -p 8787:8787 -v ~/DATASCI203/:/home/rstudio/projects -e PASSWORD=<change password> amoselb/rstudio-m1
```

I also pulled down git repos locally and then mounted the directory to projects folder on the container.<br>
