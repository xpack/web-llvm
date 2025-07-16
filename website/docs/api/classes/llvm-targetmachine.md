---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetmachine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TargetMachine` Class Reference

<p>Primary interface to the complete machine description for the target machine. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetMachine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl">CodeGenTargetMachineImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>implements a set of functionality in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a></span> class for targets that make use of the independent code generator (CodeGen) library. <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715d42b344e67511d8ea6b9c88876c23">TargetMachine</a> (const TargetMachine &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a> (const Target &amp;T, StringRef DataLayoutString, const Triple &amp;TargetTriple, StringRef CPU, StringRef FS, const TargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5319a5805c0cbcf008ac45415c9b96e">~TargetMachine</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb46dac70f3e9f315181c9fd7d848b08">operator=</a> (const TargetMachine &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce0da689ac32105fc6b050de94868bf">getTarget</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33fe94054a904130a7c774f78423c8b7">getTargetTriple</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4930d9bba5bf85a86c2177b950c10f">getTargetCPU</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b02eb89292775ff6e6a2ece94f961f">getTargetFeatureString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf8f29034e2aae38cbee562ddd194ca">setTargetFeatureString</a> (StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5e684928b2e3df5c0566ff3d4cfbfb">getSubtargetImpl</a> (const Function &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable. <a href="#a9a5e684928b2e3df5c0566ff3d4cfbfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a782928f486dd751b008f3a30bb0977c0">getObjFileLowering</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f0027ccb45dd6c9aab3966c13b02d3">createMachineFunctionInfo</a> (BumpPtrAllocator &amp;Allocator, const Function &amp;F, const TargetSubtargetInfo *STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a33f0027ccb45dd6c9aab3966c13b02d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e72bedab03b27d33dc9aa93f2bcbd6">createDefaultFuncInfoYAML</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a default initialized instance of the YAML representation for the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#ac4e72bedab03b27d33dc9aa93f2bcbd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fbe43e7b40604ccef7f06cd495f5c30">convertFuncInfoToYAML</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and initialize an instance of the YAML representation of the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a7fbe43e7b40604ccef7f06cd495f5c30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72cc273e2975b2caf712993f47d0ad9">parseMachineFunctionInfo</a> (const yaml::MachineFunctionInfo &amp;, PerFunctionMIParsingState &amp;PFS, SMDiagnostic &amp;Error, SMRange &amp;SourceRange) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse out the target's <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> from the YAML reprsentation. <a href="#ae72cc273e2975b2caf712993f47d0ad9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename STC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> STC &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a547b014aa7a464bb6371b4be6f9817e8">getSubtarget</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns a pointer to the specified type of <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a>. <a href="#a547b014aa7a464bb6371b4be6f9817e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34825337fd4c67c855cfc5d6d3a87788">createDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>. <a href="#a34825337fd4c67c855cfc5d6d3a87788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae86be92c723d5de55d99eca606c8cc">isCompatibleDataLayout</a> (const DataLayout &amp;Candidate) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> if compatible with the CodeGen for this target. <a href="#acae86be92c723d5de55d99eca606c8cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec7f7ca20aecbaf5bdd98c9cf866298">getPointerSize</a> (unsigned AS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pointer size for this target. <a href="#a6ec7f7ca20aecbaf5bdd98c9cf866298">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a411a3e39c13b46c05558240901cd3c">getPointerSizeInBits</a> (unsigned AS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad064e269d4fe74038cd6e04b6bc49a06">getProgramPointerSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3b25e081b3cb943e397b5105d74bea">getAllocaPointerSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a50afebb9bed07d36be2bac4c6f729">resetTargetOptions</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the target options based on the function's attributes. <a href="#af0a50afebb9bed07d36be2bac4c6f729">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb72c5626afbc815284e2b26bb0663f8">getMCAsmInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return target specific asm information. <a href="#afb72c5626afbc815284e2b26bb0663f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35986fd6211188deafdb8a3902cee03">getMCRegisterInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92155c8483cac23d6f8fed069521ba7c">getMCInstrInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f850d2654c88a73a7d6b1701ae5f778">getMCSubtargetInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26259e17b2c6cd3b33c161c302da8d68">getIntrinsicInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If intrinsic information is available, return it. If not, return null. <a href="#a26259e17b2c6cd3b33c161c302da8d68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa276e49983e93afa359ec83ad71ccadc">requiresStructuredCFG</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab914199574166419ae7e055ce1f43a0">setRequiresStructuredCFG</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846a6b6b666a842d3a17f128e1826bc4">getRelocationModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the code generation relocation model. <a href="#a846a6b6b666a842d3a17f128e1826bc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae106f6c6362377b3016f0d174227e193">getCodeModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the code model. <a href="#ae106f6c6362377b3016f0d174227e193">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f21a13fb913784a6a3b7e0a103827a8">getMaxCodeSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum code size possible under the code model. <a href="#a2f21a13fb913784a6a3b7e0a103827a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3afe0eadb00a51b47d5b96adeceaf1">setCodeModel</a> (CodeModel::Model CM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the code model. <a href="#aea3afe0eadb00a51b47d5b96adeceaf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f3dc6c5c58d95e41ff8d2e04f78694">setLargeDataThreshold</a> (uint64_t LDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5d09e961ee51900ce14d985bbc0839b">isLargeGlobalValue</a> (const GlobalValue *GV) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5ffac7fd84af772a216629f8bd6da9">isPositionIndependent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f0dc829be1fe9aa1c7d5151db1bf21">shouldAssumeDSOLocal</a> (const GlobalValue *GV) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a650b3b6ac132345d10690adc3e3f418c">useEmulatedTLS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this target uses emulated TLS. <a href="#a650b3b6ac132345d10690adc3e3f418c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b41be7605fb3c5d5485b6521aa561d9">useTLSDESC</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this target uses TLS Descriptors. <a href="#a3b41be7605fb3c5d5485b6521aa561d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120">TLSModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07028bb765a646ca5ca5375162a93d7c">getTLSModel</a> (const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the TLS model which should be used for the given global variable. <a href="#a07028bb765a646ca5ca5375162a93d7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030edbec5a50c887caf3ec95c7c50c44">getOptLevel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the optimization level: None, Less, Default, or Aggressive. <a href="#a030edbec5a50c887caf3ec95c7c50c44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a5b8058f50fc20fec2e9e7d8a674a6">setOptLevel</a> (CodeGenOptLevel Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overrides the optimization level. <a href="#a98a5b8058f50fc20fec2e9e7d8a674a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39135b2379ed114c1fe9035e497b18b7">setFastISel</a> (bool Enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe330a3972c5bf72e4093fd113c6ebac">getO0WantsFastISel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac018674200ea43bc03522bf1afbcca7a">setO0WantsFastISel</a> (bool Enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf9d8e59809f5486cd5ecef50e95ea5d">setGlobalISel</a> (bool Enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a03eaf18d396eb46f4c1a41bec628c">setGlobalISelAbort</a> (GlobalISelAbortMode Mode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35061955fa2e0fbba033286ae5ac1e56">setMachineOutliner</a> (bool Enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fadf68fc47b2f0e3a8dd55de3ec93c4">setSupportsDefaultOutlining</a> (bool Enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044ef65e7e12002d61ddbc98bc7e37ea">setSupportsDebugEntryValues</a> (bool Enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6448068659187735a2f57ef78d9ebbbd">setCFIFixup</a> (bool Enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb7b7446aa4f151dbd0bc2ee7420102">getAIXExtendedAltivecABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c05f5558f52383f362ff9c4cf7de8ce">getUniqueSectionNames</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f5924a8286507885cb8c080e591cfe">getUniqueBasicBlockSectionNames</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if unique basic block section names must be generated. <a href="#a67f5924a8286507885cb8c080e591cfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49533cf3eaec93375603c3b1e1dd64d4">getSeparateNamedSections</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88880f638789a2b753b5dc51bbb84eb">getDataSections</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if data objects should be emitted into their own section, corresponds to -fdata-sections. <a href="#ad88880f638789a2b753b5dc51bbb84eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77edbddebe48a5b1016c99d6ee0bb58">getFunctionSections</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if functions should be emitted into their own section, corresponding to -ffunction-sections. <a href="#af77edbddebe48a5b1016c99d6ee0bb58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b6bf1b1f018af4f76b19a45dbc30048">getIgnoreXCOFFVisibility</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if visibility attribute should not be emitted in <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a>, corresponding to -mignore-xcoff-visibility. <a href="#a5b6bf1b1f018af4f76b19a45dbc30048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f7d0a68c98e09d9023f4cdbff2dcbe">getXCOFFTracebackTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> traceback table should be emitted, corresponding to -xcoff-traceback-table. <a href="#ad1f7d0a68c98e09d9023f4cdbff2dcbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8">llvm::BasicBlockSection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab3c5f91842d5dd9f6aaf78a1ff34a9">getBBSectionsType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If basic blocks should be emitted into their own section, corresponding to -fbasic-block-sections. <a href="#afab3c5f91842d5dd9f6aaf78a1ff34a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e6d68208c385fa29fe43b305342cfd">getBBSectionsFuncListBuf</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of functions and basic block ids that need unique sections. <a href="#a49e6d68208c385fa29fe43b305342cfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321fbc5faf6c190cd1f90c19c3101cb4">isNoopAddrSpaceCast</a> (unsigned SrcAS, unsigned DestAS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a cast between SrcAS and DestAS is a noop. <a href="#a321fbc5faf6c190cd1f90c19c3101cb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35446b7e91638289cf6c36a35faef2d">setPGOOption</a> (std::optional&lt; PGOOptions &gt; PGOOpt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a456c76bb8d844400ac4baffbd090e6">getPGOOption</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7467e344da07f6b9e562e6fec2d08946">getAssumedAddrSpace</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified generic pointer could be assumed as a pointer to a specific address space, return that address space. <a href="#a7467e344da07f6b9e562e6fec2d08946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c08834ce7a667c0fc6277efa1a96072">getPredicatedAddrSpace</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified predicate checks whether a generic pointer falls within a specified address space, return that generic pointer and the address space being queried. <a href="#a1c08834ce7a667c0fc6277efa1a96072">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetiranalysis">TargetIRAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f75813c496f966352b35327085da9f">getTargetIRAnalysis</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetiranalysis">TargetIRAnalysis</a></span> appropriate for the target. <a href="#ab0f75813c496f966352b35327085da9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d17091515cc3617c0901a05308f27b">getTargetTransformInfo</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> for a given function. <a href="#a89d17091515cc3617c0901a05308f27b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fff160f7403fccaa91aa6ac107369a2">registerPassBuilderCallbacks</a> (PassBuilder &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow the target to modify the pass pipeline. <a href="#a1fff160f7403fccaa91aa6ac107369a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7caacf1b6625cc8fce9e8e9f5c95268">registerDefaultAliasAnalyses</a> (AAManager &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow the target to register alias analyses with the <a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> for use with the new pass manager. <a href="#ab7caacf1b6625cc8fce9e8e9f5c95268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e27cb1cb4e03cb35f6eb7690d3e8ff">addPassesToEmitFile</a> (PassManagerBase &amp;, raw_pwrite_stream &amp;, raw_pwrite_stream *, CodeGenFileType, bool=true, MachineModuleInfoWrapperPass *MMIWP=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes to the specified pass manager to get the specified file emitted. <a href="#a16e27cb1cb4e03cb35f6eb7690d3e8ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b157b36b2fc00d830a8b7d1546d746c">addPassesToEmitMC</a> (PassManagerBase &amp;, MCContext *&amp;, raw_pwrite_stream &amp;, bool=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes to the specified pass manager to get machine code emitted with the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>. <a href="#a8b157b36b2fc00d830a8b7d1546d746c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bf05675e97c30dca57554248f19976">targetSchedulesPostRAScheduling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if subtarget inserts the final scheduling pass on its own. <a href="#a87bf05675e97c30dca57554248f19976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25263afe4b2685f4571b432ced7d171">getNameWithPrefix</a> (SmallVectorImpl&lt; char &gt; &amp;Name, const GlobalValue *GV, Mangler &amp;Mang, bool MayAlwaysUsePrivate=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc39c2b4b06165d766b52ac292ef2aff">getSymbol</a> (const GlobalValue *GV) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ff5f9c66b8fc83ad263fc044a4d6bb">getSjLjDataSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a9240c1e9e65f3214187466bba86ef">getAddressSpaceForPseudoSourceKind</a> (unsigned Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAddressSpaceForPseudoSourceKind - Given the kind of memory (e.g. <a href="#a13a9240c1e9e65f3214187466bba86ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34172b9e43fd9c3df636174685acf800">splitModule</a> (Module &amp;M, unsigned NumParts, function_ref&lt; void(std::unique_ptr&lt; Module &gt; MPart)&gt; ModuleCallback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Entry point for module splitting. <a href="#a34172b9e43fd9c3df636174685acf800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71d6e343ca5910e1cceb77975986eda">createPassConfig</a> (PassManagerBase &amp;PM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes. <a href="#ac71d6e343ca5910e1cceb77975986eda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81bca75fcc1eb78a4ed598d55dbdd536">buildCodeGenPipeline</a> (ModulePassManager &amp;, raw_pwrite_stream &amp;, raw_pwrite_stream *, CodeGenFileType, const CGPassBuilderOption &amp;, PassInstrumentationCallbacks *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9680f0fdc42257247707862d76be7f">isMachineVerifierClean</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target is expected to pass all machine verifier checks. <a href="#aac9680f0fdc42257247707862d76be7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40506e8d8d82812f5f0e99c59aab0a09">addAsmPrinter</a> (PassManagerBase &amp;PM, raw_pwrite_stream &amp;Out, raw_pwrite_stream *DwoOut, CodeGenFileType FileType, MCContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> pass to the pipeline that prints assembly or machine code from the MI representation. <a href="#a40506e8d8d82812f5f0e99c59aab0a09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c631a136ffc02532e4334c6357ec49e">createMCStreamer</a> (raw_pwrite_stream &amp;Out, raw_pwrite_stream *DwoOut, CodeGenFileType FileType, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280c50132f28bb2f82be5f8c32d81406">usesPhysRegsForValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target uses physical regs (as nearly all targets do). <a href="#a280c50132f28bb2f82be5f8c32d81406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7dde9cfe1ea0eb1b353ee84061a2f3f">useIPRA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target wants to use interprocedural register allocation by default. <a href="#ae7dde9cfe1ea0eb1b353ee84061a2f3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614d70c089e208c5876f8fcceda06214">unqualifiedInlineAsmVariant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The default variant to use in unqualified <span class="doxyComputerOutput">asm</span> instructions. <a href="#a614d70c089e208c5876f8fcceda06214">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb18773adf0c1b4bfa5686b27f803ab">registerMachineRegisterInfoCallback</a> (MachineFunction &amp;MF) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a></td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde45f08eafa48f29b1b6d9f98a38814">TheTarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> that this machine was created for. <a href="#adde45f08eafa48f29b1b6d9f98a38814">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for the target: keep ABI type size and alignment. <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05856d96e88224279af8b29edfd1c9ad">TargetTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> string, CPU name, and target feature strings the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> instance is created with. <a href="#a05856d96e88224279af8b29edfd1c9ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca45577ddb8efe4904398939fae28d1">TargetCPU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795cc09ce82b6ef057e5400a5cee7d68">TargetFS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588867fa922c392886b07e0ad42038b4">RM</a> = <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">Reloc::Static</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320899bd91c5ee07e2fa3f2dd7ae9ca1">CMModel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">CodeModel::Small</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed0d9d3435519eeec1fecfa49753077">LargeDataThreshold</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa79b97443f6239f18c08e85a0a4fcfd">OptLevel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f434744b4ee29d39763ce90aae0156">AsmInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains target specific asm information. <a href="#a05f434744b4ee29d39763ce90aae0156">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7371bb744de95d18d5b583bedf49056">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6199d597301a76dc85a4c244549fdd">MII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaebd1c0e5f028848cc0e548bf015aaf1">STI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf089bfce826d2561637f8a6b388e27d">RequireStructuredCFG</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9398df1c20ab3f6d740829adfa6e56d9">O0WantsFastISel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da43f2ecd711e926d8eccdd80b70df9">PGOOption</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; int, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad5195630dbe90240748e648ff267d05">parseBinutilsVersion</a> (StringRef Version)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a9baa3e95a359eb7d89b671c19be78">DefaultSjLjDataSize</a> = 32</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The integer bit size to use for SjLj based exception handling. <a href="#a86a9baa3e95a359eb7d89b671c19be78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Primary interface to the complete machine description for the target machine.</p>


<p>All target-specific information should be accessible through this interface.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetMachine() {#a715d42b344e67511d8ea6b9c88876c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetMachine::TargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### TargetMachine() {#af0be9a5447cbeb928c2e3156cc071017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine::TargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DataLayoutString, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="#a05f434744b4ee29d39763ce90aae0156">AsmInfo</a>, <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>, <a href="#a6f6199d597301a76dc85a4c244549fdd">MII</a>, <a href="#af7371bb744de95d18d5b583bedf49056">MRI</a>, <a href="#a9398df1c20ab3f6d740829adfa6e56d9">O0WantsFastISel</a>, <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>, <a href="#abf089bfce826d2561637f8a6b388e27d">RequireStructuredCFG</a>, <a href="#aaebd1c0e5f028848cc0e548bf015aaf1">STI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a9ca45577ddb8efe4904398939fae28d1">TargetCPU</a>, <a href="#a795cc09ce82b6ef057e5400a5cee7d68">TargetFS</a>, <a href="#a05856d96e88224279af8b29edfd1c9ad">TargetTriple</a> and <a href="#adde45f08eafa48f29b1b6d9f98a38814">TheTarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="#acb46dac70f3e9f315181c9fd7d848b08">operator=</a> and <a href="#a715d42b344e67511d8ea6b9c88876c23">TargetMachine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TargetMachine() {#ac5319a5805c0cbcf008ac45415c9b96e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine::~TargetMachine ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#acb46dac70f3e9f315181c9fd7d848b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAsmPrinter() {#a40506e8d8d82812f5f0e99c59aab0a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::addAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> * DwoOut, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a> FileType, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> pass to the pipeline that prints assembly or machine code from the MI representation.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### addPassesToEmitFile() {#a16e27cb1cb4e03cb35f6eb7690d3e8ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::addPassesToEmitFile (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a>, bool, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass">MachineModuleInfoWrapperPass</a> * MMIWP=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes to the specified pass manager to get the specified file emitted.</p>


<p>Typically this will involve several steps of code generation. This method should return true if emission of this file type is not supported, or false on success. <span class="doxyComputerOutput">MMIWP</span> is an optional parameter that, if set to non-nullptr, will be used to set the MachineModuloInfo for this PM.</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### addPassesToEmitMC() {#a8b157b36b2fc00d830a8b7d1546d746c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::addPassesToEmitMC (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> *&amp;, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp;, bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes to the specified pass manager to get machine code emitted with the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>.</p>


<p>This method returns true if machine code is not supported. It fills the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> Ctx pointer which can be used to build custom <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a>.</p>


<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### buildCodeGenPipeline() {#a81bca75fcc1eb78a4ed598d55dbdd536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::TargetMachine::buildCodeGenPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/cgpassbuilderoption">CGPassBuilderOption</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### convertFuncInfoToYAML() {#a7fbe43e7b40604ccef7f06cd495f5c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual yaml::MachineFunctionInfo * llvm::TargetMachine::convertFuncInfoToYAML (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate and initialize an instance of the YAML representation of the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### createDataLayout() {#a34825337fd4c67c855cfc5d6d3a87788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout llvm::TargetMachine::createDataLayout ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>.</p>

</div>
</div>

### createDefaultFuncInfoYAML() {#ac4e72bedab03b27d33dc9aa93f2bcbd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual yaml::MachineFunctionInfo * llvm::TargetMachine::createDefaultFuncInfoYAML ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate and return a default initialized instance of the YAML representation for the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### createMachineFunctionInfo() {#a33f0027ccb45dd6c9aab3966c13b02d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineFunctionInfo * llvm::TargetMachine::createMachineFunctionInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#aaebd1c0e5f028848cc0e548bf015aaf1">STI</a>.</p>

</div>
</div>

### createMCStreamer() {#a1c631a136ffc02532e4334c6357ec49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; std::unique_ptr&lt; MCStreamer &gt; &gt; llvm::TargetMachine::createMCStreamer (<a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> * DwoOut, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a> FileType, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### createPassConfig() {#ac71d6e343ca5910e1cceb77975986eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual TargetPassConfig * llvm::TargetMachine::createPassConfig (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### getAddressSpaceForPseudoSourceKind() {#a13a9240c1e9e65f3214187466bba86ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetMachine::getAddressSpaceForPseudoSourceKind (unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAddressSpaceForPseudoSourceKind - Given the kind of memory (e.g.</p>


<p>stack) the target returns the corresponding address space.</p>


<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### getAIXExtendedAltivecABI() {#a2fb7b7446aa4f151dbd0bc2ee7420102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getAIXExtendedAltivecABI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getAllocaPointerSize() {#a1b3b25e081b3cb943e397b5105d74bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetMachine::getAllocaPointerSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>.</p>

</div>
</div>

### getAssumedAddrSpace() {#a7467e344da07f6b9e562e6fec2d08946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetMachine::getAssumedAddrSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the specified generic pointer could be assumed as a pointer to a specific address space, return that address space.</p>


<p>Under offloading programming, the offloading target may be passed with values only prepared on the host side and could assume certain properties.</p>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### getBBSectionsFuncListBuf() {#a49e6d68208c385fa29fe43b305342cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemoryBuffer * llvm::TargetMachine::getBBSectionsFuncListBuf ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the list of functions and basic block ids that need unique sections.</p>

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getBBSectionsType() {#afab3c5f91842d5dd9f6aaf78a1ff34a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BasicBlockSection llvm::TargetMachine::getBBSectionsType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If basic blocks should be emitted into their own section, corresponding to -fbasic-block-sections.</p>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a59db5d89fd98ad566ef2159ec3450f0d">assignSections</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>.</p>

</div>
</div>

### getCodeModel() {#ae106f6c6362377b3016f0d174227e193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeModel::Model llvm::TargetMachine::getCodeModel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the code model.</p>


<p>The choices are small, kernel, medium, large, and target default.</p>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a320899bd91c5ee07e2fa3f2dd7ae9ca1">CMModel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a411b83001c7fb0aa941c0f6daef18f05">llvm::X86InstrInfo::canMakeTailCallConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="#a2f21a13fb913784a6a3b7e0a103827a8">getMaxCodeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#af2168b4e8c9abe5efab1acc532d50feb">llvm::PPCTargetLowering::isAccessedAsGotIndirect</a>, <a href="#ae5d09e961ee51900ce14d985bbc0839b">isLargeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad1a79970217e7be886648d06d5fded3c">llvm::X86TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a496a2f61ad3c4221c58805e32bc47e5c">IsSmallObject</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6a2a00931f022fa78f6cdadb07e6d775">llvm::PPCSubtarget::isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetmachine/#ad4c676bf9a496db85baa599666ac50b8">llvm::LanaiTargetMachine::LanaiTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectbranchtracking-cpp/#a20120e38ef14ac883533e0213dd2ad14">needsPrologueENDBR</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>.</p>

</div>
</div>

### getDataSections() {#ad88880f638789a2b753b5dc51bbb84eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getDataSections ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if data objects should be emitted into their own section, corresponds to -fdata-sections.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getFunctionSections() {#af77edbddebe48a5b1016c99d6ee0bb58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getFunctionSections ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if functions should be emitted into their own section, corresponding to -ffunction-sections.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getIgnoreXCOFFVisibility() {#a5b6bf1b1f018af4f76b19a45dbc30048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getIgnoreXCOFFVisibility ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if visibility attribute should not be emitted in <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a>, corresponding to -mignore-xcoff-visibility.</p>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getIntrinsicInfo() {#a26259e17b2c6cd3b33c161c302da8d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TargetIntrinsicInfo * llvm::TargetMachine::getIntrinsicInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If intrinsic information is available, return it. If not, return null.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### getMaxCodeSize() {#a2f21a13fb913784a6a3b7e0a103827a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t TargetMachine::getMaxCodeSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum code size possible under the code model.</p>

<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="#ae106f6c6362377b3016f0d174227e193">getCodeModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80bd4ec8a9b2f8e7d9d75ab708a55c2">llvm::maxUIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a>.</p>

</div>
</div>

### getMCAsmInfo() {#afb72c5626afbc815284e2b26bb0663f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo * llvm::TargetMachine::getMCAsmInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return target specific asm information.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a05f434744b4ee29d39763ce90aae0156">AsmInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ad7e593e787ba6a94dbd287c32abe4006">llvm::X86FrameLowering::canUseLEAForSPInEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aa5f78769915f0742f77e73e45abab318">llvm::X86FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#ad4dfea35c4a2a801cf100b1be76b7329">llvm::TargetFrameLowering::enableCFIFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a1bf38b3bbe867377cde6e530a0256b29">llvm::AArch64InstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad95410bacc3866f071ecb8353986494e">llvm::ARCInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a6395fc391c48db81db6a83fef912ac07">llvm::ARMBaseInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a0364a53c9b3c44ded29d94829cfe0b4d">llvm::CSKYInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#ae4bbae04e39720c0cdd662233f32613d">llvm::LoongArchInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1e06e0f33a78381418e60bf850e7efde">llvm::MipsInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a7d0ea970ec4a5d5cb4e1d1391a2bc7af">llvm::MSP430InstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adaba46ae7351c9a651fc32fae020cb0d">llvm::PPCInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a8424c147a24cf4d707de1b7392597e48">llvm::RISCVInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0ced2d6b15f87f297ec231c753e624e6">llvm::SIInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#af092c4cd28507745f414a4bc21f3c8d0">llvm::SparcInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a4c2125b3c274c53648d92976315fb9e1">llvm::SystemZInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a3d56aa3e819a1d52538ae8294b0c0b3e">llvm::XtensaInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#aada6bb4af36a2736480f0c51fced2d58">llvm::ARMSubtarget::getPushPopSplitVariation</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#aab2e617786f0429ea73422f70fdb0606">llvm::HexagonInstrInfo::getSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a738e789cdbd35bf07b744925b6f6ae4e">llvm::X86::isExtendedSwiftAsyncFrameSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8e7ea4a37a21caeb8c336ef3e95f8ee0">llvm::AArch64InstrInfo::isFunctionSafeToOutlineFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#aaa6625e357c6806a89b36759ae16b630">llvm::AArch64FunctionInfo::needsDwarfUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#a3b2bec8faee9b97ef8c297fb0cedabdb">llvm::WebAssemblyFrameLowering::needsPrologForEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1aedcec79ca92a0d2b20626d30ebc15d">needsWinCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a1aedcec79ca92a0d2b20626d30ebc15d">needsWinCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a33a9bde0ee9fe5d047f5c84642436bb8">needsWinCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6a8d1523f211998978b3fa0bfe8818a1">llvm::X86FrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/classes/anonymous-thumb2sizereduction-cpp-/thumb2sizereduce/#a0c70c731d0c61ed9a18b61ea303aa44c">anonymous{Thumb2SizeReduction.cpp}::Thumb2SizeReduce::runOnMachineFunction</a>.</p>

</div>
</div>

### getMCInstrInfo() {#a92155c8483cac23d6f8fed069521ba7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo * llvm::TargetMachine::getMCInstrInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a6f6199d597301a76dc85a4c244549fdd">MII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a> and <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>.</p>

</div>
</div>

### getMCRegisterInfo() {#ae35986fd6211188deafdb8a3902cee03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo * llvm::TargetMachine::getMCRegisterInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#af7371bb744de95d18d5b583bedf49056">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a> and <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>.</p>

</div>
</div>

### getMCSubtargetInfo() {#a3f850d2654c88a73a7d6b1701ae5f778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo * llvm::TargetMachine::getMCSubtargetInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#aaebd1c0e5f028848cc0e548bf015aaf1">STI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#ad60d0495301b78e11523def2cb8b2b59">llvm::ARMElfTargetObjectFile::Initialize</a>.</p>

</div>
</div>

### getNameWithPrefix() {#af25263afe4b2685f4571b432ced7d171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetMachine::getNameWithPrefix (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a> &amp; Mang, bool MayAlwaysUsePrivate=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a05a26c90a4811f2e63a64f0c3660ae09">llvm::TargetLoweringObjectFile::getNameWithPrefix</a>, <a href="#a782928f486dd751b008f3a30bb0977c0">getObjFileLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ed4c5535997ad77ffee00f92430b576">llvm::GlobalValue::hasPrivateLinkage</a>.</p>


<p>Referenced by <a href="#acc39c2b4b06165d766b52ac292ef2aff">getSymbol</a>.</p>

</div>
</div>

### getO0WantsFastISel() {#abe330a3972c5bf72e4093fd113c6ebac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getO0WantsFastISel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a9398df1c20ab3f6d740829adfa6e56d9">O0WantsFastISel</a>.</p>

</div>
</div>

### getObjFileLowering() {#a782928f486dd751b008f3a30bb0977c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual TargetLoweringObjectFile * llvm::TargetMachine::getObjFileLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#af25263afe4b2685f4571b432ced7d171">getNameWithPrefix</a>, <a href="#acc39c2b4b06165d766b52ac292ef2aff">getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a01fb99881498447f36c9568903275b63">llvm::LanaiTargetLowering::LowerConstantPool</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a710c8f170506ce6c3abd66ada911e231">llvm::LanaiTargetLowering::LowerGlobalAddress</a>.</p>

</div>
</div>

### getOptLevel() {#a030edbec5a50c887caf3ec95c7c50c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::TargetMachine::getOptLevel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the optimization level: None, Less, Default, or Aggressive.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#afa79b97443f6239f18c08e85a0a4fcfd">OptLevel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#aa71d343a68eaa436458cd76f349f399a">AlignBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a26ac022a6476b64058ee229046f54034">canOptimizeTLSDFormToXForm</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbitsanalysis/#a8298169df1e09b2f28eacd99dfe6b335">llvm::GISelKnownBitsAnalysis::get</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a75d48c8917ed2a09d85cf46fcda67002">llvm::HexagonFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a484c3893b6ffdebaa29296c58fc366a1">llvm::HexagonFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a18a4e42f7e87c45cc17df255466262db">isOptNone</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowercontrolflow-cpp-/silowercontrolflow/#a50b92c758d08d3acdda45455f661f5c5">anonymous{SILowerControlFlow.cpp}::SILowerControlFlow::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopytocombine-cpp-/hexagoncopytocombine/#a9c768afdfbc0a2c828dfe51e2d05e662">anonymous{HexagonCopyToCombine.cpp}::HexagonCopyToCombine::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86speculativeexecutionsideeffectsuppression-cpp-/x86speculativeexecutionsideeffectsuppression/#a4edf4c36d95f9f36e33d84f84626b849">anonymous{X86SpeculativeExecutionSideEffectSuppression.cpp}::X86SpeculativeExecutionSideEffectSuppression::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a98e4a98a0db786235d78fce93ad4a72f">llvm::InstructionSelect::runOnMachineFunction</a>.</p>

</div>
</div>

### getPGOOption() {#a3a456c76bb8d844400ac4baffbd090e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; PGOOptions &gt; &amp; llvm::TargetMachine::getPGOOption ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a7da43f2ecd711e926d8eccdd80b70df9">PGOOption</a>.</p>

</div>
</div>

### getPointerSize() {#a6ec7f7ca20aecbaf5bdd98c9cf866298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetMachine::getPointerSize (unsigned AS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the pointer size for this target.</p>


<p>This is the only time the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> in the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> is used.</p>


<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzframelowering/#a516e35ba62aa8885c3ec33a969406b4b">llvm::SystemZFrameLowering::create</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetmachine/#a879b6a5885092a97ba2bbc28c7786a26">llvm::AVRTargetMachine::isNoopAddrSpaceCast</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#a05a4ef84c2d57dcff0762a5136595258">llvm::X86TargetMachine::isNoopAddrSpaceCast</a>.</p>

</div>
</div>

### getPointerSizeInBits() {#a5a411a3e39c13b46c05558240901cd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetMachine::getPointerSizeInBits (unsigned AS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>.</p>

</div>
</div>

### getPredicatedAddrSpace() {#a1c08834ce7a667c0fc6277efa1a96072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::pair&lt; const Value *, unsigned &gt; llvm::TargetMachine::getPredicatedAddrSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the specified predicate checks whether a generic pointer falls within a specified address space, return that generic pointer and the address space being queried.</p>


<p>Such predicates could be specified in @llvm.assume intrinsics for the optimizer to assume that the given generic pointer always falls within the address space based on that predicate.</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### getProgramPointerSize() {#ad064e269d4fe74038cd6e04b6bc49a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetMachine::getProgramPointerSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>.</p>

</div>
</div>

### getRelocationModel() {#a846a6b6b666a842d3a17f128e1826bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model TargetMachine::getRelocationModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the code generation relocation model.</p>


<p>The choices are static, PIC, and dynamic-no-pic, and target default.</p>


<p>The choices are static, PIC, and dynamic-no-pic.</p>


<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>Reference <a href="#a588867fa922c392886b07e0ad42038b4">RM</a>.</p>


<p>Referenced by <a href="#a07028bb765a646ca5ca5375162a93d7c">getTLSModel</a>, <a href="#a0e5ffac7fd84af772a216629f8bd6da9">isPositionIndependent</a>, <a href="#aa3f0dc829be1fe9aa1c7d5151db1bf21">shouldAssumeDSOLocal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>.</p>

</div>
</div>

### getSeparateNamedSections() {#a49533cf3eaec93375603c3b1e1dd64d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getSeparateNamedSections ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getSjLjDataSize() {#a53ff5f9c66b8fc83ad263fc044a4d6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetMachine::getSjLjDataSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a86a9baa3e95a359eb7d89b671c19be78">DefaultSjLjDataSize</a>.</p>

</div>
</div>

### getSubtarget() {#a547b014aa7a464bb6371b4be6f9817e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename STC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const STC &amp; llvm::TargetMachine::getSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method returns a pointer to the specified type of <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a>.</p>


<p>In debug builds, it verifies that the object being returned is of the correct type.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a9a5e684928b2e3df5c0566ff3d4cfbfb">getSubtargetImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemztdc-cpp-/systemztdcpass/#a297c01ed88bcbeaac178adb0ff9e497f">anonymous{SystemZTDC.cpp}::SystemZTDCPass::runOnFunction</a>.</p>

</div>
</div>

### getSubtargetImpl() {#a9a5e684928b2e3df5c0566ff3d4cfbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TargetSubtargetInfo * llvm::TargetMachine::getSubtargetImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#a547b014aa7a464bb6371b4be6f9817e8">getSubtarget</a> and <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#a7cac2bf189a71c58d1514aaaac25414a">anonymous{SafeStack.cpp}::SafeStackLegacyPass::runOnFunction</a>.</p>

</div>
</div>

### getSymbol() {#acc39c2b4b06165d766b52ac292ef2aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * TargetMachine::getSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2156a9e22505242a9118da71e8054269">llvm::TargetLoweringObjectFile::getMangler</a>, <a href="#af25263afe4b2685f4571b432ced7d171">getNameWithPrefix</a>, <a href="#a782928f486dd751b008f3a30bb0977c0">getObjFileLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#aefd13b57605f8327527a11ad50c0a68f">llvm::TargetLoweringObjectFile::getTargetSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a7dfd846c7bc87f28f0dc5dab92e7fe58">llvm::NVPTXTargetLowering::getParamName</a>.</p>

</div>
</div>

### getTarget() {#adce0da689ac32105fc6b050de94868bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target &amp; llvm::TargetMachine::getTarget ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#adde45f08eafa48f29b1b6d9f98a38814">TheTarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#acf14ffe7608cbfcc75f2858e0eaa38e7">llvm::CodeGenTargetMachineImpl::addAsmPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a> and <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>.</p>

</div>
</div>

### getTargetCPU() {#a8d4930d9bba5bf85a86c2177b950c10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::TargetMachine::getTargetCPU ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a9ca45577ddb8efe4904398939fae28d1">TargetCPU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ac7c7ab2466ba18c193faea8966362085">llvm::AMDGPUTargetMachine::getGPUName</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a719713d67ba4d30b964d4a4f3228e157">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>.</p>

</div>
</div>

### getTargetFeatureString() {#a81b02eb89292775ff6e6a2ece94f961f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::TargetMachine::getTargetFeatureString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a795cc09ce82b6ef057e5400a5cee7d68">TargetFS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a388dd65231ec660233341f507f02f91d">llvm::AMDGPUTargetMachine::getFeatureString</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a719713d67ba4d30b964d4a4f3228e157">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>.</p>

</div>
</div>

### getTargetIRAnalysis() {#ab0f75813c496f966352b35327085da9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIRAnalysis TargetMachine::getTargetIRAnalysis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetiranalysis">TargetIRAnalysis</a></span> appropriate for the target.</p>


<p>This is used to construct the new pass manager's target IR analysis pass, set up appropriately for this target machine. Even the old pass manager uses this to answer queries about the IR.</p>


<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a89d17091515cc3617c0901a05308f27b">getTargetTransformInfo</a>.</p>

</div>
</div>

### getTargetTransformInfo() {#a89d17091515cc3617c0901a05308f27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo TargetMachine::getTargetTransformInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> for a given function.</p>


<p>The returned <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> is specialized to the subtarget corresponding to <span class="doxyComputerOutput">F</span>.</p>


<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#ab0f75813c496f966352b35327085da9f">getTargetIRAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a732bd4cf41862afa6092c1648c02e256">llvm::SelectionDAGBuilder::shouldKeepJumpConditionsTogether</a>.</p>

</div>
</div>

### getTargetTriple() {#a33fe94054a904130a7c774f78423c8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::TargetMachine::getTargetTriple ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a05856d96e88224279af8b29edfd1c9ad">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a62fefc41d89d22d96ef82c2537da4343">createPPCAsmPrinterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a8d5210bd68a86582390a6fbf1f57e319">llvm::TargetInstrInfo::duplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ab23c37279d90814b87d6c8ab25b43d0b">emitGlobalConstantImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adb745982e84f05a0d48b878d998d47c7">llvm::RISCVTargetLowering::expandIndirectJTBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adfbecc9eaa3da520aafda5f3078baf3f">llvm::X86TargetLowering::expandIndirectJTBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#adbf8027ff0f01d2acccb979b5f79e5ca">llvm::AMDGPUSubtarget::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a1bf32141c5a35cf431382b87f661175d">llvm::TargetLoweringObjectFileXCOFF::Initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#aba8fa9d02ad8b557faaf41b37b714ba4">llvm::AArch64CallLowering::isEligibleForTailCallOptimization</a>, <a href="#ae5d09e961ee51900ce14d985bbc0839b">isLargeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#a724dea051443f75d5024385aa4f117e6">llvm::PPCTargetMachine::isPPC64</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a72542aebd8b9fca8e738edac73af1810">llvm::MipsTargetMachine::MipsTargetMachine</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#a9329650dea81789565d4d4e7019c81eb">llvm::PPCTargetMachine::PPCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a50e2c161ce287abb803123ade461704a">llvm::AArch64TargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="#aa3f0dc829be1fe9aa1c7d5151db1bf21">shouldAssumeDSOLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a88e01d7fa3f418c441946a2200eb12c0">llvm::SITargetLowering::shouldEmitFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a755eb2d2f25e8da3b2d904146e61b1a5">shouldLowerMemFuncForSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a071d371524d9b324ba9c5cc489ee3da6">shouldLowerMemFuncForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab870ac74feb45bb48a75027da41c0784">llvm::SITargetLowering::shouldUseLDSConstAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ab6e0c470f6d0cc116c75811bdf41bb">llvm::SystemZTargetMachine::SystemZTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#aee4969629bf56864f2d3058bcba4506f">llvm::X86TargetMachine::X86TargetMachine</a>.</p>

</div>
</div>

### getTLSModel() {#a07028bb765a646ca5ca5375162a93d7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TLSModel::Model TargetMachine::getTLSModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the TLS model which should be used for the given global variable.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pielevel/#ae01fe422624f3a5afd84d14146f9112ca0b4e3e20dca8947e14cee3d5fe0e4fa8">llvm::PIELevel::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120aa530fb2056fbb72e132893eba6ff4883">llvm::TLSModel::GeneralDynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#af3295ffffcff40d7c95aa9fb4d13256a">llvm::Module::getPIELevel</a>, <a href="#a846a6b6b666a842d3a17f128e1826bc4">getRelocationModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp/#a42137744a6ac05132bc99060fae4a0e3">getSelectedTLSModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a3cae4242c478d473bfa1af350f126545">llvm::TLSModel::InitialExec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a110e377ad85dc311cb9bce1e32bea8aa">llvm::TLSModel::LocalDynamic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120ae13ef3bbe423ce80086f0a684fd25753">llvm::TLSModel::LocalExec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a>, <a href="#a588867fa922c392886b07e0ad42038b4">RM</a> and <a href="#aa3f0dc829be1fe9aa1c7d5151db1bf21">shouldAssumeDSOLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a23bdd93cc79ae6095f38f4bc4f7eec80">isEligibleToFoldADDIForFasterLocalAccesses</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ab44a5ddbc927f9b63731bf050dee8048">llvm::SparcTargetLowering::LowerGlobalTLSAddress</a>.</p>

</div>
</div>

### getUniqueBasicBlockSectionNames() {#a67f5924a8286507885cb8c080e591cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getUniqueBasicBlockSectionNames ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if unique basic block section names must be generated.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getUniqueSectionNames() {#a6c05f5558f52383f362ff9c4cf7de8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getUniqueSectionNames ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### getXCOFFTracebackTable() {#ad1f7d0a68c98e09d9023f4cdbff2dcbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::getXCOFFTracebackTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> traceback table should be emitted, corresponding to -xcoff-traceback-table.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>

</div>
</div>

### isCompatibleDataLayout() {#acae86be92c723d5de55d99eca606c8cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::isCompatibleDataLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; Candidate)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> if compatible with the CodeGen for this target.</p>


<p>The LLVM <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> owns a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> that is used for the target independent optimizations and code generation. This hook provides a target specific check on the validity of this <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>.</p>

</div>
</div>

### isLargeGlobalValue() {#ae5d09e961ee51900ce14d985bbc0839b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetMachine::isLargeGlobalValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="#a8c1d24a5ba7222c0f7ddce3a50a7a048">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a788ede5201dc9b44e419e9fd2fbb38bf">llvm::GlobalValue::getAliaseeObject</a>, <a href="#ae106f6c6362377b3016f0d174227e193">getCodeModel</a>, <a href="#a33fe94054a904130a7c774f78423c8b7">getTargetTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="#a3ed0d9d3435519eeec1fecfa49753077">LargeDataThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### isMachineVerifierClean() {#aac9680f0fdc42257247707862d76be7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::isMachineVerifierClean ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the target is expected to pass all machine verifier checks.</p>


<p>This is a stopgap measure to fix targets one by one. We will remove this at some point and always enable the verifier when EXPENSIVE_CHECKS is enabled.</p>


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### isNoopAddrSpaceCast() {#a321fbc5faf6c190cd1f90c19c3101cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::isNoopAddrSpaceCast (unsigned SrcAS, unsigned DestAS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if a cast between SrcAS and DestAS is a noop.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ae3b212068ff9790a79d583db264f651a">checkAddrSpaceIsValidForLibcall</a>.</p>

</div>
</div>

### isPositionIndependent() {#a0e5ffac7fd84af772a216629f8bd6da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetMachine::isPositionIndependent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="#a846a6b6b666a842d3a17f128e1826bc4">getRelocationModel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#afcf9c9efe452f11d4713cc9657c1c4cd">computeBasePointerSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ace182ca668404b3d23cae8329d941ba4">llvm::MipsFunctionInfo::initGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#ae2e5c3e98e51697955be49b39bb42c02">llvm::MipsTargetLowering::isJumpTableRelative</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a88a3d24891c523c6a8646c4a4ea87502">llvm::TargetLoweringBase::isJumpTableRelative</a>.</p>

</div>
</div>

### parseMachineFunctionInfo() {#ae72cc273e2975b2caf712993f47d0ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::parseMachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &amp; SourceRange)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse out the target's <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> from the YAML reprsentation.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### registerDefaultAliasAnalyses() {#ab7caacf1b6625cc8fce9e8e9f5c95268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetMachine::registerDefaultAliasAnalyses (<a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow the target to register alias analyses with the <a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> for use with the new pass manager.</p>


<p>Only affects the "default" <a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a>.</p>


<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### registerMachineRegisterInfoCallback() {#abbb18773adf0c1b4bfa5686b27f803ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetMachine::registerMachineRegisterInfoCallback (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### registerPassBuilderCallbacks() {#a1fff160f7403fccaa91aa6ac107369a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetMachine::registerPassBuilderCallbacks (<a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow the target to modify the pass pipeline.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### requiresStructuredCFG() {#aa276e49983e93afa359ec83ad71ccadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetMachine::requiresStructuredCFG ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#abf089bfce826d2561637f8a6b388e27d">RequireStructuredCFG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae32dc74389a52cbb83e6a016274142f5">llvm::MachineBasicBlock::canSplitCriticalEdge</a> and <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>.</p>

</div>
</div>

### resetTargetOptions() {#af0a50afebb9bed07d36be2bac4c6f729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetMachine::resetTargetOptions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the target options based on the function's attributes.</p>


<p>setFunctionAttributes should have made the raw attribute value consistent with the command line flag if used.</p>


<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp/#af1766a3b054c04ad3f7f07086ee48036">RESET_OPTION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af3a94bd62230f4b9f99b54976663dfe8">llvm::ARMBaseTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a662d6e7c2aa31e6cac9212319d5349e3">llvm::CSKYTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a0fec1667ac50cd92d5de25da9c53f704">llvm::GCNTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#acc8d7e573d75a9749702efefef9dc9a2">llvm::M68kTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#ae3a3a1690e01cf8d748aae7010f97687">llvm::MipsTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a42f92645ffc7ba5f2dac57ec1caf08a5">llvm::R600TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a9009458436b2d38a2be9636993ab17e2">llvm::SparcTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ae65ab39e3d2d3b91527cb482c735aa">llvm::SystemZTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#ac5c975b4faf36ed756851c7a84d870ea">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#afc11b3df4a2d81fbf25988baf63fc6b3">llvm::X86TargetMachine::getSubtargetImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#afcd734d7f68ecebea11378e93eb4b3be">llvm::XtensaTargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

### setCFIFixup() {#a6448068659187735a2f57ef78d9ebbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setCFIFixup (bool Enable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a263886b11be7dae786aa918f70e909b8">llvm::RISCVTargetMachine::RISCVTargetMachine</a>.</p>

</div>
</div>

### setCodeModel() {#aea3afe0eadb00a51b47d5b96adeceaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setCodeModel (<a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> CM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the code model.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a320899bd91c5ee07e2fa3f2dd7ae9ca1">CMModel</a>.</p>

</div>
</div>

### setFastISel() {#a39135b2379ed114c1fe9035e497b18b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setFastISel (bool Enable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a5f24bce1cade82dd36f855453d0f4781">llvm::SPIRVTargetMachine::SPIRVTargetMachine</a>.</p>

</div>
</div>

### setGlobalISel() {#aaf9d8e59809f5486cd5ecef50e95ea5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setGlobalISel (bool Enable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a5f24bce1cade82dd36f855453d0f4781">llvm::SPIRVTargetMachine::SPIRVTargetMachine</a>.</p>

</div>
</div>

### setGlobalISelAbort() {#a72a03eaf18d396eb46f4c1a41bec628c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setGlobalISelAbort (<a href="/web-llvm/docs/api/namespaces/llvm/#af69c47ced839e86a65b94b0a33ee5c2a">GlobalISelAbortMode</a> Mode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a> and <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>.</p>

</div>
</div>

### setLargeDataThreshold() {#ab8f3dc6c5c58d95e41ff8d2e04f78694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setLargeDataThreshold (uint64_t LDT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a3ed0d9d3435519eeec1fecfa49753077">LargeDataThreshold</a>.</p>

</div>
</div>

### setMachineOutliner() {#a35061955fa2e0fbba033286ae5ac1e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setMachineOutliner (bool Enable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a263886b11be7dae786aa918f70e909b8">llvm::RISCVTargetMachine::RISCVTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#aee4969629bf56864f2d3058bcba4506f">llvm::X86TargetMachine::X86TargetMachine</a>.</p>

</div>
</div>

### setO0WantsFastISel() {#ac018674200ea43bc03522bf1afbcca7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setO0WantsFastISel (bool Enable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="#a9398df1c20ab3f6d740829adfa6e56d9">O0WantsFastISel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a5f24bce1cade82dd36f855453d0f4781">llvm::SPIRVTargetMachine::SPIRVTargetMachine</a>.</p>

</div>
</div>

### setOptLevel() {#a98a5b8058f50fc20fec2e9e7d8a674a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setOptLevel (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> Level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overrides the optimization level.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#afa79b97443f6239f18c08e85a0a4fcfd">OptLevel</a>.</p>

</div>
</div>

### setPGOOption() {#af35446b7e91638289cf6c36a35faef2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setPGOOption (std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &gt; PGOOpt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a7da43f2ecd711e926d8eccdd80b70df9">PGOOption</a>.</p>

</div>
</div>

### setRequiresStructuredCFG() {#aab914199574166419ae7e055ce1f43a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setRequiresStructuredCFG (bool Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#abf089bfce826d2561637f8a6b388e27d">RequireStructuredCFG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#a78a93424a800f37fc3a2162c836c9eee">llvm::NVPTXTargetMachine::NVPTXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a134b54c06f992d6e8cea8ac98f8d2be8">llvm::R600TargetMachine::R600TargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a5f24bce1cade82dd36f855453d0f4781">llvm::SPIRVTargetMachine::SPIRVTargetMachine</a>.</p>

</div>
</div>

### setSupportsDebugEntryValues() {#a044ef65e7e12002d61ddbc98bc7e37ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setSupportsDebugEntryValues (bool Enable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a72542aebd8b9fca8e738edac73af1810">llvm::MipsTargetMachine::MipsTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#aee4969629bf56864f2d3058bcba4506f">llvm::X86TargetMachine::X86TargetMachine</a>.</p>

</div>
</div>

### setSupportsDefaultOutlining() {#a6fadf68fc47b2f0e3a8dd55de3ec93c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setSupportsDefaultOutlining (bool Enable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a263886b11be7dae786aa918f70e909b8">llvm::RISCVTargetMachine::RISCVTargetMachine</a>.</p>

</div>
</div>

### setTargetFeatureString() {#adcf8f29034e2aae38cbee562ddd194ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetMachine::setTargetFeatureString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Reference <a href="#a795cc09ce82b6ef057e5400a5cee7d68">TargetFS</a>.</p>

</div>
</div>

### shouldAssumeDSOLocal() {#aa3f0dc829be1fe9aa1c7d5151db1bf21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetMachine::shouldAssumeDSOLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a846a6b6b666a842d3a17f128e1826bc4">getRelocationModel</a>, <a href="#a33fe94054a904130a7c774f78423c8b7">getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a66501d6d43642a526ab769458d700aa4">llvm::GlobalValue::hasDLLImportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a51af265dc931258cdb8ffb37ee6decee">llvm::GlobalValue::hasExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6b66f492cbea5f4b4f434d7178477116">llvm::GlobalValue::isDeclarationForLinker</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a19db81b6f3d3ab342972dce7756fb077">llvm::GlobalValue::isDSOLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a904b8b68c7e4e888158b03f0eae0e4d5">llvm::GlobalValue::isStrongDefinitionForLinker</a>, <a href="#a588867fa922c392886b07e0ad42038b4">RM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>.</p>


<p>Referenced by <a href="#a07028bb765a646ca5ca5375162a93d7c">getTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae601b00af8d8e80cd833ae31f78a9160">llvm::HexagonTargetLowering::LowerGLOBALADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a27bb49c3656188aff4e75ebc6d4147d5">llvm::SITargetLowering::shouldEmitGOTReloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>.</p>

</div>
</div>

### splitModule() {#a34172b9e43fd9c3df636174685acf800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::splitModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, unsigned NumParts, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; MPart)&gt; ModuleCallback)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Entry point for module splitting.</p>


<p>Targets can implement custom module splitting logic, mainly used by LTO for –lto-partitions.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> if the module was split, <span class="doxyComputerOutput">false</span> otherwise. When <span class="doxyComputerOutput">false</span> is returned, it is assumed that <span class="doxyComputerOutput">ModuleCallback</span> has never been called and <span class="doxyComputerOutput">M</span> has not been modified.</p></dd>
</dl>


<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### targetSchedulesPostRAScheduling() {#a87bf05675e97c30dca57554248f19976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::targetSchedulesPostRAScheduling ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if subtarget inserts the final scheduling pass on its own.</p>


<p>Branch relaxation, which must happen after block placement, can on some targets (e.g. <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a>) expose additional post-RA scheduling opportunities.</p>


<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### unqualifiedInlineAsmVariant() {#a614d70c089e208c5876f8fcceda06214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int llvm::TargetMachine::unqualifiedInlineAsmVariant ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The default variant to use in unqualified <span class="doxyComputerOutput">asm</span> instructions.</p>


<p>If this returns 0, <span class="doxyComputerOutput">asm "$(foo$|bar$)"</span> will evaluate to <span class="doxyComputerOutput">asm "foo"</span>.</p>


<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>.</p>

</div>
</div>

### useEmulatedTLS() {#a650b3b6ac132345d10690adc3e3f418c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetMachine::useEmulatedTLS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this target uses emulated TLS.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ab44a5ddbc927f9b63731bf050dee8048">llvm::SparcTargetLowering::LowerGlobalTLSAddress</a>.</p>

</div>
</div>

### useIPRA() {#ae7dde9cfe1ea0eb1b353ee84061a2f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::useIPRA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the target wants to use interprocedural register allocation by default.</p>


<p>The -enable-ipra flag can be used to override this.</p>


<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>

</div>
</div>

### usesPhysRegsForValues() {#a280c50132f28bb2f82be5f8c32d81406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetMachine::usesPhysRegsForValues ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the target uses physical regs (as nearly all targets do).</p>


<p>False for stack machines such as <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> and other virtual-register machines. If true, all vregs must be allocated before PEI. If false, then callee-save register spilling and scavenging are not needed or used. If false, implicitly defined registers will still be assumed to be physical registers, except that variadic defs will be allocated vregs.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>.</p>

</div>
</div>

### useTLSDESC() {#a3b41be7605fb3c5d5485b6521aa561d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetMachine::useTLSDESC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this target uses TLS Descriptors.</p>

<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>Reference <a href="#ab1fb67187fc37e569cc5171cbebba873">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Options {#ab1fb67187fc37e569cc5171cbebba873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetOptions llvm::TargetMachine::Options</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64betargetmachine/#a900b7768898f693a7b1953330affac35">llvm::AArch64beTargetMachine::AArch64beTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64letargetmachine/#ac62bb19fc05412e738292cde1d3fb2c3">llvm::AArch64leTargetMachine::AArch64leTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a16c22435b21cfe335c972d971e29b0d7">allowApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad51f84320038e868d4472f1b93ea6a36">llvm::AMDGPUTargetLowering::allowApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ada490959f8c0f210cd7843a1ebd04283">llvm::NVPTXTargetLowering::allowFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#aed1455dbc1ee69a6b745c72fdecac52f">llvm::NVPTXTargetLowering::allowUnsafeFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/arctargetmachine/#addfa9d3a2903fcc06cade2b6b6d0b1a1">llvm::ARCTargetMachine::ARCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbetargetmachine/#a4cabb24f403986723ab44d67f52f7268">llvm::ARMBETargetMachine::ARMBETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armletargetmachine/#ae82a61b1e94127c575e157c9a0ee9e6e">llvm::ARMLETargetMachine::ARMLETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#aff8b6cd5f8dba25944e8d80ef4eb246b">llvm::ARMFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetmachine/#a787511152a773b69a7a1a5a3031543de">llvm::AVRTargetMachine::AVRTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetmachine/#ab8863575f43949311ae24b598155dc09">llvm::BPFTargetMachine::BPFTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac83bcada2a1e9fdfeb3a5215fff012da">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#adf86b81af5da74aea6a11c36eadf41be">llvm::AArch64RegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#aa0eb9ad617a055468d105965502662c5">llvm::ARMBaseRegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81efb38c390b38633dbdb3e877a15a84">combineFMinFMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1e500fbed9b5849bfd76724ccf3825">combineFMinNumFMaxNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a40e9166415077d71f840a81b21a1313a">llvm::MipsTargetLowering::createFastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a633e7df96afce72a4e730ecb6e95e6b2">llvm::CSKYTargetMachine::CSKYTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a88484d585ecc86920ebee6396946eae2">llvm::PPCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/directxtargetmachine/#a6481c4d2d43db381d48cc39fa16e57ea">llvm::DirectXTargetMachine::DirectXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a63c498f1fcb62301a44ad58e2dc8e7fc">llvm::PPCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a904fa902f773c900d99c77af2da331c1">foldFPToIntToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a8e592210e9540d3f23611c42ac500170">llvm::GCNTargetMachine::GCNTargetMachine</a>, <a href="#a2fb7b7446aa4f151dbd0bc2ee7420102">getAIXExtendedAltivecABI</a>, <a href="#a49e6d68208c385fa29fe43b305342cfd">getBBSectionsFuncListBuf</a>, <a href="#afab3c5f91842d5dd9f6aaf78a1ff34a9">getBBSectionsType</a>, <a href="#ad88880f638789a2b753b5dc51bbb84eb">getDataSections</a>, <a href="#af77edbddebe48a5b1016c99d6ee0bb58">getFunctionSections</a>, <a href="#a5b6bf1b1f018af4f76b19a45dbc30048">getIgnoreXCOFFVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2fd734bb5606f5c8bd7bd6ef49683e1e">llvm::PPCTargetLowering::getNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#aada6bb4af36a2736480f0c51fced2d58">llvm::ARMSubtarget::getPushPopSplitVariation</a>, <a href="#a49533cf3eaec93375603c3b1e1dd64d4">getSeparateNamedSections</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="#a67f5924a8286507885cb8c080e591cfe">getUniqueBasicBlockSectionNames</a>, <a href="#a6c05f5558f52383f362ff9c4cf7de8ce">getUniqueSectionNames</a>, <a href="#ad1f7d0a68c98e09d9023f4cdbff2dcbe">getXCOFFTracebackTable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a3ca8ff16a3bd8d5f7c682180151eb3fc">llvm::ARCFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a895b02ce6ba256348e2eef839e1ef780">llvm::ARMFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a57e521638750a8eafb3e5b985cad6cb2">llvm::CSKYFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#adae83dd896dd68667b344defbc9c5381">llvm::LoongArchFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a0467fb31b542da4b9672b69ae002cf97">llvm::M68kFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#acc03bc4b3fe668894a31738a4f03269b">llvm::MipsFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a1b2778e918ea09d5b0f6e0d4ec0f3bc5">llvm::MSP430FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a6257e7a03156ea3018b555f0aff4b2">llvm::RISCVFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a9011fd4dec97b74c665033f7a42d485a">llvm::SIFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#abc1f60525acaf9f05557ea0d4bc1d339">llvm::SparcFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a639478d440d115bb94fd83bf9054da98">llvm::SystemZELFFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#aa1d1f569ffb5db8f2cbb0bc8fdf7515c">llvm::VEFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#ada8a1c1bcf75dee1d45143d3b8500d16">llvm::XCoreFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a130ce842392b2b6a8051ccfdf70b3d5a">llvm::XtensaFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#aaba049307055dcc9ea7de0eb29f0d5b3">llvm::HexagonTargetMachine::HexagonTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aab3d65d6e0daa1da2c564a3803f207b2">llvm::AArch64InstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a89fae3db628b477b713990d7a58732ea">isCombineInstrCandidateFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#aba8fa9d02ad8b557faaf41b37b714ba4">llvm::AArch64CallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a1c1ba0852c28df8598b5a0d2f0abb3aa">llvm::AMDGPUCallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ababdb755e930b1b856496616c735a117">isFMAddSubOrFMSubAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a5725394c4ad3c08a6a173b02827a32a3">llvm::ARMFrameLowering::isFPReserved</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a684dc96f8f8c8d2e9473fea07a6f5917">isLegalToCombineMinNumMaxNum</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a9d2e61bef8fbdb714e9f0a739bf49a58">llvm::AArch64TargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a857dba88c2223d0a509b5d390f7144f0">llvm::PPCTargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#adfeafe69289d62b3269dd29ba8e88038">llvm::SITargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a1aabb0d5da92e7ec4f977806b0f8d0ca">llvm::RISCVMachineFunctionInfo::isPushable</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetmachine/#ad4c676bf9a496db85baa599666ac50b8">llvm::LanaiTargetMachine::LanaiTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aa71647a93d5e73c28332b6e52407979c">llvm::AMDGPULegalizerInfo::legalizeFastUnsafeFDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ac0184339c875630ffed0e19b55899b82">llvm::AMDGPULegalizerInfo::legalizeFastUnsafeFDIV64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5552c2fa1505412508e493149af31543">llvm::AMDGPULegalizerInfo::legalizeFExp</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#a04a47a45b26a93d11e3cc1b92dfe1281">llvm::LoongArchTargetMachine::LoongArchTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b4d189fb624411d2c3e6d460da3796f">llvm::AMDGPUTargetLowering::lowerFEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a984d43e3f7d19822c71c5dac6a9dd650">llvm::AMDGPUTargetLowering::LowerFLOGCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#ab461a12892a3c384f080db036b2234a1">llvm::M68kTargetMachine::M68kTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsebtargetmachine/#ac62277e70b988b91c7addccd42334f3b">llvm::MipsebTargetMachine::MipsebTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipseltargetmachine/#aa2901f24bea76973c976cdbad5ac892a">llvm::MipselTargetMachine::MipselTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a72542aebd8b9fca8e738edac73af1810">llvm::MipsTargetMachine::MipsTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetmachine/#a204cc56ded2a0d2743a71edbb2329524">llvm::MSP430TargetMachine::MSP430TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a11b74a0fb5ceb4340d1d7a6f809e0a28">llvm::PPCFrameLowering::needsFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#a78a93424a800f37fc3a2162c836c9eee">llvm::NVPTXTargetMachine::NVPTXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine32/#ae5ce8d34d6195d4f3df89ac611d5e3b1">llvm::NVPTXTargetMachine32::NVPTXTargetMachine32</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine64/#a36ca05d7cdde12b565049da7ab71a837">llvm::NVPTXTargetMachine64::NVPTXTargetMachine64</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#a9329650dea81789565d4d4e7019c81eb">llvm::PPCTargetMachine::PPCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a134b54c06f992d6e8cea8ac98f8d2be8">llvm::R600TargetMachine::R600TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a263886b11be7dae786aa918f70e909b8">llvm::RISCVTargetMachine::RISCVTargetMachine</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a26b78c90211732e17d6b4d5adede3d62">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::runOnMachineFunction</a>, <a href="#a6448068659187735a2f57ef78d9ebbbd">setCFIFixup</a>, <a href="#a39135b2379ed114c1fe9035e497b18b7">setFastISel</a>, <a href="#aaf9d8e59809f5486cd5ecef50e95ea5d">setGlobalISel</a>, <a href="#a72a03eaf18d396eb46f4c1a41bec628c">setGlobalISelAbort</a>, <a href="#a35061955fa2e0fbba033286ae5ac1e56">setMachineOutliner</a>, <a href="#a044ef65e7e12002d61ddbc98bc7e37ea">setSupportsDebugEntryValues</a>, <a href="#a6fadf68fc47b2f0e3a8dd55de3ec93c4">setSupportsDefaultOutlining</a>, <a href="/web-llvm/docs/api/classes/llvm/sparceltargetmachine/#aae3ab3b4d18692f7f87e15adbdcc46dc">llvm::SparcelTargetMachine::SparcelTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a6a12b8b4d104e9370700c6441df0b7aa">llvm::SparcTargetMachine::SparcTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcv8targetmachine/#add42d5efb4485c4e52562027ff4c6751">llvm::SparcV8TargetMachine::SparcV8TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcv9targetmachine/#a51b1965862d7ee12bf2f35b4d011acd3">llvm::SparcV9TargetMachine::SparcV9TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a5f24bce1cade82dd36f855453d0f4781">llvm::SPIRVTargetMachine::SPIRVTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ab6e0c470f6d0cc116c75811bdf41bb">llvm::SystemZTargetMachine::SystemZTargetMachine</a>, <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>, <a href="#a650b3b6ac132345d10690adc3e3f418c">useEmulatedTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/cskysubtarget/#a96135156edd232b1c1a1e5237e033c1d">llvm::CSKYSubtarget::useHardFloatABI</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ae520d99d1f2920afdc21bdd7346ba561">llvm::NVPTXTargetLowering::usePrecSqrtF32</a>, <a href="#a3b41be7605fb3c5d5485b6521aa561d9">useTLSDESC</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetmachine/#a3ac52cbfedf6698e050636a061cfff0c">llvm::VETargetMachine::VETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a39f4b4edb8abb1954310e3b6915afc81">llvm::WebAssemblyTargetMachine::WebAssemblyTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#aee4969629bf56864f2d3058bcba4506f">llvm::X86TargetMachine::X86TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetmachine/#abe8a3c2f858125167eda7aa7a9346ccd">llvm::XCoreTargetMachine::XCoreTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#a64e6168e76349ecff07a940de2e285a5">llvm::XtensaTargetMachine::XtensaTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#a95a957a4ac339769f3090d57a1bb6815">llvm::XtensaTargetMachine::XtensaTargetMachine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AsmInfo {#a05f434744b4ee29d39763ce90aae0156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCAsmInfo&gt; llvm::TargetMachine::AsmInfo</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains target specific asm information.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bpftargetmachine/#ab8863575f43949311ae24b598155dc09">llvm::BPFTargetMachine::BPFTargetMachine</a>, <a href="#afb72c5626afbc815284e2b26bb0663f8">getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### CMModel {#a320899bd91c5ee07e2fa3f2dd7ae9ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeModel::Model llvm::TargetMachine::CMModel = <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">CodeModel::Small</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="#ae106f6c6362377b3016f0d174227e193">getCodeModel</a> and <a href="#aea3afe0eadb00a51b47d5b96adeceaf1">setCodeModel</a>.</p>

</div>
</div>

### DL {#a8c1d24a5ba7222c0f7ddce3a50a7a048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout llvm::TargetMachine::DL</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for the target: keep ABI type size and alignment.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> is created based on the string representation provided during construction. It is kept here only to avoid reparsing the string but should not really be used during compilation, because it has an internal cache that is context specific.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#a34825337fd4c67c855cfc5d6d3a87788">createDataLayout</a>, <a href="#a1b3b25e081b3cb943e397b5105d74bea">getAllocaPointerSize</a>, <a href="#a6ec7f7ca20aecbaf5bdd98c9cf866298">getPointerSize</a>, <a href="#a5a411a3e39c13b46c05558240901cd3c">getPointerSizeInBits</a>, <a href="#ad064e269d4fe74038cd6e04b6bc49a06">getProgramPointerSize</a>, <a href="#acae86be92c723d5de55d99eca606c8cc">isCompatibleDataLayout</a>, <a href="#ae5d09e961ee51900ce14d985bbc0839b">isLargeGlobalValue</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### LargeDataThreshold {#a3ed0d9d3435519eeec1fecfa49753077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TargetMachine::LargeDataThreshold = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#ae5d09e961ee51900ce14d985bbc0839b">isLargeGlobalValue</a> and <a href="#ab8f3dc6c5c58d95e41ff8d2e04f78694">setLargeDataThreshold</a>.</p>

</div>
</div>

### MII {#a6f6199d597301a76dc85a4c244549fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCInstrInfo&gt; llvm::TargetMachine::MII</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="#a92155c8483cac23d6f8fed069521ba7c">getMCInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### MRI {#af7371bb744de95d18d5b583bedf49056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCRegisterInfo&gt; llvm::TargetMachine::MRI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="#ae35986fd6211188deafdb8a3902cee03">getMCRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### O0WantsFastISel {#a9398df1c20ab3f6d740829adfa6e56d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetMachine::O0WantsFastISel</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#abe330a3972c5bf72e4093fd113c6ebac">getO0WantsFastISel</a>, <a href="#ac018674200ea43bc03522bf1afbcca7a">setO0WantsFastISel</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### OptLevel {#afa79b97443f6239f18c08e85a0a4fcfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::TargetMachine::OptLevel = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="#a030edbec5a50c887caf3ec95c7c50c44">getOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetmachine/#ad4c676bf9a496db85baa599666ac50b8">llvm::LanaiTargetMachine::LanaiTargetMachine</a> and <a href="#a98a5b8058f50fc20fec2e9e7d8a674a6">setOptLevel</a>.</p>

</div>
</div>

### PGOOption {#a7da43f2ecd711e926d8eccdd80b70df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PGOOptions&gt; llvm::TargetMachine::PGOOption</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#a3a456c76bb8d844400ac4baffbd090e6">getPGOOption</a> and <a href="#af35446b7e91638289cf6c36a35faef2d">setPGOOption</a>.</p>

</div>
</div>

### RequireStructuredCFG {#abf089bfce826d2561637f8a6b388e27d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetMachine::RequireStructuredCFG</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#aa276e49983e93afa359ec83ad71ccadc">requiresStructuredCFG</a>, <a href="#aab914199574166419ae7e055ce1f43a0">setRequiresStructuredCFG</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### RM {#a588867fa922c392886b07e0ad42038b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model llvm::TargetMachine::RM = <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">Reloc::Static</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64betargetmachine/#a900b7768898f693a7b1953330affac35">llvm::AArch64beTargetMachine::AArch64beTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64letargetmachine/#ac62bb19fc05412e738292cde1d3fb2c3">llvm::AArch64leTargetMachine::AArch64leTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/arctargetmachine/#addfa9d3a2903fcc06cade2b6b6d0b1a1">llvm::ARCTargetMachine::ARCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbetargetmachine/#a4cabb24f403986723ab44d67f52f7268">llvm::ARMBETargetMachine::ARMBETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armletargetmachine/#ae82a61b1e94127c575e157c9a0ee9e6e">llvm::ARMLETargetMachine::ARMLETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetmachine/#a787511152a773b69a7a1a5a3031543de">llvm::AVRTargetMachine::AVRTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetmachine/#ab8863575f43949311ae24b598155dc09">llvm::BPFTargetMachine::BPFTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a633e7df96afce72a4e730ecb6e95e6b2">llvm::CSKYTargetMachine::CSKYTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/directxtargetmachine/#a6481c4d2d43db381d48cc39fa16e57ea">llvm::DirectXTargetMachine::DirectXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a8e592210e9540d3f23611c42ac500170">llvm::GCNTargetMachine::GCNTargetMachine</a>, <a href="#a846a6b6b666a842d3a17f128e1826bc4">getRelocationModel</a>, <a href="#a07028bb765a646ca5ca5375162a93d7c">getTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#aaba049307055dcc9ea7de0eb29f0d5b3">llvm::HexagonTargetMachine::HexagonTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetmachine/#ad4c676bf9a496db85baa599666ac50b8">llvm::LanaiTargetMachine::LanaiTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#a04a47a45b26a93d11e3cc1b92dfe1281">llvm::LoongArchTargetMachine::LoongArchTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#ab461a12892a3c384f080db036b2234a1">llvm::M68kTargetMachine::M68kTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsebtargetmachine/#ac62277e70b988b91c7addccd42334f3b">llvm::MipsebTargetMachine::MipsebTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipseltargetmachine/#aa2901f24bea76973c976cdbad5ac892a">llvm::MipselTargetMachine::MipselTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a72542aebd8b9fca8e738edac73af1810">llvm::MipsTargetMachine::MipsTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetmachine/#a204cc56ded2a0d2743a71edbb2329524">llvm::MSP430TargetMachine::MSP430TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#a78a93424a800f37fc3a2162c836c9eee">llvm::NVPTXTargetMachine::NVPTXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine32/#ae5ce8d34d6195d4f3df89ac611d5e3b1">llvm::NVPTXTargetMachine32::NVPTXTargetMachine32</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine64/#a36ca05d7cdde12b565049da7ab71a837">llvm::NVPTXTargetMachine64::NVPTXTargetMachine64</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#a9329650dea81789565d4d4e7019c81eb">llvm::PPCTargetMachine::PPCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a134b54c06f992d6e8cea8ac98f8d2be8">llvm::R600TargetMachine::R600TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a263886b11be7dae786aa918f70e909b8">llvm::RISCVTargetMachine::RISCVTargetMachine</a>, <a href="#aa3f0dc829be1fe9aa1c7d5151db1bf21">shouldAssumeDSOLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/sparceltargetmachine/#aae3ab3b4d18692f7f87e15adbdcc46dc">llvm::SparcelTargetMachine::SparcelTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a6a12b8b4d104e9370700c6441df0b7aa">llvm::SparcTargetMachine::SparcTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcv8targetmachine/#add42d5efb4485c4e52562027ff4c6751">llvm::SparcV8TargetMachine::SparcV8TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcv9targetmachine/#a51b1965862d7ee12bf2f35b4d011acd3">llvm::SparcV9TargetMachine::SparcV9TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a5f24bce1cade82dd36f855453d0f4781">llvm::SPIRVTargetMachine::SPIRVTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ab6e0c470f6d0cc116c75811bdf41bb">llvm::SystemZTargetMachine::SystemZTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetmachine/#a3ac52cbfedf6698e050636a061cfff0c">llvm::VETargetMachine::VETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a39f4b4edb8abb1954310e3b6915afc81">llvm::WebAssemblyTargetMachine::WebAssemblyTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#aee4969629bf56864f2d3058bcba4506f">llvm::X86TargetMachine::X86TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetmachine/#abe8a3c2f858125167eda7aa7a9346ccd">llvm::XCoreTargetMachine::XCoreTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#a64e6168e76349ecff07a940de2e285a5">llvm::XtensaTargetMachine::XtensaTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#a95a957a4ac339769f3090d57a1bb6815">llvm::XtensaTargetMachine::XtensaTargetMachine</a>.</p>

</div>
</div>

### STI {#aaebd1c0e5f028848cc0e548bf015aaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCSubtargetInfo&gt; llvm::TargetMachine::STI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a42278f37d87aa2a371a59bd9b9daf784">llvm::AArch64TargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/arctargetmachine/#a8400d3d8561c14ba2977aa576cdd5ffa">llvm::ARCTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a8d4778b4a0caf7a3bc7f0f4954e11128">llvm::ARMBaseTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetmachine/#ab1f583a3705f9fc96d9849dd280ff910">llvm::AVRTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#ad7ec05321c40a7f0232063a49cd2b63c">llvm::CSKYTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#ae59b54cd21fc309e4ee5c08d209d011b">llvm::GCNTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#a16b2d6ee02b272b8d74fcc7184b57e68">llvm::HexagonTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetmachine/#aeed668eaf2802564c1db3e97bf3bba21">llvm::LanaiTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#aeb8ae06df7e8c1fc79e18becbce7ddb1">llvm::LoongArchTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#a837324ab239ad39c0631e31c43c36295">llvm::M68kTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a6c070c38f74d2dadf478e2688213aa29">llvm::MipsTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetmachine/#a609559c827653fea39c974cf328f0a35">llvm::MSP430TargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#adcbc93db96521a2f56e83faffb5a0ebc">llvm::NVPTXTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#af87d28dea3b95a6cf57467bdcb02ff87">llvm::PPCTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#aed8dabc11d30caf0f8e0aa8804cbde62">llvm::R600TargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a98eb1677d127d88cfee4aa4c2cef9292">llvm::RISCVTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a8322af65e919b7461e8be9600e07730d">llvm::SparcTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#aa351c443febfc17e15f98efe5b5fa5b2">llvm::SystemZTargetMachine::createMachineFunctionInfo</a>, <a href="#a33f0027ccb45dd6c9aab3966c13b02d3">createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetmachine/#a83f6cd0d668ce3942fb30d44de5f8a01">llvm::VETargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a82e19c7266681b3283fe1ce9ec23e180">llvm::WebAssemblyTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#a07989934f4f0b4a3dba82be453bd6fe9">llvm::X86TargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetmachine/#a447fbaf356370dcf82513fec7cbf36e0">llvm::XCoreTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#a530384e09f9622d262d7e3d877419237">llvm::XtensaTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="#a3f850d2654c88a73a7d6b1701ae5f778">getMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### TargetCPU {#a9ca45577ddb8efe4904398939fae28d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::TargetMachine::TargetCPU</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af3a94bd62230f4b9f99b54976663dfe8">llvm::ARMBaseTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a662d6e7c2aa31e6cac9212319d5349e3">llvm::CSKYTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#acc8d7e573d75a9749702efefef9dc9a2">llvm::M68kTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#ae3a3a1690e01cf8d748aae7010f97687">llvm::MipsTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a9009458436b2d38a2be9636993ab17e2">llvm::SparcTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ae65ab39e3d2d3b91527cb482c735aa">llvm::SystemZTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#ac5c975b4faf36ed756851c7a84d870ea">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#afc11b3df4a2d81fbf25988baf63fc6b3">llvm::X86TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#afcd734d7f68ecebea11378e93eb4b3be">llvm::XtensaTargetMachine::getSubtargetImpl</a>, <a href="#a8d4930d9bba5bf85a86c2177b950c10f">getTargetCPU</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### TargetFS {#a795cc09ce82b6ef057e5400a5cee7d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::TargetMachine::TargetFS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af3a94bd62230f4b9f99b54976663dfe8">llvm::ARMBaseTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a662d6e7c2aa31e6cac9212319d5349e3">llvm::CSKYTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#acc8d7e573d75a9749702efefef9dc9a2">llvm::M68kTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#ae3a3a1690e01cf8d748aae7010f97687">llvm::MipsTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a9009458436b2d38a2be9636993ab17e2">llvm::SparcTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ae65ab39e3d2d3b91527cb482c735aa">llvm::SystemZTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#ac5c975b4faf36ed756851c7a84d870ea">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#afc11b3df4a2d81fbf25988baf63fc6b3">llvm::X86TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#afcd734d7f68ecebea11378e93eb4b3be">llvm::XtensaTargetMachine::getSubtargetImpl</a>, <a href="#a81b02eb89292775ff6e6a2ece94f961f">getTargetFeatureString</a>, <a href="#adcf8f29034e2aae38cbee562ddd194ca">setTargetFeatureString</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### TargetTriple {#a05856d96e88224279af8b29edfd1c9ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::TargetMachine::TargetTriple</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> string, CPU name, and target feature strings the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> instance is created with.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af3a94bd62230f4b9f99b54976663dfe8">llvm::ARMBaseTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a662d6e7c2aa31e6cac9212319d5349e3">llvm::CSKYTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a0fec1667ac50cd92d5de25da9c53f704">llvm::GCNTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#acc8d7e573d75a9749702efefef9dc9a2">llvm::M68kTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#ae3a3a1690e01cf8d748aae7010f97687">llvm::MipsTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a42f92645ffc7ba5f2dac57ec1caf08a5">llvm::R600TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ae65ab39e3d2d3b91527cb482c735aa">llvm::SystemZTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a4e77be6f302bb2cc258a5f5ee0a8fd44">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#afc11b3df4a2d81fbf25988baf63fc6b3">llvm::X86TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#afcd734d7f68ecebea11378e93eb4b3be">llvm::XtensaTargetMachine::getSubtargetImpl</a>, <a href="#a33fe94054a904130a7c774f78423c8b7">getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a30cb863799efd80f6d23e2ac3612cf2b">llvm::ARMBaseTargetMachine::isTargetHardFloat</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

### TheTarget {#adde45f08eafa48f29b1b6d9f98a38814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target&amp; llvm::TargetMachine::TheTarget</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> that this machine was created for.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="#adce0da689ac32105fc6b050de94868bf">getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a> and <a href="#af0be9a5447cbeb928c2e3156cc071017">TargetMachine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### parseBinutilsVersion() {#aad5195630dbe90240748e648ff267d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int, int &gt; TargetMachine::parseBinutilsVersion (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Version)</td>
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



<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### DefaultSjLjDataSize {#a86a9baa3e95a359eb7d89b671c19be78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetMachine::DefaultSjLjDataSize = 32</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The integer bit size to use for SjLj based exception handling.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#a046c6262fc6fc6743bf539c87761083f">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::doInitialization</a> and <a href="#a53ff5f9c66b8fc83ad263fc044a4d6bb">getSjLjDataSize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">TargetMachine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp">TargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
