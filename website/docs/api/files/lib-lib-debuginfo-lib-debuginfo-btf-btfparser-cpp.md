---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BTFParser.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btfparser-h">llvm/DebugInfo/BTF/BTFParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-btfparser-cpp-">anonymous{BTFParser.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-btfparser-cpp-/err">Err</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/btfparser/parsecontext">ParseContext</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-btfparser-cpp-/stroranon">StrOrAnon</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RelocKindGroup { <a href="#ad1f539052870283fcdc5d6d8738b4866">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59534c1e1daba811d6792180bb6b5905">byteSize</a> (BTF::CommonType *Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac835023c2f2a4fbe350567206319f0bb">findInfo</a> (const DenseMap&lt; uint64_t, SmallVector&lt; T, 0 &gt; &gt; &amp;SecMap, SectionedAddress Address)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ad1f539052870283fcdc5d6d8738b4866">RelocKindGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b3de8cc0d131e00cd6d83fb3545921">relocKindGroup</a> (const BTF::BPFFieldReloc *Reloc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a20b9452e061c8b67f5ffcaeadc501d">isMod</a> (const BTF::CommonType *Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac0573ec9ff64b7c46d893994892cc0">printMod</a> (const BTFParser &amp;BTF, const BTF::CommonType *Type, raw_ostream &amp;Stream)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/btf/commontype">BTF::CommonType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc5b9e0eef6fe127531ff21cdf4a4320">skipModsAndTypedefs</a> (const BTFParser &amp;BTF, const BTF::CommonType *Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45afa179ec726532c135c2a22018698">relocKindName</a> (uint32_t X, raw_ostream &amp;Out)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dbdbafb8b8f310ebdd7bf5d4bcc0edd">BTFSectionName</a>[] = ".BTF"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f4e549975547fd95bd355ade7fa99d">BTFExtSectionName</a>[] = ".BTF.ext"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/btf/commontype">BTF::CommonType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76290302f77ba5ad11e9690f8e1b7412">VoidTypeInst</a> = {0, BTF::BTF_KIND_UNKN &lt;&lt; 24, {0}}</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"debug-<a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>-btf-parser"</td>
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


<div class="doxySectionDef">

## Enumerations

### RelocKindGroup {#ad1f539052870283fcdc5d6d8738b4866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum RelocKindGroup </td>
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
<td class="doxyEnumItemName">RKG_FIELD<a id="ad1f539052870283fcdc5d6d8738b4866acc13564197bcfd6980df146c028ce6ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RKG_TYPE<a id="ad1f539052870283fcdc5d6d8738b4866acee34196dfb8f9ceda266fefb3b80273"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RKG_ENUMVAL<a id="ad1f539052870283fcdc5d6d8738b4866aa1818511bb07cfa5dde2bf0c0b3491e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RKG_UNKNOWN<a id="ad1f539052870283fcdc5d6d8738b4866a3921aa4445f880f28ec8e6e3b76e0e02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### byteSize() {#a59534c1e1daba811d6792180bb6b5905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t byteSize (<a href="/web-llvm/docs/api/structs/llvm/btf/commontype">BTF::CommonType</a> * Type)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### findInfo() {#ac835023c2f2a4fbe350567206319f0bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * findInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; T, 0 &gt; &gt; &amp; SecMap, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">SectionedAddress</a> Address)</td>
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



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#adef13fb32642b46e7e46357ca7325c4e">llvm::BTFParser::findFieldReloc</a> and <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a5729622535e0781d033722c4684994c6">llvm::BTFParser::findLineInfo</a>.</p>

</div>
</div>

### isMod() {#a9a20b9452e061c8b67f5ffcaeadc501d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/btf/commontype">BTF::CommonType</a> * Type)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>Referenced by <a href="#acc5b9e0eef6fe127531ff21cdf4a4320">skipModsAndTypedefs</a>.</p>

</div>
</div>

### printMod() {#a6ac0573ec9ff64b7c46d893994892cc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool printMod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/btfparser">BTFParser</a> &amp; BTF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/btf/commontype">BTF::CommonType</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Stream)</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>.</p>

</div>
</div>

