---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/genericcycleinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GenericCycleInfo` Class Template Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> information for a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ContextT&gt;
class llvm::GenericCycleInfo&lt;ContextT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">llvm/ADT/GenericCycleInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> = typename ContextT::BlockT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> = <a href="/web-llvm/docs/api/classes/llvm/genericcycle">GenericCycle</a>&lt; ContextT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02c76b7a3dabdcbb6a18e771081710ca">FunctionT</a> = typename ContextT::FunctionT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d5180ab3d8d7c180292e17899ded14a">const_toplevel_iterator_base</a> = typename std::vector&lt; std::unique_ptr&lt; <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> &gt; &gt;::const_iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteration over top-level cycles. <a href="#a1d5180ab3d8d7c180292e17899ded14a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52c698dc9fa0ec2b2042df3a30c593f0">GenericCycle</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a38124a404a1b92ec96119f0eac2556f3">GenericCycleInfoCompute</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0ba7b6d2d92237ef9cb1c88b7ce91e9c">GenericCycleInfo</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac90ac34e4f804b38aa1e6ee181f007af">GenericCycleInfo</a> (GenericCycleInfo &amp;&amp;)=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo">GenericCycleInfo</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6bffc4a5ae536b85145c96b9c6c35909">operator=</a> (GenericCycleInfo &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87b0733715b0dce4542aa7f773837f8a">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the object to its initial state. <a href="#a87b0733715b0dce4542aa7f773837f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa93636fb87d5bd9286dd23819369c922">compute</a> (FunctionT &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the cycle info for a function. <a href="#aa93636fb87d5bd9286dd23819369c922">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaafd4490450bfe8ed71fe84c0ee76d4d">splitCriticalEdge</a> (BlockT *Pred, BlockT *Succ, BlockT *New)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a02c76b7a3dabdcbb6a18e771081710ca">FunctionT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46161384f9aa22fce4cef53216dec95a">getFunction</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ContextT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab0660190368f23e613eae071ed00394">getSSAContext</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#affe3d364d20f96ecf084548127e37ab8">getCycle</a> (const BlockT *Block) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the innermost cycle containing a given block. <a href="#affe3d364d20f96ecf084548127e37ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c47a216faa270d72d6d9e3151b317de">getSmallestCommonCycle</a> (CycleT *A, CycleT *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the innermost cycle containing both given cycles. <a href="#a5c47a216faa270d72d6d9e3151b317de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adc4336aca5f741d1d1ef4bda3cc8ded2">getCycleDepth</a> (const BlockT *Block) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get the depth for the cycle which containing a given block. <a href="#adc4336aca5f741d1d1ef4bda3cc8ded2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0649b1bdbe8877ce85c49190ac76e5b">getTopLevelParentCycle</a> (BlockT *Block)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a153679add0de628fdec2583dfd0769f2">addBlockToCycle</a> (BlockT *Block, CycleT *Cycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assumes that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a></span> is the innermost cycle containing <span class="doxyComputerOutput">Block</span>. <a href="#a153679add0de628fdec2583dfd0769f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae904a4b9606fecdfe67c809691433c35">verifyCycleNest</a> (bool VerifyFull=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for debug and self-test. <a href="#ae904a4b9606fecdfe67c809691433c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0bdd1c5ece7d11c39a095191fd9746ac">verify</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the entire cycle tree well-formed. <a href="#a0bdd1c5ece7d11c39a095191fd9746ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a553e81871c23e0e1a1048884dc38df39">print</a> (raw_ostream &amp;Out) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the cycle info. <a href="#a553e81871c23e0e1a1048884dc38df39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac5e5cadc3ccfc5c42bfd6910942a88b9">dump</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2128f697d04aae15eaa3ec8fbf9ec2a">print</a> (const CycleT *Cycle)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericcycleinfo/const-toplevel-iterator">const_toplevel_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0e00d29ec617face3e9be10e8e2d9c2">toplevel_begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericcycleinfo/const-toplevel-iterator">const_toplevel_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b96e09a105eff95799d546ecefa396a">toplevel_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d952f103899496db10f31e9ab5661b4">toplevel_cycles</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericcycleinfo/const-toplevel-iterator">const_toplevel_iterator</a> &gt;</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac32f876c4a6fba43e234ad971e5d8b79">moveTopLevelCycleToNewParent</a> (CycleT *NewParent, CycleT *Child)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move <span class="doxyComputerOutput">Child</span> to <span class="doxyComputerOutput">NewParent</span> by manipulating Children vectors. <a href="#ac32f876c4a6fba43e234ad971e5d8b79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ContextT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e991c6c6ca4a02212c5bff9af5bc70e">Context</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> *, <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a278f160a23712af2d36440c286da0ff3">BlockMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map basic blocks to their inner-most containing cycle. <a href="#a278f160a23712af2d36440c286da0ff3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> *, <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add7bf84c9a74189ee8f280d750322a74">BlockMapTopLevel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map basic blocks to their top level containing cycle. <a href="#add7bf84c9a74189ee8f280d750322a74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46df25df84db4dd5534608f66ee96c65">TopLevelCycles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Top-level cycles discovered by any DFS. <a href="#a46df25df84db4dd5534608f66ee96c65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> information for a function.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockT {#aec1c9d49a4d0b62899f66e685df5bcc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericCycleInfo&lt; ContextT &gt;::BlockT =  typename ContextT::BlockT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### const\_toplevel\_iterator\_base {#a1d5180ab3d8d7c180292e17899ded14a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericCycleInfo&lt; ContextT &gt;::const_toplevel_iterator_base = 
      typename std::vector&lt;std::unique_ptr&lt;CycleT&gt;&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iteration over top-level cycles.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### CycleT {#a9e8490b86453fd5197b0890c7c4b2b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericCycleInfo&lt; ContextT &gt;::CycleT =  GenericCycle&lt;ContextT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### FunctionT {#a02c76b7a3dabdcbb6a18e771081710ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericCycleInfo&lt; ContextT &gt;::FunctionT =  typename ContextT::FunctionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### GenericCycle {#a52c698dc9fa0ec2b2042df3a30c593f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/genericcycle">GenericCycle</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### GenericCycleInfoCompute {#a38124a404a1b92ec96119f0eac2556f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfocompute">GenericCycleInfoCompute</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>


<p>Referenced by <a href="#aa93636fb87d5bd9286dd23819369c922">llvm::GenericCycleInfo&lt; ContextT &gt;::compute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GenericCycleInfo() {#a0ba7b6d2d92237ef9cb1c88b7ce91e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericCycleInfo&lt; ContextT &gt;::GenericCycleInfo ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### GenericCycleInfo() {#ac90ac34e4f804b38aa1e6ee181f007af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericCycleInfo&lt; ContextT &gt;::GenericCycleInfo (<a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo">GenericCycleInfo</a> &amp;&amp;)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a6bffc4a5ae536b85145c96b9c6c35909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericCycleInfo &amp; llvm::GenericCycleInfo&lt; ContextT &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo">GenericCycleInfo</a> &amp;&amp;)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBlockToCycle() {#a153679add0de628fdec2583dfd0769f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::addBlockToCycle (<a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> * Block, <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * Cycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assumes that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a></span> is the innermost cycle containing <span class="doxyComputerOutput">Block</span>.</p>


<p><span class="doxyComputerOutput">Block</span> will be appended to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a></span> and all of its parent cycles. <span class="doxyComputerOutput">Block</span> will be added to BlockMap with <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a></span> and BlockMapTopLevel with <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a>'s</span> top level parent cycle.</p>


<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a> and <a href="#aaafd4490450bfe8ed71fe84c0ee76d4d">llvm::GenericCycleInfo&lt; ContextT &gt;::splitCriticalEdge</a>.</p>

</div>
</div>

### clear() {#a87b0733715b0dce4542aa7f773837f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the object to its initial state.</p>

<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>

</div>
</div>

### compute() {#aa93636fb87d5bd9286dd23819369c922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::compute (<a href="#a02c76b7a3dabdcbb6a18e771081710ca">FunctionT</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the cycle info for a function.</p>

<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a38124a404a1b92ec96119f0eac2556f3">llvm::GenericCycleInfo&lt; ContextT &gt;::GenericCycleInfoCompute</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfocompute/#a8af31f91b7b3fe098e8966229069b1ae">llvm::GenericCycleInfoCompute&lt; ContextT &gt;::run</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cycleanalysis/#add7a1719f5d818684035dca74ae8f1d5">llvm::CycleAnalysis::run</a>.</p>

</div>
</div>

### dump() {#ac5e5cadc3ccfc5c42bfd6910942a88b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::dump ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### getCycle() {#affe3d364d20f96ecf084548127e37ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::GenericCycleInfo&lt; ContextT &gt;::getCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> * Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the innermost cycle containing a given block.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the innermost cycle containing <span class="doxyComputerOutput">Block</span> or nullptr if it is not contained in any cycle.</p></dd>
</dl>


<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>.</p>


<p>Referenced by <a href="#adc4336aca5f741d1d1ef4bda3cc8ded2">llvm::GenericCycleInfo&lt; ContextT &gt;::getCycleDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aeddbadaf9b53e5eee3dade2e9cd3512d">llvm::SIInstrInfo::isSafeToSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a7410ae1c5df256622e23ceee6bd19734">mayBeInCycle</a> and <a href="#aaafd4490450bfe8ed71fe84c0ee76d4d">llvm::GenericCycleInfo&lt; ContextT &gt;::splitCriticalEdge</a>.</p>

</div>
</div>

### getCycleDepth() {#adc4336aca5f741d1d1ef4bda3cc8ded2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GenericCycleInfo&lt; ContextT &gt;::getCycleDepth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> * Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>get the depth for the cycle which containing a given block.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the depth for the innermost cycle containing <span class="doxyComputerOutput">Block</span> or 0 if it is not contained in any cycle.</p></dd>
</dl>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="#affe3d364d20f96ecf084548127e37ab8">llvm::GenericCycleInfo&lt; ContextT &gt;::getCycle</a>.</p>

</div>
</div>

### getFunction() {#a46161384f9aa22fce4cef53216dec95a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionT * llvm::GenericCycleInfo&lt; ContextT &gt;::getFunction ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### getSmallestCommonCycle() {#a5c47a216faa270d72d6d9e3151b317de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::GenericCycleInfo&lt; ContextT &gt;::getSmallestCommonCycle (<a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * A, <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the innermost cycle containing both given cycles.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the innermost cycle containing both <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> or nullptr if there is no such cycle.</p></dd>
</dl>


<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="#aaafd4490450bfe8ed71fe84c0ee76d4d">llvm::GenericCycleInfo&lt; ContextT &gt;::splitCriticalEdge</a>.</p>

</div>
</div>

### getSSAContext() {#aab0660190368f23e613eae071ed00394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ContextT &amp; llvm::GenericCycleInfo&lt; ContextT &gt;::getSSAContext ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### getTopLevelParentCycle() {#af0649b1bdbe8877ce85c49190ac76e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::GenericCycleInfo&lt; ContextT &gt;::getTopLevelParentCycle (<a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> * Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### print() {#a553e81871c23e0e1a1048884dc38df39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the cycle info.</p>

<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1d952f103899496db10f31e9ab5661b4">llvm::GenericCycleInfo&lt; ContextT &gt;::toplevel_cycles</a>.</p>


<p>Referenced by <a href="#ac5e5cadc3ccfc5c42bfd6910942a88b9">llvm::GenericCycleInfo&lt; MachineSSAContext &gt;::dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a>.</p>

</div>
</div>

### print() {#ad2128f697d04aae15eaa3ec8fbf9ec2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Printable llvm::GenericCycleInfo&lt; ContextT &gt;::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * Cycle)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### splitCriticalEdge() {#aaafd4490450bfe8ed71fe84c0ee76d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::splitCriticalEdge (<a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> * Pred, <a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> * Succ, <a href="#aec1c9d49a4d0b62899f66e685df5bcc2">BlockT</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>References <a href="#a153679add0de628fdec2583dfd0769f2">llvm::GenericCycleInfo&lt; ContextT &gt;::addBlockToCycle</a>, <a href="#affe3d364d20f96ecf084548127e37ab8">llvm::GenericCycleInfo&lt; ContextT &gt;::getCycle</a>, <a href="#a5c47a216faa270d72d6d9e3151b317de">llvm::GenericCycleInfo&lt; ContextT &gt;::getSmallestCommonCycle</a> and <a href="#ae904a4b9606fecdfe67c809691433c35">llvm::GenericCycleInfo&lt; ContextT &gt;::verifyCycleNest</a>.</p>

</div>
</div>

### toplevel\_begin() {#af0e00d29ec617face3e9be10e8e2d9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_toplevel_iterator llvm::GenericCycleInfo&lt; ContextT &gt;::toplevel_begin ()</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### toplevel\_cycles() {#a1d952f103899496db10f31e9ab5661b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_toplevel_iterator &gt; llvm::GenericCycleInfo&lt; ContextT &gt;::toplevel_cycles ()</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ab8ef8dedf48f2174b2722fdc1d262dad">FixIrreducibleImpl</a>, <a href="#a553e81871c23e0e1a1048884dc38df39">llvm::GenericCycleInfo&lt; ContextT &gt;::print</a> and <a href="#ae904a4b9606fecdfe67c809691433c35">llvm::GenericCycleInfo&lt; ContextT &gt;::verifyCycleNest</a>.</p>

</div>
</div>

### toplevel\_end() {#a3b96e09a105eff95799d546ecefa396a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_toplevel_iterator llvm::GenericCycleInfo&lt; ContextT &gt;::toplevel_end ()</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### verify() {#a0bdd1c5ece7d11c39a095191fd9746ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that the entire cycle tree well-formed.</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>Reference <a href="#ae904a4b9606fecdfe67c809691433c35">llvm::GenericCycleInfo&lt; ContextT &gt;::verifyCycleNest</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ab8ef8dedf48f2174b2722fdc1d262dad">FixIrreducibleImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/cycleinfoverifierpass/#af9fcac728641055cca5bdb95469dc5e4">llvm::CycleInfoVerifierPass::run</a>.</p>

</div>
</div>

### verifyCycleNest() {#ae904a4b9606fecdfe67c809691433c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::verifyCycleNest (bool VerifyFull=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Methods for debug and self-test.</p>


<p>Verify the internal consistency of the cycle tree.</p>


<p>Note that this does <em>not</em> check that cycles are really cycles in the CFG, or that the right set of cycles in the CFG were found.</p>


<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="#a1d952f103899496db10f31e9ab5661b4">llvm::GenericCycleInfo&lt; ContextT &gt;::toplevel_cycles</a>.</p>


<p>Referenced by <a href="#aaafd4490450bfe8ed71fe84c0ee76d4d">llvm::GenericCycleInfo&lt; ContextT &gt;::splitCriticalEdge</a> and <a href="#a0bdd1c5ece7d11c39a095191fd9746ac">llvm::GenericCycleInfo&lt; ContextT &gt;::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### moveTopLevelCycleToNewParent() {#ac32f876c4a6fba43e234ad971e5d8b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericCycleInfo&lt; ContextT &gt;::moveTopLevelCycleToNewParent (<a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * NewParent, <a href="#a9e8490b86453fd5197b0890c7c4b2b7e">CycleT</a> * Child)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move <span class="doxyComputerOutput">Child</span> to <span class="doxyComputerOutput">NewParent</span> by manipulating Children vectors.</p>


<p>Note: This is an incomplete operation that does not update the depth of the subtree.</p>


<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockMap {#a278f160a23712af2d36440c286da0ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BlockT *, CycleT *&gt; llvm::GenericCycleInfo&lt; ContextT &gt;::BlockMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map basic blocks to their inner-most containing cycle.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### BlockMapTopLevel {#add7bf84c9a74189ee8f280d750322a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BlockT *, CycleT *&gt; llvm::GenericCycleInfo&lt; ContextT &gt;::BlockMapTopLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map basic blocks to their top level containing cycle.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### Context {#a9e991c6c6ca4a02212c5bff9af5bc70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextT llvm::GenericCycleInfo&lt; ContextT &gt;::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

### TopLevelCycles {#a46df25df84db4dd5534608f66ee96c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;CycleT&gt; &gt; llvm::GenericCycleInfo&lt; ContextT &gt;::TopLevelCycles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Top-level cycles discovered by any DFS.</p>


<p>Note: The implementation treats the nullptr as the parent of every top-level cycle. See <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a> for an example.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h">GenericCycleImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleinfo-h">GenericCycleInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
