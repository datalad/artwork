# TODO: fix it up so works for both beige and non-beige
all: logo_wide_beige_tuned

%_tuned: %.svgtune
	svgtune $<
	convert -delay 10 -loop 0 logo_wide_tuned/*.svg logo_wide_beige.gif
