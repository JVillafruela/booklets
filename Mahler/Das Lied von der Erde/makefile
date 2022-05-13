THEME=adoc-themes/booklet-theme.yml

all: Das_Lied_von_der_Erde_de-fr.pdf

%.pdf: %.adoc
	asciidoctor-pdf $< -a $(THEME)