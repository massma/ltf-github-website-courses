.PHONY : clean all

all : intro-git-github.html

intro-git-github.html : intro-git-github.md
	pandoc -t revealjs -s -o intro-git-github.html intro-git-github.md -V revealjs-url=https://revealjs.com -V theme=solarized

intro-git-github.md : intro-git-github.org
	pandoc -o intro-git-github.md --from org --to markdown intro-git-github.org

clean :
	rm -f intro-git-github.html
