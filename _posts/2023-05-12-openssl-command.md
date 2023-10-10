---
title: "Openssl usefull command"
categories:
  - it
tags:
  - it
  - openssl
  - certificate
toc: true
toc_label: "Table of Contents"
---

# Openssl usefull command

## Convert PKCS7 to CRT

```
openssl pkcs7 -print_certs -in old.p7b -out new.crt
```

## Convert CRT to PEM

```
openssl x509 -in mycert.crt -out mycert.pem -outform PEM
```

## Read certificate

```
openssl x509 -noout -text -in <CERTIFICATE>
```

## Read distant certificate

```
openssl s_client -connect host:port -state -debug
```

