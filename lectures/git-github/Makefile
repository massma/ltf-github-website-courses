.PHONY : clean all

all : intro-git-github.html

intro-git-github.html : intro-git-github.md
	pandoc -t revealjs -s -o intro-git-github.html intro-git-github.md -V revealjs-url=https://revealjs.com -V theme=solarized

clean :
	rm -f intro-git-github.html
