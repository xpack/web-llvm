---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-dagdeltaalgorithm-cpp-/dagdeltaalgorithmimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DAGDeltaAlgorithmImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm/#ad4db5080e3127c468dd4bc6c0812142c">DAGDeltaAlgorithm::change_ty</a> <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm/#a3f8cd32d8d69f713bf3c1dbeb942273a">DAGDeltaAlgorithm::changeset_ty</a> <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm/#a2ef67c22dd53f113a1efa84a39ce14da">DAGDeltaAlgorithm::changesetlist_ty</a> <a href="#a73fb2fb506247d4d2ef82af67c0e5db6">changesetlist_ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm/#a658d0ed343fe1a2a704d4219a0a1a8ec">DAGDeltaAlgorithm::edge_ty</a> <a href="#a8d053db58c92b4617a06ef3f9a93d339">edge_ty</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> <a href="#a458df37525132b7bc7a204c2434f10c4">pred_iterator_ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> <a href="#a4db5c47723b0a5b7c16cc72c2b98e968">succ_iterator_ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::set&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> <a href="#a3bf7d55bcff35edf81945934b089f638">pred_closure_iterator_ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::set&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> <a href="#a15a051cc05681827799021ce9db3a044">succ_closure_iterator_ty</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0257793bd56ff42d04a2dfbb40285eb4">DeltaActiveSetHelper</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee0e07a9f4606d965c319cd0b62052c">DAGDeltaAlgorithmImpl</a> (DAGDeltaAlgorithm &amp;DDA, const changeset_ty &amp;Changes, const std::vector&lt; edge_ty &gt; &amp;Dependencies)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e6564221ac63609404d50bc83eb093">Run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724e29e318b7650573fd5c40744ed1dc">GetTestResult</a> (const changeset_ty &amp;Changes, const changeset_ty &amp;Required)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetTestResult - Get the test result for the active set <span class="doxyComputerOutput">Changes</span> with <span class="doxyComputerOutput">Required</span> changes from the cache, executing the test if necessary. <a href="#a724e29e318b7650573fd5c40744ed1dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">pred_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02b197c0c06cdc04305effde302119d4">pred_begin</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">pred_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd843bd0ae2077065fd0f74143e20d0">pred_end</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">pred_closure_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4be1cc07b67a65ded3313c37393b5ae">pred_closure_begin</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">pred_closure_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3401f181da987d56bac9eb56c9330ece">pred_closure_end</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">succ_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af956317e33b8dc64c7249323ea8ac228">succ_begin</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">succ_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb196d92064b22826f997c6ee7d1c7a">succ_end</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">succ_closure_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd768402b650a4bfc287bcd16d049bce">succ_closure_begin</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">succ_closure_iterator_ty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae930dac3103281694bcb928c90fb4864">succ_closure_end</a> (change_ty Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b62573ee5c6ebac46ce48926a55cce4">UpdatedSearchState</a> (const changeset_ty &amp;Changes, const changesetlist_ty &amp;Sets, const changeset_ty &amp;Required)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ebee41fc1753d11c1163726ef7a04c8">ExecuteOneTest</a> (const changeset_ty &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>. <a href="#a5ebee41fc1753d11c1163726ef7a04c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm">DAGDeltaAlgorithm</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7119a058426075d13c16ea6b8ed99ae5">DDA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b8596958cb24ebde1b849fe0c7e050">Roots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354fd96825d5d9984f4d7a612497f32d">FailedTestsCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache of failed test results. <a href="#a354fd96825d5d9984f4d7a612497f32d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a>, std::vector&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb0fa83d1ddf1c60fe02ef2103a06f63">Predecessors</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a>, std::vector&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba6b229b892c1196f70580fbf052c4a">Successors</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a>, std::set&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5883206cb96ef47c246de4e7ea258a2a">PredClosure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a>, std::set&lt; <a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5da553be9d7b171d3354e769d477906">SuccClosure</a></td>
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


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### change\_ty {#a17d845c1967f9530c93fc25fe88ab507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DAGDeltaAlgorithm::change_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::change_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### changeset\_ty {#a35737e034ee6cffbced3f2b44b91e3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DAGDeltaAlgorithm::changeset_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::changeset_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### changesetlist\_ty {#a73fb2fb506247d4d2ef82af67c0e5db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DAGDeltaAlgorithm::changesetlist_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::changesetlist_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### edge\_ty {#a8d053db58c92b4617a06ef3f9a93d339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DAGDeltaAlgorithm::edge_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::edge_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### pred\_closure\_iterator\_ty {#a3bf7d55bcff35edf81945934b089f638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::set&lt;change_ty&gt;::iterator anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::pred_closure_iterator_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### pred\_iterator\_ty {#a458df37525132b7bc7a204c2434f10c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;change_ty&gt;::iterator anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::pred_iterator_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### succ\_closure\_iterator\_ty {#a15a051cc05681827799021ce9db3a044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::set&lt;change_ty&gt;::iterator anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::succ_closure_iterator_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### succ\_iterator\_ty {#a4db5c47723b0a5b7c16cc72c2b98e968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;change_ty&gt;::iterator anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::succ_iterator_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DeltaActiveSetHelper {#a0257793bd56ff42d04a2dfbb40285eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/anonymous-dagdeltaalgorithm-cpp-/deltaactivesethelper">DeltaActiveSetHelper</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>


