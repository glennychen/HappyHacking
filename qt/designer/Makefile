#############################################################################
# Makefile for building: designer
# Generated by qmake (2.01a) (Qt 4.4.3) on: Thu May 28 18:18:42 2009
# Project:  designer.pro
# Template: app
# Command: /usr/local/bin/qmake-qt4 -unix -o Makefile designer.pro
#############################################################################

####### Compiler, tools and options

CC            = cc
CXX           = c++
DEFINES       = -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -pipe -funroll-loops -march=athlon64 -fno-strict-aliasing -Wall -W $(DEFINES)
CXXFLAGS      = -pipe -O2 -pipe -funroll-loops -march=athlon64 -fno-strict-aliasing -Wall -W $(DEFINES)
INCPATH       = -I/usr/local/share/qt4/mkspecs/freebsd-g++ -I. -I/usr/local/include/qt4/QtCore -I/usr/local/include/qt4/QtCore -I/usr/local/include/qt4/QtGui -I/usr/local/include/qt4/QtGui -I/usr/local/include/qt4 -I. -I. -I. -I/usr/local/include
LINK          = c++
LFLAGS        = -pthread -Wl,-rpath,/usr/local/lib/qt4
LIBS          = $(SUBLIBS)  -L/usr/local/lib -L/usr/local/lib/qt4 -lQtGui -L/usr/local/lib/qt4 -L/usr/local/lib -pthread -lpng -lSM -lICE -pthread -pthread -lXi -lXrender -lXrandr -lfreetype -lfontconfig -lXext -lX11 -lQtCore -lz -lm -pthread -lgthread-2.0 -lglib-2.0 -liconv
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/local/bin/qmake-qt4
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -R
INSTALL_FILE  = $(COPY_FILE)
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = $(COPY_FILE)
DEL_FILE      = rm -f
SYMLINK       = ln -sf
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = main.cc \
		myqtapp.cc moc_myqtapp.cpp
OBJECTS       = main.o \
		myqtapp.o \
		moc_myqtapp.o
DIST          = /usr/local/share/qt4/mkspecs/common/unix.conf \
		/usr/local/share/qt4/mkspecs/qconfig.pri \
		/usr/local/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/local/share/qt4/mkspecs/features/qt_config.prf \
		/usr/local/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/local/share/qt4/mkspecs/features/default_pre.prf \
		/usr/local/share/qt4/mkspecs/features/release.prf \
		/usr/local/share/qt4/mkspecs/features/default_post.prf \
		/usr/local/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/local/share/qt4/mkspecs/features/warn_on.prf \
		/usr/local/share/qt4/mkspecs/features/qt.prf \
		/usr/local/share/qt4/mkspecs/features/moc.prf \
		/usr/local/share/qt4/mkspecs/features/resources.prf \
		/usr/local/share/qt4/mkspecs/features/uic.prf \
		/usr/local/share/qt4/mkspecs/features/yacc.prf \
		/usr/local/share/qt4/mkspecs/features/lex.prf \
		designer.pro
QMAKE_TARGET  = designer
DESTDIR       = 
TARGET        = designer

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET): ui_myqtapp.h $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: designer.pro  /usr/local/share/qt4/mkspecs/freebsd-g++/qmake.conf /usr/local/share/qt4/mkspecs/common/unix.conf \
		/usr/local/share/qt4/mkspecs/qconfig.pri \
		/usr/local/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/local/share/qt4/mkspecs/features/qt_config.prf \
		/usr/local/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/local/share/qt4/mkspecs/features/default_pre.prf \
		/usr/local/share/qt4/mkspecs/features/release.prf \
		/usr/local/share/qt4/mkspecs/features/default_post.prf \
		/usr/local/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/local/share/qt4/mkspecs/features/warn_on.prf \
		/usr/local/share/qt4/mkspecs/features/qt.prf \
		/usr/local/share/qt4/mkspecs/features/moc.prf \
		/usr/local/share/qt4/mkspecs/features/resources.prf \
		/usr/local/share/qt4/mkspecs/features/uic.prf \
		/usr/local/share/qt4/mkspecs/features/yacc.prf \
		/usr/local/share/qt4/mkspecs/features/lex.prf \
		/usr/local/lib/qt4/libQtGui.prl \
		/usr/local/lib/qt4/libQtCore.prl
	$(QMAKE) -unix -o Makefile designer.pro
/usr/local/share/qt4/mkspecs/common/unix.conf:
/usr/local/share/qt4/mkspecs/qconfig.pri:
/usr/local/share/qt4/mkspecs/features/qt_functions.prf:
/usr/local/share/qt4/mkspecs/features/qt_config.prf:
/usr/local/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/local/share/qt4/mkspecs/features/default_pre.prf:
/usr/local/share/qt4/mkspecs/features/release.prf:
/usr/local/share/qt4/mkspecs/features/default_post.prf:
/usr/local/share/qt4/mkspecs/features/unix/thread.prf:
/usr/local/share/qt4/mkspecs/features/warn_on.prf:
/usr/local/share/qt4/mkspecs/features/qt.prf:
/usr/local/share/qt4/mkspecs/features/moc.prf:
/usr/local/share/qt4/mkspecs/features/resources.prf:
/usr/local/share/qt4/mkspecs/features/uic.prf:
/usr/local/share/qt4/mkspecs/features/yacc.prf:
/usr/local/share/qt4/mkspecs/features/lex.prf:
/usr/local/lib/qt4/libQtGui.prl:
/usr/local/lib/qt4/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -unix -o Makefile designer.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/designer1.0.0 || $(MKDIR) .tmp/designer1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/designer1.0.0/ && $(COPY_FILE) --parents myqtapp.h .tmp/designer1.0.0/ && $(COPY_FILE) --parents main.cc myqtapp.cc .tmp/designer1.0.0/ && $(COPY_FILE) --parents myqtapp.ui .tmp/designer1.0.0/ && (cd `dirname .tmp/designer1.0.0` && $(TAR) designer1.0.0.tar designer1.0.0 && $(COMPRESS) designer1.0.0.tar) && $(MOVE) `dirname .tmp/designer1.0.0`/designer1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/designer1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_myqtapp.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_myqtapp.cpp
moc_myqtapp.cpp: ui_myqtapp.h \
		myqtapp.h
	/usr/local/bin/moc-qt4 $(DEFINES) $(INCPATH) myqtapp.h -o moc_myqtapp.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: ui_myqtapp.h
compiler_uic_clean:
	-$(DEL_FILE) ui_myqtapp.h
ui_myqtapp.h: myqtapp.ui
	/usr/local/bin/uic-qt4 myqtapp.ui -o ui_myqtapp.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_uic_clean 

####### Compile

main.o: main.cc myqtapp.h \
		ui_myqtapp.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cc

myqtapp.o: myqtapp.cc myqtapp.h \
		ui_myqtapp.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o myqtapp.o myqtapp.cc

moc_myqtapp.o: moc_myqtapp.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_myqtapp.o moc_myqtapp.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

