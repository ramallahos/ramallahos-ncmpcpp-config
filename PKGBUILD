# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-ncmpcpp-config
pkgver=1
pkgrel=1
pkgdesc="NCMPCPP config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('ncmpcpp')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/ncmpcpp/"
    install -Dm 644 "config" "${pkgdir}/etc/skel/.config/ncmpcpp/config"
}



