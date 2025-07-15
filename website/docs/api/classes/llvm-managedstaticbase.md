---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/managedstaticbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ManagedStaticBase` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/managedstaticbase">ManagedStaticBase</a> - Common base class for <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a> instances. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ManagedStaticBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">llvm/Support/ManagedStatic.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic&lt;C, Creator, Deleter&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a> - This transparently changes the behavior of global statics to be lazily constructed on demand (good for reducing startup times of dynamic libraries that link in LLVM components) and for making destruction be explicit through the <a href="/web-llvm/docs/api/namespaces/llvm/#ac27f7fe6f1543ef516aa0998bad20335">llvm_shutdown()</a> function call. <a href="/web-llvm/docs/api/classes/llvm/managedstatic/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8cb3305a149ad3cfe1d526bd7cf5de">ManagedStaticBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad5f1491a2600048898c0e4429b834da">isConstructed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isConstructed - Return true if this object has not been created yet. <a href="#aad5f1491a2600048898c0e4429b834da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73eaf69bd83e867f9ad27fc7251b79c">destroy</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0455c2e6ef911ce3116fceb21d68c44c">RegisterManagedStatic</a> (void *(*creator)(), void(*deleter)(void *)) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; void * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50919239317978cb5ea4ffb91f753918">Ptr</a> {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d05e80d2397311d8d748484768dd537">DeleterFn</a>)(void *) = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/managedstaticbase">ManagedStaticBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7c1cf0ea51e0bef7f9f6714af3ce51">Next</a> = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/managedstaticbase">ManagedStaticBase</a> - Common base class for <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a> instances.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ManagedStaticBase() {#a1e8cb3305a149ad3cfe1d526bd7cf5de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ManagedStaticBase::ManagedStaticBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### destroy() {#ac73eaf69bd83e867f9ad27fc7251b79c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManagedStaticBase::destroy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp">ManagedStatic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2d05e80d2397311d8d748484768dd537">DeleterFn</a>, <a href="#a2e7c1cf0ea51e0bef7f9f6714af3ce51">Next</a>, <a href="#a50919239317978cb5ea4ffb91f753918">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp/#a2b09c6b05b45efd4853fa743e908d9b1">StaticList</a>.</p>

</div>
</div>

### isConstructed() {#aad5f1491a2600048898c0e4429b834da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ManagedStaticBase::isConstructed ()</td>
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

<p>isConstructed - Return true if this object has not been created yet.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>.</p>


<p>Reference <a href="#a50919239317978cb5ea4ffb91f753918">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### RegisterManagedStatic() {#a0455c2e6ef911ce3116fceb21d68c44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManagedStaticBase::RegisterManagedStatic (void *(*)() creator, void(*)(void *) deleter)</td>
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



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp">ManagedStatic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2d05e80d2397311d8d748484768dd537">DeleterFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp/#a0abfe48f6977bc7312df534c0916feda">getManagedStaticMutex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a09a29eef9752b39c34aa646a5812b0a7">llvm::llvm_is_multithreaded</a>, <a href="#a2e7c1cf0ea51e0bef7f9f6714af3ce51">Next</a>, <a href="#a50919239317978cb5ea4ffb91f753918">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp/#a2b09c6b05b45efd4853fa743e908d9b1">StaticList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/managedstatic/#aa3728b34e39bbece3e51c8e7d01768f1">llvm::ManagedStatic&lt; C, Creator, Deleter &gt;::operator*</a> and <a href="/web-llvm/docs/api/classes/llvm/managedstatic/#a2e5d0ddf6ef6f87222216489d4ee4fe2">llvm::ManagedStatic&lt; C, Creator, Deleter &gt;::operator*</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DeleterFn {#a2d05e80d2397311d8d748484768dd537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void(* llvm::ManagedStaticBase::DeleterFn) (void *) = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>.</p>


<p>Referenced by <a href="#ac73eaf69bd83e867f9ad27fc7251b79c">destroy</a> and <a href="#a0455c2e6ef911ce3116fceb21d68c44c">RegisterManagedStatic</a>.</p>

</div>
</div>

### Next {#a2e7c1cf0ea51e0bef7f9f6714af3ce51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ManagedStaticBase* llvm::ManagedStaticBase::Next = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>.</p>


<p>Referenced by <a href="#ac73eaf69bd83e867f9ad27fc7251b79c">destroy</a> and <a href="#a0455c2e6ef911ce3116fceb21d68c44c">RegisterManagedStatic</a>.</p>

</div>
</div>

### Ptr {#a50919239317978cb5ea4ffb91f753918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;void *&gt; llvm::ManagedStaticBase::Ptr {}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/managedstatic/#a66f4be65b6c0b6d048bb3126d2c46304">llvm::ManagedStatic&lt; C, Creator, Deleter &gt;::claim</a>, <a href="#ac73eaf69bd83e867f9ad27fc7251b79c">destroy</a>, <a href="#aad5f1491a2600048898c0e4429b834da">isConstructed</a>, <a href="/web-llvm/docs/api/classes/llvm/managedstatic/#aa3728b34e39bbece3e51c8e7d01768f1">llvm::ManagedStatic&lt; C, Creator, Deleter &gt;::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/managedstatic/#a2e5d0ddf6ef6f87222216489d4ee4fe2">llvm::ManagedStatic&lt; C, Creator, Deleter &gt;::operator*</a> and <a href="#a0455c2e6ef911ce3116fceb21d68c44c">RegisterManagedStatic</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">ManagedStatic.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp">ManagedStatic.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
