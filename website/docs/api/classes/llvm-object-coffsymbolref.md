---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/coffsymbolref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `COFFSymbolRef` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::COFFSymbolRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">llvm/Object/COFF.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abece214d042acbbc5284dc7566036c10">operator&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73bcbf0efd993e6aaff146923779983a">COFFSymbolRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97219e5af7274b84dbc7b14e620cba05">COFFSymbolRef</a> (const coff_symbol16 *CS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918a5395f2ac3eee6593a189bd7da114">COFFSymbolRef</a> (const coff_symbol32 *CS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215579b7e283e1a7e5649ad2c920e759">getRawPtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol-generic">coff_symbol_generic</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572a6e8712921bb0feb5843937877d24">getGeneric</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e6f38a9fb6968e99c6d0377776bfed">isBigObj</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb95d394c5f892cd044a1f4f9f4cbf3">getShortName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/stringtableoffset">StringTableOffset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35605d81dc4250aa7865c43aec44435d">getStringTableOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9755c11be296a4d3996014d880d4c3dd">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70cf7d54eb4ea803070fb903b70f44a">getSectionNumber</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf0d1f6f9eaf6f8e82b20ced4d137c6">getType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880e75aa151448139ea0c1b40fdaf09d">getNumberOfAuxSymbols</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9042df1ad103854552b4238ef810cec3">getBaseType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec08367bd94557ab660f9cdc10c13d3">getComplexType</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4136732b1574a1c950fcae4ed9334324">getAux</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-aux-section-definition">coff_aux_section_definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fbac004e62ecd6320be96b675f8472">getSectionDefinition</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-aux-weak-external">coff_aux_weak_external</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb9fdbd29003eae3fc725811e1072ee">getWeakExternal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f36f36481c2f0d5e8944fd514dbe177">isAbsolute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d5e578e07f26182eb80baa40b0fb6b">isExternal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf643940dab065e103dc6ef89b72e6c">isCommon</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed332f322ba151963ef7b9a82dd8c3e1">isUndefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6280349c25f1f22bbd619a3cf74acb5">isEmptySectionDeclaration</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3afda36f986ddb7d576aae27f4eaedf">isWeakExternal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af159b14a7d582be8e8cb74ed2496cace">isFunctionDefinition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cce049f3d490d8a85ec34be92f96351">isFunctionLineInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c74b387289140daf762aea822346deb">isAnyUndefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5531a06cc2e1063806db2bfa1cb31dd3">isFileRecord</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac918986bf9717a2be13ffbeeb9fafc9a">isSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67dd1972b87a5c8ccd3bf1fa4a9dd503">isSectionDefinition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad759fca3ddc68a7cae83f22044ef8a2f">isCLRToken</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0283ca37a32b832b819638d0c80ac7">isSet</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#a918bb801731475346a494b06e8f805cb">coff_symbol16</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3ea40dd496234a8be1130ad36c74b5">CS16</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#ac44385f777f6fb07e4cccf738f832ded">coff_symbol32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652f9dded152f7c9fc6b3832e4c354c2">CS32</a> = nullptr</td>
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


<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt; {#abece214d042acbbc5284dc7566036c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a> A, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a> B</td>
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


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a73bcbf0efd993e6aaff146923779983a">COFFSymbolRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### COFFSymbolRef() {#a73bcbf0efd993e6aaff146923779983a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::COFFSymbolRef::COFFSymbolRef ()</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#abece214d042acbbc5284dc7566036c10">operator&lt;</a>.</p>

</div>
</div>

### COFFSymbolRef() {#a97219e5af7274b84dbc7b14e620cba05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::COFFSymbolRef::COFFSymbolRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#a918bb801731475346a494b06e8f805cb">coff_symbol16</a> * CS)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### COFFSymbolRef() {#a918a5395f2ac3eee6593a189bd7da114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::COFFSymbolRef::COFFSymbolRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#ac44385f777f6fb07e4cccf738f832ded">coff_symbol32</a> * CS)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAux() {#a4136732b1574a1c950fcae4ed9334324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * llvm::object::COFFSymbolRef::getAux ()</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a99fbac004e62ecd6320be96b675f8472">getSectionDefinition</a> and <a href="#a5cb9fdbd29003eae3fc725811e1072ee">getWeakExternal</a>.</p>

</div>
</div>

### getBaseType() {#a9042df1ad103854552b4238ef810cec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::COFFSymbolRef::getBaseType ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#a3bf0d1f6f9eaf6f8e82b20ced4d137c6">getType</a>.</p>


<p>Referenced by <a href="#af159b14a7d582be8e8cb74ed2496cace">isFunctionDefinition</a>.</p>

</div>
</div>

### getComplexType() {#a6ec08367bd94557ab660f9cdc10c13d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::COFFSymbolRef::getComplexType ()</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a3bf0d1f6f9eaf6f8e82b20ced4d137c6">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120af01942289377f5c52c8771699eea5144">llvm::COFF::SCT_COMPLEX_TYPE_SHIFT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a69eec3d86ee001dbdc76f0da1f84bb7a">llvm::object::COFFObjectFile::getSymbolType</a> and <a href="#af159b14a7d582be8e8cb74ed2496cace">isFunctionDefinition</a>.</p>

</div>
</div>

### getGeneric() {#a572a6e8712921bb0feb5843937877d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_symbol_generic * llvm::object::COFFSymbolRef::getGeneric ()</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getNumberOfAuxSymbols() {#a880e75aa151448139ea0c1b40fdaf09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::COFFSymbolRef::getNumberOfAuxSymbols ()</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a99fbac004e62ecd6320be96b675f8472">getSectionDefinition</a>, <a href="#a5cb9fdbd29003eae3fc725811e1072ee">getWeakExternal</a> and <a href="#a67dd1972b87a5c8ccd3bf1fa4a9dd503">isSectionDefinition</a>.</p>

</div>
</div>

### getRawPtr() {#a215579b7e283e1a7e5649ad2c920e759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * llvm::object::COFFSymbolRef::getRawPtr ()</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getSectionDefinition() {#a99fbac004e62ecd6320be96b675f8472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_aux_section_definition * llvm::object::COFFSymbolRef::getSectionDefinition ()</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a4136732b1574a1c950fcae4ed9334324">getAux</a>, <a href="#a880e75aa151448139ea0c1b40fdaf09d">getNumberOfAuxSymbols</a>, <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>.</p>

</div>
</div>

### getSectionNumber() {#ad70cf7d54eb4ea803070fb903b70f44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::object::COFFSymbolRef::getSectionNumber ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad3097c5eaf4198579c34562fd89a240e">llvm::COFF::MaxNumberOfSections16</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a62ace90d17446bf72452ac5df2d0cfbd">llvm::object::COFFObjectFile::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a2456423e9e3bb5ffdc0a75fa36dd16cf">llvm::object::COFFObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#adeefe77eeb81c0dfee4bb876927e90c8">llvm::object::COFFObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a69eec3d86ee001dbdc76f0da1f84bb7a">llvm::object::COFFObjectFile::getSymbolType</a>, <a href="#a5f36f36481c2f0d5e8944fd514dbe177">isAbsolute</a>, <a href="#a2bf643940dab065e103dc6ef89b72e6c">isCommon</a>, <a href="#ab6280349c25f1f22bbd619a3cf74acb5">isEmptySectionDeclaration</a>, <a href="#af159b14a7d582be8e8cb74ed2496cace">isFunctionDefinition</a>, <a href="#a67dd1972b87a5c8ccd3bf1fa4a9dd503">isSectionDefinition</a> and <a href="#aed332f322ba151963ef7b9a82dd8c3e1">isUndefined</a>.</p>

</div>
</div>

### getShortName() {#abfb95d394c5f892cd044a1f4f9f4cbf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::object::COFFSymbolRef::getShortName ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getStorageClass() {#a3bbf5cc2b119481ae9fa8f4401ffdeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::COFFSymbolRef::getStorageClass ()</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a99fbac004e62ecd6320be96b675f8472">getSectionDefinition</a>, <a href="#a5cb9fdbd29003eae3fc725811e1072ee">getWeakExternal</a>, <a href="#ad759fca3ddc68a7cae83f22044ef8a2f">isCLRToken</a>, <a href="#a88d5e578e07f26182eb80baa40b0fb6b">isExternal</a>, <a href="#a5531a06cc2e1063806db2bfa1cb31dd3">isFileRecord</a>, <a href="#a8cce049f3d490d8a85ec34be92f96351">isFunctionLineInfo</a>, <a href="#ac918986bf9717a2be13ffbeeb9fafc9a">isSection</a>, <a href="#a67dd1972b87a5c8ccd3bf1fa4a9dd503">isSectionDefinition</a> and <a href="#ab3afda36f986ddb7d576aae27f4eaedf">isWeakExternal</a>.</p>

</div>
</div>

### getStringTableOffset() {#a35605d81dc4250aa7865c43aec44435d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringTableOffset &amp; llvm::object::COFFSymbolRef::getStringTableOffset ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getType() {#a3bf0d1f6f9eaf6f8e82b20ced4d137c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::COFFSymbolRef::getType ()</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a9042df1ad103854552b4238ef810cec3">getBaseType</a> and <a href="#a6ec08367bd94557ab660f9cdc10c13d3">getComplexType</a>.</p>

</div>
</div>

### getValue() {#a9755c11be296a4d3996014d880d4c3dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFSymbolRef::getValue ()</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a3eb2d4c0f51994ad276c2d71c80df945">llvm::object::COFFObjectFile::getCommonSymbolSizeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a198eead1f3b968154aa768771921cff8">llvm::object::COFFObjectFile::getSymbolAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#acd96a74473063785a1531e8571ed229a">llvm::object::COFFObjectFile::getSymbolValueImpl</a>, <a href="#a2bf643940dab065e103dc6ef89b72e6c">isCommon</a> and <a href="#aed332f322ba151963ef7b9a82dd8c3e1">isUndefined</a>.</p>

</div>
</div>

### getWeakExternal() {#a5cb9fdbd29003eae3fc725811e1072ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_aux_weak_external * llvm::object::COFFSymbolRef::getWeakExternal ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a4136732b1574a1c950fcae4ed9334324">getAux</a>, <a href="#a880e75aa151448139ea0c1b40fdaf09d">getNumberOfAuxSymbols</a>, <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afbf31b8df4bc8375989d1e65af8c8925">llvm::COFF::IMAGE_SYM_CLASS_WEAK_EXTERNAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a>.</p>

</div>
</div>

### isAbsolute() {#a5f36f36481c2f0d5e8944fd514dbe177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isAbsolute ()</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#ad70cf7d54eb4ea803070fb903b70f44a">getSectionNumber</a>.</p>

</div>
</div>

### isAnyUndefined() {#a4c74b387289140daf762aea822346deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isAnyUndefined ()</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#aed332f322ba151963ef7b9a82dd8c3e1">isUndefined</a> and <a href="#ab3afda36f986ddb7d576aae27f4eaedf">isWeakExternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a62ace90d17446bf72452ac5df2d0cfbd">llvm::object::COFFObjectFile::getSymbolAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a69eec3d86ee001dbdc76f0da1f84bb7a">llvm::object::COFFObjectFile::getSymbolType</a>.</p>

</div>
</div>

### isBigObj() {#ae0e6f38a9fb6968e99c6d0377776bfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isBigObj ()</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isCLRToken() {#ad759fca3ddc68a7cae83f22044ef8a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isCLRToken ()</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115ad5966872b64708d88402fe0d74bdb439">llvm::COFF::IMAGE_SYM_CLASS_CLR_TOKEN</a>.</p>

</div>
</div>

### isCommon() {#a2bf643940dab065e103dc6ef89b72e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isCommon ()</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#ad70cf7d54eb4ea803070fb903b70f44a">getSectionNumber</a>, <a href="#a9755c11be296a4d3996014d880d4c3dd">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#af755df11820d1db4f001cafe15934336a90408b6dfbdb0ff3056161935ea0e1b2">llvm::COFF::IMAGE_SYM_UNDEFINED</a> and <a href="#a88d5e578e07f26182eb80baa40b0fb6b">isExternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a62ace90d17446bf72452ac5df2d0cfbd">llvm::object::COFFObjectFile::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a69eec3d86ee001dbdc76f0da1f84bb7a">llvm::object::COFFObjectFile::getSymbolType</a>.</p>

</div>
</div>

### isEmptySectionDeclaration() {#ab6280349c25f1f22bbd619a3cf74acb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isEmptySectionDeclaration ()</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#ad70cf7d54eb4ea803070fb903b70f44a">getSectionNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#af755df11820d1db4f001cafe15934336a90408b6dfbdb0ff3056161935ea0e1b2">llvm::COFF::IMAGE_SYM_UNDEFINED</a> and <a href="#ac918986bf9717a2be13ffbeeb9fafc9a">isSection</a>.</p>

</div>
</div>

### isExternal() {#a88d5e578e07f26182eb80baa40b0fb6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isExternal ()</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a8b4296b2d59a622e33b331345fc9507b">llvm::COFF::IMAGE_SYM_CLASS_EXTERNAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a>, <a href="#a2bf643940dab065e103dc6ef89b72e6c">isCommon</a>, <a href="#af159b14a7d582be8e8cb74ed2496cace">isFunctionDefinition</a> and <a href="#aed332f322ba151963ef7b9a82dd8c3e1">isUndefined</a>.</p>

</div>
</div>

### isFileRecord() {#a5531a06cc2e1063806db2bfa1cb31dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isFileRecord ()</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115ad0bd3e42b20fc51bfb3df4ece62c5b35">llvm::COFF::IMAGE_SYM_CLASS_FILE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a69eec3d86ee001dbdc76f0da1f84bb7a">llvm::object::COFFObjectFile::getSymbolType</a>.</p>

</div>
</div>

### isFunctionDefinition() {#af159b14a7d582be8e8cb74ed2496cace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isFunctionDefinition ()</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a9042df1ad103854552b4238ef810cec3">getBaseType</a>, <a href="#a6ec08367bd94557ab660f9cdc10c13d3">getComplexType</a>, <a href="#ad70cf7d54eb4ea803070fb903b70f44a">getSectionNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120aabbef750c1bc8143f79535ea20699385">llvm::COFF::IMAGE_SYM_DTYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae70d6ec501d52a8d624abd6e944a94f2a42fd3c0cc883414b77e63cdf35ac9929">llvm::COFF::IMAGE_SYM_TYPE_NULL</a>, <a href="#a88d5e578e07f26182eb80baa40b0fb6b">isExternal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad9fb8ab8eb623e9967c0788fc42b150f">llvm::COFF::isReservedSectionNumber</a>.</p>

</div>
</div>

### isFunctionLineInfo() {#a8cce049f3d490d8a85ec34be92f96351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isFunctionLineInfo ()</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a631c5f14c1f65d499fb949f84cbd59c2">llvm::COFF::IMAGE_SYM_CLASS_FUNCTION</a>.</p>

</div>
</div>

### isSection() {#ac918986bf9717a2be13ffbeeb9fafc9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isSection ()</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a45a16b5dd6e74cbfef8b2cb72dc418c4">llvm::COFF::IMAGE_SYM_CLASS_SECTION</a>.</p>


<p>Referenced by <a href="#ab6280349c25f1f22bbd619a3cf74acb5">isEmptySectionDeclaration</a>.</p>

</div>
</div>

### isSectionDefinition() {#a67dd1972b87a5c8ccd3bf1fa4a9dd503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isSectionDefinition ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a880e75aa151448139ea0c1b40fdaf09d">getNumberOfAuxSymbols</a>, <a href="#ad70cf7d54eb4ea803070fb903b70f44a">getSectionNumber</a>, <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#af755df11820d1db4f001cafe15934336aa262b1c9c4e4e4411eb76fb8818264b5">llvm::COFF::IMAGE_SYM_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a8b4296b2d59a622e33b331345fc9507b">llvm::COFF::IMAGE_SYM_CLASS_EXTERNAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a69eec3d86ee001dbdc76f0da1f84bb7a">llvm::object::COFFObjectFile::getSymbolType</a>.</p>

</div>
</div>

### isUndefined() {#aed332f322ba151963ef7b9a82dd8c3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isUndefined ()</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#ad70cf7d54eb4ea803070fb903b70f44a">getSectionNumber</a>, <a href="#a9755c11be296a4d3996014d880d4c3dd">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#af755df11820d1db4f001cafe15934336a90408b6dfbdb0ff3056161935ea0e1b2">llvm::COFF::IMAGE_SYM_UNDEFINED</a> and <a href="#a88d5e578e07f26182eb80baa40b0fb6b">isExternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a> and <a href="#a4c74b387289140daf762aea822346deb">isAnyUndefined</a>.</p>

</div>
</div>

### isWeakExternal() {#ab3afda36f986ddb7d576aae27f4eaedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isWeakExternal ()</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a3bbf5cc2b119481ae9fa8f4401ffdeab">getStorageClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afbf31b8df4bc8375989d1e65af8c8925">llvm::COFF::IMAGE_SYM_CLASS_WEAK_EXTERNAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a9eca68d4f7435b8b5ddb0d20c10bc690">llvm::object::COFFObjectFile::getSymbolFlags</a> and <a href="#a4c74b387289140daf762aea822346deb">isAnyUndefined</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isSet() {#a6f0283ca37a32b832b819638d0c80ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFSymbolRef::isSet ()</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CS16 {#aae3ea40dd496234a8be1130ad36c74b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_symbol16* llvm::object::COFFSymbolRef::CS16 = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### CS32 {#a652f9dded152f7c9fc6b3832e4c354c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_symbol32* llvm::object::COFFSymbolRef::CS32 = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
