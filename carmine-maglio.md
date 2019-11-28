carmine.maglio
--t. touch
Updates access and modification time stamps of your file. If it doesn't exists, it'll be created.
touch filename
Example:
$ touch trick.md



--g. grep
Looks for text inside files. You can use grep to search for lines of text that match one or many regular expressions, and outputs only the matching lines.

grep pattern filename
Example:

$ grep admin /etc/passwd
_kadmin_admin:*:218:-2:Kerberos Admin Service:/var/empty:/usr/bin/false
_kadmin_changepw:*:219:-2:Kerberos Change Password Service:/var/empty:/usr/bin/false
_krb_kadmin:*:231:-2:Open Directory Kerberos Admin Service:/var/empty:/usr/bin/false
You can also force grep to ignore word case by using -i option. -r can be used to search all files under the specified directory, for example:

$ grep -r admin /etc/
And -w to search for words only. For more detail on grep, check following link.



--j. sort
Sort lines of text files

example.txt

f
b
c
g
a
e
d
sort example.txt

sort example.txt
a
b
c
d
e
f
g
randomize a sorted example.txt

sort example.txt | sort -R
b
f
a
c
d
g
e