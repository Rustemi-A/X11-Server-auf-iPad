# Makefile.in generated by automake 1.15 from Makefile.am.
# doc/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2014 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



#
# Generate output formats for a single DocBook/XML with/without chapters
#
# Variables set by the calling Makefile:
# shelfdir: the location where the docs/specs are installed. Typically $(docdir)
# docbook:  the main DocBook/XML file, no chapters, appendix or image files
# chapters: all files pulled in by an XInclude statement and images.
#

#
# This makefile is intended for Users Documentation and Functional Specifications.
# Do not use for Developer Documentation which is not installed and does not require olink.
# Refer to http://www.x.org/releases/X11R7.6/doc/xorg-docs/ReleaseNotes.html#id2584393
# for an explanation on documents classification.
#


am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
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
pkgdatadir = $(datadir)/xtrans
pkgincludedir = $(includedir)/xtrans
pkglibdir = $(libdir)/xtrans
pkglibexecdir = $(libexecdir)/xtrans
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
build_triplet = x86_64-pc-linux-gnu
host_triplet = x86_64-pc-linux-gnu
#am__append_1 = $(docbook:.xml=.html)
##am__append_2 = $(docbook:.xml=.txt)
##am__append_3 = $(docbook:.xml=.pdf) \
##	$(docbook:.xml=.ps)
##am__append_4 = $(docbook:.xml=.html.db) \
##	$(docbook:.xml=.pdf.db)
subdir = doc
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__dist_shelf_DATA_DIST) \
	$(am__DIST_COMMON)
