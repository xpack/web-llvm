---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-goffobjectwriter-cpp-/goffobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GOFFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GOFFObjectWriter.cpp}::GOFFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines the object file and target independent interfaces used by the assembler backend to write native file format object files. <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726eec348c27b5336229e78fd0b5437d">GOFFObjectWriter</a> (std::unique_ptr&lt; MCGOFFObjectTargetWriter &gt; MOTW, raw_pwrite_stream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a604e3c49da079f5e1439198eb3a89ada">~GOFFObjectWriter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3992a2bfd4bb0b0696e40fd7f55a10c6">writeHeader</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5fcffab76e6fcefcbe4293fdc63b0d3">writeEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab804e28f2b38ee3b8ff61c1b03f83668">recordRelocation</a> (MCAssembler &amp;Asm, const MCFragment *Fragment, const MCFixup &amp;Fixup, MCValue Target, uint64_t &amp;FixedValue) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Record a relocation entry. <a href="#ab804e28f2b38ee3b8ff61c1b03f83668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a260c83ace2744d606c0ffa69ec9be9f2">writeObject</a> (MCAssembler &amp;Asm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the object file and returns the number of bytes written. <a href="#a260c83ace2744d606c0ffa69ec9be9f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcgoffobjecttargetwriter">MCGOFFObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808c056c37d809e1a2a6d0853278286b">TargetObjectWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-goffobjectwriter-cpp-/goffostream">GOFFOstream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeadcf74cee04fb938b960b3ac5a1bb72">OS</a></td>
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


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GOFFObjectWriter() {#a726eec348c27b5336229e78fd0b5437d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GOFFObjectWriter.cpp}::GOFFObjectWriter::GOFFObjectWriter (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcgoffobjecttargetwriter">MCGOFFObjectTargetWriter</a> &gt; MOTW, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GOFFObjectWriter() {#a604e3c49da079f5e1439198eb3a89ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GOFFObjectWriter.cpp}::GOFFObjectWriter::~GOFFObjectWriter ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### recordRelocation() {#ab804e28f2b38ee3b8ff61c1b03f83668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GOFFObjectWriter.cpp}::GOFFObjectWriter::recordRelocation (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Target, uint64_t &amp; FixedValue)</td>
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

<p>Record a relocation entry.</p>


<p>This routine is called by the assembler after layout and relaxation, and post layout binding. The implementation is responsible for storing information about the relocation so that it can be emitted during <a href="#a260c83ace2744d606c0ffa69ec9be9f2">writeObject()</a>.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>

</div>
</div>

### writeEnd() {#af5fcffab76e6fcefcbe4293fdc63b0d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GOFFObjectWriter::writeEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a5d8160a21a216880a331021a4a112999affe3aa6f338cca77eddf80bbaab9386a">llvm::GOFF::END_EPR_None</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/anonymous-goffobjectwriter-cpp-/flags/#a1de0ca40605c5a0ccf624bf90cfe3953">anonymous{GOFFObjectWriter.cpp}::Flags::Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a0cf018cb9ae43f5fdf6288c3f4b50ffbaee4d114304b98c0c902da1fee306eea8">llvm::GOFF::RT_END</a>.</p>


<p>Referenced by <a href="#a260c83ace2744d606c0ffa69ec9be9f2">writeObject</a>.</p>

</div>
</div>

### writeHeader() {#a3992a2bfd4bb0b0696e40fd7f55a10c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GOFFObjectWriter::writeHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a0cf018cb9ae43f5fdf6288c3f4b50ffbaca3e490356a5af3693b9c0b9dfa3c309">llvm::GOFF::RT_HDR</a>.</p>


<p>Referenced by <a href="#a260c83ace2744d606c0ffa69ec9be9f2">writeObject</a>.</p>

</div>
</div>

### writeObject() {#a260c83ace2744d606c0ffa69ec9be9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t GOFFObjectWriter::writeObject (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Write the object file and returns the number of bytes written.</p>


<p>This routine is called by the assembler after layout and relaxation is complete, fixups have been evaluated and applied, and relocations generated.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af5fcffab76e6fcefcbe4293fdc63b0d3">writeEnd</a> and <a href="#a3992a2bfd4bb0b0696e40fd7f55a10c6">writeHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OS {#aeadcf74cee04fb938b960b3ac5a1bb72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GOFFOstream anonymous{GOFFObjectWriter.cpp}::GOFFObjectWriter::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### TargetObjectWriter {#a808c056c37d809e1a2a6d0853278286b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCGOFFObjectTargetWriter&gt; anonymous{GOFFObjectWriter.cpp}::GOFFObjectWriter::TargetObjectWriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/goffobjectwriter-cpp">GOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
