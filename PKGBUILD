# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

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
depends=('bash' 'coreutils' 'cat' 'sed' 'awk')
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
source=("$pkgname-$pkgver.tar.gz::https://github.com/yckbrd/pacrepoman/archive/${pkgver}.tar.gz"
        "$pkgname-$pkgver.patch")
#noextract=()
#md5sums=()
#validpgpkeys=()

#prepare() {
#	cd "$pkgname-$pkgver"
#	patch -p1 -i "$srcdir/$pkgname-$pkgver.patch"
#}

#build() {
#	cd "$pkgname-$pkgver"
#	./configure --prefix=/usr
#	make
#}

#check() {
#	cd "$pkgname-$pkgver"
#	make -k check
#}

package() {
#	cd "$pkgname-$pkgver"
#	make DESTDIR="$pkgdir/" install
	mkdir -p $pkgdir/usr/bin
	install -m 755 "$srcdir/$pkgname-$pkgver/pacrepoman" "$pkgdir/usr/bin/pacrepoman"
}
