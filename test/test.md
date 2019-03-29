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

C++:

```cpp
int main(int argc, char *argv[])
{
	return 0;
}
```

Python:

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

