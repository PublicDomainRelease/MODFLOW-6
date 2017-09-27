# makefile created on 2017-09-28 14:52:02.097109
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
$(OBJDIR)/GlobalPHMF.o \
$(OBJDIR)/GwfChdModule.o \
$(OBJDIR)/StressPeriod.o \
$(OBJDIR)/GwfMnwModule.o \
$(OBJDIR)/GwfResModule.o \
$(OBJDIR)/GwfLpfModule.o \
$(OBJDIR)/GwfRchModule.o \
$(OBJDIR)/GwfLakModule.o \
$(OBJDIR)/NWT1_xmdlib.o \
$(OBJDIR)/GwfGhbModule.o \
$(OBJDIR)/ConstantsPHMF.o \
$(OBJDIR)/ParamModule.o \
$(OBJDIR)/GwfUpwModule.o \
$(OBJDIR)/kind.o \
$(OBJDIR)/GwfLgrModule.o \
$(OBJDIR)/mach_mod.o \
$(OBJDIR)/GwfEvtModule.o \
$(OBJDIR)/GwfRivModule.o \
$(OBJDIR)/GwfDrnModule.o \
$(OBJDIR)/GwfWelModule.o \
$(OBJDIR)/gwf2hfb7_NWT.o \
$(OBJDIR)/List.o \
$(OBJDIR)/OpenSpec.o \
$(OBJDIR)/NWT1_module.o \
$(OBJDIR)/GwfBcfModule.o \
$(OBJDIR)/GwfUzfModule_NWT.o \
$(OBJDIR)/ConverterCommon.o \
$(OBJDIR)/SfrDiversion.o \
$(OBJDIR)/GwfEtsModule.o \
$(OBJDIR)/Constants.o \
$(OBJDIR)/GwfFhbModule.o \
$(OBJDIR)/GlobalVariablesPHMF.o \
$(OBJDIR)/GwfSfrModule.o \
$(OBJDIR)/GlobalVariables.o \
$(OBJDIR)/Global.o \
$(OBJDIR)/Connection.o \
$(OBJDIR)/TimeSeriesRecord.o \
$(OBJDIR)/Memory.o \
$(OBJDIR)/NWT1_ilupc_mod.o \
$(OBJDIR)/CharacterContainer.o \
$(OBJDIR)/LakeOutlet.o \
$(OBJDIR)/Auxiliary.o \
$(OBJDIR)/LakeTributary.o \
$(OBJDIR)/pcgn2.o \
$(OBJDIR)/LakeConnection.o \
$(OBJDIR)/GwfBasModule.o \
$(OBJDIR)/ArrayHandlers.o \
$(OBJDIR)/SimVariables.o \
$(OBJDIR)/MemoryList.o \
$(OBJDIR)/SfrReach.o \
$(OBJDIR)/SimPHMF.o \
$(OBJDIR)/SfrSegment.o \
$(OBJDIR)/InputOutput.o \
$(OBJDIR)/SimVariablesPHMF.o \
$(OBJDIR)/MultiLayerObsModule.o \
$(OBJDIR)/Utilities.o \
$(OBJDIR)/ModelPackage.o \
$(OBJDIR)/precutls.o \
$(OBJDIR)/BlockParser.o \
$(OBJDIR)/ArrayReadersMF5.o \
$(OBJDIR)/TimeSeries.o \
$(OBJDIR)/GwfFhbSubs.o \
$(OBJDIR)/GwfResSubs.o \
$(OBJDIR)/MemoryManager.o \
$(OBJDIR)/DiscretizationBasePHMF.o \
$(OBJDIR)/GwfSfrCheck.o \
$(OBJDIR)/File.o \
$(OBJDIR)/LineList.o \
$(OBJDIR)/Lake.o \
$(OBJDIR)/FileWriter.o \
$(OBJDIR)/ObservePHMF.o \
$(OBJDIR)/Discretization3D.o \
$(OBJDIR)/ChdType.o \
$(OBJDIR)/FileList.o \
$(OBJDIR)/StoWriter.o \
$(OBJDIR)/TdisWriter.o \
$(OBJDIR)/TdisVariables.o \
$(OBJDIR)/utl7.o \
$(OBJDIR)/GwfEvtSubs.o \
$(OBJDIR)/ObsBlock.o \
$(OBJDIR)/gmg7.o \
$(OBJDIR)/obs2ghb7.o \
$(OBJDIR)/GwfHfbSubs_NWT.o \
$(OBJDIR)/obs2riv7.o \
$(OBJDIR)/IcWriter.o \
$(OBJDIR)/GwfSfrSubs.o \
$(OBJDIR)/GwfLakSubs.o \
$(OBJDIR)/GwfUzfSubs_NWT.o \
$(OBJDIR)/GwfLgrSubs.o \
$(OBJDIR)/obs2drn7.o \
$(OBJDIR)/DisWriter.o \
$(OBJDIR)/parutl7.o \
$(OBJDIR)/Preproc.o \
$(OBJDIR)/GwfEtsSubs.o \
$(OBJDIR)/de47.o \
$(OBJDIR)/GwfRivSubs.o \
$(OBJDIR)/GwfDrnSubs.o \
$(OBJDIR)/NpfWriter.o \
$(OBJDIR)/GwfGhbSubs.o \
$(OBJDIR)/GwfRchSubs.o \
$(OBJDIR)/sip7.o \
$(OBJDIR)/NWT1_gmres.o \
$(OBJDIR)/NWT1_solver.o \
$(OBJDIR)/gwf2wel7_NWT.o \
$(OBJDIR)/GwfChdSubs.o \
$(OBJDIR)/obs2chd7.o \
$(OBJDIR)/pcg7.o \
$(OBJDIR)/Mover.o \
$(OBJDIR)/GwfMnwSubs.o \
$(OBJDIR)/NWT1_xmd.o \
$(OBJDIR)/obs2bas7.o \
$(OBJDIR)/GwfBasOcSubs.o \
$(OBJDIR)/gwf2mnw17.o \
$(OBJDIR)/gwf2mnw2i7.o \
$(OBJDIR)/ObsWriter.o \
$(OBJDIR)/DrnObsWriter.o \
$(OBJDIR)/PackageWriter.o \
$(OBJDIR)/MvrPackageWriter.o \
$(OBJDIR)/WelPackageWriter.o \
$(OBJDIR)/RivObsWriter.o \
$(OBJDIR)/RchPackageWriter.o \
$(OBJDIR)/GhbObsWriter.o \
$(OBJDIR)/MawPackageWriter.o \
$(OBJDIR)/ChdObsWriter.o \
$(OBJDIR)/DrnPackageWriter.o \
$(OBJDIR)/LakPackageWriter.o \
$(OBJDIR)/EvtPackageWriter.o \
$(OBJDIR)/SfrPackageWriter.o \
$(OBJDIR)/ImsPackageWriter.o \
$(OBJDIR)/GhbPackageWriter.o \
$(OBJDIR)/HfbPackageWriter.o \
$(OBJDIR)/OutputControlWriter.o \
$(OBJDIR)/RivPackageWriter.o \
$(OBJDIR)/ChdPackageWriter.o \
$(OBJDIR)/UzfPackageWriter.o \
$(OBJDIR)/FhbPackageWriter.o \
$(OBJDIR)/Model.o \
$(OBJDIR)/GwfLpfSubs.o \
$(OBJDIR)/GwfUpwSubs.o \
$(OBJDIR)/GwfBcfSubs.o \
$(OBJDIR)/Exchange.o \
$(OBJDIR)/GwfBasSubs.o \
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

