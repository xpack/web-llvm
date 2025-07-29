---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpblockbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPBlockBase` Class

<p><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is the building block of the Hierarchical Control-Flow Graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPBlockBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> serves as the leaf of the Hierarchical Control-Flow Graph. <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> represents a collection of VPBasicBlocks and VPRegionBlocks which form a Single-Entry-Single-Exiting subgraph of the output IR CFG. <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841e64e06418da3dfc5b125c28501f79">VPBlockTy</a> = enum { VPRegionBlockSC, VPBasicBlockSC, VPIRBasicBlockSC }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enumeration for keeping track of the concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> that are actually instantiated. <a href="#a841e64e06418da3dfc5b125c28501f79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c507ede82b7aae55ff51781fe5460e">VPBlocksTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac053f64c43882b2047a6e3327c37cea7">VPBlockUtils</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a> (const unsigned char SC, const std::string &amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d46e0af4ed3a8efd5d527ce28cf923">~VPBlockBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a988a0c37082352835d8143c41c4bb7d1">getName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd1c53f9607876b22c6fd3ec1e28a50">setName</a> (const Twine &amp;newName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b9da2f344a05c34d0ba729bd6d5e11">getVPBlockID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09de70cbaf2f15aa3b0697b5f378cc9d">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977dd2b3ef8275c4b508d17fbe63021d">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d57e2fe646928a51e97714005eefdc7">getPlan</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad152b021b8a4d61adf9c288698ae1b12">getPlan</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961946cf5fda7331e31bf343c79da2c3">setPlan</a> (VPlan *ParentPlan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the pointer of the plan containing the block. <a href="#a961946cf5fda7331e31bf343c79da2c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2be49bdbbda0aeadd51549f4b88c839">setParent</a> (VPRegionBlock *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad928235da3a32b50ba65140da09daf5d">getEntryBasicBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd35a887b6f48b00ca1d5e91e76c61b">getEntryBasicBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28da654f916bf44da5513b6f1788835c">getExitingBasicBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc14e63f0b3ccb864c8b18116cc04896">getExitingBasicBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a48c507ede82b7aae55ff51781fe5460e">VPBlocksTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeccf6a036968755c6d86e2d2bb17673a">getSuccessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a48c507ede82b7aae55ff51781fe5460e">VPBlocksTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad501c052d02299731a5aaaf56593e278">getSuccessors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> ** &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b8fb6b951d671365edaae4b68a2666">successors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> ** &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2526abff3e6d88edde3f67cc61842e74">predecessors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a48c507ede82b7aae55ff51781fe5460e">VPBlocksTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73370de0db181ec55a9ad0b7a3a78a88">getPredecessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a48c507ede82b7aae55ff51781fe5460e">VPBlocksTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237039258cea2bae16c6c04b29b80a64">getPredecessors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc0e1a3379ed4fd614889e24b8ea48c">getSingleSuccessor</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bb4808c7a5db9f8ed3f479c78c4b5e">getSinglePredecessor</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c13ffed8c55e1b8dd38fedc7e71e7a8">getNumSuccessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639c16e1926e9971c12a8e7dc0bb3fc4">getNumPredecessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b3e12afa6f4e2c80df1ef6b8016ed2">getEnclosingBlockWithSuccessors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An Enclosing Block of a block B is any block containing B, including B itself. <a href="#ad8b3e12afa6f4e2c80df1ef6b8016ed2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af97077cfc13f00d3cdeb74cb2c8b46">getEnclosingBlockWithPredecessors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a48c507ede82b7aae55ff51781fe5460e">VPBlocksTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeecdb846ffdf9d5a558c97be2b870d3">getHierarchicalSuccessors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fdc9559945a9c56514fab982e9e5c14">getSingleHierarchicalSuccessor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a48c507ede82b7aae55ff51781fe5460e">VPBlocksTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f615b312a6949a3938cc0da03875aac">getHierarchicalPredecessors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb7f03f5f68b01423a16a5dd469ddc71">getSingleHierarchicalPredecessor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ad192a841a53fd3a289320e0958e10">setOneSuccessor</a> (VPBlockBase *Successor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a given <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> <span class="doxyComputerOutput">Successor</span> as the single successor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>. <a href="#ae0ad192a841a53fd3a289320e0958e10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13d3b4d460075f3bb6a6eeb6a5e9bd7">setTwoSuccessors</a> (VPBlockBase *IfTrue, VPBlockBase *IfFalse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set two given VPBlockBases <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span> to be the two successors of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>. <a href="#aa13d3b4d460075f3bb6a6eeb6a5e9bd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a02d7faad162c3e17d0c522d032320b">setPredecessors</a> (ArrayRef&lt; VPBlockBase * &gt; NewPreds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set each <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> in <span class="doxyComputerOutput">NewPreds</span> as predecessor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>. <a href="#a6a02d7faad162c3e17d0c522d032320b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b9bb044f64dd4be2942e4f4e6b467d">setSuccessors</a> (ArrayRef&lt; VPBlockBase * &gt; NewSuccs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set each <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> in <span class="doxyComputerOutput">NewSuccss</span> as successor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>. <a href="#a08b9bb044f64dd4be2942e4f4e6b467d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbad647e343d37f18c1bb642fa424c76">clearPredecessors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all the predecessor of this block. <a href="#abbad647e343d37f18c1bb642fa424c76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e077642586377d67713ebfc26bceef3">clearSuccessors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all the successors of this block. <a href="#a9e077642586377d67713ebfc26bceef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f7e15ac1a813112684effc1e5593a4">swapSuccessors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap successors of the block. The block must have exactly 2 successors. <a href="#a43f7e15ac1a813112684effc1e5593a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa443b1e87b5e6101f6b17c13ee60858">execute</a> (VPTransformState *State)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The method which generates the output IR that correspond to this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#aaa443b1e87b5e6101f6b17c13ee60858">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846d811fcf51fcca50981fdda893c583">cost</a> (ElementCount VF, VPCostContext &amp;Ctx)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of the block. <a href="#a846d811fcf51fcca50981fdda893c583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6e3d9484c0646d55793f278cceebb6">isLegalToHoistInto</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is legal to hoist instructions into this block. <a href="#a4e6e3d9484c0646d55793f278cceebb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd254d3c7d20b321a4b4bfa6917db0d5">printAsOperand</a> (raw_ostream &amp;OS, bool PrintType=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e5d57c5b660e6897b8adc40acf3fdc">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print plain-text dump of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> to <span class="doxyComputerOutput">O</span>, prefixing all lines with <span class="doxyComputerOutput">Indent</span>. <a href="#a39e5d57c5b660e6897b8adc40acf3fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f26339b06942e3219569b4c5b738495">print</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print plain-text dump of this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>. <a href="#a5f26339b06942e3219569b4c5b738495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ac4d968960d46c6c4d93cb35369b39">printSuccessors</a> (raw_ostream &amp;O, const Twine &amp;Indent) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the successors of this block to <span class="doxyComputerOutput">O</span>, prefixing all lines with <span class="doxyComputerOutput">Indent</span>. <a href="#a44ac4d968960d46c6c4d93cb35369b39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b07d1e1a358501745f8436a63da2d9">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>. <a href="#a29b07d1e1a358501745f8436a63da2d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a7db9f25c1b9588227351ce452e872">clone</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current block and it's recipes without updating the operands of the cloned recipes, including all blocks in the single-entry single-exit region for VPRegionBlocks. <a href="#a73a7db9f25c1b9588227351ce452e872">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae036544331f1b5a08751e76fb234e1d2">appendSuccessor</a> (VPBlockBase *Successor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput">Successor</span> as the last successor to this block. <a href="#ae036544331f1b5a08751e76fb234e1d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0fba105425458e399a049243649d708">appendPredecessor</a> (VPBlockBase *Predecessor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput">Predecessor</span> as the last predecessor to this block. <a href="#af0fba105425458e399a049243649d708">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84624c268152357bbb8589d3f23285b0">removePredecessor</a> (VPBlockBase *Predecessor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">Predecessor</span> from the predecessors of this block. <a href="#a84624c268152357bbb8589d3f23285b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08819625515ef07b21fdb4f166dba884">removeSuccessor</a> (VPBlockBase *Successor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">Successor</span> from the successors of this block. <a href="#a08819625515ef07b21fdb4f166dba884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37779d0794ef3b3b22716cdc2571ea9">replacePredecessor</a> (VPBlockBase *Old, VPBlockBase *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function replaces one predecessor with another, useful when trying to replace an old block in the CFG with a new one. <a href="#aa37779d0794ef3b3b22716cdc2571ea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af8ff6d6640e5a4b8706080833b3ee6">replaceSuccessor</a> (VPBlockBase *Old, VPBlockBase *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function replaces one successor with another, useful when trying to replace an old block in the CFG with a new one. <a href="#a4af8ff6d6640e5a4b8706080833b3ee6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6de72455e75f98bb844086aac9918d5">SubclassID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass identifier (for isa/dyn_cast). <a href="#af6de72455e75f98bb844086aac9918d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24cac3c7bb00f062494152d0c8d9cd88">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An optional name for the block. <a href="#a24cac3c7bb00f062494152d0c8d9cd88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbcd334667fc2602bfc0700fbb1fbaff">Parent</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The immediate <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> which this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> belongs to, or null if it is a topmost <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>. <a href="#abbcd334667fc2602bfc0700fbb1fbaff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7b6d5e9372f30a8169f7b196c6b06e">Predecessors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of predecessor blocks. <a href="#a9b7b6d5e9372f30a8169f7b196c6b06e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af051c02157b73e86f448f938183ac4ef">Successors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of successor blocks. <a href="#af051c02157b73e86f448f938183ac4ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae387578b96250d46a204e7e6972378b2">Plan</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> containing the block. <a href="#ae387578b96250d46a204e7e6972378b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is the building block of the Hierarchical Control-Flow Graph.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> can be either a <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> or a <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>.</p>


<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### VPBlocksTy {#a48c507ede82b7aae55ff51781fe5460e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::VPBlockBase::VPBlocksTy =  SmallVectorImpl&lt;VPBlockBase *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VPBlockTy {#a841e64e06418da3dfc5b125c28501f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::VPBlockBase::VPBlockTy =  enum { VPRegionBlockSC, VPBasicBlockSC, VPIRBasicBlockSC }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enumeration for keeping track of the concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> that are actually instantiated.</p>


<p>Values of this enumeration are kept in the SubclassID field of the <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> objects. They are used for concrete type identification.</p>


<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### VPBlockUtils {#ac053f64c43882b2047a6e3327c37cea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpblockutils">VPBlockUtils</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06add2496ae8d635f9f169602771c88d376">llvm::Successor</a>, <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a> and <a href="#ac053f64c43882b2047a6e3327c37cea7">VPBlockUtils</a>.</p>


<p>Referenced by <a href="#ac053f64c43882b2047a6e3327c37cea7">VPBlockUtils</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### VPBlockBase() {#ad435a0e2dd67fef67f3169c288480063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBlockBase::VPBlockBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; N)</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#af1741a0f8cdede694db6ce57bcaa832b">llvm::VPBasicBlock::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#afe5f86d6b56efdddce5ca7baaf5d417b">llvm::VPRegionBlock::classof</a>, <a href="#a73a7db9f25c1b9588227351ce452e872">clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a0001ec4686be34ad7e56cb0798bef1b0">llvm::VPRegionBlock::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2ffeb0208ddb1c5cf8a4bfb2ef0c9008">llvm::VPBasicBlock::connectToPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#aa948ba905ff37c533b3c85068f94fd24">llvm::VPRegionBlock::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a305d2f13922c7da4206b299861370a80">llvm::VPBasicBlock::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ac503442fd011b1b4a03ab40ad3f9402e">llvm::VPRegionBlock::execute</a>, <a href="#a6af97077cfc13f00d3cdeb74cb2c8b46">getEnclosingBlockWithPredecessors</a>, <a href="#ad8b3e12afa6f4e2c80df1ef6b8016ed2">getEnclosingBlockWithSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ae2eff5aca291e3185f5e8c2b1bd350ec">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="#a3dd35a887b6f48b00ca1d5e91e76c61b">getEntryBasicBlock</a>, <a href="#ad928235da3a32b50ba65140da09daf5d">getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a431480e4d503947a4dd06763a2b7e705">llvm::VPRegionBlock::getExiting</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#add3be1d1d9e5b1ee2014c32d21bf2b5b">llvm::VPRegionBlock::getExiting</a>, <a href="#adc14e63f0b3ccb864c8b18116cc04896">getExitingBasicBlock</a>, <a href="#a28da654f916bf44da5513b6f1788835c">getExitingBasicBlock</a>, <a href="#aeb7f03f5f68b01423a16a5dd469ddc71">getSingleHierarchicalPredecessor</a>, <a href="#a9fdc9559945a9c56514fab982e9e5c14">getSingleHierarchicalSuccessor</a>, <a href="#aa1bb4808c7a5db9f8ed3f479c78c4b5e">getSinglePredecessor</a>, <a href="#aebc0e1a3379ed4fd614889e24b8ea48c">getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a9798204f943ee8fc7c6efd2ab0f7c3d6">llvm::VPRegionBlock::setEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a414a617643992b9d0e5b70df5fd423d5">llvm::VPRegionBlock::setExiting</a>, <a href="#ae0ad192a841a53fd3a289320e0958e10">setOneSuccessor</a>, <a href="#aa13d3b4d460075f3bb6a6eeb6a5e9bd7">setTwoSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a48b1baa1bde0038b903175d208c286c2">llvm::VPBasicBlock::VPBasicBlock</a>, <a href="#ac053f64c43882b2047a6e3327c37cea7">VPBlockUtils</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#af7d3e451ebdc58b7a1ae06950281e6d4">llvm::VPBasicBlock::VPlan</a> and <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#af7d3e451ebdc58b7a1ae06950281e6d4">llvm::VPRegionBlock::VPlan</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPBlockBase() {#a53d46e0af4ed3a8efd5d527ce28cf923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::VPBlockBase::~VPBlockBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearPredecessors() {#abbad647e343d37f18c1bb642fa424c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::clearPredecessors ()</td>
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

<p>Remove all the predecessor of this block.</p>

<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a63345282cd67ea46202fb33523be1408">llvm::VPBlockUtils::reassociateBlocks</a>.</p>

</div>
</div>

### clearSuccessors() {#a9e077642586377d67713ebfc26bceef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::clearSuccessors ()</td>
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

<p>Remove all the successors of this block.</p>

<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a63345282cd67ea46202fb33523be1408">llvm::VPBlockUtils::reassociateBlocks</a>.</p>

</div>
</div>

### clone() {#a73a7db9f25c1b9588227351ce452e872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual VPBlockBase * llvm::VPBlockBase::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the current block and it's recipes without updating the operands of the cloned recipes, including all blocks in the single-entry single-exit region for VPRegionBlocks.</p>

<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>

</div>
</div>

### cost() {#a846d811fcf51fcca50981fdda893c583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual InstructionCost llvm::VPBlockBase::cost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of the block.</p>

<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### dump() {#a29b07d1e1a358501745f8436a63da2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::VPBlockBase::dump ()</td>
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

<p>Dump this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>.</p>

<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a39e5d57c5b660e6897b8adc40acf3fdc">print</a>.</p>

</div>
</div>

### execute() {#aaa443b1e87b5e6101f6b17c13ee60858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::VPBlockBase::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The method which generates the output IR that correspond to this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getEnclosingBlockWithPredecessors() {#a6af97077cfc13f00d3cdeb74cb2c8b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * VPBlockBase::getEnclosingBlockWithPredecessors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the closest enclosing block starting from "this", which has predecessors.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the root enclosing block if all enclosing blocks have no predecessors.</p></dd>
</dl>


<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="#a5f615b312a6949a3938cc0da03875aac">getHierarchicalPredecessors</a> and <a href="#aeb7f03f5f68b01423a16a5dd469ddc71">getSingleHierarchicalPredecessor</a>.</p>

</div>
</div>

### getEnclosingBlockWithSuccessors() {#ad8b3e12afa6f4e2c80df1ef6b8016ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * VPBlockBase::getEnclosingBlockWithSuccessors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An Enclosing Block of a block B is any block containing B, including B itself.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the closest enclosing block starting from "this", which has successors.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the root enclosing block if all enclosing blocks have no successors.</p></dd>
</dl>


<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="#aaeecdb846ffdf9d5a558c97be2b870d3">getHierarchicalSuccessors</a> and <a href="#a9fdc9559945a9c56514fab982e9e5c14">getSingleHierarchicalSuccessor</a>.</p>

</div>
</div>

### getEntryBasicBlock() {#ad928235da3a32b50ba65140da09daf5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBasicBlock * VPBlockBase::getEntryBasicBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> that is the entry of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>, recursively, if the latter is a <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>. Otherwise, if this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is a <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a>, it is returned.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> that is the entry of Block, possibly indirectly.</p></dd>
</dl>


<p>Declaration at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ace9e1e6e7295914973dec18350b382ca">llvm::VPlanTransforms::clearReductionWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a826173bded23a3839e30074a98ad34a1">llvm::VPRecipeBuilder::createHeaderMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a9484786140efebf774cde8f072894246">llvm::InnerLoopVectorizer::fixVectorizedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8a0202a443a527ba17fcd111497feb7d">removeRedundantExpandSCEVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a2ff7a57c84a06ee83b0a28763db85c3f">removeRedundantInductionCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a7a1cca51bb9bce4efad1063dcf158967">llvm::VPlanTransforms::unrollByUF</a>.</p>

</div>
</div>

### getEntryBasicBlock() {#a3dd35a887b6f48b00ca1d5e91e76c61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * VPBlockBase::getEntryBasicBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>

</div>
</div>

### getExitingBasicBlock() {#a28da654f916bf44da5513b6f1788835c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBasicBlock * VPBlockBase::getExitingBasicBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> that is the exiting this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>, recursively, if the latter is a <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>. Otherwise, if this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is a <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a>, it is returned.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> that is the exit of Block, possibly indirectly.</p></dd>
</dl>


<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ae74f6f8bac76399d081c42c4a216c2af">llvm::VPRegionBlock::getPreheaderVPBB</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### getExitingBasicBlock() {#adc14e63f0b3ccb864c8b18116cc04896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * VPBlockBase::getExitingBasicBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>

</div>
</div>

### getHierarchicalPredecessors() {#a5f615b312a6949a3938cc0da03875aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBlocksTy &amp; llvm::VPBlockBase::getHierarchicalPredecessors ()</td>
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
<dd><p>the predecessors either attached directly to this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> or, if this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is the entry block of a <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> and has no predecessors of its own, search recursively for the first enclosing <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> that has predecessors and return them. If no such <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> exists, return the (empty) predecessors of the topmost <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> reached.</p></dd>
</dl>


<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a6af97077cfc13f00d3cdeb74cb2c8b46">getEnclosingBlockWithPredecessors</a> and <a href="#a73370de0db181ec55a9ad0b7a3a78a88">getPredecessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2ffeb0208ddb1c5cf8a4bfb2ef0c9008">llvm::VPBasicBlock::connectToPredecessors</a>.</p>

</div>
</div>

### getHierarchicalSuccessors() {#aaeecdb846ffdf9d5a558c97be2b870d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBlocksTy &amp; llvm::VPBlockBase::getHierarchicalSuccessors ()</td>
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
<dd><p>the successors either attached directly to this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> or, if this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is the exit block of a <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> and has no successors of its own, search recursively for the first enclosing <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> that has successors and return them. If no such <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> exists, return the (empty) successors of the topmost <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> reached.</p></dd>
</dl>


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#ad8b3e12afa6f4e2c80df1ef6b8016ed2">getEnclosingBlockWithSuccessors</a> and <a href="#aeccf6a036968755c6d86e2d2bb17673a">getSuccessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2ffeb0208ddb1c5cf8a4bfb2ef0c9008">llvm::VPBasicBlock::connectToPredecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock/#a1b80ef1bd7a976b5fa4b95052cfeebba">llvm::VPIRBasicBlock::execute</a>.</p>

</div>
</div>

### getName() {#a988a0c37082352835d8143c41c4bb7d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::VPBlockBase::getName ()</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#acd254d3c7d20b321a4b4bfa6917db0d5">printAsOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock/#af7d3e451ebdc58b7a1ae06950281e6d4">llvm::VPIRBasicBlock::VPlan</a>.</p>

</div>
</div>

### getNumPredecessors() {#a639c16e1926e9971c12a8e7dc0bb3fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::VPBlockBase::getNumPredecessors ()</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getNumSuccessors() {#a2c13ffed8c55e1b8dd38fedc7e71e7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::VPBlockBase::getNumSuccessors ()</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock/#a1b80ef1bd7a976b5fa4b95052cfeebba">llvm::VPIRBasicBlock::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a85800ca7a821f540ad2d6d4d3c2d4208">llvm::VPlan::getExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a8bc6161a466df7dcd1b7bcf8661e667a">hasConditionalTerminator</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5222866a9b2208ea05c3e3ed61a313e9">llvm::InnerLoopVectorizer::introduceCheckBlockInVPlan</a>.</p>

</div>
</div>

### getParent() {#a09de70cbaf2f15aa3b0697b5f378cc9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRegionBlock * llvm::VPBlockBase::getParent ()</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a8bc6161a466df7dcd1b7bcf8661e667a">hasConditionalTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a1f625b90be26a131061ab1e43740cc81">llvm::VPBlockUtils::insertBlockAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a69d51be488551c2983a022bb98494901">llvm::VPBlockUtils::insertBlockBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a3a43b6445802190031bda62347e97453">llvm::VPBlockUtils::insertTwoBlocksAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp/#a85f42ae734efbd570ae873ab9aa8edc0">isHeaderVPBB</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>, <a href="#ae0ad192a841a53fd3a289320e0958e10">setOneSuccessor</a> and <a href="/web-llvm/docs/api/classes/anonymous-vplanverifier-cpp-/vplanverifier/#a4140274aee97c60c4a26d1ecd4234a78">anonymous{VPlanVerifier.cpp}::VPlanVerifier::verify</a>.</p>

</div>
</div>

### getParent() {#a977dd2b3ef8275c4b508d17fbe63021d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPRegionBlock * llvm::VPBlockBase::getParent ()</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getPlan() {#a8d57e2fe646928a51e97714005eefdc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan * VPBlockBase::getPlan ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pointer to the plan containing the current block.</p></dd>
</dl>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a148d01ae241556feadb34a5f005b61cd">getPlanEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a6516e17cd03806dc29350794ce78ef42">llvm::VPBasicBlock::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock/#afceb03f9a3559e8a318b340834941b16">llvm::VPIRBasicBlock::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a0001ec4686be34ad7e56cb0798bef1b0">llvm::VPRegionBlock::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker/#a5a7e7a1fc5386a94fa15cc6e157d7b79">llvm::VPSlotTracker::getOrCreateName</a>, <a href="#a5f26339b06942e3219569b4c5b738495">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a3a8743a69fac5e7fa9c2b02604b2cf2f">replaceVPBBWithIRVPBB</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a9b75fcd70de89596b8f04904aa42e2cd">llvm::VPBasicBlock::splitAt</a>.</p>

</div>
</div>

### getPlan() {#ad152b021b8a4d61adf9c288698ae1b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPlan * VPBlockBase::getPlan ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a148d01ae241556feadb34a5f005b61cd">getPlanEntry</a>.</p>

</div>
</div>

### getPredecessors() {#a73370de0db181ec55a9ad0b7a3a78a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBlocksTy &amp; llvm::VPBlockBase::getPredecessors ()</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#ac1ac18b9f807acbc9846d923ea874524">cloneFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#a82c7920e0c53dc071f1ac55f91a2895f">llvm::VPIRInstruction::execute</a>, <a href="#a5f615b312a6949a3938cc0da03875aac">getHierarchicalPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a1f625b90be26a131061ab1e43740cc81">llvm::VPBlockUtils::insertBlockAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a69d51be488551c2983a022bb98494901">llvm::VPBlockUtils::insertBlockBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a2057d0749eedf6749f9e1cc6694eb1fd">llvm::VPBlockUtils::insertOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ada5844051cef5e6e1fc7a5158c8047b7">llvm::VPIRInstruction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a63345282cd67ea46202fb33523be1408">llvm::VPBlockUtils::reassociateBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a9798204f943ee8fc7c6efd2ab0f7c3d6">llvm::VPRegionBlock::setEntry</a>.</p>

</div>
</div>

### getPredecessors() {#a237039258cea2bae16c6c04b29b80a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlocksTy &amp; llvm::VPBlockBase::getPredecessors ()</td>
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



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getSingleHierarchicalPredecessor() {#aeb7f03f5f68b01423a16a5dd469ddc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * llvm::VPBlockBase::getSingleHierarchicalPredecessor ()</td>
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
<dd><p>the hierarchical predecessor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> if it has a single hierarchical predecessor. Otherwise return a null pointer.</p></dd>
</dl>


<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a6af97077cfc13f00d3cdeb74cb2c8b46">getEnclosingBlockWithPredecessors</a>, <a href="#aa1bb4808c7a5db9f8ed3f479c78c4b5e">getSinglePredecessor</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a305d2f13922c7da4206b299861370a80">llvm::VPBasicBlock::execute</a>.</p>

</div>
</div>

### getSingleHierarchicalSuccessor() {#a9fdc9559945a9c56514fab982e9e5c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * llvm::VPBlockBase::getSingleHierarchicalSuccessor ()</td>
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
<dd><p>the hierarchical successor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> if it has a single hierarchical successor. Otherwise return a null pointer.</p></dd>
</dl>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#ad8b3e12afa6f4e2c80df1ef6b8016ed2">getEnclosingBlockWithSuccessors</a>, <a href="#aebc0e1a3379ed4fd614889e24b8ea48c">getSingleSuccessor</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>

</div>
</div>

### getSinglePredecessor() {#aa1bb4808c7a5db9f8ed3f479c78c4b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * llvm::VPBlockBase::getSinglePredecessor ()</td>
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
<dd><p>the predecessor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> if it has a single predecessor. Otherwise return a null pointer.</p></dd>
</dl>


<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ae74f6f8bac76399d081c42c4a216c2af">llvm::VPRegionBlock::getPreheaderVPBB</a>, <a href="#aeb7f03f5f68b01423a16a5dd469ddc71">getSingleHierarchicalPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aee894572833ce02ad06c067d44f65b48">llvm::VPlan::getVectorPreheader</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>.</p>

</div>
</div>

### getSingleSuccessor() {#aebc0e1a3379ed4fd614889e24b8ea48c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * llvm::VPBlockBase::getSingleSuccessor ()</td>
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
<dd><p>the successor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> if it has a single successor. Otherwise return a null pointer.</p></dd>
</dl>


<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock/#a1b80ef1bd7a976b5fa4b95052cfeebba">llvm::VPIRBasicBlock::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="#a9fdc9559945a9c56514fab982e9e5c14">getSingleHierarchicalSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### getSuccessors() {#aeccf6a036968755c6d86e2d2bb17673a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBlocksTy &amp; llvm::VPBlockBase::getSuccessors ()</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#aa948ba905ff37c533b3c85068f94fd24">llvm::VPRegionBlock::cost</a>, <a href="#aaeecdb846ffdf9d5a558c97be2b870d3">getHierarchicalSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a1f625b90be26a131061ab1e43740cc81">llvm::VPBlockUtils::insertBlockAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a69d51be488551c2983a022bb98494901">llvm::VPBlockUtils::insertBlockBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a2057d0749eedf6749f9e1cc6694eb1fd">llvm::VPBlockUtils::insertOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a3a43b6445802190031bda62347e97453">llvm::VPBlockUtils::insertTwoBlocksAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5222866a9b2208ea05c3e3ed61a313e9">llvm::InnerLoopVectorizer::introduceCheckBlockInVPlan</a>, <a href="#a44ac4d968960d46c6c4d93cb35369b39">printSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a63345282cd67ea46202fb33523be1408">llvm::VPBlockUtils::reassociateBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a414a617643992b9d0e5b70df5fd423d5">llvm::VPRegionBlock::setExiting</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### getSuccessors() {#ad501c052d02299731a5aaaf56593e278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlocksTy &amp; llvm::VPBlockBase::getSuccessors ()</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getVPBlockID() {#ac2b9da2f344a05c34d0ba729bd6d5e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPBlockBase::getVPBlockID ()</td>
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
<dd><p>an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the concrete type of this object. This is used to implement the classof checks. This should not be used for any other purpose, as the values may change as LLVM evolves.</p></dd>
</dl>


<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### isLegalToHoistInto() {#a4e6e3d9484c0646d55793f278cceebb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPBlockBase::isLegalToHoistInto ()</td>
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

<p>Return true if it is legal to hoist instructions into this block.</p>

<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### predecessors() {#a2526abff3e6d88edde3f67cc61842e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; VPBlockBase ** &gt; llvm::VPBlockBase::predecessors ()</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a69d51be488551c2983a022bb98494901">llvm::VPBlockUtils::insertBlockBefore</a>.</p>

</div>
</div>

### print() {#a39e5d57c5b660e6897b8adc40acf3fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::VPBlockBase::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print plain-text dump of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> to <span class="doxyComputerOutput">O</span>, prefixing all lines with <span class="doxyComputerOutput">Indent</span>.</p>


<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a></span> is used to print unnamed <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>'s using consequtive numbers.</p>


<p>Note that the numbering is applied to the whole <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, so printing individual blocks is consistent with the whole <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> printing.</p>


<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a29b07d1e1a358501745f8436a63da2d9">dump</a> and <a href="#a5f26339b06942e3219569b4c5b738495">print</a>.</p>

</div>
</div>

### print() {#a5f26339b06942e3219569b4c5b738495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Print plain-text dump of this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>.</p>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a8d57e2fe646928a51e97714005eefdc7">getPlan</a> and <a href="#a39e5d57c5b660e6897b8adc40acf3fdc">print</a>.</p>

</div>
</div>

### printAsOperand() {#acd254d3c7d20b321a4b4bfa6917db0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::printAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool PrintType=false)</td>
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



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a988a0c37082352835d8143c41c4bb7d1">getName</a>.</p>

</div>
</div>

### printSuccessors() {#a44ac4d968960d46c6c4d93cb35369b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPBlockBase::printSuccessors (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the successors of this block to <span class="doxyComputerOutput">O</span>, prefixing all lines with <span class="doxyComputerOutput">Indent</span>.</p>

<p>Declaration at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Reference <a href="#aeccf6a036968755c6d86e2d2bb17673a">getSuccessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#abaf6ac959836f909c24a39b8913ec22f">llvm::VPBasicBlock::print</a> and <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ab02924e690f0a12f4b58c4e40e4ead42">llvm::VPRegionBlock::print</a>.</p>

</div>
</div>

### setName() {#a2bd1c53f9607876b22c6fd3ec1e28a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::setName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; newName)</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a36d6728b8c3cfca0a9bd02c3f0273477">llvm::LoopVectorizationPlanner::buildVPlans</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>.</p>

</div>
</div>

### setOneSuccessor() {#ae0ad192a841a53fd3a289320e0958e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::setOneSuccessor (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Successor)</td>
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

<p>Set a given <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> <span class="doxyComputerOutput">Successor</span> as the single successor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>.</p>


<p>This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is not added as predecessor of <span class="doxyComputerOutput">Successor</span>. This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> must have no successors.</p>


<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a09de70cbaf2f15aa3b0697b5f378cc9d">getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06add2496ae8d635f9f169602771c88d376">llvm::Successor</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>.</p>

</div>
</div>

### setParent() {#ae2be49bdbbda0aeadd51549f4b88c839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::setParent (<a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * P)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a1f625b90be26a131061ab1e43740cc81">llvm::VPBlockUtils::insertBlockAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a69d51be488551c2983a022bb98494901">llvm::VPBlockUtils::insertBlockBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a3a43b6445802190031bda62347e97453">llvm::VPBlockUtils::insertTwoBlocksAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a9798204f943ee8fc7c6efd2ab0f7c3d6">llvm::VPRegionBlock::setEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a414a617643992b9d0e5b70df5fd423d5">llvm::VPRegionBlock::setExiting</a>.</p>

</div>
</div>

### setPlan() {#a961946cf5fda7331e31bf343c79da2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPBlockBase::setPlan (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> * ParentPlan)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the pointer of the plan containing the block.</p>


<p>The block must be the entry block into the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#a9f311a1a101ba9ebbdafb31a67942b69">llvm::VPlan::setEntry</a>.</p>

</div>
</div>

### setPredecessors() {#a6a02d7faad162c3e17d0c522d032320b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::setPredecessors (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * &gt; NewPreds)</td>
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

<p>Set each <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> in <span class="doxyComputerOutput">NewPreds</span> as predecessor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>.</p>


<p>This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> must have no predecessors. This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is not added as successor of any <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> in <span class="doxyComputerOutput">NewPreds</span>.</p>


<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#ac1ac18b9f807acbc9846d923ea874524">cloneFrom</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a3a43b6445802190031bda62347e97453">llvm::VPBlockUtils::insertTwoBlocksAfter</a>.</p>

</div>
</div>

### setSuccessors() {#a08b9bb044f64dd4be2942e4f4e6b467d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::setSuccessors (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * &gt; NewSuccs)</td>
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

<p>Set each <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> in <span class="doxyComputerOutput">NewSuccss</span> as successor of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>.</p>


<p>This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> must have no successors. This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is not added as predecessor of any <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> in <span class="doxyComputerOutput">NewSuccs</span>.</p>


<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#ac1ac18b9f807acbc9846d923ea874524">cloneFrom</a>.</p>

</div>
</div>

### setTwoSuccessors() {#aa13d3b4d460075f3bb6a6eeb6a5e9bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::setTwoSuccessors (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * IfTrue, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * IfFalse)</td>
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

<p>Set two given VPBlockBases <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span> to be the two successors of this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>.</p>


<p>This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is not added as predecessor of <span class="doxyComputerOutput">IfTrue</span> or <span class="doxyComputerOutput">IfFalse</span>. This <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> must have no successors.</p>


<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad435a0e2dd67fef67f3169c288480063">VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a3a43b6445802190031bda62347e97453">llvm::VPBlockUtils::insertTwoBlocksAfter</a>.</p>

</div>
</div>

### successors() {#a37b8fb6b951d671365edaae4b68a2666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; VPBlockBase ** &gt; llvm::VPBlockBase::successors ()</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#ac1ac18b9f807acbc9846d923ea874524">cloneFrom</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a1f625b90be26a131061ab1e43740cc81">llvm::VPBlockUtils::insertBlockAfter</a>.</p>

</div>
</div>

### swapSuccessors() {#a43f7e15ac1a813112684effc1e5593a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::swapSuccessors ()</td>
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

<p>Swap successors of the block. The block must have exactly 2 successors.</p>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5222866a9b2208ea05c3e3ed61a313e9">llvm::InnerLoopVectorizer::introduceCheckBlockInVPlan</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### appendPredecessor() {#af0fba105425458e399a049243649d708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::appendPredecessor (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Predecessor)</td>
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

<p>Add <span class="doxyComputerOutput">Predecessor</span> as the last predecessor to this block.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### appendSuccessor() {#ae036544331f1b5a08751e76fb234e1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::appendSuccessor (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Successor)</td>
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

<p>Add <span class="doxyComputerOutput">Successor</span> as the last successor to this block.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### removePredecessor() {#a84624c268152357bbb8589d3f23285b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::removePredecessor (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Predecessor)</td>
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

<p>Remove <span class="doxyComputerOutput">Predecessor</span> from the predecessors of this block.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### removeSuccessor() {#a08819625515ef07b21fdb4f166dba884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::removeSuccessor (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Successor)</td>
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

<p>Remove <span class="doxyComputerOutput">Successor</span> from the successors of this block.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### replacePredecessor() {#aa37779d0794ef3b3b22716cdc2571ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::replacePredecessor (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * New)</td>
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

<p>This function replaces one predecessor with another, useful when trying to replace an old block in the CFG with a new one.</p>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### replaceSuccessor() {#a4af8ff6d6640e5a4b8706080833b3ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::replaceSuccessor (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * New)</td>
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

<p>This function replaces one successor with another, useful when trying to replace an old block in the CFG with a new one.</p>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#a24cac3c7bb00f062494152d0c8d9cd88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::VPBlockBase::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An optional name for the block.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Parent {#abbcd334667fc2602bfc0700fbb1fbaff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRegionBlock* llvm::VPBlockBase::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The immediate <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> which this <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> belongs to, or null if it is a topmost <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a>.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Plan {#ae387578b96250d46a204e7e6972378b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan* llvm::VPBlockBase::Plan = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> containing the block.</p>


<p>Can only be set on the entry block of the plan.</p>


<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Predecessors {#a9b7b6d5e9372f30a8169f7b196c6b06e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPBlockBase *, 1&gt; llvm::VPBlockBase::Predecessors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of predecessor blocks.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### SubclassID {#af6de72455e75f98bb844086aac9918d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char llvm::VPBlockBase::SubclassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subclass identifier (for isa/dyn_cast).</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Successors {#af051c02157b73e86f448f938183ac4ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPBlockBase *, 1&gt; llvm::VPBlockBase::Successors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of successor blocks.</p>

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
