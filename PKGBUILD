pkgname=vampire-plymouth
pkgver=1
pkgrel=1
epoch=
pkgdesc="bootscreen for vampire os"
arch=(any)
license=('GPL')
groups=(vampire)
depends=(plymouth)
makedepends=()
#install=
source=("$pkgname::git+https://github.com/Vampire-Offical/plymouth-theme-vampire.git")


package() {
	mkdir -p $pkgdir/usr/share/plymouth/themes/vampire
	cd $srcdir/$pkgname/sweet-arch
	cp -r . $pkgdir/usr/share/plymouth/themes/vampire
}