mkinstalldirs = $(install_sh) -d
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
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
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__dist_shelf_DATA_DIST = xtrans.xml
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(shelfdir)" "$(DESTDIR)$(shelfdir)"
DATA = $(dist_shelf_DATA) $(shelf_DATA)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__DIST_COMMON = $(srcdir)/Makefile.in $(top_srcdir)/docbook.am
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/adduser/xtrans-1.4.0/missing aclocal-1.15
ADMIN_MAN_DIR = $(mandir)/man$(ADMIN_MAN_SUFFIX)
ADMIN_MAN_SUFFIX = 8
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 0
APP_MAN_DIR = $(mandir)/man$(APP_MAN_SUFFIX)
APP_MAN_SUFFIX = 1
AUTOCONF = ${SHELL} /home/adduser/xtrans-1.4.0/missing autoconf
AUTOHEADER = ${SHELL} /home/adduser/xtrans-1.4.0/missing autoheader
AUTOMAKE = ${SHELL} /home/adduser/xtrans-1.4.0/missing automake-1.15
AWK = gawk
BASE_CFLAGS =  -Wall -Wpointer-arith -Wmissing-declarations -Wformat=2 -Wstrict-prototypes -Wmissing-prototypes -Wnested-externs -Wbad-function-cast -Wold-style-definition -Wdeclaration-after-statement -Wunused -Wuninitialized -Wshadow -Wmissing-noreturn -Wmissing-format-attribute -Wredundant-decls -Wlogical-op -Werror=implicit -Werror=nonnull -Werror=init-self -Werror=main -Werror=missing-braces -Werror=sequence-point -Werror=return-type -Werror=trigraphs -Werror=array-bounds -Werror=write-strings -Werror=address -Werror=int-to-pointer-cast -Werror=pointer-to-int-cast
CC = gcc
CCDEPMODE = depmode=none
CFLAGS = -g -O2
CHANGELOG_CMD = (GIT_DIR=$(top_srcdir)/.git git log > $(top_srcdir)/.changelog.tmp && mv $(top_srcdir)/.changelog.tmp $(top_srcdir)/ChangeLog) || (rm -f $(top_srcdir)/.changelog.tmp; touch $(top_srcdir)/ChangeLog; echo 'git directory not found: installing possibly empty changelog.' >&2)
CPP = gcc -E
CPPFLAGS = 
CWARNFLAGS =  -Wall -Wpointer-arith -Wmissing-declarations -Wformat=2 -Wstrict-prototypes -Wmissing-prototypes -Wnested-externs -Wbad-function-cast -Wold-style-definition -Wdeclaration-after-statement -Wunused -Wuninitialized -Wshadow -Wmissing-noreturn -Wmissing-format-attribute -Wredundant-decls -Wlogical-op -Werror=implicit -Werror=nonnull -Werror=init-self -Werror=main -Werror=missing-braces -Werror=sequence-point -Werror=return-type -Werror=trigraphs -Werror=array-bounds -Werror=write-strings -Werror=address -Werror=int-to-pointer-cast -Werror=pointer-to-int-cast -fno-strict-aliasing
CYGPATH_W = echo
DEFS = -DPACKAGE_NAME=\"xtrans\" -DPACKAGE_TARNAME=\"xtrans\" -DPACKAGE_VERSION=\"1.4.0\" -DPACKAGE_STRING=\"xtrans\ 1.4.0\" -DPACKAGE_BUGREPORT=\"https://gitlab.freedesktop.org/xorg/lib/libxtrans/issues\" -DPACKAGE_URL=\"\" -DPACKAGE=\"xtrans\" -DVERSION=\"1.4.0\" -DSTDC_HEADERS=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_STAT_H=1 -DHAVE_STDLIB_H=1 -DHAVE_STRING_H=1 -DHAVE_MEMORY_H=1 -DHAVE_STRINGS_H=1 -DHAVE_INTTYPES_H=1 -DHAVE_STDINT_H=1 -DHAVE_UNISTD_H=1 -DPACKAGE_VERSION_MAJOR=1 -DPACKAGE_VERSION_MINOR=4 -DPACKAGE_VERSION_PATCHLEVEL=0
DEPDIR = .deps
DRIVER_MAN_DIR = $(mandir)/man$(DRIVER_MAN_SUFFIX)
DRIVER_MAN_SUFFIX = 4
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /usr/bin/grep -E
EXEEXT = 
FILE_MAN_DIR = $(mandir)/man$(FILE_MAN_SUFFIX)
FILE_MAN_SUFFIX = 5
FOP = 
GREP = /usr/bin/grep
INSTALL = /usr/bin/install -c
INSTALL_CMD = (cp -f /INSTALL $(top_srcdir)/.INSTALL.tmp && mv $(top_srcdir)/.INSTALL.tmp $(top_srcdir)/INSTALL) || (rm -f $(top_srcdir)/.INSTALL.tmp; touch $(top_srcdir)/INSTALL; echo 'util-macros "pkgdatadir" from xorg-macros.pc not found: installing possibly empty INSTALL.' >&2)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LDFLAGS = 
LIBOBJS = 
LIBS = 
LIB_MAN_DIR = $(mandir)/man$(LIB_MAN_SUFFIX)
LIB_MAN_SUFFIX = 3
LTLIBOBJS = 
MAKEINFO = ${SHELL} /home/adduser/xtrans-1.4.0/missing makeinfo
MAN_SUBSTS = 	-e 's|__vendorversion__|"$(PACKAGE_STRING)" "$(XORG_MAN_PAGE)"|' 	-e 's|__xorgversion__|"$(PACKAGE_STRING)" "$(XORG_MAN_PAGE)"|' 	-e 's|__xservername__|Xorg|g' 	-e 's|__xconfigfile__|xorg.conf|g' 	-e 's|__projectroot__|$(prefix)|g' 	-e 's|__apploaddir__|$(appdefaultdir)|g' 	-e 's|__appmansuffix__|$(APP_MAN_SUFFIX)|g' 	-e 's|__drivermansuffix__|$(DRIVER_MAN_SUFFIX)|g' 	-e 's|__adminmansuffix__|$(ADMIN_MAN_SUFFIX)|g' 	-e 's|__libmansuffix__|$(LIB_MAN_SUFFIX)|g' 	-e 's|__miscmansuffix__|$(MISC_MAN_SUFFIX)|g' 	-e 's|__filemansuffix__|$(FILE_MAN_SUFFIX)|g'
MISC_MAN_DIR = $(mandir)/man$(MISC_MAN_SUFFIX)
MISC_MAN_SUFFIX = 7
MKDIR_P = /usr/bin/mkdir -p
OBJEXT = o
PACKAGE = xtrans
PACKAGE_BUGREPORT = https://gitlab.freedesktop.org/xorg/lib/libxtrans/issues
PACKAGE_NAME = xtrans
PACKAGE_STRING = xtrans 1.4.0
PACKAGE_TARNAME = xtrans
PACKAGE_URL = 
PACKAGE_VERSION = 1.4.0
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
SED = /usr/bin/sed
SET_MAKE = 
SHELL = /bin/bash
STRICT_CFLAGS =  -pedantic -Werror -Werror=attributes
STRIP = 
STYLESHEET_SRCDIR = /usr/share/sgml/X11
VERSION = 1.4.0
XMLTO = 
XORG_MAN_PAGE = X Version 11
XORG_SGML_PATH = /usr/share/sgml
XSLTPROC = 
XSL_STYLESHEET = /usr/share/sgml/X11/xorg.xsl
abs_builddir = /home/adduser/xtrans-1.4.0/doc
abs_srcdir = /home/adduser/xtrans-1.4.0/doc
abs_top_builddir = /home/adduser/xtrans-1.4.0
abs_top_srcdir = /home/adduser/xtrans-1.4.0
ac_ct_CC = gcc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-pc-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
fchown_define = -DHAS_FCHOWN
host = x86_64-pc-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/adduser/xtrans-1.4.0/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local/xtrans/1_4_0
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sticky_bit_define = -DHAS_STICKY_DIR_BIT
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..

