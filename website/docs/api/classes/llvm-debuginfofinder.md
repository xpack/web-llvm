---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/debuginfofinder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugInfoFinder` Class

<p>Utility to find all debug info in a module. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DebugInfoFinder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b17bf0c0c34de7e67f70df883d50094">compile_unit_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac20326c791e173643ba1bf055a2f1392">subprogram_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35c08cbe913680b77c1f0846efe2300">global_variable_expression_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb4dd412f095da79d37aab952024ddd">type_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc418e585267d5f02747ae44349384e">scope_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217bc3f8a611fdaf301fa67d86994c32">processModule</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> entire module and collect debug info anchors. <a href="#a217bc3f8a611fdaf301fa67d86994c32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5b924e90613450c0c58df4018aeb30">processInstruction</a> (const Module &amp;M, const Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a single instruction and collect debug info anchors. <a href="#a1b5b924e90613450c0c58df4018aeb30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b37e232a1aeab0bcc6e527f8ef97a78">processVariable</a> (const Module &amp;M, const DILocalVariable *DVI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a>. <a href="#a2b37e232a1aeab0bcc6e527f8ef97a78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c6b908ab32d7852c62c49d1be69418">processLocation</a> (const Module &amp;M, const DILocation *Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> debug info location. <a href="#a61c6b908ab32d7852c62c49d1be69418">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed105f22ff3e6ad4f3c80cd96ef7df1f">processDbgRecord</a> (const Module &amp;M, const DbgRecord &amp;DR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> (e.g, treat a <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> like a <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a>). <a href="#aed105f22ff3e6ad4f3c80cd96ef7df1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5327f8310ce89ad7930a1316ddf321e7">processSubprogram</a> (DISubprogram *SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> subprogram. <a href="#a5327f8310ce89ad7930a1316ddf321e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd28190e6cb1a906e346fea09bc620d">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all lists. <a href="#a7cd28190e6cb1a906e346fea09bc620d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a5b17bf0c0c34de7e67f70df883d50094">compile_unit_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c27c3f4b0e09a088b582df980f0238">compile_units</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ac20326c791e173643ba1bf055a2f1392">subprogram_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46cbea3f0c8ddd0ddb33a69a7213a9a">subprograms</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#af35c08cbe913680b77c1f0846efe2300">global_variable_expression_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2dad7176b1cbfd1313807d054421084">global_variables</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#abbb4dd412f095da79d37aab952024ddd">type_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd678837d688e6c676bdba6b8d12a95d">types</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9cc418e585267d5f02747ae44349384e">scope_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde3edd7dcbc3194fc537254331d60e7">scopes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0890d6ee9675019d518dbd90d31c4fa">compile_unit_count</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ec23850277ca5fb5ab8f1832c63226">global_variable_count</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c714a6a51c58a567cde34fbe11cdc11">subprogram_count</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e15b08dc427d7ff01b1476372592e68">type_count</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed220ab3b405e31e4732823f92fc09ff">scope_count</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4b5602d2484e5f418ddffd4401bcb1">processCompileUnit</a> (DICompileUnit *CU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99f0b2a329146c125347b683579e149">processScope</a> (DIScope *Scope)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab313e316cf8f623e73803b76de30cbae">processType</a> (DIType *DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d588d7bb2c4816408564bd42aee32c1">addCompileUnit</a> (DICompileUnit *CU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1cb9eee6bacdcd4a216021c8324cc9">addGlobalVariable</a> (DIGlobalVariableExpression *DIG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207618d5ec42cc9360130456e11ed8a7">addScope</a> (DIScope *Scope)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80064250cd838020747720022045cc66">addSubprogram</a> (DISubprogram *SP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b450b9729e0cf2198e616b6700d5dc3">addType</a> (DIType *DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a0fd6d7752ccf443e8b87c1ff63e11">CUs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd8591c6bb8a81de1017a9b23646e9a">SPs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1769043115f1b32e2fcf10a1e9b9bb41">GVs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b9e3a02b427daf9269154de14c8169">TYs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c22f775d5160862b08f7aa328da9ed">Scopes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02a89fc4a6c60940a4b1f264d5d64eb">NodesSeen</a></td>
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

<p>Utility to find all debug info in a module.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/debuginfofinder">DebugInfoFinder</a> tries to list all debug info MDNodes used in a module. To list debug info MDNodes used by an instruction, <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder">DebugInfoFinder</a> uses processDeclare, processValue and processLocation to handle <a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst">DbgDeclareInst</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> and DbgLoc attached to instructions. processModule will go through all DICompileUnits in llvm.dbg.cu and list debug info MDNodes used by the CUs.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### compile\_unit\_iterator {#a5b17bf0c0c34de7e67f70df883d50094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DebugInfoFinder::compile_unit_iterator = 
      SmallVectorImpl&lt;DICompileUnit *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### global\_variable\_expression\_iterator {#af35c08cbe913680b77c1f0846efe2300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DebugInfoFinder::global_variable_expression_iterator = 
      SmallVectorImpl&lt;DIGlobalVariableExpression *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### scope\_iterator {#a9cc418e585267d5f02747ae44349384e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DebugInfoFinder::scope_iterator =  SmallVectorImpl&lt;DIScope *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### subprogram\_iterator {#ac20326c791e173643ba1bf055a2f1392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DebugInfoFinder::subprogram_iterator =  SmallVectorImpl&lt;DISubprogram *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### type\_iterator {#abbb4dd412f095da79d37aab952024ddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DebugInfoFinder::type_iterator =  SmallVectorImpl&lt;DIType *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compile\_unit\_count() {#ae0890d6ee9675019d518dbd90d31c4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugInfoFinder::compile_unit_count ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### compile\_units() {#ae6c27c3f4b0e09a088b582df980f0238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; compile_unit_iterator &gt; llvm::DebugInfoFinder::compile_units ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b2be839460bb277d4f07f4aa5225ac">llvm::CloneFunctionInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a954c742913f42266852b86ca04547929">llvm::FindDebugInfoToIdentityMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/moduledebuginfoprinter-cpp/#a1a24d20274ad98afd584ab1c1de6cdfb">printModuleDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a>.</p>

</div>
</div>

### global\_variable\_count() {#ab1ec23850277ca5fb5ab8f1832c63226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugInfoFinder::global_variable_count ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### global\_variables() {#ab2dad7176b1cbfd1313807d054421084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; global_variable_expression_iterator &gt; llvm::DebugInfoFinder::global_variables ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/moduledebuginfoprinter-cpp/#a1a24d20274ad98afd584ab1c1de6cdfb">printModuleDebugInfo</a>.</p>

</div>
</div>

### processDbgRecord() {#aed105f22ff3e6ad4f3c80cd96ef7df1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processDbgRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &amp; DR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> (e.g, treat a <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> like a <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a>).</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a4ff1bb484be62f8dac94fc087f72f524">llvm::DebugLoc::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="#a61c6b908ab32d7852c62c49d1be69418">processLocation</a> and <a href="#a2b37e232a1aeab0bcc6e527f8ef97a78">processVariable</a>.</p>


<p>Referenced by <a href="#a1b5b924e90613450c0c58df4018aeb30">processInstruction</a>.</p>

</div>
</div>

### processInstruction() {#a1b5b924e90613450c0c58df4018aeb30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a single instruction and collect debug info anchors.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aed105f22ff3e6ad4f3c80cd96ef7df1f">processDbgRecord</a>, <a href="#a61c6b908ab32d7852c62c49d1be69418">processLocation</a> and <a href="#a2b37e232a1aeab0bcc6e527f8ef97a78">processVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad9d4e85b3abfbf1a3dd8a7fd45057cce">llvm::CollectDebugInfoForCloning</a>, <a href="#a217bc3f8a611fdaf301fa67d86994c32">processModule</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a>.</p>

</div>
</div>

### processLocation() {#a61c6b908ab32d7852c62c49d1be69418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> debug info location.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="#a61c6b908ab32d7852c62c49d1be69418">processLocation</a>.</p>


<p>Referenced by <a href="#aed105f22ff3e6ad4f3c80cd96ef7df1f">processDbgRecord</a>, <a href="#a1b5b924e90613450c0c58df4018aeb30">processInstruction</a> and <a href="#a61c6b908ab32d7852c62c49d1be69418">processLocation</a>.</p>

</div>
</div>

### processModule() {#a217bc3f8a611fdaf301fa67d86994c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> entire module and collect debug info anchors.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a1b5b924e90613450c0c58df4018aeb30">processInstruction</a> and <a href="#a5327f8310ce89ad7930a1316ddf321e7">processSubprogram</a>.</p>

</div>
</div>

### processSubprogram() {#a5327f8310ce89ad7930a1316ddf321e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processSubprogram (<a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> subprogram.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad9d4e85b3abfbf1a3dd8a7fd45057cce">llvm::CollectDebugInfoForCloning</a>, <a href="#a217bc3f8a611fdaf301fa67d86994c32">processModule</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a>.</p>

</div>
</div>

### processVariable() {#a2b37e232a1aeab0bcc6e527f8ef97a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DVI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a>.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a38229438b1c22802074b3181b0b80b85">llvm::DILocalVariable::getScope</a> and <a href="/web-llvm/docs/api/classes/llvm/divariable/#adab9179b79371579b407e31155a32366">llvm::DIVariable::getType</a>.</p>


<p>Referenced by <a href="#aed105f22ff3e6ad4f3c80cd96ef7df1f">processDbgRecord</a> and <a href="#a1b5b924e90613450c0c58df4018aeb30">processInstruction</a>.</p>

</div>
</div>

### reset() {#a7cd28190e6cb1a906e346fea09bc620d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear all lists.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### scope\_count() {#aed220ab3b405e31e4732823f92fc09ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugInfoFinder::scope_count ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### scopes() {#acde3edd7dcbc3194fc537254331d60e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; scope_iterator &gt; llvm::DebugInfoFinder::scopes ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a954c742913f42266852b86ca04547929">llvm::FindDebugInfoToIdentityMap</a>.</p>

</div>
</div>

### subprogram\_count() {#a1c714a6a51c58a567cde34fbe11cdc11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugInfoFinder::subprogram_count ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a954c742913f42266852b86ca04547929">llvm::FindDebugInfoToIdentityMap</a>.</p>

</div>
</div>

### subprograms() {#ab46cbea3f0c8ddd0ddb33a69a7213a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; subprogram_iterator &gt; llvm::DebugInfoFinder::subprograms ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a954c742913f42266852b86ca04547929">llvm::FindDebugInfoToIdentityMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/moduledebuginfoprinter-cpp/#a1a24d20274ad98afd584ab1c1de6cdfb">printModuleDebugInfo</a>.</p>

</div>
</div>

### type\_count() {#a3e15b08dc427d7ff01b1476372592e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugInfoFinder::type_count ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### types() {#acd678837d688e6c676bdba6b8d12a95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; type_iterator &gt; llvm::DebugInfoFinder::types ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a954c742913f42266852b86ca04547929">llvm::FindDebugInfoToIdentityMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/moduledebuginfoprinter-cpp/#a1a24d20274ad98afd584ab1c1de6cdfb">printModuleDebugInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addCompileUnit() {#a0d588d7bb2c4816408564bd42aee32c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugInfoFinder::addCompileUnit (<a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### addGlobalVariable() {#afb1cb9eee6bacdcd4a216021c8324cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugInfoFinder::addGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> * DIG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### addScope() {#a207618d5ec42cc9360130456e11ed8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugInfoFinder::addScope (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### addSubprogram() {#a80064250cd838020747720022045cc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugInfoFinder::addSubprogram (<a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### addType() {#a0b450b9729e0cf2198e616b6700d5dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugInfoFinder::addType (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### processCompileUnit() {#a2c4b5602d2484e5f418ddffd4401bcb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processCompileUnit (<a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### processScope() {#ad99f0b2a329146c125347b683579e149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processScope (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### processType() {#ab313e316cf8f623e73803b76de30cbae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugInfoFinder::processType (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CUs {#af6a0fd6d7752ccf443e8b87c1ff63e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DICompileUnit *, 8&gt; llvm::DebugInfoFinder::CUs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### GVs {#a1769043115f1b32e2fcf10a1e9b9bb41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DIGlobalVariableExpression *, 8&gt; llvm::DebugInfoFinder::GVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### NodesSeen {#aa02a89fc4a6c60940a4b1f264d5d64eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const MDNode *, 32&gt; llvm::DebugInfoFinder::NodesSeen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### Scopes {#ac2c22f775d5160862b08f7aa328da9ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DIScope *, 8&gt; llvm::DebugInfoFinder::Scopes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### SPs {#a6dd8591c6bb8a81de1017a9b23646e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DISubprogram *, 8&gt; llvm::DebugInfoFinder::SPs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### TYs {#ab3b9e3a02b427daf9269154de14c8169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DIType *, 8&gt; llvm::DebugInfoFinder::TYs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
