# Maintainer: Anton Grensjö <anton@grensjo.se>
pkgname=python-tld
_realname=tld
pkgver=0.9
pkgrel=1
pkgdesc="Extracts the top level domain (TLD) from the URL given"
arch=('any')
url="https://github.com/barseghyanartur/tld"
license=('GPL')
depends=('python' 'python-six')
makedepends=('python-setuptools')
options=(!emptydirs)
source=("https://github.com/barseghyanartur/tld/archive/${pkgver}.tar.gz")
sha256sums=('4dc152f8737e2724cd4ef0c43931d1b655fe1025a9f01cda87670daf8c7e8af6')

package() {
  cd "$srcdir/$_realname-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
