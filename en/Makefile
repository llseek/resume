TARGET = resume_en.pdf
SOURCE = resume_en.tex

all: $(TARGET)

$(TARGET): $(SOURCE)
	xelatex $<

.PHONY: clean

clean:
	@rm -rf $(TARGET) *.log *.dvi
