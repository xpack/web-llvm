---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armjitsymbolflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMJITSymbolFlags` Class

<p>ARM-specific JIT symbol flags. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARMJITSymbolFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">llvm/ExecutionEngine/JITSymbol.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FlagNames { <a href="#a213d02a59bf1fd85318a706440ca169c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6dbb3d85fd5bafc54b2244a6f7fc4f">ARMJITSymbolFlags</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec3875f67cbcf4db761aec620a8d1998">operator JITSymbolFlags::TargetFlagsType &amp;</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a52b2cde16c7a36e0ac89c4a9462f2226">JITSymbolFlags::TargetFlagsType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eaf5c58239970029dcd4e2203587771">Flags</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armjitsymbolflags">ARMJITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942d2281f1774d37e0225dfde4166ae4">fromObjectSymbol</a> (const object::SymbolRef &amp;Symbol)</td>
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

<p>ARM-specific JIT symbol flags.</p>


<p>FIXME: This should be moved into a target-specific header.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FlagNames {#a213d02a59bf1fd85318a706440ca169c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMJITSymbolFlags::FlagNames </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a213d02a59bf1fd85318a706440ca169caf0eb43a4a76d5acfbdaeb7b1dc35defa"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Thumb<a id="a213d02a59bf1fd85318a706440ca169cabcaf88e63f6a97eb2b750bcaa8fc8d47"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ARMJITSymbolFlags() {#afa6dbb3d85fd5bafc54b2244a6f7fc4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARMJITSymbolFlags::ARMJITSymbolFlags ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Referenced by <a href="#a942d2281f1774d37e0225dfde4166ae4">fromObjectSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator JITSymbolFlags::TargetFlagsType &amp;() {#aec3875f67cbcf4db761aec620a8d1998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARMJITSymbolFlags::operator JITSymbolFlags::TargetFlagsType &amp; ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Flags {#a2eaf5c58239970029dcd4e2203587771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags::TargetFlagsType llvm::ARMJITSymbolFlags::Flags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromObjectSymbol() {#a942d2281f1774d37e0225dfde4166ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMJITSymbolFlags llvm::ARMJITSymbolFlags::fromObjectSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">object::SymbolRef</a> &amp; Symbol)</td>
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



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/jitsymbol-cpp">JITSymbol.cpp</a>.</p>


<p>References <a href="#afa6dbb3d85fd5bafc54b2244a6f7fc4f">ARMJITSymbolFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a586a24e61bc504778e4c89c8bb929e90">llvm::object::BasicSymbolRef::SF_Thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#a213d02a59bf1fd85318a706440ca169cabcaf88e63f6a97eb2b750bcaa8fc8d47">Thumb</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a5be127713fc8105efd1e4261f09b1097">llvm::RuntimeDyldMachOARM::getJITSymbolFlags</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/jitsymbol-cpp">JITSymbol.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
