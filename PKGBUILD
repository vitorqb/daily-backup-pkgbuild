# Maintainer: Vitor Barbosa <vitorqb@gmail.com>
pkgname=daily-backup
pkgver=1.1.0
pkgrel=1
epoch=
pkgdesc="Daily backup utilities for vitor"
arch=(any)
url=""
license=('GPL')
groups=()
depends=("python3" "curl" "gnupg")
makedepends=()
checkdepends=()
optdepends=("backblaze-b2" "openssh")
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("$pkgname-$pkgver.tar.gz::https://github.com/vitorqb/daily-backup/archive/$pkgver.tar.gz")
noextract=()
md5sums=('3956673c2553871a4211e709a0f775d9')
validpgpkeys=()

package() {
    cd $pkgname-$pkgver
    ./install --prefix "$pkgdir"
}
