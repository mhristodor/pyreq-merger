# pyreq-merger

Minimal tool used for merging 2 requirement files into a single one by either upgrading or downgrading the package versions.

#### Usage Example

`pyreq file1 file2 --method downgrade --output mynewreq.txt` 

Output is a new requirement file with the specified name in the current working directory.