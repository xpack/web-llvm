---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/debugsymbolrvasubsectionref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugSymbolRVASubsectionRef` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::DebugSymbolRVASubsectionRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">llvm/DebugInfo/CodeView/DebugSymbolRVASubsection.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref">DebugSubsectionRef</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a1b6c9e9b6880d813f98914ae8cefb">ArrayType</a> = <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad192a448275f2c09e57c349f5e38ac05">DebugSymbolRVASubsectionRef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray/#a0c6c655bf4d3fea07f07b7316af3a6a9">ArrayType::Iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98deb749c158c7a00a11ca3ad337286">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray/#a0c6c655bf4d3fea07f07b7316af3a6a9">ArrayType::Iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0384dfa88ac0b071bde119493ed97376">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55082e6517e92987e33ee8bc22075e94">initialize</a> (BinaryStreamReader &amp;Reader)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a80a1b6c9e9b6880d813f98914ae8cefb">ArrayType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b3977dd210c396a80f5fda9e91e703">RVAs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2927ffee61fcaf2faf2830d74854f262">classof</a> (const DebugSubsectionRef *S)</td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArrayType {#a80a1b6c9e9b6880d813f98914ae8cefb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::codeview::DebugSymbolRVASubsectionRef::ArrayType =  FixedStreamArray&lt;support::ulittle32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DebugSymbolRVASubsectionRef() {#ad192a448275f2c09e57c349f5e38ac05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugSymbolRVASubsectionRef::DebugSymbolRVASubsectionRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsymbolrvasubsection-cpp">DebugSymbolRVASubsection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa7ceca3b146da79c40e312d0a180582ff">llvm::codeview::CoffSymbolRVA</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref/#acca35ccd89314881b9924f28968ac872">llvm::codeview::DebugSubsectionRef::DebugSubsectionRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#af98deb749c158c7a00a11ca3ad337286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType::Iterator llvm::codeview::DebugSymbolRVASubsectionRef::begin ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>.</p>

</div>
</div>

### end() {#a0384dfa88ac0b071bde119493ed97376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType::Iterator llvm::codeview::DebugSymbolRVASubsectionRef::end ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>.</p>

</div>
</div>

### initialize() {#a55082e6517e92987e33ee8bc22075e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DebugSymbolRVASubsectionRef::initialize (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Reader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsymbolrvasubsection-cpp">DebugSymbolRVASubsection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a81b49f753bf7db44da6cf4b0fc59b76e">llvm::BinaryStreamReader::bytesRemaining</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RVAs {#a06b3977dd210c396a80f5fda9e91e703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType llvm::codeview::DebugSymbolRVASubsectionRef::RVAs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a2927ffee61fcaf2faf2830d74854f262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::DebugSymbolRVASubsectionRef::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref">DebugSubsectionRef</a> * S)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa7ceca3b146da79c40e312d0a180582ff">llvm::codeview::CoffSymbolRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref/#acca35ccd89314881b9924f28968ac872">llvm::codeview::DebugSubsectionRef::DebugSubsectionRef</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref/#a83bd49c4af0b650932ba2b257c67f94c">llvm::codeview::DebugSubsectionRef::kind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsymbolrvasubsection-h">DebugSymbolRVASubsection.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsymbolrvasubsection-cpp">DebugSymbolRVASubsection.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
