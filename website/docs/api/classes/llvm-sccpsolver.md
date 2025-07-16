---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sccpsolver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCCPSolver` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/sccpsolver">SCCPSolver</a> - This interface class is a general purpose solver for Sparse Conditional <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Propagation (SCCP). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCCPSolver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">llvm/Transforms/Utils/SCCPSolver.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0f9d53c781fbed9fb8f657d44a3e25">SCCPSolver</a> (const DataLayout &amp;DL, std::function&lt; const TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI, LLVMContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b835b1f4347dd95002cdb91d9d6c58d">~SCCPSolver</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292161e0623c9b2105197ff588f0920a">addPredicateInfo</a> (Function &amp;F, DominatorTree &amp;DT, AssumptionCache &amp;AC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2fa77f7d65438220a9fef42964d284">markBlockExecutable</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>markBlockExecutable - This method can be used by clients to mark all of the blocks that are known to be intrinsically live in the processed unit. <a href="#acb2fa77f7d65438220a9fef42964d284">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/predicatebase">PredicateBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674c1b383ab9b9b2191be9fad7b08d7d">getPredicateInfoFor</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199003a361f6d87612ab03c249ab04c6">trackValueOfGlobalVariable</a> (GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>trackValueOfGlobalVariable - Clients can use this method to inform the <a href="/web-llvm/docs/api/classes/llvm/sccpsolver">SCCPSolver</a> that it should track loads and stores to the specified global variable if it can. <a href="#a199003a361f6d87612ab03c249ab04c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5147010939209f2d4c1b7891d2f1ef43">addTrackedFunction</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addTrackedFunction - If the SCCP solver is supposed to track calls into and out of the specified function (which cannot have its address taken), this method must be called. <a href="#a5147010939209f2d4c1b7891d2f1ef43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab14dd263e92d4c88176c888c6b7956f7">addToMustPreserveReturnsInFunctions</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add function to the list of functions whose return cannot be modified. <a href="#ab14dd263e92d4c88176c888c6b7956f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9beb9b76f6ad337d1e0038f97fcc30">mustPreserveReturn</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the return of the given function cannot be modified. <a href="#adf9beb9b76f6ad337d1e0038f97fcc30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e13f6c5a2a78ec3b68dad32a2b6b5e">addArgumentTrackedFunction</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac4a6400d54748b0245e0ce203280fd">isArgumentTrackedFunction</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given function is in the solver's set of argument-tracked functions. <a href="#aeac4a6400d54748b0245e0ce203280fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0506af9f643c74ce5bdcb19f36e397">getArgumentTrackedFunctions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6a1ff9823ca3ddb89d80fe379603ee">solve</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Solve - Solve for constants and executable blocks. <a href="#a2d6a1ff9823ca3ddb89d80fe379603ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814c9ef427065262b0ff3c0dc3d9f19d">resolvedUndefsIn</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>resolvedUndefsIn - While solving the dataflow for a function, we assume that branches on undef values cannot reach any of their successors. <a href="#a814c9ef427065262b0ff3c0dc3d9f19d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659bc647a6b3504fc00f522405ea2b94">solveWhileResolvedUndefsIn</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b22410f3213aaf29c15590e3da1c670">solveWhileResolvedUndefsIn</a> (SmallVectorImpl&lt; Function * &gt; &amp;WorkList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95bd3f2616c863d18afeabf8138175cc">solveWhileResolvedUndefs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16a1026117ac160108d8a5bab0ae445">isBlockExecutable</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6219c3e8978e60523fc38b668ddbe2">isEdgeFeasible</a> (BasicBlock *From, BasicBlock *To) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961c1857e2b424b5b66afd743fce0c69">getStructLatticeValueFor</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95cb0700e1d0d1a584fd0d325139fee0">removeLatticeValueFor</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bdb6461656b4a113516cb06dce779a">resetLatticeValueFor</a> (CallBase *Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate the Lattice <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of <span class="doxyComputerOutput">Call</span> and its users after specializing the call. <a href="#a16bdb6461656b4a113516cb06dce779a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab146e74d42b852877cc1e935d808005a">getLatticeValueFor</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ca96cd91afca7c10938c06e7717ac5">getTrackedRetVals</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTrackedRetVals - Get the inferred return value map. <a href="#ad5ca96cd91afca7c10938c06e7717ac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15faa77c390af978b9b1a99163bca7ae">getTrackedGlobals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTrackedGlobals - Get and return the set of inferred initializers for global variables. <a href="#a15faa77c390af978b9b1a99163bca7ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c2b47a19dd62cb74325a82c9b24bf31">getMRVFunctionsTracked</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMRVFunctionsTracked - Get the set of functions which return multiple values tracked by the pass. <a href="#a9c2b47a19dd62cb74325a82c9b24bf31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88f6c356f4e17eaebfb81ac86426758">markOverdefined</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>markOverdefined - Mark the specified value overdefined. <a href="#af88f6c356f4e17eaebfb81ac86426758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bca075219cfb484e464a6f89d37786d">trackValueOfArgument</a> (Argument *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>trackValueOfArgument - Mark the specified argument overdefined unless it have range attribute. <a href="#a3bca075219cfb484e464a6f89d37786d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2670c5122001cda5dfb2647fc4cc6d04">isStructLatticeConstant</a> (Function *F, StructType *STy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b47ae8a8d36c7aaf34c47e25de5ec4">getConstant</a> (const ValueLatticeElement &amp;LV, Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to return a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> if <span class="doxyComputerOutput">LV</span> is either a constant or a constant range with a single element. <a href="#ab0b47ae8a8d36c7aaf34c47e25de5ec4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca89aae97dda0e84dade221194b03e3">getConstantOrNull</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return either a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> or nullptr for a given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a9ca89aae97dda0e84dade221194b03e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9cec3152490daf65f67a88717c7b0f">setLatticeValueForSpecializationArguments</a> (Function *F, const SmallVectorImpl&lt; ArgInfo &gt; &amp;Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the Lattice <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for the arguments of a specialization <span class="doxyComputerOutput">F</span>. <a href="#ace9cec3152490daf65f67a88717c7b0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea0787eb78b2ba612d39c09a17515720">markFunctionUnreachable</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark all of the blocks in function <span class="doxyComputerOutput">F</span> non-executable. <a href="#aea0787eb78b2ba612d39c09a17515720">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364ce42337c757bcfbfae5e0bd789ec7">visit</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0299e4a68bc89afd5f3599df2fc9fc6e">visitCall</a> (CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfdaab0d47c510fa75c73885c78cd06">simplifyInstsInBlock</a> (BasicBlock &amp;BB, SmallPtrSetImpl&lt; Value * &gt; &amp;InsertedValues, Statistic &amp;InstRemovedStat, Statistic &amp;InstReplacedStat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">removeNonFeasibleEdges</a> (BasicBlock *BB, DomTreeUpdater &amp;DTU, BasicBlock *&amp;NewUnreachableBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac961f5026f37ab4f7a912c967f1ac671">inferReturnAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238416b839e59fc3331c8bc15ccfd50b">inferArgAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7cd4c14e02c076508142fbb2c1aa79">tryToReplaceWithConstant</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor">SCCPInstVisitor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04b87183555e131fe5e897dbfc999d8">Visitor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad443783793d65506b0b69745c79d26d5">isConstant</a> (const ValueLatticeElement &amp;LV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58f6a2457188593908aae83468858d3">isOverdefined</a> (const ValueLatticeElement &amp;LV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/sccpsolver">SCCPSolver</a> - This interface class is a general purpose solver for Sparse Conditional <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Propagation (SCCP).</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SCCPSolver() {#aeb0f9d53c781fbed9fb8f657d44a3e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCCPSolver::SCCPSolver (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SCCPSolver() {#a0b835b1f4347dd95002cdb91d9d6c58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCCPSolver::~SCCPSolver ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addArgumentTrackedFunction() {#a89e13f6c5a2a78ec3b68dad32a2b6b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::addArgumentTrackedFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### addPredicateInfo() {#a292161e0623c9b2105197ff588f0920a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::addPredicateInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### addToMustPreserveReturnsInFunctions() {#ab14dd263e92d4c88176c888c6b7956f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::addToMustPreserveReturnsInFunctions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add function to the list of functions whose return cannot be modified.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a1f7cd4c14e02c076508142fbb2c1aa79">tryToReplaceWithConstant</a>.</p>

</div>
</div>

### addTrackedFunction() {#a5147010939209f2d4c1b7891d2f1ef43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::addTrackedFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addTrackedFunction - If the SCCP solver is supposed to track calls into and out of the specified function (which cannot have its address taken), this method must be called.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### getArgumentTrackedFunctions() {#a7b0506af9f643c74ce5bdcb19f36e397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSetImpl&lt; Function * &gt; &amp; SCCPSolver::getArgumentTrackedFunctions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="#a238416b839e59fc3331c8bc15ccfd50b">inferArgAttributes</a>.</p>

</div>
</div>

### getConstant() {#ab0b47ae8a8d36c7aaf34c47e25de5ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * SCCPSolver::getConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; LV, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to return a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> if <span class="doxyComputerOutput">LV</span> is either a constant or a constant range with a single element.</p>

<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>

</div>
</div>

### getConstantOrNull() {#a9ca89aae97dda0e84dade221194b03e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * SCCPSolver::getConstantOrNull (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return either a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> or nullptr for a given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="#a1f7cd4c14e02c076508142fbb2c1aa79">tryToReplaceWithConstant</a>.</p>

</div>
</div>

### getLatticeValueFor() {#ab146e74d42b852877cc1e935d808005a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValueLatticeElement &amp; SCCPSolver::getLatticeValueFor (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#a409abf8b151a61b0adacda9229f3cc21">findReturnsToZap</a>, <a href="#a238416b839e59fc3331c8bc15ccfd50b">inferArgAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>.</p>

</div>
</div>

### getMRVFunctionsTracked() {#a9c2b47a19dd62cb74325a82c9b24bf31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSet&lt; Function *, 16 &gt; SCCPSolver::getMRVFunctionsTracked ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMRVFunctionsTracked - Get the set of functions which return multiple values tracked by the pass.</p>

<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### getPredicateInfoFor() {#a674c1b383ab9b9b2191be9fad7b08d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PredicateBase * SCCPSolver::getPredicateInfoFor (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### getStructLatticeValueFor() {#a961c1857e2b424b5b66afd743fce0c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; ValueLatticeElement &gt; SCCPSolver::getStructLatticeValueFor (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2207 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>

</div>
</div>

### getTrackedGlobals() {#a15faa77c390af978b9b1a99163bca7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt; GlobalVariable *, ValueLatticeElement &gt; &amp; SCCPSolver::getTrackedGlobals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getTrackedGlobals - Get and return the set of inferred initializers for global variables.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### getTrackedRetVals() {#ad5ca96cd91afca7c10938c06e7717ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MapVector&lt; Function *, ValueLatticeElement &gt; &amp; SCCPSolver::getTrackedRetVals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getTrackedRetVals - Get the inferred return value map.</p>

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="#ac961f5026f37ab4f7a912c967f1ac671">inferReturnAttributes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### inferArgAttributes() {#a238416b839e59fc3331c8bc15ccfd50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCCPSolver::inferArgAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">llvm::AttributeList::FirstArgIndex</a>, <a href="#a7b0506af9f643c74ce5bdcb19f36e397">getArgumentTrackedFunctions</a>, <a href="#ab146e74d42b852877cc1e935d808005a">getLatticeValueFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a> and <a href="#ac16a1026117ac160108d8a5bab0ae445">isBlockExecutable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### inferReturnAttributes() {#ac961f5026f37ab4f7a912c967f1ac671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCCPSolver::inferReturnAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad5ca96cd91afca7c10938c06e7717ac5">getTrackedRetVals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">llvm::AttributeList::ReturnIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### isArgumentTrackedFunction() {#aeac4a6400d54748b0245e0ce203280fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCCPSolver::isArgumentTrackedFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the given function is in the solver's set of argument-tracked functions.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#a409abf8b151a61b0adacda9229f3cc21">findReturnsToZap</a>.</p>

</div>
</div>

### isBlockExecutable() {#ac16a1026117ac160108d8a5bab0ae445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCCPSolver::isBlockExecutable (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="#a238416b839e59fc3331c8bc15ccfd50b">inferArgAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### isEdgeFeasible() {#ada6219c3e8978e60523fc38b668ddbe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCCPSolver::isEdgeFeasible (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">removeNonFeasibleEdges</a>.</p>

</div>
</div>

### isStructLatticeConstant() {#a2670c5122001cda5dfb2647fc4cc6d04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCCPSolver::isStructLatticeConstant (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * STy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### markBlockExecutable() {#acb2fa77f7d65438220a9fef42964d284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCCPSolver::markBlockExecutable (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>markBlockExecutable - This method can be used by clients to mark all of the blocks that are known to be intrinsically live in the processed unit.</p>


<p>This returns true if the block was not considered live before.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### markFunctionUnreachable() {#aea0787eb78b2ba612d39c09a17515720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::markFunctionUnreachable (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark all of the blocks in function <span class="doxyComputerOutput">F</span> non-executable.</p>


<p>Clients can used this method to erase a function from the module (e.g., if it has been completely specialized and is no longer needed).</p>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### markOverdefined() {#af88f6c356f4e17eaebfb81ac86426758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::markOverdefined (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>markOverdefined - Mark the specified value overdefined.</p>


<p>This works with both scalars and structs.</p>


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>

</div>
</div>

### mustPreserveReturn() {#adf9beb9b76f6ad337d1e0038f97fcc30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCCPSolver::mustPreserveReturn (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the return of the given function cannot be modified.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#a409abf8b151a61b0adacda9229f3cc21">findReturnsToZap</a>.</p>

</div>
</div>

### removeLatticeValueFor() {#a95cb0700e1d0d1a584fd0d325139fee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::removeLatticeValueFor (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2211 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>.</p>

</div>
</div>

### removeNonFeasibleEdges() {#ab1e7a17f7727ff9a32ffc2a1efdb7bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCCPSolver::removeNonFeasibleEdges (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> &amp; DTU, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; NewUnreachableBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Delete</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ada6219c3e8978e60523fc38b668ddbe2">isEdgeFeasible</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afe7af0c3ec2ef1f525173acd2ea4ba60">llvm::BasicBlock::removePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### resetLatticeValueFor() {#a16bdb6461656b4a113516cb06dce779a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::resetLatticeValueFor (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidate the Lattice <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of <span class="doxyComputerOutput">Call</span> and its users after specializing the call.</p>


<p>Then recompute it.</p>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>

</div>
</div>

### resolvedUndefsIn() {#a814c9ef427065262b0ff3c0dc3d9f19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCCPSolver::resolvedUndefsIn (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>resolvedUndefsIn - While solving the dataflow for a function, we assume that branches on undef values cannot reach any of their successors.</p>


<p>However, this is not a safe assumption. After we solve dataflow, this method should be use to handle this. If this returns true, the solver should be rerun.</p>


<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### setLatticeValueForSpecializationArguments() {#ace9cec3152490daf65f67a88717c7b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::setLatticeValueForSpecializationArguments (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/arginfo">ArgInfo</a> &gt; &amp; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the Lattice <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for the arguments of a specialization <span class="doxyComputerOutput">F</span>.</p>


<p>If an argument is <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> then its lattice value is marked with the corresponding actual argument in <span class="doxyComputerOutput">Args</span>. Otherwise, its lattice value is inherited (copied) from the corresponding formal argument in <span class="doxyComputerOutput">Args</span>.</p>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### simplifyInstsInBlock() {#a9cfdaab0d47c510fa75c73885c78cd06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCCPSolver::simplifyInstsInBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; InsertedValues, <a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">Statistic</a> &amp; InstRemovedStat, <a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">Statistic</a> &amp; InstReplacedStat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="#a1f7cd4c14e02c076508142fbb2c1aa79">tryToReplaceWithConstant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845142f96a84f067cb6bf639e37980d0">llvm::wouldInstructionBeTriviallyDead</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### solve() {#a2d6a1ff9823ca3ddb89d80fe379603ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::solve ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Solve - Solve for constants and executable blocks.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2179 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### solveWhileResolvedUndefs() {#a95bd3f2616c863d18afeabf8138175cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::solveWhileResolvedUndefs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>

</div>
</div>

### solveWhileResolvedUndefsIn() {#a659bc647a6b3504fc00f522405ea2b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::solveWhileResolvedUndefsIn (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### solveWhileResolvedUndefsIn() {#a0b22410f3213aaf29c15590e3da1c670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::solveWhileResolvedUndefsIn (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; WorkList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2190 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>

</div>
</div>

### trackValueOfArgument() {#a3bca075219cfb484e464a6f89d37786d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::trackValueOfArgument (<a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>trackValueOfArgument - Mark the specified argument overdefined unless it have range attribute.</p>


<p>This works with both scalars and structs.</p>


<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>.</p>

</div>
</div>

### trackValueOfGlobalVariable() {#a199003a361f6d87612ab03c249ab04c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::trackValueOfGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>trackValueOfGlobalVariable - Clients can use this method to inform the <a href="/web-llvm/docs/api/classes/llvm/sccpsolver">SCCPSolver</a> that it should track loads and stores to the specified global variable if it can.</p>


<p>This is only legal to call if performing Interprocedural SCCP.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### tryToReplaceWithConstant() {#a1f7cd4c14e02c076508142fbb2c1aa79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCCPSolver::tryToReplaceWithConstant (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="#ab14dd263e92d4c88176c888c6b7956f7">addToMustPreserveReturnsInFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="#a9ca89aae97dda0e84dade221194b03e3">getConstantOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a50426b12f4acb3d9f74d0778948e9597">llvm::CallBase::isMustTailCall</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca6c03d5e52bbdefc8c392e3ed77c7d6a1">llvm::LLVMContext::OB_clang_arc_attachedcall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845142f96a84f067cb6bf639e37980d0">llvm::wouldInstructionBeTriviallyDead</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="#a9cfdaab0d47c510fa75c73885c78cd06">simplifyInstsInBlock</a>.</p>

</div>
</div>

### visit() {#a364ce42337c757bcfbfae5e0bd789ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::visit (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitCall() {#a0299e4a68bc89afd5f3599df2fc9fc6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCCPSolver::visitCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 2267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Visitor {#ae04b87183555e131fe5e897dbfc999d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SCCPInstVisitor&gt; llvm::SCCPSolver::Visitor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isConstant() {#ad443783793d65506b0b69745c79d26d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCCPSolver::isConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; LV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a73e8c58e4d729c42b5f27e3d847c54f8">llvm::ValueLatticeElement::getConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a62d37ceb318e78806df7e0a928b0eb1c">llvm::ValueLatticeElement::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a7ab774f05d02e4bbe7817798cdf19186">llvm::ValueLatticeElement::isConstantRange</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a91cf2c952ea87d701fe608fe4aaabfe4">llvm::ConstantRange::isSingleElement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a77590453ed3ac517979894f1f40bca12">llvm::SCCPInstVisitor::getConstantOrNull</a>, <a href="#ae58f6a2457188593908aae83468858d3">isOverdefined</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#abbe263f1f7adf177d16f061137dd8c19">llvm::SCCPInstVisitor::isStructLatticeConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### isOverdefined() {#ae58f6a2457188593908aae83468858d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCCPSolver::isOverdefined (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; LV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a>.</p>


<p>References <a href="#ad443783793d65506b0b69745c79d26d5">isConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#ab20e06908032fd7028c20c1d2d5a248a">llvm::ValueLatticeElement::isUnknownOrUndef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#a409abf8b151a61b0adacda9229f3cc21">findReturnsToZap</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a77590453ed3ac517979894f1f40bca12">llvm::SCCPInstVisitor::getConstantOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sccpsolver-h">SCCPSolver.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp">SCCPSolver.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
