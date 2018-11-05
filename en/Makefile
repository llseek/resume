TARGET = resume.pdf
SOURCE = resume.tex

all: $(TARGET)

$(TARGET): $(SOURCE)
	xelatex $<

.PHONY: clean

clean:
	@rm -rf $(TARGET) *.log *.dvi
