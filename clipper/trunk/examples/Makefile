# Makefile.in generated by automake 1.13.4 from Makefile.am.
# examples/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2013 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



am__is_gnu_make = test -n '$(MAKEFILE_LIST)' && test -n '$(MAKELEVEL)'
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/clipper
pkgincludedir = $(includedir)/clipper
pkglibdir = $(libdir)/clipper
pkglibexecdir = $(libexecdir)/clipper
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
check_PROGRAMS = rfltest$(EXEEXT) sgtest$(EXEEXT) symtest$(EXEEXT) \
	$(am__EXEEXT_1) $(am__EXEEXT_2) $(am__EXEEXT_3) \
	$(am__EXEEXT_4) $(am__EXEEXT_5) $(am__EXEEXT_6) \
	$(am__EXEEXT_7) $(am__EXEEXT_8)
am__append_1 = ccad diffmap maptest mtztest
am__append_2 = cmaplocal ffttest sktest
am__append_3 = cnstest
am__append_4 = cns2mtz maketestdata sftest
am__append_5 = phstest
am__append_6 = ciftophs
#am__append_7 = ftndemo
#am__append_8 = cctbxtest
subdir = examples
DIST_COMMON = $(srcdir)/Makefile.in $(srcdir)/Makefile.am \
	$(top_srcdir)/build-aux/depcomp COPYING
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/ax_pthread.m4 \
	$(top_srcdir)/m4/fftw.m4 $(top_srcdir)/m4/libtool.m4 \
	$(top_srcdir)/m4/ltoptions.m4 $(top_srcdir)/m4/ltsugar.m4 \
	$(top_srcdir)/m4/ltversion.m4 $(top_srcdir)/m4/lt~obsolete.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__EXEEXT_1 = ccad$(EXEEXT) diffmap$(EXEEXT) \
	maptest$(EXEEXT) mtztest$(EXEEXT)
am__EXEEXT_2 =  \
	cmaplocal$(EXEEXT) \
	ffttest$(EXEEXT) \
	sktest$(EXEEXT)
am__EXEEXT_3 = cnstest$(EXEEXT)
am__EXEEXT_4 = cns2mtz$(EXEEXT) \
	maketestdata$(EXEEXT) \
	sftest$(EXEEXT)
am__EXEEXT_5 = phstest$(EXEEXT)
am__EXEEXT_6 = ciftophs$(EXEEXT)
#am__EXEEXT_7 = ftndemo$(EXEEXT)
#am__EXEEXT_8 = cctbxtest$(EXEEXT)
am_ccad_OBJECTS = ccad.$(OBJEXT)
ccad_OBJECTS = $(am_ccad_OBJECTS)
am__DEPENDENCIES_1 =
am__DEPENDENCIES_2 = ../clipper/core/libclipper-core.la \
	$(am__DEPENDENCIES_1)
ccad_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(am__DEPENDENCIES_2)
AM_V_lt = $(am__v_lt_$(V))
am__v_lt_ = $(am__v_lt_$(AM_DEFAULT_VERBOSITY))
am__v_lt_0 = --silent
am__v_lt_1 = 
am_cctbxtest_OBJECTS = cctbxtest.$(OBJEXT)
cctbxtest_OBJECTS = $(am_cctbxtest_OBJECTS)
cctbxtest_DEPENDENCIES = ../clipper/cctbx/libclipper-cctbx.la \
	$(ADD_CLIPPER_CONTRIB) $(am__DEPENDENCIES_2)
am_ciftophs_OBJECTS = ciftophs.$(OBJEXT)
ciftophs_OBJECTS = $(am_ciftophs_OBJECTS)
ciftophs_DEPENDENCIES = ../clipper/phs/libclipper-phs.la \
	$(ADD_CLIPPER_CIF) $(am__DEPENDENCIES_2)
am_cmaplocal_OBJECTS = cmaplocal.$(OBJEXT)
cmaplocal_OBJECTS = $(am_cmaplocal_OBJECTS)
cmaplocal_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_CONTRIB) \
	$(am__DEPENDENCIES_2)
