# Maintainer: Vivien Maisonneuve <v dot maisonneuve at gmail dot com>
# Category: science
pkgname='python-linpy'
pkgver='1.0.3'
pkgrel=2
pkgdesc='A polyhedral library based on isl'
arch=('i686' 'x86_64')
url='https://scm.cri.ensmp.fr/git/linpy.git'
license=('GPL3')
depends=('python' 'isl')
optdepends=('python-sympy' 'python-matplotlib')
source=("https://pypi.python.org/packages/source/L/LinPy/LinPy-$pkgver.tar.gz")
md5sums=('92ac488a3dd4c8fd92b97d4f642f26b6')

package() {
    cd "$srcdir/LinPy-$pkgver"
    python setup.py install --root="$pkgdir/" --optimize=1
}
