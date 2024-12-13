pkgname=hosty
pkgver=1.0.1
pkgrel=1
pkgdesc="A simple utility for managing hostnames"
arch=('any')
url="https://github.com/CtrlPy/hosty"
license=('MIT') 
depends=('python' 'python-click' 'python-markdown-it-py' 'python-mdurl' 'python-pygments' 'python-rich' 'python-typing_extensions' 'python-urwid' 'python-wcwidth')
makedepends=('git')
source=("$pkgname-$pkgver.tar.gz::$url/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('SKIP') 

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
}
