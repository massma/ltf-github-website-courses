.PHONY : clean all

all : eeae-student-resources.html water-center-resources.html

eeae-student-resources.html : eeae-student-resources.md
	pandoc -o eeae-student-resources.html -c ../pandoc.css --from markdown --to html5 eeae-student-resources.md

water-center-resources.html : water-center-resources.md
	pandoc -o water-center-resources.html -c ../pandoc.css --from markdown --to html5 water-center-resources.md

clean :
	rm -f eeae-student-resources.html water-center-resources.html
