# Command Execution

## Payload Used

```bash
127.0.0.1 && whoami
```

## Description

Command Execution vulnerability allows attackers to execute system commands on the target server.

## Steps

1. Open DVWA
2. Navigate to Command Execution
3. Enter payload:
   ```bash
   127.0.0.1 && whoami
   ```
4. Application executed command successfully

## Result

Successfully executed system command and retrieved current user.

## Screenshots
