#############################################################################
# Makefile for building: EAP-SIM-GW
# Generated by qmake (3.0) (Qt 5.1.0) on: ?? 29. ??? 12:59:13 2014
# Project:  ..\EAP-SIM-GW\EAP-SIM-GW.pro
# Template: app
#############################################################################

MAKEFILE      = Makefile.Release

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DUNICODE -DSTATIC -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_CORE_LIB
CFLAGS        = -pipe -O2 -Wall -Wextra $(DEFINES)
CXXFLAGS      = -pipe -std=c++0x -Wcomment -O2 -frtti -Wall -Wextra -fexceptions -pthread $(DEFINES)
INCPATH       = -I../EAP-SIM-GW -I"/opt/DSI/INC" -I"release" -I"." 
LINKER      =        g++
LFLAGS        =        -static-libgcc -Wl,-s -Wl,-subsystem
LIBS        =        /opt/DSI/64/libgctlib.so 
QMAKE         = qmake.exe
IDC           = idc
IDL           = midl
ZIP           = zip -r -9
DEF_FILE      = 
RES_FILE      = 
COPY          = copy /y
SED           = 
COPY_FILE     = $(COPY)
COPY_DIR      = xcopy /s /q /y /i
DEL_FILE      = rm
DEL_DIR       = rmdir
MOVE          = move
CHK_DIR_EXISTS= if not exist
MKDIR         = mkdir
INSTALL_FILE    = $(COPY_FILE)
INSTALL_PROGRAM = $(COPY_FILE)
INSTALL_DIR     = $(COPY_DIR)

####### Output directory

OBJECTS_DIR   = release

####### Files

SOURCES       = ../EAP-SIM-GW/PSPacket.cpp \
		../EAP-SIM-GW/mtu_main.cpp \
		../EAP-SIM-GW/mtu_fmt.cpp \
		../EAP-SIM-GW/mtu.cpp 
OBJECTS       = release/PSPacket.o \
		release/mtu_main.o \
		release/mtu_fmt.o \
		release/mtu.o

DIST          = 
QMAKE_TARGET  = EAP-SIM-GW
DESTDIR        = release/ #avoid trailing-slash linebreak
TARGET         = eap-sim-gw
DESTDIR_TARGET = release/eap-sim-gw

####### Implicit rules

.SUFFIXES: .cpp .cc .cxx .c

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o $@ $<

####### Build rules

first: all
all: Makefile  $(DESTDIR_TARGET)

$(DESTDIR_TARGET):  $(OBJECTS) 
	$(LINKER) $(LFLAGS) -o $(DESTDIR_TARGET) $(OBJECTS)  $(LIBS)

qmake: FORCE
	@$(QMAKE) -spec win32-g++ -o Makefile.Release ../EAP-SIM-GW/EAP-SIM-GW.pro

qmake_all: FORCE

