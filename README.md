# vm.lv2

## A simple Virtual Machine for LV2


### Build status

[![build status](https://gitlab.com/OpenMusicKontrollers/vm.lv2/badges/master/build.svg)](https://gitlab.com/OpenMusicKontrollers/vm.lv2/commits/master)

### Dependencies

* [LV2](http://lv2plug.in) (LV2 Plugin Standard)

### Build / install

	git clone https://git.open-music-kontrollers.ch/lv2/vm.lv2
	cd vm.lv2
	meson build
	cd build
	ninja -j4
	sudo ninja install

### License

Copyright (c) 2017 Hanspeter Portner (dev@open-music-kontrollers.ch)

This is free software: you can redistribute it and/or modify
it under the terms of the Artistic License 2.0 as published by
The Perl Foundation.

This source is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
Artistic License 2.0 for more details.

You should have received a copy of the Artistic License 2.0
along the source as a COPYING file. If not, obtain it from
<http://www.perlfoundation.org/artistic_license_2_0>.
