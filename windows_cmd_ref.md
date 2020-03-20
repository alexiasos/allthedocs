# Windows Commands and PowerShell Oneliners

## Information Gathering

### Collection
Query system information and output in table format:

`systeminfo /fo TABLE`

Query for scheduled tasks, output them in table format, make it verbose:

`schtasks /query /FO table /V`

Compress a directory into a zip file:

`powershell -NoProfile -Command "Compress-Archive -Path C:\path\to\directory\ -DestinationPath C:\path\to\outfile.zip"`
