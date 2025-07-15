---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/globalwithnodeapi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GlobalWithNodeAPI` Class Template Reference

<p>Provides API functions, like <a href="#a6ca3df0dddca4fe048a4bdb535362010">getIterator()</a> and <a href="#ac80dadfb9db2288710b8d145fe27ad84">getReverseIterator()</a> to <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc">GlobalIFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable">GlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias">GlobalAlias</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename GlobalT, typename LLVMGlobalT, typename ParentT, typename LLVMParentT&gt;
class llvm::sandboxir::GlobalWithNodeAPI&lt;GlobalT, LLVMGlobalT, ParentT, LLVMParentT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">llvm/SandboxIR/Constant.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/parentt">ParentT</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afeace33990af9dc8f24656e4e09fc710">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator">mapped_iterator</a>&lt; decltype(static_cast&lt; LLVMGlobalT * &gt;(nullptr) -&gt;<a href="#a6ca3df0dddca4fe048a4bdb535362010">getIterator</a>()), LLVMGVToGV &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75db05e067c94df46015d33e36d271df">reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator">mapped_iterator</a>&lt; decltype(static_cast&lt; LLVMGlobalT * &gt;(nullptr) -&gt;<a href="#ac80dadfb9db2288710b8d145fe27ad84">getReverseIterator</a>()), LLVMGVToGV &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a176352fb8ec7d1282c172015265c2634">GlobalWithNodeAPI</a> (Value::ClassID ID, LLVMParentT *C, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8bcbcefa45fb5dec449326922668aa3">getParent</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#afeace33990af9dc8f24656e4e09fc710">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ca3df0dddca4fe048a4bdb535362010">getIterator</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a75db05e067c94df46015d33e36d271df">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac80dadfb9db2288710b8d145fe27ad84">getReverseIterator</a> () const</td>
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

<p>Provides API functions, like <a href="#a6ca3df0dddca4fe048a4bdb535362010">getIterator()</a> and <a href="#ac80dadfb9db2288710b8d145fe27ad84">getReverseIterator()</a> to <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc">GlobalIFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable">GlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias">GlobalAlias</a>.</p>


<p>In LLVM IR these are provided by <a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a>.</p>


<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#afeace33990af9dc8f24656e4e09fc710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename GlobalT, typename LLVMGlobalT, typename ParentT, typename LLVMParentT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::GlobalWithNodeAPI&lt; GlobalT, LLVMGlobalT, ParentT, LLVMParentT &gt;::iterator =  mapped_iterator&lt;
      decltype(static_cast&lt;LLVMGlobalT *&gt;(nullptr)-&gt;getIterator()), LLVMGVToGV&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>

</div>
</div>

### reverse\_iterator {#a75db05e067c94df46015d33e36d271df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename GlobalT, typename LLVMGlobalT, typename ParentT, typename LLVMParentT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::GlobalWithNodeAPI&lt; GlobalT, LLVMGlobalT, ParentT, LLVMParentT &gt;::reverse_iterator =  mapped_iterator&lt;
      decltype(static_cast&lt;LLVMGlobalT *&gt;(nullptr)-&gt;getReverseIterator()),
      LLVMGVToGV&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GlobalWithNodeAPI() {#a176352fb8ec7d1282c172015265c2634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename GlobalT, typename LLVMGlobalT, typename ParentT, typename LLVMParentT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::GlobalWithNodeAPI&lt; GlobalT, LLVMGlobalT, ParentT, LLVMParentT &gt;::GlobalWithNodeAPI (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#afa2029c46b6caf94a7d05ceb0dbcefe9">Value::ClassID</a> ID, LLVMParentT * C, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIterator() {#a6ca3df0dddca4fe048a4bdb535362010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename GlobalT, typename LLVMGlobalT, typename ParentT, typename LLVMParentT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sandboxir::GlobalWithNodeAPI&lt; GlobalT, LLVMGlobalT, ParentT, LLVMParentT &gt;::getIterator ()</td>
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



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a36f31bfe9e8b65522b0be4bdcec96e83">llvm::map_iterator</a>.</p>

</div>
</div>

### getParent() {#ae8bcbcefa45fb5dec449326922668aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename GlobalT, typename LLVMGlobalT, typename ParentT, typename LLVMParentT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::sandboxir::GlobalWithNodeAPI&lt; GlobalT, LLVMGlobalT, ParentT, LLVMParentT &gt;::getParent ()</td>
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



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>

</div>
</div>

### getReverseIterator() {#ac80dadfb9db2288710b8d145fe27ad84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename GlobalT, typename LLVMGlobalT, typename ParentT, typename LLVMParentT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::sandboxir::GlobalWithNodeAPI&lt; GlobalT, LLVMGlobalT, ParentT, LLVMParentT &gt;::getReverseIterator ()</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a36f31bfe9e8b65522b0be4bdcec96e83">llvm::map_iterator</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
