# Maintainer: Eduardo Parra Mazuecos <eduparra90@gmail.com>

# I maintain this on github, feel free to submit a pull request to
# https://github.com/soker90/paquetes-archinux.git
pkgname=python-pyexcel
pkgver=0.5.7
pkgrel=1
pkgdesc="A wrapper library that provides one API to read, manipulate and write data in different excel formats"
arch=('i686' 'x86_64')
url="https://github.com/pyexcel/pyexcel"
license=('BSD')
makedepends=('python-setuptools')
depends=('python' 'python-texttable' 'python-pyexcel-io' 'python-lml')
source=("https://github.com/pyexcel/pyexcel/archive/v$pkgver.tar.gz")
md5sums=('c365e109f6eec9547b9284ce83dc3c07')

package() {
      cd "$srcdir/pyexcel-${pkgver}"
      python setup.py install --root=${pkgdir}
}
