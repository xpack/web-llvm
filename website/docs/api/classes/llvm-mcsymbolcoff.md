---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbolcoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCSymbolCOFF` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbolCOFF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">llvm/MC/MCSymbolCOFF.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> - Instances of this class represent a symbol name in the MC file, and MCSymbols are created and uniqued by the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> class. <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SymbolFlags : uint16_t { <a href="#a8aa4c5e745bae9e7fc430b4c1601ca11">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4bc9d94fbfd9e2b3135ea1b4dc3193">MCSymbolCOFF</a> (const MCSymbolTableEntry *Name, bool isTemporary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a719212db6cebe8b978ebc9c4c7d0625b">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c4747e9872c40666e2e6932dabc8d0">setType</a> (uint16_t Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af87b3ae59f6e6531a3c0cbc2aab544f6">getClass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff8aca2e0a127f3bf37e56c9dcaabaf">setClass</a> (uint16_t StorageClass) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coff/#ac437dcd9750980233a278c48d2515271">COFF::WeakExternalCharacteristics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37cdc599522d884c88461f88dc18ac2">getWeakExternalCharacteristics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6e7c88e67fc58206c665c3c4f498a1">setWeakExternalCharacteristics</a> (COFF::WeakExternalCharacteristics Characteristics) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238d8c4330bd8208af7c03ac2ac47117">setIsWeakExternal</a> (bool WeakExt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f99a95ef446233d0940b18a46321a88">isSafeSEH</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582f0e948a6c830817d56afcc5c8f4bc">setIsSafeSEH</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59544009286b4cd17ff9b8e565337683">Type</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This corresponds to the e_type field of the <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> symbol. <a href="#a59544009286b4cd17ff9b8e565337683">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d0b7232f2ca80fd124bbb752f0479e3">classof</a> (const MCSymbol *S)</td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SymbolFlags {#a8aa4c5e745bae9e7fc430b4c1601ca11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSymbolCOFF::SymbolFlags : uint16_t</td>
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
<td class="doxyEnumItemName">SF_ClassMask<a id="a8aa4c5e745bae9e7fc430b4c1601ca11afdafed25c2be4dfcb8b929a2cb1030ed"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00FF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ClassShift<a id="a8aa4c5e745bae9e7fc430b4c1601ca11a30ae3973bed706f9059d2ef949ec5262"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_SafeSEH<a id="a8aa4c5e745bae9e7fc430b4c1601ca11aedc5d650e2c3204b086df76cea168a1b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_WeakExternalCharacteristicsMask<a id="a8aa4c5e745bae9e7fc430b4c1601ca11a1a25e865f6739de1dadb37d87789b8f9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0E00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_WeakExternalCharacteristicsShift<a id="a8aa4c5e745bae9e7fc430b4c1601ca11a7c458a289744f59440259953b38914a0"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCSymbolCOFF() {#a9f4bc9d94fbfd9e2b3135ea1b4dc3193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbolCOFF::MCSymbolCOFF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool isTemporary)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab8dab642726ffad2a75d9fb7e4ec4291a031eff3517a3a7518e717cc1eb9c5b8c">llvm::MCSymbol::SymbolKindCOFF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getClass() {#af87b3ae59f6e6531a3c0cbc2aab544f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSymbolCOFF::getClass ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### getType() {#a719212db6cebe8b978ebc9c4c7d0625b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSymbolCOFF::getType ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>

</div>
</div>

### getWeakExternalCharacteristics() {#af37cdc599522d884c88461f88dc18ac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFF::WeakExternalCharacteristics llvm::MCSymbolCOFF::getWeakExternalCharacteristics ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### isSafeSEH() {#a8f99a95ef446233d0940b18a46321a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolCOFF::isSafeSEH ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>.</p>

</div>
</div>

### setClass() {#a8ff8aca2e0a127f3bf37e56c9dcaabaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolCOFF::setClass (uint16_t StorageClass)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setIsSafeSEH() {#a582f0e948a6c830817d56afcc5c8f4bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolCOFF::setIsSafeSEH ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>.</p>

</div>
</div>

### setIsWeakExternal() {#a238d8c4330bd8208af7c03ac2ac47117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolCOFF::setIsWeakExternal (bool WeakExt)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a14d6c7ed60ac780e10ebc636b6aeba3f">llvm::MCSymbol::IsWeakExternal</a>.</p>

</div>
</div>

### setType() {#a78c4747e9872c40666e2e6932dabc8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolCOFF::setType (uint16_t Ty)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>.</p>

</div>
</div>

### setWeakExternalCharacteristics() {#a2d6e7c88e67fc58206c665c3c4f498a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolCOFF::setWeakExternalCharacteristics (<a href="/web-llvm/docs/api/namespaces/llvm/coff/#ac437dcd9750980233a278c48d2515271">COFF::WeakExternalCharacteristics</a> Characteristics)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Type {#a59544009286b4cd17ff9b8e565337683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSymbolCOFF::Type = 0</td>
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

<p>This corresponds to the e_type field of the <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> symbol.</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8d0b7232f2ca80fd124bbb752f0479e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolCOFF::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a820696a7bde417a8827ec1a981968084">llvm::MCSymbol::isCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolcoff-h">MCSymbolCOFF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
