all:
	rm -Rf out/
	mkdir -p out/
	cd v0.20/ && mkdocs build --clean && mv site/ ../out/v0.20/
	cd v0.20/ && mkdocs build --clean && mkdocs2pandoc > ceu-libuv-v0.20.md && pandoc ceu-libuv-v0.20.md -o ceu-libuv-v0.20.pdf && mv site/ ../out/v0.20/
	cd v0.30/ && mkdocs build --clean && mv site/ ../out/v0.30/
	cd v0.30/ && mkdocs build --clean && mkdocs2pandoc > ceu-libuv-v0.30.md && pandoc ceu-libuv-v0.30.md -o ceu-libuv-v0.30.pdf && mv site/ ../out/v0.30/
