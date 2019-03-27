test.pdf : test.md
	#pandoc $< -t json | python3 ../pandoc_code_attribute.py | pandoc -f json -o test.pdf
	pandoc $< --filter pandoc-code-attribute --listings -o test.pdf

.PHONY: clean

clean:
	rm -f test.pdf test.out

