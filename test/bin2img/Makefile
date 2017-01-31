SUBPROJECT := $(if $(PROJECT),$(PROJECT)/test/bin2img,.)

bin2img: $(wildcard *.go)
	go build -tags "$(BUILDTAGS)" -o $@ $(SUBPROJECT)

.PHONY: clean
clean:
	rm -f bin2img
