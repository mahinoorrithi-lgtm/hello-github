# SQL Injection Blind

## Payload Used

```sql
1' AND '1'='1
```

## Description

Blind SQL Injection allows attackers to retrieve information indirectly by observing application behavior.

## Steps

1. Open DVWA
2. Navigate to SQL Injection Blind
3. Enter payload:
   ```sql
   1' AND '1'='1
   ```
4. Application returned valid response

## Result

Successfully identified Blind SQL Injection vulnerability
