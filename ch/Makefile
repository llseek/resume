TARGET = resume_ch.pdf
SOURCE = resume_ch.tex

all: $(TARGET)

$(TARGET): $(SOURCE)
	xelatex $<

.PHONY: clean

clean:
	@rm -rf $(TARGET) *.log *.aux *.out
