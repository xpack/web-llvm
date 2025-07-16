---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSymbol` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> - Instances of this class represent a symbol name in the MC file, and MCSymbols are created and uniqued by the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff">MCSymbolCOFF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolgoff">MCSymbolGOFF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho">MCSymbolMachO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff">MCSymbolXCOFF</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9e4586713b5561ff4a0daf55d476fc">NameEntryStorageTy</a> = union { <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> *NameEntry; uint64_t AlignmentPadding; }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name for a symbol. <a href="#acc9e4586713b5561ff4a0daf55d476fc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SymbolKind { <a href="#ab8dab642726ffad2a75d9fb7e4ec4291">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of the symbol. <a href="#ab8dab642726ffad2a75d9fb7e4ec4291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Contents : uint8_t { <a href="#ab281e4b5733c0b3ca5969fc1d651333b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A symbol can contain an Offset, or <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, or be Common, but never more than one of these. <a href="#ab281e4b5733c0b3ca5969fc1d651333b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a454d311b0ae2e3bdac7d581e79062f4f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The alignment of the symbol if it is 'common'. <a href="#a454d311b0ae2e3bdac7d581e79062f4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#acbbfb6821ac7b027fd6fb8e8aab043f2">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Flags field is used by object file implementations to store additional per symbol information which is not easily classified. <a href="#acbbfb6821ac7b027fd6fb8e8aab043f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4003ba7a2726fde2214660963213cc31">MCExpr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7862d2f746209c16291d7139dab55e00">MCContext</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2078a2958acdd7023e063c33b16c3dc9">MCSymbol</a> (const MCSymbol &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> (SymbolKind Kind, const MCSymbolTableEntry *Name, bool isTemporary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af735a30a6eae3b4118d4d901fcd59f07">operator=</a> (const MCSymbol &amp;)=delete</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44507ca9ae5a30fe3aaf1cdea68d2eb8">operator new</a> (size_t s, const MCSymbolTableEntry *Name, MCContext &amp;Ctx)</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e135d28fd19d606803e1b88e7ef9f1">operator delete</a> (void *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d0d85d5eb99c9c9a98cf5eefc95e51">operator delete</a> (void *, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement delete - required by std, but never called. <a href="#ae8d0d85d5eb99c9c9a98cf5eefc95e51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1097b0c7bf887d3e77edffc9f88ee607">operator delete</a> (void *, unsigned, bool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement delete - required by std, but never called. <a href="#a1097b0c7bf887d3e77edffc9f88ee607">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c7b2b9784361914262eeb0a6f0b18d">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getName - Get the symbol name. <a href="#a57c7b2b9784361914262eeb0a6f0b18d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc0bd5c7cfcb87bc65c90ec1423f958">isRegistered</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae646cd55f238024a83328a7a1565ac11">setIsRegistered</a> (bool Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9241f6f7d54c02902a249fb72ea6295">setUsedInReloc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6973fed52c67fe96c0493207984376b">isUsedInReloc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8c6e58e0fb2534a0b6289f30b1d25d">getIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the (implementation defined) index. <a href="#aab8c6e58e0fb2534a0b6289f30b1d25d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03af2ef8f5bbbd64f174f0a8feb3c32">setIndex</a> (uint32_t Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the (implementation defined) index. <a href="#aa03af2ef8f5bbbd64f174f0a8feb3c32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad829c4f6666903fc66490cd4b5445eae">isUnset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54312c2c4a267e78f5ee754c68dfbcc">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9ae52dad6d9d0840fce1109f46c953">setOffset</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18bc1f4226626995dc930237a9ff7b6">getCommonSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of a 'common' symbol. <a href="#ac18bc1f4226626995dc930237a9ff7b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ae0062893460c1d6fb0fc612ede192">setCommon</a> (uint64_t Size, Align Alignment, bool Target=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark this symbol as being 'common'. <a href="#a38ae0062893460c1d6fb0fc612ede192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8212a1be8c83903d02e10af1cd534dc7">getCommonAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment of a 'common' symbol. <a href="#a8212a1be8c83903d02e10af1cd534dc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4a05b32a482232267400c369932868">declareCommon</a> (uint64_t Size, Align Alignment, bool Target=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declare this symbol as being 'common'. <a href="#acd4a05b32a482232267400c369932868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e87f4e2c6164013059b777bc2b6cf2a">isCommon</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a 'common' symbol. <a href="#a4e87f4e2c6164013059b777bc2b6cf2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a806e3c35d0361b3f662d723f8c616">isTargetCommon</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a target-specific common-like symbol. <a href="#a22a806e3c35d0361b3f662d723f8c616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a> (bool SetUsed=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada159ab0506b0f377aaa17516506f65a">isExternal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a90289b3b4b0ce7aa1b450fd38607d">setExternal</a> (bool Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61020d1a9925e4f1ad5bb1a6b8e5e46e">isWeakExternal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f7a23e572edb7b1bc46d9639c3204a">print</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print the value to the stream <span class="doxyComputerOutput">OS</span>. <a href="#a27f7a23e572edb7b1bc46d9639c3204a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2ff5e9eadc78b9ea7a216595933f86">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - Print the value to stderr. <a href="#aca2ff5e9eadc78b9ea7a216595933f86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a712cacf1731d527651876ac16e90cad0">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the (implementation defined) symbol flags. <a href="#a712cacf1731d527651876ac16e90cad0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3e2ebdfaad92643de69faf7f28967e">setFlags</a> (uint32_t Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the (implementation defined) symbol flags. <a href="#a6e3e2ebdfaad92643de69faf7f28967e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f740178324a11d838ee335b2986d6eb">modifyFlags</a> (uint32_t Value, uint32_t Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modify the flags via a mask. <a href="#a4f740178324a11d838ee335b2986d6eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bfc4fbf60b744d0c271c3b9a5ab7c5c">getNameEntryPtr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the name field. Requires that we have a name. <a href="#a8bfc4fbf60b744d0c271c3b9a5ab7c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8bbdcaff3734316691298b46a0c9419">getNameEntryPtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb98c740be7ed4c20e1efb0a49bb4d81">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset to apply to the fragment address to form this symbol's value. <a href="#aeb98c740be7ed4c20e1efb0a49bb4d81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c1a1754ca6d09df3c97dc02e91016f">CommonSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size of the symbol, if it is 'common'. <a href="#ae6c1a1754ca6d09df3c97dc02e91016f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade459224fb570ada6dfe814e45423df2">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If non-null, the value for a variable symbol. <a href="#ade459224fb570ada6dfe814e45423df2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd0cd49830dc61d53ea13f8a02865da">Fragment</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a symbol has a Fragment, the section is implied, so we only need one pointer. <a href="#aacd0cd49830dc61d53ea13f8a02865da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8d48125737efeee8f6c557cccd09d6">HasName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this symbol is named. <a href="#a9b8d48125737efeee8f6c557cccd09d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90fdd791ab1dadcac4bc95adbd58016">IsTemporary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsTemporary - True if this is an assembler temporary label, which typically does not survive in the .o file's symbol table. <a href="#ac90fdd791ab1dadcac4bc95adbd58016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a0f665a30884d490a667c24b6f9743">IsRedefinable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this symbol can be redefined. <a href="#a67a0f665a30884d490a667c24b6f9743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f78bb9dc66342e9dbedec745bc8855">IsUsed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsUsed - True if this symbol has been used. <a href="#a45f78bb9dc66342e9dbedec745bc8855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1760cea79950dc4fdf4257ee6ee853">IsRegistered</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e25f118b3801875582f52dfaeaaa6f">IsExternal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this symbol is visible outside this translation unit. <a href="#a74e25f118b3801875582f52dfaeaaa6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5601a855d573cb6cd60c7d0a0cb6039c">IsPrivateExtern</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mach-O specific: This symbol is private extern. <a href="#a5601a855d573cb6cd60c7d0a0cb6039c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d6c7ed60ac780e10ebc636b6aeba3f">IsWeakExternal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This symbol is weak external. <a href="#a14d6c7ed60ac780e10ebc636b6aeba3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6571d8b653cd83974156495475d00e">Kind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM RTTI discriminator. <a href="#afa6571d8b653cd83974156495475d00e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f82643b6ed35890789b5fd89220e9bf">IsUsedInReloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we have created a relocation that uses this symbol. <a href="#a5f82643b6ed35890789b5fd89220e9bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is actually a <a href="#ab281e4b5733c0b3ca5969fc1d651333b">Contents</a> enumerator, but is unsigned to avoid sign extension and achieve better bitpacking with MSVC. <a href="#aa982a927d29bb0b33d323340bf669c4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8271909bf0b0c839a7171941c5da0e6f">CommonAlignLog2</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654fdc7113f88027cc2016453184e880">Flags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87340fa42dc2d338e7603b01794948b8">Index</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index field, for use by the object file implementation. <a href="#a87340fa42dc2d338e7603b01794948b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">llvm::MCSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43135c5e948732999ee5e016535023ae"></a></td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab889b3167a4e08aeb1268d4712f7221c">AbsolutePseudoFragment</a> = &amp;<a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbol-cpp/#a8068d87b2e32e33757bdd790404031d2">SentinelFragment</a></td>
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

## Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1c818c7e94eb25afce63fc2f91c0e2">isTemporary</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isTemporary - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is an assembler temporary symbol. <a href="#acb1c818c7e94eb25afce63fc2f91c0e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6614e2886fdbfefe64b8b2a7580295">isUsed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isUsed - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is used. <a href="#a8f6614e2886fdbfefe64b8b2a7580295">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7689c81cf651a3ac9c6f0ee5ab65c6">isRedefinable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol is redefinable. <a href="#a7b7689c81cf651a3ac9c6f0ee5ab65c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64f2a23a64ea508097104bbe78ad7ff">setRedefinable</a> (bool Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark this symbol as redefinable. <a href="#aa64f2a23a64ea508097104bbe78ad7ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe52fcc0194159b0a6e516e3ece4e4a2">redefineIfPossible</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare this symbol to be redefined. <a href="#abe52fcc0194159b0a6e516e3ece4e4a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Associated Sections Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2899e74730516967f04d81966bb4f881">isDefined</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isDefined - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol is defined (i.e., it has an address). <a href="#a2899e74730516967f04d81966bb4f881">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3214f95c05e3d2af5e3e56667dc54239">isInSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isInSection - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol is defined in some section (i.e., it is defined but not absolute). <a href="#a3214f95c05e3d2af5e3e56667dc54239">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa462dae167e31cac32e97bb0c77ab071">isUndefined</a> (bool SetUsed=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isUndefined - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol undefined (i.e., implicitly defined). <a href="#aa462dae167e31cac32e97bb0c77ab071">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f8b88ccaf57e90229faab2169cd2e4">isAbsolute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isAbsolute - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is an absolute symbol. <a href="#a00f8b88ccaf57e90229faab2169cd2e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d669d1338ce8b4ddf910da10c51607">getSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the section associated with a defined, non-absolute symbol. <a href="#ab7d669d1338ce8b4ddf910da10c51607">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59bf6e97f0f02573b74d322186c91327">setFragment</a> (MCFragment *F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the symbol as defined in the fragment <span class="doxyComputerOutput">F</span>. <a href="#a59bf6e97f0f02573b74d322186c91327">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65fa2b7850f38cafbc74ab99c3a3fed">setUndefined</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the symbol as undefined. <a href="#ab65fa2b7850f38cafbc74ab99c3a3fed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d2549f322ec04f233dc4304b4bbd16">isELF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820696a7bde417a8827ec1a981968084">isCOFF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c04471cea55b02d601f1dcd40825e9c">isGOFF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1874095bacbd303d9200e3c6f3fc0f5f">isMachO</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063e60f6284c95d6447e7afbfb4e8ace">isWasm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f37b1f48f732756d82ca7a2b2a1beb">isXCOFF</a> () const</td>
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

## Variable Symbols Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620bf1ce8489b3da259faf0c55a862aa">isVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVariable - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a variable symbol. <a href="#a620bf1ce8489b3da259faf0c55a862aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2192a3f25b0bc0505cc168a012038046">getVariableValue</a> (bool SetUsed=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getVariableValue - Get the value for variable symbols. <a href="#a2192a3f25b0bc0505cc168a012038046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f1486460b5e2da7f4527bbb2da54eff">setVariableValue</a> (const MCExpr *Value)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> - Instances of this class represent a symbol name in the MC file, and MCSymbols are created and uniqued by the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> class.</p>


<p>MCSymbols should only be constructed with valid names for the object file.</p>


<p>If the symbol is defined/emitted into the current translation unit, the Section member is set to indicate what section it lives in. Otherwise, if it is a reference to an external entity, it has a null section.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### NameEntryStorageTy {#acc9e4586713b5561ff4a0daf55d476fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCSymbol::NameEntryStorageTy =  union {
    const MCSymbolTableEntry *NameEntry;
    uint64_t AlignmentPadding;
  }</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name for a symbol.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> contains a uint64_t so is probably aligned to 8. On a 32-bit system, the name is a pointer so isn't going to satisfy the 8 byte alignment of uint64_t. Account for that here.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a454d311b0ae2e3bdac7d581e79062f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The alignment of the symbol if it is 'common'.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumCommonAlignmentBits<a id="a454d311b0ae2e3bdac7d581e79062f4fac8ece6378cbe9f0340ed2cfc60c19616"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>


<p>Internally, this is stored as log2(align) + 1. We reserve 5 bits to encode this value which allows the following values 0b00000 -&gt; unset 0b00001 -&gt; 1ULL &lt;&lt; 0 = 1 0b00010 -&gt; 1ULL &lt;&lt; 1 = 2 0b00011 -&gt; 1ULL &lt;&lt; 2 = 4 ... 0b11111 -&gt; 1ULL &lt;&lt; 30 = 1 GiB</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

### anonymous enum  {#acbbfb6821ac7b027fd6fb8e8aab043f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Flags field is used by object file implementations to store additional per symbol information which is not easily classified.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumFlagsBits<a id="acbbfb6821ac7b027fd6fb8e8aab043f2a08af0ccac8c4c96802f9fa92ef52e34d"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

### Contents {#ab281e4b5733c0b3ca5969fc1d651333b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSymbol::Contents : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A symbol can contain an Offset, or <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, or be Common, but never more than one of these.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymContentsUnset<a id="ab281e4b5733c0b3ca5969fc1d651333baaac521554a8934e34e473fc085ad7c4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymContentsOffset<a id="ab281e4b5733c0b3ca5969fc1d651333ba9529576611c3f1013a277a6440aaedc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymContentsVariable<a id="ab281e4b5733c0b3ca5969fc1d651333baeacb7989d1dabfc220151df99c57a55c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymContentsCommon<a id="ab281e4b5733c0b3ca5969fc1d651333ba7b555343319009595cf8d1d6d16586a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymContentsTargetCommon<a id="ab281e4b5733c0b3ca5969fc1d651333bab2fa0e4a177b7e2c8edb170a90b7ca8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

### SymbolKind {#ab8dab642726ffad2a75d9fb7e4ec4291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSymbol::SymbolKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of the symbol.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolKindUnset<a id="ab8dab642726ffad2a75d9fb7e4ec4291a8b2e39e5d0377741c6e033c8218396e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolKindCOFF<a id="ab8dab642726ffad2a75d9fb7e4ec4291a031eff3517a3a7518e717cc1eb9c5b8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolKindELF<a id="ab8dab642726ffad2a75d9fb7e4ec4291ae346ce5c2a999355f4e55692f502d583"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolKindGOFF<a id="ab8dab642726ffad2a75d9fb7e4ec4291a78a22e912f7933c3ac315c2ab67a9212"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolKindMachO<a id="ab8dab642726ffad2a75d9fb7e4ec4291add342b668ac3888a3aef1e9895366842"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolKindWasm<a id="ab8dab642726ffad2a75d9fb7e4ec4291aba489d15d843572410f5bbf9dcba0934"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolKindXCOFF<a id="ab8dab642726ffad2a75d9fb7e4ec4291a481f422e7c0ce93801f9be23c44f6fe2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>If it is any value other than unset then this class is actually one of the appropriate subclasses of <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a>.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MCContext {#a7862d2f746209c16291d7139dab55e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a7862d2f746209c16291d7139dab55e00">MCContext</a>.</p>


<p>Referenced by <a href="#a7862d2f746209c16291d7139dab55e00">MCContext</a> and <a href="#a44507ca9ae5a30fe3aaf1cdea68d2eb8">operator new</a>.</p>

</div>
</div>

### MCExpr {#a4003ba7a2726fde2214660963213cc31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a4003ba7a2726fde2214660963213cc31">MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a83461ac06968f969da6b77b0e3e90527">llvm::MCSymbolELF::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a4be99a3a42bbf0d95ef6ae77e3739696">llvm::MCSymbolWasm::getSize</a>, <a href="#a2192a3f25b0bc0505cc168a012038046">getVariableValue</a>, <a href="#a4003ba7a2726fde2214660963213cc31">MCExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a63edf630bae30668b44c9be9a85cb9a8">llvm::MCSymbolELF::setSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#af330152133430b4db138c108eeda9afa">llvm::MCSymbolWasm::setSize</a> and <a href="#a7f1486460b5e2da7f4527bbb2da54eff">setVariableValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCSymbol() {#a2078a2958acdd7023e063c33b16c3dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbol::MCSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MCSymbol() {#a66a74a9d90f80bcf982d70ab2446862e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbol::MCSymbol (<a href="#ab8dab642726ffad2a75d9fb7e4ec4291">SymbolKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool isTemporary)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#a8271909bf0b0c839a7171941c5da0e6f">CommonAlignLog2</a>, <a href="#a654fdc7113f88027cc2016453184e880">Flags</a>, <a href="#a9b8d48125737efeee8f6c557cccd09d6">HasName</a>, <a href="#a74e25f118b3801875582f52dfaeaaa6f">IsExternal</a>, <a href="#a5601a855d573cb6cd60c7d0a0cb6039c">IsPrivateExtern</a>, <a href="#a67a0f665a30884d490a667c24b6f9743">IsRedefinable</a>, <a href="#a5f1760cea79950dc4fdf4257ee6ee853">IsRegistered</a>, <a href="#ac90fdd791ab1dadcac4bc95adbd58016">IsTemporary</a>, <a href="#acb1c818c7e94eb25afce63fc2f91c0e2">isTemporary</a>, <a href="#a45f78bb9dc66342e9dbedec745bc8855">IsUsed</a>, <a href="#a5f82643b6ed35890789b5fd89220e9bf">IsUsedInReloc</a>, <a href="#a14d6c7ed60ac780e10ebc636b6aeba3f">IsWeakExternal</a>, <a href="#afa6571d8b653cd83974156495475d00e">Kind</a>, <a href="#aeb98c740be7ed4c20e1efb0a49bb4d81">Offset</a>, <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a> and <a href="#ab281e4b5733c0b3ca5969fc1d651333baaac521554a8934e34e473fc085ad7c4c">SymContentsUnset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a8d0b7232f2ca80fd124bbb752f0479e3">llvm::MCSymbolCOFF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aa50f62817c413083ae49d53c57d56484">llvm::MCSymbolELF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolgoff/#a90f5440ed9deca226c5cb595bc6158ea">llvm::MCSymbolGOFF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#ab56b2b692c921cce4f2c49267f44ab4e">llvm::MCSymbolMachO::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a18b060951fe2c68b6071614499e1d8ab">llvm::MCSymbolWasm::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a08a0eb104e53ad194da0dcc598b63bb2">llvm::MCSymbolXCOFF::classof</a>, <a href="#a2078a2958acdd7023e063c33b16c3dc9">MCSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a9f4bc9d94fbfd9e2b3135ea1b4dc3193">llvm::MCSymbolCOFF::MCSymbolCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ab5409f62668af4a8e307fe9149e1ff92">llvm::MCSymbolELF::MCSymbolELF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolgoff/#a0c2a2e7f8850e5d8c1ce927cbe98b760">llvm::MCSymbolGOFF::MCSymbolGOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a59262c6e30a690a5ab41dd3dce25fba3">llvm::MCSymbolMachO::MCSymbolMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a3b1a4d377afcb0e8b74c7b1da059ed45">llvm::MCSymbolWasm::MCSymbolWasm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a2c1a8a60db1ccd5a95705b427ca23733">llvm::MCSymbolXCOFF::MCSymbolXCOFF</a>, <a href="#a44507ca9ae5a30fe3aaf1cdea68d2eb8">operator new</a> and <a href="#af735a30a6eae3b4118d4d901fcd59f07">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#af735a30a6eae3b4118d4d901fcd59f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol &amp; llvm::MCSymbol::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator new() {#a44507ca9ae5a30fe3aaf1cdea68d2eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * MCSymbol::operator new (size_t s, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbol-cpp">MCSymbol.cpp</a>.</p>


<p>References <a href="#a7862d2f746209c16291d7139dab55e00">MCContext</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator delete() {#ae4e135d28fd19d606803e1b88e7ef9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::operator delete (void *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

### operator delete() {#ae8d0d85d5eb99c9c9a98cf5eefc95e51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::operator delete (void *, unsigned)</td>
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

<p>Placement delete - required by std, but never called.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

### operator delete() {#a1097b0c7bf887d3e77edffc9f88ee607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::operator delete (void *, unsigned, bool)</td>
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

<p>Placement delete - required by std, but never called.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### declareCommon() {#acd4a05b32a482232267400c369932868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::declareCommon (uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool Target=false)</td>
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

<p>Declare this symbol as being 'common'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/target"&gt;Target&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- Is the symbol a target-specific common-like symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if symbol was already declared as a different type</p></dd>
</dl>


<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae6c1a1754ca6d09df3c97dc02e91016f">CommonSize</a>, <a href="#a8212a1be8c83903d02e10af1cd534dc7">getCommonAlignment</a>, <a href="#af54312c2c4a267e78f5ee754c68dfbcc">getOffset</a>, <a href="#a4e87f4e2c6164013059b777bc2b6cf2a">isCommon</a>, <a href="#a22a806e3c35d0361b3f662d723f8c616">isTargetCommon</a>, <a href="#a38ae0062893460c1d6fb0fc612ede192">setCommon</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a>.</p>

</div>
</div>

### dump() {#aca2ff5e9eadc78b9ea7a216595933f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MCSymbol::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - Print the value to stderr.</p>

<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbol-cpp">MCSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a3a68266def3072d13b2cafb555b9e28c">llvm::MCAssembler::dump</a>.</p>

</div>
</div>

### getCommonAlignment() {#a8212a1be8c83903d02e10af1cd534dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::MCSymbol::getCommonAlignment ()</td>
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

<p>Return the alignment of a 'common' symbol.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8271909bf0b0c839a7171941c5da0e6f">CommonAlignLog2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf0a0b32865d4f5ea01718c492ec983a">llvm::decodeMaybeAlign</a> and <a href="#a4e87f4e2c6164013059b777bc2b6cf2a">isCommon</a>.</p>


<p>Referenced by <a href="#acd4a05b32a482232267400c369932868">declareCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a3d42cecd93e81cab0163fc6d56fba6ac">llvm::MCSymbolMachO::getEncodedFlags</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a58befb331c0a20300b519e2d96ad7efb">anonymous{ELFObjectWriter.cpp}::ELFWriter::symbolValue</a>.</p>

</div>
</div>

### getCommonSize() {#ac18bc1f4226626995dc930237a9ff7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCSymbol::getCommonSize ()</td>
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

<p>Return the size of a 'common' symbol.</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae6c1a1754ca6d09df3c97dc02e91016f">CommonSize</a> and <a href="#a4e87f4e2c6164013059b777bc2b6cf2a">isCommon</a>.</p>

</div>
</div>

### getFragment() {#afe11aa50f8890a5eeda1fadf7e2f576e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::MCSymbol::getFragment (bool SetUsed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a>, <a href="#aacd0cd49830dc61d53ea13f8a02865da">Fragment</a>, <a href="#a2192a3f25b0bc0505cc168a012038046">getVariableValue</a>, <a href="#a620bf1ce8489b3da259faf0c55a862aa">isVariable</a> and <a href="#a61020d1a9925e4f1ad5bb1a6b8e5e46e">isWeakExternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#ab3fd02f1d1b3eeeec275c2485ba8af0a">llvm::MachObjectWriter::getAtom</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a99b84e083c8b17e6af277efb72bc6fa0">anonymous{XCOFFObjectWriter.cpp}::getContainingCsect</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#aeb3dece637ebb3e1beecc3ea3a150f09">getLabelOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a4b6a90d8388aab90babe76b13765ddf6">llvm::RISCVMCExpr::getPCRelHiFixup</a>, <a href="#ab7d669d1338ce8b4ddf910da10c51607">getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="#a00f8b88ccaf57e90229faab2169cd2e4">isAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#ac824d3ba330c71dc80aeea123922f11d">llvm::MCObjectWriter::isSymbolRefDifferenceFullyResolved</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a854e63ee2f4ff3e684ba403e8342d88d">llvm::MachObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="#aa462dae167e31cac32e97bb0c77ab071">isUndefined</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### getIndex() {#aab8c6e58e0fb2534a0b6289f30b1d25d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCSymbol::getIndex ()</td>
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

<p>Get the (implementation defined) index.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a87340fa42dc2d338e7603b01794948b8">Index</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a3a68266def3072d13b2cafb555b9e28c">llvm::MCAssembler::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a41f368207329f5957e26e92ca87ebdbf">llvm::DwarfDebug::insertSectionLabel</a> and <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a>.</p>

</div>
</div>

### getName() {#a57c7b2b9784361914262eeb0a6f0b18d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbol::getName ()</td>
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

<p>getName - Get the symbol name.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a9b8d48125737efeee8f6c557cccd09d6">HasName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#aeac390246bd74f8e7897e99b30ae2c6f">llvm::MCResourceInfo::createTotalNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a6fa44a1fa346266bc9d287dce014dcfb">llvm::MCResourceInfo::createTotalNumVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#ab470d8aa53480de68554a22812342ca7">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIEpilogEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a082d0b0afa7b05bf751feabbc3550f2b">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitArrayBound</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a34ce30f596de6334b5f17323b15e4fa4">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a56d51423094db4b2932d7e53c69ea140">llvm::MipsTargetAsmStreamer::emitDirectiveCpsetup</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#aa0ada33537d92cbc3a1eb8815c70a28c">llvm::WebAssemblyTargetAsmStreamer::emitExportName</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#a3d00e1ac3848f4af6f98182dca6f5045">llvm::WebAssemblyTargetAsmStreamer::emitFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#aa2841293de9505ceb9ef958d38fa1526">llvm::WebAssemblyTargetAsmStreamer::emitGlobalType</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a046ce1a28d601dbc32167434da7ce4cd">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::EmitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aac53de41a4af1d12db6ce7d5a0cf6678">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ac0b0be8a73319c121d8c53e4219eff24">llvm::WebAssemblyTargetAsmStreamer::emitImportModule</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#a553f2aafa48b30ff11741b23bcffe6ad">llvm::WebAssemblyTargetAsmStreamer::emitImportName</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetasmstreamer/#a3bed684acd63359143ccec5b37ccd397">llvm::XtensaTargetAsmStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a9b50dd93932455982bef5aaf44afd0aa">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitPseudoProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ab1be13e43fafccdcb3c7fb6ff5b316e5">llvm::WebAssemblyTargetAsmStreamer::emitTableType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ad431095019a0f5c940ea308e3bcfadbf">llvm::WebAssemblyTargetAsmStreamer::emitTagType</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer/#a0c4536e911b01c1a6f0ab8ed2a62bf16">anonymous{PPCMCTargetDesc.cpp}::PPCTargetAsmStreamer::emitTCEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#ad3e4f5bb59058be7d568e2505d04b830">llvm::NVPTXTargetStreamer::emitValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a3d4443a5f4df398bcde06fae90a11c04">EvaluateCRExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aef93e9316e910cbb64002e1cdfad0f01">llvm::MCContext::getAssociativeCOFFSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp/#a0e2890f613a1a43228dec112d337340d">getAuthPtrSlotSymbolHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ac06af0994b284d9e18c3b90c7c500a03">llvm::MCAssembler::getBaseSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a1d086ef68afbc813e0403f73866b1cdb">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getCallTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a64fec16b33fa7f23710afb8904948f30">llvm::MCContext::getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a3d42cecd93e81cab0163fc6d56fba6ac">llvm::MCSymbolMachO::getEncodedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a36fdd6258a57e9924a00446921669046">llvm::MCSymbolWasm::getImportName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#aeb3dece637ebb3e1beecc3ea3a150f09">getLabelOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a7dfd846c7bc87f28f0dc5dab92e7fe58">llvm::NVPTXTargetLowering::getParamName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad75e2aa4d67c101594e1f7448588c8d3">llvm::TargetLoweringObjectFileCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a8cf6220e005c692b687fb495317b2d70">getStaticStructorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a447f1f2cd3572d7c1d3317369ed4ea7a">getSymbolOffsetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#adcdf9e06b3bfdbe3a419b71ee19fc753">llvm::MCSymbolXCOFF::getUnqualifiedName</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ad715fadab36063fc73cd1c87d0fcc636">llvm::MCContext::getWasmSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a719cb125836c429953e4eb35be1e93b4">hasGOTReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a919e61fbc03b7b8a1660337897db7094">llvm::MCAsmBackend::isDarwinCanonicalPersonality</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a72864dd5479176074c3bbcc3b0e50c22">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerFAULTING_OP</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="#a27f7a23e572edb7b1bc46d9639c3204a">print</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a59aaa2e922d6173cbeaed43a2d58423a">llvm::X86Operand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#acc39fa43ddee9c26c911927bb0afee99">llvm::WebAssemblyInstPrinter::printCatchList</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a71696cd21e4b5e6a498bfa1c891f147a">llvm::SystemZInstPrinterCommon::printPCRelTLSOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#a95deb4634cbeb9bd9936eee80df81c17">llvm::NVPTXInstPrinter::printProtoIdent</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ada3d2a129f8e8076337a902e8077adcf">llvm::PPCInstPrinter::printTLSCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a575d0689ae105eb694d6bdc9cc873935">llvm::MCContext::registerInlineAsmLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a3e9dd2df270e8ff9b688dc40af18e54e">startsWithGlobalOffsetTable</a> and <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a>.</p>

</div>
</div>

### getOffset() {#af54312c2c4a267e78f5ee754c68dfbcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCSymbol::getOffset ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeb98c740be7ed4c20e1efb0a49bb4d81">Offset</a>, <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333ba9529576611c3f1013a277a6440aaedc1">SymContentsOffset</a> and <a href="#ab281e4b5733c0b3ca5969fc1d651333baaac521554a8934e34e473fc085ad7c4c">SymContentsUnset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>, <a href="#acd4a05b32a482232267400c369932868">declareCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#aeb3dece637ebb3e1beecc3ea3a150f09">getLabelOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a4b6a90d8388aab90babe76b13765ddf6">llvm::RISCVMCExpr::getPCRelHiFixup</a> and <a href="#a38ae0062893460c1d6fb0fc612ede192">setCommon</a>.</p>

</div>
</div>

### isCommon() {#a4e87f4e2c6164013059b777bc2b6cf2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isCommon ()</td>
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

<p>Is this a 'common' symbol.</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333ba7b555343319009595cf8d1d6d16586a3">SymContentsCommon</a> and <a href="#ab281e4b5733c0b3ca5969fc1d651333bab2fa0e4a177b7e2c8edb170a90b7ca8f">SymContentsTargetCommon</a>.</p>


<p>Referenced by <a href="#acd4a05b32a482232267400c369932868">declareCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ac06af0994b284d9e18c3b90c7c500a03">llvm::MCAssembler::getBaseSymbol</a>, <a href="#a8212a1be8c83903d02e10af1cd534dc7">getCommonAlignment</a>, <a href="#ac18bc1f4226626995dc930237a9ff7b6">getCommonSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a3d42cecd93e81cab0163fc6d56fba6ac">llvm::MCSymbolMachO::getEncodedFlags</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a58befb331c0a20300b519e2d96ad7efb">anonymous{ELFObjectWriter.cpp}::ELFWriter::symbolValue</a>.</p>

</div>
</div>

### isExternal() {#ada159ab0506b0f377aaa17516506f65a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isExternal ()</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a74e25f118b3801875582f52dfaeaaa6f">IsExternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a69d646b59f77217c6a669115f4a30283">llvm::ARMAsmBackend::shouldForceRelocation</a>.</p>

</div>
</div>

### isRegistered() {#a9cc0bd5c7cfcb87bc65c90ec1423f958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isRegistered ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a5f1760cea79950dc4fdf4257ee6ee853">IsRegistered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a>.</p>

</div>
</div>

### isTargetCommon() {#a22a806e3c35d0361b3f662d723f8c616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isTargetCommon ()</td>
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

<p>Is this a target-specific common-like symbol.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a> and <a href="#ab281e4b5733c0b3ca5969fc1d651333bab2fa0e4a177b7e2c8edb170a90b7ca8f">SymContentsTargetCommon</a>.</p>


<p>Referenced by <a href="#acd4a05b32a482232267400c369932868">declareCommon</a>.</p>

</div>
</div>

### isUnset() {#ad829c4f6666903fc66490cd4b5445eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isUnset ()</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a> and <a href="#ab281e4b5733c0b3ca5969fc1d651333baaac521554a8934e34e473fc085ad7c4c">SymContentsUnset</a>.</p>

</div>
</div>

### isUsedInReloc() {#af6973fed52c67fe96c0493207984376b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isUsedInReloc ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a5f82643b6ed35890789b5fd89220e9bf">IsUsedInReloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ae357568bfa7baaa244f16208924f4637">llvm::MCSymbolELF::getBinding</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#acfd6b837b0a2c4f3fbf36102a70cc5b9">isInSymtab</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#aa8f615443ab1c333d7a2dafd4f5009ab">llvm::MCSymbolMachO::isSymbolLinkerVisible</a>.</p>

</div>
</div>

### isWeakExternal() {#a61020d1a9925e4f1ad5bb1a6b8e5e46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isWeakExternal ()</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a14d6c7ed60ac780e10ebc636b6aeba3f">IsWeakExternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a050338ae4cc98b34569977f26196f415">canExpand</a>, <a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae066b71f79346e6cf0e978da4656e1bc">llvm::MCExpr::isSymbolUsedInExpression</a>.</p>

</div>
</div>

### print() {#a27f7a23e572edb7b1bc46d9639c3204a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSymbol::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>print - Print the value to the stream <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbol-cpp">MCSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a57c7b2b9784361914262eeb0a6f0b18d">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aef73072733b19b438fdd3af23627706c">llvm::MCAsmInfo::isValidUnquotedName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a66b2402fdf6bed91396cc511f818ae65">llvm::MCAsmInfo::supportsNameQuoting</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aaec2d1923c9f931fc50ff7d8f06a4555">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitAddrsigSym</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a83ebec98343071d599da4791ca684669">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFILsda</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2e7a2fbd7a50f4bb4db72650d848e706">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIPersonality</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ac25530725b6ee241fdd59a2b41cc8222">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#af1fd3e492100e8cc074e33590fc9e951">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVFPOData</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa96077a0e4bce1c56fb5c2660e5752df">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVInlineLinetableDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a238e59e2af8906f2cfc5155663d7a196">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVLinetableDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ab3cd968a6ba01a35c097a702ea02fb4f">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitELFSymverDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer/#a6807c6b1007827cfda4d5fa7fae5747e">anonymous{PPCMCTargetDesc.cpp}::PPCTargetAsmStreamer::emitLocalEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4d9da6fd250447386af90f45a41bb8a0">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#adb765c6ee407ec7777308406d9fbcf30">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandler</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2d3b4a12c2fbc688388c6c2b422f8e88">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitXCOFFLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a111dc82835d20c22a21d07426ec732df">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kasmprinter/#a5474d7cf1a213163c8929c3189e2c166">llvm::M68kAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a8549db3c421967b14bad3b2e6ab53980">llvm::CSKYAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#ab3b56dc8749765fe615f325594493167">llvm::WebAssemblyAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp/#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoreinstprinter-cpp/#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#adc984afaf62b041cceff164e14cdb889">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aec3f83e468ca215a70dda2742816745c">llvm::HexagonAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a34e471aa6f0a6f1975d57f3aafc7b2e0">llvm::AsmPrinter::PrintSymbolOperand</a>.</p>

</div>
</div>

### setCommon() {#a38ae0062893460c1d6fb0fc612ede192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setCommon (uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool Target=false)</td>
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

<p>Mark this symbol as being 'common'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/target"&gt;Target&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- Is the symbol a target-specific common-like symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8271909bf0b0c839a7171941c5da0e6f">CommonAlignLog2</a>, <a href="#ae6c1a1754ca6d09df3c97dc02e91016f">CommonSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15ce86953ef9122361a5be3aba654272">llvm::encode</a>, <a href="#af54312c2c4a267e78f5ee754c68dfbcc">getOffset</a>, <a href="#a454d311b0ae2e3bdac7d581e79062f4fac8ece6378cbe9f0340ed2cfc60c19616">NumCommonAlignmentBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333ba7b555343319009595cf8d1d6d16586a3">SymContentsCommon</a> and <a href="#ab281e4b5733c0b3ca5969fc1d651333bab2fa0e4a177b7e2c8edb170a90b7ca8f">SymContentsTargetCommon</a>.</p>


<p>Referenced by <a href="#acd4a05b32a482232267400c369932868">declareCommon</a>.</p>

</div>
</div>

### setExternal() {#a41a90289b3b4b0ce7aa1b450fd38607d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setExternal (bool Value)</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#a74e25f118b3801875582f52dfaeaaa6f">IsExternal</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a03ebbddf5185beab8e633649235fe873">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::finalizeCGProfileEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a12d7f7b28045ca28e88138c63c174184">llvm::MCWinCOFFStreamer::finalizeCGProfileEntry</a>.</p>

</div>
</div>

### setIndex() {#aa03af2ef8f5bbbd64f174f0a8feb3c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setIndex (uint32_t Value)</td>
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

<p>Set the (implementation defined) index.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#a87340fa42dc2d338e7603b01794948b8">Index</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a>.</p>

</div>
</div>

### setIsRegistered() {#ae646cd55f238024a83328a7a1565ac11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setIsRegistered (bool Value)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#a5f1760cea79950dc4fdf4257ee6ee853">IsRegistered</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>

</div>
</div>

### setOffset() {#abb9ae52dad6d9d0840fce1109f46c953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setOffset (uint64_t Value)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeb98c740be7ed4c20e1efb0a49bb4d81">Offset</a>, <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333ba9529576611c3f1013a277a6440aaedc1">SymContentsOffset</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333baaac521554a8934e34e473fc085ad7c4c">SymContentsUnset</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>

</div>
</div>

### setUsedInReloc() {#aa9241f6f7d54c02902a249fb72ea6295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setUsedInReloc ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a5f82643b6ed35890789b5fd89220e9bf">IsUsedInReloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a73aed7794053594cfb9536d55eac30fd">llvm::ELFObjectWriter::recordRelocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getFlags() {#a712cacf1731d527651876ac16e90cad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCSymbol::getFlags ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the (implementation defined) symbol flags.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a654fdc7113f88027cc2016453184e880">Flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#af87b3ae59f6e6531a3c0cbc2aab544f6">llvm::MCSymbolCOFF::getClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a3d42cecd93e81cab0163fc6d56fba6ac">llvm::MCSymbolMachO::getEncodedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#af37cdc599522d884c88461f88dc18ac2">llvm::MCSymbolCOFF::getWeakExternalCharacteristics</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#ab003656c29b4c5d9c6507f348e6dd5ae">llvm::MCSymbolMachO::isAltEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a666e25e11bd035c93786545bec5ce44e">llvm::MCSymbolELF::isBindingSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a4e9995da1ca72262cb03ede4637bc30b">llvm::MCSymbolMachO::isCold</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a6397be1a70c3c747af829c3d590e329d">llvm::MCSymbolXCOFF::isEHInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a2b84295e51434ac5b2b268a2fa7c130c">llvm::MCSymbolWasm::isExported</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a27d141d83c2f705e53214a5e6bb84e83">llvm::MCSymbolELF::isMemtag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a28b98b657efc7bbefc66eee331b727ef">llvm::MCSymbolMachO::isNoDeadStrip</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a903f25fc3d903840c154d513b80942da">llvm::MCSymbolWasm::isNoStrip</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a8f99a95ef446233d0940b18a46321a88">llvm::MCSymbolCOFF::isSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ada18a65001620ef826d10d729fd05df6">llvm::MCSymbolELF::isSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#ab94c032da5cfa06ad26d8277ca9e50ba">llvm::MCSymbolMachO::isSymbolResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#af0aaed75ab9d50975313452d033616e5">llvm::MCSymbolWasm::isTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#addcff0bd4e0d9566b3ea715e0e3b7cb2">llvm::MCSymbolMachO::isWeakDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a5936108678489f329bbdabdc0a0f518d">llvm::MCSymbolMachO::isWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a3e683b1f93c043f9fb48cdc47e736fb2">llvm::MCSymbolELF::isWeakrefUsedInReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ac1edee41b5f81ab31451e8bf98a3a3e6">llvm::MCSymbolELF::setBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a785dd47a727f7ced9db97da95dc69690">llvm::MCSymbolELF::setIsSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a9bbad98aac843f2c52cd716efdde45e5">llvm::MCSymbolELF::setIsWeakrefUsedInReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a4904497c380093675bde4af54fb493ce">llvm::MCSymbolELF::setMemtag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aed9abfbf50800b7378713d657bf0cf5a">llvm::MCSymbolELF::setOther</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aed759e9547e045f0bd987987de0f76bc">llvm::MCSymbolELF::setType</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a42d355b38e3f57001fdbce9f13846a04">llvm::MCSymbolELF::setVisibility</a>.</p>

</div>
</div>

### modifyFlags() {#a4f740178324a11d838ee335b2986d6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::modifyFlags (uint32_t Value, uint32_t Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modify the flags via a mask.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a654fdc7113f88027cc2016453184e880">Flags</a>, <a href="#acbbfb6821ac7b027fd6fb8e8aab043f2a08af0ccac8c4c96802f9fa92ef52e34d">NumFlagsBits</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a4c7b06ed26ba9de68ded30b76ed10ac2">llvm::MCSymbolMachO::clearReferenceType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a797be6dd7516a69a4d649e2178bd3c87">llvm::MCSymbolMachO::setAltEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a8ff8aca2e0a127f3bf37e56c9dcaabaf">llvm::MCSymbolCOFF::setClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a819400d6ff31b187871e44c764c8dfe5">llvm::MCSymbolMachO::setCold</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a49f40a63f3dc40a07df172bebf7eb98c">llvm::MCSymbolXCOFF::setEHInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#ab601ca3b61286b47c425b061856e876f">llvm::MCSymbolWasm::setExported</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a582f0e948a6c830817d56afcc5c8f4bc">llvm::MCSymbolCOFF::setIsSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#adb2be0f571f852febfb9eebb2430e20b">llvm::MCSymbolMachO::setNoDeadStrip</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a67c1c155ac78b299701444d7a31046e5">llvm::MCSymbolWasm::setNoStrip</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a6d037272c9f203be545f70f27e74d06f">llvm::MCSymbolMachO::setReferenceTypeUndefinedLazy</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a424d918450c2c5105897fe64ec38cb4e">llvm::MCSymbolMachO::setSymbolResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#aebf4ea5a6029e7f7c4c450b6b31bcb55">llvm::MCSymbolMachO::setThumbFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#af9d60a95bc4f401939956b7328ee70d9">llvm::MCSymbolWasm::setTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a3d47c1bb8775e9d756b990236529d6f7">llvm::MCSymbolMachO::setWeakDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a2d6e7c88e67fc58206c665c3c4f498a1">llvm::MCSymbolCOFF::setWeakExternalCharacteristics</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a1711756403f673069e350b3fe47d58ea">llvm::MCSymbolMachO::setWeakReference</a>.</p>

</div>
</div>

### setFlags() {#a6e3e2ebdfaad92643de69faf7f28967e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setFlags (uint32_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the (implementation defined) symbol flags.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a654fdc7113f88027cc2016453184e880">Flags</a>, <a href="#acbbfb6821ac7b027fd6fb8e8aab043f2a08af0ccac8c4c96802f9fa92ef52e34d">NumFlagsBits</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ac1edee41b5f81ab31451e8bf98a3a3e6">llvm::MCSymbolELF::setBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#aabc80b88bff0a524bea64a39da3ee383">llvm::MCSymbolMachO::setDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a785dd47a727f7ced9db97da95dc69690">llvm::MCSymbolELF::setIsSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a9bbad98aac843f2c52cd716efdde45e5">llvm::MCSymbolELF::setIsWeakrefUsedInReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a4904497c380093675bde4af54fb493ce">llvm::MCSymbolELF::setMemtag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aed9abfbf50800b7378713d657bf0cf5a">llvm::MCSymbolELF::setOther</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aed759e9547e045f0bd987987de0f76bc">llvm::MCSymbolELF::setType</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a42d355b38e3f57001fdbce9f13846a04">llvm::MCSymbolELF::setVisibility</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNameEntryPtr() {#a8bfc4fbf60b744d0c271c3b9a5ab7c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolTableEntry *&amp; llvm::MCSymbol::getNameEntryPtr ()</td>
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

<p>Get a reference to the name field. Requires that we have a name.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

### getNameEntryPtr() {#ac8bbdcaff3734316691298b46a0c9419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolTableEntry *&amp; llvm::MCSymbol::getNameEntryPtr ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CommonSize {#ae6c1a1754ca6d09df3c97dc02e91016f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCSymbol::CommonSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size of the symbol, if it is 'common'.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#acd4a05b32a482232267400c369932868">declareCommon</a>, <a href="#ac18bc1f4226626995dc930237a9ff7b6">getCommonSize</a> and <a href="#a38ae0062893460c1d6fb0fc612ede192">setCommon</a>.</p>

</div>
</div>

### Offset {#aeb98c740be7ed4c20e1efb0a49bb4d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCSymbol::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset to apply to the fragment address to form this symbol's value.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#af54312c2c4a267e78f5ee754c68dfbcc">getOffset</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="#abb9ae52dad6d9d0840fce1109f46c953">setOffset</a>.</p>

</div>
</div>

### Value {#ade459224fb570ada6dfe814e45423df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::MCSymbol::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If non-null, the value for a variable symbol.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a2192a3f25b0bc0505cc168a012038046">getVariableValue</a>, <a href="#a4f740178324a11d838ee335b2986d6eb">modifyFlags</a>, <a href="#abe52fcc0194159b0a6e516e3ece4e4a2">redefineIfPossible</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#aabc80b88bff0a524bea64a39da3ee383">llvm::MCSymbolMachO::setDesc</a>, <a href="#a41a90289b3b4b0ce7aa1b450fd38607d">setExternal</a>, <a href="#a6e3e2ebdfaad92643de69faf7f28967e">setFlags</a>, <a href="#aa03af2ef8f5bbbd64f174f0a8feb3c32">setIndex</a>, <a href="#ae646cd55f238024a83328a7a1565ac11">setIsRegistered</a>, <a href="#abb9ae52dad6d9d0840fce1109f46c953">setOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a9afef6139b3e549e7a5a7d88990d4a23">llvm::MCSymbolMachO::setPrivateExtern</a>, <a href="#aa64f2a23a64ea508097104bbe78ad7ff">setRedefinable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a6d037272c9f203be545f70f27e74d06f">llvm::MCSymbolMachO::setReferenceTypeUndefinedLazy</a> and <a href="#a7f1486460b5e2da7f4527bbb2da54eff">setVariableValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

###  {#a43135c5e948732999ee5e016535023ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::MCSymbol llvm::MCSymbol</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>

</div>
</div>

### CommonAlignLog2 {#a8271909bf0b0c839a7171941c5da0e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::CommonAlignLog2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a8212a1be8c83903d02e10af1cd534dc7">getCommonAlignment</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="#a38ae0062893460c1d6fb0fc612ede192">setCommon</a>.</p>

</div>
</div>

### Flags {#a654fdc7113f88027cc2016453184e880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCSymbol::Flags</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ae357568bfa7baaa244f16208924f4637">llvm::MCSymbolELF::getBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a3d42cecd93e81cab0163fc6d56fba6ac">llvm::MCSymbolMachO::getEncodedFlags</a>, <a href="#a712cacf1731d527651876ac16e90cad0">getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a2badd3f8011db90045f7be286331125f">llvm::MCSymbolELF::getOther</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a2c716684711cb83467c2138bc4e84454">llvm::MCSymbolELF::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#add2f34e14532817ad86d5c8f3b179c2a">llvm::MCSymbolELF::getVisibility</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>, <a href="#a4f740178324a11d838ee335b2986d6eb">modifyFlags</a> and <a href="#a6e3e2ebdfaad92643de69faf7f28967e">setFlags</a>.</p>

</div>
</div>

### Fragment {#aacd0cd49830dc61d53ea13f8a02865da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment* llvm::MCSymbol::Fragment = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a symbol has a Fragment, the section is implied, so we only need one pointer.</p>


<p>The special AbsolutePseudoFragment value is for absolute symbols. If this is a variable symbol, this caches the variable value's fragment. FIXME: We might be able to simplify this by having the asm streamer create dummy fragments. If this is a section, then it gives the symbol is defined in. This is null for undefined symbols.</p>


<p>If this is a fragment, then it gives the fragment this symbol's value is relative to, if any.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a>, <a href="#a59bf6e97f0f02573b74d322186c91327">setFragment</a> and <a href="#ab65fa2b7850f38cafbc74ab99c3a3fed">setUndefined</a>.</p>

</div>
</div>

### HasName {#a9b8d48125737efeee8f6c557cccd09d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::HasName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this symbol is named.</p>


<p>A named symbol will have a pointer to the name allocated in the bytes immediately prior to the <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a>.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a57c7b2b9784361914262eeb0a6f0b18d">getName</a> and <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>.</p>

</div>
</div>

### Index {#a87340fa42dc2d338e7603b01794948b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCSymbol::Index = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index field, for use by the object file implementation.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#aab8c6e58e0fb2534a0b6289f30b1d25d">getIndex</a> and <a href="#aa03af2ef8f5bbbd64f174f0a8feb3c32">setIndex</a>.</p>

</div>
</div>

### IsExternal {#a74e25f118b3801875582f52dfaeaaa6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsExternal</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this symbol is visible outside this translation unit.</p>


<p>Note: <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> uses binding instead of this bit.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#ada159ab0506b0f377aaa17516506f65a">isExternal</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="#a41a90289b3b4b0ce7aa1b450fd38607d">setExternal</a>.</p>

</div>
</div>

### IsPrivateExtern {#a5601a855d573cb6cd60c7d0a0cb6039c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsPrivateExtern</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mach-O specific: This symbol is private extern.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a07cf7f49f636f68568612d4d8175246c">llvm::MCSymbolMachO::isPrivateExtern</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a9afef6139b3e549e7a5a7d88990d4a23">llvm::MCSymbolMachO::setPrivateExtern</a>.</p>

</div>
</div>

### IsRedefinable {#a67a0f665a30884d490a667c24b6f9743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsRedefinable</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this symbol can be redefined.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a7b7689c81cf651a3ac9c6f0ee5ab65c6">isRedefinable</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>, <a href="#abe52fcc0194159b0a6e516e3ece4e4a2">redefineIfPossible</a> and <a href="#aa64f2a23a64ea508097104bbe78ad7ff">setRedefinable</a>.</p>

</div>
</div>

### IsRegistered {#a5f1760cea79950dc4fdf4257ee6ee853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsRegistered</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a9cc0bd5c7cfcb87bc65c90ec1423f958">isRegistered</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="#ae646cd55f238024a83328a7a1565ac11">setIsRegistered</a>.</p>

</div>
</div>

### IsTemporary {#ac90fdd791ab1dadcac4bc95adbd58016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsTemporary</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsTemporary - True if this is an assembler temporary label, which typically does not survive in the .o file's symbol table.</p>


<p>Usually "Lfoo" or ".foo".</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#acb1c818c7e94eb25afce63fc2f91c0e2">isTemporary</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolgoff/#a0c2a2e7f8850e5d8c1ce927cbe98b760">llvm::MCSymbolGOFF::MCSymbolGOFF</a>.</p>

</div>
</div>

### IsUsed {#a45f78bb9dc66342e9dbedec745bc8855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsUsed</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsUsed - True if this symbol has been used.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a2192a3f25b0bc0505cc168a012038046">getVariableValue</a>, <a href="#a8f6614e2886fdbfefe64b8b2a7580295">isUsed</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="#a7f1486460b5e2da7f4527bbb2da54eff">setVariableValue</a>.</p>

</div>
</div>

### IsUsedInReloc {#a5f82643b6ed35890789b5fd89220e9bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsUsedInReloc</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if we have created a relocation that uses this symbol.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#af6973fed52c67fe96c0493207984376b">isUsedInReloc</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="#aa9241f6f7d54c02902a249fb72ea6295">setUsedInReloc</a>.</p>

</div>
</div>

### IsWeakExternal {#a14d6c7ed60ac780e10ebc636b6aeba3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::IsWeakExternal</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This symbol is weak external.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a61020d1a9925e4f1ad5bb1a6b8e5e46e">isWeakExternal</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a238d8c4330bd8208af7c03ac2ac47117">llvm::MCSymbolCOFF::setIsWeakExternal</a>.</p>

</div>
</div>

### Kind {#afa6571d8b653cd83974156495475d00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::Kind</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM RTTI discriminator.</p>


<p>This is actually a <a href="#ab8dab642726ffad2a75d9fb7e4ec4291">SymbolKind</a> enumerator, but is unsigned to avoid sign extension and achieve better bitpacking with MSVC.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#a820696a7bde417a8827ec1a981968084">isCOFF</a>, <a href="#a32d2549f322ec04f233dc4304b4bbd16">isELF</a>, <a href="#a3c04471cea55b02d601f1dcd40825e9c">isGOFF</a>, <a href="#a1874095bacbd303d9200e3c6f3fc0f5f">isMachO</a>, <a href="#a063e60f6284c95d6447e7afbfb4e8ace">isWasm</a>, <a href="#ae7f37b1f48f732756d82ca7a2b2a1beb">isXCOFF</a> and <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>.</p>

</div>
</div>

### SymbolContents {#aa982a927d29bb0b33d323340bf669c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbol::SymbolContents</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is actually a <a href="#ab281e4b5733c0b3ca5969fc1d651333b">Contents</a> enumerator, but is unsigned to avoid sign extension and achieve better bitpacking with MSVC.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="#af54312c2c4a267e78f5ee754c68dfbcc">getOffset</a>, <a href="#a4e87f4e2c6164013059b777bc2b6cf2a">isCommon</a>, <a href="#a22a806e3c35d0361b3f662d723f8c616">isTargetCommon</a>, <a href="#ad829c4f6666903fc66490cd4b5445eae">isUnset</a>, <a href="#a620bf1ce8489b3da259faf0c55a862aa">isVariable</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>, <a href="#abe52fcc0194159b0a6e516e3ece4e4a2">redefineIfPossible</a>, <a href="#a38ae0062893460c1d6fb0fc612ede192">setCommon</a>, <a href="#abb9ae52dad6d9d0840fce1109f46c953">setOffset</a> and <a href="#a7f1486460b5e2da7f4527bbb2da54eff">setVariableValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### AbsolutePseudoFragment {#ab889b3167a4e08aeb1268d4712f7221c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * MCSymbol::AbsolutePseudoFragment = &amp;<a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbol-cpp/#a8068d87b2e32e33757bdd790404031d2">SentinelFragment</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#a00f8b88ccaf57e90229faab2169cd2e4">isAbsolute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### isRedefinable {#a7b7689c81cf651a3ac9c6f0ee5ab65c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isRedefinable ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol is redefinable.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a67a0f665a30884d490a667c24b6f9743">IsRedefinable</a>.</p>

</div>
</div>

### isTemporary {#acb1c818c7e94eb25afce63fc2f91c0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isTemporary ()</td>
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

<p>isTemporary - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is an assembler temporary symbol.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#ac90fdd791ab1dadcac4bc95adbd58016">IsTemporary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a58e3c2a4ec9c34e4a8c8388fb66946ae">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a912942cd73fd3f0a2dfb952fed5c49dc">llvm::MCWinCOFFStreamer::emitCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfelfobjectwriter-cpp-/bpfelfobjectwriter/#a6a865396f00972a6e0d0c4f731128e31">anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#acfd6b837b0a2c4f3fbf36102a70cc5b9">isInSymtab</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#aa8f615443ab1c333d7a2dafd4f5009ab">llvm::MCSymbolMachO::isSymbolLinkerVisible</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a854e63ee2f4ff3e684ba403e8342d88d">llvm::MachObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="#a66a74a9d90f80bcf982d70ab2446862e">MCSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a9f4bc9d94fbfd9e2b3135ea1b4dc3193">llvm::MCSymbolCOFF::MCSymbolCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ab5409f62668af4a8e307fe9149e1ff92">llvm::MCSymbolELF::MCSymbolELF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a59262c6e30a690a5ab41dd3dce25fba3">llvm::MCSymbolMachO::MCSymbolMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a3b1a4d377afcb0e8b74c7b1da059ed45">llvm::MCSymbolWasm::MCSymbolWasm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a2c1a8a60db1ccd5a95705b427ca23733">llvm::MCSymbolXCOFF::MCSymbolXCOFF</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#adb14af816964063e2e902f6d9586abcd">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveIndirectSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a> and <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a>.</p>

</div>
</div>

### isUsed {#a8f6614e2886fdbfefe64b8b2a7580295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isUsed ()</td>
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

<p>isUsed - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is used.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#a45f78bb9dc66342e9dbedec745bc8855">IsUsed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>.</p>

</div>
</div>

### redefineIfPossible {#abe52fcc0194159b0a6e516e3ece4e4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::redefineIfPossible ()</td>
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

<p>Prepare this symbol to be redefined.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#a67a0f665a30884d490a667c24b6f9743">IsRedefinable</a>, <a href="#ab65fa2b7850f38cafbc74ab99c3a3fed">setUndefined</a>, <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333baaac521554a8934e34e473fc085ad7c4c">SymContentsUnset</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333baeacb7989d1dabfc220151df99c57a55c">SymContentsVariable</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>.</p>

</div>
</div>

### setRedefinable {#aa64f2a23a64ea508097104bbe78ad7ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setRedefinable (bool Value)</td>
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

<p>Mark this symbol as redefinable.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#a67a0f665a30884d490a667c24b6f9743">IsRedefinable</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Associated Sections

### getSection {#ab7d669d1338ce8b4ddf910da10c51607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection &amp; llvm::MCSymbol::getSection ()</td>
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

<p>Get the section associated with a defined, non-absolute symbol.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a> and <a href="#a3214f95c05e3d2af5e3e56667dc54239">isInSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mclinesection/#a3bfcb56edfb6e38a5e722f77a50c88fd">llvm::MCLineSection::addEndEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#af5b3d468d882817a49ac012840023d10">llvm::BTFDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#afe65683534ca819c702e4eb5f158f387">emitRangeList</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a27ab1f18a7bff8a82c03e03302227f0d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a2c00c11ef810b9f4ca1781a341de60d3">llvm::CodeViewContext::encodeInlineLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a64fec16b33fa7f23710afb8904948f30">llvm::MCContext::getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfelfobjectwriter-cpp-/bpfelfobjectwriter/#a6a865396f00972a6e0d0c4f731128e31">anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#ad8e9bd47b27dc42d0fc9b49ca743ba8d">llvm::LoongArchAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a41f368207329f5957e26e92ca87ebdbf">llvm::DwarfDebug::insertSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a854e63ee2f4ff3e684ba403e8342d88d">llvm::MachObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a0210297240fdf8674947d7cee55594c6">llvm::MCObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffobjectwriter/#a9d5e7168cbab3f139a9c4438e7016d12">llvm::WinCOFFObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aeaa22f130bcc2796a4d90a2be0e2fe38">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSectionHeader</a>.</p>

</div>
</div>

### isAbsolute {#a00f8b88ccaf57e90229faab2169cd2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isAbsolute ()</td>
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

<p>isAbsolute - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is an absolute symbol.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#ab889b3167a4e08aeb1268d4712f7221c">AbsolutePseudoFragment</a> and <a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a>.</p>


<p>Referenced by <a href="#a3214f95c05e3d2af5e3e56667dc54239">isInSection</a>.</p>

</div>
</div>

### isCOFF {#a820696a7bde417a8827ec1a981968084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isCOFF ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#afa6571d8b653cd83974156495475d00e">Kind</a> and <a href="#ab8dab642726ffad2a75d9fb7e4ec4291a031eff3517a3a7518e717cc1eb9c5b8c">SymbolKindCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a8d0b7232f2ca80fd124bbb752f0479e3">llvm::MCSymbolCOFF::classof</a>.</p>

</div>
</div>

### isDefined {#a2899e74730516967f04d81966bb4f881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isDefined ()</td>
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

<p>isDefined - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol is defined (i.e., it has an address).</p>


<p>Defined symbols are either absolute or in some section.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#aa462dae167e31cac32e97bb0c77ab071">isUndefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0b3f89703fa8ecd73c1b43a7ac656402">llvm::DwarfCompileUnit::attachLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a1f1ea57bc156f9e309b4049bc1d10e17">llvm::EHStreamer::computePadMap</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b7c6daec7e647061052e0947de4703b">llvm::AsmPrinter::emitFunctionBody</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ae357568bfa7baaa244f16208924f4637">llvm::MCSymbolELF::getBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a64fec16b33fa7f23710afb8904948f30">llvm::MCContext::getCOFFSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a99b84e083c8b17e6af277efb72bc6fa0">anonymous{XCOFFObjectWriter.cpp}::getContainingCsect</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfelfobjectwriter-cpp-/bpfelfobjectwriter/#a6a865396f00972a6e0d0c4f731128e31">anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter::getRelocType</a>, <a href="#a3214f95c05e3d2af5e3e56667dc54239">isInSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#acfd6b837b0a2c4f3fbf36102a70cc5b9">isInSymtab</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a463a346d7da05840b0c7f4b92dd3caf6">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveAltEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a> and <a href="/web-llvm/docs/api/classes/llvm/addrlabelmap/#aba3d880d5b4c6f123a2c50923e78c46a">llvm::AddrLabelMap::UpdateForDeletedBlock</a>.</p>

</div>
</div>

### isELF {#a32d2549f322ec04f233dc4304b4bbd16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isELF ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#afa6571d8b653cd83974156495475d00e">Kind</a> and <a href="#ab8dab642726ffad2a75d9fb7e4ec4291ae346ce5c2a999355f4e55692f502d583">SymbolKindELF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aa50f62817c413083ae49d53c57d56484">llvm::MCSymbolELF::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a69d646b59f77217c6a669115f4a30283">llvm::ARMAsmBackend::shouldForceRelocation</a>.</p>

</div>
</div>

### isGOFF {#a3c04471cea55b02d601f1dcd40825e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isGOFF ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#afa6571d8b653cd83974156495475d00e">Kind</a> and <a href="#ab8dab642726ffad2a75d9fb7e4ec4291a78a22e912f7933c3ac315c2ab67a9212">SymbolKindGOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolgoff/#a90f5440ed9deca226c5cb595bc6158ea">llvm::MCSymbolGOFF::classof</a>.</p>

</div>
</div>

### isInSection {#a3214f95c05e3d2af5e3e56667dc54239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isInSection ()</td>
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

<p>isInSection - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol is defined in some section (i.e., it is defined but not absolute).</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#a00f8b88ccaf57e90229faab2169cd2e4">isAbsolute</a> and <a href="#a2899e74730516967f04d81966bb4f881">isDefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#af5b3d468d882817a49ac012840023d10">llvm::BTFDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a050338ae4cc98b34569977f26196f415">canExpand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4c7cbce4c016b12020711970ace1128">llvm::MCStreamer::endSection</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#ab3fd02f1d1b3eeeec275c2485ba8af0a">llvm::MachObjectWriter::getAtom</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a64fec16b33fa7f23710afb8904948f30">llvm::MCContext::getCOFFSection</a>, <a href="#ab7d669d1338ce8b4ddf910da10c51607">getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#ad8e9bd47b27dc42d0fc9b49ca743ba8d">llvm::LoongArchAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a854e63ee2f4ff3e684ba403e8342d88d">llvm::MachObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a05b1a7fa3b559a330d9830ec956a8383">llvm::MCStreamer::switchSectionNoPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aeaa22f130bcc2796a4d90a2be0e2fe38">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSectionHeader</a>.</p>

</div>
</div>

### isMachO {#a1874095bacbd303d9200e3c6f3fc0f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isMachO ()</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#afa6571d8b653cd83974156495475d00e">Kind</a> and <a href="#ab8dab642726ffad2a75d9fb7e4ec4291add342b668ac3888a3aef1e9895366842">SymbolKindMachO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#ab56b2b692c921cce4f2c49267f44ab4e">llvm::MCSymbolMachO::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a919e61fbc03b7b8a1660337897db7094">llvm::MCAsmBackend::isDarwinCanonicalPersonality</a>.</p>

</div>
</div>

### isUndefined {#aa462dae167e31cac32e97bb0c77ab071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isUndefined (bool SetUsed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>isUndefined - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this symbol undefined (i.e., implicitly defined).</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a0d4cfdd1099f849b68c5072d1d7fd017">llvm::MachObjectWriter::doesSymbolRequireExternRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="#a2899e74730516967f04d81966bb4f881">isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#ac824d3ba330c71dc80aeea123922f11d">llvm::MCObjectWriter::isSymbolRefDifferenceFullyResolved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a865b1c6f63f4309779f26c93bd7030bf">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveTBSS</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a684c8f59f91c7a9a03ed144fef80ba6a">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveZerofill</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### isWasm {#a063e60f6284c95d6447e7afbfb4e8ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isWasm ()</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#afa6571d8b653cd83974156495475d00e">Kind</a> and <a href="#ab8dab642726ffad2a75d9fb7e4ec4291aba489d15d843572410f5bbf9dcba0934">SymbolKindWasm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a18b060951fe2c68b6071614499e1d8ab">llvm::MCSymbolWasm::classof</a>.</p>

</div>
</div>

### isXCOFF {#ae7f37b1f48f732756d82ca7a2b2a1beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isXCOFF ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#afa6571d8b653cd83974156495475d00e">Kind</a> and <a href="#ab8dab642726ffad2a75d9fb7e4ec4291a481f422e7c0ce93801f9be23c44f6fe2">SymbolKindXCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a08a0eb104e53ad194da0dcc598b63bb2">llvm::MCSymbolXCOFF::classof</a>.</p>

</div>
</div>

### setFragment {#a59bf6e97f0f02573b74d322186c91327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setFragment (<a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * F)</td>
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

<p>Mark the symbol as defined in the fragment <span class="doxyComputerOutput">F</span>.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#aacd0cd49830dc61d53ea13f8a02865da">Fragment</a> and <a href="#a620bf1ce8489b3da259faf0c55a862aa">isVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a64fec16b33fa7f23710afb8904948f30">llvm::MCContext::getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ad715fadab36063fc73cd1c87d0fcc636">llvm::MCContext::getWasmSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### setUndefined {#ab65fa2b7850f38cafbc74ab99c3a3fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbol::setUndefined ()</td>
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

<p>Mark the symbol as undefined.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>Reference <a href="#aacd0cd49830dc61d53ea13f8a02865da">Fragment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyasmparser-cpp-/#a97776aecc75fa260afa954c88a1bfed6">anonymous{WebAssemblyAsmParser.cpp}::getOrCreateFunctionTableSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a33df8ca13cb8bb9e37d1f43b202aef7f">llvm::WebAssembly::getOrCreateFunctionTableSymbol</a>, <a href="#abe52fcc0194159b0a6e516e3ece4e4a2">redefineIfPossible</a> and <a href="#a7f1486460b5e2da7f4527bbb2da54eff">setVariableValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variable Symbols

### getVariableValue {#a2192a3f25b0bc0505cc168a012038046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MCSymbol::getVariableValue (bool SetUsed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>getVariableValue - Get the value for variable symbols.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a45f78bb9dc66342e9dbedec745bc8855">IsUsed</a>, <a href="#a620bf1ce8489b3da259faf0c55a862aa">isVariable</a>, <a href="#a4003ba7a2726fde2214660963213cc31">MCExpr</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a050338ae4cc98b34569977f26196f415">canExpand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a8b7ffd07b20ace5663469673c7fdfc28">llvm::MachObjectWriter::findAliasedSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a447f1f2cd3572d7c1d3317369ed4ea7a">getSymbolOffsetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae066b71f79346e6cf0e978da4656e1bc">llvm::MCExpr::isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a9090caa8ccfc6c4298f8d31ffbc73ca4">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSymbol</a>.</p>

</div>
</div>

### isVariable {#a620bf1ce8489b3da259faf0c55a862aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbol::isVariable ()</td>
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

<p>isVariable - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a variable symbol.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>.</p>


<p>References <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a> and <a href="#ab281e4b5733c0b3ca5969fc1d651333baeacb7989d1dabfc220151df99c57a55c">SymContentsVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a8b7ffd07b20ace5663469673c7fdfc28">llvm::MachObjectWriter::findAliasedSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="#afe11aa50f8890a5eeda1fadf7e2f576e">getFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a447f1f2cd3572d7c1d3317369ed4ea7a">getSymbolOffsetImpl</a>, <a href="#a2192a3f25b0bc0505cc168a012038046">getVariableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae066b71f79346e6cf0e978da4656e1bc">llvm::MCExpr::isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>, <a href="#a59bf6e97f0f02573b74d322186c91327">setFragment</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a9090caa8ccfc6c4298f8d31ffbc73ca4">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSymbol</a>.</p>

</div>
</div>

### setVariableValue {#a7f1486460b5e2da7f4527bbb2da54eff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSymbol::setVariableValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbol-cpp">MCSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a45f78bb9dc66342e9dbedec745bc8855">IsUsed</a>, <a href="#a4003ba7a2726fde2214660963213cc31">MCExpr</a>, <a href="#ab65fa2b7850f38cafbc74ab99c3a3fed">setUndefined</a>, <a href="#aa982a927d29bb0b33d323340bf669c4b">SymbolContents</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333baaac521554a8934e34e473fc085ad7c4c">SymContentsUnset</a>, <a href="#ab281e4b5733c0b3ca5969fc1d651333baeacb7989d1dabfc220151df99c57a55c">SymContentsVariable</a> and <a href="#ade459224fb570ada6dfe814e45423df2">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac11138742df2a7103190a1955e6b7331">llvm::MCELFStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#ac85beb9165822c1f0510c92a3f340b35">llvm::MCWasmStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">MCSymbol.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbol-cpp">MCSymbol.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
