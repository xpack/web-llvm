---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objectsizeoffsetvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ObjectSizeOffsetVisitor` Class Reference

<p>Evaluate the size and offset of an object pointed to by a Value* statically. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ObjectSizeOffsetVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;SubClass, RetTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instruction visitors. <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41236d30fb63a5afc255be644469ef55">ObjectSizeOffsetVisitor</a> (const DataLayout &amp;DL, const TargetLibraryInfo *TLI, LLVMContext &amp;Context, ObjectSizeOpts Options={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sizeoffsetapint">SizeOffsetAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0cefa2bf3b3199ab80b4b897c49e86">compute</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf0370381bb5be6f2e6f4bbe28f3289">visitAllocaInst</a> (AllocaInst &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ed781ba4c19600badfccc2dff6de10">visitArgument</a> (Argument &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cdafccac9da7d9c25309754698eb68a">visitCallBase</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc16b0d0db7fe60390a13fa3d11dd89">visitConstantPointerNull</a> (ConstantPointerNull &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297ef1ba9967684ebfd198469bd91d8c">visitExtractElementInst</a> (ExtractElementInst &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f12b8a5502f6f0e34c20c7910df422">visitExtractValueInst</a> (ExtractValueInst &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81bb5b0675c34a74c62b2547865c8d7b">visitGlobalAlias</a> (GlobalAlias &amp;GA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d90faf3dd7128f83eca30377481bfe">visitGlobalVariable</a> (GlobalVariable &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357c3ded744863e7d61cd7925da5f7a8">visitIntToPtrInst</a> (IntToPtrInst &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d2b338e83bb54392ec08fdc023b544">visitLoadInst</a> (LoadInst &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7410acf190bc26941fa3f2662715097d">visitPHINode</a> (PHINode &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e92e7da4e84204152ef8b23516a903">visitSelectInst</a> (SelectInst &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9154a2cd666bc44eb7ce40faa5e5a32">visitUndefValue</a> (UndefValue &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a310e8c166b51b6e22d9149f43e0ef4">visitInstruction</a> (Instruction &amp;I)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512ec1d3c38a17b21b3fc05c601b0e7c">align</a> (APInt Size, MaybeAlign Align)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/align">Align</a> <span class="doxyComputerOutput">Size</span> according to <span class="doxyComputerOutput">Alignment</span>. <a href="#a512ec1d3c38a17b21b3fc05c601b0e7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8514561e4c9b625bdd600f945ca4055c">findLoadOffsetRange</a> (LoadInst &amp;LoadFrom, BasicBlock &amp;BB, BasicBlock::iterator From, SmallDenseMap&lt; BasicBlock *, OffsetSpan, 8 &gt; &amp;VisitedBlocks, unsigned &amp;ScannedInstCount)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a255e653eee6dd6ef8aa91c49be8296fc">combineOffsetRange</a> (OffsetSpan LHS, OffsetSpan RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1cc74dd65b84119959ffdc41072d9bc">computeImpl</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c621b8d3e19528dddd804de6153cf2">computeValue</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2053f9aaeecf5a8e6ed08cfcd94086">CheckedZextOrTrunc</a> (APInt &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58967d94e07b66631e07f67d9d1607d8">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e3423a8b21cb33de4cb722383353b0">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objectsizeopts">ObjectSizeOpts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb968e84fa03deec7f70246a99d03abc">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311538b41a71f7a122cc67edbd80e145">IntTyBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c17e58129c57df97d946770dd7c00a">Zero</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d6fd636b4ca520e3c5ece7bb3df32d">SeenInsts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5156819cffcd1f3c85efab6781222d13">InstructionsVisited</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaebc4dd3b1cf9e57ff3be8890791203">unknown</a> ()</td>
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

<p>Evaluate the size and offset of an object pointed to by a Value* statically.</p>


<p>Fails if size or offset are not known at compile time.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ObjectSizeOffsetVisitor() {#a41236d30fb63a5afc255be644469ef55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectSizeOffsetVisitor::ObjectSizeOffsetVisitor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts">ObjectSizeOpts</a> Options={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compute() {#a8c0cefa2bf3b3199ab80b4b897c49e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SizeOffsetAPInt ObjectSizeOffsetVisitor::compute (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/offsetspan/#a570730bb165bed0db1f58575b0dd719a">llvm::OffsetSpan::After</a>, <a href="/web-llvm/docs/api/structs/llvm/offsetspan/#aff12e515f8229c427ccd973711c1e674">llvm::OffsetSpan::Before</a>, <a href="/web-llvm/docs/api/structs/llvm/offsetspan/#aeff8d21fedad729dbb810e25ba724665">llvm::OffsetSpan::bothKnown</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8eadefd13f9ab5c5bd023984cbb0dac7109">llvm::ObjectSizeOpts::ExactSizeFromOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/structs/llvm/offsetspan/#a7ee90d1ce6c5d290375e1c3e5abf11f2">llvm::OffsetSpan::knownAfter</a> and <a href="/web-llvm/docs/api/structs/llvm/offsetspan/#a2ec0d64d71c543e76d24244861390d7d">llvm::OffsetSpan::knownBefore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a62ba0e5ee2d86f663c6de4efda6082a7">llvm::getObjectSize</a>.</p>

</div>
</div>

### visitAllocaInst() {#a3bf0370381bb5be6f2e6f4bbe28f3289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitAllocaInst (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#aa20af95aa4e2d7198d12bf87a6a38b1e">aggregatePossibleConstantValues</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8ea78d811e98514cd165dda532286610fd2">llvm::ObjectSizeOpts::Min</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### visitArgument() {#ad2ed781ba4c19600badfccc2dff6de10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitArgument (<a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### visitCallBase() {#a2cdafccac9da7d9c25309754698eb68a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#aa20af95aa4e2d7198d12bf87a6a38b1e">aggregatePossibleConstantValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acdec81ddbe2a44db51de1226fa1ff5f0">llvm::getAllocSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### visitConstantPointerNull() {#a1cc16b0d0db7fe60390a13fa3d11dd89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitConstantPointerNull (<a href="/web-llvm/docs/api/classes/llvm/constantpointernull">ConstantPointerNull</a> &amp; CPN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a> and <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#ab7338f76624b2494acf477ee8ca0dd9f">llvm::ConstantPointerNull::getType</a>.</p>

</div>
</div>

### visitExtractElementInst() {#a297ef1ba9967684ebfd198469bd91d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitExtractElementInst (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### visitExtractValueInst() {#a18f12b8a5502f6f0e34c20c7910df422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitExtractValueInst (<a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### visitGlobalAlias() {#a81bb5b0675c34a74c62b2547865c8d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitGlobalAlias (<a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp; GA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a7666cc7bd9294c7ae9992c41c591e08b">llvm::GlobalAlias::getAliasee</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa1558e13ceef68db8ea9f4e3b5a64cbd">llvm::GlobalValue::isInterposable</a>.</p>

</div>
</div>

### visitGlobalVariable() {#a29d90faf3dd7128f83eca30377481bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a115ac0121663aa8365e095d095d0c633">llvm::GlobalObject::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a51af265dc931258cdb8ffb37ee6decee">llvm::GlobalValue::hasExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a1c66d4eff947253e7610a66379974d63">llvm::GlobalVariable::hasInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa1558e13ceef68db8ea9f4e3b5a64cbd">llvm::GlobalValue::isInterposable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8ea78d811e98514cd165dda532286610fd2">llvm::ObjectSizeOpts::Min</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### visitInstruction() {#a8a310e8c166b51b6e22d9149f43e0ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### visitIntToPtrInst() {#a357c3ded744863e7d61cd7925da5f7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitIntToPtrInst (<a href="/web-llvm/docs/api/classes/llvm/inttoptrinst">IntToPtrInst</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 991 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### visitLoadInst() {#a59d2b338e83bb54392ec08fdc023b544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitLoadInst (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/offsetspan/#aeff8d21fedad729dbb810e25ba724665">llvm::OffsetSpan::bothKnown</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>.</p>

</div>
</div>

### visitPHINode() {#a7410acf190bc26941fa3f2662715097d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a> and <a href="/web-llvm/docs/api/classes/llvm/phinode/#a1f0ff79b64a40d383b891f1baba89c6b">llvm::PHINode::incoming_values</a>.</p>

</div>
</div>

### visitSelectInst() {#a00e92e7da4e84204152ef8b23516a903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitUndefValue() {#aa9154a2cd666bc44eb7ce40faa5e5a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::visitUndefValue (<a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### align() {#a512ec1d3c38a17b21b3fc05c601b0e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ObjectSizeOffsetVisitor::align (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Size, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/align">Align</a> <span class="doxyComputerOutput">Size</span> according to <span class="doxyComputerOutput">Alignment</span>.</p>


<p>If <span class="doxyComputerOutput">Size</span> is greater than getSignedMaxValue(), set it as unknown as we can only represent signed value in <a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a>.</p>


<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### CheckedZextOrTrunc() {#aad2053f9aaeecf5a8e6ed08cfcd94086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectSizeOffsetVisitor::CheckedZextOrTrunc (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### combineOffsetRange() {#a255e653eee6dd6ef8aa91c49be8296fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::combineOffsetRange (<a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a> LHS, <a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a> RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 1125 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### computeImpl() {#ad1cc74dd65b84119959ffdc41072d9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::computeImpl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### computeValue() {#ac1c621b8d3e19528dddd804de6153cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::computeValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### findLoadOffsetRange() {#a8514561e4c9b625bdd600f945ca4055c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan ObjectSizeOffsetVisitor::findLoadOffsetRange (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; LoadFrom, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> From, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a>, 8 &gt; &amp; VisitedBlocks, unsigned &amp; ScannedInstCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#a58967d94e07b66631e07f67d9d1607d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::ObjectSizeOffsetVisitor::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

### InstructionsVisited {#a5156819cffcd1f3c85efab6781222d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ObjectSizeOffsetVisitor::InstructionsVisited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

### IntTyBits {#a311538b41a71f7a122cc67edbd80e145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ObjectSizeOffsetVisitor::IntTyBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

### Options {#adb968e84fa03deec7f70246a99d03abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectSizeOpts llvm::ObjectSizeOffsetVisitor::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

### SeenInsts {#a66d6fd636b4ca520e3c5ece7bb3df32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;Instruction *, OffsetSpan, 8&gt; llvm::ObjectSizeOffsetVisitor::SeenInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

### TLI {#a94e3423a8b21cb33de4cb722383353b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::ObjectSizeOffsetVisitor::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

### Zero {#ac5c17e58129c57df97d946770dd7c00a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::ObjectSizeOffsetVisitor::Zero</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### unknown() {#acaebc4dd3b1cf9e57ff3be8890791203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetSpan llvm::ObjectSizeOffsetVisitor::unknown ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
