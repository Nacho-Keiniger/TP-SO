################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include src/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: memoria

dependents:
	-cd /media/sf_carpeta-compartida/0\ TP_Sistemas_operativos_2021-main/futiles/Debug && $(MAKE) clean all

# Tool invocations
memoria: $(OBJS) $(USER_OBJS) /media/sf_carpeta-compartida/0\ TP_Sistemas_operativos_2021-main/futiles/Debug/libfutiles.so
	@echo 'Building target: $@'
	@echo 'Invoking: GCC C Linker'
	gcc -L"/media/sf_carpeta-compartida/0 TP_Sistemas_operativos_2021-main/futiles/Debug" -o "memoria" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXECUTABLES)$(OBJS)$(C_DEPS) memoria
	-@echo ' '

.PHONY: all clean dependents
/media/sf_carpeta-compartida/0\ TP_Sistemas_operativos_2021-main/futiles/Debug/libfutiles.so:

-include ../makefile.targets
