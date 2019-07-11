test.pdf : test.md
	pandoc --listings $< -t json | python3 ../pandoc_code_attribute.py | pandoc --listings -f json -o test.tex
	pandoc --listings $< -t json | python3 ../pandoc_code_attribute.py 
	#pandoc $< --filter pandoc-code-attribute --listings -o test.pdf

.PHONY: inline

inline:
	#pandoc --listings inline-test.md -t json | python3 ../pandoc_code_attribute.py | pandoc --listings -f json -o inline-test.tex
	pandoc --listings inline-test.md -o inline-test.tex
	pandoc --listings inline-test.md -t json 
	#pandoc --listings inline-test.md -t json | python3 ../pandoc_code_attribute.py

.PHONY: clean

clean:
	rm -f test.pdf test.out

