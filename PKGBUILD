# Maintainer: holmeslinux <holmes_holmes@live.com>

pkgname=jwmconf
pkgver=0.1
pkgrel=1
pkgdesc="an interactive jwm interface using pmenu"
arch=(any)
url="https://github.com/holmeslinux/$pkgname"
license=(GPL2)
depends=('pmenu'
	'bash')
makedepends=('git')
source=("git://github.com/holmeslinux/$pkgname")
md5sums=('SKIP')

package () {
    install -Dm755 "$srcdir/$pkgname/jwmconf" "$pkgdir/usr/bin/jwmconf"
}