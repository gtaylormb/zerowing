# Find all Verilog/SystemVerilog files recursively
SOURCES := $(shell find . -type f \( -name "*.v" -o -name "*.sv" \))

SLANG_OPTIONS :=

# The default target: run slang on everything
lint:
	slang $(SLANG_OPTIONS) $(SOURCES)

# Optional: show which files will be linted
print-files:
	@echo $(SOURCES)