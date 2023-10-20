PKG = st

PKGBUILD:
	git clone --depth=1 https://aur.archlinux.org/${PKG}.git
	cp -f ${PKG}/PKGBUILD .
	rm -rf ${PKG}

clean:
	rm -rf PKGBUILD src pkg *.pkg.tar.* st*.tar.gz

.PHONY: clean
