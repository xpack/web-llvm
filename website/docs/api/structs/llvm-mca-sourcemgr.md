---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mca/sourcemgr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SourceMgr` Struct

<p>Abstracting the input code sequence (a sequence of <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>) and assigning unique identifiers to every instruction in the sequence. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::mca::SourceMgr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">llvm/MCA/SourceMgr.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/circularsourcemgr">CircularSourceMgr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The default implementation of <em><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a></em>. <a href="/web-llvm/docs/api/classes/llvm/mca/circularsourcemgr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/incrementalsourcemgr">IncrementalSourceMgr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An implementation of <em><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a></em> that allows users to add new instructions incrementally / dynamically. <a href="/web-llvm/docs/api/classes/llvm/mca/incrementalsourcemgr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a> = std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888710418e29a832599c9a3c763b9f98">~SourceMgr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83bbe5e07cea5bde328dde339681a168">getInstructions</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides a fixed range of <em><a href="#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a></em> to iterate. <a href="#a83bbe5e07cea5bde328dde339681a168">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28567a06f9ff4a7bbdb9d23603b14cf5">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(Fixed) Number of <em><a href="#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a></em>. <a href="#a28567a06f9ff4a7bbdb9d23603b14cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe16a1071f44255130ad8e0a8b47be4f">hasNext</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether there is any <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em> to inspect / peek next. <a href="#afe16a1071f44255130ad8e0a8b47be4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa062242c151e18d00bd68f6bde3726a7">isEnd</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the instruction stream has eneded. <a href="#aa062242c151e18d00bd68f6bde3726a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad28a21d3b817efd2ca56891b7df785e6">peekNext</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>. <a href="#ad28a21d3b817efd2ca56891b7df785e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07533029273c58a25a28ec3d68856abd">updateNext</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance to the next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>. <a href="#a07533029273c58a25a28ec3d68856abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Abstracting the input code sequence (a sequence of <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>) and assigning unique identifiers to every instruction in the sequence.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### UniqueInst {#ac81a93288d7e85027cbd1ec07d5d8432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::mca::SourceMgr::UniqueInst =  std::unique_ptr&lt;Instruction&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SourceMgr() {#a888710418e29a832599c9a3c763b9f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::mca::SourceMgr::~SourceMgr ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInstructions() {#a83bbe5e07cea5bde328dde339681a168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArrayRef&lt; UniqueInst &gt; llvm::mca::SourceMgr::getInstructions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provides a fixed range of <em><a href="#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a></em> to iterate.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="#a28567a06f9ff4a7bbdb9d23603b14cf5">size</a>.</p>

</div>
</div>

### hasNext() {#afe16a1071f44255130ad8e0a8b47be4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::mca::SourceMgr::hasNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether there is any <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em> to inspect / peek next.</p>


<p>Note that returning false from this doesn't mean the instruction stream has ended.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### isEnd() {#aa062242c151e18d00bd68f6bde3726a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::mca::SourceMgr::isEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the instruction stream has eneded.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### peekNext() {#ad28a21d3b817efd2ca56891b7df785e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SourceRef llvm::mca::SourceMgr::peekNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### size() {#a28567a06f9ff4a7bbdb9d23603b14cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual size_t llvm::mca::SourceMgr::size ()</td>
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

<p>(Fixed) Number of <em><a href="#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a></em>.</p>


<p>Returns the size of <em>getInstructions</em> by default.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>


<p>References <a href="#a83bbe5e07cea5bde328dde339681a168">getInstructions</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### updateNext() {#a07533029273c58a25a28ec3d68856abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::mca::SourceMgr::updateNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance to the next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/sourcemgr-h">SourceMgr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