### relocKindGroup() {#a21b3de8cc0d131e00cd6d83fb3545921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RelocKindGroup relocKindGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/btf/bpffieldreloc">BTF::BPFFieldReloc</a> * Reloc)</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ad68d76b71372e215deecb4c8ed3270c2">llvm::BTF::BTF_TYPE_ID_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799acbb290538d39cb27fb3cc388297b226b">llvm::BTF::BTF_TYPE_ID_REMOTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a371669db5e8b461d1cfa6c3c4a58ac60">llvm::BTF::ENUM_VALUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ab96e1ec4defd44b7cf6d64d2154eeb8a">llvm::BTF::ENUM_VALUE_EXISTENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a65537ca629fc55c1cb58287b73d352b5">llvm::BTF::FIELD_BYTE_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799aa7ed9c11a74d7d89fd613edd59aa09a7">llvm::BTF::FIELD_BYTE_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799af20ac25cf46638e7e25a14ec2df08ef6">llvm::BTF::FIELD_EXISTENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799adebd77ac95d260fd74b6b7d5af076808">llvm::BTF::FIELD_LSHIFT_U64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a0ba30ef232f9881a53f6f66295926e2f">llvm::BTF::FIELD_RSHIFT_U64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a371ef25f16d59edde27ea1418bbd5425">llvm::BTF::FIELD_SIGNEDNESS</a>, <a href="#ad1f539052870283fcdc5d6d8738b4866aa1818511bb07cfa5dde2bf0c0b3491e6">RKG_ENUMVAL</a>, <a href="#ad1f539052870283fcdc5d6d8738b4866acc13564197bcfd6980df146c028ce6ef">RKG_FIELD</a>, <a href="#ad1f539052870283fcdc5d6d8738b4866acee34196dfb8f9ceda266fefb3b80273">RKG_TYPE</a>, <a href="#ad1f539052870283fcdc5d6d8738b4866a3921aa4445f880f28ec8e6e3b76e0e02">RKG_UNKNOWN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ad5e3f2784be9365b4b1e4ea9f7ed7577">llvm::BTF::TYPE_EXISTENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ae1b7461f572b33b7261159c8546dd7ac">llvm::BTF::TYPE_MATCH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799aeb14048b6ba0696f38cf4a87744413d5">llvm::BTF::TYPE_SIZE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>.</p>

</div>
</div>

### relocKindName() {#ab45afa179ec726532c135c2a22018698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void relocKindName (uint32_t X, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ad68d76b71372e215deecb4c8ed3270c2">llvm::BTF::BTF_TYPE_ID_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799acbb290538d39cb27fb3cc388297b226b">llvm::BTF::BTF_TYPE_ID_REMOTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a371669db5e8b461d1cfa6c3c4a58ac60">llvm::BTF::ENUM_VALUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ab96e1ec4defd44b7cf6d64d2154eeb8a">llvm::BTF::ENUM_VALUE_EXISTENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a65537ca629fc55c1cb58287b73d352b5">llvm::BTF::FIELD_BYTE_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799aa7ed9c11a74d7d89fd613edd59aa09a7">llvm::BTF::FIELD_BYTE_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799af20ac25cf46638e7e25a14ec2df08ef6">llvm::BTF::FIELD_EXISTENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799adebd77ac95d260fd74b6b7d5af076808">llvm::BTF::FIELD_LSHIFT_U64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a0ba30ef232f9881a53f6f66295926e2f">llvm::BTF::FIELD_RSHIFT_U64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799a371ef25f16d59edde27ea1418bbd5425">llvm::BTF::FIELD_SIGNEDNESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ad5e3f2784be9365b4b1e4ea9f7ed7577">llvm::BTF::TYPE_EXISTENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ae1b7461f572b33b7261159c8546dd7ac">llvm::BTF::TYPE_MATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799aeb14048b6ba0696f38cf4a87744413d5">llvm::BTF::TYPE_SIZE</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>.</p>

</div>
</div>

### skipModsAndTypedefs() {#acc5b9e0eef6fe127531ff21cdf4a4320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BTF::CommonType * skipModsAndTypedefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/btfparser">BTFParser</a> &amp; BTF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/btf/commontype">BTF::CommonType</a> * Type)</td>
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



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#a9a20b9452e061c8b67f5ffcaeadc501d">isMod</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BTFExtSectionName {#aa7f4e549975547fd95bd355ade7fa99d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char BTFExtSectionName[] = ".BTF.ext"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#ad79aeb0e88860433b5085bcae9006bbd">llvm::BTFParser::hasBTFSections</a> and <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a4c7c5e28bb5767c6be05394c38ab0d21">llvm::BTFParser::parse</a>.</p>

</div>
</div>

### BTFSectionName {#a9dbdbafb8b8f310ebdd7bf5d4bcc0edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char BTFSectionName[] = ".BTF"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#ad79aeb0e88860433b5085bcae9006bbd">llvm::BTFParser::hasBTFSections</a> and <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a4c7c5e28bb5767c6be05394c38ab0d21">llvm::BTFParser::parse</a>.</p>

</div>
</div>

### VoidTypeInst {#a76290302f77ba5ad11e9690f8e1b7412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BTF::CommonType VoidTypeInst = {0, BTF::BTF_KIND_UNKN &lt;&lt; 24, {0}}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"debug-<a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>-btf-parser"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp">BTFParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
