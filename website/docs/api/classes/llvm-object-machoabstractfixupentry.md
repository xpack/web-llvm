---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/machoabstractfixupentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachOAbstractFixupEntry` Class

<p><a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry">MachOAbstractFixupEntry</a> is an abstract class representing a fixup in a MH_DYLDLINK file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::MachOAbstractFixupEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry">MachOChainedFixupEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5c724a4788135ad66edb2be0a81927">MachOAbstractFixupEntry</a> (Error *Err, const MachOObjectFile *O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b451776650c336a61dce2ded1567b42">segmentIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4cfcbe2edfc0f5f854011a80d484453">segmentOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1e98553d4f43a04d568177889bbbe8">segmentAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1876c1aeacf40c58006ad015843c11">segmentName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0533b81cf611c9ca97f96f49e822eec4">sectionName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741a9a132a478da57292d0b8db6da296">typeName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6f1d5a48cda5c3f01fddcc8a9f835ec">symbolName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94dc6ccfce6db0ec588c5b7a9a214cba">flags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753fae8a56a88447dc63b8ef8d588249">addend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85de8e4cf77922279c11f9fbc006761">ordinal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3405a21cc5f1439f90e739194a72fa6d">address</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99df095b437947e14e1b354baf97d723">pointerValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbf2356e27b7fdb7a118a5e64f1ef21">rawValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552450cc93580b8f60a2d4a0356ff850">moveNext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb42d8a720b462a7bbd69c29c46deba3">moveToFirst</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae155e3bbdfe979091b05ce2ab8c6c98c">moveToEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a82529e6317d5daafd32d4a0416818">textAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad960b227c861de4dec3ae4e952502359">E</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee04f68132b24f954142920e9907d47f">O</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd8b7d16088e28f13ffaadd0a3d92b2">SegmentOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd024ce2eebd7b07cc4c659c8112be13">SegmentIndex</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b46c8e7ab964fb57866644a2c46a56">SymbolName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf255fb43542c54c0615e0c3374de6e">Ordinal</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c19099c69732495167457fd55a00d7b">Flags</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b832cfb5038b187d63082022ccefa8">Addend</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8f4c6150a51ad161e5888bc62029aa">PointerValue</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1004e8fd48db72eb421cbdbbb12d6b6a">RawValue</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab10af10cfaadf6fa5d5e85b0d2047cae">Done</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1898552c98b496d8bebe7da48d8e3668">TextAddress</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry">MachOAbstractFixupEntry</a> is an abstract class representing a fixup in a MH_DYLDLINK file.</p>


<p>Fixups generally represent rebases and binds. Binds also subdivide into additional subtypes (weak, lazy, reexport).</p>


<p>The two concrete subclasses of <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry">MachOAbstractFixupEntry</a> are:</p>


<p>MachORebaseBindEntry - for dyld opcode-based tables, including threaded- rebase, where rebases are mixed in with other bind opcodes. <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry">MachOChainedFixupEntry</a> - for pointer chains embedded in data pages.</p>


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachOAbstractFixupEntry() {#a7a5c724a4788135ad66edb2be0a81927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOAbstractFixupEntry::MachOAbstractFixupEntry (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3251 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad960b227c861de4dec3ae4e952502359">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="#aee04f68132b24f954142920e9907d47f">O</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a5f2f9b655a6e370dd8792b2eeede2ea1">llvm::object::MachOChainedFixupEntry::MachOChainedFixupEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addend() {#a753fae8a56a88447dc63b8ef8d588249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t MachOAbstractFixupEntry::addend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3296 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#ae1b832cfb5038b187d63082022ccefa8">Addend</a>.</p>

</div>
</div>

### address() {#a3405a21cc5f1439f90e739194a72fa6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOAbstractFixupEntry::address ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the location of this fixup as a VM Address. For the VM Address this fixup is pointing to, use <a href="#a99df095b437947e14e1b354baf97d723">pointerValue()</a>.</p></dd>
</dl>


<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3290 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#aee04f68132b24f954142920e9907d47f">O</a>, <a href="#abd024ce2eebd7b07cc4c659c8112be13">SegmentIndex</a> and <a href="#a4bd8b7d16088e28f13ffaadd0a3d92b2">SegmentOffset</a>.</p>

</div>
</div>

### flags() {#a94dc6ccfce6db0ec588c5b7a9a214cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOAbstractFixupEntry::flags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3298 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#a0c19099c69732495167457fd55a00d7b">Flags</a>.</p>

</div>
</div>

### moveNext() {#a552450cc93580b8f60a2d4a0356ff850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOAbstractFixupEntry::moveNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3315 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### ordinal() {#ac85de8e4cf77922279c11f9fbc006761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachOAbstractFixupEntry::ordinal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3300 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#aecf255fb43542c54c0615e0c3374de6e">Ordinal</a>.</p>

</div>
</div>

### pointerValue() {#a99df095b437947e14e1b354baf97d723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOAbstractFixupEntry::pointerValue ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the VM Address pointed to by this fixup. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="#a99df095b437947e14e1b354baf97d723">pointerValue()</a> to compare against other VM Addresses, such as section addresses or segment vmaddrs.</p></dd>
</dl>


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="#abc8f4c6150a51ad161e5888bc62029aa">PointerValue</a>.</p>

</div>
</div>

### rawValue() {#a9fbf2356e27b7fdb7a118a5e64f1ef21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOAbstractFixupEntry::rawValue ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the raw "on-disk" representation of the fixup. For Threaded rebases and Chained pointers these values are generally encoded into various different pointer formats. This value is exposed in API for tools that want to display and annotate the raw bits.</p></dd>
</dl>


<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="#a1004e8fd48db72eb421cbdbbb12d6b6a">RawValue</a>.</p>

</div>
</div>

### sectionName() {#a0533b81cf611c9ca97f96f49e822eec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOAbstractFixupEntry::sectionName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3286 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#aee04f68132b24f954142920e9907d47f">O</a>, <a href="#abd024ce2eebd7b07cc4c659c8112be13">SegmentIndex</a> and <a href="#a4bd8b7d16088e28f13ffaadd0a3d92b2">SegmentOffset</a>.</p>

</div>
</div>

### segmentAddress() {#a0f1e98553d4f43a04d568177889bbbe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOAbstractFixupEntry::segmentAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3278 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#aee04f68132b24f954142920e9907d47f">O</a> and <a href="#abd024ce2eebd7b07cc4c659c8112be13">SegmentIndex</a>.</p>

</div>
</div>

### segmentIndex() {#a1b451776650c336a61dce2ded1567b42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t MachOAbstractFixupEntry::segmentIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3272 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#abd024ce2eebd7b07cc4c659c8112be13">SegmentIndex</a>.</p>

</div>
</div>

### segmentName() {#aca1876c1aeacf40c58006ad015843c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOAbstractFixupEntry::segmentName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3282 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#aee04f68132b24f954142920e9907d47f">O</a> and <a href="#abd024ce2eebd7b07cc4c659c8112be13">SegmentIndex</a>.</p>

</div>
</div>

### segmentOffset() {#af4cfcbe2edfc0f5f854011a80d484453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOAbstractFixupEntry::segmentOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3274 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#a4bd8b7d16088e28f13ffaadd0a3d92b2">SegmentOffset</a>.</p>

</div>
</div>

### symbolName() {#aa6f1d5a48cda5c3f01fddcc8a9f835ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOAbstractFixupEntry::symbolName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3294 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#a65b46c8e7ab964fb57866644a2c46a56">SymbolName</a>.</p>

</div>
</div>

### typeName() {#a741a9a132a478da57292d0b8db6da296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOAbstractFixupEntry::typeName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3302 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### moveToEnd() {#ae155e3bbdfe979091b05ce2ab8c6c98c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOAbstractFixupEntry::moveToEnd ()</td>
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



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3313 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#ab10af10cfaadf6fa5d5e85b0d2047cae">Done</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a6babc84320fb3f2fa66c109c58c8b1f2">llvm::object::MachOChainedFixupEntry::moveToEnd</a>.</p>

</div>
</div>

### moveToFirst() {#abb42d8a720b462a7bbd69c29c46deba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOAbstractFixupEntry::moveToFirst ()</td>
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



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3304 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ae1b832cfb5038b187d63082022ccefa8">Addend</a>, <a href="#ab10af10cfaadf6fa5d5e85b0d2047cae">Done</a>, <a href="#a0c19099c69732495167457fd55a00d7b">Flags</a>, <a href="#aecf255fb43542c54c0615e0c3374de6e">Ordinal</a>, <a href="#abd024ce2eebd7b07cc4c659c8112be13">SegmentIndex</a> and <a href="#a4bd8b7d16088e28f13ffaadd0a3d92b2">SegmentOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a9238134129c8aed37a5a4274fdda8676">llvm::object::MachOChainedFixupEntry::moveToFirst</a>.</p>

</div>
</div>

### textAddress() {#a83a82529e6317d5daafd32d4a0416818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOAbstractFixupEntry::textAddress ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the vm address of the start of __TEXT segment.</p></dd>
</dl>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Addend {#ae1b832cfb5038b187d63082022ccefa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::object::MachOAbstractFixupEntry::Addend = 0</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a753fae8a56a88447dc63b8ef8d588249">addend</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a> and <a href="#abb42d8a720b462a7bbd69c29c46deba3">moveToFirst</a>.</p>

</div>
</div>

### Done {#ab10af10cfaadf6fa5d5e85b0d2047cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOAbstractFixupEntry::Done = false</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>, <a href="#ae155e3bbdfe979091b05ce2ab8c6c98c">moveToEnd</a>, <a href="#abb42d8a720b462a7bbd69c29c46deba3">moveToFirst</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a9238134129c8aed37a5a4274fdda8676">llvm::object::MachOChainedFixupEntry::moveToFirst</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a35b61c6d12c2d79861b7f5d83765072b">llvm::object::MachOChainedFixupEntry::operator==</a>.</p>

</div>
</div>

### E {#ad960b227c861de4dec3ae4e952502359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error* llvm::object::MachOAbstractFixupEntry::E</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a7a5c724a4788135ad66edb2be0a81927">MachOAbstractFixupEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a5f2f9b655a6e370dd8792b2eeede2ea1">llvm::object::MachOChainedFixupEntry::MachOChainedFixupEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>.</p>

</div>
</div>

### Flags {#a0c19099c69732495167457fd55a00d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOAbstractFixupEntry::Flags = 0</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a94dc6ccfce6db0ec588c5b7a9a214cba">flags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a> and <a href="#abb42d8a720b462a7bbd69c29c46deba3">moveToFirst</a>.</p>

</div>
</div>

### O {#aee04f68132b24f954142920e9907d47f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachOObjectFile* llvm::object::MachOAbstractFixupEntry::O</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a3405a21cc5f1439f90e739194a72fa6d">address</a>, <a href="#a7a5c724a4788135ad66edb2be0a81927">MachOAbstractFixupEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a5f2f9b655a6e370dd8792b2eeede2ea1">llvm::object::MachOChainedFixupEntry::MachOChainedFixupEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>, <a href="#a0533b81cf611c9ca97f96f49e822eec4">sectionName</a>, <a href="#a0f1e98553d4f43a04d568177889bbbe8">segmentAddress</a> and <a href="#aca1876c1aeacf40c58006ad015843c11">segmentName</a>.</p>

</div>
</div>

### Ordinal {#aecf255fb43542c54c0615e0c3374de6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::object::MachOAbstractFixupEntry::Ordinal = 0</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>, <a href="#abb42d8a720b462a7bbd69c29c46deba3">moveToFirst</a> and <a href="#ac85de8e4cf77922279c11f9fbc006761">ordinal</a>.</p>

</div>
</div>

### PointerValue {#abc8f4c6150a51ad161e5888bc62029aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOAbstractFixupEntry::PointerValue = 0</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a> and <a href="#a99df095b437947e14e1b354baf97d723">pointerValue</a>.</p>

</div>
</div>

### RawValue {#a1004e8fd48db72eb421cbdbbb12d6b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOAbstractFixupEntry::RawValue = 0</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a> and <a href="#a9fbf2356e27b7fdb7a118a5e64f1ef21">rawValue</a>.</p>

</div>
</div>

### SegmentIndex {#abd024ce2eebd7b07cc4c659c8112be13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::object::MachOAbstractFixupEntry::SegmentIndex = -1</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a3405a21cc5f1439f90e739194a72fa6d">address</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>, <a href="#abb42d8a720b462a7bbd69c29c46deba3">moveToFirst</a>, <a href="#a0533b81cf611c9ca97f96f49e822eec4">sectionName</a>, <a href="#a0f1e98553d4f43a04d568177889bbbe8">segmentAddress</a>, <a href="#a1b451776650c336a61dce2ded1567b42">segmentIndex</a> and <a href="#aca1876c1aeacf40c58006ad015843c11">segmentName</a>.</p>

</div>
</div>

### SegmentOffset {#a4bd8b7d16088e28f13ffaadd0a3d92b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOAbstractFixupEntry::SegmentOffset = 0</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a3405a21cc5f1439f90e739194a72fa6d">address</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>, <a href="#abb42d8a720b462a7bbd69c29c46deba3">moveToFirst</a>, <a href="#a0533b81cf611c9ca97f96f49e822eec4">sectionName</a> and <a href="#af4cfcbe2edfc0f5f854011a80d484453">segmentOffset</a>.</p>

</div>
</div>

### SymbolName {#a65b46c8e7ab964fb57866644a2c46a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::MachOAbstractFixupEntry::SymbolName</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a> and <a href="#aa6f1d5a48cda5c3f01fddcc8a9f835ec">symbolName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TextAddress {#a1898552c98b496d8bebe7da48d8e3668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOAbstractFixupEntry::TextAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
