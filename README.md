platform_manifest
=================
How to build:

1) First you need to sync Elevate:
  A) mkdir elevate
	B) cd elevate
	C) repo init -u git://github.com/ElevateRom/platform_manifest.git -b master
	D) repo sync

2) You now need to add in your device specific trees (kernel, device, vendor...etc)

3) Now you can build:
	A) . build/envsetup.sh
	B) lunch
	c) choose device from menu
	D) make bacon

4) relax, eat some pizza, go for a walk...do something, this can take a while...your finished product will be located in /elevate/out/target/product/devicenamehere