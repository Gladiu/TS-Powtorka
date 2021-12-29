all: 1.pdf 2.pdf 3.pdf 4.pdf 5.pdf 6.pdf 7.pdf 8.pdf 9.pdf
1.pdf:
	-@pdflatex -interaction=nonstopmode ../source/1.tex
2.pdf:
	-@pdflatex -interaction=nonstopmode ../source/2.tex
3.pdf:
	-@pdflatex -interaction=nonstopmode ../source/3.tex
4.pdf:
	-@pdflatex -interaction=nonstopmode ../source/4.tex
5.pdf:
	-@pdflatex -interaction=nonstopmode ../source/5.tex
6.pdf:
	-@pdflatex -interaction=nonstopmode ../source/6.tex
7.pdf:
	-@pdflatex -interaction=nonstopmode ../source/7.tex
8.pdf:
	-@pdflatex -interaction=nonstopmode ../source/8.tex
9.pdf:
	-@pdflatex -interaction=nonstopmode ../source/9.tex
clean:
	for file in *.log *.aux ; do \
		if [ -e "$file" ]; then \
		    rm "$$file" || exit 1; \
		else \
		    printf 'No such file: %s\n' "$file" \
		fi \
	done
