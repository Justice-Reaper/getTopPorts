# get-top-ports
A Bash script that extracts the most common ports from Nmap, saves them to a text file in two different formats, and automatically copies the output to the clipboard

# Help panel

```
# ./get-top-ports -h
Usage: ./get-top-ports --protocol <protocol> --number-of-ports <number> --format <format>
Available protocols: TCP, UDP, SCTP
Available formats: one-per-line, inline
Example: ./get-top-ports --protocol TCP --number-of-ports 1000 --format one-per-line
```

# Usage

```
# ./get-top-ports --protocol TCP --number-of-ports 8000 --format inline
Created directory: inline/
Getting 8000 most common TCP ports in inline format...
Process completed ✓
Number of ports obtained: 7999
TCP ports saved in: inline/top-8000-tcp-ports.txt
Format: inline
Content copied to clipboard ✓
```
