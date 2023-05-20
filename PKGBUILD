# Maintainer: Yannick Brouard <github@brouard.solutions>
pkgname=pacrepoman
pkgver=0.1.0
pkgrel=1
#epoch=
pkgdesc="CLI Pacman repository manager"
arch=('any')
url="https://github.com/yckbrd/pacrepoman"
license=('MIT')
#groups=()
depends=('bash' 'coreutils' 'sed' 'awk')
#makedepends=()
#checkdepends=()
#optdepends=()
#provides=()
#conflicts=()
#replaces=()
#backup=()
#options=()
#install=
#changelog=
source=("$pkgname-$pkgver.tar.gz::https://github.com/yckbrd/pacrepoman/archive/${pkgver}.tar.gz")
#noextract=()
#md5sums=()
#validpgpkeys=()

package()
{
mkdir -p $pkgdir/usr/bin
install -m 755 "$srcdir/$pkgname-$pkgver/pacrepoman" "$pkgdir/usr/bin/pacrepoman"
}
