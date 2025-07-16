---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsectionmacho
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSectionMachO` Class Reference

<p>This represents a section on a Mach-O system (used by Mac OS X). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCSectionMachO { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">llvm/MC/MCSectionMachO.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instances of this class represent a uniqued identifier for a section in the current translation unit. <a href="/web-llvm/docs/api/classes/llvm/mcsection/#details">More...</a></p>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a805301448dc24a07811a2913b9da0f00">MCSectionMachO</a> (StringRef Segment, StringRef Section, unsigned TAA, unsigned reserved2, SectionKind K, MCSymbol *Begin)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3daa3b8dd38ee3a426a6f83bb3cac0d2">getSegmentName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0040086fb7002dc0a8a8fca7c388f02">getTypeAndAttributes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea94e3423a1333226055af9dbc650050">getStubSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409">MachO::SectionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f530d6116df447fdadb8ef67239cd4e">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac857b3db4ba0094058d536d4938d6fda">hasAttribute</a> (unsigned Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaebfb20a6b5145fda04f26aa65a47ae">printSwitchToSection</a> (const MCAsmInfo &amp;MAI, const Triple &amp;T, raw_ostream &amp;OS, uint32_t Subsection) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b926924b0e9206ee54c25ceab6bdadd">useCodeAlign</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a .align directive should use "optimized nops" to fill instead of 0s. <a href="#a9b926924b0e9206ee54c25ceab6bdadd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afbb5dfa522ea740721a0b001ba51cb">allocAtoms</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a675536cb781344d9c70b6e7e4f8d411a">getAtom</a> (size_t I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3193be17f8e456167a77a550b7af9a48">setAtom</a> (size_t I, const MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9924b82c9e99eadd5770f45cf56ad36">getLayoutOrder</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7a8a680b0f6e156da6b35fca896cb3">setLayoutOrder</a> (unsigned Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8114be804d9b4e07a2e499b9830aba9f">SegmentName</a>[16]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6efce195c6d858e821890eefa45a0d">TypeAndAttributes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the SECTION_TYPE and SECTION_ATTRIBUTES field of a section, drawn from the enums below. <a href="#a0c6efce195c6d858e821890eefa45a0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765f0cab67da4b0a51f8c16e3e26dda8">Reserved2</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The 'reserved2' field of a section, used to represent the size of stubs, for example. <a href="#a765f0cab67da4b0a51f8c16e3e26dda8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f03db5fffd0583271b96204ba4072d9">LayoutOrder</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a8213141eebaa75ba0143ab138730b">Atoms</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea0b527a25e96bb74c8217704b22a07">ParseSectionSpecifier</a> (StringRef Spec, StringRef &amp;Segment, StringRef &amp;Section, unsigned &amp;TAA, bool &amp;TAAParsed, unsigned &amp;StubSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the section specifier indicated by "Spec". <a href="#a1ea0b527a25e96bb74c8217704b22a07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10116482e7a563e3eed9f06cdafa098">classof</a> (const MCSection *S)</td>
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

<p>This represents a section on a Mach-O system (used by Mac OS X).</p>


<p>On a Mac system, these are also described in /usr/include/mach-o/loader.h.</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


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
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


<p>Reference <a href="#a7862d2f746209c16291d7139dab55e00">MCContext</a>.</p>


<p>Referenced by <a href="#a7862d2f746209c16291d7139dab55e00">MCContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MCSectionMachO() {#a805301448dc24a07811a2913b9da0f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionMachO::MCSectionMachO (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Segment, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned TAA, unsigned reserved2, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Begin)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocAtoms() {#a8afbb5dfa522ea740721a0b001ba51cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSectionMachO::allocAtoms ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac28ea8ba1e28d8b3a3ca7234e1bc1083">llvm::MCSection::curFragList</a>.</p>

</div>
</div>

### getAtom() {#a675536cb781344d9c70b6e7e4f8d411a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * MCSectionMachO::getAtom (size_t I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getLayoutOrder() {#aa9924b82c9e99eadd5770f45cf56ad36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSectionMachO::getLayoutOrder ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>

</div>
</div>

### getSegmentName() {#a3daa3b8dd38ee3a426a6f83bb3cac0d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSectionMachO::getSegmentName ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp/#a4bdfc7678b89f0959870e072aaf0d036">canUseLocalRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a3ce73ec5824c032df5044c83409259be">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitZerofill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfodarwin/#ab4ef3ac1427687f11d30de588a790122">llvm::MCAsmInfoDarwin::isSectionAtomizableBySymbols</a> and <a href="#adaebfb20a6b5145fda04f26aa65a47ae">printSwitchToSection</a>.</p>

</div>
</div>

### getStubSize() {#aea94e3423a1333226055af9dbc650050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSectionMachO::getStubSize ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a>.</p>

</div>
</div>

### getType() {#a2f530d6116df447fdadb8ef67239cd4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::SectionType llvm::MCSectionMachO::getType ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198afcc0f8ee030bc9729199d678956638b3">llvm::MachO::SECTION_TYPE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp/#a4bdfc7678b89f0959870e072aaf0d036">canUseLocalRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfodarwin/#ab4ef3ac1427687f11d30de588a790122">llvm::MCAsmInfoDarwin::isSectionAtomizableBySymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#adb14af816964063e2e902f6d9586abcd">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveIndirectSymbol</a> and <a href="#adaebfb20a6b5145fda04f26aa65a47ae">printSwitchToSection</a>.</p>

</div>
</div>

### getTypeAndAttributes() {#ac0040086fb7002dc0a8a8fca7c388f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSectionMachO::getTypeAndAttributes ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a> and <a href="#adaebfb20a6b5145fda04f26aa65a47ae">printSwitchToSection</a>.</p>

</div>
</div>

### hasAttribute() {#ac857b3db4ba0094058d536d4938d6fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSectionMachO::hasAttribute (unsigned Value)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


<p>Referenced by <a href="#a9b926924b0e9206ee54c25ceab6bdadd">useCodeAlign</a>.</p>

</div>
</div>

### printSwitchToSection() {#adaebfb20a6b5145fda04f26aa65a47ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSectionMachO::printSwitchToSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint32_t Subsection)</td>
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



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ad2fc2a7c27ca977660fbf4c84aee3da7">AssemblerName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#a1ff3c3a24eb70dad710bab309549b283">AttrFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#aac4366cca0c8d3cd472a02a71f4aa34c">llvm::MCSection::getName</a>, <a href="#a3daa3b8dd38ee3a426a6f83bb3cac0d2">getSegmentName</a>, <a href="#a2f530d6116df447fdadb8ef67239cd4e">getType</a>, <a href="#ac0040086fb7002dc0a8a8fca7c388f02">getTypeAndAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409aa07c96f79ac85c1447d24b167f6ad634">llvm::MachO::LAST_KNOWN_SECTION_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198a9e5f751177cc42392885008fcce9e61a">llvm::MachO::SECTION_ATTRIBUTES</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#a8040205b8d0f2b27405bdd5606f7f3c0">SectionAttrDescriptors</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#a5b6520d99fc98f9e19785696dc7ae4f1">SectionTypeDescriptors</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### setAtom() {#a3193be17f8e456167a77a550b7af9a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSectionMachO::setAtom (size_t I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### setLayoutOrder() {#abd7a8a680b0f6e156da6b35fca896cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSectionMachO::setLayoutOrder (unsigned Value)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>

</div>
</div>

### useCodeAlign() {#a9b926924b0e9206ee54c25ceab6bdadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCSectionMachO::useCodeAlign ()</td>
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

<p>Return true if a .align directive should use "optimized nops" to fill instead of 0s.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>References <a href="#ac857b3db4ba0094058d536d4938d6fda">hasAttribute</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a96ef438f63eb95474a1bb24b8ef24e5b">llvm::MachO::S_ATTR_PURE_INSTRUCTIONS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Atoms {#ae3a8213141eebaa75ba0143ab138730b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const MCSymbol *, 0&gt; llvm::MCSectionMachO::Atoms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>

</div>
</div>

### LayoutOrder {#a6f03db5fffd0583271b96204ba4072d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSectionMachO::LayoutOrder = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>

</div>
</div>

### Reserved2 {#a765f0cab67da4b0a51f8c16e3e26dda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSectionMachO::Reserved2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The 'reserved2' field of a section, used to represent the size of stubs, for example.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>

</div>
</div>

### SegmentName {#a8114be804d9b4e07a2e499b9830aba9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::MCSectionMachO::SegmentName[16]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>

</div>
</div>

### TypeAndAttributes {#a0c6efce195c6d858e821890eefa45a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSectionMachO::TypeAndAttributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the SECTION_TYPE and SECTION_ATTRIBUTES field of a section, drawn from the enums below.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad10116482e7a563e3eed9f06cdafa098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSectionMachO::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * S)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a2337a53a051cfed7b9fc29a4eb1e5f1c">llvm::MCSection::getVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ad2c130ecb0e15e740bfad7eb61eb061e">llvm::MCSection::MCSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#afecf7c84b079ea5c169f71b6c06ece98a55ed9b1dac938f496436528db3576783">llvm::MCSection::SV_MachO</a>.</p>

</div>
</div>

### ParseSectionSpecifier() {#a1ea0b527a25e96bb74c8217704b22a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MCSectionMachO::ParseSectionSpecifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spec, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Segment, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Section, unsigned &amp; TAA, bool &amp; TAAParsed, unsigned &amp; StubSize)</td>
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

<p>Parse the section specifier indicated by "Spec".</p>


<p>ParseSectionSpecifier - Parse the section specifier indicated by "Spec".</p>


<p>This is a string that can appear after a .section directive in a mach-o flavored .s file. If successful, this fills in the specified Out parameters and returns an empty string. When an invalid section specifier is present, this returns an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> indicating the problem. If no TAA was parsed, TAA is not altered, and TAAWasSet becomes false.</p>


<p>This is a string that can appear after a .section directive in a mach-o flavored .s file. If successful, this fills in the specified Out parameters and returns an empty string. When an invalid section specifier is present, this returns a string indicating the problem.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409ae03f48f1f4c31faadeac53f15460c2d6">llvm::MachO::S_SYMBOL_STUBS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198afcc0f8ee030bc9729199d678956638b3">llvm::MachO::SECTION_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#a8040205b8d0f2b27405bdd5606f7f3c0">SectionAttrDescriptors</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#a5b6520d99fc98f9e19785696dc7ae4f1">SectionTypeDescriptors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">MCSectionMachO.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
