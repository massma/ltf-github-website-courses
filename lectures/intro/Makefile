.PHONY : clean

test.html : test.org
	pandoc -t revealjs -s -o test.html test.org -V revealjs-url=https://revealjs.com -V theme=solarized

clean :
	rm -f test.html
