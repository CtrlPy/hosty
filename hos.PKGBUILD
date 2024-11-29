# Maintainer: Sasha <nesnite@gmail.com>
pkgname=hos
pkgver=1.3.1
pkgrel=1
pkgdesc="A terminal utility for managing custom domains in /etc/hosts"
arch=('any')
url="https://github.com/CtrlPy/hos"
license=('MIT')
depends=('python')
makedepends=('python-setuptools')
source=("/hos")
sha256sums=('SKIP')

package() {
    cd "$srcdir/$pkgname-$pkgver"
    python setup.py install --root="$pkgdir/" --optimize=1
    install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
