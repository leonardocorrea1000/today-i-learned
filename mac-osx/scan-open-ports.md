## How to scan open ports on Mac OSX

<p>Network Utility was deprecated in macOS and no longer functions as of macOS Big Sur (version 11), released in 2020.
</p>

### MacOs Version: 13.3.1 - Ventura

In terminal

```bash
 nc -vz 192.168.1.xxx 1-65000 2>&1 | grep succeed
```
