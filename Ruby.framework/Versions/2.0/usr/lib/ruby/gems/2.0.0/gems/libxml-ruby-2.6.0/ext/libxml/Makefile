
SHELL = /bin/sh

# V=0 quiet, V=1 verbose.  other values don't work.
V = 0
Q1 = $(V:1=)
Q = $(Q1:0=@)
ECHO1 = $(V:1=@:)
ECHO = $(ECHO1:0=@echo)

#### Start of system configuration section. ####

srcdir = .
topdir = /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.10.Internal.sdk/System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/include/ruby-2.0.0
hdrdir = $(topdir)
arch_hdrdir = /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.10.Internal.sdk/System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/include/ruby-2.0.0/universal-darwin14
PATH_SEPARATOR = :
VPATH = $(srcdir):$(arch_hdrdir)/ruby:$(hdrdir)/ruby
prefix = /System/Library/Frameworks/Ruby.framework/Versions/2.0/usr
rubysitearchprefix = $(rubylibprefix)/$(sitearch)
rubyarchprefix = $(rubylibprefix)/$(arch)
rubylibprefix = $(libdir)/$(RUBY_BASE_NAME)
exec_prefix = $(prefix)
vendorarchhdrdir = $(vendorhdrdir)/$(sitearch)
sitearchhdrdir = $(sitehdrdir)/$(sitearch)
rubyarchhdrdir = $(rubyhdrdir)/$(arch)
vendorhdrdir = $(rubyhdrdir)/vendor_ruby
sitehdrdir = $(rubyhdrdir)/site_ruby
rubyhdrdir = $(includedir)/$(RUBY_VERSION_NAME)
vendorarchdir = $(vendorlibdir)/$(sitearch)
vendorlibdir = $(vendordir)/$(ruby_version)
vendordir = $(rubylibprefix)/vendor_ruby
sitearchdir = ./.gem.20140909-41258-x2yhxi
sitelibdir = ./.gem.20140909-41258-x2yhxi
sitedir = $(DESTDIR)/Library/Ruby/Site
rubyarchdir = $(rubylibdir)/$(arch)
rubylibdir = $(rubylibprefix)/$(ruby_version)
sitearchincludedir = $(includedir)/$(sitearch)
archincludedir = $(includedir)/$(arch)
sitearchlibdir = $(libdir)/$(sitearch)
archlibdir = $(libdir)/$(arch)
ridir = $(datarootdir)/$(RI_BASE_NAME)
mandir = $(DESTDIR)/usr/share/man
localedir = $(datarootdir)/locale
libdir = $(exec_prefix)/lib
psdir = $(docdir)
pdfdir = $(docdir)
dvidir = $(docdir)
htmldir = $(docdir)
infodir = $(DESTDIR)/usr/share/info
docdir = $(datarootdir)/doc/$(PACKAGE)
oldincludedir = /usr/include
includedir = /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.10.Internal.sdk$(prefix)/include
localstatedir = $(prefix)/var
sharedstatedir = $(prefix)/com
sysconfdir = $(DESTDIR)/Library/Ruby/Site
datadir = $(datarootdir)
datarootdir = $(prefix)/share
libexecdir = $(exec_prefix)/libexec
sbindir = $(exec_prefix)/sbin
bindir = $(exec_prefix)/bin
archdir = $(rubyarchdir)


CC = xcrun clang
CXX = xcrun clang++
LIBRUBY = $(LIBRUBY_SO)
LIBRUBY_A = lib$(RUBY_SO_NAME)-static.a
LIBRUBYARG_SHARED = -l$(RUBY_SO_NAME)
LIBRUBYARG_STATIC = -l$(RUBY_SO_NAME)-static
empty =
OUTFLAG = -o $(empty)
COUTFLAG = -o $(empty)

RUBY_EXTCONF_H = extconf.h
cflags   =  $(optflags) $(debugflags) $(warnflags)
optflags = 
debugflags = -g
warnflags = 
CCDLFLAGS = 
CFLAGS   = $(CCDLFLAGS)  -g -Os -pipe -DHAVE_GCC_SYNC_BUILTINS -I/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.10.Internal.sdk/usr/include/libxml2 -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir) -I/usr/local/include $(ARCH_FLAG)
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir) -I/usr/local/include
DEFS     = 
CPPFLAGS = -DRUBY_EXTCONF_H=\"$(RUBY_EXTCONF_H)\" -D_XOPEN_SOURCE -D_DARWIN_C_SOURCE -D_DARWIN_UNLIMITED_SELECT -D_REENTRANT $(DEFS) $(cppflags)
CXXFLAGS = $(CCDLFLAGS) $(ARCH_FLAG) -g -Os -pipe  $(ARCH_FLAG)
ldflags  = -L. -L/usr/local/lib
dldflags = -Wl,-undefined,dynamic_lookup -Wl,-multiply_defined,suppress 
ARCH_FLAG = -arch x86_64
DLDFLAGS = $(ldflags) $(dldflags) $(ARCH_FLAG)
LDSHARED = $(CC) -dynamic -bundle
LDSHAREDXX = $(CXX) -dynamic -bundle
AR = ar
EXEEXT = 

