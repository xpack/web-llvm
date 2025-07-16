---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbolxcoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSymbolXCOFF` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbolXCOFF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">llvm/MC/MCSymbolXCOFF.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">XCOFFSymbolFlags : uint16_t { <a href="#a75d754d48124f7c32c231cb0eb63f09e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CodeModel : uint8_t { <a href="#a5ef9bbf615c9136516bbdff6b4749a63">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1a8a60db1ccd5a95705b427ca23733">MCSymbolXCOFF</a> (const MCSymbolTableEntry *Name, bool isTemporary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6b554211ae5a568103156c1104155b">setStorageClass</a> (XCOFF::StorageClass SC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7d41d72dd0aeafa71928a5bf76ccd1">getStorageClass</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdf9e06b3bfdbe3a419b71ee19fc753">getUnqualifiedName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe94030c5621c1bedda2ec43510dac28">getRepresentedCsect</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693e90ee238ffff82ab04868fd031770">setRepresentedCsect</a> (MCSectionXCOFF *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f3dd791789ba757ad8a5d380920bad">setVisibilityType</a> (XCOFF::VisibilityType SVT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73e">XCOFF::VisibilityType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056f7790e0ee8bf43c57ee8119b90d95">getVisibilityType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e316bff70880cf511b6790ab29ad1d">hasRename</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f00cb351329db16b28f1667020615f4">setSymbolTableName</a> (StringRef STN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29896ac9b731b80cfb021fb432b73d7d">getSymbolTableName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6397be1a70c3c747af829c3d590e329d">isEHInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f40a63f3dc40a07df172bebf7eb98c">setEHInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3010d5888201be4274e1b80d16eb77f4">hasPerSymbolCodeModel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5ef9bbf615c9136516bbdff6b4749a63">CodeModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d630f0a9c4b8acf156da5c42f0d3cf7">getPerSymbolCodeModel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3475f9c6a708f0f5b9a3fd41d2b655">setPerSymbolCodeModel</a> (MCSymbolXCOFF::CodeModel Model)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a52f773563f3bf374c9089b51f3d42">StorageClass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a5ef9bbf615c9136516bbdff6b4749a63">CodeModel</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1b5dba6aa2a48ab15955ccb5d2e4cf">PerSymbolCodeModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88d37ecd390eb302311a4e2b3a7e019">RepresentedCsect</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73e">XCOFF::VisibilityType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4693065a0e45df1fe6df37aef9eb5f58">VisibilityType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73ead0a12244f2c9383cf63c7e8ced746bdd">XCOFF::SYM_V_UNSPECIFIED</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a7286442a96e269059546eb266d5b0">SymbolTableName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93b69a2d3a61fc8e16134bfee12ef3f">HasRename</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a0eb104e53ad194da0dcc598b63bb2">classof</a> (const MCSymbol *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8c201e99f1acf8f6cdc654093c0a61">getUnqualifiedName</a> (StringRef Name)</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### CodeModel {#a5ef9bbf615c9136516bbdff6b4749a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSymbolXCOFF::CodeModel : uint8_t</td>
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
<td class="doxyEnumItemName">CM_Small<a id="a5ef9bbf615c9136516bbdff6b4749a63a640a76fdf20143530026cdb07f15d055"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_Large<a id="a5ef9bbf615c9136516bbdff6b4749a63a70dbe554aa66c75d8d5053a94d9dde5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### XCOFFSymbolFlags {#a75d754d48124f7c32c231cb0eb63f09e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSymbolXCOFF::XCOFFSymbolFlags : uint16_t</td>
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
<td class="doxyEnumItemName">SF_EHInfo<a id="a75d754d48124f7c32c231cb0eb63f09ead1565b68e8e906f9b29fe24739922bb6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0001)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCSymbolXCOFF() {#a2c1a8a60db1ccd5a95705b427ca23733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbolXCOFF::MCSymbolXCOFF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool isTemporary)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab8dab642726ffad2a75d9fb7e4ec4291a481f422e7c0ce93801f9be23c44f6fe2">llvm::MCSymbol::SymbolKindXCOFF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPerSymbolCodeModel() {#a4d630f0a9c4b8acf156da5c42f0d3cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeModel llvm::MCSymbolXCOFF::getPerSymbolCodeModel ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3010d5888201be4274e1b80d16eb77f4">hasPerSymbolCodeModel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a24e99c9fbb9fedd3a9b504d09ddfa21b">llvm::TargetLoweringObjectFileXCOFF::getSectionForTOCEntry</a>.</p>

</div>
</div>

### getRepresentedCsect() {#afe94030c5621c1bedda2ec43510dac28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionXCOFF * MCSymbolXCOFF::getRepresentedCsect ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>, definition at line 13 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolxcoff-cpp">MCSymbolXCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a29896ac9b731b80cfb021fb432b73d7d">getSymbolTableName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a99b84e083c8b17e6af277efb72bc6fa0">anonymous{XCOFFObjectWriter.cpp}::getContainingCsect</a>.</p>

</div>
</div>

### getStorageClass() {#a2e7d41d72dd0aeafa71928a5bf76ccd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::StorageClass llvm::MCSymbolXCOFF::getStorageClass ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getSymbolTableName() {#a29896ac9b731b80cfb021fb432b73d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbolXCOFF::getSymbolTableName ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>References <a href="#adcdf9e06b3bfdbe3a419b71ee19fc753">getUnqualifiedName</a> and <a href="#a37e316bff70880cf511b6790ab29ad1d">hasRename</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7cd6d58462a0ebf3fa2c3d1423b0e2c6">llvm::AsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a53cb03e5a5afb8080089249f461f141e">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer/#a0c4536e911b01c1a6f0ab8ed2a62bf16">anonymous{PPCMCTargetDesc.cpp}::PPCTargetAsmStreamer::emitTCEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2d3b4a12c2fbc688388c6c2b422f8e88">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitXCOFFLocalCommonSymbol</a>, <a href="#afe94030c5621c1bedda2ec43510dac28">getRepresentedCsect</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a24e99c9fbb9fedd3a9b504d09ddfa21b">llvm::TargetLoweringObjectFileXCOFF::getSectionForTOCEntry</a> and <a href="#a693e90ee238ffff82ab04868fd031770">setRepresentedCsect</a>.</p>

</div>
</div>

### getUnqualifiedName() {#adcdf9e06b3bfdbe3a419b71ee19fc753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbolXCOFF::getUnqualifiedName ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a> and <a href="#adcdf9e06b3bfdbe3a419b71ee19fc753">getUnqualifiedName</a>.</p>


<p>Referenced by <a href="#a29896ac9b731b80cfb021fb432b73d7d">getSymbolTableName</a> and <a href="#adcdf9e06b3bfdbe3a419b71ee19fc753">getUnqualifiedName</a>.</p>

</div>
</div>

### getVisibilityType() {#a056f7790e0ee8bf43c57ee8119b90d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::VisibilityType llvm::MCSymbolXCOFF::getVisibilityType ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### hasPerSymbolCodeModel() {#a3010d5888201be4274e1b80d16eb77f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolXCOFF::hasPerSymbolCodeModel ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>Referenced by <a href="#a4d630f0a9c4b8acf156da5c42f0d3cf7">getPerSymbolCodeModel</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a24e99c9fbb9fedd3a9b504d09ddfa21b">llvm::TargetLoweringObjectFileXCOFF::getSectionForTOCEntry</a>.</p>

</div>
</div>

### hasRename() {#a37e316bff70880cf511b6790ab29ad1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolXCOFF::hasRename ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7cd6d58462a0ebf3fa2c3d1423b0e2c6">llvm::AsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a53cb03e5a5afb8080089249f461f141e">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer/#a0c4536e911b01c1a6f0ab8ed2a62bf16">anonymous{PPCMCTargetDesc.cpp}::PPCTargetAsmStreamer::emitTCEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2d3b4a12c2fbc688388c6c2b422f8e88">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitXCOFFLocalCommonSymbol</a> and <a href="#a29896ac9b731b80cfb021fb432b73d7d">getSymbolTableName</a>.</p>

</div>
</div>

### isEHInfo() {#a6397be1a70c3c747af829c3d590e329d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolXCOFF::isEHInfo ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a24e99c9fbb9fedd3a9b504d09ddfa21b">llvm::TargetLoweringObjectFileXCOFF::getSectionForTOCEntry</a>.</p>

</div>
</div>

### setEHInfo() {#a49f40a63f3dc40a07df172bebf7eb98c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolXCOFF::setEHInfo ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setPerSymbolCodeModel() {#a8a3475f9c6a708f0f5b9a3fd41d2b655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolXCOFF::setPerSymbolCodeModel (<a href="#a5ef9bbf615c9136516bbdff6b4749a63">MCSymbolXCOFF::CodeModel</a> Model)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a59e65916783e5d7fcab8e5004ca5063e">setOptionalCodeModel</a>.</p>

</div>
</div>

### setRepresentedCsect() {#a693e90ee238ffff82ab04868fd031770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSymbolXCOFF::setRepresentedCsect (<a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolxcoff-cpp">MCSymbolXCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a29896ac9b731b80cfb021fb432b73d7d">getSymbolTableName</a>.</p>

</div>
</div>

### setStorageClass() {#aba6b554211ae5a568103156c1104155b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolXCOFF::setStorageClass (<a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a> SC)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### setSymbolTableName() {#a6f00cb351329db16b28f1667020615f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolXCOFF::setSymbolTableName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> STN)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### setVisibilityType() {#a37f3dd791789ba757ad8a5d380920bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolXCOFF::setVisibilityType (<a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73e">XCOFF::VisibilityType</a> SVT)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasRename {#aa93b69a2d3a61fc8e16134bfee12ef3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolXCOFF::HasRename = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### PerSymbolCodeModel {#a0f1b5dba6aa2a48ab15955ccb5d2e4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CodeModel&gt; llvm::MCSymbolXCOFF::PerSymbolCodeModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### RepresentedCsect {#af88d37ecd390eb302311a4e2b3a7e019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionXCOFF* llvm::MCSymbolXCOFF::RepresentedCsect = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### StorageClass {#a99a52f773563f3bf374c9089b51f3d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;XCOFF::StorageClass&gt; llvm::MCSymbolXCOFF::StorageClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### SymbolTableName {#a52a7286442a96e269059546eb266d5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbolXCOFF::SymbolTableName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

### VisibilityType {#a4693065a0e45df1fe6df37aef9eb5f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::VisibilityType llvm::MCSymbolXCOFF::VisibilityType = <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73ead0a12244f2c9383cf63c7e8ced746bdd">XCOFF::SYM_V_UNSPECIFIED</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a08a0eb104e53ad194da0dcc598b63bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolXCOFF::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ae7f37b1f48f732756d82ca7a2b2a1beb">llvm::MCSymbol::isXCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a>.</p>

</div>
</div>

### getUnqualifiedName() {#a6a8c201e99f1acf8f6cdc654093c0a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbolXCOFF::getUnqualifiedName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">MCSymbolXCOFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolxcoff-cpp">MCSymbolXCOFF.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
