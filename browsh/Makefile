PKG = browsh

PKGBUILD:
	git clone --depth=1 https://aur.archlinux.org/${PKG}.git
	cp -f ${PKG}/PKGBUILD .
	rm -rf ${PKG}

clean:
	rm -rf PKGBUILD ${PKG}

.PHONY: clean
