# Wind River Workbench generated Makefile.
# Do not edit!!!
#
# The file ".wrmakefile" is the template used by the Wind River Workbench to
# generate the makefiles of this project. Add user-specific build targets and
# make rules only(!) in this project's ".wrmakefile" file. These will then be
# automatically dumped into the makefiles.

WIND_HOME := $(subst \,/,$(WIND_HOME))
WIND_BASE := $(subst \,/,$(WIND_BASE))
WIND_USR := $(subst \,/,$(WIND_USR))
WRVX_COMPBASE := $(subst \,/,$(WRVX_COMPBASE))

all : pre_build main_all post_build

_clean ::
	@echo "make: removing targets and objects of `pwd`"

TRACE=0
TRACEON=$(TRACE:0=@)
TRACE_FLAG=$(TRACEON:1=)

MAKEFILE := Makefile

FLEXIBLE_BUILD := 1

BUILD_SPEC = PENTIUM4gnu
DEBUG_MODE = 1
ifeq ($(DEBUG_MODE),1)
MODE_DIR := Debug
else
MODE_DIR := NonDebug
endif
OBJ_DIR := .
WS_ROOT_DIR := C:/WindRiver/workspace
PRJ_ROOT_DIR := $(WS_ROOT_DIR)/libmxml



#Global Build Macros
PROJECT_TYPE = DKM
DEFINES = 
EXPAND_DBG = 0


#BuildSpec specific Build Macros
VX_CPU_FAMILY = pentium
CPU = PENTIUM4
TOOL_FAMILY = gnu
TOOL = gnu
TOOL_PATH = 
CC_ARCH_SPEC = -mtune=pentium4 -march=pentium4 -nostdlib -fno-builtin -fno-defer-pop
VSB_DIR = $(WIND_BASE)/target/lib
VSB_CONFIG_FILE = $(VSB_DIR)/h/config/vsbConfig.h
LIBPATH = 
LIBS = 

IDE_INCLUDES = -I$(WIND_BASE)/target/h -I$(WIND_BASE)/target/h/wrn/coreip 

IDE_LIBRARIES = 



#BuildTool flags
ifeq ($(DEBUG_MODE),1)
DEBUGFLAGS_C-Compiler = -g
DEBUGFLAGS_C++-Compiler = -g
DEBUGFLAGS_Linker = -g
DEBUGFLAGS_Partial-Image-Linker = 
DEBUGFLAGS_Librarian = 
DEBUGFLAGS_Assembler = -g
else
DEBUGFLAGS_C-Compiler = -O2
DEBUGFLAGS_C++-Compiler = -O2
DEBUGFLAGS_Linker = -O2
DEBUGFLAGS_Partial-Image-Linker = 
DEBUGFLAGS_Librarian = 
DEBUGFLAGS_Assembler = -O2
endif


#Project Targets
PROJECT_TARGETS = libmxml/$(MODE_DIR)/libmxml.a


#Rules

# libmxml
ifeq ($(DEBUG_MODE),1)
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -g
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -g
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -g
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -g
else
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -O2
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -O2
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -O2
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
libmxml/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -O2
endif
libmxml/$(MODE_DIR)/% : IDE_INCLUDES = -I$(WIND_BASE)/target/h -I$(WIND_BASE)/target/h/wrn/coreip 
libmxml/$(MODE_DIR)/% : IDE_LIBRARIES = 
libmxml/$(MODE_DIR)/% : PROJECT_TYPE = DKM
libmxml/$(MODE_DIR)/% : DEFINES = 
libmxml/$(MODE_DIR)/% : EXPAND_DBG = 0
libmxml/$(MODE_DIR)/% : VX_CPU_FAMILY = pentium
libmxml/$(MODE_DIR)/% : CPU = PENTIUM4
libmxml/$(MODE_DIR)/% : TOOL_FAMILY = gnu
libmxml/$(MODE_DIR)/% : TOOL = gnu
libmxml/$(MODE_DIR)/% : TOOL_PATH = 
libmxml/$(MODE_DIR)/% : CC_ARCH_SPEC = -mtune=pentium4 -march=pentium4 -nostdlib -fno-builtin -fno-defer-pop
libmxml/$(MODE_DIR)/% : VSB_DIR = $(WIND_BASE)/target/lib
libmxml/$(MODE_DIR)/% : VSB_CONFIG_FILE = $(VSB_DIR)/h/config/vsbConfig.h
libmxml/$(MODE_DIR)/% : LIBPATH = 
libmxml/$(MODE_DIR)/% : LIBS = 
libmxml/$(MODE_DIR)/% : OBJ_DIR := libmxml/$(MODE_DIR)