# Main DocBook/XML files (DOCTYPE book)
docbook = xtrans.xml

# The location where the DocBook/XML files and their generated formats are installed
shelfdir = $(docdir)

# DocBook/XML generated output formats to be installed
shelf_DATA = $(am__append_1) $(am__append_2) \
	$(am__append_3) $(am__append_4)

# DocBook/XML file with chapters, appendix and images it includes
dist_shelf_DATA = $(docbook) $(chapters)
#XMLTO_SEARCHPATH_FLAGS = \
#	--searchpath "$(XORG_SGML_PATH)/X11" 		\
#	--searchpath "$(abs_top_builddir)"

#XMLTO_HTML_OLINK_FLAGS = \
#	--stringparam target.database.document=$(XORG_SGML_PATH)/X11/dbs/masterdb.html.xml \
#	--stringparam current.docid="$(<:.xml=)"

#XMLTO_HTML_STYLESHEET_FLAGS = -x $(STYLESHEET_SRCDIR)/xorg-xhtml.xsl
#XMLTO_HTML_FLAGS = \
#	$(XMLTO_SEARCHPATH_FLAGS)			\
#	$(XMLTO_HTML_STYLESHEET_FLAGS)			\
#	$(XMLTO_HTML_OLINK_FLAGS)

##XMLTO_FO_IMAGEPATH_FLAGS = --stringparam img.src.path=$(abs_builddir)/
##XMLTO_PDF_OLINK_FLAGS = \
##	--stringparam target.database.document=$(XORG_SGML_PATH)/X11/dbs/masterdb.pdf.xml \
##	--stringparam current.docid="$(<:.xml=)"

##XMLTO_FO_STYLESHEET_FLAGS = -x $(STYLESHEET_SRCDIR)/xorg-fo.xsl
##XMLTO_FO_FLAGS = \
##	$(XMLTO_SEARCHPATH_FLAGS)			\
##	$(XMLTO_FO_STYLESHEET_FLAGS)			\
##	$(XMLTO_FO_IMAGEPATH_FLAGS)			\
##	$(XMLTO_PDF_OLINK_FLAGS)


