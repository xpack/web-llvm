---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/densemapinfo-6d820381112462a5bb6b93e4ae7ccfa6
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DenseMapInfo` Struct Template Reference

<p>Provide <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> for <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DenseMapInfo&lt;TargetInstrInfo::RegSubRegPair&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13fc7475f78b2bc7d3d2c062de86a51">RegInfo</a> = <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65eaee414c0bdce3aeee60b779e3a5e">SubRegInfo</a> = <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; unsigned &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25c8fda3a2440cdd80c5700908b6ffe">getEmptyKey</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71bdb91d07d20f218df3df2edaef89d">getTombstoneKey</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4315dd5a3e784903ff1a7e7a546528">getHashValue</a> (const TargetInstrInfo::RegSubRegPair &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reuse getHashValue implementation from std::pair&lt;unsigned, unsigned&gt;. <a href="#a3d4315dd5a3e784903ff1a7e7a546528">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9fa041d45b08902da295d552d85ff05">isEqual</a> (const TargetInstrInfo::RegSubRegPair &amp;LHS, const TargetInstrInfo::RegSubRegPair &amp;RHS)</td>
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

<p>Provide <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> for <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a>.</p>

<p>Definition at line 2301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### RegInfo {#ab13fc7475f78b2bc7d3d2c062de86a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::RegInfo =  DenseMapInfo&lt;Register&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### SubRegInfo {#ac65eaee414c0bdce3aeee60b779e3a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::SubRegInfo =  DenseMapInfo&lt;unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEmptyKey() {#af25c8fda3a2440cdd80c5700908b6ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetInstrInfo::RegSubRegPair llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::getEmptyKey ()</td>
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



<p>Definition at line 2305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### getHashValue() {#a3d4315dd5a3e784903ff1a7e7a546528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::getHashValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a> &amp; Val)</td>
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

<p>Reuse getHashValue implementation from std::pair&lt;unsigned, unsigned&gt;.</p>

<p>Definition at line 2317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#a3d4315dd5a3e784903ff1a7e7a546528">getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#aad7e848e562b1368d6ee4794d84957c6">llvm::TargetInstrInfo::RegSubRegPair::Reg</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#a66f92cf2247d7b3c3a351ff48dd42d7d">llvm::TargetInstrInfo::RegSubRegPair::SubReg</a>.</p>


<p>Referenced by <a href="#a3d4315dd5a3e784903ff1a7e7a546528">getHashValue</a>.</p>

</div>
</div>

### getTombstoneKey() {#ac71bdb91d07d20f218df3df2edaef89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetInstrInfo::RegSubRegPair llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::getTombstoneKey ()</td>
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



<p>Definition at line 2310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

### isEqual() {#af9fa041d45b08902da295d552d85ff05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::isEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a> &amp; RHS)</td>
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



<p>Definition at line 2322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
