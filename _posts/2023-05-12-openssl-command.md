---
title: "Openssl usefull command"
categories:
  - IT
tags:
  - IT
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

## Read certificate

```
openssl x509 -noout -text -in <CERTIFICATE>
```

