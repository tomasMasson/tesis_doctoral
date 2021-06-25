# Update references
references.bib: bibliography/*
	pubs -c .pubsrc export > $@

# Compile PDF document
tesis.pdf: *.md references.bib
	pandoc  \
		*.md \
		--include-in-header=preamble.tex \
		--template=template.tex \
		--variable=fontsize:11pt \
		--variable=mainfont:cmunrm.ttf \
		--variable=mainfontoptions:BoldFont=cmunbx.ttf \
		--variable=mainfontoptions:ItalicFont=cmunti.ttf \
		--variable=mainfontoptions:BoldItalicFont=cmunbi.ttf \
		--variable=papersize:a4paper \
		--variable=documentclass:book \
		--variable=link-citations:yes \
		--pdf-engine xelatex \
		--filter pantable \
		--bibliography=references.bib \
		--citeproc \
		--number-sections \
		--output $@
