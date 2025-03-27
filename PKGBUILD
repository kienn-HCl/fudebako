pkgname=fudebako
pkgver=0.0.1
pkgrel=1
pkgdesc="A Gtk(GJS) based desktop shells"
arch=('any')
url="https://github.com/mcbeeringi/fudebako"
license=('MIT')
depends=('gtk4' 'gjs')
optdepends=('gtk4-layer-shell')
source=(
	"LICENSE"
	"fudebako-menu"
)

package() {
	cd "$pkgname-$pkgver"
	install -Dm755 "fbdk-menu" "${pkgdir}/usr/bin/fdbk-menu"
}
