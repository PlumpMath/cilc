
SRC_FILES = LLVM.cs RefBase.cs \
            Analysis.cs \
            Builder.cs \
	    BasicBlock.cs \
	    Context.cs \
            Type.cs DerivedType.cs IntegerType.cs OpaqueType.cs \
            FunctionType.cs \
            CompositeType.cs StructType.cs \
            SequentialType.cs ArrayType.cs PointerType.cs \
            Function.cs \
            TypeHandle.cs \
            Value.cs GlobalVariable.cs \
            Module.cs \
            TargetData.cs

all: $(SRC_FILES)
	gmcs -debug -t:library -out:llvm.dll $(SRC_FILES)
