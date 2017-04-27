# `<a>`

| Property | Value |
| -------- | ----- |
| Mandatory | No |
| Location | Somewhere within `<body>` |
| Must be closed | Yes |

## About
This tag creates a link 

## Arguments
| Argument | Description | Type | Mandatory |
| -------- | ----------- | ---- | --------- |
| `href`   | The location the link to go to | URL | Yes |
| `title`  | Text to display when hovering | Text | No  |
| `target` | Allows you to set location of link to open | Text | No |

## Usage
```
<a href="[url]">[text]</a>
```

## Tips and Tricks
Here are some tips and tricks on using `<a>`.

### Open link in new tab
Set the `target` argument to `_blank` to open the link in a new tab.