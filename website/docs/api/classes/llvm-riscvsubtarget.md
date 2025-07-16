---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvsubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RISCVSubtarget` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">Target/RISCV/RISCVSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/riscvgensubtargetinfo">RISCVGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">RISCVProcFamilyEnum : uint8_t { <a href="#a362f8ead36d52e8761d070a41a39b699">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aeedbb2a07de13359931bcfa7ac874b">RISCVSubtarget</a> (const Triple &amp;TT, StringRef CPU, StringRef TuneCPU, StringRef FS, StringRef ABIName, unsigned RVVVectorBitsMin, unsigned RVVVectorLMULMax, const TargetMachine &amp;TM)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60048f2005766cfb5cc5de074ddac07">~RISCVSubtarget</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1eef4715bae7fe3cc35da63667375cc">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering">RISCVFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa43f5cea68a67fa22f1e814f604748d">getFrameLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo">RISCVInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1484b3b6dbf33deb1c526d456f1d256">getInstrInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo">RISCVRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac548025beac55d0f686dab8fa015e968">getRegisterInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering">RISCVTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2af8cfe3fcf89cb957885bfc303e8ae">getTargetLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87837dd4520a5b26084fcc881ac22c11">enableMachineScheduler</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefce96990585d8819e2702a563863889">enablePostRAScheduler</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bd4a14707e53de1514163e99bcf2a2">getPrefFunctionAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b38594f3617c7c36810057db1b9b592">getPrefLoopAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a362f8ead36d52e8761d070a41a39b699">RISCVProcFamilyEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65dd3e36612c10cbe66eb5ef824a597">getProcFamily</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns RISC-V processor family. <a href="#ab65dd3e36612c10cbe66eb5ef824a597">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa4dfd381666516aca9f87ba54353b7">hasStdExtCOrZca</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc81c9b952b9afcac875886f74435ba">hasStdExtCOrZcd</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a7b05ef975b869e6703599f0484e71">hasStdExtCOrZcfOrZce</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1863034a809e86649565f12f7262f26">hasStdExtZvl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc52fbf49e951e3cd085982bd57bdec">hasStdExtFOrZfinx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f78b0c873468bfa29ca2bf9a6249690">hasStdExtDOrZdinx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e6663a927a03c322e63064911ffb69">hasStdExtZfhOrZhinx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1e2c2f7d74d55ed4364b559a8ba936">hasStdExtZfhminOrZhinxmin</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af29a2ad8ab36cf0c7339ecf1803dfb90">hasHalfFPLoadStoreMove</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fdaeab72e0d5f5dba627042f433e417">hasConditionalMoveFusion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9fbb2a5a666589b2843c496f3ae479">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657dd2086f68037531f461853480fcf7">getXLenVT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc41e12851a645259c839ba8974bbe7">getXLen</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2d380dcba647a508c62a0655a01854">useLoadStorePairs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89299d08d61f8a76dbfcc9f159b09e6e">useCCMovInsn</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb186e5250943a7cde853ce5fb953cec">getFLen</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea13d382a3d0d0f975d218476ce499ae">getELen</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec69534e1dc21afa0aaa006323a7a0b">getRealMinVLen</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde732c96ba8d5e16bd6f142a4277edd">getRealMaxVLen</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa14643e5edb6a57a25bd223cc9ce6201">getRealVLen</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Quantity&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Quantity</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a81aea63feaef67ae0d43def88a62cf">expandVScale</a> (Quantity X) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> or <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> <span class="doxyComputerOutput">X</span> is scalable and VScale (VLEN) is exactly known, returns <span class="doxyComputerOutput">X</span> converted to a fixed quantity. <a href="#a4a81aea63feaef67ae0d43def88a62cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9">RISCVABI::ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042109b0e24a597548522e043ddd5e32">getTargetABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c45f1ce513b0b26a70031fdab7a0c9">isSoftFPABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e3b2db7eff9e6c2d104f1c69e37ed0">isRegisterReservedByUser</a> (Register i) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa238d66f84ea50dfff55e810683f1c01">isXRaySupported</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9227d5dccc1baf1834e4b98c5b9502e5">hasVInstructions</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f512c8f41efc281f156fa9d16b4d30f">hasVInstructionsI64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acffdf8ccaefb9abf0bf993e12f4f5a">hasVInstructionsF16Minimal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f216bb52e836a9222288ad723e4a8c2">hasVInstructionsF16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613dac4211cfe4be730d6eeae17508ba">hasVInstructionsBF16Minimal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a845763521dc55e82885dee62bf7b2">hasVInstructionsF32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2643e659475a1d2b1d2cb8aa2cdc7562">hasVInstructionsF64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a20374f2d3c442db2ac840088dd3b74">hasVInstructionsAnyF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a32b6dbac1aba561adcee67899f453">hasVInstructionsFullMultiply</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64cfc845bf060670e27d0370c48a19a">getMaxInterleaveFactor</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f6011f198db34f2721a50b5c979262">hasOptimizedSegmentLoadStore</a> (unsigned NF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618c76d324e0032cf850b0aec1b23706">getDLenFactor</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed42e4f48592d590ad1d0582f9a4739c">getSelectionDAGInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86cde408d11d9915b137c4e8cba0facc">getCallLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88541540ee7e0ef805182d0046f14c69">getInstructionSelector</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffb2584de0f2af385367245d5d1e4ab">getLegalizerInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo">RISCVRegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a859e3da9cdb9386addfe62f056a1474e">getRegBankInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2a6c84d6eb16ab6d4f4d54ae5950c9">isTargetAndroid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2226fd445e0ea519e49fe00211c0b4">isTargetFuchsia</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa45ce52d82a76626fd2af082a6fa52">useConstantPoolForLargeInts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88dc8b839aabb06854d711317cbbdac8">getMaxBuildIntsCost</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aca129a5e6a4d7fd2f6b2e70bc6e43f">getMaxLMULForFixedLengthVectors</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad0f5d235cb1bbabac4b7534c5c264c">useRVVForFixedLengthVectors</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9266d39a98a9bff394ac07b1b68a0d0">enableSubRegLiveness</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6cb603be3295a693acde423b89740ab">enableMachinePipeliner</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b899641adcffd8db95115244ef1566b">useDFAforSMS</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982c34f5a3a2e77f3a3bd58937bb3076">useAA</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.). <a href="#a982c34f5a3a2e77f3a3bd58937bb3076">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad23d39bcb81d170e6d7c8730e7425685">getCacheLineSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8aa94c39dafb0035b7dc409bde2d91">getPrefetchDistance</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1386d00db75760a9dc5819b1529366f">getMinPrefetchStride</a> (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f2ed3772983bc795ed43a07ee3f169">getMaxPrefetchIterationsAhead</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06aa72f98156d6988ba05b08f6b10bb3">getMinimumJumpTableEntries</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd1d359a581d3119be8ff699d197e71">getTailDupAggressiveThreshold</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f670322abe773cdba91e41b2cde522c">getMaxStoresPerMemset</a> (bool OptSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b5527a1307f4b57ea4cd452051f0f46">getMaxGluedStoresPerMemcpy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f66be42914cc613c3d155f451f2c9fc">getMaxStoresPerMemcpy</a> (bool OptSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a664455593170ca80ded2a41b082eeca3">getMaxStoresPerMemmove</a> (bool OptSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36423f436d55c9167094dfde5ce180e6">getMaxLoadsPerMemcmp</a> (bool OptSize) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3">MISched::Direction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560074e3f75f9c4e20f005c1848487c7">getPostRASchedDirection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5b05466a0b20a9ccb6ff4cf3476523">overrideSchedPolicy</a> (MachineSchedPolicy &amp;Policy, unsigned NumRegionInstrs) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86947dbacbd971019d8257dbfe60ce05">overridePostRASchedPolicy</a> (MachineSchedPolicy &amp;Policy, unsigned NumRegionInstrs) const override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8c58c51b71cc3be9ed385cd5b3023c">getMaxRVVVectorSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6751a4e61c691a8135fd00df58004016">getMinRVVVectorSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3a8d18273148bb946e9fa2f7b1fcbe">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0c6883f50c19e86d7d417da87ea94c">initializeSubtargetDependencies</a> (const Triple &amp;TT, StringRef CPU, StringRef TuneCPU, StringRef FS, StringRef ABIName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes using the passed in CPU and feature strings so that we can use initializer lists for subtarget initialization. <a href="#a0c0c6883f50c19e86d7d417da87ea94c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb587681f6e542538b71c19cd974fff">TSInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a2e85935aebd42dd415a8061583a3a">CallLoweringInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682696b4052b64944c95d9eed5c1edf4">InstSelector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ad2fffac917c44f45036052f93168d">Legalizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo">RISCVRegisterBankInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5f5dfb7178df88b1aa4304d37d2422">RegBankInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a362f8ead36d52e8761d070a41a39b699">RISCVProcFamilyEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a996dc726d267d80c6612b98704e6dc5e">RISCVProcFamily</a> = <a href="#a362f8ead36d52e8761d070a41a39b699ab2ab6f2a0f6a12a8c16763be7aaeddf1">Others</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ef85802084c074c70409c0cdf29a24">ZvlLen</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5c37cc421173f39b2b53923fc418c3">RVVVectorBitsMin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb63b74f33f766e5954a53944d25d86a">RVVVectorBitsMax</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72dd829e7b7476bf4fc04d3db99dbe25">MaxInterleaveFactor</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9">RISCVABI::ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a44fce7b23e5b904c465cded764de5">TargetABI</a> = <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829">RISCVABI::ABI_Unknown</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; RISCV::NUM_TARGET_REGS &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5bc2ea2c44075be6db268f9eb694ecc">UserReservedRegister</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/riscvtuneinfotable/riscvtuneinfo">RISCVTuneInfoTable::RISCVTuneInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a6912b6befec938ba3765c01f34681">TuneInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvframelowering">RISCVFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af41a8e638a2895c108586e0cbc8b113c">FrameLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo">RISCVInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df2cea8a6c393644760aabdd000fb22">InstrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo">RISCVRegisterInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2f3fe775c942a88cd1d0a8f7137663">RegInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering">RISCVTargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd587906d0f7388b175c7d870208a23">TLInfo</a></td>
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


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### RISCVProcFamilyEnum {#a362f8ead36d52e8761d070a41a39b699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVSubtarget::RISCVProcFamilyEnum : uint8_t</td>
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
<td class="doxyEnumItemName">Others<a id="a362f8ead36d52e8761d070a41a39b699ab2ab6f2a0f6a12a8c16763be7aaeddf1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SiFive7<a id="a362f8ead36d52e8761d070a41a39b699ac210740d1b4d841c7ee3cb153d622961"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VentanaVeyron<a id="a362f8ead36d52e8761d070a41a39b699a6bcfb1a06fd6518a1d37d671496119e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIPSP8700<a id="a362f8ead36d52e8761d070a41a39b699a948de7d63864205d049156ef80df1788"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RISCVSubtarget() {#a6aeedbb2a07de13359931bcfa7ac874b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVSubtarget::RISCVSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ABIName, unsigned RVVVectorBitsMin, unsigned RVVVectorLMULMax, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="#a8bb587681f6e542538b71c19cd974fff">TSInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RISCVSubtarget() {#ab60048f2005766cfb5cc5de074ddac07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVSubtarget::~RISCVSubtarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableMachinePipeliner() {#aa6cb603be3295a693acde423b89740ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVSubtarget::enableMachinePipeliner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>

</div>
</div>

### enableMachineScheduler() {#a87837dd4520a5b26084fcc881ac22c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::enableMachineScheduler ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### enablePostRAScheduler() {#aefce96990585d8819e2702a563863889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::enablePostRAScheduler ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### enableSubRegLiveness() {#ae9266d39a98a9bff394ac07b1b68a0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVSubtarget::enableSubRegLiveness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>

</div>
</div>

### expandVScale() {#a4a81aea63feaef67ae0d43def88a62cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Quantity&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Quantity llvm::RISCVSubtarget::expandVScale (Quantity X)</td>
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

<p>If the <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> or <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> <span class="doxyComputerOutput">X</span> is scalable and VScale (VLEN) is exactly known, returns <span class="doxyComputerOutput">X</span> converted to a fixed quantity.</p>


<p>Otherwise returns <span class="doxyComputerOutput">X</span> unmodified.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>References <a href="#aa14643e5edb6a57a25bd223cc9ce6201">getRealVLen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ad53ed145f88b1e1c966ff68df9029e7f">llvm::RISCV::RVVBitsPerBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### getCacheLineSize() {#ad23d39bcb81d170e6d7c8730e7425685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getCacheLineSize ()</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getCallLowering() {#a86cde408d11d9915b137c4e8cba0facc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallLowering * RISCVSubtarget::getCallLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="#ad3a2e85935aebd42dd415a8061583a3a">CallLoweringInfo</a> and <a href="#ae2af8cfe3fcf89cb957885bfc303e8ae">getTargetLowering</a>.</p>

</div>
</div>

### getDLenFactor() {#a618c76d324e0032cf850b0aec1b23706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getDLenFactor ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getELen() {#aea13d382a3d0d0f975d218476ce499ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getELen ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9227d5dccc1baf1834e4b98c5b9502e5">hasVInstructions</a> and <a href="#a1f512c8f41efc281f156fa9d16b4d30f">hasVInstructionsI64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a244716fab72ecb4d39dedd40cf1cff05">getContainerForFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2b002084e30ad9a9607108932eeae5e2">getWideningInterleave</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b77bb8d8bdd5dbaaf125f1afbd96ebd">isInterleaveShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aeed184a32cfc1dd279753d4a633bfba1">lowerBuildVectorViaPacking</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a897f4bf6b373f935cca5183ce7d4fd78">lowerGetVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### getFLen() {#afb186e5250943a7cde853ce5fb953cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getFLen ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>.</p>

</div>
</div>

### getFrameLowering() {#afa43f5cea68a67fa22f1e814f604748d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVFrameLowering * llvm::RISCVSubtarget::getFrameLowering ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a7a4a4089f8f04bc4d76b68399bdb6099">llvm::RISCVMachineFunctionInfo::RISCVMachineFunctionInfo</a>.</p>

</div>
</div>

### getInstrInfo() {#ad1484b3b6dbf33deb1c526d456f1d256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVInstrInfo * llvm::RISCVSubtarget::getInstrInfo ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a293e39e43b6f68064cdfd37061c84128">llvm::RISCVRegisterInfo::lowerVRELOAD</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a7238a4dd92fc1bb51c004c49c2b22263">llvm::RISCVRegisterInfo::lowerVSPILL</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmakecompressible-cpp-/riscvmakecompressibleopt/#a76561cc6613d04a06e24640760923da2">anonymous{RISCVMakeCompressible.cpp}::RISCVMakeCompressibleOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#ad200cfefbe78ae182babcc1c3211aa99">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a26b78c90211732e17d6b4d5adede3d62">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::runOnMachineFunction</a>.</p>

</div>
</div>

### getInstructionSelector() {#a88541540ee7e0ef805182d0046f14c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector * RISCVSubtarget::getInstructionSelector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3f16e5daf8352a4a822d023810d5598e">llvm::createRISCVInstructionSelector</a>, <a href="#a859e3da9cdb9386addfe62f056a1474e">getRegBankInfo</a> and <a href="#a682696b4052b64944c95d9eed5c1edf4">InstSelector</a>.</p>

</div>
</div>

### getLegalizerInfo() {#a0ffb2584de0f2af385367245d5d1e4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo * RISCVSubtarget::getLegalizerInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="#a18ad2fffac917c44f45036052f93168d">Legalizer</a>.</p>

</div>
</div>

### getMaxBuildIntsCost() {#a88dc8b839aabb06854d711317cbbdac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVSubtarget::getMaxBuildIntsCost ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp/#af4f3c9694d208796cfcf6bcee4415704">RISCVMaxBuildIntsCost</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab8b58d0a8c95d411d0f7aa891c9fd3f1">lowerConstant</a>.</p>

</div>
</div>

### getMaxGluedStoresPerMemcpy() {#a6b5527a1307f4b57ea4cd452051f0f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMaxGluedStoresPerMemcpy ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getMaxInterleaveFactor() {#ae64cfc845bf060670e27d0370c48a19a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMaxInterleaveFactor ()</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="#a9227d5dccc1baf1834e4b98c5b9502e5">hasVInstructions</a>.</p>

</div>
</div>

### getMaxLMULForFixedLengthVectors() {#a1aca129a5e6a4d7fd2f6b2e70bc6e43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVSubtarget::getMaxLMULForFixedLengthVectors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>, <a href="#a9227d5dccc1baf1834e4b98c5b9502e5">hasVInstructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp/#a95e0e3aeeac4cb4a88496748b440cc81">RVVVectorLMULMax</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### getMaxLoadsPerMemcmp() {#a36423f436d55c9167094dfde5ce180e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMaxLoadsPerMemcmp (bool OptSize)</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getMaxPrefetchIterationsAhead() {#a25f2ed3772983bc795ed43a07ee3f169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMaxPrefetchIterationsAhead ()</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getMaxStoresPerMemcpy() {#a2f66be42914cc613c3d155f451f2c9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMaxStoresPerMemcpy (bool OptSize)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getMaxStoresPerMemmove() {#a664455593170ca80ded2a41b082eeca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMaxStoresPerMemmove (bool OptSize)</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getMaxStoresPerMemset() {#a3f670322abe773cdba91e41b2cde522c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMaxStoresPerMemset (bool OptSize)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getMinimumJumpTableEntries() {#a06aa72f98156d6988ba05b08f6b10bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVSubtarget::getMinimumJumpTableEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp/#ac353e36085897c81990a8b53271a4e7b">RISCVMinimumJumpTableEntries</a>.</p>

</div>
</div>

### getMinPrefetchStride() {#ac1386d00db75760a9dc5819b1529366f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getMinPrefetchStride (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getPostRASchedDirection() {#a560074e3f75f9c4e20f005c1848487c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MISched::Direction llvm::RISCVSubtarget::getPostRASchedDirection ()</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#a86947dbacbd971019d8257dbfe60ce05">overridePostRASchedPolicy</a>.</p>

</div>
</div>

### getPrefetchDistance() {#afb8aa94c39dafb0035b7dc409bde2d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getPrefetchDistance ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getPrefFunctionAlignment() {#ab3bd4a14707e53de1514163e99bcf2a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RISCVSubtarget::getPrefFunctionAlignment ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getPrefLoopAlignment() {#a8b38594f3617c7c36810057db1b9b592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RISCVSubtarget::getPrefLoopAlignment ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getProcFamily() {#ab65dd3e36612c10cbe66eb5ef824a597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVProcFamilyEnum llvm::RISCVSubtarget::getProcFamily ()</td>
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

<p>Returns RISC-V processor family.</p>


<p>Avoid this function! CPU specifics should be kept local to this class and preferably modeled with <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> or properties in initializeProperties().</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getRealMaxVLen() {#abde732c96ba8d5e16bd6f142a4277edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getRealMaxVLen ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="#abc8c58c51b71cc3be9ed385cd5b3023c">getMaxRVVVectorSizeInBits</a>.</p>


<p>Referenced by <a href="#aa14643e5edb6a57a25bd223cc9ce6201">getRealVLen</a>.</p>

</div>
</div>

### getRealMinVLen() {#a3ec69534e1dc21afa0aaa006323a7a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getRealMinVLen ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="#a6751a4e61c691a8135fd00df58004016">getMinRVVVectorSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a244716fab72ecb4d39dedd40cf1cff05">getContainerForFixedLengthVector</a>, <a href="#aa14643e5edb6a57a25bd223cc9ce6201">getRealVLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa4640fbd4aeb9dc24896de22c21d652a">getSmallestVTForIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad228a0beee72778d8ea7dbd9de249158">isValidEGW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### getRealVLen() {#aa14643e5edb6a57a25bd223cc9ce6201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::RISCVSubtarget::getRealVLen ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>References <a href="#abde732c96ba8d5e16bd6f142a4277edd">getRealMaxVLen</a> and <a href="#a3ec69534e1dc21afa0aaa006323a7a0b">getRealMinVLen</a>.</p>


<p>Referenced by <a href="#a4a81aea63feaef67ae0d43def88a62cf">expandVScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a293e39e43b6f68064cdfd37061c84128">llvm::RISCVRegisterInfo::lowerVRELOAD</a> and <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a7238a4dd92fc1bb51c004c49c2b22263">llvm::RISCVRegisterInfo::lowerVSPILL</a>.</p>

</div>
</div>

### getRegBankInfo() {#a859e3da9cdb9386addfe62f056a1474e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVRegisterBankInfo * RISCVSubtarget::getRegBankInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="#acb5f5dfb7178df88b1aa4304d37d2422">RegBankInfo</a>.</p>


<p>Referenced by <a href="#a88541540ee7e0ef805182d0046f14c69">getInstructionSelector</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>.</p>

</div>
</div>

### getRegisterInfo() {#ac548025beac55d0f686dab8fa015e968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVRegisterInfo * llvm::RISCVSubtarget::getRegisterInfo ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#acec254d4fbb18621ee4d54f867af85f9">isConvertibleToVMV_V_V</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a293e39e43b6f68064cdfd37061c84128">llvm::RISCVRegisterInfo::lowerVRELOAD</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a7238a4dd92fc1bb51c004c49c2b22263">llvm::RISCVRegisterInfo::lowerVSPILL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a190dd3c890042807e4008b5bdd04927a">llvm::RISCVTargetLowering::RISCVTargetLowering</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#ad200cfefbe78ae182babcc1c3211aa99">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a26b78c90211732e17d6b4d5adede3d62">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::runOnMachineFunction</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#aed42e4f48592d590ad1d0582f9a4739c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionDAGTargetInfo * RISCVSubtarget::getSelectionDAGInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="#a8bb587681f6e542538b71c19cd974fff">TSInfo</a>.</p>

</div>
</div>

### getTailDupAggressiveThreshold() {#a3dd1d359a581d3119be8ff699d197e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getTailDupAggressiveThreshold ()</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### getTargetABI() {#a042109b0e24a597548522e043ddd5e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVABI::ABI llvm::RISCVSubtarget::getTargetABI ()</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a10b000ebfe8f8018565e8180e73d3a7d">CC_RISCVAssign2XLen</a>.</p>

</div>
</div>

### getTargetLowering() {#ae2af8cfe3fcf89cb957885bfc303e8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVTargetLowering * llvm::RISCVSubtarget::getTargetLowering ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a>, <a href="#a86cde408d11d9915b137c4e8cba0facc">getCallLowering</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#afa89bad4ae6c9667571ba16df07adf70">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getOrCreateExtendedOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3e9938aeee2aaef4ca5933920bb8c2af">isLegalBitRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvgatherscatterlowering-cpp-/riscvgatherscatterlowering/#a463122d7144f83fbbc69c99609fd2599">anonymous{RISCVGatherScatterLowering.cpp}::RISCVGatherScatterLowering::runOnFunction</a>.</p>

</div>
</div>

### getXLen() {#a6bc41e12851a645259c839ba8974bbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::getXLen ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="#afd9fbb2a5a666589b2843c496f3ae479">is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac1953eca2805574de12debdab3116430">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aeed184a32cfc1dd279753d4a633bfba1">lowerBuildVectorViaPacking</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4f2247785b2cfa91b42485591c4a71df">lowerFABSorFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a618e1a8b97a48a4cf1d6b8941823be50">lowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ace90a1ae5966f6c7a0830a440698d4c5">performBITREVERSECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acedf14c0b42fdeea7ed01a8a6e051299">transformAddImmMulImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab64eb471c9d5a9db3c882d6bed499ddd">transformAddShlImm</a>.</p>

</div>
</div>

### getXLenVT() {#a657dd2086f68037531f461853480fcf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::RISCVSubtarget::getXLenVT ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="#afd9fbb2a5a666589b2843c496f3ae479">is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a45e6e22e05efa275135c8ae32f60da40">buildDefaultVLOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad34d9541b1000d244dd78e0cf23b45ea">combine_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6d9136998f9ff100ad8449a69477ab94">combineScalarCTPOPToVCPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5efc2b9d3d3b40b85f5f7366bc145837">combineSubShiftToOrcB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a905bf60f4a852a875fe2058dec3494c3">convertFromScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a38a4767fc581ef400cbef34ac25d9f6c">expandMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a8985b59d609a1b923fce5c512026b7e8">getDefaultScalableVLOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a799736eea326f07eee562702205360a3">getDefaultVLOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#afde9480139004244c156f9f6357a9611">getVSlidedown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac5eaf594a776b0cf7ea967fbe443be1f">getVSlideup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2b002084e30ad9a9607108932eeae5e2">getWideningInterleave</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af387d765ff63b855d2acab54f7ec7f47">lowerBuildVectorViaDominantValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aeed184a32cfc1dd279753d4a633bfba1">lowerBuildVectorViaPacking</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a948a1ca16b9bc0cfc5c513197f92b4a7">lowerCttzElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a47c057e00771d3428bba280de009c4c8">lowerDisjointIndicesShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4f2247785b2cfa91b42485591c4a71df">lowerFABSorFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a618e1a8b97a48a4cf1d6b8941823be50">lowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4ff956cb752e5161a4058793dd3beff7">lowerFMAXIMUM_FMINIMUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b112e0384ad2aeacb1e414e37695c6b">lowerFP_TO_INT_SAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abec179193cc8369e33418e87154d7d04">lowerFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a897f4bf6b373f935cca5183ce7d4fd78">lowerGetVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a82c6255bfa9b041c0fb327435a4d7272">lowerReductionSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab39855d189957c348ae6db001226dc8f">lowerScalarInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a31daee0d0756aea8c392995d14f8fbf9">lowerScalarSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a10f91530b8b44cb2811821da0f0ca280">lowerVECTOR_SHUFFLEAsVSlide1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5c0b59043e612b22bd1b30c674325afa">lowerVECTOR_SHUFFLEAsVSlidedown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#add5b44a9fa06b625d7242da3a08957e8">lowerVECTOR_SHUFFLEAsVSlideup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe950951aec4aa71b14f89b89d26eae0">lowerVectorFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a95bb2318cffbd613f244603838b30094">lowerVectorIntrinsicScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acc354c12306e08991c73849216e09f78">lowerVectorStrictFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9850b320a9762bd0eac97a4469122838">lowerVectorXRINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad1d5172c0e53a85688cd701b1677dddf">matchSplatAsGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7fca4dc2eee895ba0f0cc33cd3ca6c4d">performFP_TO_INT_SATCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aed0a6ba299e2e585945210e2c39ac2ef">performFP_TO_INTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ada4201742fab8916f9da75acd2b58fc1">performSRACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a84a7819a9f36f529085ab85492b5a4d7">performVP_REVERSECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90e158dcd9e3da205b3703145ed4cfcb">performVP_STORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1e4c4f01eb41b2197d78ab15c9dd7b4c">promoteVCIXScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae7edfd8337d702eebfdbf7010c3b2c74">tryMemPairCombine</a>.</p>

</div>
</div>

### hasConditionalMoveFusion() {#a6fdaeab72e0d5f5dba627042f433e417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasConditionalMoveFusion ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="#a0aa4dfd381666516aca9f87ba54353b7">hasStdExtCOrZca</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac1953eca2805574de12debdab3116430">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a72f1d6515236af504f465f5b35249e2b">combineSelectToBinOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac82e376bb0f509a7df81b213df951293">performSELECTCombine</a>.</p>

</div>
</div>

### hasHalfFPLoadStoreMove() {#af29a2ad8ab36cf0c7339ecf1803dfb90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasHalfFPLoadStoreMove ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### hasOptimizedSegmentLoadStore() {#aa8f6011f198db34f2721a50b5c979262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasOptimizedSegmentLoadStore (unsigned NF)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### hasStdExtCOrZca() {#a0aa4dfd381666516aca9f87ba54353b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtCOrZca ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#aa72d59e703230d33686b9e5b1c0973ea">estimateFunctionSizeInBytes</a>, <a href="#a6fdaeab72e0d5f5dba627042f433e417">hasConditionalMoveFusion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a2d9f47f05b39d7fae4d54d338ce32caa">isCompressibleLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a512924d8725f22c9bf0e2533214ad6b6">isCompressibleStore</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvmakecompressible-cpp-/riscvmakecompressibleopt/#a76561cc6613d04a06e24640760923da2">anonymous{RISCVMakeCompressible.cpp}::RISCVMakeCompressibleOpt::runOnMachineFunction</a>.</p>

</div>
</div>

### hasStdExtCOrZcd() {#adcc81c9b952b9afcac875886f74435ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtCOrZcd ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a2d9f47f05b39d7fae4d54d338ce32caa">isCompressibleLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a512924d8725f22c9bf0e2533214ad6b6">isCompressibleStore</a>.</p>

</div>
</div>

### hasStdExtCOrZcfOrZce() {#ab2a7b05ef975b869e6703599f0484e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtCOrZcfOrZce ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a2d9f47f05b39d7fae4d54d338ce32caa">isCompressibleLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a512924d8725f22c9bf0e2533214ad6b6">isCompressibleStore</a>.</p>

</div>
</div>

### hasStdExtDOrZdinx() {#a2f78b0c873468bfa29ca2bf9a6249690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtDOrZdinx ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### hasStdExtFOrZfinx() {#aefc52fbf49e951e3cd085982bd57bdec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtFOrZfinx ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### hasStdExtZfhminOrZhinxmin() {#abd1e2c2f7d74d55ed4364b559a8ba936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtZfhminOrZhinxmin ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### hasStdExtZfhOrZhinx() {#a36e6663a927a03c322e63064911ffb69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtZfhOrZhinx ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad8cbb97883279338e0a8bb99e38bbd4d">lowerFP_TO_INT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b112e0384ad2aeacb1e414e37695c6b">lowerFP_TO_INT_SAT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe5865f3d9d2bb4ef6147178a360b1e8">lowerINT_TO_FP</a>.</p>

</div>
</div>

### hasStdExtZvl() {#af1863034a809e86649565f12f7262f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasStdExtZvl ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### hasVInstructions() {#a9227d5dccc1baf1834e4b98c5b9502e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructions ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a672b2d48b831e2db6310036e4bf711d0">llvm::RISCVCallLowering::canLowerReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="#aea13d382a3d0d0f975d218476ce499ae">getELen</a>, <a href="#ae64cfc845bf060670e27d0370c48a19a">getMaxInterleaveFactor</a>, <a href="#a1aca129a5e6a4d7fd2f6b2e70bc6e43f">getMaxLMULForFixedLengthVectors</a>, <a href="#abc8c58c51b71cc3be9ed385cd5b3023c">getMaxRVVVectorSizeInBits</a>, <a href="#a6751a4e61c691a8135fd00df58004016">getMinRVVVectorSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af59f353dd1adb78d8e0187803c5edb83">getScavSlotsNumForRVV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a2abf3deda7636d63c863cee5508d57e7">isSupportedArgumentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a13ed6ec6cd0ee09fee7023d96d80a823">isSupportedReturnType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a95bb2318cffbd613f244603838b30094">lowerVectorIntrinsicScalars</a> and <a href="#a4ad0f5d235cb1bbabac4b7534c5c264c">useRVVForFixedLengthVectors</a>.</p>

</div>
</div>

### hasVInstructionsAnyF() {#a9a20374f2d3c442db2ac840088dd3b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsAnyF ()</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="#ae5a845763521dc55e82885dee62bf7b2">hasVInstructionsF32</a>.</p>

</div>
</div>

### hasVInstructionsBF16Minimal() {#a613dac4211cfe4be730d6eeae17508ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsBF16Minimal ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### hasVInstructionsF16() {#a7f216bb52e836a9222288ad723e4a8c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsF16 ()</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7f474c75e4f6f415f391e9676c849935">isPromotedOpNeedingSplit</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#adb5a1dc721c95f38cb7951e826d9e646">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedFPExtend</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a10f91530b8b44cb2811821da0f0ca280">lowerVECTOR_SHUFFLEAsVSlide1</a>.</p>

</div>
</div>

### hasVInstructionsF16Minimal() {#a6acffdf8ccaefb9abf0bf993e12f4f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsF16Minimal ()</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7f474c75e4f6f415f391e9676c849935">isPromotedOpNeedingSplit</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### hasVInstructionsF32() {#ae5a845763521dc55e82885dee62bf7b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsF32 ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9a20374f2d3c442db2ac840088dd3b74">hasVInstructionsAnyF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### hasVInstructionsF64() {#a2643e659475a1d2b1d2cb8aa2cdc7562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsF64 ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### hasVInstructionsFullMultiply() {#ae2a32b6dbac1aba561adcee67899f453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsFullMultiply ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### hasVInstructionsI64() {#a1f512c8f41efc281f156fa9d16b4d30f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::hasVInstructionsI64 ()</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#aea13d382a3d0d0f975d218476ce499ae">getELen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

### is64Bit() {#afd9fbb2a5a666589b2843c496f3ae479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::is64Bit ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a04866da4b47769738d66f9d25fcf7304">llvm::CC_RISCV_GHC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#abbd64fe331cf0d150d28e127653d700c">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::fillUpExtensionSupportForSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1d62502e1f5ca4bf6fbc50c225799b19">getPACKOpcode</a>, <a href="#a6bc41e12851a645259c839ba8974bbe7">getXLen</a>, <a href="#a657dd2086f68037531f461853480fcf7">getXLenVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a2d9f47f05b39d7fae4d54d338ce32caa">isCompressibleLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a512924d8725f22c9bf0e2533214ad6b6">isCompressibleStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c93589d74f9163f56f3f1200bcf9ad6">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2caf0087e5ae1170754a8a4503df9a98">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9843d498d81fb04dfb533d4702589ae8">performSIGN_EXTEND_INREGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aef2ca69d18797d6709fade0d00b0a286">performTRUNCATECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6659c72985a2b34b2b0714641762ef21">performXORCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a>.</p>

</div>
</div>

### isRegisterReservedByUser() {#a98e3b2db7eff9e6c2d104f1c69e37ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::isRegisterReservedByUser (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> i)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>.</p>

</div>
</div>

### isSoftFPABI() {#af1c45f1ce513b0b26a70031fdab7a0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::isSoftFPABI ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a8f2e55f34742f82eeaa55cbd79d44c0e">llvm::RISCVABI::ABI_ILP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a9e062b1814798f2a29e2b28e74a36bc1">llvm::RISCVABI::ABI_ILP32E</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9ae72b691ee57f47810281dffc97cbde06">llvm::RISCVABI::ABI_LP64</a>.</p>

</div>
</div>

### isTargetAndroid() {#aef2a6c84d6eb16ab6d4f4d54ae5950c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::isTargetAndroid ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### isTargetFuchsia() {#a5c2226fd445e0ea519e49fe00211c0b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::isTargetFuchsia ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### isXRaySupported() {#aa238d66f84ea50dfff55e810683f1c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::isXRaySupported ()</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### overridePostRASchedPolicy() {#a86947dbacbd971019d8257dbfe60ce05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVSubtarget::overridePostRASchedPolicy (<a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a> &amp; Policy, unsigned NumRegionInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3aab012f17d1537ed7a7c6d45b1d2fc0e9">llvm::MISched::Bidirectional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3abd98ce24773c9ca1e3f7ce3c541e43ea">llvm::MISched::BottomUp</a>, <a href="#a560074e3f75f9c4e20f005c1848487c7">getPostRASchedDirection</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a47ee8ec29daa3551f798ff4449fbf4d5">llvm::MachineSchedPolicy::OnlyBottomUp</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a0f609dd4ed94ea69ab680a7228f8786b">llvm::MachineSchedPolicy::OnlyTopDown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3ae89742249a15ad5696e3dcec82f0e76a">llvm::MISched::TopDown</a>.</p>

</div>
</div>

### overrideSchedPolicy() {#a8b5b05466a0b20a9ccb6ff4cf3476523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVSubtarget::overrideSchedPolicy (<a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a> &amp; Policy, unsigned NumRegionInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a2600398bcf6d98dea6035e652870b41a">llvm::MachineSchedPolicy::DisableLatencyHeuristic</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a47ee8ec29daa3551f798ff4449fbf4d5">llvm::MachineSchedPolicy::OnlyBottomUp</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a0f609dd4ed94ea69ab680a7228f8786b">llvm::MachineSchedPolicy::OnlyTopDown</a> and <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#aee4e3964174cee8cf362508ccef135ca">llvm::MachineSchedPolicy::ShouldTrackPressure</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#ac1eef4715bae7fe3cc35da63667375cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RISCVSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### useAA() {#a982c34f5a3a2e77f3a3bd58937bb3076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVSubtarget::useAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.).</p>

<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#ad59a2062ef349882aa9c631277e37a74">UseAA</a>.</p>

</div>
</div>

### useCCMovInsn() {#a89299d08d61f8a76dbfcc9f159b09e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVSubtarget::useCCMovInsn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp/#ad455ee87b0026128277a488ae02149ec">UseCCMovInsn</a>.</p>

</div>
</div>

### useConstantPoolForLargeInts() {#aaaa45ce52d82a76626fd2af082a6fa52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVSubtarget::useConstantPoolForLargeInts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp/#ae185af4e4a53e20ec8cea68f37079805">RISCVDisableUsingConstantPoolForLargeInts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab8b58d0a8c95d411d0f7aa891c9fd3f1">lowerConstant</a>.</p>

</div>
</div>

### useDFAforSMS() {#a3b899641adcffd8db95115244ef1566b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::useDFAforSMS ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### useLoadStorePairs() {#a9d2d380dcba647a508c62a0655a01854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVSubtarget::useLoadStorePairs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### useRVVForFixedLengthVectors() {#a4ad0f5d235cb1bbabac4b7534c5c264c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVSubtarget::useRVVForFixedLengthVectors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="#a6751a4e61c691a8135fd00df58004016">getMinRVVVectorSizeInBits</a>, <a href="#a9227d5dccc1baf1834e4b98c5b9502e5">hasVInstructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ad53ed145f88b1e1c966ff68df9029e7f">llvm::RISCV::RVVBitsPerBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa588bb9a1fc19299a7e3af33acc5f9ba">useRVVForFixedLengthVectorVT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getMaxRVVVectorSizeInBits() {#abc8c58c51b71cc3be9ed385cd5b3023c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVSubtarget::getMaxRVVVectorSizeInBits ()</td>
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



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9227d5dccc1baf1834e4b98c5b9502e5">hasVInstructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#abde732c96ba8d5e16bd6f142a4277edd">getRealMaxVLen</a>.</p>

</div>
</div>

### getMinRVVVectorSizeInBits() {#a6751a4e61c691a8135fd00df58004016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVSubtarget::getMinRVVVectorSizeInBits ()</td>
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



<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9227d5dccc1baf1834e4b98c5b9502e5">hasVInstructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a3ec69534e1dc21afa0aaa006323a7a0b">getRealMinVLen</a> and <a href="#a4ad0f5d235cb1bbabac4b7534c5c264c">useRVVForFixedLengthVectors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a7c3a8d18273148bb946e9fa2f7b1fcbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVSubtarget::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#a0c0c6883f50c19e86d7d417da87ea94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVSubtarget &amp; RISCVSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ABIName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializes using the passed in CPU and feature strings so that we can use initializer lists for subtarget initialization.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CallLoweringInfo {#ad3a2e85935aebd42dd415a8061583a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallLowering&gt; llvm::RISCVSubtarget::CallLoweringInfo</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#a86cde408d11d9915b137c4e8cba0facc">getCallLowering</a>.</p>

</div>
</div>

### InstSelector {#a682696b4052b64944c95d9eed5c1edf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstructionSelector&gt; llvm::RISCVSubtarget::InstSelector</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#a88541540ee7e0ef805182d0046f14c69">getInstructionSelector</a>.</p>

</div>
</div>

### Legalizer {#a18ad2fffac917c44f45036052f93168d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalizerInfo&gt; llvm::RISCVSubtarget::Legalizer</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0ffb2584de0f2af385367245d5d1e4ab">getLegalizerInfo</a>.</p>

</div>
</div>

### RegBankInfo {#acb5f5dfb7178df88b1aa4304d37d2422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RISCVRegisterBankInfo&gt; llvm::RISCVSubtarget::RegBankInfo</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#a859e3da9cdb9386addfe62f056a1474e">getRegBankInfo</a>.</p>

</div>
</div>

### TSInfo {#a8bb587681f6e542538b71c19cd974fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const SelectionDAGTargetInfo&gt; llvm::RISCVSubtarget::TSInfo</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>


<p>Referenced by <a href="#aed42e4f48592d590ad1d0582f9a4739c">getSelectionDAGInfo</a> and <a href="#a6aeedbb2a07de13359931bcfa7ac874b">RISCVSubtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FrameLowering {#af41a8e638a2895c108586e0cbc8b113c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVFrameLowering llvm::RISCVSubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#a2df2cea8a6c393644760aabdd000fb22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVInstrInfo llvm::RISCVSubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### MaxInterleaveFactor {#a72dd829e7b7476bf4fc04d3db99dbe25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::RISCVSubtarget::MaxInterleaveFactor = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### RegInfo {#a9b2f3fe775c942a88cd1d0a8f7137663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVRegisterInfo llvm::RISCVSubtarget::RegInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### RISCVProcFamily {#a996dc726d267d80c6612b98704e6dc5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVProcFamilyEnum llvm::RISCVSubtarget::RISCVProcFamily = <a href="#a362f8ead36d52e8761d070a41a39b699ab2ab6f2a0f6a12a8c16763be7aaeddf1">Others</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### RVVVectorBitsMax {#abb63b74f33f766e5954a53944d25d86a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::RVVVectorBitsMax</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### RVVVectorBitsMin {#a1c5c37cc421173f39b2b53923fc418c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::RVVVectorBitsMin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### TargetABI {#a90a44fce7b23e5b904c465cded764de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVABI::ABI llvm::RISCVSubtarget::TargetABI = <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829">RISCVABI::ABI_Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#a7cd587906d0f7388b175c7d870208a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVTargetLowering llvm::RISCVSubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### TuneInfo {#ad7a6912b6befec938ba3765c01f34681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVTuneInfoTable::RISCVTuneInfo* llvm::RISCVSubtarget::TuneInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### UserReservedRegister {#ab5bc2ea2c44075be6db268f9eb694ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;RISCV::NUM_TARGET_REGS&gt; llvm::RISCVSubtarget::UserReservedRegister</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

### ZvlLen {#a75ef85802084c074c70409c0cdf29a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVSubtarget::ZvlLen = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-cpp">RISCVSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
