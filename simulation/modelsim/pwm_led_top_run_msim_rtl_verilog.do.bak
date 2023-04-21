transcript on
if {[file exists rtl_work]} {
	vdel -lib rtl_work -all
}
vlib rtl_work
vmap work rtl_work

vlog -vlog01compat -work work +incdir+D:/MSEE/5363/Week2/DE10litePWM {D:/MSEE/5363/Week2/DE10litePWM/pwm_led_top.v}
vlog -vlog01compat -work work +incdir+D:/MSEE/5363/Week2/DE10litePWM {D:/MSEE/5363/Week2/DE10litePWM/pwm_gen.v}
vlog -vlog01compat -work work +incdir+D:/MSEE/5363/Week2/DE10litePWM {D:/MSEE/5363/Week2/DE10litePWM/debouncer.v}
vlog -vlog01compat -work work +incdir+D:/MSEE/5363/Week2/DE10litePWM {D:/MSEE/5363/Week2/DE10litePWM/pwm_pll.v}
vlog -vlog01compat -work work +incdir+D:/MSEE/5363/Week2/DE10litePWM/db {D:/MSEE/5363/Week2/DE10litePWM/db/pwm_pll_altpll.v}