libmxml/$(MODE_DIR)/Objects/libmxml/mxml-attr.o : $(PRJ_ROOT_DIR)/mxml-attr.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-entity.o : $(PRJ_ROOT_DIR)/mxml-entity.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-file.o : $(PRJ_ROOT_DIR)/mxml-file.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-get.o : $(PRJ_ROOT_DIR)/mxml-get.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-index.o : $(PRJ_ROOT_DIR)/mxml-index.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-node.o : $(PRJ_ROOT_DIR)/mxml-node.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-private.o : $(PRJ_ROOT_DIR)/mxml-private.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-search.o : $(PRJ_ROOT_DIR)/mxml-search.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-set.o : $(PRJ_ROOT_DIR)/mxml-set.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


libmxml/$(MODE_DIR)/Objects/libmxml/mxml-string.o : $(PRJ_ROOT_DIR)/mxml-string.c
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -Wall   -MD -MP $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL  -D_VSB_CONFIG_FILE=\"$(VSB_CONFIG_FILE)\"   $(DEFINES) -o "$@" -c "$<"


OBJECTS_libmxml = libmxml/$(MODE_DIR)/Objects/libmxml/mxml-attr.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-entity.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-file.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-get.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-index.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-node.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-private.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-search.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-set.o \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-string.o

libmxml/$(MODE_DIR)/libmxml.a : $(OBJECTS_libmxml)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)arpentium crus "$@" $(OBJECTS_libmxml) $(ADDED_OBJECTS)

libmxml/$(MODE_DIR)/libmxml_compile_file : $(FILE) ;

_clean :: libmxml/$(MODE_DIR)/libmxml_clean

libmxml/$(MODE_DIR)/libmxml_clean : 
	$(TRACE_FLAG)if [ -d "libmxml" ]; then cd "libmxml"; rm -rf $(MODE_DIR); fi

DEP_FILES := libmxml/$(MODE_DIR)/Objects/libmxml/mxml-attr.d libmxml/$(MODE_DIR)/Objects/libmxml/mxml-entity.d libmxml/$(MODE_DIR)/Objects/libmxml/mxml-file.d \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-get.d libmxml/$(MODE_DIR)/Objects/libmxml/mxml-index.d libmxml/$(MODE_DIR)/Objects/libmxml/mxml-node.d \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-private.d libmxml/$(MODE_DIR)/Objects/libmxml/mxml-search.d libmxml/$(MODE_DIR)/Objects/libmxml/mxml-set.d \
	 libmxml/$(MODE_DIR)/Objects/libmxml/mxml-string.d
-include $(DEP_FILES)


WIND_SCOPETOOLS_BASE := $(subst \,/,$(WIND_SCOPETOOLS_BASE))

clean_scopetools :
	$(TRACE_FLAG)rm -rf $(PRJ_ROOT_DIR)/.coveragescope/db

CLEAN_STEP := clean_scopetools


-include $(PRJ_ROOT_DIR)/*.makefile

-include *.makefile

main_all : external_build $(PROJECT_TARGETS)
	@echo "make: built targets of `pwd`"

# entry point for extending the build
external_build ::
	@echo ""

# main entry point for pre processing prior to the build
pre_build :: $(PRE_BUILD_STEP) generate_sources
	@echo ""

# entry point for generating sources prior to the build
generate_sources ::
	@echo ""

# main entry point for post processing after the build
post_build :: $(POST_BUILD_STEP) deploy_output
	@echo ""

# entry point for deploying output after the build
deploy_output ::
	@echo ""

clean :: external_clean $(CLEAN_STEP) _clean

# entry point for extending the build clean
external_clean ::
	@echo ""
