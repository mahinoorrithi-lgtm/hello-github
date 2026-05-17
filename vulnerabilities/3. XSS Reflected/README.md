# XSS Reflected

## Payload Used

```html
<script>alert('XSS')</script>
```

## Description

Reflected XSS occurs when user input is immediately returned by the application without sanitization.

## Steps

1. Open DVWA
2. Navigate to XSS Reflected
3. Enter payload:
   ```html
   <script>alert('XSS')</script>
   ```
4. JavaScript alert executed successfully

## Result

Successfully executed JavaScript using reflected XSS
