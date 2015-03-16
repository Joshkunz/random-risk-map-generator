.PHONY: clean

src = $(shell find . -name "*.java")
class = $(patsubst %.java,%.class,$(src))

target = Launcher

$(target).class: $(src)
	javac $(src)

clean:
	rm $(class)
