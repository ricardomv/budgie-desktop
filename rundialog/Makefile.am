-include $(top_srcdir)/common.mk

bin_PROGRAMS = budgie-run-dialog

budgie_run_dialog_SOURCES = \
	RunDialog.vala \
	../data/budgie-run-dialog-resources.c

budgie_run_dialog_CFLAGS = \
	$(GTK3_CFLAGS) \
	$(GMENU_CFLAGS) \
	$(GEE_CFLAGS) \
	-DGMENU_I_KNOW_THIS_IS_UNSTABLE

budgie_run_dialog_LDADD = \
	$(GTK3_LIBS) \
	$(GEE_LIBS) \
	$(GMENU_LIBS)

budgie_run_dialog_VALAFLAGS = \
	--pkg gtk+-3.0 \
	--pkg libgnome-menu-3.0 \
	--pkg gio-unix-2.0 \
	--pkg gee-0.8
