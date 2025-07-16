---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbolelf
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSymbolELF` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbolELF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">llvm/MC/MCSymbolELF.h</a>"
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5409f62668af4a8e307fe9149e1ff92">MCSymbolELF</a> (const MCSymbolTableEntry *Name, bool isTemporary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63edf630bae30668b44c9be9a85cb9a8">setSize</a> (const MCExpr *SS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83461ac06968f969da6b77b0e3e90527">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d355b38e3f57001fdbce9f13846a04">setVisibility</a> (unsigned Visibility)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2f34e14532817ad86d5c8f3b179c2a">getVisibility</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed9abfbf50800b7378713d657bf0cf5a">setOther</a> (unsigned Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2badd3f8011db90045f7be286331125f">getOther</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed759e9547e045f0bd987987de0f76bc">setType</a> (unsigned Type) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c716684711cb83467c2138bc4e84454">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1edee41b5f81ab31451e8bf98a3a3e6">setBinding</a> (unsigned Binding) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae357568bfa7baaa244f16208924f4637">getBinding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666e25e11bd035c93786545bec5ce44e">isBindingSet</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bbad98aac843f2c52cd716efdde45e5">setIsWeakrefUsedInReloc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e683b1f93c043f9fb48cdc47e736fb2">isWeakrefUsedInReloc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785dd47a727f7ced9db97da95dc69690">setIsSignature</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada18a65001620ef826d10d729fd05df6">isSignature</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4904497c380093675bde4af54fb493ce">setMemtag</a> (bool Tagged)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d141d83c2f705e53214a5e6bb84e83">isMemtag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b0b4bbaeddd13707c9d4b6456495d3">setIsBindingSet</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe7517b525d1cabefe112902c868c81">SymbolSize</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An expression describing how to calculate the size of a symbol. <a href="#a2fe7517b525d1cabefe112902c868c81">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50f62817c413083ae49d53c57d56484">classof</a> (const MCSymbol *S)</td>
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


<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCSymbolELF() {#ab5409f62668af4a8e307fe9149e1ff92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbolELF::MCSymbolELF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool isTemporary)</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab8dab642726ffad2a75d9fb7e4ec4291ae346ce5c2a999355f4e55692f502d583">llvm::MCSymbol::SymbolKindELF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBinding() {#ae357568bfa7baaa244f16208924f4637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbolELF::getBinding ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a654fdc7113f88027cc2016453184e880">llvm::MCSymbol::Flags</a>, <a href="#a666e25e11bd035c93786545bec5ce44e">isBindingSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>, <a href="#ada18a65001620ef826d10d729fd05df6">isSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#af6973fed52c67fe96c0493207984376b">llvm::MCSymbol::isUsedInReloc</a>, <a href="#a3e683b1f93c043f9fb48cdc47e736fb2">isWeakrefUsedInReloc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77af266d61f5074811ef82444eeeff11c89">llvm::ELF::STB_GNU_UNIQUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a> and <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a>.</p>

</div>
</div>

### getOther() {#a2badd3f8011db90045f7be286331125f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbolELF::getOther ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a654fdc7113f88027cc2016453184e880">llvm::MCSymbol::Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetelfstreamer/#ad95e201b1bc95e8227cbea05d1a7f856">anonymous{PPCMCTargetDesc.cpp}::PPCTargetELFStreamer::emitLocalEntry</a>.</p>

</div>
</div>

### getSize() {#a83461ac06968f969da6b77b0e3e90527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MCSymbolELF::getSize ()</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4003ba7a2726fde2214660963213cc31">llvm::MCSymbol::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a9090caa8ccfc6c4298f8d31ffbc73ca4">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSymbol</a>.</p>

</div>
</div>

### getType() {#a2c716684711cb83467c2138bc4e84454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbolELF::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a654fdc7113f88027cc2016453184e880">llvm::MCSymbol::Flags</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a6fb5d8136ffc8cfccf0425682fae235f">llvm::ELF::STT_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179ab453d9dfef54b0c7fd0cbaf82b4ba9d6">llvm::ELF::STT_TLS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a> and <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a>.</p>

</div>
</div>

### getVisibility() {#add2f34e14532817ad86d5c8f3b179c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbolELF::getVisibility ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a654fdc7113f88027cc2016453184e880">llvm::MCSymbol::Flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>.</p>

</div>
</div>

### isBindingSet() {#a666e25e11bd035c93786545bec5ce44e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolELF::isBindingSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a> and <a href="#ae357568bfa7baaa244f16208924f4637">getBinding</a>.</p>

</div>
</div>

### isMemtag() {#a27d141d83c2f705e53214a5e6bb84e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolELF::isMemtag ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a>.</p>

</div>
</div>

### isSignature() {#ada18a65001620ef826d10d729fd05df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolELF::isSignature ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>


<p>Referenced by <a href="#ae357568bfa7baaa244f16208924f4637">getBinding</a>.</p>

</div>
</div>

### isWeakrefUsedInReloc() {#a3e683b1f93c043f9fb48cdc47e736fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolELF::isWeakrefUsedInReloc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>.</p>


<p>Referenced by <a href="#ae357568bfa7baaa244f16208924f4637">getBinding</a>.</p>

</div>
</div>

### setBinding() {#ac1edee41b5f81ab31451e8bf98a3a3e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setBinding (unsigned Binding)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77af266d61f5074811ef82444eeeff11c89">llvm::ELF::STB_GNU_UNIQUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>.</p>

</div>
</div>

### setIsSignature() {#a785dd47a727f7ced9db97da95dc69690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setIsSignature ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a>.</p>

</div>
</div>

### setIsWeakrefUsedInReloc() {#a9bbad98aac843f2c52cd716efdde45e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setIsWeakrefUsedInReloc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a73aed7794053594cfb9536d55eac30fd">llvm::ELFObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### setMemtag() {#a4904497c380093675bde4af54fb493ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setMemtag (bool Tagged)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a>.</p>

</div>
</div>

### setOther() {#aed9abfbf50800b7378713d657bf0cf5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setOther (unsigned Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetelfstreamer/#ad95e201b1bc95e8227cbea05d1a7f856">anonymous{PPCMCTargetDesc.cpp}::PPCTargetELFStreamer::emitLocalEntry</a>.</p>

</div>
</div>

### setSize() {#a63edf630bae30668b44c9be9a85cb9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * SS)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4003ba7a2726fde2214660963213cc31">llvm::MCSymbol::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>.</p>

</div>
</div>

### setType() {#aed759e9547e045f0bd987987de0f76bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setType (unsigned Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a6fb5d8136ffc8cfccf0425682fae235f">llvm::ELF::STT_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179ab453d9dfef54b0c7fd0cbaf82b4ba9d6">llvm::ELF::STT_TLS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>.</p>

</div>
</div>

### setVisibility() {#a42d355b38e3f57001fdbce9f13846a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setVisibility (unsigned Visibility)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a6e3e2ebdfaad92643de69faf7f28967e">llvm::MCSymbol::setFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5af3e7284f94dabe52ad31412ab70c15f4">llvm::ELF::STV_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5ab38517de2fd6c124c49e40bc25c25c0c">llvm::ELF::STV_HIDDEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5a443262fcc164a05e17cef6868ab529d3">llvm::ELF::STV_INTERNAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5aec3ecfdbfbbe90889a70c56df29b263a">llvm::ELF::STV_PROTECTED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setIsBindingSet() {#ac3b0b4bbaeddd13707c9d4b6456495d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolELF::setIsBindingSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SymbolSize {#a2fe7517b525d1cabefe112902c868c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::MCSymbolELF::SymbolSize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An expression describing how to calculate the size of a symbol.</p>


<p>If a symbol has no size this field will be NULL.</p>


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aa50f62817c413083ae49d53c57d56484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolELF::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a32d2549f322ec04f233dc4304b4bbd16">llvm::MCSymbol::isELF</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">MCSymbolELF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcsymbolelf-cpp">MCSymbolELF.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
