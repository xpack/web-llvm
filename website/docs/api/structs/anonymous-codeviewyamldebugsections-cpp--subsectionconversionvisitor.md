---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SubsectionConversionVisitor` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionvisitor">DebugSubsectionVisitor</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b869144e47069cb6fbeca8ff49a6de">visitUnknown</a> (DebugUnknownSubsectionRef &amp;Unknown) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa282429f771c1001960ab39ffe30ef28">visitLines</a> (DebugLinesSubsectionRef &amp;Lines, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6468d10b992a6ad6bb3908531839004">visitFileChecksums</a> (DebugChecksumsSubsectionRef &amp;Checksums, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed8c2f4079a6030f5f98ae798a374041">visitInlineeLines</a> (DebugInlineeLinesSubsectionRef &amp;Inlinees, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbf9bc88c2dff15da11c242335b2769">visitCrossModuleExports</a> (DebugCrossModuleExportsSubsectionRef &amp;Checksums, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817662724fa3463e8dd93d42e17e3596">visitCrossModuleImports</a> (DebugCrossModuleImportsSubsectionRef &amp;Inlinees, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a4af68293ab58edcdd373776f70476">visitStringTable</a> (DebugStringTableSubsectionRef &amp;ST, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167e306fc412a1eedbd1c70c7ed838bb">visitSymbols</a> (DebugSymbolsSubsectionRef &amp;Symbols, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59986054f1f5fed916f1e896ee9a2368">visitFrameData</a> (DebugFrameDataSubsectionRef &amp;Symbols, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10fdcb5526a3924122ebfa4246d2de1">visitCOFFSymbolRVAs</a> (DebugSymbolRVASubsectionRef &amp;Symbols, const StringsAndChecksumsRef &amp;State) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamldebugsubsection">YAMLDebugSubsection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a></td>
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


<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SubsectionConversionVisitor() {#a10c167541393ca7b5bd48a224222f9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::SubsectionConversionVisitor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afaa0b0293a2db49f5f93c15a62e095c819">llvm::codeview::Lines</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa5214a8a633c296d1d9d504fc54556692">llvm::codeview::Symbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fa4e81c184ac3ad48a389cd4454c4a05bb">Unknown</a>, <a href="#af10fdcb5526a3924122ebfa4246d2de1">visitCOFFSymbolRVAs</a>, <a href="#a9fbf9bc88c2dff15da11c242335b2769">visitCrossModuleExports</a>, <a href="#a817662724fa3463e8dd93d42e17e3596">visitCrossModuleImports</a>, <a href="#ad6468d10b992a6ad6bb3908531839004">visitFileChecksums</a>, <a href="#a59986054f1f5fed916f1e896ee9a2368">visitFrameData</a>, <a href="#aed8c2f4079a6030f5f98ae798a374041">visitInlineeLines</a>, <a href="#aa282429f771c1001960ab39ffe30ef28">visitLines</a>, <a href="#a25a4af68293ab58edcdd373776f70476">visitStringTable</a>, <a href="#a167e306fc412a1eedbd1c70c7ed838bb">visitSymbols</a> and <a href="#ad7b869144e47069cb6fbeca8ff49a6de">visitUnknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitCOFFSymbolRVAs() {#af10fdcb5526a3924122ebfa4246d2de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitCOFFSymbolRVAs (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolrvasubsectionref">DebugSymbolRVASubsectionRef</a> &amp; Symbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcoffsymbolrvasubsection/#aab18a1d4105702416687dd414fcfc2ba">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCoffSymbolRVASubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitCrossModuleExports() {#a9fbf9bc88c2dff15da11c242335b2769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitCrossModuleExports (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleexportssubsectionref">DebugCrossModuleExportsSubsectionRef</a> &amp; Checksums, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleexportssubsection/#a5d3e321118a9257121b1254b7e810d0b">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleExportsSubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitCrossModuleImports() {#a817662724fa3463e8dd93d42e17e3596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitCrossModuleImports (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleimportssubsectionref">DebugCrossModuleImportsSubsectionRef</a> &amp; Inlinees, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleimportssubsection/#ab42895970e4ba1faf321f15498ec80e3">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleImportsSubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitFileChecksums() {#ad6468d10b992a6ad6bb3908531839004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitFileChecksums (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsectionref">DebugChecksumsSubsectionRef</a> &amp; Checksums, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlchecksumssubsection/#a453d6247532a40368a1aa72bb3bc2e08">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLChecksumsSubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitFrameData() {#a59986054f1f5fed916f1e896ee9a2368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitFrameData (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref">DebugFrameDataSubsectionRef</a> &amp; Symbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlframedatasubsection/#adbb271a35aa3f6d4d6209ed00bf1620b">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLFrameDataSubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitInlineeLines() {#aed8c2f4079a6030f5f98ae798a374041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitInlineeLines (<a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsectionref">DebugInlineeLinesSubsectionRef</a> &amp; Inlinees, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlinlineelinessubsection/#af257dee047efcfef7fd6c5641195d97c">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLInlineeLinesSubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitLines() {#aa282429f771c1001960ab39ffe30ef28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitLines (<a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsectionref">DebugLinesSubsectionRef</a> &amp; Lines, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamllinessubsection/#aec34b23d6a06eb6e4db5290bced7391a">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLLinesSubsection::fromCodeViewSubsection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afaa0b0293a2db49f5f93c15a62e095c819">llvm::codeview::Lines</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitStringTable() {#a25a4af68293ab58edcdd373776f70476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitStringTable (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref">DebugStringTableSubsectionRef</a> &amp; ST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlstringtablesubsection/#a4f338238a79ff08b58e7caf51b4e4986">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLStringTableSubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitSymbols() {#a167e306fc412a1eedbd1c70c7ed838bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitSymbols (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolssubsectionref">DebugSymbolsSubsectionRef</a> &amp; Symbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksumsref">StringsAndChecksumsRef</a> &amp; State)</td>
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



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlsymbolssubsection/#a3e9bc9ee10900fa54b28a92efd48103e">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLSymbolsSubsection::fromCodeViewSubsection</a>, <a href="#ac1a22572fd5daed6976b341f2cf37b68">Subsection</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa5214a8a633c296d1d9d504fc54556692">llvm::codeview::Symbols</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

### visitUnknown() {#ad7b869144e47069cb6fbeca8ff49a6de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SubsectionConversionVisitor::visitUnknown (<a href="/web-llvm/docs/api/classes/llvm/codeview/debugunknownsubsectionref">DebugUnknownSubsectionRef</a> &amp; Unknown)</td>
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



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0e494c491fad71e29cc10efce7c59f6caa3ef1e12501238ddcca5063cc730a494">llvm::codeview::operation_unsupported</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fa4e81c184ac3ad48a389cd4454c4a05bb">Unknown</a>.</p>


<p>Referenced by <a href="#a10c167541393ca7b5bd48a224222f9a2">SubsectionConversionVisitor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Subsection {#ac1a22572fd5daed6976b341f2cf37b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">YAMLDebugSubsection anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::Subsection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>Referenced by <a href="#af10fdcb5526a3924122ebfa4246d2de1">visitCOFFSymbolRVAs</a>, <a href="#a9fbf9bc88c2dff15da11c242335b2769">visitCrossModuleExports</a>, <a href="#a817662724fa3463e8dd93d42e17e3596">visitCrossModuleImports</a>, <a href="#ad6468d10b992a6ad6bb3908531839004">visitFileChecksums</a>, <a href="#a59986054f1f5fed916f1e896ee9a2368">visitFrameData</a>, <a href="#aed8c2f4079a6030f5f98ae798a374041">visitInlineeLines</a>, <a href="#aa282429f771c1001960ab39ffe30ef28">visitLines</a>, <a href="#a25a4af68293ab58edcdd373776f70476">visitStringTable</a> and <a href="#a167e306fc412a1eedbd1c70c7ed838bb">visitSymbols</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
