---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbolmacho
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSymbolMachO` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbolMachO { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">llvm/MC/MCSymbolMachO.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MachOSymbolFlags : uint16_t { <a href="#a415fa6175d6fb7b4de98dee1e7ebd0db">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We store the value for the 'desc' symbol field in the lowest 16 bits of the implementation defined flags. <a href="#a415fa6175d6fb7b4de98dee1e7ebd0db">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59262c6e30a690a5ab41dd3dce25fba3">MCSymbolMachO</a> (const MCSymbolTableEntry *Name, bool isTemporary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cf7f49f636f68568612d4d8175246c">isPrivateExtern</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afef6139b3e549e7a5a7d88990d4a23">setPrivateExtern</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c7b06ed26ba9de68ded30b76ed10ac2">clearReferenceType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d037272c9f203be545f70f27e74d06f">setReferenceTypeUndefinedLazy</a> (bool Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf4ea5a6029e7f7c4c450b6b31bcb55">setThumbFunc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b98b657efc7bbefc66eee331b727ef">isNoDeadStrip</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2be0f571f852febfb9eebb2430e20b">setNoDeadStrip</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5936108678489f329bbdabdc0a0f518d">isWeakReference</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1711756403f673069e350b3fe47d58ea">setWeakReference</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addcff0bd4e0d9566b3ea715e0e3b7cb2">isWeakDefinition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d47c1bb8775e9d756b990236529d6f7">setWeakDefinition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94c032da5cfa06ad26d8277ca9e50ba">isSymbolResolver</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424d918450c2c5105897fe64ec38cb4e">setSymbolResolver</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797be6dd7516a69a4d649e2178bd3c87">setAltEntry</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab003656c29b4c5d9c6507f348e6dd5ae">isAltEntry</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819400d6ff31b187871e44c764c8dfe5">setCold</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9995da1ca72262cb03ede4637bc30b">isCold</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc80b88bff0a524bea64a39da3ee383">setDesc</a> (unsigned Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f615443ab1c333d7a2dafd4f5009ab">isSymbolLinkerVisible</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d42cecd93e81cab0163fc6d56fba6ac">getEncodedFlags</a> (bool EncodeAsAltEntry) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the encoded value of the flags as they will be emitted in to the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> binary. <a href="#a3d42cecd93e81cab0163fc6d56fba6ac">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56b2b692c921cce4f2c49267f44ab4e">classof</a> (const MCSymbol *S)</td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MachOSymbolFlags {#a415fa6175d6fb7b4de98dee1e7ebd0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSymbolMachO::MachOSymbolFlags : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We store the value for the 'desc' symbol field in the lowest 16 bits of the implementation defined flags.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_DescFlagsMask<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba351f520854be4ff176c67ddb09b7c11e"></a></td>
<td class="doxyEnumItemDescription"> (= 0xFFFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ReferenceTypeMask<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba620e77bcdb1c0c375149c9d1083217ed"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0007)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ReferenceTypeUndefinedNonLazy<a id="a415fa6175d6fb7b4de98dee1e7ebd0dbaac735ddd6a932515e2fca0ca25207193"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ReferenceTypeUndefinedLazy<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba241edd445d428de6f57b3b429c3e4afc"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ReferenceTypeDefined<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba0a3376324c2aadd34591fbb7c857fd1b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ReferenceTypePrivateDefined<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba12510def7f53b3ec3f835db47127fb15"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0003)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ReferenceTypePrivateUndefinedNonLazy<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba5c94eafcc5adab2c88d954235e2b62d5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ReferenceTypePrivateUndefinedLazy<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba9b3452d43038b4e93d0bc52598ffa9d4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0005)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_ThumbFunc<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba21f0730c4745e108a9d8322b03709848"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_NoDeadStrip<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba8d5019698e85bb1a4a1ea5b68c2b9e3d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0020)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_WeakReference<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba724ee7ebab49571b4e5c755f7d045914"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0040)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_WeakDefinition<a id="a415fa6175d6fb7b4de98dee1e7ebd0dbaefa4fee53daca109d17ab58bde593d12"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0080)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_SymbolResolver<a id="a415fa6175d6fb7b4de98dee1e7ebd0dbacb3d950457b7336e2107c715f63be611"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_AltEntry<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba7ef8f0502e3d3864a10081d55cb67ec5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Cold<a id="a415fa6175d6fb7b4de98dee1e7ebd0dba6624e31bd829532e05c6b58dfda51f9f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_CommonAlignmentMask<a id="a415fa6175d6fb7b4de98dee1e7ebd0dbacdf839995d042d2038484b9a2972e727"></a></td>
<td class="doxyEnumItemDescription"> (= 0xF0FF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_CommonAlignmentShift<a id="a415fa6175d6fb7b4de98dee1e7ebd0dbacc3178afd45074576e6c96a4dd853dff"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCSymbolMachO() {#a59262c6e30a690a5ab41dd3dce25fba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbolMachO::MCSymbolMachO (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool isTemporary)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab8dab642726ffad2a75d9fb7e4ec4291add342b668ac3888a3aef1e9895366842">llvm::MCSymbol::SymbolKindMachO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearReferenceType() {#a4c7b06ed26ba9de68ded30b76ed10ac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::clearReferenceType ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### getEncodedFlags() {#a3d42cecd93e81cab0163fc6d56fba6ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSymbolMachO::getEncodedFlags (bool EncodeAsAltEntry)</td>
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

<p>Get the encoded value of the flags as they will be emitted in to the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> binary.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a654fdc7113f88027cc2016453184e880">llvm::MCSymbol::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a8212a1be8c83903d02e10af1cd534dc7">llvm::MCSymbol::getCommonAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4e87f4e2c6164013059b777bc2b6cf2a">llvm::MCSymbol::isCommon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### isAltEntry() {#ab003656c29b4c5d9c6507f348e6dd5ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isAltEntry ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### isCold() {#a4e9995da1ca72262cb03ede4637bc30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isCold ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### isNoDeadStrip() {#a28b98b657efc7bbefc66eee331b727ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isNoDeadStrip ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### isPrivateExtern() {#a07cf7f49f636f68568612d4d8175246c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isPrivateExtern ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a5601a855d573cb6cd60c7d0a0cb6039c">llvm::MCSymbol::IsPrivateExtern</a>.</p>

</div>
</div>

### isSymbolLinkerVisible() {#aa8f615443ab1c333d7a2dafd4f5009ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isSymbolLinkerVisible ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#af6973fed52c67fe96c0493207984376b">llvm::MCSymbol::isUsedInReloc</a>.</p>

</div>
</div>

### isSymbolResolver() {#ab94c032da5cfa06ad26d8277ca9e50ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isSymbolResolver ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### isWeakDefinition() {#addcff0bd4e0d9566b3ea715e0e3b7cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isWeakDefinition ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### isWeakReference() {#a5936108678489f329bbdabdc0a0f518d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::isWeakReference ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>

</div>
</div>

### setAltEntry() {#a797be6dd7516a69a4d649e2178bd3c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setAltEntry ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setCold() {#a819400d6ff31b187871e44c764c8dfe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setCold ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setDesc() {#aabc80b88bff0a524bea64a39da3ee383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setDesc (unsigned Value)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ade459224fb570ada6dfe814e45423df2">llvm::MCSymbol::Value</a>.</p>

</div>
</div>

### setNoDeadStrip() {#adb2be0f571f852febfb9eebb2430e20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setNoDeadStrip ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setPrivateExtern() {#a9afef6139b3e549e7a5a7d88990d4a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setPrivateExtern (bool Value)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a5601a855d573cb6cd60c7d0a0cb6039c">llvm::MCSymbol::IsPrivateExtern</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ade459224fb570ada6dfe814e45423df2">llvm::MCSymbol::Value</a>.</p>

</div>
</div>

### setReferenceTypeUndefinedLazy() {#a6d037272c9f203be545f70f27e74d06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setReferenceTypeUndefinedLazy (bool Value)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ade459224fb570ada6dfe814e45423df2">llvm::MCSymbol::Value</a>.</p>

</div>
</div>

### setSymbolResolver() {#a424d918450c2c5105897fe64ec38cb4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setSymbolResolver ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setThumbFunc() {#aebf4ea5a6029e7f7c4c450b6b31bcb55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setThumbFunc ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setWeakDefinition() {#a3d47c1bb8775e9d756b990236529d6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setWeakDefinition ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

### setWeakReference() {#a1711756403f673069e350b3fe47d58ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolMachO::setWeakReference ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ab56b2b692c921cce4f2c49267f44ab4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolMachO::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a1874095bacbd303d9200e3c6f3fc0f5f">llvm::MCSymbol::isMachO</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">MCSymbolMachO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