RUBY_INSTALL_NAME = ruby
RUBY_SO_NAME = ruby.2.0.0
RUBYW_INSTALL_NAME = 
RUBY_VERSION_NAME = $(RUBY_BASE_NAME)-$(ruby_version)
RUBYW_BASE_NAME = rubyw
RUBY_BASE_NAME = ruby

arch = universal-darwin14
sitearch = $(arch)
ruby_version = 2.0.0
ruby = $(bindir)/ruby
RUBY = $(ruby)
ruby_headers = $(hdrdir)/ruby.h $(hdrdir)/ruby/defines.h $(arch_hdrdir)/ruby/config.h $(RUBY_EXTCONF_H)

RM = rm -f
RM_RF = $(RUBY) -run -e rm -- -rf
RMDIRS = rmdir -p
MAKEDIRS = mkdir -p
INSTALL = /usr/bin/install -c
INSTALL_PROG = $(INSTALL) -m 0755
INSTALL_DATA = $(INSTALL) -m 644
COPY = cp
TOUCH = exit >

#### End of system configuration section. ####

preload = 

libpath = . $(libdir) /System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/lib
LIBPATH =  -L. -L$(libdir) -L/System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/lib
DEFFILE = 

CLEANFILES = mkmf.log
DISTCLEANFILES = 
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = 
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED) -lxml2 -lxml2 -liconv -lz -lm  -lpthread -ldl -lobjc 
ORIG_SRCS = libxml.c ruby_xml.c ruby_xml_attr.c ruby_xml_attr_decl.c ruby_xml_attributes.c ruby_xml_cbg.c ruby_xml_document.c ruby_xml_dtd.c ruby_xml_encoding.c ruby_xml_error.c ruby_xml_html_parser.c ruby_xml_html_parser_context.c ruby_xml_html_parser_options.c ruby_xml_input_cbg.c ruby_xml_io.c ruby_xml_namespace.c ruby_xml_namespaces.c ruby_xml_node.c ruby_xml_parser.c ruby_xml_parser_context.c ruby_xml_parser_options.c ruby_xml_reader.c ruby_xml_relaxng.c ruby_xml_sax2_handler.c ruby_xml_sax_parser.c ruby_xml_schema.c ruby_xml_schema_attribute.c ruby_xml_schema_element.c ruby_xml_schema_facet.c ruby_xml_schema_type.c ruby_xml_writer.c ruby_xml_xinclude.c ruby_xml_xpath.c ruby_xml_xpath_context.c ruby_xml_xpath_expression.c ruby_xml_xpath_object.c ruby_xml_xpointer.c
SRCS = $(ORIG_SRCS) 
OBJS = libxml.o ruby_xml.o ruby_xml_attr.o ruby_xml_attr_decl.o ruby_xml_attributes.o ruby_xml_cbg.o ruby_xml_document.o ruby_xml_dtd.o ruby_xml_encoding.o ruby_xml_error.o ruby_xml_html_parser.o ruby_xml_html_parser_context.o ruby_xml_html_parser_options.o ruby_xml_input_cbg.o ruby_xml_io.o ruby_xml_namespace.o ruby_xml_namespaces.o ruby_xml_node.o ruby_xml_parser.o ruby_xml_parser_context.o ruby_xml_parser_options.o ruby_xml_reader.o ruby_xml_relaxng.o ruby_xml_sax2_handler.o ruby_xml_sax_parser.o ruby_xml_schema.o ruby_xml_schema_attribute.o ruby_xml_schema_element.o ruby_xml_schema_facet.o ruby_xml_schema_type.o ruby_xml_writer.o ruby_xml_xinclude.o ruby_xml_xpath.o ruby_xml_xpath_context.o ruby_xml_xpath_expression.o ruby_xml_xpath_object.o ruby_xml_xpointer.o
HDRS = $(srcdir)/extconf.h $(srcdir)/ruby_libxml.h $(srcdir)/ruby_xml.h $(srcdir)/ruby_xml_attr.h $(srcdir)/ruby_xml_attr_decl.h $(srcdir)/ruby_xml_attributes.h $(srcdir)/ruby_xml_document.h $(srcdir)/ruby_xml_dtd.h $(srcdir)/ruby_xml_encoding.h $(srcdir)/ruby_xml_error.h $(srcdir)/ruby_xml_html_parser.h $(srcdir)/ruby_xml_html_parser_context.h $(srcdir)/ruby_xml_html_parser_options.h $(srcdir)/ruby_xml_input_cbg.h $(srcdir)/ruby_xml_io.h $(srcdir)/ruby_xml_namespace.h $(srcdir)/ruby_xml_namespaces.h $(srcdir)/ruby_xml_node.h $(srcdir)/ruby_xml_parser.h $(srcdir)/ruby_xml_parser_context.h $(srcdir)/ruby_xml_parser_options.h $(srcdir)/ruby_xml_reader.h $(srcdir)/ruby_xml_relaxng.h $(srcdir)/ruby_xml_sax2_handler.h $(srcdir)/ruby_xml_sax_parser.h $(srcdir)/ruby_xml_schema.h $(srcdir)/ruby_xml_schema_attribute.h $(srcdir)/ruby_xml_schema_element.h $(srcdir)/ruby_xml_schema_facet.h $(srcdir)/ruby_xml_schema_type.h $(srcdir)/ruby_xml_version.h $(srcdir)/ruby_xml_writer.h $(srcdir)/ruby_xml_xinclude.h $(srcdir)/ruby_xml_xpath.h $(srcdir)/ruby_xml_xpath_context.h $(srcdir)/ruby_xml_xpath_expression.h $(srcdir)/ruby_xml_xpath_object.h $(srcdir)/ruby_xml_xpointer.h
TARGET = libxml_ruby
TARGET_NAME = libxml_ruby
TARGET_ENTRY = Init_$(TARGET_NAME)
DLLIB = $(TARGET).bundle
EXTSTATIC = 
STATIC_LIB = 

