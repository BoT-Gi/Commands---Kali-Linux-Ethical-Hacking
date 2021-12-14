### showmount command 
```
showmount -e 10.2.2.2 
```
(`-e` or `--exports` shows the export list)

output
/share        (everyone)
/my-notes     (noone)


#'mount' command 

mount 10.2.2.2:/share fold1

("share" is shared folder in the host and
 "fold1" is on our machine - saving mount 'share' folder in to our local machine's 'fold1')
 
 #output
 Go to the 'fold1' to see the output!