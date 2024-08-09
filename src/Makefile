.PHONY: live build clean

live:
	@echo "Previewing main slides..."
	-@reveal-md main.md -w || true

build:
	@echo "Building main slides..."
	@reveal-md main.md --static ../slide --assets-dir assets
	@rm ../slide/main.html

clean:
	@echo "Cleaning up..."
	rm -rf ../slide
