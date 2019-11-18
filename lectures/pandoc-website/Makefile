.PHONY : clean all

all : generate-materials.html

generate-materials.html : generate-materials.md
	pandoc -t revealjs -s -o generate-materials.html generate-materials.md -V revealjs-url=https://revealjs.com -V theme=solarized

clean :
	rm -f generate-materials.html
