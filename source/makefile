# Update references
references.bib: bibliography/*
	pubs -c .pubsrc export > $@

# Compile PDF document
tesis.pdf: *.md references.bib metadata.yml
	pandoc  \
		*.md \
		--pdf-engine xelatex \
		--metadata-file metadata.yml \
		--citeproc \
		-o $@
