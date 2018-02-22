# makefile created on 2018-02-21 10:51:31.352875
# by pymake (version 1.1.0)
# using the gfortran fortran and gcc c/c++ compilers.

# Define the directories for the object and module files,
# the executable, and the executable name and path.
OBJDIR = ./obj_temp
BINDIR = .
PROGRAM = mf5to6

SOURCEDIR1=../src
SOURCEDIR2=../src/LGR
SOURCEDIR3=../src/MF2005
SOURCEDIR4=../src/NWT
SOURCEDIR5=../src/Preproc
SOURCEDIR6=../../../src/Utilities/Memory
SOURCEDIR7=../../../src/Utilities/TimeSeries
SOURCEDIR8=../../../src/Utilities

VPATH = \
${SOURCEDIR1} \
${SOURCEDIR2} \
${SOURCEDIR3} \
${SOURCEDIR4} \
${SOURCEDIR5} \
${SOURCEDIR6} \
${SOURCEDIR7} \
${SOURCEDIR8} 

.SUFFIXES: .c .cpp .f .f90 .F90 .fpp .o

# Define the Fortran compile flags
FC = gfortran
FFLAGS = -O2 -fbacktrace 

# Define the C compile flags
CC = gcc
CFLAGS = -O3 -D_UF 

# Define the libraries
SYSLIBS = 

OBJECTS = \
$(OBJDIR)/GwfBcfModule.o \
$(OBJDIR)/StressPeriod.o \
$(OBJDIR)/gwf2hfb7_NWT.o \
$(OBJDIR)/GwfLakModule.o \
$(OBJDIR)/GwfEvtModule.o \
$(OBJDIR)/GlobalPHMF.o \
$(OBJDIR)/ParamModule.o \
$(OBJDIR)/GwfDrnModule.o \
$(OBJDIR)/GwfChdModule.o \
$(OBJDIR)/GwfFhbModule.o \
$(OBJDIR)/GwfGhbModule.o \
$(OBJDIR)/kind.o \
$(OBJDIR)/GwfUpwModule.o \
$(OBJDIR)/GwfRchModule.o \
$(OBJDIR)/Constants.o \
$(OBJDIR)/GwfResModule.o \
$(OBJDIR)/NWT1_xmdlib.o \
$(OBJDIR)/ConverterCommon.o \
$(OBJDIR)/GwfEtsModule.o \
$(OBJDIR)/GwfRivModule.o \
$(OBJDIR)/GwfUzfModule_NWT.o \
$(OBJDIR)/ConstantsPHMF.o \
$(OBJDIR)/GwfWelModule.o \
$(OBJDIR)/GwfLpfModule.o \
$(OBJDIR)/Memory.o \
$(OBJDIR)/GwfLgrModule.o \
$(OBJDIR)/GwfMnwModule.o \
$(OBJDIR)/GlobalVariablesPHMF.o \
$(OBJDIR)/mach_mod.o \
$(OBJDIR)/OpenSpec.o \
$(OBJDIR)/Connection.o \
$(OBJDIR)/GwfSfrModule.o \
$(OBJDIR)/Global.o \
$(OBJDIR)/List.o \
$(OBJDIR)/NWT1_module.o \
$(OBJDIR)/TimeSeriesRecord.o \
$(OBJDIR)/LakeTributary.o \
$(OBJDIR)/NWT1_ilupc_mod.o \
$(OBJDIR)/LakeOutlet.o \
$(OBJDIR)/SimVariables.o \
$(OBJDIR)/CharacterContainer.o \
$(OBJDIR)/GlobalVariables.o \
$(OBJDIR)/SfrDiversion.o \
$(OBJDIR)/Auxiliary.o \
$(OBJDIR)/MemoryList.o \
$(OBJDIR)/LakeConnection.o \
$(OBJDIR)/GwfBasModule.o \
$(OBJDIR)/pcgn2.o \
$(OBJDIR)/ArrayHandlers.o \
$(OBJDIR)/ModelPackage.o \
$(OBJDIR)/SfrReach.o \
$(OBJDIR)/SfrSegment.o \
$(OBJDIR)/SimPHMF.o \
$(OBJDIR)/SimVariablesPHMF.o \
$(OBJDIR)/InputOutput.o \
$(OBJDIR)/BlockParser.o \
$(OBJDIR)/Utilities.o \
$(OBJDIR)/ObservePHMF.o \
$(OBJDIR)/GwfSfrCheck.o \
$(OBJDIR)/MemoryManager.o \
$(OBJDIR)/precutls.o \
$(OBJDIR)/MultiLayerObsModule.o \
$(OBJDIR)/GwfFhbSubs.o \
$(OBJDIR)/ArrayReadersMF5.o \
$(OBJDIR)/TimeSeries.o \
$(OBJDIR)/Lake.o \
$(OBJDIR)/LineList.o \
$(OBJDIR)/File.o \
$(OBJDIR)/GwfResSubs.o \
$(OBJDIR)/ChdType.o \
$(OBJDIR)/DiscretizationBasePHMF.o \
$(OBJDIR)/Discretization3D.o \
$(OBJDIR)/FileWriter.o \
$(OBJDIR)/FileList.o \
$(OBJDIR)/DisWriter.o \
$(OBJDIR)/StoWriter.o \
$(OBJDIR)/NpfWriter.o \
$(OBJDIR)/TdisWriter.o \
$(OBJDIR)/utl7.o \
$(OBJDIR)/ObsBlock.o \
$(OBJDIR)/IcWriter.o \
$(OBJDIR)/parutl7.o \
$(OBJDIR)/GwfBasOcSubs.o \
$(OBJDIR)/GwfLakSubs.o \
$(OBJDIR)/GwfUzfSubs_NWT.o \
$(OBJDIR)/TdisVariables.o \
$(OBJDIR)/pcg7.o \
$(OBJDIR)/obs2ghb7.o \
$(OBJDIR)/obs2drn7.o \
$(OBJDIR)/gmg7.o \
$(OBJDIR)/NWT1_xmd.o \
$(OBJDIR)/Mover.o \
$(OBJDIR)/GwfMnwSubs.o \
$(OBJDIR)/GwfEvtSubs.o \
$(OBJDIR)/obs2bas7.o \
$(OBJDIR)/GwfEtsSubs.o \
$(OBJDIR)/gwf2wel7_NWT.o \
$(OBJDIR)/GwfRivSubs.o \
$(OBJDIR)/sip7.o \
$(OBJDIR)/obs2chd7.o \
$(OBJDIR)/obs2riv7.o \
$(OBJDIR)/NWT1_gmres.o \
$(OBJDIR)/gwf2mnw2i7.o \
$(OBJDIR)/GwfGhbSubs.o \
$(OBJDIR)/GwfSfrSubs.o \
$(OBJDIR)/Preproc.o \
$(OBJDIR)/GwfHfbSubs_NWT.o \
$(OBJDIR)/NWT1_solver.o \
$(OBJDIR)/GwfLgrSubs.o \
$(OBJDIR)/GwfChdSubs.o \
$(OBJDIR)/GwfRchSubs.o \
$(OBJDIR)/de47.o \
$(OBJDIR)/GwfDrnSubs.o \
$(OBJDIR)/ObsWriter.o \
$(OBJDIR)/gwf2mnw17.o \
$(OBJDIR)/GhbObsWriter.o \
$(OBJDIR)/PackageWriter.o \
$(OBJDIR)/RivObsWriter.o \
$(OBJDIR)/MvrPackageWriter.o \
$(OBJDIR)/GhbPackageWriter.o \
$(OBJDIR)/DrnObsWriter.o \
$(OBJDIR)/ChdObsWriter.o \
$(OBJDIR)/RchPackageWriter.o \
$(OBJDIR)/LakPackageWriter.o \
$(OBJDIR)/RivPackageWriter.o \
$(OBJDIR)/EvtPackageWriter.o \
$(OBJDIR)/ImsPackageWriter.o \
$(OBJDIR)/HfbPackageWriter.o \
$(OBJDIR)/DrnPackageWriter.o \
$(OBJDIR)/SfrPackageWriter.o \
$(OBJDIR)/ChdPackageWriter.o \
$(OBJDIR)/WelPackageWriter.o \
$(OBJDIR)/UzfPackageWriter.o \
$(OBJDIR)/OutputControlWriter.o \
$(OBJDIR)/MawPackageWriter.o \
$(OBJDIR)/FhbPackageWriter.o \
$(OBJDIR)/Model.o \
$(OBJDIR)/GwfLpfSubs.o \
$(OBJDIR)/GwfBasSubs.o \
$(OBJDIR)/GwfBcfSubs.o \
$(OBJDIR)/Exchange.o \
$(OBJDIR)/GwfUpwSubs.o \
$(OBJDIR)/ModelConverter.o \
$(OBJDIR)/ExchangeWriter.o \
$(OBJDIR)/SimFileWriter.o \
$(OBJDIR)/mf5to6.o 