am_cns2mtz_OBJECTS = cns2mtz.$(OBJEXT)
cns2mtz_OBJECTS = $(am_cns2mtz_OBJECTS)
cns2mtz_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_MMDB) \
	$(am__DEPENDENCIES_2)
am_cnstest_OBJECTS = cnstest.$(OBJEXT)
cnstest_OBJECTS = $(am_cnstest_OBJECTS)
cnstest_DEPENDENCIES = ../clipper/cns/libclipper-cns.la \
	$(ADD_CLIPPER_CCP4) $(am__DEPENDENCIES_2)
am_diffmap_OBJECTS = diffmap.$(OBJEXT)
diffmap_OBJECTS = $(am_diffmap_OBJECTS)
diffmap_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(am__DEPENDENCIES_2)
am_ffttest_OBJECTS = ffttest.$(OBJEXT)
ffttest_OBJECTS = $(am_ffttest_OBJECTS)
ffttest_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_CONTRIB) \
	$(am__DEPENDENCIES_2)
am_ftndemo_OBJECTS = ftndemo.$(OBJEXT)
ftndemo_OBJECTS = $(am_ftndemo_OBJECTS)
ftndemo_DEPENDENCIES = ../clipper/fortran/libclipper-fortran.la \
	$(am__DEPENDENCIES_2) $(am__DEPENDENCIES_1)
am_maketestdata_OBJECTS = maketestdata.$(OBJEXT)
maketestdata_OBJECTS = $(am_maketestdata_OBJECTS)
maketestdata_DEPENDENCIES = $(ADD_CLIPPER_MMDB) $(ADD_CLIPPER_CCP4) \
	$(ADD_CLIPPER_CONTRIB) $(am__DEPENDENCIES_2)
am_maptest_OBJECTS = maptest.$(OBJEXT)
maptest_OBJECTS = $(am_maptest_OBJECTS)
maptest_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(am__DEPENDENCIES_2)
am_mtztest_OBJECTS = mtztest.$(OBJEXT)
mtztest_OBJECTS = $(am_mtztest_OBJECTS)
mtztest_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(am__DEPENDENCIES_2)
am_phstest_OBJECTS = phstest.$(OBJEXT)
phstest_OBJECTS = $(am_phstest_OBJECTS)
phstest_DEPENDENCIES = ../clipper/phs/libclipper-phs.la \
	$(ADD_CLIPPER_CCP4) $(am__DEPENDENCIES_2)
am_rfltest_OBJECTS = rfltest.$(OBJEXT)
rfltest_OBJECTS = $(am_rfltest_OBJECTS)
rfltest_LDADD = $(LDADD)
rfltest_DEPENDENCIES = ../clipper/core/libclipper-core.la \
	$(am__DEPENDENCIES_1)
am_sftest_OBJECTS = sftest.$(OBJEXT)
sftest_OBJECTS = $(am_sftest_OBJECTS)
sftest_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_MMDB) \
	$(ADD_CLIPPER_CONTRIB) $(am__DEPENDENCIES_2)
am_sgtest_OBJECTS = sgtest.$(OBJEXT)
sgtest_OBJECTS = $(am_sgtest_OBJECTS)
sgtest_LDADD = $(LDADD)
sgtest_DEPENDENCIES = ../clipper/core/libclipper-core.la \
	$(am__DEPENDENCIES_1)
am_sktest_OBJECTS = sktest.$(OBJEXT)
sktest_OBJECTS = $(am_sktest_OBJECTS)
sktest_DEPENDENCIES = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_CONTRIB) \
	$(am__DEPENDENCIES_2)
am_symtest_OBJECTS = symtest.$(OBJEXT)
symtest_OBJECTS = $(am_symtest_OBJECTS)
symtest_LDADD = $(LDADD)
symtest_DEPENDENCIES = ../clipper/core/libclipper-core.la \
	$(am__DEPENDENCIES_1)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/build-aux/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
LTCXXCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CXXFLAGS) $(CXXFLAGS)
AM_V_CXX = $(am__v_CXX_$(V))
am__v_CXX_ = $(am__v_CXX_$(AM_DEFAULT_VERBOSITY))
am__v_CXX_0 = @echo "  CXX     " $@;
am__v_CXX_1 = 
CXXLD = $(CXX)
CXXLINK = $(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CXXLD) $(AM_CXXFLAGS) \
	$(CXXFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CXXLD = $(am__v_CXXLD_$(V))
am__v_CXXLD_ = $(am__v_CXXLD_$(AM_DEFAULT_VERBOSITY))
am__v_CXXLD_0 = @echo "  CXXLD   " $@;
am__v_CXXLD_1 = 
F77COMPILE = $(F77) $(AM_FFLAGS) $(FFLAGS)
LTF77COMPILE = $(LIBTOOL) $(AM_V_lt) --tag=F77 $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(F77) $(AM_FFLAGS) $(FFLAGS)
AM_V_F77 = $(am__v_F77_$(V))
am__v_F77_ = $(am__v_F77_$(AM_DEFAULT_VERBOSITY))
am__v_F77_0 = @echo "  F77     " $@;
am__v_F77_1 = 
F77LD = $(F77)
F77LINK = $(LIBTOOL) $(AM_V_lt) --tag=F77 $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(F77LD) $(AM_FFLAGS) $(FFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_F77LD = $(am__v_F77LD_$(V))
am__v_F77LD_ = $(am__v_F77LD_$(AM_DEFAULT_VERBOSITY))
am__v_F77LD_0 = @echo "  F77LD   " $@;
am__v_F77LD_1 = 
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
SOURCES = $(ccad_SOURCES) $(cctbxtest_SOURCES) $(ciftophs_SOURCES) \
	$(cmaplocal_SOURCES) $(cns2mtz_SOURCES) $(cnstest_SOURCES) \
	$(diffmap_SOURCES) $(ffttest_SOURCES) $(ftndemo_SOURCES) \
	$(maketestdata_SOURCES) $(maptest_SOURCES) $(mtztest_SOURCES) \
	$(phstest_SOURCES) $(rfltest_SOURCES) $(sftest_SOURCES) \
	$(sgtest_SOURCES) $(sktest_SOURCES) $(symtest_SOURCES)
DIST_SOURCES = $(ccad_SOURCES) $(cctbxtest_SOURCES) \
	$(ciftophs_SOURCES) $(cmaplocal_SOURCES) $(cns2mtz_SOURCES) \
	$(cnstest_SOURCES) $(diffmap_SOURCES) $(ffttest_SOURCES) \
	$(ftndemo_SOURCES) $(maketestdata_SOURCES) $(maptest_SOURCES) \
	$(mtztest_SOURCES) $(phstest_SOURCES) $(rfltest_SOURCES) \
	$(sftest_SOURCES) $(sgtest_SOURCES) $(sktest_SOURCES) \
	$(symtest_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/jordan/dev/privateer/dependencies/clipper/trunk/build-aux/missing aclocal-1.13
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = ar
AUTOCONF = ${SHELL} /home/jordan/dev/privateer/dependencies/clipper/trunk/build-aux/missing autoconf
AUTOHEADER = ${SHELL} /home/jordan/dev/privateer/dependencies/clipper/trunk/build-aux/missing autoheader
AUTOMAKE = ${SHELL} /home/jordan/dev/privateer/dependencies/clipper/trunk/build-aux/missing automake-1.13
AWK = mawk
CC = /usr/bin/gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2
CLIPPER_LIBS = -lclipper-ccp4 -lclipper-cif -lclipper-minimol -lclipper-mmdb -lclipper-cns -lclipper-phs -lclipper-contrib -lclipper-core
CLIPPER_REQUIRES = ccp4c mmdb2
CPP = /usr/bin/gcc -E
CPPFLAGS = -I/home/jordan/dev/privateer/dependencies/include
CXX = /usr/bin/g++
CXXCPP = /usr/bin/g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -O2 -w -std=c++11
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = false
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /usr/bin/grep -E
EXEEXT = 
F77 = 
FFLAGS = 
FFTW2_LIBS = -L/home/jordan/dev/privateer/dependencies/lib -lrfftw -lfftw
FGREP = /usr/bin/grep -F
FLIBS = 
GREP = /usr/bin/grep
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS = -L/home/jordan/dev/privateer/dependencies/lib -L/home/jordan/dev/privateer/dependencies/lib64
LIBOBJS = 
LIBS = -L$(libdir)
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /home/jordan/dev/privateer/dependencies/clipper/trunk/build-aux/missing makeinfo
MANIFEST_TOOL = :
MKDIR_P = /usr/bin/mkdir -p
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = clipper
PACKAGE_BUGREPORT = 
PACKAGE_NAME = clipper
PACKAGE_STRING = clipper 2.1
PACKAGE_TARNAME = clipper
PACKAGE_URL = 
PACKAGE_VERSION = 2.1
PATH_SEPARATOR = :
PTHREAD_CC = /usr/bin/gcc
PTHREAD_CFLAGS = 
PTHREAD_LIBS = -lpthread
RANLIB = ranlib
SED = /usr/bin/sed
SET_MAKE = 
SHELL = /bin/bash
STRIP = strip
VERSION = 2.1
VERSION_INFO = -version-info 2:1
abs_builddir = /home/jordan/dev/privateer/dependencies/clipper/trunk/examples
abs_srcdir = /home/jordan/dev/privateer/dependencies/clipper/trunk/examples
abs_top_builddir = /home/jordan/dev/privateer/dependencies/clipper/trunk
abs_top_srcdir = /home/jordan/dev/privateer/dependencies/clipper/trunk
ac_ct_AR = ar
ac_ct_CC = /usr/bin/gcc
ac_ct_CXX = 
ac_ct_DUMPBIN = 
ac_ct_F77 = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
ax_pthread_config = 
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/jordan/dev/privateer/dependencies/clipper/trunk/build-aux/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /home/jordan/dev/privateer/dependencies
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
ccad_SOURCES = ccad.cpp
cctbxtest_SOURCES = cctbxtest.cpp
ciftophs_SOURCES = ciftophs.cpp
cnstest_SOURCES = cnstest.cpp
cmaplocal_SOURCES = cmaplocal.cpp
cns2mtz_SOURCES = cns2mtz.cpp cns2mtz.h
diffmap_SOURCES = diffmap.cpp
ffttest_SOURCES = ffttest.cpp
ftndemo_SOURCES = ftndemo.f
ftndemo_LINK = $(CXXLINK)
maketestdata_SOURCES = maketestdata.cpp
maptest_SOURCES = maptest.cpp
mtztest_SOURCES = mtztest.cpp
phstest_SOURCES = phstest.cpp
rfltest_SOURCES = rfltest.cpp
sftest_SOURCES = sftest.cpp
sgtest_SOURCES = sgtest.cpp
sktest_SOURCES = sktest.cpp
symtest_SOURCES = symtest.cpp
AM_CPPFLAGS = -I$(top_srcdir)

# LDADD is used for programs for which program_LDADD is not set
LDADD = ../clipper/core/libclipper-core.la $(FFTW2_LIBS)
ADD_CLIPPER_CCP4 = ../clipper/ccp4/libclipper-ccp4.la
ADD_CLIPPER_MMDB = ../clipper/mmdb/libclipper-mmdb.la
ADD_CLIPPER_CIF = ../clipper/cif/libclipper-cif.la
ADD_CLIPPER_CONTRIB = ../clipper/contrib/libclipper-contrib.la
ccad_LDADD = $(ADD_CLIPPER_CCP4) $(LDADD)
cctbxtest_LDADD = ../clipper/cctbx/libclipper-cctbx.la $(ADD_CLIPPER_CONTRIB) $(LDADD)
ciftophs_LDADD = ../clipper/phs/libclipper-phs.la $(ADD_CLIPPER_CIF) $(LDADD)
cmaplocal_LDADD = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_CONTRIB) $(LDADD)
cns2mtz_LDADD = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_MMDB) $(LDADD)
cnstest_LDADD = ../clipper/cns/libclipper-cns.la $(ADD_CLIPPER_CCP4) $(LDADD)
diffmap_LDADD = $(ADD_CLIPPER_CCP4) $(LDADD)
ffttest_LDADD = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_CONTRIB) $(LDADD)
ftndemo_LDADD = ../clipper/fortran/libclipper-fortran.la $(LDADD) $(FLIBS)
maketestdata_LDADD = $(ADD_CLIPPER_MMDB) $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_CONTRIB) $(LDADD)
maptest_LDADD = $(ADD_CLIPPER_CCP4) $(LDADD)
mtztest_LDADD = $(ADD_CLIPPER_CCP4) $(LDADD)
phstest_LDADD = ../clipper/phs/libclipper-phs.la $(ADD_CLIPPER_CCP4) $(LDADD)
sftest_LDADD = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_MMDB) $(ADD_CLIPPER_CONTRIB) $(LDADD)
sktest_LDADD = $(ADD_CLIPPER_CCP4) $(ADD_CLIPPER_CONTRIB) $(LDADD)
EXTRA_DIST = test.csh test.log testfile.mtz
all: all-am

