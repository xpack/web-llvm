---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functionimportglobalprocessing
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionImportGlobalProcessing` Class Reference

<p>Class to handle necessary <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> changes required by ThinLTO function importing, including linkage changes and any necessary renaming. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FunctionImportGlobalProcessing { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">llvm/Transforms/Utils/FunctionImportUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d457aedadef41588c7ae3c16adbfc8">FunctionImportGlobalProcessing</a> (Module &amp;M, const ModuleSummaryIndex &amp;Index, SetVector&lt; GlobalValue * &gt; *GlobalsToImport, bool ClearDSOLocalOnDeclarations)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6d45acb67bb0109f15791d99469bb4">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac763faaf8e4ada21d68e1f4d5aa8fd5f">shouldPromoteLocalToGlobal</a> (const GlobalValue *SGV, ValueInfo VI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we should promote the given local value to global scope. <a href="#ac763faaf8e4ada21d68e1f4d5aa8fd5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d0707bcc4b87e833fa6d7845577163">isNonRenamableLocal</a> (const GlobalValue &amp;GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given value is a local that can't be renamed (promoted). <a href="#aa4d0707bcc4b87e833fa6d7845577163">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a139fc22efa824e8a1241006c33ebe531">isPerformingImport</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper methods to check if we are importing from or potentially exporting from the current source module. <a href="#a139fc22efa824e8a1241006c33ebe531">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af163b85811bfbc78a55e5117514197bc">isModuleExporting</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8ca8f14264b69f973f4240182d6e32">doImportAsDefinition</a> (const GlobalValue *SGV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we are importing from the source module, checks if we should import SGV as a definition, otherwise import as a declaration. <a href="#abb8ca8f14264b69f973f4240182d6e32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2677b53d46932435cd90371cdcc7029">getPromotedName</a> (const GlobalValue *SGV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name for a local SGV that should be promoted and renamed to global scope in the linked destination module. <a href="#ac2677b53d46932435cd90371cdcc7029">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c30cfa6d26aaa32dff6fb83579ab27">processGlobalsForThinLTO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> globals so that they can be used in ThinLTO. <a href="#a82c30cfa6d26aaa32dff6fb83579ab27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b14aab149eb078fb6a680cb2ec02753">processGlobalForThinLTO</a> (GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e57abcd498aa6730e18cd434934ac9">getLinkage</a> (const GlobalValue *SGV, bool DoPromote)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the new linkage for SGV that should be used in the linked destination module. <a href="#ae7e57abcd498aa6730e18cd434934ac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf562ed33e85bcc4140727052b83b9f">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> which we are exporting or importing functions from. <a href="#a3bf562ed33e85bcc4140727052b83b9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e5e1b06954344782090c9c64ce6c49">ImportIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> summary index passed in for function importing/exporting handling. <a href="#a40e5e1b06954344782090c9c64ce6c49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadadbac82aae68def15c93f343352c39">GlobalsToImport</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Globals to import from this module, all other functions will be imported as declarations instead of definitions. <a href="#aadadbac82aae68def15c93f343352c39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888c54fae80f3de0eaa2610743704145">HasExportedFunctions</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true if the given <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> contains any functions from this source module, in which case we must conservatively assume that any of its functions may be imported into another module as part of a different backend compilation process. <a href="#a888c54fae80f3de0eaa2610743704145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca29dbc576bf01d37c00bdb9a410d4a">ClearDSOLocalOnDeclarations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true (only applicatable to <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> -fpic) if dso_local should be dropped for a declaration. <a href="#abca29dbc576bf01d37c00bdb9a410d4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be4e4b9b629131c0a2abf947ada947e">Used</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of llvm. <a href="#a4be4e4b9b629131c0a2abf947ada947e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *, <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75975d5c05fc43b17db630691f880a8e">RenamedComdats</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of any COMDATs that require renaming (because COMDAT leader was promoted and renamed). <a href="#a75975d5c05fc43b17db630691f880a8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to handle necessary <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> changes required by ThinLTO function importing, including linkage changes and any necessary renaming.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionImportGlobalProcessing() {#ad2d457aedadef41588c7ae3c16adbfc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionImportGlobalProcessing::FunctionImportGlobalProcessing (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; * GlobalsToImport, bool ClearDSOLocalOnDeclarations)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afd1cdae0d7a12aa1861ac142c059f5d2">llvm::collectUsedGlobalVariables</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a8de3ed741dadc9c979a4ff17c0a9116e">NDEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#afc6d45acb67bb0109f15791d99469bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionImportGlobalProcessing::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a46122434c47e17760d4c6709878a0dd6">llvm::renameModuleForThinLTO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### doImportAsDefinition() {#abb8ca8f14264b69f973f4240182d6e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FunctionImportGlobalProcessing::doImportAsDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * SGV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we are importing from the source module, checks if we should import SGV as a definition, otherwise import as a declaration.</p>


<p>Checks if we should import SGV as a definition, otherwise import as a declaration.</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

### getLinkage() {#ae7e57abcd498aa6730e18cd434934ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::LinkageTypes FunctionImportGlobalProcessing::getLinkage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * SGV, bool DoPromote)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the new linkage for SGV that should be used in the linked destination module.</p>


<p>Specifically, for ThinLTO importing or exporting it may need to be adjusted. When <span class="doxyComputerOutput">DoPromote</span> is true then we must adjust the linkage for a required promotion of a local to global scope.</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

### getPromotedName() {#ac2677b53d46932435cd90371cdcc7029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string FunctionImportGlobalProcessing::getPromotedName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * SGV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name for a local SGV that should be promoted and renamed to global scope in the linked destination module.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

### isModuleExporting() {#af163b85811bfbc78a55e5117514197bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionImportGlobalProcessing::isModuleExporting ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### isNonRenamableLocal() {#aa4d0707bcc4b87e833fa6d7845577163}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FunctionImportGlobalProcessing::isNonRenamableLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given value is a local that can't be renamed (promoted).</p>


<p>Only used in assertion checking, and disabled under NDEBUG since the Used set will not be populated.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

### isPerformingImport() {#a139fc22efa824e8a1241006c33ebe531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionImportGlobalProcessing::isPerformingImport ()</td>
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

<p>Helper methods to check if we are importing from or potentially exporting from the current source module.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### processGlobalForThinLTO() {#a7b14aab149eb078fb6a680cb2ec02753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionImportGlobalProcessing::processGlobalForThinLTO (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

### processGlobalsForThinLTO() {#a82c30cfa6d26aaa32dff6fb83579ab27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionImportGlobalProcessing::processGlobalsForThinLTO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> globals so that they can be used in ThinLTO.</p>


<p>This includes promoting local variables so that they can be reference externally by thin lto imported globals and converting strong external globals to available_externally.</p>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

### shouldPromoteLocalToGlobal() {#ac763faaf8e4ada21d68e1f4d5aa8fd5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FunctionImportGlobalProcessing::shouldPromoteLocalToGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * SGV, <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> VI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we should promote the given local value to global scope.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClearDSOLocalOnDeclarations {#abca29dbc576bf01d37c00bdb9a410d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionImportGlobalProcessing::ClearDSOLocalOnDeclarations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true (only applicatable to <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> -fpic) if dso_local should be dropped for a declaration.</p>


<p>On <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>, the assembler is conservative and assumes a global default visibility symbol can be interposable. No direct access relocation is allowed, if the definition is not in the translation unit, even if the definition is available in the linkage unit. Thus we need to clear dso_local to disable direct access.</p>


<p>This flag should not be set for -fno-pic or -fpie, which would unnecessarily disable direct access.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### GlobalsToImport {#aadadbac82aae68def15c93f343352c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;GlobalValue *&gt;* llvm::FunctionImportGlobalProcessing::GlobalsToImport</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Globals to import from this module, all other functions will be imported as declarations instead of definitions.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### HasExportedFunctions {#a888c54fae80f3de0eaa2610743704145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionImportGlobalProcessing::HasExportedFunctions = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true if the given <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> contains any functions from this source module, in which case we must conservatively assume that any of its functions may be imported into another module as part of a different backend compilation process.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### ImportIndex {#a40e5e1b06954344782090c9c64ce6c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex&amp; llvm::FunctionImportGlobalProcessing::ImportIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> summary index passed in for function importing/exporting handling.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### M {#a3bf562ed33e85bcc4140727052b83b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::FunctionImportGlobalProcessing::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> which we are exporting or importing functions from.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### RenamedComdats {#a75975d5c05fc43b17db630691f880a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Comdat *, Comdat *&gt; llvm::FunctionImportGlobalProcessing::RenamedComdats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of any COMDATs that require renaming (because COMDAT leader was promoted and renamed).</p>


<p>Maps from original COMDAT to one with new name.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

### Used {#a4be4e4b9b629131c0a2abf947ada947e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;GlobalValue *, 4&gt; llvm::FunctionImportGlobalProcessing::Used</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of llvm.</p>


<p>*used values, in order to validate that we don't try to promote any non-renamable values.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">FunctionImportUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
