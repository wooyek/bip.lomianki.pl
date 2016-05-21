# bip.lomianki.pl
Kopia biuletynu informacji pulicznej urzędu Miasta i Gminy Łomianki


## Mirror

```
httrack  -%c120 -p7 -c8 --disable-security-limits --max-rate=3000000 --update --mirror bip.lomianki.pl
find bip.lomianki.pl/*.pdf -type f -exec md5sum {} + > pdf.md5
find bip.lomianki.pl/*.pdf -type f -exec md5sum {} + >> pdf.md5
```
