# XSS Stored

## Payload Used

```html
<script>alert('Stored XSS')</script>
```

## Description

Stored XSS occurs when malicious JavaScript is permanently stored by the application and executed for every visitor.

## Steps

1. Open DVWA
2. Navigate to XSS Stored
3. Enter:
   - Name: admin
   - Message:
   ```html
   <script>alert('Stored XSS')</script>
   ```
4. Submit the payload
5. Alert box executed successfully

## Result

Successfully executed stored XSS payload.

## Screenshots
