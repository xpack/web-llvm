---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mca/stallinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `StallInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::mca::StallInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">llvm/MCA/Stages/InOrderIssueStage.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StallKind { <a href="#a8bd475d02daeafdf54dbe71af13dd111">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe9645bbce0df937290ff406e90dea44">StallInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8bd475d02daeafdf54dbe71af13dd111">StallKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1269068402729d07bc3534008b17ee7c">getStallKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5949905bcf7645a55ee60f399746d66">getCyclesLeft</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2a69d95fd6474cd53d282d9bd49a7d">getInstruction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8265aeb6d81af64620bb56aa0a5fa6">getInstruction</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af799a01c9106d85d4cd69b9842d34d7b">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9d72d9fa69a0ac11d61ca818cee795">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acff909cacaa9bcca9cc301c8a3bfc5b2">update</a> (const InstRef &amp;Inst, unsigned Cycles, StallKind SK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86819437259d4cbb4021f18d317d37aa">cycleEnd</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c90dc647aea31521614954a1af2d5e">IR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ec119991b3862f3d5ea1d3d132a91c">CyclesLeft</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8bd475d02daeafdf54dbe71af13dd111">StallKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d3bc60694ba80596f1b745d4ef43cb">Kind</a> = <a href="#a8bd475d02daeafdf54dbe71af13dd111a5b39c8b553c821e7cddc6da64b5bd2ee">StallKind::DEFAULT</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### StallKind {#a8bd475d02daeafdf54dbe71af13dd111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::mca::StallInfo::StallKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">DEFAULT<a id="a8bd475d02daeafdf54dbe71af13dd111a5b39c8b553c821e7cddc6da64b5bd2ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REGISTER_DEPS<a id="a8bd475d02daeafdf54dbe71af13dd111a113eb6e26aaad657316fc6f037a88461"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DISPATCH<a id="a8bd475d02daeafdf54dbe71af13dd111ad21bb1180372f5ea28ce21d3af47b930"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DELAY<a id="a8bd475d02daeafdf54dbe71af13dd111aa9bec09f1dc309241c952d3828424945"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_STORE<a id="a8bd475d02daeafdf54dbe71af13dd111aee61a8e7324bb91dab1f2944eea1f457"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CUSTOM_STALL<a id="a8bd475d02daeafdf54dbe71af13dd111a3d349dbb22885bde78cfe5da2ef174a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StallInfo() {#abe9645bbce0df937290ff406e90dea44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::StallInfo::StallInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a6c9d72d9fa69a0ac11d61ca818cee795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::StallInfo::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>


<p>References <a href="#a37ec119991b3862f3d5ea1d3d132a91c">CyclesLeft</a>, <a href="#a8bd475d02daeafdf54dbe71af13dd111a5b39c8b553c821e7cddc6da64b5bd2ee">DEFAULT</a>, <a href="#ad6c90dc647aea31521614954a1af2d5e">IR</a> and <a href="#a61d3bc60694ba80596f1b745d4ef43cb">Kind</a>.</p>

</div>
</div>

### cycleEnd() {#a86819437259d4cbb4021f18d317d37aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::StallInfo::cycleEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>


<p>References <a href="#a37ec119991b3862f3d5ea1d3d132a91c">CyclesLeft</a> and <a href="#af799a01c9106d85d4cd69b9842d34d7b">isValid</a>.</p>

</div>
</div>

### getCyclesLeft() {#ac5949905bcf7645a55ee60f399746d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::StallInfo::getCyclesLeft ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Reference <a href="#a37ec119991b3862f3d5ea1d3d132a91c">CyclesLeft</a>.</p>

</div>
</div>

### getInstruction() {#a2c2a69d95fd6474cd53d282d9bd49a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstRef &amp; llvm::mca::StallInfo::getInstruction ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Reference <a href="#ad6c90dc647aea31521614954a1af2d5e">IR</a>.</p>

</div>
</div>

### getInstruction() {#a1b8265aeb6d81af64620bb56aa0a5fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstRef &amp; llvm::mca::StallInfo::getInstruction ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Reference <a href="#ad6c90dc647aea31521614954a1af2d5e">IR</a>.</p>

</div>
</div>

### getStallKind() {#a1269068402729d07bc3534008b17ee7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StallKind llvm::mca::StallInfo::getStallKind ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Reference <a href="#a61d3bc60694ba80596f1b745d4ef43cb">Kind</a>.</p>

</div>
</div>

### isValid() {#af799a01c9106d85d4cd69b9842d34d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::StallInfo::isValid ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Reference <a href="#ad6c90dc647aea31521614954a1af2d5e">IR</a>.</p>


<p>Referenced by <a href="#a86819437259d4cbb4021f18d317d37aa">cycleEnd</a>.</p>

</div>
</div>

### update() {#acff909cacaa9bcca9cc301c8a3bfc5b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::StallInfo::update (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; Inst, unsigned Cycles, <a href="#a8bd475d02daeafdf54dbe71af13dd111">StallKind</a> SK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>


<p>References <a href="#a37ec119991b3862f3d5ea1d3d132a91c">CyclesLeft</a>, <a href="#ad6c90dc647aea31521614954a1af2d5e">IR</a> and <a href="#a61d3bc60694ba80596f1b745d4ef43cb">Kind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CyclesLeft {#a37ec119991b3862f3d5ea1d3d132a91c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::StallInfo::CyclesLeft = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Referenced by <a href="#a6c9d72d9fa69a0ac11d61ca818cee795">clear</a>, <a href="#a86819437259d4cbb4021f18d317d37aa">cycleEnd</a>, <a href="#ac5949905bcf7645a55ee60f399746d66">getCyclesLeft</a> and <a href="#acff909cacaa9bcca9cc301c8a3bfc5b2">update</a>.</p>

</div>
</div>

### IR {#ad6c90dc647aea31521614954a1af2d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstRef llvm::mca::StallInfo::IR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Referenced by <a href="#a6c9d72d9fa69a0ac11d61ca818cee795">clear</a>, <a href="#a1b8265aeb6d81af64620bb56aa0a5fa6">getInstruction</a>, <a href="#a2c2a69d95fd6474cd53d282d9bd49a7d">getInstruction</a>, <a href="#af799a01c9106d85d4cd69b9842d34d7b">isValid</a> and <a href="#acff909cacaa9bcca9cc301c8a3bfc5b2">update</a>.</p>

</div>
</div>

### Kind {#a61d3bc60694ba80596f1b745d4ef43cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StallKind llvm::mca::StallInfo::Kind = <a href="#a8bd475d02daeafdf54dbe71af13dd111a5b39c8b553c821e7cddc6da64b5bd2ee">StallKind::DEFAULT</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<p>Referenced by <a href="#a6c9d72d9fa69a0ac11d61ca818cee795">clear</a>, <a href="#a1269068402729d07bc3534008b17ee7c">getStallKind</a> and <a href="#acff909cacaa9bcca9cc301c8a3bfc5b2">update</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
