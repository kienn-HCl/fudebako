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
	"fdbk-menu"
)
sha256sums=(
	"SKIP"
	"SKIP"
)

package() {
	# cd "$pkgname-$pkgver"
	install -Dm755 "${srcdir}/fdbk-menu" "${pkgdir}/usr/bin/fdbk-menu"
}