.SUFFIXES:
.SUFFIXES: .cpp .f .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign examples/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign examples/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

clean-checkPROGRAMS:
	@list='$(check_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list

ccad$(EXEEXT): $(ccad_OBJECTS) $(ccad_DEPENDENCIES) $(EXTRA_ccad_DEPENDENCIES) 
	@rm -f ccad$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(ccad_OBJECTS) $(ccad_LDADD) $(LIBS)

cctbxtest$(EXEEXT): $(cctbxtest_OBJECTS) $(cctbxtest_DEPENDENCIES) $(EXTRA_cctbxtest_DEPENDENCIES) 
	@rm -f cctbxtest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(cctbxtest_OBJECTS) $(cctbxtest_LDADD) $(LIBS)

ciftophs$(EXEEXT): $(ciftophs_OBJECTS) $(ciftophs_DEPENDENCIES) $(EXTRA_ciftophs_DEPENDENCIES) 
	@rm -f ciftophs$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(ciftophs_OBJECTS) $(ciftophs_LDADD) $(LIBS)

cmaplocal$(EXEEXT): $(cmaplocal_OBJECTS) $(cmaplocal_DEPENDENCIES) $(EXTRA_cmaplocal_DEPENDENCIES) 
	@rm -f cmaplocal$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(cmaplocal_OBJECTS) $(cmaplocal_LDADD) $(LIBS)

