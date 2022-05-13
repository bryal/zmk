.PHONY: all
all:
	west build -d build/left  -b nice_nano_v2-a -- -DSHIELD=kyria_rev2_left  -DZMK_CONFIG="/home/jojo/Hack/zmk-config/config"
	west build -d build/right -b nice_nano_v2 -- -DSHIELD=kyria_rev2_right -DZMK_CONFIG="/home/jojo/Hack/zmk-config/config"

.PHONY: pristine
pristine:
	west build --pristine -d build/left  -b nice_nano_v2-a -- -DSHIELD=kyria_rev2_left  -DZMK_CONFIG="/home/jojo/Hack/zmk-config/config"
	west build            -d build/right -b nice_nano_v2 -- -DSHIELD=kyria_rev2_right -DZMK_CONFIG="/home/jojo/Hack/zmk-config/config"
