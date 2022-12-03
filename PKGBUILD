# Maintainer: ghesy <ehsan at disroot dot org>

_repo='ghesy/Cantora-PKGBUILD'
_group='impallari'
_pkgname="ttf-${_group}-cantora"
provides=("$_pkgname")
conflicts=("$_pkgname")

pkgname=${_pkgname}-latest
pkgdesc='Cantora is a friendly semi-formal, semi-condensed, semi-sans-serif font from Pablo Impallari.'
pkgver=2022.12.03.010817
pkgrel=1
url='https://fonts.google.com/specimen/Cantora+One'
arch=('any')
license=('OFL')
groups=("${_group}-fonts")
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/${_repo}/archive/refs/tags/${pkgver}.tar.gz")
sha256sums=('skip')

package() {
	install -Dm644 CantoraOne-Regular.ttf "${pkgdir}/usr/share/fonts/TTF/${_group}"
	install -Dm644 OFL.txt "${pkgdir}/usr/share/licenses/${pkgname}/"
}

# vim:filetype=PKGBUILD