dist:
	$(ZIP) EAP-SIM-GW.zip $(SOURCES) $(DIST) ../EAP-SIM-GW/EAP-SIM-GW.pro ../../Qt/Qt5.1.0/5.1.0/mingw48_32/mkspecs/features/spec_pre.prf ../../Qt/Qt5.1.0/5.1.0/mingw48_32/mkspecs/qdevice.pri ../../Qt/Qt5.1.0/5.1.0/mingw48_32/mkspecs/features/device_config.prf ../../Qt/Qt5.1.0/5.1.0/mingw48_32/mkspecs/common/shell-win32.conf ../..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\qconfig.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_axbase.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_axcontainer.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_axserver.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_bootstrap.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_clucene.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_concurrent.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_core.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_declarative.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_designer.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_designercomponents.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_gui.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_help.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_multimedia.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_multimediawidgets.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_network.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_opengl.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_openglextensions.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_platformsupport.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_printsupport.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_qml.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_qmldevtools.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_qmltest.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_qtmultimediaquicktools.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_quick.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_quickparticles.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_script.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_scripttools.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_sensors.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_serialport.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_sql.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_svg.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_testlib.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_uitools.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_v8.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_webkit.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_webkitwidgets.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_widgets.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_xml.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\modules\qt_lib_xmlpatterns.pri ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\qt_functions.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\qt_config.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\win32-g++\qmake.conf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\spec_post.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\exclusive_builds.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\default_pre.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\win32\default_pre.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\resolve_config.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\default_post.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\build_pass.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\win32\console.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\win32\rtti.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\warn_on.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\qt.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\resources.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\moc.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\win32\opengl.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\testcase_targets.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\exceptions.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\yacc.prf ..\..\Qt\Qt5.1.0\5.1.0\mingw48_32\mkspecs\features\lex.prf ..\EAP-SIM-GW\EAP-SIM-GW.pro D:/Qt/Qt5.1.0/5.1.0/mingw48_32/lib/Qt5Gui.prl D:/Qt/Qt5.1.0/5.1.0/mingw48_32/lib/Qt5Core.prl  RESOURCES HEADERS SOURCES OBJECTIVE_SOURCES YACCSOURCES YACCSOURCES LEXSOURCES 

clean: compiler_clean 
	-$(DEL_FILE) release/PSPacket.o release/mtu_main.o release/mtu_fmt.o release/mtu.o

distclean: clean
	-$(DEL_FILE) $(DESTDIR_TARGET)
	-$(DEL_FILE) Makefile.Release

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

check: first

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_moc_header_make_all:
compiler_moc_header_clean:
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: 



####### Compile

release/PSPacket.o: ../EAP-SIM-GW/PSPacket.cpp ../EAP-SIM-GW/CoACommon.h \
		../EAP-SIM-GW/PSPacket.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/PSPacket.o ../EAP-SIM-GW/PSPacket.cpp

release/mtu_main.o: ../EAP-SIM-GW/mtu_main.cpp \
		../EAP-SIM-GW/mtu.h \
		/opt/DSI/INC/system.h \
		/opt/DSI/INC/msg.h \
		/opt/DSI/INC/sysgct.h \
		/opt/DSI/INC/bit2byte.h \
		/opt/DSI/INC/asciibin.h \
		/opt/DSI/INC/strtonum.h \
		/opt/DSI/INC/ss7_inc.h \
		/opt/DSI/INC/map_inc.h \
		/opt/DSI/INC/pack.h \
		../EAP-SIM-GW/CoACommon.h \
		../EAP-SIM-GW/PSPacket.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/mtu_main.o ../EAP-SIM-GW/mtu_main.cpp

release/mtu_fmt.o: ../EAP-SIM-GW/mtu_fmt.cpp ../EAP-SIM-GW/mtu.h \
		/opt/DSI/INC/system.h \
		/opt/DSI/INC/msg.h \
		/opt/DSI/INC/sysgct.h \
		/opt/DSI/INC/bit2byte.h \
		/opt/DSI/INC/asciibin.h \
		/opt/DSI/INC/strtonum.h \
		/opt/DSI/INC/ss7_inc.h \
		/opt/DSI/INC/map_inc.h \
		/opt/DSI/INC/pack.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/mtu_fmt.o ../EAP-SIM-GW/mtu_fmt.cpp

release/mtu.o: ../EAP-SIM-GW/mtu.cpp ../EAP-SIM-GW/mtu.h \
		/opt/DSI/INC/system.h \
		/opt/DSI/INC/msg.h \
		/opt/DSI/INC/sysgct.h \
		/opt/DSI/INC/bit2byte.h \
		/opt/DSI/INC/asciibin.h \
		/opt/DSI/INC/strtonum.h \
		/opt/DSI/INC/ss7_inc.h \
		/opt/DSI/INC/map_inc.h \
		/opt/DSI/INC/pack.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/mtu.o ../EAP-SIM-GW/mtu.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

