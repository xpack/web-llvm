---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/orc-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Orc.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">llvm-c/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/targetmachine-h">llvm-c/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmjitsymbolflags">LLVMJITSymbolFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the linkage flags for a symbol definition. <a href="/web-llvm/docs/api/structs/llvmjitsymbolflags/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmjitevaluatedsymbol">LLVMJITEvaluatedSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an evaluated symbol address and flags. <a href="/web-llvm/docs/api/structs/llvmjitevaluatedsymbol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolflagsmappair">LLVMOrcCSymbolFlagsMapPair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a pair of a symbol name and <a href="/web-llvm/docs/api/structs/llvmjitsymbolflags">LLVMJITSymbolFlags</a>. <a href="/web-llvm/docs/api/structs/llvmorccsymbolflagsmappair/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolmappair">LLVMOrcCSymbolMapPair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a pair of a symbol name and an evaluated symbol. <a href="/web-llvm/docs/api/structs/llvmorccsymbolmappair/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolaliasmapentry">LLVMOrcCSymbolAliasMapEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a SymbolAliasMapEntry. <a href="/web-llvm/docs/api/structs/llvmorccsymbolaliasmapentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolaliasmappair">LLVMOrcCSymbolAliasMapPair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a pair of a symbol name and SymbolAliasMapEntry. <a href="/web-llvm/docs/api/structs/llvmorccsymbolaliasmappair/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolslist">LLVMOrcCSymbolsList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a list of <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">LLVMOrcSymbolStringPoolEntryRef</a> and the associated length. <a href="/web-llvm/docs/api/structs/llvmorccsymbolslist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccdependencemappair">LLVMOrcCDependenceMapPair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a pair of a JITDylib and <a href="/web-llvm/docs/api/structs/llvmorccsymbolslist">LLVMOrcCSymbolsList</a>. <a href="/web-llvm/docs/api/structs/llvmorccdependencemappair/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymboldependencegroup">LLVMOrcCSymbolDependenceGroup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of symbols that share dependencies. <a href="/web-llvm/docs/api/structs/llvmorccsymboldependencegroup/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccjitdylibsearchorderelement">LLVMOrcCJITDylibSearchOrderElement</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An element type for a JITDylib search order. <a href="/web-llvm/docs/api/structs/llvmorccjitdylibsearchorderelement/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorcclookupsetelement">LLVMOrcCLookupSetElement</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An element type for a symbol lookup set. <a href="/web-llvm/docs/api/structs/llvmorcclookupsetelement/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint64_t <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga0090ecb3247c07ddd95c73af66353602">LLVMOrcJITTargetAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an address in the executor process. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga0090ecb3247c07ddd95c73af66353602">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint64_t <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga97e95b1f18576f4c1cef9d33b11c7fe3">LLVMOrcExecutorAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an address in the executor process. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga97e95b1f18576f4c1cef9d33b11c7fe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint8_t <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga182cc91c7fd0535ded1858201eb981ea">LLVMJITSymbolTargetFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents target specific flags for a symbol definition. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga182cc91c7fd0535ded1858201eb981ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueExecutionSession * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga653c8620112eddd7c75085a0b586c97d">LLVMOrcExecutionSessionRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::ExecutionSession instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga653c8620112eddd7c75085a0b586c97d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga553a82673fe3ac4a56ac98f85ea8615f">LLVMOrcErrorReporterFunction</a>)(void *Ctx, LLVMErrorRef Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Error reporter function. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga553a82673fe3ac4a56ac98f85ea8615f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueSymbolStringPool * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga864a8a98d4eb3de4d9ade03a9cab4a7e">LLVMOrcSymbolStringPoolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::SymbolStringPool. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga864a8a98d4eb3de4d9ade03a9cab4a7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueSymbolStringPoolEntry * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">LLVMOrcSymbolStringPoolEntryRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::SymbolStringPool table entry. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolflagsmappair">LLVMOrcCSymbolFlagsMapPair</a> * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga2f609f9078a3e33634f97ce24bb2f0d1">LLVMOrcCSymbolFlagsMapPairs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a list of (SymbolStringPtr, JITSymbolFlags) pairs that can be used to construct a SymbolFlagsMap. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga2f609f9078a3e33634f97ce24bb2f0d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolmappair">LLVMOrcCSymbolMapPair</a> * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga42dbd0f3d83438ca4d108439f0da6185">LLVMOrcCSymbolMapPairs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a list of (SymbolStringPtr, JITEvaluatedSymbol) pairs that can be used to construct a SymbolMap. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga42dbd0f3d83438ca4d108439f0da6185">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolaliasmappair">LLVMOrcCSymbolAliasMapPair</a> * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga42ba12769841f4516304047ecccee53f">LLVMOrcCSymbolAliasMapPairs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a list of (SymbolStringPtr, (SymbolStringPtr, JITSymbolFlags)) pairs that can be used to construct a SymbolFlagsMap. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga42ba12769841f4516304047ecccee53f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueJITDylib * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::JITDylib instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccdependencemappair">LLVMOrcCDependenceMapPair</a> * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8e7a4413500f2d0800e67f98aea4370f">LLVMOrcCDependenceMapPairs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a list of (JITDylibRef, (LLVMOrcSymbolStringPoolEntryRef*, size_t)) pairs that can be used to construct a SymbolDependenceMap. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8e7a4413500f2d0800e67f98aea4370f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccjitdylibsearchorderelement">LLVMOrcCJITDylibSearchOrderElement</a> * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga84cf05880074fcb51f89f1cee2fd21c7">LLVMOrcCJITDylibSearchOrder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A JITDylib search order. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga84cf05880074fcb51f89f1cee2fd21c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorcclookupsetelement">LLVMOrcCLookupSetElement</a> * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa0ccb40b10b4c48b05cf742e2e5efe8f">LLVMOrcCLookupSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of symbols to look up / generate. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa0ccb40b10b4c48b05cf742e2e5efe8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueMaterializationUnit * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf17d82579d868fbdda47a32ad1cc08b4">LLVMOrcMaterializationUnitRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to a uniquely owned orc::MaterializationUnit instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf17d82579d868fbdda47a32ad1cc08b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueMaterializationResponsibility * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga5b61102812117fe16978261f6d635e6c">LLVMOrcMaterializationResponsibilityRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to a uniquely owned orc::MaterializationResponsibility instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga5b61102812117fe16978261f6d635e6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gacd70f412e613614839766293b19a1bc5">LLVMOrcMaterializationUnitMaterializeFunction</a>)(void *Ctx, LLVMOrcMaterializationResponsibilityRef MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A MaterializationUnit materialize callback. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gacd70f412e613614839766293b19a1bc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac5ff0262f17e21b218425ea47651fdb4">LLVMOrcMaterializationUnitDiscardFunction</a>)(void *Ctx, LLVMOrcJITDylibRef JD, LLVMOrcSymbolStringPoolEntryRef Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A MaterializationUnit discard callback. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac5ff0262f17e21b218425ea47651fdb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga864c46b3900d86a78ad328d9f5a11ff9">LLVMOrcMaterializationUnitDestroyFunction</a>)(void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A MaterializationUnit destruction callback. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga864c46b3900d86a78ad328d9f5a11ff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueResourceTracker * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga89e1aa5a29b792a5bfa7336ceb3dc9aa">LLVMOrcResourceTrackerRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::ResourceTracker instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga89e1aa5a29b792a5bfa7336ceb3dc9aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueDefinitionGenerator * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaaf57966a4ec602e970c2875a81b90c21">LLVMOrcDefinitionGeneratorRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::DefinitionGenerator. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaaf57966a4ec602e970c2875a81b90c21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueLookupState * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae1baa3cd8ebe2bafcd4e202f3d9dd416">LLVMOrcLookupStateRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An opaque lookup state object. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae1baa3cd8ebe2bafcd4e202f3d9dd416">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a>(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7d174ec56b7cf3fb68e21efdc7453f99">LLVMOrcCAPIDefinitionGeneratorTryToGenerateFunction</a>)(LLVMOrcDefinitionGeneratorRef GeneratorObj, void *Ctx, LLVMOrcLookupStateRef *LookupState, LLVMOrcLookupKind Kind, LLVMOrcJITDylibRef JD, LLVMOrcJITDylibLookupFlags JDLookupFlags, LLVMOrcCLookupSet LookupSet, size_t LookupSetSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A custom generator function. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7d174ec56b7cf3fb68e21efdc7453f99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga63d2bfad712b6c4d803fbf3b0fac6de9">LLVMOrcDisposeCAPIDefinitionGeneratorFunction</a>)(void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disposer for a custom generator. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga63d2bfad712b6c4d803fbf3b0fac6de9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaabac852e55d273a02b1d5eb6ec425d75">LLVMOrcSymbolPredicate</a>)(void *Ctx, LLVMOrcSymbolStringPoolEntryRef Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> function for SymbolStringPoolEntries. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaabac852e55d273a02b1d5eb6ec425d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueThreadSafeContext * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf6c9e2e2f52a13c97b3b6603df2f34df">LLVMOrcThreadSafeContextRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::ThreadSafeContext instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf6c9e2e2f52a13c97b3b6603df2f34df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueThreadSafeModule * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga648d8baae98e849c320c2cf7ec7e548e">LLVMOrcThreadSafeModuleRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::ThreadSafeModule instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga648d8baae98e849c320c2cf7ec7e548e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a>(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga05077b2112b1465de0708fd362a48dac">LLVMOrcGenericIRModuleOperationFunction</a>)(void *Ctx, LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function for inspecting/mutating IR modules, suitable for use with LLVMOrcThreadSafeModuleWithModuleDo. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga05077b2112b1465de0708fd362a48dac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueJITTargetMachineBuilder * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga46ed788f31d61b98c26e7db8043cfc7d">LLVMOrcJITTargetMachineBuilderRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::JITTargetMachineBuilder instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga46ed788f31d61b98c26e7db8043cfc7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueObjectLayer * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::ObjectLayer instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueObjectLinkingLayer * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga41a76ac34fe87b02cb50937397b07b4f">LLVMOrcObjectLinkingLayerRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::ObjectLinkingLayer instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga41a76ac34fe87b02cb50937397b07b4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueIRTransformLayer * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae01c36dccf1a785726fa3cd9e4baf54c">LLVMOrcIRTransformLayerRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::IRTransformLayer instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae01c36dccf1a785726fa3cd9e4baf54c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a>(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga85c7b1a167dc09e503e4c7e1db85229b">LLVMOrcIRTransformLayerTransformFunction</a>)(void *Ctx, LLVMOrcThreadSafeModuleRef *ModInOut, LLVMOrcMaterializationResponsibilityRef MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function for applying transformations as part of an transform layer. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga85c7b1a167dc09e503e4c7e1db85229b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueObjectTransformLayer * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga23625da1e5775d1b063319ee1e7ca83b">LLVMOrcObjectTransformLayerRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::ObjectTransformLayer instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga23625da1e5775d1b063319ee1e7ca83b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a>(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga2d2285585c4c7a9ef179c449e5ff482c">LLVMOrcObjectTransformLayerTransformFunction</a>)(void *Ctx, LLVMMemoryBufferRef *ObjInOut)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function for applying transformations to an object file buffer. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga2d2285585c4c7a9ef179c449e5ff482c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueIndirectStubsManager * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga6c826d2b477de0b97c2943f852f3f4b5">LLVMOrcIndirectStubsManagerRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::IndirectStubsManager instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga6c826d2b477de0b97c2943f852f3f4b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueLazyCallThroughManager * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab96f555259037db21970e83a941b42e8">LLVMOrcLazyCallThroughManagerRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::LazyCallThroughManager instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab96f555259037db21970e83a941b42e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueDumpObjects * <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gadae2662d8f533a63bf4ca3242868c743">LLVMOrcDumpObjectsRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::DumpObjects object. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gadae2662d8f533a63bf4ca3242868c743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga6ef408f24a1947343fb304e694d5388c">LLVMOrcExecutionSessionLookupHandleResultFunction</a>)(LLVMErrorRef Err, LLVMOrcCSymbolMapPairs Result, size_t NumPairs, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for ExecutionSession lookups. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga6ef408f24a1947343fb304e694d5388c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMJITSymbolGenericFlags { <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9f61ce88060abadec7f6f6f0f9b457c4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents generic linkage flags for a symbol definition. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9f61ce88060abadec7f6f6f0f9b457c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMOrcLookupKind { <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1077051dfe1f446fda4004011f513e2f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup kind. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1077051dfe1f446fda4004011f513e2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMOrcJITDylibLookupFlags { <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafb8e107655fbfbaa3e0a917891d96d7d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>JITDylib lookup flags. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafb8e107655fbfbaa3e0a917891d96d7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMOrcSymbolLookupFlags { <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gabd046a5177c36cda183e285788ed6ad6">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol lookup flags for lookup sets. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gabd046a5177c36cda183e285788ed6ad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8a80c4cc975011bd82f1ecca88875308">LLVMOrcExecutionSessionSetErrorReporter</a> (LLVMOrcExecutionSessionRef ES, LLVMOrcErrorReporterFunction ReportError, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attach a custom error reporter function to the ExecutionSession. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8a80c4cc975011bd82f1ecca88875308">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga864a8a98d4eb3de4d9ade03a9cab4a7e">LLVMOrcSymbolStringPoolRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga0617f4efcfa8013dcb60dca8147c040f">LLVMOrcExecutionSessionGetSymbolStringPool</a> (LLVMOrcExecutionSessionRef ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the SymbolStringPool for an ExecutionSession. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga0617f4efcfa8013dcb60dca8147c040f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga06e01f9b3d4498a56bc8d95be706771d">LLVMOrcSymbolStringPoolClearDeadEntries</a> (LLVMOrcSymbolStringPoolRef SSP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all unreferenced symbol string pool entries. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga06e01f9b3d4498a56bc8d95be706771d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">LLVMOrcSymbolStringPoolEntryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gabe10f423ce0da67ab09709135e441758">LLVMOrcExecutionSessionIntern</a> (LLVMOrcExecutionSessionRef ES, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intern a string in the ExecutionSession's SymbolStringPool and return a reference to it. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gabe10f423ce0da67ab09709135e441758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4af207d5a28d38c765a7f33d658df2a5">LLVMOrcExecutionSessionLookup</a> (LLVMOrcExecutionSessionRef ES, LLVMOrcLookupKind K, LLVMOrcCJITDylibSearchOrder SearchOrder, size_t SearchOrderSize, LLVMOrcCLookupSet Symbols, size_t SymbolsSize, LLVMOrcExecutionSessionLookupHandleResultFunction HandleResult, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up symbols in an execution session. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4af207d5a28d38c765a7f33d658df2a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8ba4d7f6c0ab3832570202586679dd54">LLVMOrcRetainSymbolStringPoolEntry</a> (LLVMOrcSymbolStringPoolEntryRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increments the ref-count for a SymbolStringPool entry. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8ba4d7f6c0ab3832570202586679dd54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaedd28421e5f7f097a787fc8f275f5145">LLVMOrcReleaseSymbolStringPoolEntry</a> (LLVMOrcSymbolStringPoolEntryRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduces the ref-count for of a SymbolStringPool entry. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaedd28421e5f7f097a787fc8f275f5145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa33d0b4d7dde29c11825f2f6e93b42af">LLVMOrcSymbolStringPoolEntryStr</a> (LLVMOrcSymbolStringPoolEntryRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the c-string for the given symbol. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa33d0b4d7dde29c11825f2f6e93b42af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7e655f2ad033c0f73598434d94db02d3">LLVMOrcReleaseResourceTracker</a> (LLVMOrcResourceTrackerRef RT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduces the ref-count of a ResourceTracker. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7e655f2ad033c0f73598434d94db02d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafec934cefd3892257d5f677605c28835">LLVMOrcResourceTrackerTransferTo</a> (LLVMOrcResourceTrackerRef SrcRT, LLVMOrcResourceTrackerRef DstRT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfers tracking of all resources associated with resource tracker SrcRT to resource tracker DstRT. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafec934cefd3892257d5f677605c28835">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga32e62df5dab033d0866ab619c1352a49">LLVMOrcResourceTrackerRemove</a> (LLVMOrcResourceTrackerRef RT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all resources associated with the given tracker. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga32e62df5dab033d0866ab619c1352a49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4fd0ab526b5f3f612a0bbe6deaafdcc3">LLVMOrcDisposeDefinitionGenerator</a> (LLVMOrcDefinitionGeneratorRef DG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a JITDylib::DefinitionGenerator. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4fd0ab526b5f3f612a0bbe6deaafdcc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1b955b866c3a9134a3085f19e7708d22">LLVMOrcDisposeMaterializationUnit</a> (LLVMOrcMaterializationUnitRef MU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a MaterializationUnit. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1b955b866c3a9134a3085f19e7708d22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf17d82579d868fbdda47a32ad1cc08b4">LLVMOrcMaterializationUnitRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga22d7fb042682841596db76f6513401cb">LLVMOrcCreateCustomMaterializationUnit</a> (const char *Name, void *Ctx, LLVMOrcCSymbolFlagsMapPairs Syms, size_t NumSyms, LLVMOrcSymbolStringPoolEntryRef InitSym, LLVMOrcMaterializationUnitMaterializeFunction Materialize, LLVMOrcMaterializationUnitDiscardFunction Discard, LLVMOrcMaterializationUnitDestroyFunction Destroy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a custom MaterializationUnit. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga22d7fb042682841596db76f6513401cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf17d82579d868fbdda47a32ad1cc08b4">LLVMOrcMaterializationUnitRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga2fa4d5572b2c93896a2999f5b5e3ca36">LLVMOrcAbsoluteSymbols</a> (LLVMOrcCSymbolMapPairs Syms, size_t NumPairs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a MaterializationUnit to define the given symbols as pointing to the corresponding raw addresses. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga2fa4d5572b2c93896a2999f5b5e3ca36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf17d82579d868fbdda47a32ad1cc08b4">LLVMOrcMaterializationUnitRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaff2e3e277287f32072f5d857ee39941d">LLVMOrcLazyReexports</a> (LLVMOrcLazyCallThroughManagerRef LCTM, LLVMOrcIndirectStubsManagerRef ISM, LLVMOrcJITDylibRef SourceRef, LLVMOrcCSymbolAliasMapPairs CallableAliases, size_t NumPairs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a MaterializationUnit to define lazy re-expots. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaff2e3e277287f32072f5d857ee39941d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga04a286a23f6983abf4ba8676e6e948f5">LLVMOrcDisposeMaterializationResponsibility</a> (LLVMOrcMaterializationResponsibilityRef MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disposes of the passed MaterializationResponsibility object. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga04a286a23f6983abf4ba8676e6e948f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga12f595f9f244d9141a259fe3597d9c38">LLVMOrcMaterializationResponsibilityGetTargetDylib</a> (LLVMOrcMaterializationResponsibilityRef MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target JITDylib that these symbols are being materialized into. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga12f595f9f244d9141a259fe3597d9c38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga653c8620112eddd7c75085a0b586c97d">LLVMOrcExecutionSessionRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga243817689de0af47567128bd2b986349">LLVMOrcMaterializationResponsibilityGetExecutionSession</a> (LLVMOrcMaterializationResponsibilityRef MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ExecutionSession for this MaterializationResponsibility. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga243817689de0af47567128bd2b986349">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga2f609f9078a3e33634f97ce24bb2f0d1">LLVMOrcCSymbolFlagsMapPairs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga17349a4a145c7bf1c7891e7057822fa8">LLVMOrcMaterializationResponsibilityGetSymbols</a> (LLVMOrcMaterializationResponsibilityRef MR, size_t *NumPairs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the symbol flags map for this responsibility instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga17349a4a145c7bf1c7891e7057822fa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga10f4adbd85399a80b5c78090ebd60750">LLVMOrcDisposeCSymbolFlagsMap</a> (LLVMOrcCSymbolFlagsMapPairs Pairs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disposes of the passed LLVMOrcCSymbolFlagsMap. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga10f4adbd85399a80b5c78090ebd60750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">LLVMOrcSymbolStringPoolEntryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga675c5e5d67c4a2c624a575bf8964720d">LLVMOrcMaterializationResponsibilityGetInitializerSymbol</a> (LLVMOrcMaterializationResponsibilityRef MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the initialization pseudo-symbol, if any. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga675c5e5d67c4a2c624a575bf8964720d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">LLVMOrcSymbolStringPoolEntryRef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga120f9b694ced7208de2a0c222f04ce3a">LLVMOrcMaterializationResponsibilityGetRequestedSymbols</a> (LLVMOrcMaterializationResponsibilityRef MR, size_t *NumSymbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the names of any symbols covered by this MaterializationResponsibility object that have queries pending. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga120f9b694ced7208de2a0c222f04ce3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae860ebe05cb8a79a6786f52f88e47ee6">LLVMOrcDisposeSymbols</a> (LLVMOrcSymbolStringPoolEntryRef *Symbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disposes of the passed LLVMOrcSymbolStringPoolEntryRef* . <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae860ebe05cb8a79a6786f52f88e47ee6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac3b9da0aeddc9d7aeea4438d079c23f5">LLVMOrcMaterializationResponsibilityNotifyResolved</a> (LLVMOrcMaterializationResponsibilityRef MR, LLVMOrcCSymbolMapPairs Symbols, size_t NumPairs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notifies the target JITDylib that the given symbols have been resolved. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac3b9da0aeddc9d7aeea4438d079c23f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa61c29f8e9b10a3fb43d18026b531fa3">LLVMOrcMaterializationResponsibilityNotifyEmitted</a> (LLVMOrcMaterializationResponsibilityRef MR, LLVMOrcCSymbolDependenceGroup *SymbolDepGroups, size_t NumSymbolDepGroups)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notifies the target JITDylib (and any pending queries on that JITDylib) that all symbols covered by this MaterializationResponsibility instance have been emitted. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa61c29f8e9b10a3fb43d18026b531fa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac2f7c1ab68ff4224984382e511f714f3">LLVMOrcMaterializationResponsibilityDefineMaterializing</a> (LLVMOrcMaterializationResponsibilityRef MR, LLVMOrcCSymbolFlagsMapPairs Pairs, size_t NumPairs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to claim responsibility for new definitions. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac2f7c1ab68ff4224984382e511f714f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa58bdbc16510130f875e4264c5a65b87">LLVMOrcMaterializationResponsibilityFailMaterialization</a> (LLVMOrcMaterializationResponsibilityRef MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify all not-yet-emitted covered by this MaterializationResponsibility instance that an error has occurred. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa58bdbc16510130f875e4264c5a65b87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga28164bf01a8b5f61a17e303e8930ae28">LLVMOrcMaterializationResponsibilityReplace</a> (LLVMOrcMaterializationResponsibilityRef MR, LLVMOrcMaterializationUnitRef MU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfers responsibility to the given MaterializationUnit for all symbols defined by that MaterializationUnit. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga28164bf01a8b5f61a17e303e8930ae28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8ed0de76e9767b06afa96fd9df5796b6">LLVMOrcMaterializationResponsibilityDelegate</a> (LLVMOrcMaterializationResponsibilityRef MR, LLVMOrcSymbolStringPoolEntryRef *Symbols, size_t NumSymbols, LLVMOrcMaterializationResponsibilityRef *Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delegates responsibility for the given symbols to the returned materialization responsibility. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8ed0de76e9767b06afa96fd9df5796b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gadf5a7d0febb9788e712a6c221d7f6630">LLVMOrcExecutionSessionCreateBareJITDylib</a> (LLVMOrcExecutionSessionRef ES, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a "bare" JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gadf5a7d0febb9788e712a6c221d7f6630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaec6788883ef8ca0728d8f31c16a8a90e">LLVMOrcExecutionSessionCreateJITDylib</a> (LLVMOrcExecutionSessionRef ES, LLVMOrcJITDylibRef *Result, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaec6788883ef8ca0728d8f31c16a8a90e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa183c05d257c1a3d2536ccf3966678d2">LLVMOrcExecutionSessionGetJITDylibByName</a> (LLVMOrcExecutionSessionRef ES, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the JITDylib with the given name, or NULL if no such JITDylib exists. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa183c05d257c1a3d2536ccf3966678d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga89e1aa5a29b792a5bfa7336ceb3dc9aa">LLVMOrcResourceTrackerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga29104e1f2632cba11f3f1096a91ac933">LLVMOrcJITDylibCreateResourceTracker</a> (LLVMOrcJITDylibRef JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to a newly created resource tracker associated with JD. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga29104e1f2632cba11f3f1096a91ac933">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga89e1aa5a29b792a5bfa7336ceb3dc9aa">LLVMOrcResourceTrackerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga64d3a131727a9b6b86a10db6c4c37f15">LLVMOrcJITDylibGetDefaultResourceTracker</a> (LLVMOrcJITDylibRef JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the default resource tracker for the given JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga64d3a131727a9b6b86a10db6c4c37f15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa349e25fd72cbf480e926aeab681b4e2">LLVMOrcJITDylibDefine</a> (LLVMOrcJITDylibRef JD, LLVMOrcMaterializationUnitRef MU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given MaterializationUnit to the given JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa349e25fd72cbf480e926aeab681b4e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gadb3fbb441d13869c9e123df861aff457">LLVMOrcJITDylibClear</a> (LLVMOrcJITDylibRef JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls remove on all trackers associated with this JITDylib, see JITDylib::clear(). <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gadb3fbb441d13869c9e123df861aff457">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9d2415e745faef2e4c57622bf863c29a">LLVMOrcJITDylibAddGenerator</a> (LLVMOrcJITDylibRef JD, LLVMOrcDefinitionGeneratorRef DG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a DefinitionGenerator to the given JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9d2415e745faef2e4c57622bf863c29a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaaf57966a4ec602e970c2875a81b90c21">LLVMOrcDefinitionGeneratorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaeae36f6ecbe5a2fd8297d8381ea78de7">LLVMOrcCreateCustomCAPIDefinitionGenerator</a> (LLVMOrcCAPIDefinitionGeneratorTryToGenerateFunction F, void *Ctx, LLVMOrcDisposeCAPIDefinitionGeneratorFunction Dispose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a custom generator. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaeae36f6ecbe5a2fd8297d8381ea78de7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga74ea16b3e4391d71430233d238722120">LLVMOrcLookupStateContinueLookup</a> (LLVMOrcLookupStateRef S, LLVMErrorRef Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Continue a lookup that was suspended in a generator (see <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7d174ec56b7cf3fb68e21efdc7453f99">LLVMOrcCAPIDefinitionGeneratorTryToGenerateFunction</a>). <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga74ea16b3e4391d71430233d238722120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga989066e131860f8fe758251c061860a7">LLVMOrcCreateDynamicLibrarySearchGeneratorForProcess</a> (LLVMOrcDefinitionGeneratorRef *Result, char GlobalPrefx, LLVMOrcSymbolPredicate Filter, void *FilterCtx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a DynamicLibrarySearchGenerator that will reflect process symbols into the JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga989066e131860f8fe758251c061860a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7286ab56f015dc3d1364ee35c18248a0">LLVMOrcCreateDynamicLibrarySearchGeneratorForPath</a> (LLVMOrcDefinitionGeneratorRef *Result, const char *FileName, char GlobalPrefix, LLVMOrcSymbolPredicate Filter, void *FilterCtx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a LLVMOrcCreateDynamicLibararySearchGeneratorForPath that will reflect library symbols into the JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7286ab56f015dc3d1364ee35c18248a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafc0fae848a36b96fc330e3efdd3db981">LLVMOrcCreateStaticLibrarySearchGeneratorForPath</a> (LLVMOrcDefinitionGeneratorRef *Result, LLVMOrcObjectLayerRef ObjLayer, const char *FileName, const char *TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a LLVMOrcCreateStaticLibrarySearchGeneratorForPath that will reflect static library symbols into the JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafc0fae848a36b96fc330e3efdd3db981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf6c9e2e2f52a13c97b3b6603df2f34df">LLVMOrcThreadSafeContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa919752f64bf2de65a2650cf798a1cac">LLVMOrcCreateNewThreadSafeContext</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a ThreadSafeContext containing a new LLVMContext. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa919752f64bf2de65a2650cf798a1cac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaec9cc19235846b45f4528954954d5647">LLVMOrcThreadSafeContextGetContext</a> (LLVMOrcThreadSafeContextRef TSCtx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the wrapped LLVMContext. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaec9cc19235846b45f4528954954d5647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga85586185869e79721f5b6c0df6d5bcd0">LLVMOrcDisposeThreadSafeContext</a> (LLVMOrcThreadSafeContextRef TSCtx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a ThreadSafeContext. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga85586185869e79721f5b6c0df6d5bcd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga648d8baae98e849c320c2cf7ec7e548e">LLVMOrcThreadSafeModuleRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga30404ae91177de960965fd31fc73510c">LLVMOrcCreateNewThreadSafeModule</a> (LLVMModuleRef M, LLVMOrcThreadSafeContextRef TSCtx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a ThreadSafeModule wrapper around the given LLVM module. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga30404ae91177de960965fd31fc73510c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga3ca6bb3ecd59630e1ec5c4b2ab618c54">LLVMOrcDisposeThreadSafeModule</a> (LLVMOrcThreadSafeModuleRef TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a ThreadSafeModule. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga3ca6bb3ecd59630e1ec5c4b2ab618c54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1f7486814ae9dd6e67c4a43b70af4e8f">LLVMOrcThreadSafeModuleWithModuleDo</a> (LLVMOrcThreadSafeModuleRef TSM, LLVMOrcGenericIRModuleOperationFunction F, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the given function to the module contained in this ThreadSafeModule. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga1f7486814ae9dd6e67c4a43b70af4e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga5718550d7bc69420aef9830b23a1bec7">LLVMOrcJITTargetMachineBuilderDetectHost</a> (LLVMOrcJITTargetMachineBuilderRef *Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a JITTargetMachineBuilder by detecting the host. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga5718550d7bc69420aef9830b23a1bec7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga46ed788f31d61b98c26e7db8043cfc7d">LLVMOrcJITTargetMachineBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa132b01f25af37e77cd7610fe8b431d2">LLVMOrcJITTargetMachineBuilderCreateFromTargetMachine</a> (LLVMTargetMachineRef TM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a JITTargetMachineBuilder from the given TargetMachine template. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa132b01f25af37e77cd7610fe8b431d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaff9873d4cb56e4b0e91fe99b8e52a309">LLVMOrcDisposeJITTargetMachineBuilder</a> (LLVMOrcJITTargetMachineBuilderRef JTMB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a JITTargetMachineBuilder. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaff9873d4cb56e4b0e91fe99b8e52a309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gad191475ab9c622ad8f092c116d7ec086">LLVMOrcJITTargetMachineBuilderGetTargetTriple</a> (LLVMOrcJITTargetMachineBuilderRef JTMB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target triple for the given JITTargetMachineBuilder as a string. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gad191475ab9c622ad8f092c116d7ec086">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9b1d8862e3663a1008441bd8b5d611db">LLVMOrcJITTargetMachineBuilderSetTargetTriple</a> (LLVMOrcJITTargetMachineBuilderRef JTMB, const char *TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the target triple for the given JITTargetMachineBuilder to the given string. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9b1d8862e3663a1008441bd8b5d611db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac3356e8c9028ec515d44d41994f742ed">LLVMOrcObjectLayerAddObjectFile</a> (LLVMOrcObjectLayerRef ObjLayer, LLVMOrcJITDylibRef JD, LLVMMemoryBufferRef ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an object to an ObjectLayer to the given JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac3356e8c9028ec515d44d41994f742ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga171817def76317bb07e9953a5393a3d9">LLVMOrcObjectLayerAddObjectFileWithRT</a> (LLVMOrcObjectLayerRef ObjLayer, LLVMOrcResourceTrackerRef RT, LLVMMemoryBufferRef ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an object to an ObjectLayer using the given ResourceTracker. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga171817def76317bb07e9953a5393a3d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8a39e2320711e383e9ccaf78ed725a87">LLVMOrcObjectLayerEmit</a> (LLVMOrcObjectLayerRef ObjLayer, LLVMOrcMaterializationResponsibilityRef R, LLVMMemoryBufferRef ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an object buffer to an ObjectLayer. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8a39e2320711e383e9ccaf78ed725a87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga3a534fcf2aaf76a3c3919559b770cc00">LLVMOrcDisposeObjectLayer</a> (LLVMOrcObjectLayerRef ObjLayer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an ObjectLayer. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga3a534fcf2aaf76a3c3919559b770cc00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga271736e0a58e4f01073c4496dd766e4c">LLVMOrcIRTransformLayerEmit</a> (LLVMOrcIRTransformLayerRef IRTransformLayer, LLVMOrcMaterializationResponsibilityRef MR, LLVMOrcThreadSafeModuleRef TSM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf72d2f5a4800465a3b6f36d8d534162a">LLVMOrcIRTransformLayerSetTransform</a> (LLVMOrcIRTransformLayerRef IRTransformLayer, LLVMOrcIRTransformLayerTransformFunction TransformFunction, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the transform function of the provided transform layer, passing through a pointer to user provided context. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf72d2f5a4800465a3b6f36d8d534162a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga3cac6ed2b5c8f922b4154ef915096a22">LLVMOrcObjectTransformLayerSetTransform</a> (LLVMOrcObjectTransformLayerRef ObjTransformLayer, LLVMOrcObjectTransformLayerTransformFunction TransformFunction, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the transform function on an LLVMOrcObjectTransformLayer. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga3cac6ed2b5c8f922b4154ef915096a22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga6c826d2b477de0b97c2943f852f3f4b5">LLVMOrcIndirectStubsManagerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9a2781fcf8c1fd4525b8ac1455a415d4">LLVMOrcCreateLocalIndirectStubsManager</a> (const char *TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a LocalIndirectStubsManager from the given target triple. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9a2781fcf8c1fd4525b8ac1455a415d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac17cfd3baff6796b352847a89965e483">LLVMOrcDisposeIndirectStubsManager</a> (LLVMOrcIndirectStubsManagerRef ISM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an IndirectStubsManager. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac17cfd3baff6796b352847a89965e483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga18d11d3d068c59207d39cd72a6224f01">LLVMOrcCreateLocalLazyCallThroughManager</a> (const char *TargetTriple, LLVMOrcExecutionSessionRef ES, LLVMOrcJITTargetAddress ErrorHandlerAddr, LLVMOrcLazyCallThroughManagerRef *LCTM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaddb9e6231abd7910902280f4057eaa32">LLVMOrcDisposeLazyCallThroughManager</a> (LLVMOrcLazyCallThroughManagerRef LCTM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an LazyCallThroughManager. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaddb9e6231abd7910902280f4057eaa32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gadae2662d8f533a63bf4ca3242868c743">LLVMOrcDumpObjectsRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga86c43f72e8b66fc6aefe1a4464177d50">LLVMOrcCreateDumpObjects</a> (const char *DumpDir, const char *IdentifierOverride)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DumpObjects instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga86c43f72e8b66fc6aefe1a4464177d50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gad0046618cd87b1b02777e9c78d864340">LLVMOrcDisposeDumpObjects</a> (LLVMOrcDumpObjectsRef DumpObjects)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a DumpObjects instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gad0046618cd87b1b02777e9c78d864340">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9293a65df367929436b36c2fff46e563">LLVMOrcDumpObjects_CallOperator</a> (LLVMOrcDumpObjectsRef DumpObjects, LLVMMemoryBufferRef *ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the contents of the given MemoryBuffer. <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9293a65df367929436b36c2fff46e563">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
