## CDNStrip

Striping CDN IPs from a list of IP Addresses

## Install

```shell
go install github.com/hack-parthsharma/CDNStrip@latest
```

## Usage

```shell
# simple usage
cat ips | cdnstrip -c 50

# write the output to a file
cat ips | cdnstrip -cdn cdn.txt -n non-cdn.txt
```
