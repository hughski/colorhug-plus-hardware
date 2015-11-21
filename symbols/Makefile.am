GENERATED_FILES =					\
	23K640.sym					\
	L78L33AC.sym					\
	MBT3904DW1T1.sym				\
	PIC18F46J50.sym					\
	SPARK-DET-VIS.sym				\
	TCN75A.sym

designsymbolsdir = $(datadir)/colorhug-hardware/symbols
designsymbols_DATA =					\
	${GENERATED_FILES}				\
	USB_mini_TYPE-B_5_SMT.sym

all: ${GENERATED_FILES}

%.sym: %.tsym
	${TRAGESYM} $< $@

CLEANFILES =						\
	${GENERATED_FILES}

EXTRA_DIST = ${designsymbols_DATA}

-include $(top_srcdir)/git.mk
