---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/threadsafemodule
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ThreadSafeModule` Class Reference

<p>An LLVM <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> together with a shared <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ThreadSafeModule { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">llvm/ExecutionEngine/Orc/ThreadSafeModule.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5238e1d80536030a7ddd0a00e18c7371">ThreadSafeModule</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default construct a <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a>. <a href="#a5238e1d80536030a7ddd0a00e18c7371">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8aab03373a96cc61ae3da687bd73eb">ThreadSafeModule</a> (ThreadSafeModule &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59b16a2ba2778523a92d88a10d000e9d">ThreadSafeModule</a> (std::unique_ptr&lt; Module &gt; M, std::unique_ptr&lt; LLVMContext &gt; Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> from a unique_ptr&lt;Module&gt; and a unique_ptr&lt;LLVMContext&gt;. <a href="#a59b16a2ba2778523a92d88a10d000e9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad76bc6379e9faa0a0b2e360817bbc37">ThreadSafeModule</a> (std::unique_ptr&lt; Module &gt; M, ThreadSafeContext TSCtx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> from a unique_ptr&lt;Module&gt; and an existing <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a>. <a href="#aad76bc6379e9faa0a0b2e360817bbc37">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39fded867bd4a9aa23197880a2523bdb">~ThreadSafeModule</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bba70015bd06fc62083890136957dda">operator=</a> (ThreadSafeModule &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad047604d783d265d6f5a5cfc3f0345e3">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> conversion: This <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> will evaluate to true if it wraps a non-null module. <a href="#ad047604d783d265d6f5a5cfc3f0345e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5dc53e9bbda9066a1ade839494fe0cd9">withModuleDo</a> (Func &amp;&amp;F) -&gt; decltype(auto)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Locks the associated <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> and calls the given function on the contained <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#a5dc53e9bbda9066a1ade839494fe0cd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa62be2ea900c7dbd8c0d45af767142c5">withModuleDo</a> (Func &amp;&amp;F) const -&gt; decltype(auto)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Locks the associated <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> and calls the given function on the contained <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#aa62be2ea900c7dbd8c0d45af767142c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f1e21cac5addd85d48c5e4819d31df7">consumingModuleDo</a> (Func &amp;&amp;F) -&gt; decltype(auto)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Locks the associated <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> and calls the given function, passing the contained std::unique_ptr&lt;Module&gt;. <a href="#a0f1e21cac5addd85d48c5e4819d31df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58bcc80e93468f93bcb88913975c9d14">getModuleUnlocked</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a raw pointer to the contained module without locking the context. <a href="#a58bcc80e93468f93bcb88913975c9d14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9654d98cd18ba8401ea64b4b082b4fe">getModuleUnlocked</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a raw pointer to the contained module without locking the context. <a href="#ab9654d98cd18ba8401ea64b4b082b4fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005c94184fdf73cdac56be7b8f17fc12">getContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the context for this <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a>. <a href="#a005c94184fdf73cdac56be7b8f17fc12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87a495772936fa46bfb2d96682c4637">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f9c1e22fc674fd824ccb312c29fcd0b">TSCtx</a></td>
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

<p>An LLVM <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> together with a shared <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a>.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThreadSafeModule() {#a5238e1d80536030a7ddd0a00e18c7371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ThreadSafeModule::ThreadSafeModule ()</td>
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

<p>Default construct a <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a>.</p>


<p>This results in a null module and null context.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>Referenced by <a href="#a1bba70015bd06fc62083890136957dda">operator=</a> and <a href="#a7e8aab03373a96cc61ae3da687bd73eb">ThreadSafeModule</a>.</p>

</div>
</div>

### ThreadSafeModule() {#a7e8aab03373a96cc61ae3da687bd73eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ThreadSafeModule::ThreadSafeModule (<a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp;&amp; Other)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a5238e1d80536030a7ddd0a00e18c7371">ThreadSafeModule</a>.</p>

</div>
</div>

### ThreadSafeModule() {#a59b16a2ba2778523a92d88a10d000e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ThreadSafeModule::ThreadSafeModule (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &gt; Ctx)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> from a unique_ptr&lt;Module&gt; and a unique_ptr&lt;LLVMContext&gt;.</p>


<p>This creates a new <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> from the given context.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### ThreadSafeModule() {#aad76bc6379e9faa0a0b2e360817bbc37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ThreadSafeModule::ThreadSafeModule (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> TSCtx)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> from a unique_ptr&lt;Module&gt; and an existing <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a>.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ThreadSafeModule() {#a39fded867bd4a9aa23197880a2523bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ThreadSafeModule::~ThreadSafeModule ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#ad047604d783d265d6f5a5cfc3f0345e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ThreadSafeModule::operator bool ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> conversion: This <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> will evaluate to true if it wraps a non-null module.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator=() {#a1bba70015bd06fc62083890136957dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeModule &amp; llvm::orc::ThreadSafeModule::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp;&amp; Other)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a5238e1d80536030a7ddd0a00e18c7371">ThreadSafeModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### consumingModuleDo() {#a0f1e21cac5addd85d48c5e4819d31df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(auto) llvm::orc::ThreadSafeModule::consumingModuleDo (Func &amp;&amp; F)</td>
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

<p>Locks the associated <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> and calls the given function, passing the contained std::unique_ptr&lt;Module&gt;.</p>


<p>The given function should consume the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getContext() {#a005c94184fdf73cdac56be7b8f17fc12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeContext llvm::orc::ThreadSafeModule::getContext ()</td>
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

<p>Returns the context for this <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a>.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>.</p>

</div>
</div>

### getModuleUnlocked() {#a58bcc80e93468f93bcb88913975c9d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::orc::ThreadSafeModule::getModuleUnlocked ()</td>
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

<p>Get a raw pointer to the contained module without locking the context.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>.</p>

</div>
</div>

### getModuleUnlocked() {#ab9654d98cd18ba8401ea64b4b082b4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * llvm::orc::ThreadSafeModule::getModuleUnlocked ()</td>
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

<p>Get a raw pointer to the contained module without locking the context.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>

</div>
</div>

### withModuleDo() {#a5dc53e9bbda9066a1ade839494fe0cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(auto) llvm::orc::ThreadSafeModule::withModuleDo (Func &amp;&amp; F)</td>
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

<p>Locks the associated <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> and calls the given function on the contained <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#ae80aa20118c3b2a9fe857c47dd576d44">llvm::orc::LLJIT::addIRModule</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjit/#afa6fca2ea17d5c43653424337abc473a">llvm::orc::LLLazyJIT::addLazyIRModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#acb572d27661acd51c80b1bca18cd1ee3">llvm::orc::cloneToNewContext</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer/#a176fd0ce1f0e28e675e04c05c7716a03">llvm::orc::IRCompileLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer/#a422aebce39fe92265115190c32de1312">llvm::orc::IRPartitionLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#aa1d94843d12c81b1eda3d646bb2ab38e">llvm::orc::ReOptimizeLayer::reoptimizeIfCallFrequent</a>.</p>

</div>
</div>

### withModuleDo() {#aa62be2ea900c7dbd8c0d45af767142c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(auto) llvm::orc::ThreadSafeModule::withModuleDo (Func &amp;&amp; F)</td>
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

<p>Locks the associated <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> and calls the given function on the contained <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### M {#ad87a495772936fa46bfb2d96682c4637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Module&gt; llvm::orc::ThreadSafeModule::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>

</div>
</div>

### TSCtx {#a7f9c1e22fc674fd824ccb312c29fcd0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeContext llvm::orc::ThreadSafeModule::TSCtx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/threadsafemodule-h">ThreadSafeModule.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
