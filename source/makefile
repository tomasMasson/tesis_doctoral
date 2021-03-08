# Update references
references.bib: bibliography/*
	pubs -c .pubsrc export > $@

# Compile PDF document
tesis.pdf: *.md references.bib metadata.yml
	pandoc  \
		*.md \
		--include-in-header=preamble.tex \
		--variable=fontsize:11pt \
		--variable=papersize:a4paper \
		--variable=documentclass:book \
		--variable=link-citations:yes \
		--pdf-engine xelatex \
		--filter pantable \
		--metadata-file metadata.yml \
		--bibliography=references.bib \
		--citeproc \
		--number-sections \
		--output $@
