# Update references
references.bib:
	pubs -c .pubsrc export > $@

# Compile PDF document
tesis.pdf: *.md references.bib
	pandoc  \
		*.md \
		--pdf-engine xelatex \
		--metadata-file metadata.yml \
		--citeproc \
		-o $@
