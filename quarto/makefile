.PHONY: clean

# exercise → _site/  (student-facing, no solutions)
# solution → _site/instructor/  (instructor-facing, with solutions)

render:
	quarto render

clean:
	rm -rf _site
	rm -rf pages/*.html
	rm -rf index.html
	rm -rf site_libs/
