---
code-attribute:
	- cpp
	- python
header-includes: |
	\usepackage{listings}
	\usepackage[usenames,dvipsnames]{color}
	
	\lstset{ % General settings
		numbers=left,
		numberstyle=\tiny
	}

	\lstdefinestyle{cpp}{ % Only for C++
		keywordstyle=\color{Green}
	}

	\lstdefinestyle{python}{ % Only for Python
		keywordstyle=\color{Magenta}
	}
---

## C++:

* Inline: `int a = 0`{.cpp}.

* Block:

```cpp
int main(int argc, char *argv[])
{
	return 0;
}
```

## Python

* Inline: `print('Yes')`{.python}.

* Block:

```python
def main():
	print('Hello')

if __name__ == '__main__':
	main()
```

Others:

```pseudo
for i in list
	do something
```

