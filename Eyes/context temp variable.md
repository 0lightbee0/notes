```
People p = ("Jackie")
{	case p.name
	"Jackie" {

	}
	! "Yumk" {

	}
	! in blacklist || "Jhon Sigmer" {

	}
	print($) // Jackie
	{	case $[0]

	}
}
{	case "Hello"
	print($) // "Hello"
}
print($) // nil
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgwMzg4MTkyOF19
-->