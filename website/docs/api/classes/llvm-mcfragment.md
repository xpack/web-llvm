---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcfragment
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCFragment` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCFragment { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">llvm/MC/MCFragment.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcalignfragment">MCAlignFragment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment">MCBoundaryAlignFragment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents required padding such that a particular other set of fragments does not cross a particular power-of-two boundary. <a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment">MCCVInlineLineTableFragment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fragment representing the binary annotations produced by the .cv_inline_linetable directive. <a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdummyfragment">MCDummyFragment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment">MCEncodedFragment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface implemented by fragments that contain encoded instructions and/or data. <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfillfragment">MCFillFragment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcnopsfragment">MCNopsFragment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcorgfragment">MCOrgFragment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolidfragment">MCSymbolIdFragment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a symbol table index fragment. <a href="/web-llvm/docs/api/classes/llvm/mcsymbolidfragment/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FragmentType : uint8_t { <a href="#aebf48160a3995325c6d2465080bcab68">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747ff8a8f0850b33062e4c8a115db32a">MCAssembler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4137b1ab897da1187cfc148ca3f8c128">MCObjectStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1a6df46fca095e84bffe737ce4ef72">MCSection</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312f660c73af24d1d2697e1b1c25ff93">MCFragment</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3b8e566bc0fa9a19ad2bbe5b939688">MCFragment</a> (const MCFragment &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a> (FragmentType Kind, bool HasInstructions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3605f1763b44bcb7115234ae600f20f">operator=</a> (const MCFragment &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e0da8cb1cac614df18ebb7ad458f3e">destroy</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroys the current fragment. <a href="#a60e0da8cb1cac614df18ebb7ad458f3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8324c4f0dec3572356e50c2876248fc3">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aebf48160a3995325c6d2465080bcab68">FragmentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2982683863a142955ae805f3bf930b4e">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b98ffc5ede97acf84a20b7476d3ffff">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47545378d5aa20fea6ea19963b436d65">setParent</a> (MCSection *Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e2fd6c6e6a95e8b339866567c8345d7">getAtom</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35243ed13b290de63e2d79e8b1e75711">getLayoutOrder</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f660b772e3f52336835fe6256420705">setLayoutOrder</a> (unsigned Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd02e61b262530ebe5c9a27ac0a0a693">hasInstructions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this fragment have instructions emitted into it? <a href="#acd02e61b262530ebe5c9a27ac0a0a693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73af1340aaefb3f64c1e4000ce6254e4">dump</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47324e10b138f859b0fee6acf80bd979">HasInstructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by subclasses for better packing. <a href="#a47324e10b138f859b0fee6acf80bd979">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063d6d412258d30d4ce0fcb37b645e9f">AlignToBundleEnd</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa9816583f9e76543cd195c5b0acffc">LinkerRelaxable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mcdatafragment">MCDataFragment</a>. <a href="#a0aa9816583f9e76543cd195c5b0acffc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7041d4aa87ae600ae5b28a4096dd9b">AllowAutoPadding</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a>: x86-specific. <a href="#a9f7041d4aa87ae600ae5b28a4096dd9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b773d1b8f03855dea9fee3c9352bba">Next</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab897ca89ead9e7a024d5f4ea0ac623cd">Parent</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The data for the section this fragment is in. <a href="#ab897ca89ead9e7a024d5f4ea0ac623cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c657506d3f434a1337b05b86fab9155">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset of this fragment in its section. <a href="#a4c657506d3f434a1337b05b86fab9155">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1efbeaeceaf87436de9bd22a4691eca7">LayoutOrder</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The layout order of this fragment. <a href="#a1efbeaeceaf87436de9bd22a4691eca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aebf48160a3995325c6d2465080bcab68">FragmentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c0a9aa7d8ac64226a0874401500e27a">Kind</a></td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FragmentType {#aebf48160a3995325c6d2465080bcab68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCFragment::FragmentType : uint8_t</td>
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
<td class="doxyEnumItemName">FT_Align<a id="aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_Data<a id="aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_Fill<a id="aebf48160a3995325c6d2465080bcab68a1d46f74bcd87621a62557b9b6fc67c4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_Nops<a id="aebf48160a3995325c6d2465080bcab68afa54da4eb8fe165449fbbd9a300903be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_Relaxable<a id="aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_Org<a id="aebf48160a3995325c6d2465080bcab68ac39471f5e9b12943cc8249cddbacd100"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_Dwarf<a id="aebf48160a3995325c6d2465080bcab68a01473d8036e353978ae750c8dace1a10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_DwarfFrame<a id="aebf48160a3995325c6d2465080bcab68a2f12197bbe6c6a91731b3828d033a212"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_LEB<a id="aebf48160a3995325c6d2465080bcab68acdb2608fe021d8fb06cf91d424f5bc53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_BoundaryAlign<a id="aebf48160a3995325c6d2465080bcab68a79f2f5b7f9eccf921287b14be41f29ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_SymbolId<a id="aebf48160a3995325c6d2465080bcab68a39bf3fdfcea08fc7dc5e927aa5fce3be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_CVInlineLines<a id="aebf48160a3995325c6d2465080bcab68a4c741eccc3322f72bad81e89b70c9382"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_CVDefRange<a id="aebf48160a3995325c6d2465080bcab68a99243fc57a7beebaba062a013912846f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_PseudoProbe<a id="aebf48160a3995325c6d2465080bcab68adcbefeedb7422d13473a4df6ff1cf964"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FT_Dummy<a id="aebf48160a3995325c6d2465080bcab68acd75963af411400a2ed7c133a25d17a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MCAssembler {#a747ff8a8f0850b33062e4c8a115db32a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a747ff8a8f0850b33062e4c8a115db32a">MCAssembler</a>.</p>


<p>Referenced by <a href="#a747ff8a8f0850b33062e4c8a115db32a">MCAssembler</a>.</p>

</div>
</div>

### MCObjectStreamer {#a4137b1ab897da1187cfc148ca3f8c128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a4137b1ab897da1187cfc148ca3f8c128">MCObjectStreamer</a>.</p>


<p>Referenced by <a href="#a4137b1ab897da1187cfc148ca3f8c128">MCObjectStreamer</a>.</p>

</div>
</div>

### MCSection {#a6f1a6df46fca095e84bffe737ce4ef72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a6f1a6df46fca095e84bffe737ce4ef72">MCSection</a>.</p>


<p>Referenced by <a href="#a7b98ffc5ede97acf84a20b7476d3ffff">getParent</a>, <a href="#a6f1a6df46fca095e84bffe737ce4ef72">MCSection</a> and <a href="#a47545378d5aa20fea6ea19963b436d65">setParent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCFragment() {#a312f660c73af24d1d2697e1b1c25ff93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCFragment::MCFragment ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### MCFragment() {#a8e3b8e566bc0fa9a19ad2bbe5b939688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCFragment::MCFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp;)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MCFragment() {#a08c64d9919161955899f42fad75089dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment::MCFragment (<a href="#aebf48160a3995325c6d2465080bcab68">FragmentType</a> Kind, bool HasInstructions)</td>
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



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcfragment-cpp">MCFragment.cpp</a>.</p>


<p>References <a href="#a063d6d412258d30d4ce0fcb37b645e9f">AlignToBundleEnd</a>, <a href="#a9f7041d4aa87ae600ae5b28a4096dd9b">AllowAutoPadding</a>, <a href="#a47324e10b138f859b0fee6acf80bd979">HasInstructions</a> and <a href="#a0aa9816583f9e76543cd195c5b0acffc">LinkerRelaxable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#ad5b3e7cc613b81af334359f6a861504a">llvm::MCAlignFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment/#aad4b145c67feca903353d0a914cdb4cb">llvm::MCBoundaryAlignFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment/#a38b8ef0db921b2e5117282cf72546e73">llvm::MCCVInlineLineTableFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdummyfragment/#a2841821c200ff281ee2eb9cc83933d4a">llvm::MCDummyFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a73e39521dd5e96c8562e4bfa9fea5472">llvm::MCEncodedFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfillfragment/#acd3fa0502c5f75d2701bba093a14811a">llvm::MCFillFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcnopsfragment/#ad9ebccb681aeb8d90370924f531468cf">llvm::MCNopsFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcorgfragment/#a36fffa7bf6527b3a7d1fc642634b5e3c">llvm::MCOrgFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolidfragment/#a7db195b7a0f1785f6a1cdbf7b5aeb7f1">llvm::MCSymbolIdFragment::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment/#aa0af65890138ce266990b34ae612e9d3">llvm::MCBoundaryAlignFragment::getLastFragment</a>, <a href="#a8324c4f0dec3572356e50c2876248fc3">getNext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#a4fd24c780cf65830f1112f7dd7bcc5a1">llvm::MCAlignFragment::MCAlignFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment/#a42983baf8470788ab623d1e8d3871a48">llvm::MCBoundaryAlignFragment::MCBoundaryAlignFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment/#a7742d9db81b13c0a62effc49aefdf025">llvm::MCCVInlineLineTableFragment::MCCVInlineLineTableFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdummyfragment/#a95821ea0eecce02a52a12f188922956e">llvm::MCDummyFragment::MCDummyFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a17077f9e77e49104a7a6c08cc1a96cff">llvm::MCEncodedFragment::MCEncodedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfillfragment/#a0394115f7be2fa74b7113aa11064c22d">llvm::MCFillFragment::MCFillFragment</a>, <a href="#a8e3b8e566bc0fa9a19ad2bbe5b939688">MCFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcnopsfragment/#a9dda9da5023f419451410b588154170b">llvm::MCNopsFragment::MCNopsFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcorgfragment/#ad761505757e621025fc93379ad56d847">llvm::MCOrgFragment::MCOrgFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolidfragment/#a334acca4ef88665938593e6de7f3aef8">llvm::MCSymbolIdFragment::MCSymbolIdFragment</a>, <a href="#ac3605f1763b44bcb7115234ae600f20f">operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment/#afb92a9a596bd11ffedfae405de2ee1ca">llvm::MCBoundaryAlignFragment::setLastFragment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ac3605f1763b44bcb7115234ae600f20f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment &amp; llvm::MCFragment::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp;)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### destroy() {#a60e0da8cb1cac614df18ebb7ad458f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCFragment::destroy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroys the current fragment.</p>


<p>This must be used instead of delete as <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> is non-virtual. This method will dispatch to the appropriate subclass.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcfragment-cpp">MCFragment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23">FT_Align</a>, <a href="#aebf48160a3995325c6d2465080bcab68a79f2f5b7f9eccf921287b14be41f29ac">FT_BoundaryAlign</a>, <a href="#aebf48160a3995325c6d2465080bcab68a99243fc57a7beebaba062a013912846f">FT_CVDefRange</a>, <a href="#aebf48160a3995325c6d2465080bcab68a4c741eccc3322f72bad81e89b70c9382">FT_CVInlineLines</a>, <a href="#aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80">FT_Data</a>, <a href="#aebf48160a3995325c6d2465080bcab68acd75963af411400a2ed7c133a25d17a3">FT_Dummy</a>, <a href="#aebf48160a3995325c6d2465080bcab68a01473d8036e353978ae750c8dace1a10">FT_Dwarf</a>, <a href="#aebf48160a3995325c6d2465080bcab68a2f12197bbe6c6a91731b3828d033a212">FT_DwarfFrame</a>, <a href="#aebf48160a3995325c6d2465080bcab68a1d46f74bcd87621a62557b9b6fc67c4b">FT_Fill</a>, <a href="#aebf48160a3995325c6d2465080bcab68acdb2608fe021d8fb06cf91d424f5bc53">FT_LEB</a>, <a href="#aebf48160a3995325c6d2465080bcab68afa54da4eb8fe165449fbbd9a300903be">FT_Nops</a>, <a href="#aebf48160a3995325c6d2465080bcab68ac39471f5e9b12943cc8249cddbacd100">FT_Org</a>, <a href="#aebf48160a3995325c6d2465080bcab68adcbefeedb7422d13473a4df6ff1cf964">FT_PseudoProbe</a>, <a href="#aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104">FT_Relaxable</a> and <a href="#aebf48160a3995325c6d2465080bcab68a39bf3fdfcea08fc7dc5e927aa5fce3be">FT_SymbolId</a>.</p>

</div>
</div>

### dump() {#a73af1340aaefb3f64c1e4000ce6254e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MCFragment::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcfragment-cpp">MCFragment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23">FT_Align</a>, <a href="#aebf48160a3995325c6d2465080bcab68a79f2f5b7f9eccf921287b14be41f29ac">FT_BoundaryAlign</a>, <a href="#aebf48160a3995325c6d2465080bcab68a99243fc57a7beebaba062a013912846f">FT_CVDefRange</a>, <a href="#aebf48160a3995325c6d2465080bcab68a4c741eccc3322f72bad81e89b70c9382">FT_CVInlineLines</a>, <a href="#aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80">FT_Data</a>, <a href="#aebf48160a3995325c6d2465080bcab68acd75963af411400a2ed7c133a25d17a3">FT_Dummy</a>, <a href="#aebf48160a3995325c6d2465080bcab68a01473d8036e353978ae750c8dace1a10">FT_Dwarf</a>, <a href="#aebf48160a3995325c6d2465080bcab68a2f12197bbe6c6a91731b3828d033a212">FT_DwarfFrame</a>, <a href="#aebf48160a3995325c6d2465080bcab68a1d46f74bcd87621a62557b9b6fc67c4b">FT_Fill</a>, <a href="#aebf48160a3995325c6d2465080bcab68acdb2608fe021d8fb06cf91d424f5bc53">FT_LEB</a>, <a href="#aebf48160a3995325c6d2465080bcab68afa54da4eb8fe165449fbbd9a300903be">FT_Nops</a>, <a href="#aebf48160a3995325c6d2465080bcab68ac39471f5e9b12943cc8249cddbacd100">FT_Org</a>, <a href="#aebf48160a3995325c6d2465080bcab68adcbefeedb7422d13473a4df6ff1cf964">FT_PseudoProbe</a>, <a href="#aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104">FT_Relaxable</a>, <a href="#aebf48160a3995325c6d2465080bcab68a39bf3fdfcea08fc7dc5e927aa5fce3be">FT_SymbolId</a>, <a href="#a2982683863a142955ae805f3bf930b4e">getKind</a>, <a href="#acd02e61b262530ebe5c9a27ac0a0a693">hasInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2145da5bde7663d745e9c3ade392809f">llvm::interleave</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### getAtom() {#a4e2fd6c6e6a95e8b339866567c8345d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * MCFragment::getAtom ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcfragment-cpp">MCFragment.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#ab3fd02f1d1b3eeeec275c2485ba8af0a">llvm::MachObjectWriter::getAtom</a> and <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a854e63ee2f4ff3e684ba403e8342d88d">llvm::MachObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>.</p>

</div>
</div>

### getKind() {#a2982683863a142955ae805f3bf930b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FragmentType llvm::MCFragment::getKind ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="#a73af1340aaefb3f64c1e4000ce6254e4">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>.</p>

</div>
</div>

### getLayoutOrder() {#a35243ed13b290de63e2d79e8b1e75711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCFragment::getLayoutOrder ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>.</p>

</div>
</div>

### getNext() {#a8324c4f0dec3572356e50c2876248fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::MCFragment::getNext ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>.</p>

</div>
</div>

### getParent() {#a7b98ffc5ede97acf84a20b7476d3ffff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCFragment::getParent ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a6f1a6df46fca095e84bffe737ce4ef72">MCSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#abc4d6b7d638e45034130bc3ab18e5be6">llvm::MCAssembler::computeFragmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#ab3fd02f1d1b3eeeec275c2485ba8af0a">llvm::MachObjectWriter::getAtom</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a99b84e083c8b17e6af277efb72bc6fa0">anonymous{XCOFFObjectWriter.cpp}::getContainingCsect</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a2be2c8edb4b559c7d47cfa0ec881739f">llvm::MachObjectWriter::getFragmentAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#ac2d01e55341f0be3c3d62a8346dc4807">llvm::ELFObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a854e63ee2f4ff3e684ba403e8342d88d">llvm::MachObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a0210297240fdf8674947d7cee55594c6">llvm::MCObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffobjectwriter/#a9d5e7168cbab3f139a9c4438e7016d12">llvm::WinCOFFObjectWriter::isSymbolRefDifferenceFullyResolvedImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a73aed7794053594cfb9536d55eac30fd">llvm::ELFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffobjectwriter/#a25ccd828a9ce444bcfcb33af6b1ffb37">llvm::WinCOFFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#ae083e4782d3a3ca6e98fbaacbb8d3f8f">llvm::WinCOFFWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment/#afb92a9a596bd11ffedfae405de2ee1ca">llvm::MCBoundaryAlignFragment::setLastFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### hasInstructions() {#acd02e61b262530ebe5c9a27ac0a0a693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCFragment::hasInstructions ()</td>
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

<p>Does this fragment have instructions emitted into it?</p>


<p>By default this is false, but specific fragment types may set it to true.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a47324e10b138f859b0fee6acf80bd979">HasInstructions</a>.</p>


<p>Referenced by <a href="#a73af1340aaefb3f64c1e4000ce6254e4">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#aed080c421ef7325c6e04a5bf027d9044">llvm::MCAssembler::writeFragmentPadding</a>.</p>

</div>
</div>

### setLayoutOrder() {#a6f660b772e3f52336835fe6256420705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCFragment::setLayoutOrder (unsigned Value)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### setParent() {#a47545378d5aa20fea6ea19963b436d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCFragment::setParent (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Value)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="#a6f1a6df46fca095e84bffe737ce4ef72">MCSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AlignToBundleEnd {#a063d6d412258d30d4ce0fcb37b645e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCFragment::AlignToBundleEnd</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#ab067e7ecede21fc252afdcc1eb282bfa">llvm::MCEncodedFragment::alignToBundleEnd</a>, <a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a91a7eddf74a4da82d1ce4ece79f49c61">llvm::MCEncodedFragment::setAlignToBundleEnd</a>.</p>

</div>
</div>

### AllowAutoPadding {#a9f7041d4aa87ae600ae5b28a4096dd9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCFragment::AllowAutoPadding</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a>: x86-specific.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#a6965f7a34449437c164118e26fb9fb64">llvm::MCRelaxableFragment::getAllowAutoPadding</a>, <a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#a366b703cdfb336b949488c63782c01e1">llvm::MCRelaxableFragment::setAllowAutoPadding</a>.</p>

</div>
</div>

### HasInstructions {#a47324e10b138f859b0fee6acf80bd979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCFragment::HasInstructions</td>
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

<p>Used by subclasses for better packing.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment">MCEncodedFragment</a></p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="#acd02e61b262530ebe5c9a27ac0a0a693">hasInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a17077f9e77e49104a7a6c08cc1a96cff">llvm::MCEncodedFragment::MCEncodedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a7054d0d6cace5c185998fbcdcd5c2f0a">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::MCEncodedFragmentWithFixups</a>, <a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a7a26478a3a6b526708c8b955e3cebd39">llvm::MCEncodedFragment::setHasInstructions</a>.</p>

</div>
</div>

### LinkerRelaxable {#a0aa9816583f9e76543cd195c5b0acffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCFragment::LinkerRelaxable</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/mcdatafragment">MCDataFragment</a>.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdatafragment/#a85e85a5ed8842dac08d3ff8c84f3ccb9">llvm::MCDataFragment::isLinkerRelaxable</a>, <a href="#a08c64d9919161955899f42fad75089dc">MCFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdatafragment/#a111e410bcefcbecc509d8e9fee6c477e">llvm::MCDataFragment::setLinkerRelaxable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a7c0a9aa7d8ac64226a0874401500e27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FragmentType llvm::MCFragment::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### LayoutOrder {#a1efbeaeceaf87436de9bd22a4691eca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCFragment::LayoutOrder = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The layout order of this fragment.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### Next {#a28b773d1b8f03855dea9fee3c9352bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment* llvm::MCFragment::Next = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### Offset {#a4c657506d3f434a1337b05b86fab9155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCFragment::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset of this fragment in its section.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### Parent {#ab897ca89ead9e7a024d5f4ea0ac623cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCFragment::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The data for the section this fragment is in.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcfragment-cpp">MCFragment.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
