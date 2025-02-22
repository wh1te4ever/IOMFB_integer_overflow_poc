.PHONY: all macos clean

all:
	xcrun -sdk iphoneos clang -arch arm64 -mios-version-min=10.0 -Weverything poc.c -o poc -framework IOKit -framework CoreFoundation -lcompression -Os

clean:
	$(RM) poc