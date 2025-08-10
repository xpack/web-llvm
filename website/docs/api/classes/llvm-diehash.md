---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diehash
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DIEHash` Class

<p>An object containing the capability of hashing and adding hash attributes onto a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIEHash { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">CodeGen/AsmPrinter/DIEHash.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa797ce3f0976b5b2c84aa243f358eb0a">DIEHash</a> (AsmPrinter *A=nullptr, DwarfCompileUnit *CU=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad27bf36fbf19cdf6d2e5a9dfeebaf260">computeCUSignature</a> (StringRef DWOName, const DIE &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> signature. <a href="#ad27bf36fbf19cdf6d2e5a9dfeebaf260">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e2fce16609b6482e290f3f24172f85">computeTypeSignature</a> (const DIE &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the type signature. <a href="#a22e2fce16609b6482e290f3f24172f85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063be6e165f8e65e7de310de0ce3c220">update</a> (uint8_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds. <a href="#a063be6e165f8e65e7de310de0ce3c220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade85a09627dcb50ba5fb50f6229fbae1">addULEB128</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encodes and adds. <a href="#ade85a09627dcb50ba5fb50f6229fbae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab458e091bd49a857ced20f00a83c6965">addSLEB128</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encodes and adds. <a href="#ab458e091bd49a857ced20f00a83c6965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ee5d1f893f38e06003101066e6f30b">hashRawTypeReference</a> (const DIE &amp;Entry)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2949099d4783246b5cf81c59477a3fe">addParentContext</a> (const DIE &amp;Parent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the parent context of. <a href="#ae2949099d4783246b5cf81c59477a3fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a7226655e75b3878146c57d18fee65">addAttributes</a> (const DIE &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the attributes of. <a href="#a46a7226655e75b3878146c57d18fee65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0d956eceb40a3bc01c5f49f2682d2e">computeHash</a> (const DIE &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the full DWARF4 7.27 hash of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ada0d956eceb40a3bc01c5f49f2682d2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cdd02593c8c57e743e669c72ff810ed">addString</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds. <a href="#a8cdd02593c8c57e743e669c72ff810ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c8d6348b33dd023129a417d1cd2934">collectAttributes</a> (const DIE &amp;Die, DIEAttrs &amp;Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects the attributes of <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a02c8d6348b33dd023129a417d1cd2934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690d8f27552bfb770e10812eaf474672">hashAttributes</a> (const DIEAttrs &amp;Attrs, dwarf::Tag Tag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes the attributes in. <a href="#a690d8f27552bfb770e10812eaf474672">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3b3a845eff571985f2cc6aa6b59b50">hashBlockData</a> (const DIE::const_value_range &amp;Values)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes the data in a block like <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a>, e.g. <a href="#adc3b3a845eff571985f2cc6aa6b59b50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12db3e43081f36b4d8965f563477449b">hashLocList</a> (const DIELocList &amp;LocList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes the contents pointed to in the .debug_loc section. <a href="#a12db3e43081f36b4d8965f563477449b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9776f078c8aca990f8ab07108ffc0fe5">hashAttribute</a> (const DIEValue &amp;Value, dwarf::Tag Tag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes an individual attribute. <a href="#a9776f078c8aca990f8ab07108ffc0fe5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc1615ca450ba6f30f73db5b2c26149">hashDIEEntry</a> (dwarf::Attribute Attribute, dwarf::Tag Tag, const DIE &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes an attribute that refers to another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a6cc1615ca450ba6f30f73db5b2c26149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437686ffabce0f67e3afab4cc3c53747">hashShallowTypeReference</a> (dwarf::Attribute Attribute, const DIE &amp;Entry, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes a reference to a named type in such a way that is independent of whether that type is described by a declaration or a definition. <a href="#a437686ffabce0f67e3afab4cc3c53747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6fd46fc2f501bccb361ba7f47e6876">hashRepeatedTypeReference</a> (dwarf::Attribute Attribute, unsigned DieNumber)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes a reference to a previously referenced type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a9e6fd46fc2f501bccb361ba7f47e6876">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a24c257145c5efca98c5b7fddbd28d">hashNestedType</a> (const DIE &amp;Die, StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab972608ffe6388ad6e14945237dde68e">Hash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca977678d6a30093831fa32dd219e475">AP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5ecde99c1850eaa32c8b5f30a93107">CU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a870268054b8943e5d84ca393c58bfec8">Numbering</a></td>
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

<p>An object containing the capability of hashing and adding hash attributes onto a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIEHash() {#aa797ce3f0976b5b2c84aa243f358eb0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIEHash::DIEHash (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * CU=nullptr)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSLEB128() {#ab458e091bd49a857ced20f00a83c6965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::addSLEB128 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encodes and adds.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>to the hash as a SLEB128.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### addULEB128() {#ade85a09627dcb50ba5fb50f6229fbae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::addULEB128 (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encodes and adds.</p>


<p>Adds the unsigned in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to the hash encoded as a ULEB128.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>to the hash as a ULEB128.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a14ee5d1f893f38e06003101066e6f30b">hashRawTypeReference</a>.</p>

</div>
</div>

### computeCUSignature() {#ad27bf36fbf19cdf6d2e5a9dfeebaf260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DIEHash::computeCUSignature (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DWOName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> signature.</p>


<p>This is based on the type signature computation given in section 7.27 of the DWARF4 standard.</p>


<p>It is an md5 hash of the flattened description of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with the inclusion of the full <a href="/web-llvm/docs/api/namespaces/cu">CU</a> and all top level <a href="/web-llvm/docs/api/namespaces/cu">CU</a> entities.</p>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>

</div>
</div>

### computeTypeSignature() {#a22e2fce16609b6482e290f3f24172f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DIEHash::computeTypeSignature (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the type signature.</p>


<p>This is based on the type signature computation given in section 7.27 of the DWARF4 standard.</p>


<p>It is an md5 hash of the flattened description of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with the inclusion of additional forms not specifically called out in the standard.</p>


<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/die/#af985c8a58986e45114a8c3e6cbf0504a">llvm::DIE::getParent</a>.</p>

</div>
</div>

### hashRawTypeReference() {#a14ee5d1f893f38e06003101066e6f30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashRawTypeReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>


<p>Reference <a href="#ade85a09627dcb50ba5fb50f6229fbae1">addULEB128</a>.</p>

</div>
</div>

### update() {#a063be6e165f8e65e7de310de0ce3c220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DIEHash::update (uint8_t Value)</td>
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

<p>Adds.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>to the hash.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addAttributes() {#a46a7226655e75b3878146c57d18fee65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::addAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds the attributes of.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>to the hash.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### addParentContext() {#ae2949099d4783246b5cf81c59477a3fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::addParentContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds the parent context of.</p>


<p>Including <span class="doxyComputerOutput">Parent</span> adds the context of Parent to the hash..</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>to the hash.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### addString() {#a8cdd02593c8c57e743e669c72ff810ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::addString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds.</p>


<p>Adds the string in <span class="doxyComputerOutput">Str</span> to the hash.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Str</td>
<td class="doxyParamItemDescription"><p>to the hash and includes a NULL byte.</p></td>
</tr>
</table>
</dd>
</dl>

<p>This also hashes a trailing NULL with the string.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### collectAttributes() {#a02c8d6348b33dd023129a417d1cd2934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::collectAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, DIEAttrs &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collects the attributes of <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>into the</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attrs</td>
<td class="doxyParamItemDescription"><p>structure.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### computeHash() {#ada0d956eceb40a3bc01c5f49f2682d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::computeHash (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the full DWARF4 7.27 hash of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashAttribute() {#a9776f078c8aca990f8ab07108ffc0fe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp; Value, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hashes an individual attribute.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashAttributes() {#a690d8f27552bfb770e10812eaf474672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DIEAttrs &amp; Attrs, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hashes the attributes in.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attrs</td>
<td class="doxyParamItemDescription"><p>in order.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashBlockData() {#adc3b3a845eff571985f2cc6aa6b59b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashBlockData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dievaluelist/#af32bf2d3893fa6a50956553675758578">DIE::const_value_range</a> &amp; Values)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hashes the data in a block like <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a>, e.g.</p>


<p>DW_FORM_block or DW_FORM_exprloc.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashDIEEntry() {#a6cc1615ca450ba6f30f73db5b2c26149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashDIEEntry (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hashes an attribute that refers to another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashLocList() {#a12db3e43081f36b4d8965f563477449b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashLocList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dieloclist">DIELocList</a> &amp; LocList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hashes the contents pointed to in the .debug_loc section.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashNestedType() {#a36a24c257145c5efca98c5b7fddbd28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashNestedType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashRepeatedTypeReference() {#a9e6fd46fc2f501bccb361ba7f47e6876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashRepeatedTypeReference (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, unsigned DieNumber)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hashes a reference to a previously referenced type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

### hashShallowTypeReference() {#a437686ffabce0f67e3afab4cc3c53747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEHash::hashShallowTypeReference (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hashes a reference to a named type in such a way that is independent of whether that type is described by a declaration or a definition.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AP {#aca977678d6a30093831fa32dd219e475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* llvm::DIEHash::AP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>.</p>

</div>
</div>

### CU {#a9b5ecde99c1850eaa32c8b5f30a93107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit* llvm::DIEHash::CU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>.</p>

</div>
</div>

### Hash {#ab972608ffe6388ad6e14945237dde68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5 llvm::DIEHash::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>.</p>

</div>
</div>

### Numbering {#a870268054b8943e5d84ca393c58bfec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DIE *, unsigned&gt; llvm::DIEHash::Numbering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-cpp">DIEHash.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
