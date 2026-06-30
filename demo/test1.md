# Markdown Syntax Highlighting Test

This file is for testing fenced code block import highlighting in Writer.

## SQL block (should highlight)

```sql
-- Active users by name
SELECT name, email
FROM users
WHERE active = 1
ORDER BY name;
```

## Basic block (should highlight)

```basic
' Compute a simple sum
Dim total As Integer
total = 40 + 2
If total > 0 Then
    Print "Total:", total
End If
```

## VB alias block (should highlight as Basic)

```vb
Sub Main()
    Dim msg As String
    msg = "Hello from VB alias"
    Print msg
End Sub
```

## Unknown language block (should remain uncolored text)

```python
def hello(name):
    return f"Hello, {name}"
```
