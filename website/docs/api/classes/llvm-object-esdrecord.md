---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/esdrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ESDRecord` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::ESDRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">llvm/Object/GOFF.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/record">Record</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a <a href="/web-llvm/docs/api/namespaces/llvm/goff">GOFF</a> physical record. <a href="/web-llvm/docs/api/classes/llvm/object/record/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41be86591fdf189a06549d4f79778363">getData</a> (const uint8_t *Record, SmallString&lt; 256 &gt; &amp;CompleteData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f69c62cb368a82f813d20559b771afd">getSymbolType</a> (const uint8_t *Record, GOFF::ESDSymbolType &amp;SymbolType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d2201cdad88bd4981c06028e8b4c87a">getEsdId</a> (const uint8_t *Record, uint32_t &amp;EsdId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89665782cf8d112a3547acdc66cc0a1c">getParentEsdId</a> (const uint8_t *Record, uint32_t &amp;EsdId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20245bf07f26c7c93be4aa8707e1a27b">getOffset</a> (const uint8_t *Record, uint32_t &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2b4d5d089d12bb5f0e83ed0f37e28c">getLength</a> (const uint8_t *Record, uint32_t &amp;Length)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76249510a3813e5688338c252b271d5">getNameSpaceId</a> (const uint8_t *Record, GOFF::ESDNameSpaceId &amp;Id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a445dd802984ef710b1ccaf5a5ada2b8f">getFillBytePresent</a> (const uint8_t *Record, bool &amp;Present)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e6bf13951edb895a30fd3beab7fcce">getNameMangled</a> (const uint8_t *Record, bool &amp;Mangled)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af40849e67ad6b5f296a7b695e5d06fbe">getRenamable</a> (const uint8_t *Record, bool &amp;Renamable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea77b214dc8f83c7edf8b7db1666c269">getRemovable</a> (const uint8_t *Record, bool &amp;Removable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8a9f52f85cbdbbbb9f3f30ec001460">getFillByteValue</a> (const uint8_t *Record, uint8_t &amp;Fill)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a516f3f99075b03a2827823a26d20a0f4">getAdaEsdId</a> (const uint8_t *Record, uint32_t &amp;EsdId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f484a3f5cbdee1f8208afcc1b12038c">getSortPriority</a> (const uint8_t *Record, uint32_t &amp;Priority)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6858cfaa9e9d289d7a4134a204c90089">getAmode</a> (const uint8_t *Record, GOFF::ESDAmode &amp;Amode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eea7ffc710777d6561cda7a5e4f8c57">getRmode</a> (const uint8_t *Record, GOFF::ESDRmode &amp;Rmode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e6ab7ae3094d97a45352feb7dc7758">getTextStyle</a> (const uint8_t *Record, GOFF::ESDTextStyle &amp;Style)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597ed0b588d19008d10c83ff5ee5ef88">getBindingAlgorithm</a> (const uint8_t *Record, GOFF::ESDBindingAlgorithm &amp;Algorithm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4258b2abc2bf3967873ba3d9ce436303">getTaskingBehavior</a> (const uint8_t *Record, GOFF::ESDTaskingBehavior &amp;TaskingBehavior)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c2fb6f2f3b28850625cb896809b4e5a">getReadOnly</a> (const uint8_t *Record, bool &amp;ReadOnly)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7266dc4718ccfa5af3e1e34ba75fd3d">getExecutable</a> (const uint8_t *Record, GOFF::ESDExecutable &amp;Executable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249517638648cd2af36d179fa0c603ba">getDuplicateSeverity</a> (const uint8_t *Record, GOFF::ESDDuplicateSymbolSeverity &amp;DSS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10feb91fb4edb2fa3e1e4bc1e219be35">getBindingStrength</a> (const uint8_t *Record, GOFF::ESDBindingStrength &amp;Strength)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f871ae083a28c89da507e24096e77a2">getLoadingBehavior</a> (const uint8_t *Record, GOFF::ESDLoadingBehavior &amp;Behavior)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071c9b7f13b2e3a77ea1939a6d2b0f54">getIndirectReference</a> (const uint8_t *Record, bool &amp;Indirect)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96e2aa558f44e2345459cf2492944a3">getBindingScope</a> (const uint8_t *Record, GOFF::ESDBindingScope &amp;Scope)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa762348109ffca6f7c3564c26659ecb2">getLinkageType</a> (const uint8_t *Record, GOFF::ESDLinkageType &amp;Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f23fb26bc4072fd103b50f0a4053fb">getAlignment</a> (const uint8_t *Record, GOFF::ESDAlignment &amp;Alignment)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9aaf80f8b8b1af0fa63cd19126f2a2b">getNameLength</a> (const uint8_t *Record)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa936176b8bea6d8ea58203389007d068">ESDMaxUncontinuedNameLength</a> = 8</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of bytes for name; any more must go in continuation. <a href="#aa936176b8bea6d8ea58203389007d068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f124a7c988d0a2f0fac4fd708f2506">MaxNameLength</a> = 32 * 1024</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum name length for ESD records and continuations. <a href="#a77f124a7c988d0a2f0fac4fd708f2506">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getAdaEsdId() {#a516f3f99075b03a2827823a26d20a0f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getAdaEsdId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint32_t &amp; EsdId)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>

</div>
</div>

### getAlignment() {#aa5f23fb26bc4072fd103b50f0a4053fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a60e042e85a921167b7eafc40ea8d01c8">GOFF::ESDAlignment</a> &amp; Alignment)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getAmode() {#a6858cfaa9e9d289d7a4134a204c90089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getAmode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a7476f23b4baa1e04abd0b8027430e60b">GOFF::ESDAmode</a> &amp; Amode)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>

</div>
</div>

### getBindingAlgorithm() {#a597ed0b588d19008d10c83ff5ee5ef88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getBindingAlgorithm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a1a2cc71bb9d87d0a400363fbd7c58a54">GOFF::ESDBindingAlgorithm</a> &amp; Algorithm)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getBindingScope() {#ac96e2aa558f44e2345459cf2492944a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getBindingScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a7cf849181299799ef59693a574f4f159">GOFF::ESDBindingScope</a> &amp; Scope)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getBindingStrength() {#a10feb91fb4edb2fa3e1e4bc1e219be35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getBindingStrength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#ae8b8f71c9c63a3ec241f496db20f6fee">GOFF::ESDBindingStrength</a> &amp; Strength)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getData() {#a41be86591fdf189a06549d4f79778363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ESDRecord::getData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 256 &gt; &amp; CompleteData)</td>
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



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/object/goffobjectfile-cpp">GOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/record/#a68447fd5872ee1b7ff3b7bd7d39e0077">llvm::object::Record::getContinuousData</a> and <a href="#aa9aaf80f8b8b1af0fa63cd19126f2a2b">getNameLength</a>.</p>

</div>
</div>

### getDuplicateSeverity() {#a249517638648cd2af36d179fa0c603ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getDuplicateSeverity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a1e50db0c64f34cae10b47b8546db9965">GOFF::ESDDuplicateSymbolSeverity</a> &amp; DSS)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getEsdId() {#a3d2201cdad88bd4981c06028e8b4c87a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getEsdId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint32_t &amp; EsdId)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a3b3a59937edbc6f58ff06abe51ce621f">llvm::object::GOFFObjectFile::GOFFObjectFile</a>.</p>

</div>
</div>

### getExecutable() {#ac7266dc4718ccfa5af3e1e34ba75fd3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getExecutable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a4933550171684a52cb5aa6313d49d0c5">GOFF::ESDExecutable</a> &amp; Executable)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getFillBytePresent() {#a445dd802984ef710b1ccaf5a5ada2b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getFillBytePresent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, bool &amp; Present)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getFillByteValue() {#a8b8a9f52f85cbdbbbb9f3f30ec001460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getFillByteValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint8_t &amp; Fill)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>

</div>
</div>

### getIndirectReference() {#a071c9b7f13b2e3a77ea1939a6d2b0f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getIndirectReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, bool &amp; Indirect)</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getLength() {#a4c2b4d5d089d12bb5f0e83ed0f37e28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint32_t &amp; Length)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a3b3a59937edbc6f58ff06abe51ce621f">llvm::object::GOFFObjectFile::GOFFObjectFile</a>.</p>

</div>
</div>

### getLinkageType() {#aa762348109ffca6f7c3564c26659ecb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getLinkageType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a964f795216d46d29fb7f202b2906e445">GOFF::ESDLinkageType</a> &amp; Type)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getLoadingBehavior() {#a3f871ae083a28c89da507e24096e77a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getLoadingBehavior (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a079279c714f0f26248898ed727d238b0">GOFF::ESDLoadingBehavior</a> &amp; Behavior)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a855362ac17f1c442082771c3fd112dab">llvm::object::GOFFObjectFile::isSectionNoLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a64a97f0250f312802e03ad774dec91c3">llvm::object::GOFFObjectFile::isSectionReadOnlyData</a>.</p>

</div>
</div>

### getNameLength() {#aa9aaf80f8b8b1af0fa63cd19126f2a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::ESDRecord::getNameLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="#a41be86591fdf189a06549d4f79778363">getData</a>.</p>

</div>
</div>

### getNameMangled() {#a41e6bf13951edb895a30fd3beab7fcce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getNameMangled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, bool &amp; Mangled)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getNameSpaceId() {#ad76249510a3813e5688338c252b271d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getNameSpaceId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#aa06368da948b8fc7d53d9d38e9de12d3">GOFF::ESDNameSpaceId</a> &amp; Id)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>

</div>
</div>

### getOffset() {#a20245bf07f26c7c93be4aa8707e1a27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint32_t &amp; Offset)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getParentEsdId() {#a89665782cf8d112a3547acdc66cc0a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getParentEsdId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint32_t &amp; EsdId)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a3b3a59937edbc6f58ff06abe51ce621f">llvm::object::GOFFObjectFile::GOFFObjectFile</a>.</p>

</div>
</div>

### getReadOnly() {#a7c2fb6f2f3b28850625cb896809b4e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getReadOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, bool &amp; ReadOnly)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getRemovable() {#aea77b214dc8f83c7edf8b7db1666c269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getRemovable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, bool &amp; Removable)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getRenamable() {#af40849e67ad6b5f296a7b695e5d06fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getRenamable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, bool &amp; Renamable)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getRmode() {#a7eea7ffc710777d6561cda7a5e4f8c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getRmode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#afc8c8c26be7cc7ae8a484cdcc138962d">GOFF::ESDRmode</a> &amp; Rmode)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>

</div>
</div>

### getSortPriority() {#a7f484a3f5cbdee1f8208afcc1b12038c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getSortPriority (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint32_t &amp; Priority)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>

</div>
</div>

### getSymbolType() {#a8f69c62cb368a82f813d20559b771afd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getSymbolType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#aa230a619fca0943af5d9715621ddf536">GOFF::ESDSymbolType</a> &amp; SymbolType)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a3b3a59937edbc6f58ff06abe51ce621f">llvm::object::GOFFObjectFile::GOFFObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#ab57c2fa773cd18a175133ac8598e9466">llvm::object::GOFFObjectFile::moveSymbolNext</a>.</p>

</div>
</div>

### getTaskingBehavior() {#a4258b2abc2bf3967873ba3d9ce436303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getTaskingBehavior (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#ac1617e3b17ea3df4374129abf2996af5">GOFF::ESDTaskingBehavior</a> &amp; TaskingBehavior)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

### getTextStyle() {#aa2e6ab7ae3094d97a45352feb7dc7758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ESDRecord::getTextStyle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a48b496176726b7e568930b70ccd8ec95">GOFF::ESDTextStyle</a> &amp; Style)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/record/#a621bf457e53725ae30708875b8d33bec">llvm::object::Record::getBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ESDMaxUncontinuedNameLength {#aa936176b8bea6d8ea58203389007d068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::object::ESDRecord::ESDMaxUncontinuedNameLength = 8</td>
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

<p>Number of bytes for name; any more must go in continuation.</p>


<p>This is the number of bytes that can fit into the data field of an ESD record.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>

</div>
</div>

### MaxNameLength {#a77f124a7c988d0a2f0fac4fd708f2506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t llvm::object::ESDRecord::MaxNameLength = 32 * 1024</td>
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

<p>Maximum name length for ESD records and continuations.</p>


<p>This is the number of bytes that can fit into the data field of an ESD record AND following continuations. This is limited fundamentally by the 16 bit SIGNED length field.</p>


<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/goffobjectfile-cpp">GOFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
