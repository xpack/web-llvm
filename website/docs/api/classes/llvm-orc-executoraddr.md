---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/executoraddr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ExecutorAddr` Class

<p>Represents an address in the executor process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ExecutorAddr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">llvm/ExecutionEngine/Orc/Shared/ExecutorAddress.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08c5e1385c9dbeb93ed92f693ff6eb6c">rawPtr</a> = <a href="/web-llvm/docs/api/structs/llvm/identity">llvm::identity</a>&lt; T * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrap/unwrap function that leaves pointers unmodified. <a href="#a08c5e1385c9dbeb93ed92f693ff6eb6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28b93ed546fe33e59ebe11a0d12e5de3">defaultWrap</a> = <a href="#a08c5e1385c9dbeb93ed92f693ff6eb6c">rawPtr</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default wrap function to use on this host. <a href="#a28b93ed546fe33e59ebe11a0d12e5de3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af035df00937f8e06a93bec7468dd124c">defaultUnwrap</a> = <a href="#a08c5e1385c9dbeb93ed92f693ff6eb6c">rawPtr</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default unwrap function to use on this host. <a href="#af035df00937f8e06a93bec7468dd124c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a1afbe7c379378f3b16cb93997f3ae">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f70bd6c87e4898715792b31b70abcf">operator!=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7911c5530d17010ffe2fb162b57bf1e">operator&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad1720b996e49206f0a9f31d944485ba">operator&lt;=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876db71ca04f15442e02acfc0a542eb6">operator&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93181f4fcf2d0bb5270822fab3bcf464">operator&gt;=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982e9c72bd028ab6758fe5f5c72bbf38">ExecutorAddr</a> (uint64_t Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> from the given value. <a href="#a982e9c72bd028ab6758fe5f5c72bbf38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b9146227646207a138c6d0dda12b5d">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9165f6b1fd5bbaedd8fe5a9d368855">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942d040a8ecfd173f45860874c58365d">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f63225f588de33ff1f40cce9a51e5d6">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430aa3e2bf458dd041cf0670dc5fce74">operator--</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9c297934ef332a5ab2884b3db9c476">operator+=</a> (const ExecutorAddrDiff &amp;Delta)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44dca1baa190dc4957cba6957e76aa26">operator-=</a> (const ExecutorAddrDiff &amp;Delta)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5df5d5fa49d180d3ca3de567f60de79">toPtr</a> (WrapFn &amp;&amp;Wrap=WrapFn()) const -&gt; std::enable_if_t&lt; std::is_pointer&lt; T &gt;::value, T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> to a pointer of the given type. <a href="#af5df5d5fa49d180d3ca3de567f60de79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename WrapFn = defaultWrap&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a60f74e5a67f055b8e04b9a553a88d28f">toPtr</a> (WrapFn &amp;&amp;Wrap=WrapFn()) const -&gt; std::enable_if_t&lt; std::is_function&lt; T &gt;::value, T * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> to a pointer of the given function type. <a href="#a60f74e5a67f055b8e04b9a553a88d28f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee908fb9052f020e3c50e3f1a7d81c5">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515ee8bc22e39503d6d5af160be64f26">setValue</a> (uint64_t Addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66da62fbedcae290389c622ed09b0d55">isNull</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87978ddee8422f2208ce402ee5262989">Addr</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename UnwrapFn = defaultUnwrap&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8adb0ae35f7e95c960c86cfe19bc7215">fromPtr</a> (T *Ptr, UnwrapFn &amp;&amp;Unwrap=UnwrapFn())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> from the given pointer. <a href="#a8adb0ae35f7e95c960c86cfe19bc7215">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents an address in the executor process.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### defaultUnwrap {#af035df00937f8e06a93bec7468dd124c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutorAddr::defaultUnwrap =  rawPtr&lt;T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default unwrap function to use on this host.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

### defaultWrap {#a28b93ed546fe33e59ebe11a0d12e5de3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutorAddr::defaultWrap =  rawPtr&lt;T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default wrap function to use on this host.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

### rawPtr {#a08c5e1385c9dbeb93ed92f693ff6eb6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutorAddr::rawPtr =  llvm::identity&lt;T *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A wrap/unwrap function that leaves pointers unmodified.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator!= {#af2f70bd6c87e4898715792b31b70abcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; RHS</td>
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


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt; {#ab7911c5530d17010ffe2fb162b57bf1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; RHS</td>
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


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;= {#aad1720b996e49206f0a9f31d944485ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; RHS</td>
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


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator== {#a40a1afbe7c379378f3b16cb93997f3ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; RHS</td>
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


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt; {#a876db71ca04f15442e02acfc0a542eb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; RHS</td>
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


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;= {#a93181f4fcf2d0bb5270822fab3bcf464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp; RHS</td>
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


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExecutorAddr() {#addee789ebf3b73c88bfe5fba256042cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorAddr::ExecutorAddr ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Referenced by <a href="#a8adb0ae35f7e95c960c86cfe19bc7215">fromPtr</a>, <a href="#af2f70bd6c87e4898715792b31b70abcf">operator!=</a>, <a href="#a2d9165f6b1fd5bbaedd8fe5a9d368855">operator++</a>, <a href="#a6f63225f588de33ff1f40cce9a51e5d6">operator++</a>, <a href="#abb9c297934ef332a5ab2884b3db9c476">operator+=</a>, <a href="#a942d040a8ecfd173f45860874c58365d">operator--</a>, <a href="#a430aa3e2bf458dd041cf0670dc5fce74">operator--</a>, <a href="#a44dca1baa190dc4957cba6957e76aa26">operator-=</a>, <a href="#ab7911c5530d17010ffe2fb162b57bf1e">operator&lt;</a>, <a href="#aad1720b996e49206f0a9f31d944485ba">operator&lt;=</a>, <a href="#a40a1afbe7c379378f3b16cb93997f3ae">operator==</a>, <a href="#a876db71ca04f15442e02acfc0a542eb6">operator&gt;</a> and <a href="#a93181f4fcf2d0bb5270822fab3bcf464">operator&gt;=</a>.</p>

</div>
</div>

### ExecutorAddr() {#a982e9c72bd028ab6758fe5f5c72bbf38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorAddr::ExecutorAddr (uint64_t Addr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> from the given value.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a47b9146227646207a138c6d0dda12b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorAddr::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

### operator--() {#a942d040a8ecfd173f45860874c58365d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr &amp; llvm::orc::ExecutorAddr::operator-- ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Reference <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>.</p>

</div>
</div>

### operator--() {#a430aa3e2bf458dd041cf0670dc5fce74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::ExecutorAddr::operator-- (int)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Reference <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>.</p>

</div>
</div>

### operator-=() {#a44dca1baa190dc4957cba6957e76aa26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr &amp; llvm::orc::ExecutorAddr::operator-= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">ExecutorAddrDiff</a> &amp; Delta)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Reference <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>.</p>

</div>
</div>

### operator++() {#a2d9165f6b1fd5bbaedd8fe5a9d368855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr &amp; llvm::orc::ExecutorAddr::operator++ ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Reference <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>.</p>

</div>
</div>

### operator++() {#a6f63225f588de33ff1f40cce9a51e5d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::ExecutorAddr::operator++ (int)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Reference <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>.</p>

</div>
</div>

### operator+=() {#abb9c297934ef332a5ab2884b3db9c476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr &amp; llvm::orc::ExecutorAddr::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">ExecutorAddrDiff</a> &amp; Delta)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Reference <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getValue() {#a4ee908fb9052f020e3c50e3f1a7d81c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::ExecutorAddr::getValue ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4ef363a05894432d81f30df1ada8ae51">llvm::jitlink::alignToBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a61310b6c90769dc38a55a4b84b1cc054">llvm::jitlink::aarch64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a5a393f897c1439c03e7ef35e7874a8a1">llvm::jitlink::ppc64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a53f135c84cfb135c8e3f890659a3f782">llvm::jitlink::aarch32::applyFixupArm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a183363f7e8482b2c1e193956dea835ee">llvm::jitlink::aarch32::applyFixupThumb</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a21d1557ff7212b52d2935836c8619919">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::completeSynthesisAndRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/simplesegmentalloc/#afd606b508cfbab129894d4b176cad942">llvm::jitlink::SimpleSegmentAlloc::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a78f018d0c5133b2d60d092d68f6b046b">llvm::orc::createIRTypedAddress</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a16f7e0099c6134ab100f80300b710e41">anonymous{PerfSupportPlugin.cpp}::createX64EHFrameHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/namespaces/llvmorclazycallthroughmanagerref/#a25ef4ea37fd470785124fe531d34dd08">LLVMOrcLazyCallThroughManagerRef::fromExecutorSymbolDef</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a38f6a722ee6303b849007724d9da2bb/#a568b12cdf09ec965eda751542a13fdf2">llvm::DenseMapInfo&lt; orc::ExecutorAddr &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-linkgraphlinkinglayer-cpp-/#ad7ab6c07e2f58775b2e014b2951243d7">anonymous{LinkGraphLinkingLayer.cpp}::getJITSymbolPtrForSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#ac61404d428edea90fb2c5b180daf5361">llvm::jitlink::x86_64::optimizeGOTAndStubAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7c663d3ebf566f53b426b05f6555c600/#a840a9a1b2bb7c91a6e4b9c97238a4f90">llvm::orc::shared::SPSSerializationTraits&lt; SPSExecutorAddr, ExecutorAddr &gt;::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7c663d3ebf566f53b426b05f6555c600/#aba3260fb694456474e1bdcbc5d2f13b7">llvm::orc::shared::SPSSerializationTraits&lt; SPSExecutorAddr, ExecutorAddr &gt;::size</a>, <a href="/web-llvm/docs/api/classes/anonymous-epcindirectionutils-cpp-/epcindirectstubsmanager/#a6bac8d07501a16b2f372dea7bb937675">anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::updatePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsmanager/#acb10fef5b99a6616761ba72b5ec033f1">llvm::orc::LocalIndirectStubsManager&lt; TargetT &gt;::updatePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orci386/#a68f02ee05b509d13a5bbe46ebfe1b191">llvm::orc::OrcI386::writeIndirectStubsBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orcmips32-base/#a291426ba8ac5302b2b4d3bd5c7fddb45">llvm::orc::OrcMips32_Base::writeIndirectStubsBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orcmips64/#a17decd16b501f862acabcdade2f93e61">llvm::orc::OrcMips64::writeIndirectStubsBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orci386/#a4a68e05a19cbcde386e875324cbd0839">llvm::orc::OrcI386::writeResolverCode</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orcmips32-base/#a1fba981beeb5b1d76145fd235d0cc391">llvm::orc::OrcMips32_Base::writeResolverCode</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orcmips64/#ac7613ff82688f9ffd9bceed5302d2023">llvm::orc::OrcMips64::writeResolverCode</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orci386/#a587f5cd2b4c2ec04a580205a00480a3d">llvm::orc::OrcI386::writeTrampolines</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orcmips32-base/#ac172b43b00334f657534d4454952ed4d">llvm::orc::OrcMips32_Base::writeTrampolines</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/orcmips64/#aba3177c569c4f3396b4677236ae84447">llvm::orc::OrcMips64::writeTrampolines</a>.</p>

</div>
</div>

### isNull() {#a66da62fbedcae290389c622ed09b0d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::ExecutorAddr::isNull ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

### setValue() {#a515ee8bc22e39503d6d5af160be64f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutorAddr::setValue (uint64_t Addr)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc/#a555b4d547e388b770585087dc398b667">llvm::jitlink::JITLinkMemoryManager::FinalizedAlloc::release</a>.</p>

</div>
</div>

### toPtr() {#af5df5d5fa49d180d3ca3de567f60de79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename WrapFn = defaultWrap&lt;std::remove_pointer_t&lt;T&gt;&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_pointer&lt; T &gt;::value, T &gt; llvm::orc::ExecutorAddr::toPtr (WrapFn &amp;&amp; Wrap=WrapFn())</td>
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

<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> to a pointer of the given type.</p>


<p>Warning: This should only be used when JITing in-process.</p>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ab3e5050d43a1deb05a2878c74eb99abd">llvm::orc::SelfExecutorProcessControl::callWrapperAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessehframeregistrar/#a68566ad4088e1e9c966c4ed85fcd92d0">llvm::jitlink::InProcessEHFrameRegistrar::deregisterEHFrames</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/registerehframes-cpp/#a9b551a3462e625ef17a28d319f5f8552">deregisterEHFrameWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a492e4d6b2bf660e7c499e22f85b72440">llvm::orc::InProcessMemoryMapper::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/methodwrapperhandler/#a70ffbc1ac2af66528c7830838143d78e">llvm::orc::shared::MethodWrapperHandler&lt; RetT, ClassT, ArgTs &gt;::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#ad56d2316a6611ee7bf8958565aee64a2">llvm::orc::InProcessMemoryMapper::prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessehframeregistrar/#a3dcccb2fcb683beab5ac825632b53438">llvm::jitlink::InProcessEHFrameRegistrar::registerEHFrames</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/registerehframes-cpp/#af85e4f75c575f657d41b360041c1fee7">registerEHFrameWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#afccfa89bd18bf4723d4176fdcdc700e9">llvm::orc::SelfExecutorProcessControl::runAsIntFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#afd6eab68573896815e1b7e3fbb7554d0">llvm::orc::rt_bootstrap::runAsIntFunctionWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#aac95e98c378e0095b769073c8f459e21">llvm::orc::SelfExecutorProcessControl::runAsMain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#aa426d973cb19ceb73313af9043a0f3f7">llvm::orc::rt_bootstrap::runAsMainWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a95d2cbff7443f6cf07d3c3e8f4198b37">llvm::orc::SelfExecutorProcessControl::runAsVoidFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a3fd747bb0dc9d8e1ad63288b1b6a604b">llvm::orc::rt_bootstrap::runAsVoidFunctionWrapper</a>.</p>

</div>
</div>

### toPtr() {#a60f74e5a67f055b8e04b9a553a88d28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename WrapFn = defaultWrap&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_function&lt; T &gt;::value, T * &gt; llvm::orc::ExecutorAddr::toPtr (WrapFn &amp;&amp; Wrap=WrapFn())</td>
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

<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> to a pointer of the given function type.</p>


<p>Warning: This should only be used when JITing in-process.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Addr {#a87978ddee8422f2208ce402ee5262989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::ExecutorAddr::Addr = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromPtr() {#a8adb0ae35f7e95c960c86cfe19bc7215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename UnwrapFn = defaultUnwrap&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::ExecutorAddr::fromPtr (T * Ptr, UnwrapFn &amp;&amp; Unwrap=UnwrapFn())</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> from the given pointer.</p>


<p>Warning: This should only be used when JITing in-process.</p>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>


<p>References <a href="#addee789ebf3b73c88bfe5fba256042cb">ExecutorAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a30b2bf2d887d64fbcbd360accb5ed8a1">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::addBootstrapSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#adecf4516866175cd6afadcb25ba6e888">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::addBootstrapSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#ae8c4ce91d8e4f8891a7b0b4aa07dc301">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::addBootstrapSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#a6cfb7c36eddb6eeab4a0dbece2b7f21c">llvm::orc::UnwindInfoManager::addBootstrapSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2eb4c57e962ea964e0917f7dee774c93">llvm::orc::addDefaultBootstrapValuesForHostProcess</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/speculator/#aa6a0f8e9226177178d049976fd7394be">llvm::orc::Speculator::addSpeculationRuntime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/#a9f8e852fe43d6fd7d73092c820f89981">llvm::jitlink::InProcessMemoryManager::allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a71f5d58b4df8b116ebda816fd6b29a61">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsinfo/#ae74fd50627af3f80c098c4d8737c846d">llvm::orc::LocalIndirectStubsInfo&lt; ORCABI &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localcxxruntimeoverrides/#a64281bb2737cb8f10abe3b3ec40d23c4">llvm::orc::LocalCXXRuntimeOverrides::enable</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsmanager/#a14ffb0b8e15fb3b4e1cc3323d62792c3">llvm::orc::LocalIndirectStubsManager&lt; TargetT &gt;::findPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsmanager/#adc40cb67cc5445496ae9cd71dc3ec05b">llvm::orc::LocalIndirectStubsManager&lt; TargetT &gt;::findStub</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef/#a4027523e233ec73fad998066e26ffc71">llvm::orc::ExecutorSymbolDef::fromPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#add2269e99095cafef133d663ab4a3688">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::GenericLLVMIRPlatformSupport</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#a102ac250c000b2204564f9d315807ead">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#a89babf245d443732b10c16ced7ca9c08">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::open</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a7567e026468fa261fb6186a2d30115ff">llvm::orc::InProcessMemoryMapper::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#aded6fc2ddd0d73f2f6b24beff42b70ea">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad5f773f31c1e2529e6dca4686a3b968e">llvm::orc::setUpInProcessLCTMReentryViaEPCIU</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#af35944202db51be01b3c6330c976f3a3">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::shutdown</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator/#a6f48283edeff2b9dfa266043c7229d2f">llvm::orc::DynamicLibrarySearchGenerator::tryToGenerate</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a9a8a5be08a1b215a7da11ae9d55ad31b">llvm::orc::InProcessMemoryMapper::~InProcessMemoryMapper</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
