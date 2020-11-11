.PHONY : clean all

all : generate-materials.html

generate-materials.html : generate-materials.md
	pandoc -t revealjs -s -o $@ $< -V revealjs-url=../../reveal.js -V theme=solarized

clean :
	rm -f generate-materials.html
