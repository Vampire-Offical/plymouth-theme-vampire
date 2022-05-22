pkgname=vampire-plymouth
pkgver=1
pkgrel=1.1
epoch=
pkgdesc="bootscreen for vampire os"
arch=(any)
license=('GPL')
groups=(vampire)
depends=(plymouth)
conflicts=(plymouth-theme-vampire)
makedepends=()
#install=
source=("$pkgname::git+https://github.com/Vampire-Offical/plymouth-theme-vampire.git")
md5sums=('SKIP')

package() {
	mkdir -p $pkgdir/usr/share/plymouth/themes/vampire
	cd $srcdir/$pkgname/sweet-arch
	cp -r . $pkgdir/usr/share/plymouth/themes/vampire
}
