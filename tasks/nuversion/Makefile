# Component (mission) name. Developers need not change/delete this.
HD_COMPONENT_NAME	= nustar

# Software release version number. Developers need not change/delete this.
HD_COMPONENT_VERS	=

# If this directory needs to build a task, list its name here.
HD_CTASK		= nuversion

# C language source files (.c) to use for the task.
HD_CTASK_SRC_c		= ${HD_CTASK}.c

# C flags to use in every compilation.
HD_CFLAGS		= ${HD_STD_CFLAGS}

# Library flags to use when linking C task.
HD_CLIBS		= ${HD_LFLAGS} -lnustardas ${HD_STD_LIBS} ${SYSLIBS} ${F77LIBS4C}

# Tasks to be installed.
HD_INSTALL_TASKS	= ${HD_CTASK}

# Help file(s) to install.
HD_INSTALL_HELP		= 

include ${HD_STD_MAKEFILE}
