---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopBase` Class Template Reference

<p>Instances of this class are used to represent loops that are detected in the flow graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class BlockT, class LoopT&gt;
class llvm::LoopBase&lt;BlockT, LoopT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">llvm/Support/GenericLoopInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">std::vector&lt; LoopT * &gt;::const_iterator <a href="#a72e879f0ce9d0a27682764a646e4e39b">iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">std::vector&lt; LoopT * &gt;::const_reverse_iterator <a href="#a6a54d22b222dd2d916b746691a77bf1b">reverse_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; BlockT * &gt;::const_iterator <a href="#ab24de043c5c57a0d0dbb2adf902e8db1">block_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">std::pair&lt; BlockT *, BlockT * &gt; <a href="#a7af45cfb87a55ce89a5fb4d3bd030f99">Edge</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a7af45cfb87a55ce89a5fb4d3bd030f99">Edge</a> type. <a href="#a7af45cfb87a55ce89a5fb4d3bd030f99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a33e248a0d534ee2f1efac8ccada6e824">LoopInfoBase&lt; BlockT, LoopT &gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a59a281b029e934c17c57b63835e3da6d">LoopBase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This creates an empty loop. <a href="#a59a281b029e934c17c57b63835e3da6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a49b0d8558f7035e143827c43def3a4e0">LoopBase</a> (BlockT *BB)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac2f293d7125e96b5af3cbb8b8475b2ce">LoopBase</a> (const LoopBase&lt; BlockT, LoopT &gt; &amp;)=delete</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a53ffbec3d6c6ed90a6c4cb95821564c7">~LoopBase</a> ()</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47b4fda64a2f25bfc113a88a396fd8a4">operator=</a> (const LoopBase&lt; BlockT, LoopT &gt; &amp;)=delete -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopbase">LoopBase</a>&lt; BlockT, LoopT &gt; &amp;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a57994482c17097d9f936acff3a6598ac">getLoopDepth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the nesting level of this loop. <a href="#a57994482c17097d9f936acff3a6598ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">getHeader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae34bcd53f75fab0c03b509ecccb4cfaf">getParentLoop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the parent loop if it exists or nullptr for top level loops. <a href="#ae34bcd53f75fab0c03b509ecccb4cfaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4beaa4fee25a2bddc65e7bfb3256428b">getOutermostLoop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the outermost loop in which this loop is contained. <a href="#a4beaa4fee25a2bddc65e7bfb3256428b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae00897ea85f68b4b34da55d3e6cb308b">getOutermostLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae20cb5deb73baeef7ce6066ae40ac30c">setParentLoop</a> (LoopT *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a raw interface for bypassing addChildLoop. <a href="#ae20cb5deb73baeef7ce6066ae40ac30c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04337b572d34ea413c35dbac5d75530b">contains</a> (const LoopT *L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified loop is contained within in this loop. <a href="#a04337b572d34ea413c35dbac5d75530b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a90277ae893bf65114f311d451b30da61">contains</a> (const BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified basic block is in this loop. <a href="#a90277ae893bf65114f311d451b30da61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class InstT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2104f591c8f4f8453a58b36e676b807d">contains</a> (const InstT *Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified instruction is in this loop. <a href="#a2104f591c8f4f8453a58b36e676b807d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a56aaf5c25d50d52888f79b444f2d6c">getSubLoops</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; LoopT * &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the loops contained entirely within this loop. <a href="#a4a56aaf5c25d50d52888f79b444f2d6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab2a10b1f4c08d1b204d4152441b3666f">getSubLoopsVector</a> () -&gt; std::vector&lt; LoopT * &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a72e879f0ce9d0a27682764a646e4e39b">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af2f81059dc7566164b018aac6555eb1a">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a72e879f0ce9d0a27682764a646e4e39b">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a98eb0888f30e7a27151a7b02fa053205">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6a54d22b222dd2d916b746691a77bf1b">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab46c719e495b9c74838830999b187e87">rbegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6a54d22b222dd2d916b746691a77bf1b">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad45f06ecb4a52cc8a00fa239220d93ff">rend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16165c1e5da45acaa086c3a54a188d34">isInnermost</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop does not contain any (natural) loops. <a href="#a16165c1e5da45acaa086c3a54a188d34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0fa33dfd6ffaaae721fc05b6941263aa">isOutermost</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop does not have a parent (natural) loop. <a href="#a0fa33dfd6ffaaae721fc05b6941263aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac94e1f7398df9df2508957f58a82279a">getBlocks</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; BlockT * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a list of the basic blocks which make up this loop. <a href="#ac94e1f7398df9df2508957f58a82279a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab24de043c5c57a0d0dbb2adf902e8db1">block_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9096a02aa326d9a55f4d16ba9f9d243">block_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab24de043c5c57a0d0dbb2adf902e8db1">block_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a7815ad3e094df37f2312a4bba8c13e">block_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78bec3084b9a47ee11cc2e56f9004717">blocks</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab24de043c5c57a0d0dbb2adf902e8db1">block_iterator</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a261ee3c4745564c7be9283984c9af06b">getNumBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of blocks in this loop in constant time. <a href="#a261ee3c4745564c7be9283984c9af06b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a694013a572e3a133dc062625c6f8b02f">getBlocksVector</a> () -&gt; std::vector&lt; BlockT * &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a direct, mutable handle to the blocks vector so that we can mutate it efficiently with techniques like <span class="doxyComputerOutput">std::remove</span>. <a href="#a694013a572e3a133dc062625c6f8b02f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06036ccc79d96685d00a5eb38606cde9">getBlocksSet</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockT * &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a direct, mutable handle to the blocks set so that we can mutate it efficiently. <a href="#a06036ccc79d96685d00a5eb38606cde9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af54068e435ee3c1dfa91a69dec020def">getBlocksSet</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockT * &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a direct, immutable handle to the blocks set. <a href="#af54068e435ee3c1dfa91a69dec020def">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7cea07afaa9cb9cb11334832b90eaf0a">isInvalid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this loop is no longer valid. <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af691775d5a45e28afbdb3e97cab22eee">isLoopExiting</a> (const BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if terminator in the block can branch to another block that is outside of the current loop. <a href="#af691775d5a45e28afbdb3e97cab22eee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a942049bae5e6ebd49bcc8a70a35f824b">isLoopLatch</a> (const BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a389bb3581ba3c8094b89642efaf8e514">getNumBackEdges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the number of back edges to the loop header. <a href="#a389bb3581ba3c8094b89642efaf8e514">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46880fab7a9d5bd439725f2acc59b80d">getExitingBlocks</a> (SmallVectorImpl&lt; BlockT * &gt; &amp;ExitingBlocks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all blocks inside the loop that have successors outside of the loop. <a href="#a46880fab7a9d5bd439725f2acc59b80d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf6f53d7652b471c995b7d10f3dd2729">getExitingBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If getExitingBlocks would return exactly one block, return that block. <a href="#adf6f53d7652b471c995b7d10f3dd2729">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d9238c61483c12dce660bae4c8cc2d2">getExitBlocks</a> (SmallVectorImpl&lt; BlockT * &gt; &amp;ExitBlocks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all of the successor blocks of this loop. <a href="#a1d9238c61483c12dce660bae4c8cc2d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab48af53a5000ecede46c76dabb4578d2">getExitBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If getExitBlocks would return exactly one block, return that block. <a href="#ab48af53a5000ecede46c76dabb4578d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7ebc88c9b32b51b749bd5bbcfaa5fb8">hasDedicatedExits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if no exit block for the loop has a predecessor that is outside the loop. <a href="#ae7ebc88c9b32b51b749bd5bbcfaa5fb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae069a12f0a2d2deb69e30b439a91190e">getUniqueExitBlocks</a> (SmallVectorImpl&lt; BlockT * &gt; &amp;ExitBlocks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all unique successor blocks of this loop. <a href="#ae069a12f0a2d2deb69e30b439a91190e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed67883fd0d5f8356bb709b4d16ebe70">getUniqueNonLatchExitBlocks</a> (SmallVectorImpl&lt; BlockT * &gt; &amp;ExitBlocks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all unique successor blocks of this loop except successors from Latch block are not considered. <a href="#aed67883fd0d5f8356bb709b4d16ebe70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd50c2de451ac9fc0865dc747dd2d485">getUniqueExitBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If getUniqueExitBlocks would return exactly one block, return that block. <a href="#afd50c2de451ac9fc0865dc747dd2d485">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a462e59069cb22aa0abd869033bb546fb">getUniqueLatchExitBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the unique exit block for the latch, or null if there are multiple different exit blocks or the latch is not exiting. <a href="#a462e59069cb22aa0abd869033bb546fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5f6bd919ffbc45bfa5e083ab9f4cef0">hasNoExitBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this loop does not have any exit blocks. <a href="#ab5f6bd919ffbc45bfa5e083ab9f4cef0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad953b1e46f8bd2ca82b9cb7285a66a7">getExitEdges</a> (SmallVectorImpl&lt; Edge &gt; &amp;ExitEdges) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all pairs of (<em>inside_block</em>,<em>outside_block</em>). <a href="#aad953b1e46f8bd2ca82b9cb7285a66a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac3280e7f76f955403fe17eacf126b90d">getLoopPreheader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there is a preheader for this loop, return it. <a href="#ac3280e7f76f955403fe17eacf126b90d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88575baf2ad9f4cd2e2432e6da4a976b">getLoopPredecessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given loop's header has exactly one unique predecessor outside the loop, return it. <a href="#a88575baf2ad9f4cd2e2432e6da4a976b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1230fd674d2609b96527fe65eaf40b1b">getLoopLatch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there is a single latch block for this loop, return it. <a href="#a1230fd674d2609b96527fe65eaf40b1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a542a6493b191eb84b5457d35ecd685c5">getLoopLatches</a> (SmallVectorImpl&lt; BlockT * &gt; &amp;LoopLatches) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all loop latch blocks of this loop. <a href="#a542a6493b191eb84b5457d35ecd685c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a450c14cda08c142b7777d753ca363cc7">getLoopsInPreorder</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopT *, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all loops in the loop nest rooted by the loop in preorder, with siblings in forward program order. <a href="#a450c14cda08c142b7777d753ca363cc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b5ed0cf8ca9b437a418c50c5ec79a38">getLoopsInPreorder</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LoopT *, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63f099d3bf7cf97eb3ae2d630e3d1afc">addBasicBlockToLoop</a> (BlockT *NewBB, LoopInfoBase&lt; BlockT, LoopT &gt; &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used by other analyses to update loop information. <a href="#a63f099d3bf7cf97eb3ae2d630e3d1afc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd429aeb9a967ffa720ea42621ee6f2d">replaceChildLoopWith</a> (LoopT *OldChild, LoopT *NewChild)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used when splitting loops up. <a href="#abd429aeb9a967ffa720ea42621ee6f2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a990a86b0de7a84a9f489d2034878e330">addChildLoop</a> (LoopT *NewChild)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified loop to be a child of this loop. <a href="#a990a86b0de7a84a9f489d2034878e330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd824d78def66604189ab07c6266572d">removeChildLoop</a> (iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This removes the specified child from being a subloop of this loop. <a href="#afd824d78def66604189ab07c6266572d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f58bf248977e85097295e3ac5a28505">removeChildLoop</a> (LoopT *Child)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This removes the specified child from being a subloop of this loop. <a href="#a6f58bf248977e85097295e3ac5a28505">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0a5e875687fec396caa916b3950e0a3">addBlockEntry</a> (BlockT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This adds a basic block directly to the basic block list. <a href="#ab0a5e875687fec396caa916b3950e0a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f79aa048a6238c8c904c2e985fa25f8">reverseBlock</a> (unsigned from)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>interface to reverse Blocks[from, end of loop] in this loop <a href="#a3f79aa048a6238c8c904c2e985fa25f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a756142b56356b7a9083d52a88c7bd3af">reserveBlocks</a> (unsigned size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>interface to do reserve() for Blocks <a href="#a756142b56356b7a9083d52a88c7bd3af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb94ad465ab2bc46ff40bec6263f7355">moveToHeader</a> (BlockT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used to move BB (which must be part of this loop) to be the loop header of the loop (the block that dominates all others). <a href="#afb94ad465ab2bc46ff40bec6263f7355">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b9dddb31a33eea763f49038e9cf7d63">removeBlockFromLoop</a> (BlockT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This removes the specified basic block from the current loop, updating the Blocks as appropriate. <a href="#a1b9dddb31a33eea763f49038e9cf7d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2896fd505fc6356f4ad5b53bb5001a39">verifyLoop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify loop structure. <a href="#a2896fd505fc6356f4ad5b53bb5001a39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a297fe1e46e53629f71cc8e9b4f53b8c9">verifyLoopNest</a> (DenseSet&lt; const LoopT * &gt; *Loops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify loop structure of this loop and all nested loops. <a href="#a297fe1e46e53629f71cc8e9b4f53b8c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a01ada0e39978b9efc4de4f0f69130b18">isAnnotatedParallel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the loop is annotated parallel. <a href="#a01ada0e39978b9efc4de4f0f69130b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b3fe20235340fb3bbf3ff86ec172d73">print</a> (raw_ostream &amp;OS, bool Verbose=false, bool PrintNested=true, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print loop with all the BBs inside it. <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2cb6a81f7afe86ce3b5aae20481837ba">ParentLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; LoopT * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2083d0568bbed8c162cf5c3edce5c154">SubLoops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; BlockT * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a22ed982a13d7ee63f2c5f9a0ddb3ed2a">Blocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockT *, 8 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8fb6155b628834277612ee143abdfcd">DenseBlockSet</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0a4eb676d872db65ea116ed4e983c61b">getInnerLoopsInPreorder</a> (const LoopT &amp;L, SmallVectorImpl&lt; Type &gt; &amp;PreOrderLoops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all inner loops in the loop nest rooted by the loop in preorder, with siblings in forward program order. <a href="#a0a4eb676d872db65ea116ed4e983c61b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Instances of this class are used to represent loops that are detected in the flow graph.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### block\_iterator {#ab24de043c5c57a0d0dbb2adf902e8db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef ArrayRef&lt;BlockT*&gt;::const_iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::block_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### Edge {#a7af45cfb87a55ce89a5fb4d3bd030f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::pair&lt;BlockT *, BlockT *&gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::Edge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a7af45cfb87a55ce89a5fb4d3bd030f99">Edge</a> type.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### iterator {#a72e879f0ce9d0a27682764a646e4e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;LoopT*&gt;::const_iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### reverse\_iterator {#a6a54d22b222dd2d916b746691a77bf1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;LoopT*&gt;::const_reverse_iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LoopInfoBase&lt; BlockT, LoopT &gt; {#a33e248a0d534ee2f1efac8ccada6e824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/loopinfobase">LoopInfoBase</a>&lt; BlockT, LoopT &gt;</td>
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


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### LoopBase() {#a59a281b029e934c17c57b63835e3da6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopBase&lt; BlockT, LoopT &gt;::LoopBase ()</td>
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

<p>This creates an empty loop.</p>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### LoopBase() {#a49b0d8558f7035e143827c43def3a4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopBase&lt; BlockT, LoopT &gt;::LoopBase (BlockT * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LoopBase() {#ac2f293d7125e96b5af3cbb8b8475b2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopBase&lt; BlockT, LoopT &gt;::LoopBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopbase">LoopBase</a>&lt; BlockT, LoopT &gt; &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~LoopBase() {#a53ffbec3d6c6ed90a6c4cb95821564c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopBase&lt; BlockT, LoopT &gt;::~LoopBase ()</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a47b4fda64a2f25bfc113a88a396fd8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopBase&lt; BlockT, LoopT &gt; &amp; llvm::LoopBase&lt; BlockT, LoopT &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopbase">LoopBase</a>&lt; BlockT, LoopT &gt; &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBasicBlockToLoop() {#a63f099d3bf7cf97eb3ae2d630e3d1afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::addBasicBlockToLoop (BlockT * NewBB, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase">LoopInfoBase</a>&lt; BlockT, LoopT &gt; &amp; LIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is used by other analyses to update loop information.</p>


<p>addBasicBlockToLoop - This method is used by other analyses to update loop information.</p>


<p>NewBB is set to be a new member of the current loop. Because of this, it is added as a member of all parent loops, and is added to the specified <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> object as being in the current basic block. It is not valid to replace the loop header with this method.</p>


<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac3328dd05f047ea11f19504685b0e136">llvm::addClonedBlockToLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### addBlockEntry() {#ab0a5e875687fec396caa916b3950e0a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::addBlockEntry (BlockT * BB)</td>
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

<p>This adds a basic block directly to the basic block list.</p>


<p>This should only be used by transformations that create new loops. Other transformations should use addBasicBlockToLoop.</p>


<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>.</p>

</div>
</div>

### addChildLoop() {#a990a86b0de7a84a9f489d2034878e330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop (LoopT * NewChild)</td>
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

<p>Add the specified loop to be a child of this loop.</p>


<p>This updates the loop depth of the new child.</p>


<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac3328dd05f047ea11f19504685b0e136">llvm::addClonedBlockToLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/#a8547d158fd9eb8e0cb27673ac3034a1c">llvm::TileInfo::CreateTiledLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ac503442fd011b1b4a03ab40ad3f9402e">llvm::VPRegionBlock::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afa8d35023dc30883011a5641eac69d38">hoistLoopToNewParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a>.</p>

</div>
</div>

### begin() {#af2f81059dc7566164b018aac6555eb1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::begin ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#a4a56aaf5c25d50d52888f79b444f2d6c">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#aef5a823f024815a31e9be15d48d037dc">isLoopDead</a>, <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>, <a href="#afd824d78def66604189ab07c6266572d">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a> and <a href="#a297fe1e46e53629f71cc8e9b4f53b8c9">llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoopNest</a>.</p>

</div>
</div>

### block\_begin() {#af9096a02aa326d9a55f4d16ba9f9d243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block_iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::block_begin ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#ac94e1f7398df9df2508957f58a82279a">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks</a>.</p>


<p>Referenced by <a href="#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a855d933ff14db67cb1158c9829edd0bc">partitionOuterLoopBlocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a0ca3a00e53b761acd04d67f7401b6ee8">partitionOuterLoopBlocks</a>.</p>

</div>
</div>

### block\_end() {#a7a7815ad3e094df37f2312a4bba8c13e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block_iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::block_end ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#ac94e1f7398df9df2508957f58a82279a">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks</a>.</p>


<p>Referenced by <a href="#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a855d933ff14db67cb1158c9829edd0bc">partitionOuterLoopBlocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a0ca3a00e53b761acd04d67f7401b6ee8">partitionOuterLoopBlocks</a>.</p>

</div>
</div>

### blocks() {#a78bec3084b9a47ee11cc2e56f9004717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; block_iterator &gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af9096a02aa326d9a55f4d16ba9f9d243">llvm::LoopBase&lt; BlockT, LoopT &gt;::block_begin</a>, <a href="#a7a7815ad3e094df37f2312a4bba8c13e">llvm::LoopBase&lt; BlockT, LoopT &gt;::block_end</a>, <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#aca2badb4637a1c884bebc80828feac0a">llvm::ICFLoopSafetyInfo::computeLoopSafetyInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopsafetyinfo/#a262c2df9639d3f71b8d2a8158b819809">llvm::SimpleLoopSafetyInfo::computeLoopSafetyInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6e3405af64e42dd7c8d209196c884772">containsDecreasingPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a696283c30308704d020a9d86065aa3ae">planContainsAdditionalSimplifications</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ab68c7ba7bd95784715357a3fbf5235a7">llvm::AArch64TTIImpl::preferPredicateOverEpilogue</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>.</p>

</div>
</div>

### contains() {#a04337b572d34ea413c35dbac5d75530b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopT * L)</td>
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

<p>Return true if the specified loop is contained within in this loop.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a0937bbe895c7ed05d32c861b0f9e0f97">llvm::LoopSafetyInfo::allLoopPathsLeadToBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#ad908d5abcd036d7ff7e277fda6821cf0">CanProveNotTakenFirstIteration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a586a0928ddd8c387ebb2032e9f61e55b">collectCastInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a544a0723e20148ceb9a3bb3210f45270">llvm::collectChildrenInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#a0f2532bb6e482a8f04b68585b8cfc032">collectTransitivePredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="#a2104f591c8f4f8453a58b36e676b807d">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#a639eff65ee8e468b3891fbe67db54788">llvm::ICFLoopSafetyInfo::doesNotWriteMemoryBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#ab5d2c0ed240c8f7f889eedc466380a0f">llvm::ICFLoopSafetyInfo::doesNotWriteMemoryBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a69f32678ea46cdda0318c0be9bdb1c7e">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a44102f5040261d1ac399f288fc2c4a68">getInnermostLoopFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ff3bf3190a09af37c0a2eee8b5a367c">llvm::getLoopConvergenceHeart</a>, <a href="#a542a6493b191eb84b5457d35ecd685c5">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatches</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinfo-cpp-/unloopupdater/#a764281a8361495e92ef18a100019c9ec">anonymous{LoopInfo.cpp}::UnloopUpdater::getNearestLoop</a>, <a href="#a389bb3581ba3c8094b89642efaf8e514">llvm::LoopBase&lt; BlockT, LoopT &gt;::getNumBackEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp/#a2ae98e15f35ee616bea08c594611d2d7">getSingleSchedPred</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89f41bef45732023f8662884065cd058">llvm::hasOutsideLoopUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afa8d35023dc30883011a5641eac69d38">hoistLoopToNewParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aabae34d2dbed5dde1865f19ccbe4cb81">inSubLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a845058902483d2afbab93214dcce8684">isExitingLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1a0282efdd962c35bc840b90bafeb35b">isFoldableInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#adb1a03152610d15e008c2fdcb93602ed">llvm::InductionDescriptor::isFPInductionPHI</a>, <a href="#af691775d5a45e28afbdb3e97cab22eee">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopExiting</a>, <a href="#a942049bae5e6ebd49bcc8a70a35f824b">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopLatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0581d6d5dc280ba2a39087a557050a6a">isNotUsedOrFoldableInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02e1ff75cab81386059f88d395054b1c">llvm::isSafeToUnrollAndJam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3eb7a9b091032d4d053727b7a578a97e">llvm::isUniformLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a15fee12c900f8acb172d4f6d05d9b06c">needToInsertPhisForLCSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a14d6eb48f298d47bdf871282b0c03f58">partitionLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a28d9fc94843828b60459abd31b7e82c6">pointerInvalidatedByLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#af4fe7de52124908c8a757ea62ac9c59b">removeBlockFromLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab12b535502b86394c84bfd24d58e4657">llvm::LoopInfo::replacementPreservesLCSSAForm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0bb855d418108ea53140e71d7b35a2cd">splitPredecessorsOfLoopExit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinfo-cpp-/unloopupdater/#a45ca996be25c9ad831564c77e37e976c">anonymous{LoopInfo.cpp}::UnloopUpdater::updateBlockParents</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a99bbdbd6641e69bcad8fda4bf1726525">visitPointers</a>.</p>

</div>
</div>

### contains() {#a90277ae893bf65114f311d451b30da61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockT * BB)</td>
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

<p>Return true if the specified basic block is in this loop.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### contains() {#a2104f591c8f4f8453a58b36e676b807d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class InstT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InstT * Inst)</td>
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

<p>Return true if the specified instruction is in this loop.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>.</p>

</div>
</div>

### end() {#a98eb0888f30e7a27151a7b02fa053205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::end ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#a4a56aaf5c25d50d52888f79b444f2d6c">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#aef5a823f024815a31e9be15d48d037dc">isLoopDead</a>, <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a> and <a href="#a297fe1e46e53629f71cc8e9b4f53b8c9">llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoopNest</a>.</p>

</div>
</div>

### getBlocks() {#ac94e1f7398df9df2508957f58a82279a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BlockT * &gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks ()</td>
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

<p>Get a list of the basic blocks which make up this loop.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="#af9096a02aa326d9a55f4d16ba9f9d243">llvm::LoopBase&lt; BlockT, LoopT &gt;::block_begin</a>, <a href="#a7a7815ad3e094df37f2312a4bba8c13e">llvm::LoopBase&lt; BlockT, LoopT &gt;::block_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopsafetyinfo/#a262c2df9639d3f71b8d2a8158b819809">llvm::SimpleLoopSafetyInfo::computeLoopSafetyInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a28d9fc94843828b60459abd31b7e82c6">pointerInvalidatedByLoop</a>, <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### getBlocksSet() {#a06036ccc79d96685d00a5eb38606cde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSetImpl&lt; const BlockT * &gt; &amp; llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocksSet ()</td>
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

<p>Return a direct, mutable handle to the blocks set so that we can mutate it efficiently.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### getBlocksSet() {#af54068e435ee3c1dfa91a69dec020def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSetImpl&lt; const BlockT * &gt; &amp; llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocksSet ()</td>
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

<p>Return a direct, immutable handle to the blocks set.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### getBlocksVector() {#a694013a572e3a133dc062625c6f8b02f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; BlockT * &gt; &amp; llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocksVector ()</td>
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

<p>Return a direct, mutable handle to the blocks vector so that we can mutate it efficiently with techniques like <span class="doxyComputerOutput">std::remove</span>.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### getExitBlock() {#ab48af53a5000ecede46c76dabb4578d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If getExitBlocks would return exactly one block, return that block.</p>


<p>getExitBlock - If getExitBlocks would return exactly one block, return that block.</p>


<p>Otherwise return null.</p>


<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8b11747fb5f445aa96b3551722a58a64">llvm::getExitBlockHelper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a797a9f600b2119356e4ea74cdc6ba25a">llvm::LoopNest::getInterveningInstructions</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a2a08cef5ef885ecb702cabcedb86c95e">anonymous{LoopInterchange.cpp}::LoopInterchange::processLoopList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### getExitBlocks() {#a1d9238c61483c12dce660bae4c8cc2d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlocks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BlockT * &gt; &amp; ExitBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all of the successor blocks of this loop.</p>


<p>getExitBlocks - Return all of the successor blocks of this loop.</p>


<p>These are the blocks <em>outside of the current loop</em> which are branched to.</p>


<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>.</p>

</div>
</div>

### getExitEdges() {#aad953b1e46f8bd2ca82b9cb7285a66a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitEdges (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a7af45cfb87a55ce89a5fb4d3bd030f99">Edge</a> &gt; &amp; ExitEdges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all pairs of (<em>inside_block</em>,<em>outside_block</em>).</p>


<p>getExitEdges - Return all pairs of (<em>inside_block</em>,<em>outside_block</em>).</p>


<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### getExitingBlock() {#adf6f53d7652b471c995b7d10f3dd2729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If getExitingBlocks would return exactly one block, return that block.</p>


<p>getExitingBlock - If getExitingBlocks would return exactly one block, return that block.</p>


<p>Otherwise return null.</p>


<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6975e193997c4e0183e96774a7cb39">llvm::find_singleton</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a07f138d2a84576c85e238a26969e5ff9">isExitBlock</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### getExitingBlocks() {#a46880fab7a9d5bd439725f2acc59b80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlocks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BlockT * &gt; &amp; ExitingBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all blocks inside the loop that have successors outside of the loop.</p>


<p>getExitingBlocks - Return all blocks inside the loop that have successors outside of the loop.</p>


<p>These are the blocks <em>inside of the current loop</em> which branch out. The returned list is always unique.</p>


<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>.</p>

</div>
</div>

### getHeader() {#a4a75755081e9a3803d2f4ccf6f0cb1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#ac94e1f7398df9df2508957f58a82279a">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac3328dd05f047ea11f19504685b0e136">llvm::addClonedBlockToLoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a41ea5a32fdaf85d4aa83b1e2d8473fdc">llvm::BlockFrequencyInfoImplBase::addLoopSuccessorsToDist</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a0937bbe895c7ed05d32c861b0f9e0f97">llvm::LoopSafetyInfo::allLoopPathsLeadToBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#ad908d5abcd036d7ff7e277fda6821cf0">CanProveNotTakenFirstIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#a0f2532bb6e482a8f04b68585b8cfc032">collectTransitivePredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a183e3a3a68925c5689cd2149c940f59e">llvm::LoopSafetyInfo::computeBlockColors</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopsafetyinfo/#a262c2df9639d3f71b8d2a8158b819809">llvm::SimpleLoopSafetyInfo::computeLoopSafetyInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a6bfe058b12abe3443b07d4f4d55d863f">createStringMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a8ce6d27f2029316071fd8130578a2229">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::currentLimitations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#a639eff65ee8e468b3891fbe67db54788">llvm::ICFLoopSafetyInfo::doesNotWriteMemoryBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5a05fbafdbe696de6c83937542acc38e">emitBasicBlockLoopComments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#abb12e569451bee60098c4608b8ca8fa5">llvm::SystemZPostRASchedStrategy::enterMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a69f32678ea46cdda0318c0be9bdb1c7e">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a797a9f600b2119356e4ea74cdc6ba25a">llvm::LoopNest::getInterveningInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ff3bf3190a09af37c0a2eee8b5a367c">llvm::getLoopConvergenceHeart</a>, <a href="#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="#a542a6493b191eb84b5457d35ecd685c5">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatches</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a58791fa7d9b74c05628abed162ce2725">llvm::BlockFrequencyInfoImplBase::getLoopName</a>, <a href="#a88575baf2ad9f4cd2e2432e6da4a976b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPredecessor</a>, <a href="#a389bb3581ba3c8094b89642efaf8e514">llvm::LoopBase&lt; BlockT, LoopT &gt;::getNumBackEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp/#a2ae98e15f35ee616bea08c594611d2d7">getSingleSchedPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#abad1ad05191dcc842acb7c84422494a5">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::hasBackEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a68fba9e05f782a97df84dff26ef5abfa">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::isActiveLoophead</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3c81223cabf643af27adba3b3ceb680c">isExistingPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#adb1a03152610d15e008c2fdcb93602ed">llvm::InductionDescriptor::isFPInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopsafetyinfo/#a0d72ea03ecc07b164934986286ea086d">llvm::SimpleLoopSafetyInfo::isGuaranteedToExecute</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#afd0a71dc4e0ed5b83c50e875e6726661">llvm::ScalarEvolution::isKnownViaInduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a>, <a href="#a942049bae5e6ebd49bcc8a70a35f824b">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a484f974fc232e862a87a6380d3a7587d">llvm::RecurrenceDescriptor::isReductionPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a43d3fe2699745c950168939ee8f0d5cb">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::normalizeInfiniteLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a28d9fc94843828b60459abd31b7e82c6">pointerInvalidatedByLoop</a>, <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9e656ca6880429c47f777ef0d06ac030">PrintParentLoopComment</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a5342eefdd06826f163b13f40992ce8e4">anonymous{LoopInterchange.cpp}::LoopInterchange::processLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#af4fe7de52124908c8a757ea62ac9c59b">removeBlockFromLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c19b37908311872f655348755e8d003">llvm::reportVectorization</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicmimpl/#a91e4daed2453931a75ea961f1dce12ad">anonymous{MachineLICM.cpp}::MachineLICMImpl::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a0a23768d13b961c25d4bb19c3f42824c">llvm::MachineTraceMetrics::Ensemble::verify</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a99bbdbd6641e69bcad8fda4bf1726525">visitPointers</a>.</p>

</div>
</div>

### getLoopDepth() {#a57994482c17097d9f936acff3a6598ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopDepth ()</td>
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

<p>Return the nesting level of this loop.</p>


<p>An outer-most loop has depth 1, for consistency with loop depth values used for basic blocks, where depth 0 is used for blocks not inside any loops.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#ac41c50a3b85aa5098391b76548f04e3b">checkDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp/#a2a79bc90af20f89ce218dd987ea35aee">doesContainLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5a05fbafdbe696de6c83937542acc38e">emitBasicBlockLoopComments</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a69f32678ea46cdda0318c0be9bdb1c7e">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a8b3e30ba3a19f0debefc124b3682a1a1">getInnerMostLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#aee0bc590a090ac389d8f1f3957e669b6">llvm::LoopNest::getInnermostLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a44102f5040261d1ac399f288fc2c4a68">getInnermostLoopFor</a>, <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9e656ca6880429c47f777ef0d06ac030">PrintParentLoopComment</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### getLoopLatch() {#a1230fd674d2609b96527fe65eaf40b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there is a single latch block for this loop, return it.</p>


<p>getLoopLatch - If there is a single latch block for this loop, return it.</p>


<p>A latch block is a block that contains a branch back to the header.</p>


<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ac0eeb33419165d13b0fa5c5f6fc69505">areInnerLoopLatchPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a6080253e27bfa816dce219371e6a820c">areOuterLoopExitPHIsSupported</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a435b95efad7ea03299bd527b55b4708a">collectUsersInExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a797a9f600b2119356e4ea74cdc6ba25a">llvm::LoopNest::getInterveningInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a1324f8c4f6c399fbb6c4fae0404a47ca">getOuterLoopLatchCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aa898a031df90bb6ac31dc9cb253b310e">getReductionInstr</a>, <a href="#a462e59069cb22aa0abd869033bb546fb">llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueLatchExitBlock</a>, <a href="#aed67883fd0d5f8356bb709b4d16ebe70">llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueNonLatchExitBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac438183b3cdb70d2fa78265512238514">llvm::hasIterationCountInvariantInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3eb7a9b091032d4d053727b7a578a97e">llvm::isUniformLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a43d3fe2699745c950168939ee8f0d5cb">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::normalizeInfiniteLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a14d6eb48f298d47bdf871282b0c03f58">partitionLoopBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### getLoopLatches() {#a542a6493b191eb84b5457d35ecd685c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatches (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BlockT * &gt; &amp; LoopLatches)</td>
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

<p>Return all loop latch blocks of this loop.</p>


<p>A latch block is a block that contains a branch back to the header.</p>


<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a>, <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getLoopPredecessor() {#a88575baf2ad9f4cd2e2432e6da4a976b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPredecessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the given loop's header has exactly one unique predecessor outside the loop, return it.</p>


<p>getLoopPredecessor - If the given loop's header has exactly one unique predecessor outside the loop, return it.</p>


<p>Otherwise return null. This is less strict that the loop "preheader" concept, which requires the predecessor to have exactly one successor.</p>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>.</p>

</div>
</div>

### getLoopPreheader() {#ac3280e7f76f955403fe17eacf126b90d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there is a preheader for this loop, return it.</p>


<p>getLoopPreheader - If there is a preheader for this loop, return it.</p>


<p>A loop has a preheader if there is only one edge to the header of the loop from outside of the loop. If this is the case, the block branching to the header of the loop is the preheader node.</p>


<p>This method returns null if there is no preheader for the loop.</p>


<p>A loop has a preheader if there is only one edge to the header of the loop from outside of the loop and it is legal to hoist instructions into the predecessor. If this is the case, the block branching to the header of the loop is the preheader node.</p>


<p>This method returns null if there is no preheader for the loop.</p>


<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="#a88575baf2ad9f4cd2e2432e6da4a976b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a>, <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afea5bacb2f6022a2738266bec65bce41">llvm::detail::isLegalToHoistInto</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#ad908d5abcd036d7ff7e277fda6821cf0">CanProveNotTakenFirstIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a36f7b9a37f452349ad02d4d7f7d33972">anonymous{LoopDistribute.cpp}::InstPartitionContainer::cloneLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a0d6b9e4d1f5157d53f36e8c37f218233">anonymous{SimplifyIndVar.cpp}::WidenIV::createExtendInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a9336eb7b4fbcee561dbb8c52d9eabe64">createWidenInductionRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a797a9f600b2119356e4ea74cdc6ba25a">llvm::LoopNest::getInterveningInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a51b2fd564c6db478ebdc025a9781c7d0">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::isPreheaderToFlush</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a14d6eb48f298d47bdf871282b0c03f58">partitionLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### getLoopsInPreorder() {#a450c14cda08c142b7777d753ca363cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; const LoopT *, 4 &gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder ()</td>
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

<p>Return all loops in the loop nest rooted by the loop in preorder, with siblings in forward program order.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="#a0a4eb676d872db65ea116ed4e983c61b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getInnerLoopsInPreorder</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#ac41c50a3b85aa5098391b76548f04e3b">checkDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a855d933ff14db67cb1158c9829edd0bc">partitionOuterLoopBlocks</a>.</p>

</div>
</div>

### getLoopsInPreorder() {#a2b5ed0cf8ca9b437a418c50c5ec79a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; LoopT *, 4 &gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="#a0a4eb676d872db65ea116ed4e983c61b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getInnerLoopsInPreorder</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getNumBackEdges() {#a389bb3581ba3c8094b89642efaf8e514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopBase&lt; BlockT, LoopT &gt;::getNumBackEdges ()</td>
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

<p>Calculate the number of back edges to the loop header.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>.</p>

</div>
</div>

### getNumBlocks() {#a261ee3c4745564c7be9283984c9af06b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopBase&lt; BlockT, LoopT &gt;::getNumBlocks ()</td>
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

<p>Get the number of blocks in this loop in constant time.</p>


<p>Invalidate the loop, indicating that it is no longer a loop.</p>


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a> and <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#a4e63f991f0e0d6a73bbc6d0d75c49f22">llvm::LoopBlocksDFS::LoopBlocksDFS</a>.</p>

</div>
</div>

### getOutermostLoop() {#a4beaa4fee25a2bddc65e7bfb3256428b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getOutermostLoop ()</td>
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

<p>Get the outermost loop in which this loop is contained.</p>


<p>This may be the loop itself, if it already is the outermost loop.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### getOutermostLoop() {#ae00897ea85f68b4b34da55d3e6cb308b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getOutermostLoop ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### getParentLoop() {#ae34bcd53f75fab0c03b509ecccb4cfaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop ()</td>
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

<p>Return the parent loop if it exists or nullptr for top level loops.</p>


<p>A loop is either top-level in a function (that is, it is not contained in any other loop) or it is entirely enclosed in some other loop. If a loop is top-level, it has no parent, otherwise its parent is the innermost loop in which it is enclosed.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac3328dd05f047ea11f19504685b0e136">llvm::addClonedBlockToLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5a05fbafdbe696de6c83937542acc38e">emitBasicBlockLoopComments</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a8b3e30ba3a19f0debefc124b3682a1a1">getInnerMostLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a44102f5040261d1ac399f288fc2c4a68">getInnermostLoopFor</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinfo-cpp-/unloopupdater/#a764281a8361495e92ef18a100019c9ec">anonymous{LoopInfo.cpp}::UnloopUpdater::getNearestLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a5e771bd40bbd3121ec36a96aa44ef46a">getTopMostExitingLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac438183b3cdb70d2fa78265512238514">llvm::hasIterationCountInvariantInParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afa8d35023dc30883011a5641eac69d38">hoistLoopToNewParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a68fba9e05f782a97df84dff26ef5abfa">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::isActiveLoophead</a>, <a href="#a0fa33dfd6ffaaae721fc05b6941263aa">llvm::LoopBase&lt; BlockT, LoopT &gt;::isOutermost</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9e656ca6880429c47f777ef0d06ac030">PrintParentLoopComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#af4fe7de52124908c8a757ea62ac9c59b">removeBlockFromLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinfo-cpp-/unloopupdater/#a744753a404df90782bb4e68ac6fb293c">anonymous{LoopInfo.cpp}::UnloopUpdater::removeBlocksFromAncestors</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a>.</p>

</div>
</div>

### getSubLoops() {#a4a56aaf5c25d50d52888f79b444f2d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; LoopT * &gt; &amp; llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops ()</td>
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

<p>Return the loops contained entirely within this loop.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ac0eeb33419165d13b0fa5c5f6fc69505">areInnerLoopLatchPHIsSupported</a>, <a href="#af2f81059dc7566164b018aac6555eb1a">llvm::LoopBase&lt; BlockT, LoopT &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a8ce6d27f2029316071fd8130578a2229">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::currentLimitations</a>, <a href="#a98eb0888f30e7a27151a7b02fa053205">llvm::LoopBase&lt; BlockT, LoopT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#ad2c7f512c7735232319f74e85a4263e2">llvm::LoopNest::getMaxPerfectDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a8bb1c6e90f84b4551595a8a1c27534bc">isEligibleLoopForm</a>, <a href="#a16165c1e5da45acaa086c3a54a188d34">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInnermost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ada6d2508cfa150fd7974bef2dc21c40f">populateWorklist</a>, <a href="#ab46c719e495b9c74838830999b187e87">llvm::LoopBase&lt; BlockT, LoopT &gt;::rbegin</a> and <a href="#ad45f06ecb4a52cc8a00fa239220d93ff">llvm::LoopBase&lt; BlockT, LoopT &gt;::rend</a>.</p>

</div>
</div>

### getSubLoopsVector() {#ab2a10b1f4c08d1b204d4152441b3666f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; LoopT * &gt; &amp; llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoopsVector ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### getUniqueExitBlock() {#afd50c2de451ac9fc0865dc747dd2d485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueExitBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If getUniqueExitBlocks would return exactly one block, return that block.</p>


<p>Otherwise return null.</p>


<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8b11747fb5f445aa96b3551722a58a64">llvm::getExitBlockHelper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ad50c8a25364117c5dd799586dd5b0904">areInnerLoopExitPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a6080253e27bfa816dce219371e6a820c">areOuterLoopExitPHIsSupported</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>.</p>

</div>
</div>

### getUniqueExitBlocks() {#ae069a12f0a2d2deb69e30b439a91190e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueExitBlocks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BlockT * &gt; &amp; ExitBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all unique successor blocks of this loop.</p>


<p>These are the blocks <em>outside of the current loop</em> which are branched to.</p>


<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abe4d96949c2b4fda155b9e1914518e3a">llvm::getUniqueExitBlocksHelper</a>.</p>


<p>Referenced by <a href="#ae7ebc88c9b32b51b749bd5bbcfaa5fb8">llvm::LoopBase&lt; BlockT, LoopT &gt;::hasDedicatedExits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0bb855d418108ea53140e71d7b35a2cd">splitPredecessorsOfLoopExit</a>.</p>

</div>
</div>

### getUniqueLatchExitBlock() {#a462e59069cb22aa0abd869033bb546fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueLatchExitBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the unique exit block for the latch, or null if there are multiple different exit blocks or the latch is not exiting.</p>

<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6975e193997c4e0183e96774a7cb39">llvm::find_singleton</a> and <a href="#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>.</p>

</div>
</div>

### getUniqueNonLatchExitBlocks() {#aed67883fd0d5f8356bb709b4d16ebe70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueNonLatchExitBlocks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BlockT * &gt; &amp; ExitBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return all unique successor blocks of this loop except successors from Latch block are not considered.</p>


<p>If the exit comes from Latch has also non Latch predecessor in a loop it will be added to ExitBlocks. These are the blocks <em>outside of the current loop</em> which are branched to.</p>


<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abe4d96949c2b4fda155b9e1914518e3a">llvm::getUniqueExitBlocksHelper</a>.</p>

</div>
</div>

### hasDedicatedExits() {#ae7ebc88c9b32b51b749bd5bbcfaa5fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::hasDedicatedExits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if no exit block for the loop has a predecessor that is outside the loop.</p>

<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#ae069a12f0a2d2deb69e30b439a91190e">llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueExitBlocks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a>.</p>

</div>
</div>

### hasNoExitBlocks() {#ab5f6bd919ffbc45bfa5e083ab9f4cef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::hasNoExitBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this loop does not have any exit blocks.</p>

<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8b11747fb5f445aa96b3551722a58a64">llvm::getExitBlockHelper</a>.</p>

</div>
</div>

### isAnnotatedParallel() {#a01ada0e39978b9efc4de4f0f69130b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::isAnnotatedParallel ()</td>
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

<p>Returns true if the loop is annotated parallel.</p>


<p>Derived classes can override this method using static template polymorphism.</p>


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Referenced by <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>.</p>

</div>
</div>

### isInnermost() {#a16165c1e5da45acaa086c3a54a188d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::isInnermost ()</td>
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

<p>Return true if the loop does not contain any (natural) loops.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#a4a56aaf5c25d50d52888f79b444f2d6c">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5a05fbafdbe696de6c83937542acc38e">emitBasicBlockLoopComments</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c19b37908311872f655348755e8d003">llvm::reportVectorization</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>.</p>

</div>
</div>

### isInvalid() {#a7cea07afaa9cb9cb11334832b90eaf0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid ()</td>
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

<p>Return true if this loop is no longer valid.</p>


<p>The only valid use of this helper is "assert(L.isInvalid())" or equivalent, since IsInvalid is set to true by the destructor. In other words, if this accessor returns true, the caller has already triggered UB by calling this accessor; and so it can only be called in a context where a return value of true indicates a programmer error.</p>


<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Referenced by <a href="#a63f099d3bf7cf97eb3ae2d630e3d1afc">llvm::LoopBase&lt; BlockT, LoopT &gt;::addBasicBlockToLoop</a>, <a href="#ab0a5e875687fec396caa916b3950e0a3">llvm::LoopBase&lt; BlockT, LoopT &gt;::addBlockEntry</a>, <a href="#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="#a90277ae893bf65114f311d451b30da61">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a>, <a href="#ac94e1f7398df9df2508957f58a82279a">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks</a>, <a href="#a06036ccc79d96685d00a5eb38606cde9">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocksSet</a>, <a href="#af54068e435ee3c1dfa91a69dec020def">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocksSet</a>, <a href="#a694013a572e3a133dc062625c6f8b02f">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocksVector</a>, <a href="#a1d9238c61483c12dce660bae4c8cc2d2">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlocks</a>, <a href="#aad953b1e46f8bd2ca82b9cb7285a66a7">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitEdges</a>, <a href="#adf6f53d7652b471c995b7d10f3dd2729">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlock</a>, <a href="#a46880fab7a9d5bd439725f2acc59b80d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlocks</a>, <a href="#a57994482c17097d9f936acff3a6598ac">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopDepth</a>, <a href="#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="#a542a6493b191eb84b5457d35ecd685c5">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatches</a>, <a href="#a88575baf2ad9f4cd2e2432e6da4a976b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPredecessor</a>, <a href="#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="#a389bb3581ba3c8094b89642efaf8e514">llvm::LoopBase&lt; BlockT, LoopT &gt;::getNumBackEdges</a>, <a href="#a261ee3c4745564c7be9283984c9af06b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getNumBlocks</a>, <a href="#a4a56aaf5c25d50d52888f79b444f2d6c">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops</a>, <a href="#ab2a10b1f4c08d1b204d4152441b3666f">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoopsVector</a>, <a href="#af691775d5a45e28afbdb3e97cab22eee">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopExiting</a>, <a href="#a942049bae5e6ebd49bcc8a70a35f824b">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopLatch</a>, <a href="#afb94ad465ab2bc46ff40bec6263f7355">llvm::LoopBase&lt; BlockT, LoopT &gt;::moveToHeader</a>, <a href="#a1b9dddb31a33eea763f49038e9cf7d63">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeBlockFromLoop</a>, <a href="#afd824d78def66604189ab07c6266572d">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop</a>, <a href="#abd429aeb9a967ffa720ea42621ee6f2d">llvm::LoopBase&lt; BlockT, LoopT &gt;::replaceChildLoopWith</a>, <a href="#a756142b56356b7a9083d52a88c7bd3af">llvm::LoopBase&lt; BlockT, LoopT &gt;::reserveBlocks</a>, <a href="#a3f79aa048a6238c8c904c2e985fa25f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::reverseBlock</a>, <a href="#ae20cb5deb73baeef7ce6066ae40ac30c">llvm::LoopBase&lt; BlockT, LoopT &gt;::setParentLoop</a> and <a href="#a297fe1e46e53629f71cc8e9b4f53b8c9">llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoopNest</a>.</p>

</div>
</div>

### isLoopExiting() {#af691775d5a45e28afbdb3e97cab22eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopExiting (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockT * BB)</td>
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

<p>True if terminator in the block can branch to another block that is outside of the current loop.</p>


<p><span class="doxyComputerOutput">BB</span> must be inside the loop.</p>


<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a5e771bd40bbd3121ec36a96aa44ef46a">getTopMostExitingLoop</a>, <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### isLoopLatch() {#a942049bae5e6ebd49bcc8a70a35f824b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopLatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockT * BB)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>.</p>

</div>
</div>

### isOutermost() {#a0fa33dfd6ffaaae721fc05b6941263aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopBase&lt; BlockT, LoopT &gt;::isOutermost ()</td>
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

<p>Return true if the loop does not have a parent (natural) loop.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a> and <a href="/web-llvm/docs/api/classes/llvm/cachecost/#aa74e490a12ab54ad9687e6844fe605f1">llvm::CacheCost::getCacheCost</a>.</p>

</div>
</div>

### moveToHeader() {#afb94ad465ab2bc46ff40bec6263f7355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::moveToHeader (BlockT * BB)</td>
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

<p>This method is used to move BB (which must be part of this loop) to be the loop header of the loop (the block that dominates all others).</p>

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### print() {#a5b3fe20235340fb3bbf3ff86ec172d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool Verbose=false, bool PrintNested=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print loop with all the BBs inside it.</p>

<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="#af2f81059dc7566164b018aac6555eb1a">llvm::LoopBase&lt; BlockT, LoopT &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a98eb0888f30e7a27151a7b02fa053205">llvm::LoopBase&lt; BlockT, LoopT &gt;::end</a>, <a href="#ac94e1f7398df9df2508957f58a82279a">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks</a>, <a href="#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="#a57994482c17097d9f936acff3a6598ac">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#a01ada0e39978b9efc4de4f0f69130b18">llvm::LoopBase&lt; BlockT, LoopT &gt;::isAnnotatedParallel</a>, <a href="#af691775d5a45e28afbdb3e97cab22eee">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopExiting</a>, <a href="#a942049bae5e6ebd49bcc8a70a35f824b">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopLatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae4a8ad4586fa2c7678de84a5fc9ad411">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a>.</p>

</div>
</div>

### rbegin() {#ab46c719e495b9c74838830999b187e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::rbegin ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#a4a56aaf5c25d50d52888f79b444f2d6c">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops</a>.</p>

</div>
</div>

### removeBlockFromLoop() {#a1b9dddb31a33eea763f49038e9cf7d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::removeBlockFromLoop (BlockT * BB)</td>
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

<p>This removes the specified basic block from the current loop, updating the Blocks as appropriate.</p>


<p>This does not update the mapping in the <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> class.</p>


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>.</p>

</div>
</div>

### removeChildLoop() {#afd824d78def66604189ab07c6266572d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopT * llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop (<a href="#a72e879f0ce9d0a27682764a646e4e39b">iterator</a> I)</td>
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

<p>This removes the specified child from being a subloop of this loop.</p>


<p>The loop is not deleted, as it will presumably be inserted into another loop.</p>


<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af2f81059dc7566164b018aac6555eb1a">llvm::LoopBase&lt; BlockT, LoopT &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#ab508a6297bcb823ca9d561facc241470">llvm::LoopInfo::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afa8d35023dc30883011a5641eac69d38">hoistLoopToNewParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="#a6f58bf248977e85097295e3ac5a28505">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#ac41caf6254221316cf74145aacc3da9a">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::restructureLoops</a>.</p>

</div>
</div>

### removeChildLoop() {#a6f58bf248977e85097295e3ac5a28505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopT * llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop (LoopT * Child)</td>
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

<p>This removes the specified child from being a subloop of this loop.</p>


<p>The loop is not deleted, as it will presumably be inserted into another loop.</p>


<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a> and <a href="#afd824d78def66604189ab07c6266572d">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop</a>.</p>

</div>
</div>

### rend() {#ad45f06ecb4a52cc8a00fa239220d93ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::LoopBase&lt; BlockT, LoopT &gt;::rend ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>Reference <a href="#a4a56aaf5c25d50d52888f79b444f2d6c">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops</a>.</p>

</div>
</div>

### replaceChildLoopWith() {#abd429aeb9a967ffa720ea42621ee6f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::replaceChildLoopWith (LoopT * OldChild, LoopT * NewChild)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is used when splitting loops up.</p>


<p>replaceChildLoopWith - This is used when splitting loops up.</p>


<p>It replaces the OldChild entry in our children list with NewChild, and updates the parent pointer of OldChild to be null and the NewChild to be this loop. This updates the loop depth of the new child.</p>


<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>.</p>

</div>
</div>

### reserveBlocks() {#a756142b56356b7a9083d52a88c7bd3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::reserveBlocks (unsigned size)</td>
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

<p>interface to do reserve() for Blocks</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>.</p>

</div>
</div>

### reverseBlock() {#a3f79aa048a6238c8c904c2e985fa25f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::reverseBlock (unsigned from)</td>
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

<p>interface to reverse Blocks[from, end of loop] in this loop</p>

<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### setParentLoop() {#ae20cb5deb73baeef7ce6066ae40ac30c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::setParentLoop (LoopT * L)</td>
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

<p>This is a raw interface for bypassing addChildLoop.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>.</p>

</div>
</div>

### verifyLoop() {#a2896fd505fc6356f4ad5b53bb5001a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify loop structure.</p>


<p>verifyLoop - Verify loop structure</p>


<p>Declaration at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a> and <a href="#a297fe1e46e53629f71cc8e9b4f53b8c9">llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoopNest</a>.</p>

</div>
</div>

### verifyLoopNest() {#a297fe1e46e53629f71cc8e9b4f53b8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoopNest (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopT * &gt; * Loops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify loop structure of this loop and all nested loops.</p>


<p>verifyLoop - Verify loop structure of this loop and all nested loops.</p>


<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af2f81059dc7566164b018aac6555eb1a">llvm::LoopBase&lt; BlockT, LoopT &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a98eb0888f30e7a27151a7b02fa053205">llvm::LoopBase&lt; BlockT, LoopT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInvalid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a> and <a href="#a2896fd505fc6356f4ad5b53bb5001a39">llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Blocks {#a22ed982a13d7ee63f2c5f9a0ddb3ed2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BlockT *&gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::Blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### DenseBlockSet {#af8fb6155b628834277612ee143abdfcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const BlockT *, 8&gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::DenseBlockSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### ParentLoop {#a2cb6a81f7afe86ce3b5aae20481837ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopT* llvm::LoopBase&lt; BlockT, LoopT &gt;::ParentLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

### SubLoops {#a2083d0568bbed8c162cf5c3edce5c154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LoopT *&gt; llvm::LoopBase&lt; BlockT, LoopT &gt;::SubLoops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getInnerLoopsInPreorder() {#a0a4eb676d872db65ea116ed4e983c61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopBase&lt; BlockT, LoopT &gt;::getInnerLoopsInPreorder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopT &amp; L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> &gt; &amp; PreOrderLoops)</td>
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

<p>Return all inner loops in the loop nest rooted by the loop in preorder, with siblings in forward program order.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a2b5ed0cf8ca9b437a418c50c5ec79a38">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder</a> and <a href="#a450c14cda08c142b7777d753ca363cc7">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfo-h">GenericLoopInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
