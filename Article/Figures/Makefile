
TEX_FILES:=CIRED_PQU.tex European_Shunt_Line.tex Every_Projections.tex
PDF_FILES:=$(TEX_FILES:%.tex=%.pdf)

all: $(PDF_FILES)

%.pdf: %.tex Preambule.tex
	@arara $<
