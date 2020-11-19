# Useful Bash Commands

List biggest 5 files and subdirectories
```
du -sh * | sort -k 1 -hr | head -5
```

Commands explanation
* du
  * s: summarise (group by directory) 
  * h: human readable
* sort
  * k: indicative of column to sort by
  * h: human readable
  * r: reverse
