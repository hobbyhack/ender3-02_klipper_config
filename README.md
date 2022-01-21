This printer prints: pla, tpu, petg, and carbon fiber nylon fatastically

Inherited ender3 with the following changes:
hemera extruder with slice 450 temp sensor
120v bed heater with EPCOS 100K B57560G104F sensor
linear rails
bltouch
skr 1.4 turbo with tmc2209 drivers
x, y, z endstops have been removed (using bltouch, tmc)
.6mm nozzle

projects completed:
migrated from marlin to klipper

current issues:
the combination of using the TMCs as endstops and the linear rails causes some failed homing
the center screw on the y rail needs to be screwed in and then backed out 2 full turns

Todo:
input shaper w/ accelerometer - some ringing currently
after input shaper retune pressure advance
remove linear rails - the original ender3 motion sytem performs
add back x, y endstops (maybe upgrade to hall sensors) and configure endstop phase