cns2mtz$(EXEEXT): $(cns2mtz_OBJECTS) $(cns2mtz_DEPENDENCIES) $(EXTRA_cns2mtz_DEPENDENCIES) 
	@rm -f cns2mtz$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(cns2mtz_OBJECTS) $(cns2mtz_LDADD) $(LIBS)

cnstest$(EXEEXT): $(cnstest_OBJECTS) $(cnstest_DEPENDENCIES) $(EXTRA_cnstest_DEPENDENCIES) 
	@rm -f cnstest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(cnstest_OBJECTS) $(cnstest_LDADD) $(LIBS)

diffmap$(EXEEXT): $(diffmap_OBJECTS) $(diffmap_DEPENDENCIES) $(EXTRA_diffmap_DEPENDENCIES) 
	@rm -f diffmap$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(diffmap_OBJECTS) $(diffmap_LDADD) $(LIBS)

ffttest$(EXEEXT): $(ffttest_OBJECTS) $(ffttest_DEPENDENCIES) $(EXTRA_ffttest_DEPENDENCIES) 
	@rm -f ffttest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(ffttest_OBJECTS) $(ffttest_LDADD) $(LIBS)

ftndemo$(EXEEXT): $(ftndemo_OBJECTS) $(ftndemo_DEPENDENCIES) $(EXTRA_ftndemo_DEPENDENCIES) 
	@rm -f ftndemo$(EXEEXT)
	$(AM_V_GEN)$(ftndemo_LINK) $(ftndemo_OBJECTS) $(ftndemo_LDADD) $(LIBS)

maketestdata$(EXEEXT): $(maketestdata_OBJECTS) $(maketestdata_DEPENDENCIES) $(EXTRA_maketestdata_DEPENDENCIES) 
	@rm -f maketestdata$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(maketestdata_OBJECTS) $(maketestdata_LDADD) $(LIBS)

maptest$(EXEEXT): $(maptest_OBJECTS) $(maptest_DEPENDENCIES) $(EXTRA_maptest_DEPENDENCIES) 
	@rm -f maptest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(maptest_OBJECTS) $(maptest_LDADD) $(LIBS)

