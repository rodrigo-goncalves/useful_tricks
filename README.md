# Useful Tricks for daily usage

Regex to filter the http... www... bit from URLs
```
# From the beginning of the line, match everything until it finds a double forward-slash (//). Optionaly, match three w's, then all numbers, if any, until finally matching a literal dot. 
^.+?\/{2}(w{3}(\d+)?\.?)?
```
