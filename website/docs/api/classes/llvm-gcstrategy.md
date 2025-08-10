---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCStrategy` Class

<p><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> describes a garbage collector algorithm's code generation requirements, and provides overridable hooks for those needs which cannot be abstractly described. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">llvm/IR/GCStrategy.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/coreclrgc">CoreCLRGC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A GCStrategy for the CoreCLR Runtime. <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/coreclrgc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/erlanggc">ErlangGC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An example GC which attempts to be compatible with Erlang/OTP garbage collector. <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/erlanggc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/ocamlgc">OcamlGC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An example GC which attempts to be compatible with Objective Caml 3.10.0. <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/ocamlgc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/shadowstackgc">ShadowStackGC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A GC strategy for uncooperative targets. <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/shadowstackgc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/statepointgc">StatepointGC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A GCStrategy which serves as an example for the usage of a statepoint based lowering strategy. <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/statepointgc/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0052c613569d8b1bd3b87a3e133423">GCModuleInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5b7efa0f9360dac6bbd35ab553cb0d">GCStrategy</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed755642573059053607d5642eb99da9">~GCStrategy</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae253aa14fb9f8582e089850f07616599">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of the GC strategy. <a href="#ae253aa14fb9f8582e089850f07616599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2fe86699990ff4cec0233e3daf651d">useStatepoints</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this strategy is expecting the use of gc.statepoints, and false otherwise. <a href="#a7b2fe86699990ff4cec0233e3daf651d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b51aca35066f7e941e54bb504d8755">usesMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If set, appropriate metadata tables must be emitted by the back-end (assembler, JIT, or otherwise). <a href="#a79b51aca35066f7e941e54bb504d8755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d4b88865bc96bd6a93c3076e210af61">UseStatepoints</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32c75ebeabf283b9a98b1b5641a2885e">UseRS4GC</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Uses gc.statepoints as opposed to gc.roots, if set, NeededSafePoints and UsesMetadata should be left at their default values. <a href="#a32c75ebeabf283b9a98b1b5641a2885e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876df2ee9b43a6e37c7e25cdbc5ee458">NeededSafePoints</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If UseStatepoints is set, this determines whether the <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc">RewriteStatepointsForGC</a> pass should rewrite this function's calls. <a href="#a876df2ee9b43a6e37c7e25cdbc5ee458">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d53780e41b87b0b8cb0e4a822f38281">UsesMetadata</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If set, backend must emit metadata tables. <a href="#a5d53780e41b87b0b8cb0e4a822f38281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b41b74548936c21212303f8626286e6">Name</a></td>
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

## Statepoint Specific Properties Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bbb5320403c4748de766cc6efc5e55e">isGCManagedPointer</a> (const Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the type specified can be reliably distinguished, returns true for pointers to GC managed locations and false for pointers to non-GC managed locations. <a href="#a6bbb5320403c4748de766cc6efc5e55e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86859e2cfd56ae04d6baef2f512e22fd">useRS4GC</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc">RewriteStatepointsForGC</a> pass should run on functions using this GC. <a href="#a86859e2cfd56ae04d6baef2f512e22fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## GCRoot Specific Properties Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ea3bc520b9a03eae28fc6857a79f24">needsSafePoints</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if safe points need to be inferred on call sites. <a href="#a80ea3bc520b9a03eae28fc6857a79f24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> describes a garbage collector algorithm's code generation requirements, and provides overridable hooks for those needs which cannot be abstractly described.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> objects must be looked up through the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. The objects themselves are owned by the Context and must be immutable.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<div class="doxySectionDef">

## Friends

### GCModuleInfo {#a5b0052c613569d8b1bd3b87a3e133423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/gcmoduleinfo">GCModuleInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Reference <a href="#a5b0052c613569d8b1bd3b87a3e133423">GCModuleInfo</a>.</p>


<p>Referenced by <a href="#a5b0052c613569d8b1bd3b87a3e133423">GCModuleInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCStrategy() {#abc5b7efa0f9360dac6bbd35ab553cb0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCStrategy::GCStrategy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GCStrategy() {#aed755642573059053607d5642eb99da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::GCStrategy::~GCStrategy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getName() {#ae253aa14fb9f8582e089850f07616599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::GCStrategy::getName ()</td>
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

<p>Return the name of the GC strategy.</p>


<p>This is the value of the collector name string specified on functions which use this strategy.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-erlanggcprinter-cpp-/erlanggcprinter/#a574679a34186d5db3a7b14b0ce5c5078">anonymous{ErlangGCPrinter.cpp}::ErlangGCPrinter::finishAssembly</a>.</p>

</div>
</div>

### usesMetadata() {#a79b51aca35066f7e941e54bb504d8755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::usesMetadata ()</td>
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

<p>If set, appropriate metadata tables must be emitted by the back-end (assembler, JIT, or otherwise).</p>


<p>The default stackmap information can be found in the StackMap section as described in the documentation.</p>


<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Reference <a href="#a5d53780e41b87b0b8cb0e4a822f38281">UsesMetadata</a>.</p>

</div>
</div>

### useStatepoints() {#a7b2fe86699990ff4cec0233e3daf651d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::useStatepoints ()</td>
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

<p>Returns true if this strategy is expecting the use of gc.statepoints, and false otherwise.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Reference <a href="#a6d4b88865bc96bd6a93c3076e210af61">UseStatepoints</a>.</p>


<p>Referenced by <a href="#a86859e2cfd56ae04d6baef2f512e22fd">useRS4GC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### NeededSafePoints {#a876df2ee9b43a6e37c7e25cdbc5ee458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::NeededSafePoints = false</td>
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

<p>If UseStatepoints is set, this determines whether the <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc">RewriteStatepointsForGC</a> pass should rewrite this function's calls.</p>


<p>This should only be set if UseStatepoints is set. if set, calls are inferred to be safepoints</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/coreclrgc/#ad855caa394ad8edf75f93cbd521dee22">anonymous{BuiltinGCs.cpp}::CoreCLRGC::CoreCLRGC</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/erlanggc/#a448b4082c6e640d8c6373f86896ea839">anonymous{BuiltinGCs.cpp}::ErlangGC::ErlangGC</a>, <a href="#a80ea3bc520b9a03eae28fc6857a79f24">needsSafePoints</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/ocamlgc/#a5f857693031a2dc678526f64cc899121">anonymous{BuiltinGCs.cpp}::OcamlGC::OcamlGC</a> and <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/statepointgc/#ad783af64abf7eede187e42abfcbd4f22">anonymous{BuiltinGCs.cpp}::StatepointGC::StatepointGC</a>.</p>

</div>
</div>

### UseRS4GC {#a32c75ebeabf283b9a98b1b5641a2885e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::UseRS4GC = false</td>
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

<p>Uses gc.statepoints as opposed to gc.roots, if set, NeededSafePoints and UsesMetadata should be left at their default values.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/coreclrgc/#ad855caa394ad8edf75f93cbd521dee22">anonymous{BuiltinGCs.cpp}::CoreCLRGC::CoreCLRGC</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/statepointgc/#ad783af64abf7eede187e42abfcbd4f22">anonymous{BuiltinGCs.cpp}::StatepointGC::StatepointGC</a> and <a href="#a86859e2cfd56ae04d6baef2f512e22fd">useRS4GC</a>.</p>

</div>
</div>

### UsesMetadata {#a5d53780e41b87b0b8cb0e4a822f38281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::UsesMetadata = false</td>
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

<p>If set, backend must emit metadata tables.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/coreclrgc/#ad855caa394ad8edf75f93cbd521dee22">anonymous{BuiltinGCs.cpp}::CoreCLRGC::CoreCLRGC</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/erlanggc/#a448b4082c6e640d8c6373f86896ea839">anonymous{BuiltinGCs.cpp}::ErlangGC::ErlangGC</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/ocamlgc/#a5f857693031a2dc678526f64cc899121">anonymous{BuiltinGCs.cpp}::OcamlGC::OcamlGC</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/statepointgc/#ad783af64abf7eede187e42abfcbd4f22">anonymous{BuiltinGCs.cpp}::StatepointGC::StatepointGC</a> and <a href="#a79b51aca35066f7e941e54bb504d8755">usesMetadata</a>.</p>

</div>
</div>

### UseStatepoints {#a6d4b88865bc96bd6a93c3076e210af61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::UseStatepoints = false</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/coreclrgc/#ad855caa394ad8edf75f93cbd521dee22">anonymous{BuiltinGCs.cpp}::CoreCLRGC::CoreCLRGC</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/statepointgc/#ad783af64abf7eede187e42abfcbd4f22">anonymous{BuiltinGCs.cpp}::StatepointGC::StatepointGC</a> and <a href="#a7b2fe86699990ff4cec0233e3daf651d">useStatepoints</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#a2b41b74548936c21212303f8626286e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::GCStrategy::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Statepoint Specific Properties

### isGCManagedPointer {#a6bbb5320403c4748de766cc6efc5e55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; bool &gt; llvm::GCStrategy::isGCManagedPointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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


<p>Note a <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> can always return 'std::nullopt' (i.e. an empty optional indicating it can't reliably distinguish.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>

</div>
</div>

### useRS4GC {#a86859e2cfd56ae04d6baef2f512e22fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::useRS4GC ()</td>
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

<p>Returns true if the <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc">RewriteStatepointsForGC</a> pass should run on functions using this GC.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a32c75ebeabf283b9a98b1b5641a2885e">UseRS4GC</a> and <a href="#a7b2fe86699990ff4cec0233e3daf651d">useStatepoints</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## GCRoot Specific Properties



<p>These properties and overrides only apply to collector strategies using <a href="/web-llvm/docs/api/structs/llvm/gcroot">GCRoot</a>.</p>


### needsSafePoints {#a80ea3bc520b9a03eae28fc6857a79f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStrategy::needsSafePoints ()</td>
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

<p>True if safe points need to be inferred on call sites.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a>.</p>


<p>Reference <a href="#a876df2ee9b43a6e37c7e25cdbc5ee458">NeededSafePoints</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">GCStrategy.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
