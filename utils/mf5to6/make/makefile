# makefile created on 2017-08-11 14:30:25.869854
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
$(OBJDIR)/gwf2hfb7_NWT.o \
$(OBJDIR)/GwfEtsModule.o \
$(OBJDIR)/GwfBcfModule.o \
$(OBJDIR)/GwfWelModule.o \
$(OBJDIR)/ConverterCommon.o \
$(OBJDIR)/GwfResModule.o \
$(OBJDIR)/GwfDrnModule.o \
$(OBJDIR)/GlobalPHMF.o \
$(OBJDIR)/OpenSpec.o \
$(OBJDIR)/GwfRchModule.o \
$(OBJDIR)/GwfFhbModule.o \
$(OBJDIR)/StressPeriod.o \
$(OBJDIR)/GwfGhbModule.o \
$(OBJDIR)/GwfChdModule.o \
$(OBJDIR)/GwfUpwModule.o \
$(OBJDIR)/GwfLpfModule.o \
$(OBJDIR)/NWT1_xmdlib.o \
$(OBJDIR)/GwfLgrModule.o \
$(OBJDIR)/GwfRivModule.o \
$(OBJDIR)/kind.o \
$(OBJDIR)/GwfUzfModule_NWT.o \
$(OBJDIR)/ConstantsPHMF.o \
$(OBJDIR)/List.o \
$(OBJDIR)/TimeSeriesRecord.o \
$(OBJDIR)/GwfMnwModule.o \
$(OBJDIR)/GwfEvtModule.o \
$(OBJDIR)/SfrDiversion.o \
$(OBJDIR)/GwfLakModule.o \
$(OBJDIR)/mach_mod.o \
$(OBJDIR)/ParamModule.o \
$(OBJDIR)/NWT1_module.o \
$(OBJDIR)/Constants.o \
$(OBJDIR)/GwfSfrModule.o \
$(OBJDIR)/GlobalVariables.o \
$(OBJDIR)/GlobalVariablesPHMF.o \
$(OBJDIR)/Memory.o \
$(OBJDIR)/LakeOutlet.o \
$(OBJDIR)/Auxiliary.o \
$(OBJDIR)/LakeTributary.o \
$(OBJDIR)/MemoryList.o \
$(OBJDIR)/Global.o \
$(OBJDIR)/LakeConnection.o \
$(OBJDIR)/pcgn2.o \
$(OBJDIR)/ArrayHandlers.o \
$(OBJDIR)/CharacterContainer.o \
$(OBJDIR)/GwfBasModule.o \
$(OBJDIR)/SfrReach.o \
$(OBJDIR)/Connection.o \
$(OBJDIR)/SimVariables.o \
$(OBJDIR)/NWT1_ilupc_mod.o \
$(OBJDIR)/SimPHMF.o \
$(OBJDIR)/ModelPackage.o \
$(OBJDIR)/InputOutput.o \
$(OBJDIR)/SfrSegment.o \
$(OBJDIR)/MultiLayerObsModule.o \
$(OBJDIR)/Lake.o \
$(OBJDIR)/BlockParser.o \
$(OBJDIR)/GwfFhbSubs.o \
$(OBJDIR)/MemoryManager.o \
$(OBJDIR)/SimVariablesPHMF.o \
$(OBJDIR)/GwfSfrCheck.o \
$(OBJDIR)/ArrayReadersMF5.o \
$(OBJDIR)/Utilities.o \
$(OBJDIR)/GwfResSubs.o \
$(OBJDIR)/ObservePHMF.o \
$(OBJDIR)/precutls.o \
$(OBJDIR)/TimeSeries.o \
$(OBJDIR)/LineList.o \
$(OBJDIR)/DiscretizationBasePHMF.o \
$(OBJDIR)/File.o \
$(OBJDIR)/FileWriter.o \
$(OBJDIR)/ChdType.o \
$(OBJDIR)/Discretization3D.o \
$(OBJDIR)/StoWriter.o \
$(OBJDIR)/DisWriter.o \
$(OBJDIR)/FileList.o \
$(OBJDIR)/IcWriter.o \
$(OBJDIR)/NpfWriter.o \
$(OBJDIR)/TdisWriter.o \
$(OBJDIR)/ObsBlock.o \
$(OBJDIR)/TdisVariables.o \
$(OBJDIR)/utl7.o \
$(OBJDIR)/NWT1_gmres.o \
$(OBJDIR)/obs2drn7.o \
$(OBJDIR)/pcg7.o \
$(OBJDIR)/gmg7.o \
$(OBJDIR)/GwfGhbSubs.o \
$(OBJDIR)/NWT1_xmd.o \
$(OBJDIR)/GwfDrnSubs.o \
$(OBJDIR)/GwfEtsSubs.o \
$(OBJDIR)/gwf2wel7_NWT.o \
$(OBJDIR)/obs2chd7.o \
$(OBJDIR)/Preproc.o \
$(OBJDIR)/GwfSfrSubs.o \
$(OBJDIR)/GwfLgrSubs.o \
$(OBJDIR)/GwfEvtSubs.o \
$(OBJDIR)/GwfBasOcSubs.o \
$(OBJDIR)/Mover.o \
$(OBJDIR)/GwfMnwSubs.o \
$(OBJDIR)/GwfRivSubs.o \
$(OBJDIR)/obs2bas7.o \
$(OBJDIR)/obs2ghb7.o \
$(OBJDIR)/GwfHfbSubs_NWT.o \
$(OBJDIR)/GwfRchSubs.o \
$(OBJDIR)/sip7.o \
$(OBJDIR)/obs2riv7.o \
$(OBJDIR)/NWT1_solver.o \
$(OBJDIR)/de47.o \
$(OBJDIR)/GwfChdSubs.o \
$(OBJDIR)/parutl7.o \
$(OBJDIR)/GwfLakSubs.o \
$(OBJDIR)/GwfUzfSubs_NWT.o \
$(OBJDIR)/gwf2mnw17.o \
$(OBJDIR)/ObsWriter.o \
$(OBJDIR)/PackageWriter.o \
$(OBJDIR)/RivObsWriter.o \
$(OBJDIR)/MvrPackageWriter.o \
$(OBJDIR)/DrnPackageWriter.o \
$(OBJDIR)/gwf2mnw2i7.o \
$(OBJDIR)/RchPackageWriter.o \
$(OBJDIR)/MawPackageWriter.o \
$(OBJDIR)/DrnObsWriter.o \
$(OBJDIR)/WelPackageWriter.o \
$(OBJDIR)/EvtPackageWriter.o \
$(OBJDIR)/HfbPackageWriter.o \
$(OBJDIR)/GhbObsWriter.o \
$(OBJDIR)/ImsPackageWriter.o \
$(OBJDIR)/ChdObsWriter.o \
$(OBJDIR)/OutputControlWriter.o \
$(OBJDIR)/SfrPackageWriter.o \
$(OBJDIR)/GhbPackageWriter.o \
$(OBJDIR)/UzfPackageWriter.o \
$(OBJDIR)/RivPackageWriter.o \
$(OBJDIR)/LakPackageWriter.o \
$(OBJDIR)/ChdPackageWriter.o \
$(OBJDIR)/FhbPackageWriter.o \
$(OBJDIR)/Model.o \
$(OBJDIR)/GwfUpwSubs.o \
$(OBJDIR)/Exchange.o \
$(OBJDIR)/GwfBcfSubs.o \
$(OBJDIR)/GwfLpfSubs.o \
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

