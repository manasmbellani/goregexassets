# GoRegexAssets

This is a script to extract various types of assets such as IP, Domains and Emails from one or more files/folders. Currently, the following asset types are supported: 
* IPs
* Domains
* Emails

## Examples

### Extract all domains from a file
To extract ALL domains from a folder `/tmp/`, run the following cmd. Note that 
this can generate a lot of false positives.

```
go run goregexassets/goregexassets.go -paths /tmp/ -assetType domain
```

### Extract all IPs from a file/folder
To extract ALL IPs from a folder `/tmp/`, run the following cmd. 

```
go run goregexassets/goregexassets.go -paths /tmp/ -assetType ip
```

### Extract all emails from a file/folder
To extract ALL IPs from a folder `/tmp/`, run the following cmd.

```
go run goregexassets/goregexassets.go -paths /tmp/ -assetType email
```

### Extract all URL paths from a file/folder
To extract ALL IPs from a folder `/tmp/`, run the following cmd.

```
go run goregexassets/goregexassets.go -paths /tmp/ -assetType urlpath
```

