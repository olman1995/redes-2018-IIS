ISC BIND 9\bin

rndc-confgen -a
ipconfig /flushdns
rndc reload
nslookup windows.dr.pt