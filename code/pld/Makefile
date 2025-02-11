all: decoder.jed


%.jed:	%.pld
	./5vcomp $<

clean:
	rm -f *.abs *.sim *.pdf

.PHONY: clean all