# Generate documents cross-reference target databases
##XSLT_SEARCHPATH_FLAGS = \
##	--path "$(XORG_SGML_PATH)/X11"			\
##	--path "$(abs_top_builddir)"

##XSLT_OLINK_FLAGS = \
##	--stringparam targets.filename "$@" 		\
##	--stringparam collect.xref.targets "only" 	\
##	--stringparam olink.base.uri "$(@:.db=)"

##XSLT_HTML_FLAGS = \
##	$(XSLT_SEARCHPATH_FLAGS) 			\
##	$(XSLT_OLINK_FLAGS)				\
##	--nonet --xinclude				\
##	$(STYLESHEET_SRCDIR)/xorg-xhtml.xsl

##XSLT_PDF_FLAGS = \
##	$(XSLT_SEARCHPATH_FLAGS) 			\
##	$(XSLT_OLINK_FLAGS)				\
##	--nonet --xinclude				\
##	$(STYLESHEET_SRCDIR)/xorg-fo.xsl

CLEANFILES = $(shelf_DATA)
all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am $(top_srcdir)/docbook.am $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign doc/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign doc/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;
$(top_srcdir)/docbook.am $(am__empty):

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-dist_shelfDATA: $(dist_shelf_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_shelf_DATA)'; test -n "$(shelfdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(shelfdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(shelfdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(shelfdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(shelfdir)" || exit $$?; \
	done

uninstall-dist_shelfDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_shelf_DATA)'; test -n "$(shelfdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(shelfdir)'; $(am__uninstall_files_from_dir)
install-shelfDATA: $(shelf_DATA)
	@$(NORMAL_INSTALL)
	@list='$(shelf_DATA)'; test -n "$(shelfdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(shelfdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(shelfdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(shelfdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(shelfdir)" || exit $$?; \
	done

uninstall-shelfDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(shelf_DATA)'; test -n "$(shelfdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(shelfdir)'; $(am__uninstall_files_from_dir)
tags TAGS:

ctags CTAGS:

cscope cscopelist:


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
check: check-am
all-am: Makefile $(DATA)
installdirs:
	for dir in "$(DESTDIR)$(shelfdir)" "$(DESTDIR)$(shelfdir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
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
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-dist_shelfDATA install-shelfDATA

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
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-dist_shelfDATA uninstall-shelfDATA

.MAKE: install-am install-strip

.PHONY: all all-am check check-am clean clean-generic cscopelist-am \
	ctags-am distclean distclean-generic distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-dist_shelfDATA install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-info install-info-am install-man \
	install-pdf install-pdf-am install-ps install-ps-am \
	install-shelfDATA install-strip installcheck installcheck-am \
	installdirs maintainer-clean maintainer-clean-generic \
	mostlyclean mostlyclean-generic pdf pdf-am ps ps-am tags-am \
	uninstall uninstall-am uninstall-dist_shelfDATA \
	uninstall-shelfDATA

.PRECIOUS: Makefile

#%.html: %.xml $(chapters)
#	$(AM_V_GEN)$(XMLTO) $(XMLTO_HTML_FLAGS) xhtml-nochunks $<
##%.txt: %.xml $(chapters)
##	$(AM_V_GEN)$(XMLTO) $(XMLTO_HTML_FLAGS) txt $<
##%.pdf: %.xml $(chapters)
##	$(AM_V_GEN)$(XMLTO) $(XMLTO_FO_FLAGS) --with-fop pdf $<
##%.ps: %.xml $(chapters)
##	$(AM_V_GEN)$(XMLTO) $(XMLTO_FO_FLAGS) --with-fop ps $<
##%.html.db: %.xml  $(chapters)
##	$(AM_V_GEN)$(XSLTPROC) $(XSLT_HTML_FLAGS) $<
##%.pdf.db: %.xml $(chapters)
##	$(AM_V_GEN)$(XSLTPROC) $(XSLT_PDF_FLAGS) $<

# Generate DocBook/XML output formats with or without stylesheets

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
