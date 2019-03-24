TARGET = resume_en.pdf
SOURCE = resume_en.tex

all: $(TARGET)

$(TARGET): $(SOURCE)
	xelatex $<

fonts:
	mkdir -p ~/.fonts
	cp ../fonts/* ~/.fonts/
	fc-cache -f -v

.PHONY: clean

clean:
	@rm -rf $(TARGET) *.log *.dvi
