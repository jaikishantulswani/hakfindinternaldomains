**(modified purposely to get only the ips which are not internal)**

Original project of hakluke at https://github.com/hakluke/hakfindinternaldomains

# hakfindinternaldomains
Feed it a list of subdomains, it will resolve them and tell you which ones are internal

# Installation

```
go install github.com/hakluke/hakfindinternaldomains
```

# Usage

```
cat subdomains.txt | hakfindinternaldomains -t 50
```
