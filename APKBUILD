# Maintainer: thinhx2 <nthinh1102@gmail.com>

# Reference: <https://postmarketos.org/devicepkg>
pkgname=device-xiaomi-sirius
pkgdesc="Xiaomi MI 8 SE"
pkgver=0.1
pkgrel=1
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="postmarketos-base linux-xiaomi-sirius mkbootimg mesa-dri-gallium"
makedepends="devicepkg-dev"

source="deviceinfo"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="54e190bfbb6d406c4bb7a25fae258dc114011d71cf64888bc9dc01a6aee204c95596bee1c88ae5faa82c15b200bc50f9627d005f8192a3eefb057cd865177131  deviceinfo"
