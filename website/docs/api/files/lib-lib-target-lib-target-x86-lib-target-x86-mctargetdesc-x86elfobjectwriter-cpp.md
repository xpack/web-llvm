---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `X86ELFObjectWriter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86fixupkinds-h">MCTargetDesc/X86FixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">MCTargetDesc/X86MCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">llvm/MC/MCFixup.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86elfobjectwriter-cpp-">anonymous{X86ELFObjectWriter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86elfobjectwriter-cpp-/x86elfobjectwriter">X86ELFObjectWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">X86_64RelType { <a href="#a699265f793024e284dffcb9285ed80b3">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">X86_32RelType { <a href="#aade30633c3798cd32b0030749beb242e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a699265f793024e284dffcb9285ed80b3">X86_64RelType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c006bc6dbff23aa42d99f00194f2540">getType64</a> (MCFixupKind Kind, MCSymbolRefExpr::VariantKind &amp;Modifier, bool &amp;IsPCRel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae332273aae9436156b17f8d5e090e2">checkIs32</a> (MCContext &amp;Ctx, SMLoc Loc, X86_64RelType Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce1fab4e3b72fb321503c9c38b8d82e">checkIs64</a> (MCContext &amp;Ctx, SMLoc Loc, X86_64RelType Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b572e067c869cffa4bc0a02b5813ff">getRelocType64</a> (MCContext &amp;Ctx, SMLoc Loc, MCSymbolRefExpr::VariantKind Modifier, X86_64RelType Type, bool IsPCRel, MCFixupKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4ff31dc184d0b06bd11399d38e5c46">getRelocType32</a> (MCContext &amp;Ctx, SMLoc Loc, MCSymbolRefExpr::VariantKind Modifier, X86_32RelType Type, bool IsPCRel, MCFixupKind Kind)</td>
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

### X86\_32RelType {#aade30633c3798cd32b0030749beb242e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum X86_32RelType </td>
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
<td class="doxyEnumItemName">RT32_NONE<a id="aade30633c3798cd32b0030749beb242ea909d046afc92361f343eb2aa6b60d883"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT32_32<a id="aade30633c3798cd32b0030749beb242eaf285f206e4f3a2621feaf1440aad9ad3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT32_16<a id="aade30633c3798cd32b0030749beb242ea3f7cee58c28ce70b48f74c90c8753eae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT32_8<a id="aade30633c3798cd32b0030749beb242ea509675896dedf422e81c83fbaf217861"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp">X86ELFObjectWriter.cpp</a>.</p>

</div>
</div>

### X86\_64RelType {#a699265f793024e284dffcb9285ed80b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum X86_64RelType </td>
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
<td class="doxyEnumItemName">RT64_NONE<a id="a699265f793024e284dffcb9285ed80b3a055ce5b0ff605660162286efc860307d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT64_64<a id="a699265f793024e284dffcb9285ed80b3a50d317a110baa27feed214be396e4389"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT64_32<a id="a699265f793024e284dffcb9285ed80b3aa8a4f4402071dde692f12ff3a9d8b597"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT64_32S<a id="a699265f793024e284dffcb9285ed80b3abd7f3add94d3488bbca971cae2b915a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT64_16<a id="a699265f793024e284dffcb9285ed80b3a2d90947b32363f1af372265efb17794a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT64_8<a id="a699265f793024e284dffcb9285ed80b3aa204625d985eadc6f4a495a4b18e0b0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp">X86ELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### checkIs32() {#aaae332273aae9436156b17f8d5e090e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkIs32 (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="#a699265f793024e284dffcb9285ed80b3">X86_64RelType</a> Type)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp">X86ELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="#a699265f793024e284dffcb9285ed80b3aa8a4f4402071dde692f12ff3a9d8b597">RT64_32</a>.</p>


<p>Referenced by <a href="#af5b572e067c869cffa4bc0a02b5813ff">getRelocType64</a>.</p>

</div>
</div>

### checkIs64() {#a6ce1fab4e3b72fb321503c9c38b8d82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkIs64 (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="#a699265f793024e284dffcb9285ed80b3">X86_64RelType</a> Type)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp">X86ELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="#a699265f793024e284dffcb9285ed80b3a50d317a110baa27feed214be396e4389">RT64_64</a>.</p>


<p>Referenced by <a href="#af5b572e067c869cffa4bc0a02b5813ff">getRelocType64</a>.</p>

</div>
</div>

### getRelocType32() {#adf4ff31dc184d0b06bd11399d38e5c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getRelocType32 (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> Modifier, <a href="#aade30633c3798cd32b0030749beb242e">X86_32RelType</a> Type, bool IsPCRel, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp">X86ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca372de3ecc0967f0c818089f93138a0de">llvm::X86::reloc_signed_4byte_relax</a>, <a href="#aade30633c3798cd32b0030749beb242ea3f7cee58c28ce70b48f74c90c8753eae">RT32_16</a>, <a href="#aade30633c3798cd32b0030749beb242eaf285f206e4f3a2621feaf1440aad9ad3">RT32_32</a>, <a href="#aade30633c3798cd32b0030749beb242ea509675896dedf422e81c83fbaf217861">RT32_8</a>, <a href="#aade30633c3798cd32b0030749beb242ea909d046afc92361f343eb2aa6b60d883">RT32_NONE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a005feb527dcbfd0ff9cb36d5926259b5">llvm::MCSymbolRefExpr::VK_DTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a39bde642c4c205e820490b44c7c99eaf">llvm::MCSymbolRefExpr::VK_GOTNTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62">llvm::MCSymbolRefExpr::VK_GOTOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8ab1ea9815c9a2bbe67f215b5ee2f680">llvm::MCSymbolRefExpr::VK_GOTTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a542605f9315d7c837ffdf0db3d36ab00">llvm::MCSymbolRefExpr::VK_INDNTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ad51962e40d9ba19993f108197dd65f57">llvm::MCSymbolRefExpr::VK_NTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a03bfc9e15ea1f28db8231b2259bac14d">llvm::MCSymbolRefExpr::VK_TLSCALL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0dfb6ffd20ec6e759a99ca36206fc27b">llvm::MCSymbolRefExpr::VK_TLSDESC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab2e079373e7edad956ec4feb0587658e">llvm::MCSymbolRefExpr::VK_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a3edde5344c6385f99e6b4f7606b79048">llvm::MCSymbolRefExpr::VK_TLSLDM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aab276e610bb8711df7b2a9565411b2f3">llvm::MCSymbolRefExpr::VK_TPOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a02786fddb19ccf9f05859236b8d4d23f">llvm::MCSymbolRefExpr::VK_X86_ABS8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86elfobjectwriter-cpp-/x86elfobjectwriter/#a4d354a06d39b9d042b7d4e830f688988">anonymous{X86ELFObjectWriter.cpp}::X86ELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getRelocType64() {#af5b572e067c869cffa4bc0a02b5813ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getRelocType64 (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> Modifier, <a href="#a699265f793024e284dffcb9285ed80b3">X86_64RelType</a> Type, bool IsPCRel, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp">X86ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaae332273aae9436156b17f8d5e090e2">checkIs32</a>, <a href="#a6ce1fab4e3b72fb321503c9c38b8d82e">checkIs64</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcacd0ed684ad2d4c067ca938d45567540c">llvm::X86::reloc_riprel_4byte_movq_load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca303862a22911ad0a16f5f88c89d7c105">llvm::X86::reloc_riprel_4byte_movq_load_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca711b77689359fcf4cb49f96b5571d5c0">llvm::X86::reloc_riprel_4byte_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca7b4bcca3a40ad945a73f1c1d199c6362">llvm::X86::reloc_riprel_4byte_relax_evex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca962ed593088a527512dad825d971922e">llvm::X86::reloc_riprel_4byte_relax_rex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea71f97aa32a2a3fabf01372d4079a5c">llvm::X86::reloc_riprel_4byte_relax_rex2</a>, <a href="#a699265f793024e284dffcb9285ed80b3a2d90947b32363f1af372265efb17794a">RT64_16</a>, <a href="#a699265f793024e284dffcb9285ed80b3aa8a4f4402071dde692f12ff3a9d8b597">RT64_32</a>, <a href="#a699265f793024e284dffcb9285ed80b3abd7f3add94d3488bbca971cae2b915a1">RT64_32S</a>, <a href="#a699265f793024e284dffcb9285ed80b3a50d317a110baa27feed214be396e4389">RT64_64</a>, <a href="#a699265f793024e284dffcb9285ed80b3aa204625d985eadc6f4a495a4b18e0b0f">RT64_8</a>, <a href="#a699265f793024e284dffcb9285ed80b3a055ce5b0ff605660162286efc860307d">RT64_NONE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a005feb527dcbfd0ff9cb36d5926259b5">llvm::MCSymbolRefExpr::VK_DTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62">llvm::MCSymbolRefExpr::VK_GOTOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2f5bfabdc7c07641d263e7f3921de0f5">llvm::MCSymbolRefExpr::VK_GOTPCREL_NORELAX</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8ab1ea9815c9a2bbe67f215b5ee2f680">llvm::MCSymbolRefExpr::VK_GOTTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ae82d65eb3584ba7c4f28110e5f033763">llvm::MCSymbolRefExpr::VK_SIZE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a03bfc9e15ea1f28db8231b2259bac14d">llvm::MCSymbolRefExpr::VK_TLSCALL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0dfb6ffd20ec6e759a99ca36206fc27b">llvm::MCSymbolRefExpr::VK_TLSDESC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab2e079373e7edad956ec4feb0587658e">llvm::MCSymbolRefExpr::VK_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2bd18a4543b4686a238d7c84cf299257">llvm::MCSymbolRefExpr::VK_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aab276e610bb8711df7b2a9565411b2f3">llvm::MCSymbolRefExpr::VK_TPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a02786fddb19ccf9f05859236b8d4d23f">llvm::MCSymbolRefExpr::VK_X86_ABS8</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aec6e66cd0fb96e202f1a13f25bf29cbf">llvm::MCSymbolRefExpr::VK_X86_PLTOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86elfobjectwriter-cpp-/x86elfobjectwriter/#a4d354a06d39b9d042b7d4e830f688988">anonymous{X86ELFObjectWriter.cpp}::X86ELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getType64() {#a7c006bc6dbff23aa42d99f00194f2540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86_64RelType getType64 (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> &amp; Modifier, bool &amp; IsPCRel)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86elfobjectwriter-cpp">X86ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac6095ed6f2c30887aef8adc449b1efa5">llvm::FK_PCRel_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca3b2a5a68543379e2c0ecada70a114244">llvm::X86::reloc_branch_4byte_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcac5689c8a9dd3bf74dbf81b1f3d34b158">llvm::X86::reloc_global_offset_table</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca178b428b67d947f825484889ea7fae1a">llvm::X86::reloc_global_offset_table8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea3ac30c46fc4086e0fac8473ece1f8b">llvm::X86::reloc_riprel_4byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcacd0ed684ad2d4c067ca938d45567540c">llvm::X86::reloc_riprel_4byte_movq_load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca303862a22911ad0a16f5f88c89d7c105">llvm::X86::reloc_riprel_4byte_movq_load_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca711b77689359fcf4cb49f96b5571d5c0">llvm::X86::reloc_riprel_4byte_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca7b4bcca3a40ad945a73f1c1d199c6362">llvm::X86::reloc_riprel_4byte_relax_evex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca962ed593088a527512dad825d971922e">llvm::X86::reloc_riprel_4byte_relax_rex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea71f97aa32a2a3fabf01372d4079a5c">llvm::X86::reloc_riprel_4byte_relax_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca8b029ea6e687fd2d4caf13cbbe2cde08">llvm::X86::reloc_signed_4byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca372de3ecc0967f0c818089f93138a0de">llvm::X86::reloc_signed_4byte_relax</a>, <a href="#a699265f793024e284dffcb9285ed80b3a2d90947b32363f1af372265efb17794a">RT64_16</a>, <a href="#a699265f793024e284dffcb9285ed80b3aa8a4f4402071dde692f12ff3a9d8b597">RT64_32</a>, <a href="#a699265f793024e284dffcb9285ed80b3abd7f3add94d3488bbca971cae2b915a1">RT64_32S</a>, <a href="#a699265f793024e284dffcb9285ed80b3a50d317a110baa27feed214be396e4389">RT64_64</a>, <a href="#a699265f793024e284dffcb9285ed80b3aa204625d985eadc6f4a495a4b18e0b0f">RT64_8</a>, <a href="#a699265f793024e284dffcb9285ed80b3a055ce5b0ff605660162286efc860307d">RT64_NONE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86elfobjectwriter-cpp-/x86elfobjectwriter/#a4d354a06d39b9d042b7d4e830f688988">anonymous{X86ELFObjectWriter.cpp}::X86ELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
