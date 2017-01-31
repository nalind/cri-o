SUBPROJECT := $(if $(PROJECT),$(PROJECT)/test/copyimg,.)

copyimg: $(wildcard *.go)
	go build -tags "$(BUILDTAGS)" -o $@ $(SUBPROJECT)

.PHONY: clean
clean:
	rm -f copyimg
