# Maintainer: Ulrik Boll Djurtoft <201406850 at post dot au dot dk>
pkgname=ttf-au
pkgver=1.0
pkgrel=1
pkgdesc="The official fonts for Aarhus University: AU Passata, AU Peto and AU Logo"
arch=('any')
url="http://medarbejdere.au.dk/en/administration/communication/design/msofficetemplates/downloadfonts/"
license=('custom')
depends=('fontconfig' 'xorg-font-utils')
source=('http://medarbejdere.au.dk/fileadmin/www.designmanual.au.dk/hent_filer/hent_skrifttyper/fonte.zip')
noextract=()
md5sums=('36b2114a3102b1db7511a39fd7322262')

package()
{
	install -Dm 644 "${srcdir}/AULogoBold.ttf" "${pkgdir}/usr/share/fonts/${pkgname}/AULogoBold.ttf"
	install -Dm 644 "${srcdir}/AULogoReg.ttf" "${pkgdir}/usr/share/fonts/${pkgname}/AULogoReg.ttf"
	install -Dm 644 "${srcdir}/AUPassata_Bold.ttf" "${pkgdir}/usr/share/fonts/${pkgname}/AUPassata_Bold.ttf"
	install -Dm 644 "${srcdir}/AUPassata_Light.ttf" "${pkgdir}/usr/share/fonts/${pkgname}/AUPassata_Light.ttf"
	install -Dm 644 "${srcdir}/AUPassata_Rg.ttf" "${pkgdir}/usr/share/fonts/${pkgname}/AUPassata_Rg.ttf"
	install -Dm 644 "${srcdir}/AU_Peto.ttf" "${pkgdir}/usr/share/fonts/${pkgname}/AU_Peto.ttf"
}
