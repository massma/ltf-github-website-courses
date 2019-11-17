.PHONY : clean all

all : generate-materials.html

generate-materials.html : generate-materials.md
	pandoc -t revealjs -s -o generate-materials.html generate-materials.md -V revealjs-url=https://revealjs.com -V theme=solarized

generate-materials.md : generate-materials.org
	pandoc -o generate-materials.md --from org --to markdown generate-materials.org

clean :
	rm -f generate-materials.html
