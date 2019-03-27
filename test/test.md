---
header-includes: |
	\usepackage{listings}
	
	\lstset{ % General settings
		numbers=left,
		numberstyle=\tiny
	}

	\lstdefinestyle{cpp}{ % Only for C++
		emphstyle=\color{Green}
	}

	\lstdefinestyle{python}{ % Only for Python
		emphstyle=\color{Magenta}
	}
---

C++:

~~~cpp
int main(int argc, char *argv[])
{
	return 0;
}
~~~

Python:

~~~python
def main():
	print('Hello')

if __name__ == '__main__':
	main()
~~~
