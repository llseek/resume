TARGET = resume_ch.pdf
SOURCE = resume_ch.tex

all: $(TARGET)

$(TARGET): $(SOURCE)
	xelatex $<

fonts:
	mkdir -p ~/.fonts
	cp ../fonts/* ~/.fonts/
	fc-cache -f -v

.PHONY: clean

clean:
	@rm -rf $(TARGET) *.log *.aux *.out
