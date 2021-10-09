# Working with *

```
$ ls .*
```

The asterisk (*) above match:

```
'file-name'
'folder-name/'
'.'
''
```

<img src="./md-assets/2021-10-06_13-43-32.png " width=400px/>

## Show dot and non-dot items

```
echo .*  # show dot item
echo *   # show non-dot item
```
<img src="./md-assets/2021-10-09_12-25-29.png" width=280px/>

## Show one item per line

Pipe to `tr` to show one item per line:

```
echo .* * | tr ' ' '\n'
```


<img src="./md-assets/Screen Shot 2021-10-09 at 12.31.57.png" width=200px/>