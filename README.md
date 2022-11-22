# Apache HTTP-Server 2.4.49-2.4.50 Path Traversal & Remote Code 
## Usage: 
```
python3 exploit.py <rhost> <rport> <option> <cmd/file-absolute-path>
```
## Example:
### Remote Code Execution
```
python3 exploit.py 127.0.0.1 8080 rce 'id'
```

### Path Traversal
```
python3 exploit.py 127.0.0.1 8080 file '/etc/passwd'
```
