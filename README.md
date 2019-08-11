# linkall
A simple tool for generating numerous symbolic links using python3.5 or greater

# Why?
I find myself spending allot of time reusing this script in a bunch of places which means that to me at least it has value.

# How?
Put a file in the director called "files.json" (not very creative I know) and then fill it with json entries like such

```json
[
	{"source":"<path to source file 1>",   "target":"<path to target 1>"},
	{"source":"<path to source file 2>",   "target":"<path to target 2>"},
	...
	{"source":"<path to source file N>",   "target":"<path to target N>"}
]
```
