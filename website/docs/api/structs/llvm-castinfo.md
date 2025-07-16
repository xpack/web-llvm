---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/castinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CastInfo` Struct Template Reference

<p>This struct provides a method for customizing the way a cast is performed. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename To, typename From, typename Enable = void&gt;
struct llvm::CastInfo&lt;To, From, Enable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/castispossible">CastIsPossible&lt;To, From, Enable&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This struct provides a way to check if a given cast is possible. <a href="/web-llvm/docs/api/structs/llvm/castispossible/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename From, typename Enable = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a694f5e7233cf55082a0ac75f3e0eabaf">Self</a> = <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo</a>&lt; To, From, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">Enable</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename From, typename Enable = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93bebb67e4960a08613dff9ecc05962c">CastReturnType</a> = typename <a href="/web-llvm/docs/api/structs/llvm/cast-retty">cast_retty</a>&lt; To, From &gt;::ret_type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename From, typename Enable = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#a93bebb67e4960a08613dff9ecc05962c">CastReturnType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a143f6f757917e1245aed3882209b466f">doCast</a> (const From &amp;f)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename From, typename Enable = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#a93bebb67e4960a08613dff9ecc05962c">CastReturnType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09597b5e97eabe6d1cc60e6846a989a3">castFailed</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename From, typename Enable = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#a93bebb67e4960a08613dff9ecc05962c">CastReturnType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83d4b9f9263ad371a544f013ec863569">doCastIfPossible</a> (const From &amp;f)</td>
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

<p>This struct provides a method for customizing the way a cast is performed.</p>


<p>It inherits from <a href="/web-llvm/docs/api/structs/llvm/castispossible">CastIsPossible</a>, to support the case of declaring many <a href="/web-llvm/docs/api/structs/llvm/castispossible">CastIsPossible</a> specializations without having to specialize the full <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo</a>.</p>


<p>In order to specialize different behaviors, specify different functions in your <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo</a> specialization. For isa&lt;&gt; customization, provide:</p>


<p><span class="doxyComputerOutput">static bool isPossible(const From &amp;f)</span></p>


<p>For cast&lt;&gt; customization, provide:</p>


<p><span class="doxyComputerOutput">static To doCast(const From &amp;f)</span></p>


<p>For dyn_cast&lt;&gt; and the *_if_present&lt;&gt; variants' customization, provide:</p>


<p><span class="doxyComputerOutput">static To <a href="#a09597b5e97eabe6d1cc60e6846a989a3">castFailed()</a></span> and <span class="doxyComputerOutput">static To doCastIfPossible(const From &amp;f)</span></p>


<p>Your specialization might look something like this:</p>


<p>template&lt;&gt; struct <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo&lt;foo, bar&gt;</a> : public <a href="/web-llvm/docs/api/structs/llvm/castispossible">CastIsPossible&lt;foo, bar&gt;</a> { static inline foo doCast(const bar &amp;b) { return foo(const_cast&lt;bar &amp;&gt;(b)); } static inline foo <a href="#a09597b5e97eabe6d1cc60e6846a989a3">castFailed()</a> { return foo(); } static inline foo doCastIfPossible(const bar &amp;b) { if (!CastInfo&lt;foo, bar&gt;::isPossible(b)) return <a href="#a09597b5e97eabe6d1cc60e6846a989a3">castFailed()</a>; return doCast(b); } };</p>


<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CastReturnType {#a93bebb67e4960a08613dff9ecc05962c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename From, typename Enable = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CastInfo&lt; To, From, Enable &gt;::CastReturnType =  typename cast_retty&lt;To, From&gt;::ret_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>

</div>
</div>

### Self {#a694f5e7233cf55082a0ac75f3e0eabaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename From, typename Enable = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CastInfo&lt; To, From, Enable &gt;::Self =  CastInfo&lt;To, From, Enable&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### castFailed() {#a09597b5e97eabe6d1cc60e6846a989a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename From, typename Enable = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastReturnType llvm::CastInfo&lt; To, From, Enable &gt;::castFailed ()</td>
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



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a07be078de4a2c223bd6a76e24e1c02db">llvm::cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9ad4a13c0360e7657d58950ae715f9f">llvm::cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96c961b742155c537f12aa6440958348">llvm::cast_if_present</a>, <a href="#a83d4b9f9263ad371a544f013ec863569">llvm::CastInfo&lt; To, From, Enable &gt;::doCastIfPossible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afeb383c24b48a2c5083b8dd22a9d01e2">llvm::dyn_cast_if_present</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87bf481e3b73da3f12ef845a67b9a17c">llvm::dyn_cast_if_present</a>.</p>

</div>
</div>

### doCast() {#a143f6f757917e1245aed3882209b466f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename From, typename Enable = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastReturnType llvm::CastInfo&lt; To, From, Enable &gt;::doCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> From &amp; f)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71bd44e15e7fa8caf63e9b36753d1d24">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a288423633bcc517f32d43c6670b4f6f3">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/castinfo-db4f59cb616dd1b49786c906cf5bbd9b/#abd426648e3e22b14d4cc95d354e3b1aa">llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt; &gt;::doCast</a> and <a href="#a83d4b9f9263ad371a544f013ec863569">llvm::CastInfo&lt; To, From, Enable &gt;::doCastIfPossible</a>.</p>

</div>
</div>

### doCastIfPossible() {#a83d4b9f9263ad371a544f013ec863569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename From, typename Enable = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastReturnType llvm::CastInfo&lt; To, From, Enable &gt;::doCastIfPossible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> From &amp; f)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519aad1dd3d14fdde393b577eb07d497">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af346f4a9e03423c2dc8e812fd9e0e229">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afeb383c24b48a2c5083b8dd22a9d01e2">llvm::dyn_cast_if_present</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87bf481e3b73da3f12ef845a67b9a17c">llvm::dyn_cast_if_present</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
