---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcmachobjecttargetwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCMachObjectTargetWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCMachObjectTargetWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">llvm/MC/MCMachObjectWriter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for classes that define behaviour that is specific to both the target and the object format. <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter">AArch64MachObjectWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter">ARMMachObjectWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86machobjectwriter-cpp-/x86machobjectwriter">X86MachObjectWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5600ec5363bb5d1b3c62b55f8363a99">MCMachObjectTargetWriter</a> (bool Is64Bit_, uint32_t CPUType_, uint32_t CPUSubtype_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72c4322605792f6909c4a090eb1b977">~MCMachObjectTargetWriter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201">Triple::ObjectFormatType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa965ff21f0e8eef08edfa1bfea7fec5e">getFormat</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de2f6e5a540523361079449187624ea">setLocalDifferenceRelocationType</a> (unsigned Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29646065109fbfb6d612d736b4e4e42c">LocalDifference_RIT</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585fed60885001bfbcb03bdb998bc6e0">CPUSubtype</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eaaac98d322fad9a60d222f3372698a">Is64Bit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f6a1a5853ffb0e6b9d5370b36d5d4a">CPUType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b7278eca425360cb3c5b5cbce53ccb">classof</a> (const MCObjectTargetWriter *W)</td>
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

## Lifetime Management Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad861a6511c414b6b2abafc5ea8393092">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889ee913a5a35d194d61c83d4dca50bc">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268d350fcaf24a92775d17bcf37486ea">getCPUType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c2391f6b6f8c898c8a4cf1e60dc4afc">getCPUSubtype</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7fb81744b8c0e6db3802dbeda10e2a1">getLocalDifferenceRelocationType</a> () const</td>
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

## API Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d8b06533488625f599a722d3442b35">recordRelocation</a> (MachObjectWriter *Writer, MCAssembler &amp;Asm, const MCFragment *Fragment, const MCFixup &amp;Fixup, MCValue Target, uint64_t &amp;FixedValue)=0</td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### MCMachObjectTargetWriter() {#ab5600ec5363bb5d1b3c62b55f8363a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCMachObjectTargetWriter::MCMachObjectTargetWriter (bool Is64Bit_, uint32_t CPUType_, uint32_t CPUSubtype_)</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 13 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachobjecttargetwriter-cpp">MCMachObjectTargetWriter.cpp</a>.</p>


<p>Reference <a href="#a585fed60885001bfbcb03bdb998bc6e0">CPUSubtype</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#a2ed961a70254a62667fa5944977cd375">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::AArch64MachObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#af0dc371c1b92b24792e9c2f67dfea907">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::ARMMachObjectWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86machobjectwriter-cpp-/x86machobjectwriter/#aa5f05639e1509cf433f523d5e5499c01">anonymous{X86MachObjectWriter.cpp}::X86MachObjectWriter::X86MachObjectWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCMachObjectTargetWriter() {#af72c4322605792f6909c4a090eb1b977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCMachObjectTargetWriter::~MCMachObjectTargetWriter ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFormat() {#aa965ff21f0e8eef08edfa1bfea7fec5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ObjectFormatType llvm::MCMachObjectTargetWriter::getFormat ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### setLocalDifferenceRelocationType() {#a5de2f6e5a540523361079449187624ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCMachObjectTargetWriter::setLocalDifferenceRelocationType (unsigned Type)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="#a29646065109fbfb6d612d736b4e4e42c">LocalDifference_RIT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LocalDifference\_RIT {#a29646065109fbfb6d612d736b4e4e42c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCMachObjectTargetWriter::LocalDifference_RIT = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="#af7fb81744b8c0e6db3802dbeda10e2a1">getLocalDifferenceRelocationType</a> and <a href="#a5de2f6e5a540523361079449187624ea">setLocalDifferenceRelocationType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CPUSubtype {#a585fed60885001bfbcb03bdb998bc6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCMachObjectTargetWriter::CPUSubtype</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#a2ed961a70254a62667fa5944977cd375">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::AArch64MachObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#af0dc371c1b92b24792e9c2f67dfea907">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::ARMMachObjectWriter</a>, <a href="#a6c2391f6b6f8c898c8a4cf1e60dc4afc">getCPUSubtype</a>, <a href="#ab5600ec5363bb5d1b3c62b55f8363a99">MCMachObjectTargetWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86machobjectwriter-cpp-/x86machobjectwriter/#aa5f05639e1509cf433f523d5e5499c01">anonymous{X86MachObjectWriter.cpp}::X86MachObjectWriter::X86MachObjectWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CPUType {#ae4f6a1a5853ffb0e6b9d5370b36d5d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::MCMachObjectTargetWriter::CPUType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### Is64Bit {#a1eaaac98d322fad9a60d222f3372698a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCMachObjectTargetWriter::Is64Bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a93b7278eca425360cb3c5b5cbce53ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCMachObjectTargetWriter::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> * W)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Lifetime Management

### reset {#ad861a6511c414b6b2abafc5ea8393092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCMachObjectTargetWriter::reset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getCPUSubtype {#a6c2391f6b6f8c898c8a4cf1e60dc4afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCMachObjectTargetWriter::getCPUSubtype ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="#a585fed60885001bfbcb03bdb998bc6e0">CPUSubtype</a>.</p>

</div>
</div>

### getCPUType {#a268d350fcaf24a92775d17bcf37486ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCMachObjectTargetWriter::getCPUType ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### getLocalDifferenceRelocationType {#af7fb81744b8c0e6db3802dbeda10e2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCMachObjectTargetWriter::getLocalDifferenceRelocationType ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="#a29646065109fbfb6d612d736b4e4e42c">LocalDifference_RIT</a>.</p>

</div>
</div>

### is64Bit {#a889ee913a5a35d194d61c83d4dca50bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCMachObjectTargetWriter::is64Bit ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## API

### recordRelocation {#a43d8b06533488625f599a722d3442b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCMachObjectTargetWriter::recordRelocation (<a href="/web-llvm/docs/api/classes/llvm/machobjectwriter">MachObjectWriter</a> * Writer, <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Target, uint64_t &amp; FixedValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachobjecttargetwriter-cpp">MCMachObjectTargetWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