mtztest$(EXEEXT): $(mtztest_OBJECTS) $(mtztest_DEPENDENCIES) $(EXTRA_mtztest_DEPENDENCIES) 
	@rm -f mtztest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(mtztest_OBJECTS) $(mtztest_LDADD) $(LIBS)

phstest$(EXEEXT): $(phstest_OBJECTS) $(phstest_DEPENDENCIES) $(EXTRA_phstest_DEPENDENCIES) 
	@rm -f phstest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(phstest_OBJECTS) $(phstest_LDADD) $(LIBS)

rfltest$(EXEEXT): $(rfltest_OBJECTS) $(rfltest_DEPENDENCIES) $(EXTRA_rfltest_DEPENDENCIES) 
	@rm -f rfltest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(rfltest_OBJECTS) $(rfltest_LDADD) $(LIBS)

sftest$(EXEEXT): $(sftest_OBJECTS) $(sftest_DEPENDENCIES) $(EXTRA_sftest_DEPENDENCIES) 
	@rm -f sftest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(sftest_OBJECTS) $(sftest_LDADD) $(LIBS)

sgtest$(EXEEXT): $(sgtest_OBJECTS) $(sgtest_DEPENDENCIES) $(EXTRA_sgtest_DEPENDENCIES) 
	@rm -f sgtest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(sgtest_OBJECTS) $(sgtest_LDADD) $(LIBS)

sktest$(EXEEXT): $(sktest_OBJECTS) $(sktest_DEPENDENCIES) $(EXTRA_sktest_DEPENDENCIES) 
	@rm -f sktest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(sktest_OBJECTS) $(sktest_LDADD) $(LIBS)

symtest$(EXEEXT): $(symtest_OBJECTS) $(symtest_DEPENDENCIES) $(EXTRA_symtest_DEPENDENCIES) 
	@rm -f symtest$(EXEEXT)
	$(AM_V_CXXLD)$(CXXLINK) $(symtest_OBJECTS) $(symtest_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/ccad.Po
include ./$(DEPDIR)/cctbxtest.Po
include ./$(DEPDIR)/ciftophs.Po
include ./$(DEPDIR)/cmaplocal.Po
include ./$(DEPDIR)/cns2mtz.Po
include ./$(DEPDIR)/cnstest.Po
include ./$(DEPDIR)/diffmap.Po
include ./$(DEPDIR)/ffttest.Po
include ./$(DEPDIR)/maketestdata.Po
include ./$(DEPDIR)/maptest.Po
include ./$(DEPDIR)/mtztest.Po
include ./$(DEPDIR)/phstest.Po
include ./$(DEPDIR)/rfltest.Po
include ./$(DEPDIR)/sftest.Po
include ./$(DEPDIR)/sgtest.Po
include ./$(DEPDIR)/sktest.Po
include ./$(DEPDIR)/symtest.Po

.cpp.o:
	$(AM_V_CXX)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.o$$||'`;\
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CXX)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(AM_V_CXX_no)$(CXXCOMPILE) -c -o $@ $<

.cpp.obj:
	$(AM_V_CXX)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.obj$$||'`;\
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ `$(CYGPATH_W) '$<'` &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CXX)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(AM_V_CXX_no)$(CXXCOMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.cpp.lo:
	$(AM_V_CXX)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.lo$$||'`;\
	$(LTCXXCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Plo
#	$(AM_V_CXX)source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(AM_V_CXX_no)$(LTCXXCOMPILE) -c -o $@ $<

.f.o:
	$(AM_V_F77)$(F77COMPILE) -c -o $@ $<

.f.obj:
	$(AM_V_F77)$(F77COMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.f.lo:
	$(AM_V_F77)$(LTF77COMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
	$(MAKE) $(AM_MAKEFLAGS) $(check_PROGRAMS)
check: check-am
all-am: Makefile
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-checkPROGRAMS clean-generic clean-libtool \
	mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am:

.MAKE: check-am install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean \
	clean-checkPROGRAMS clean-generic clean-libtool cscopelist-am \
	ctags ctags-am distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-dvi install-dvi-am install-exec \
	install-exec-am install-html install-html-am install-info \
	install-info-am install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags tags-am uninstall uninstall-am


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
