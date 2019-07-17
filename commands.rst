Usual commands
==============
chpasswd
mysql
    -p, --password
psql
    -W, --password
ftp
    account [passwd]
rsync
    RSYNC_PASSWORD (envvar)
    --password-file
genpkey
    -pass
ldapadd, ldapmodify, ldapwhoami, ldapdelete, ldapexop, ldapsearch, ldapmodrdn
    -w passwd
    -y passwdfile
ldappasswd
    -a oldPasswd
    -t oldPasswdFile
    -s newPasswd
    -T newPasswdFile
    -w passwd
    -y passwdfile
ldapsetpasswd
    [encoded password]
htpasswd
    -b
curl
    -E, --cert <certificate[:password]>
    --pass <phrase>
    -u, --user <user:password>
    -U, --proxy-user <user:password>
    -x, --proxy <[protocol://][user:password@]proxyhost[:port]>
wget
    --password=password
    --http-password=password
    --proxy-password=password
    --ftp-password=password
docker login
    -p password
snmpkey
    snmpkey <authProto> <password> <authEngineID> [<privProto> [<password>]]
smbtar
    -p password
smbcacls, smbtree
    -A|--authentication-file=filename
    -U|--user=username[%password]
    --pw-nt-hash
smbget
    -p, --password=STRING
smbclient
    [password]
    -A|--authentication-file=filename
    -U|--user=username[%password]
    --pw-nt-hash
    logon <username> <password>
    posix_encrypt <domain> <username> <password>
    PASSWD (envvar)
rpcclient
    -A|--authentication-file=filename
    -U|--user=username[%password]
    --pw-nt-hash
funzip
    [-password]
tsget
    -p key_password
ts
    -passin password_src
mkpasswd
unrar, unrar-nonfree
    -p<password>
sqlt-dumper
    -p|--password     Database password
psftp
    -pw password
pscp
    -pw password
plink
    -pw password
7z, 7za, 7zr
    -p{Password}
unzip
    -P password
x11vnc
    -passwdfile filename
    -storepasswd pass file
samba-tool
    --password=PASSWORD
    user add username [password]
    user create username [password]


Crypto
======
pkcs12, spkac, ec, ca, pkey, pkcs8, req, smime, rsa, pkeyutl, x509
enc
    -pass param
    -k password
openssl
    pass:password
sshpass
    -p<password>
sshkeygen
    -P passphrase
genrsa
    -passout param


Exotic commands
===============
mogrify, animate, stream, compare, identify, convert
    -authenticate value
pdinfo, xpdf, pdftohtml, pdfimages, pdfdetach, pdftops, pdftocairo, pdffonts, dumppdf
    -opw <string>
    -upw <string>
exiftool
    -password PASSWD
pdf2txt
    -P password
irssi
    -w, --password=PASSWORD
qemu-system
    password=<secret>
    x509-key-password=<file>
ab
    -A auth-username:password
    -P proxy-auth-username:password
mactime
    -p password file



Places to look
==============
git config
apt config