BINDIR        = $(DESTDIR)$(bindir)
RUBYCOMMONDIR = $(DESTDIR)$(sitedir)$(target_prefix)
RUBYLIBDIR    = $(DESTDIR)$(sitelibdir)$(target_prefix)
RUBYARCHDIR   = $(DESTDIR)$(sitearchdir)$(target_prefix)
HDRDIR        = $(DESTDIR)$(rubyhdrdir)/ruby$(target_prefix)
ARCHHDRDIR    = $(DESTDIR)$(rubyhdrdir)/$(arch)/ruby$(target_prefix)

TARGET_SO     = $(DLLIB)
CLEANLIBS     = $(TARGET).bundle 
CLEANOBJS     = *.o  *.bak

all:    $(DLLIB)
static: $(STATIC_LIB)
.PHONY: all install static install-so install-rb
.PHONY: clean clean-so clean-static clean-rb

clean-static::
clean-rb-default::
clean-rb::
clean-so::
clean: clean-so clean-static clean-rb-default clean-rb
		-$(Q)$(RM) $(CLEANLIBS) $(CLEANOBJS) $(CLEANFILES) .*.time

distclean-rb-default::
distclean-rb::
distclean-so::
distclean-static::
distclean: clean distclean-so distclean-static distclean-rb-default distclean-rb
		-$(Q)$(RM) Makefile $(RUBY_EXTCONF_H) conftest.* mkmf.log
		-$(Q)$(RM) core ruby$(EXEEXT) *~ $(DISTCLEANFILES)
		-$(Q)$(RMDIRS) $(DISTCLEANDIRS) 2> /dev/null || true

realclean: distclean
install: install-so install-rb

install-so: $(DLLIB) ./.RUBYARCHDIR.time
	$(INSTALL_PROG) $(DLLIB) $(RUBYARCHDIR)
clean-static::
	-$(Q)$(RM) $(STATIC_LIB)
install-rb: pre-install-rb install-rb-default
install-rb-default: pre-install-rb-default
pre-install-rb: Makefile
pre-install-rb-default: Makefile
pre-install-rb-default:
	$(ECHO) installing default libxml_ruby libraries
./.RUBYARCHDIR.time:
	$(Q) $(MAKEDIRS) $(RUBYARCHDIR)
	$(Q) $(TOUCH) $@

site-install: site-install-so site-install-rb
site-install-so: install-so
site-install-rb: install-rb

.SUFFIXES: .c .m .cc .mm .cxx .cpp .C .o

.cc.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.mm.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.cxx.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.cpp.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.C.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.c.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $<

.m.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $<

$(DLLIB): $(OBJS) Makefile
	$(ECHO) linking shared-object $(DLLIB)
	-$(Q)$(RM) $(@)
	$(Q) $(LDSHARED) -o $@ $(OBJS) $(LIBPATH) $(DLDFLAGS) $(LOCAL_LIBS) $(LIBS)
	$(Q) test -z '$(RUBY_CODESIGN)' || codesign -s '$(RUBY_CODESIGN)' -f $@



$(OBJS): $(HDRS) $(ruby_headers)
