---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-builtingcs-cpp-/coreclrgc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CoreCLRGC` Class

<p>A GCStrategy for the CoreCLR Runtime. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{BuiltinGCs.cpp}::CoreCLRGC { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> describes a garbage collector algorithm's code generation requirements, and provides overridable hooks for those needs which cannot be abstractly described. <a href="/web-llvm/docs/api/classes/llvm/gcstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad855caa394ad8edf75f93cbd521dee22">CoreCLRGC</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5844a0f3f8ef4d67cd6603f7ab3e49">isGCManagedPointer</a> (const Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the type specified can be reliably distinguished, returns true for pointers to GC managed locations and false for pointers to non-GC managed locations. <a href="#a7b5844a0f3f8ef4d67cd6603f7ab3e49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A GCStrategy for the CoreCLR Runtime.</p>


<p>The strategy is similar to Statepoint-example GC, but differs from it in certain aspects, such as: 1) Base-pointers need not be explicitly tracked and reported for interior pointers 2) Uses a different format for encoding stack-maps 3) Location of Safe-point polls: polls are only needed before loop-back edges and before tail-calls (not needed at function-entry)</p>


<p>The above differences in behavior are to be implemented in upcoming checkins.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp">BuiltinGCs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CoreCLRGC() {#ad855caa394ad8edf75f93cbd521dee22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BuiltinGCs.cpp}::CoreCLRGC::CoreCLRGC ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp">BuiltinGCs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcstrategy/#a876df2ee9b43a6e37c7e25cdbc5ee458">llvm::GCStrategy::NeededSafePoints</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstrategy/#a32c75ebeabf283b9a98b1b5641a2885e">llvm::GCStrategy::UseRS4GC</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstrategy/#a5d53780e41b87b0b8cb0e4a822f38281">llvm::GCStrategy::UsesMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/gcstrategy/#a6d4b88865bc96bd6a93c3076e210af61">llvm::GCStrategy::UseStatepoints</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isGCManagedPointer() {#a7b5844a0f3f8ef4d67cd6603f7ab3e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; anonymous{BuiltinGCs.cpp}::CoreCLRGC::isGCManagedPointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the type specified can be reliably distinguished, returns true for pointers to GC managed locations and false for pointers to non-GC managed locations.</p>


<p>Note a GCStrategy can always return 'std::nullopt' (i.e. an empty optional indicating it can't reliably distinguish.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp">BuiltinGCs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp">BuiltinGCs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