<p>Reference <a href="#a0257793bd56ff42d04a2dfbb40285eb4">DeltaActiveSetHelper</a>.</p>


<p>Referenced by <a href="#a0257793bd56ff42d04a2dfbb40285eb4">DeltaActiveSetHelper</a> and <a href="#a16e6564221ac63609404d50bc83eb093">Run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DAGDeltaAlgorithmImpl() {#adee0e07a9f4606d965c319cd0b62052c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DAGDeltaAlgorithmImpl::DAGDeltaAlgorithmImpl (<a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm">DAGDeltaAlgorithm</a> &amp; DDA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="#a8d053db58c92b4617a06ef3f9a93d339">edge_ty</a> &gt; &amp; Dependencies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### GetTestResult() {#a724e29e318b7650573fd5c40744ed1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DAGDeltaAlgorithmImpl::GetTestResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a> &amp; Required)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetTestResult - Get the test result for the active set <span class="doxyComputerOutput">Changes</span> with <span class="doxyComputerOutput">Required</span> changes from the cache, executing the test if necessary.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Changes</td>
<td class="doxyParamItemDescription"><p>- The set of active changes being minimized, which should have their pred closure included in the test.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Required</td>
<td class="doxyParamItemDescription"><p>- The set of changes which have previously been established to be required.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The test result.</p></dd>
</dl>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### Run() {#a16e6564221ac63609404d50bc83eb093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DAGDeltaAlgorithm::changeset_ty DAGDeltaAlgorithmImpl::Run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>


<p>References <a href="#a0257793bd56ff42d04a2dfbb40285eb4">DeltaActiveSetHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ExecuteOneTest() {#a5ebee41fc1753d11c1163726ef7a04c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::ExecuteOneTest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a> &amp; S)</td>
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

<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### pred\_begin() {#a02b197c0c06cdc04305effde302119d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::pred_begin (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### pred\_closure\_begin() {#af4be1cc07b67a65ded3313c37393b5ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_closure_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::pred_closure_begin (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### pred\_closure\_end() {#a3401f181da987d56bac9eb56c9330ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_closure_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::pred_closure_end (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### pred\_end() {#a1fd843bd0ae2077065fd0f74143e20d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::pred_end (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### succ\_begin() {#af956317e33b8dc64c7249323ea8ac228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::succ_begin (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### succ\_closure\_begin() {#afd768402b650a4bfc287bcd16d049bce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_closure_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::succ_closure_begin (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### succ\_closure\_end() {#ae930dac3103281694bcb928c90fb4864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_closure_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::succ_closure_end (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### succ\_end() {#afbb196d92064b22826f997c6ee7d1c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_iterator_ty anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::succ_end (<a href="#a17d845c1967f9530c93fc25fe88ab507">change_ty</a> Node)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### UpdatedSearchState() {#a5b62573ee5c6ebac46ce48926a55cce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::UpdatedSearchState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a73fb2fb506247d4d2ef82af67c0e5db6">changesetlist_ty</a> &amp; Sets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a35737e034ee6cffbced3f2b44b91e3e1">changeset_ty</a> &amp; Required)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DDA {#a7119a058426075d13c16ea6b8ed99ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DAGDeltaAlgorithm&amp; anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::DDA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### FailedTestsCache {#a354fd96825d5d9984f4d7a612497f32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;changeset_ty&gt; anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::FailedTestsCache</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache of failed test results.</p>


<p>Successful test results are never cached since we always reduce following a success. We maintain an independent cache from that used by the individual delta passes because we may get hits across multiple individual delta invocations.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### PredClosure {#a5883206cb96ef47c246de4e7ea258a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;change_ty, std::set&lt;change_ty&gt; &gt; anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::PredClosure</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### Predecessors {#adb0fa83d1ddf1c60fe02ef2103a06f63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;change_ty, std::vector&lt;change_ty&gt; &gt; anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::Predecessors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### Roots {#a14b8596958cb24ebde1b849fe0c7e050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;change_ty&gt; anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::Roots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### SuccClosure {#ac5da553be9d7b171d3354e769d477906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;change_ty, std::set&lt;change_ty&gt; &gt; anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::SuccClosure</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### Successors {#a9ba6b229b892c1196f70580fbf052c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;change_ty, std::vector&lt;change_ty&gt; &gt; anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::Successors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