# Define task functions

# Create the bin directory and compile and link the program
all: makebin | $(PROGRAM)

# Make the bin directory for the executable
makebin :
	mkdir -p $(BINDIR)

# Define the objects that make up the program
$(PROGRAM) : $(OBJECTS)
	-$(FC) $(FFLAGS) -o $@ $(OBJECTS) $(SYSLIBS) -I$(OBJDIR) -J$(OBJDIR) 

$(OBJDIR)/%.o : %.f
	@mkdir -p $(@D)
	$(FC) $(FFLAGS) -c $< -o $@ -I$(OBJDIR) -J$(OBJDIR) 

$(OBJDIR)/%.o : %.f90
	@mkdir -p $(@D)
	$(FC) $(FFLAGS) -c $< -o $@ -I$(OBJDIR) -J$(OBJDIR) 

$(OBJDIR)/%.o : %.F90
	@mkdir -p $(@D)
	$(FC) $(FFLAGS) -c $< -o $@ -I$(OBJDIR) -J$(OBJDIR) 

$(OBJDIR)/%.o : %.fpp
	@mkdir -p $(@D)
	$(FC) $(FFLAGS) -c $< -o $@ -I$(OBJDIR) -J$(OBJDIR) 

$(OBJDIR)/%.o : %.c
	@mkdir -p $(@D)
	$(CC) $(CFLAGS) -c $< -o $@

$(OBJDIR)/%.o : %.cpp
	@mkdir -p $(@D)
	$(CC) $(CFLAGS) -c $< -o $@

# Clean the object and module files and the executable
.PHONY : clean
clean : 
	-rm -rf $(OBJDIR)
	-rm -rf $(PROGRAM)

# Clean the object and module files
.PHONY : cleanobj
cleanobj : 
	-rm -rf $(OBJDIR)

