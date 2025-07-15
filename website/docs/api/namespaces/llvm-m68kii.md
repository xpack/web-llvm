---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/m68kii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `M68kII` Namespace Reference

<p>This namespace holds all of the target specific flags that instruction info tracks. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::M68kII { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TOF { <a href="#adb1ef011f9833415094dce191a23ad88">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum. <a href="#adb1ef011f9833415094dce191a23ad88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796b2bb3ebbfdac8fa3eab2211052ac0">isGlobalStubReference</a> (unsigned char TargetFlag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified TargetFlag operand is a reference to a stub for a global, not the global itself. <a href="#a796b2bb3ebbfdac8fa3eab2211052ac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebce1e4db21e2bb2dd9afbd715e46cf8">isDirectGlobalReference</a> (unsigned char Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return True if the specified <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is a direct reference for a symbol. <a href="#aebce1e4db21e2bb2dd9afbd715e46cf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b5687ac518a430130855b87a819778">isGlobalRelativeToPICBase</a> (unsigned char TargetFlag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified global value reference is relative to a 32-bit PIC base (<a href="/web-llvm/docs/api/namespaces/llvm/m68kisd/#a5d785b7c28047e4e75d1fed254de7a5eaf4ce8c5d66fc94f7573b82c3ace0491b">M68kISD::GLOBAL_BASE_REG</a>). <a href="#a58b5687ac518a430130855b87a819778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9165d78c666e8da012ab8fb8be991f42">isPCRelGlobalReference</a> (unsigned char Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return True if the specified <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> requires PC addressing mode. <a href="#a9165d78c666e8da012ab8fb8be991f42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fad40e51755ae37012b3ae037fbc114">isPCRelBlockReference</a> (unsigned char Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return True if the Block is referenced using PC. <a href="#a2fad40e51755ae37012b3ae037fbc114">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100a61532e5a2d0e5a9c5c32b9f26894">isAddressRegister</a> (unsigned RegNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea6d67356077bc6a037e43b03bbfe05">hasMultiMIOperands</a> (unsigned Op, unsigned LogicalOpIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3fb2bc1b1ca197366995e7f5a4f6fd8">getMaskedSpillRegister</a> (unsigned order)</td>
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

<p>This namespace holds all of the target specific flags that instruction info tracks.</p>

<div class="doxySectionDef">

## Enumerations

### TOF {#adb1ef011f9833415094dce191a23ad88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::M68kII::TOF </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NO_FLAG<a id="adb1ef011f9833415094dce191a23ad88ae40504bd63df1c211500fcd35a29a601"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ABSOLUTE_ADDRESS<a id="adb1ef011f9833415094dce191a23ad88a79ada893fa3a7cbe1b2d180bedcf2ba9"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand this indicates that the immediate is the absolute address of the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PC_RELATIVE_ADDRESS<a id="adb1ef011f9833415094dce191a23ad88a9b5b1d8ef02f8f95a63b78aa46bc9f15"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand this indicates that the immediate is the pc-relative address of the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT<a id="adb1ef011f9833415094dce191a23ad88a6da451e267e7fa37d09e4f116d7a0f56"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand this indicates that the immediate is the offset to the GOT entry for the symbol name from the base of the GOT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTOFF<a id="adb1ef011f9833415094dce191a23ad88a14de646b08b938d4b58469a685923fd7"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand this indicates that the immediate is the offset to the location of the symbol name from the base of the GOT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTPCREL<a id="adb1ef011f9833415094dce191a23ad88a7c9861e5ad1a38ababe5a78c1c0c95f6"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand this indicates that the immediate is offset to the GOT entry for the symbol name from the current code location</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PLT<a id="adb1ef011f9833415094dce191a23ad88a57e0e9fc5c5f19541861ef8dd3161679"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand this indicates that the immediate is offset to the PLT entry of symbol name from the current code location</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSGD<a id="adb1ef011f9833415094dce191a23ad88a7420be6c99ca50b5c9681bd7c751cbac"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand, this indicates that the immediate is the offset to the slot in GOT which stores the information for accessing the TLS variable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLD<a id="adb1ef011f9833415094dce191a23ad88ac50fc42c1821b21c2a8330bc683ea2b7"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand, this indicates that the immediate is the offset to variable within the thread local storage when operating in Local Dynamic mode</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLDM<a id="adb1ef011f9833415094dce191a23ad88a403784327265ec4dd7136f05d6a3c79a"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand, this indicates that the immediate is the offset to the slot in GOT which stores the information for accessing the TLS variable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSIE<a id="adb1ef011f9833415094dce191a23ad88ac20c347227f3c3c16af195d97d1c399b"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand, this indicates that the immediate is the offset to the variable within the thread local storage when operating in Initial Exec mode</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLE<a id="adb1ef011f9833415094dce191a23ad88a5f23a5d94574e27c889a585834ba0864"></a></td>
<td class="doxyEnumItemDescription">On a symbol operand, this indicates that the immediate is the offset to the variable within in the thread local storage when operating in Local Exec mode</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getMaskedSpillRegister() {#ad3fb2bc1b1ca197366995e7f5a4f6fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kII::getMaskedSpillRegister (unsigned order)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>

</div>
</div>

### hasMultiMIOperands() {#a9ea6d67356077bc6a037e43b03bbfe05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kII::hasMultiMIOperands (unsigned Op, unsigned LogicalOpIdx)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>

</div>
</div>

### isAddressRegister() {#a100a61532e5a2d0e5a9c5c32b9f26894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kII::isAddressRegister (unsigned RegNo)</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kasmprinter/#a5474d7cf1a213163c8929c3189e2c166">llvm::M68kAsmPrinter::PrintAsmMemoryOperand</a>.</p>

</div>
</div>

### isDirectGlobalReference() {#aebce1e4db21e2bb2dd9afbd715e46cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kII::isDirectGlobalReference (unsigned char Flag)</td>
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

<p>Return True if the specified <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is a direct reference for a symbol.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>


<p>References <a href="#adb1ef011f9833415094dce191a23ad88a79ada893fa3a7cbe1b2d180bedcf2ba9">MO_ABSOLUTE_ADDRESS</a>, <a href="#adb1ef011f9833415094dce191a23ad88ae40504bd63df1c211500fcd35a29a601">MO_NO_FLAG</a> and <a href="#adb1ef011f9833415094dce191a23ad88a9b5b1d8ef02f8f95a63b78aa46bc9f15">MO_PC_RELATIVE_ADDRESS</a>.</p>

</div>
</div>

### isGlobalRelativeToPICBase() {#a58b5687ac518a430130855b87a819778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kII::isGlobalRelativeToPICBase (unsigned char TargetFlag)</td>
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

<p>Return true if the specified global value reference is relative to a 32-bit PIC base (<a href="/web-llvm/docs/api/namespaces/llvm/m68kisd/#a5d785b7c28047e4e75d1fed254de7a5eaf4ce8c5d66fc94f7573b82c3ace0491b">M68kISD::GLOBAL_BASE_REG</a>).</p>


<p>If this is true, the addressing mode has the PIC base register added in.</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>


<p>References <a href="#adb1ef011f9833415094dce191a23ad88a6da451e267e7fa37d09e4f116d7a0f56">MO_GOT</a> and <a href="#adb1ef011f9833415094dce191a23ad88a14de646b08b938d4b58469a685923fd7">MO_GOTOFF</a>.</p>

</div>
</div>

### isGlobalStubReference() {#a796b2bb3ebbfdac8fa3eab2211052ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kII::isGlobalStubReference (unsigned char TargetFlag)</td>
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

<p>Return true if the specified TargetFlag operand is a reference to a stub for a global, not the global itself.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>


<p>References <a href="#adb1ef011f9833415094dce191a23ad88a6da451e267e7fa37d09e4f116d7a0f56">MO_GOT</a> and <a href="#adb1ef011f9833415094dce191a23ad88a7c9861e5ad1a38ababe5a78c1c0c95f6">MO_GOTPCREL</a>.</p>

</div>
</div>

### isPCRelBlockReference() {#a2fad40e51755ae37012b3ae037fbc114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kII::isPCRelBlockReference (unsigned char Flag)</td>
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

<p>Return True if the Block is referenced using PC.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>


<p>Reference <a href="#adb1ef011f9833415094dce191a23ad88a9b5b1d8ef02f8f95a63b78aa46bc9f15">MO_PC_RELATIVE_ADDRESS</a>.</p>

</div>
</div>

### isPCRelGlobalReference() {#a9165d78c666e8da012ab8fb8be991f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kII::isPCRelGlobalReference (unsigned char Flag)</td>
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

<p>Return True if the specified <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> requires PC addressing mode.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>


<p>References <a href="#adb1ef011f9833415094dce191a23ad88a7c9861e5ad1a38ababe5a78c1c0c95f6">MO_GOTPCREL</a> and <a href="#adb1ef011f9833415094dce191a23ad88a9b5b1d8ef02f8f95a63b78aa46bc9f15">MO_PC_RELATIVE_ADDRESS</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
