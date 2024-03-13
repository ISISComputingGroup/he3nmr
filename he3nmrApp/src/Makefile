TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += he3nmr

# xxxRecord.h will be created from xxxRecord.dbd
#DBDINC += xxxRecord
# install he3nmr.dbd into <top>/dbd
DBD += he3nmr.dbd

# specify all source files to be compiled and added to the library
#he3nmr_SRCS += xxx

he3nmr_LIBS += $(EPICS_BASE_IOC_LIBS)

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

