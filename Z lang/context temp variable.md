```
People p = ("Jackie")
{	$ p.name
	case "Jackie" {

	}
	case ! "Yumk" {

	}
	case ! in blacklist || "Jhon Sigmer" {

	}
	print($) // Jackie
	case {	
		case $[0]
		print($) // nil
	}
}
{	case "Hello"
	print($) // "Hello"
}
print($) // nil
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE3NDUyOTg2OV19
-->