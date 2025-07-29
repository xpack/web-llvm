---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/registerregallocbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegisterRegAllocBase` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/registerregallocbase">RegisterRegAllocBase</a> class - Track the registration of register allocators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class SubClass&gt;
class llvm::RegisterRegAllocBase&lt;SubClass&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">llvm/CodeGen/RegAllocRegistry.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode">MachinePassRegistryNode&lt;PassCtorTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode">MachinePassRegistryNode</a> - Machine pass node stored in registration list. <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac256dded4525ec3126d5fc14652cd0b3">FunctionPassCtor</a> = <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *(*)()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac90e8d65fa65253a4f819c03fb734f38">RegisterRegAllocBase</a> (const char *N, const char *D, FunctionPassCtor C)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7bfb8a4a416f7f5c78d7ff30966b6373">~RegisterRegAllocBase</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SubClass *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19407f45d4617ad4d75defe9d79e8142">getNext</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static SubClass *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a90e0bcaa78d7c718624e55a7e10343da">getList</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#ac256dded4525ec3126d5fc14652cd0b3">FunctionPassCtor</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a64385ccd715f0aa796300d361b525e4c">getDefault</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a96bb0f039016d0b9999a18a660a38f5b">setDefault</a> (FunctionPassCtor C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abcf5d142b905ed59d6bd8b68a5b29fcb">setListener</a> (MachinePassRegistryListener&lt; FunctionPassCtor &gt; *L)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SubClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinepassregistry">MachinePassRegistry</a>&lt; <a href="#ac256dded4525ec3126d5fc14652cd0b3">FunctionPassCtor</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9bef730d208036f57d8c2be1ae914ab3">Registry</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/registerregallocbase">RegisterRegAllocBase</a> class - Track the registration of register allocators.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FunctionPassCtor {#ac256dded4525ec3126d5fc14652cd0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegisterRegAllocBase&lt; SubClass &gt;::FunctionPassCtor =  FunctionPass *(*)()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegisterRegAllocBase() {#ac90e8d65fa65253a4f819c03fb734f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterRegAllocBase&lt; SubClass &gt;::RegisterRegAllocBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * D, <a href="#ac256dded4525ec3126d5fc14652cd0b3">FunctionPassCtor</a> C)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#a8587f6cac52094711e570462f5fc659d">llvm::MachinePassRegistryNode&lt; FunctionPass *(*)()&gt;::MachinePassRegistryNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a9bef730d208036f57d8c2be1ae914ab3">llvm::RegisterRegAllocBase&lt; SubClass &gt;::Registry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RegisterRegAllocBase() {#a7bfb8a4a416f7f5c78d7ff30966b6373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterRegAllocBase&lt; SubClass &gt;::~RegisterRegAllocBase ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>Reference <a href="#a9bef730d208036f57d8c2be1ae914ab3">llvm::RegisterRegAllocBase&lt; SubClass &gt;::Registry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNext() {#a19407f45d4617ad4d75defe9d79e8142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubClass * llvm::RegisterRegAllocBase&lt; SubClass &gt;::getNext ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#a9230c536c8593b8158fa1d786eb20f9e">llvm::MachinePassRegistryNode&lt; PassCtorTy &gt;::getNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDefault() {#a64385ccd715f0aa796300d361b525e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPassCtor llvm::RegisterRegAllocBase&lt; SubClass &gt;::getDefault ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>Reference <a href="#a9bef730d208036f57d8c2be1ae914ab3">llvm::RegisterRegAllocBase&lt; SubClass &gt;::Registry</a>.</p>

</div>
</div>

### getList() {#a90e0bcaa78d7c718624e55a7e10343da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubClass * llvm::RegisterRegAllocBase&lt; SubClass &gt;::getList ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>Reference <a href="#a9bef730d208036f57d8c2be1ae914ab3">llvm::RegisterRegAllocBase&lt; SubClass &gt;::Registry</a>.</p>

</div>
</div>

### setDefault() {#a96bb0f039016d0b9999a18a660a38f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegisterRegAllocBase&lt; SubClass &gt;::setDefault (<a href="#ac256dded4525ec3126d5fc14652cd0b3">FunctionPassCtor</a> C)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9bef730d208036f57d8c2be1ae914ab3">llvm::RegisterRegAllocBase&lt; SubClass &gt;::Registry</a>.</p>

</div>
</div>

### setListener() {#abcf5d142b905ed59d6bd8b68a5b29fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegisterRegAllocBase&lt; SubClass &gt;::setListener (<a href="/web-llvm/docs/api/classes/llvm/machinepassregistrylistener">MachinePassRegistryListener</a>&lt; <a href="#ac256dded4525ec3126d5fc14652cd0b3">FunctionPassCtor</a> &gt; * L)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>Reference <a href="#a9bef730d208036f57d8c2be1ae914ab3">llvm::RegisterRegAllocBase&lt; SubClass &gt;::Registry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Registry {#a9bef730d208036f57d8c2be1ae914ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SubClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePassRegistry&lt;FunctionPassCtor&gt; llvm::RegisterRegAllocBase&lt; SubClass &gt;::Registry</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a>.</p>


<p>Referenced by <a href="#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; SubClass &gt;::getDefault</a>, <a href="#a90e0bcaa78d7c718624e55a7e10343da">llvm::RegisterRegAllocBase&lt; SubClass &gt;::getList</a>, <a href="#ac90e8d65fa65253a4f819c03fb734f38">llvm::RegisterRegAllocBase&lt; SubClass &gt;::RegisterRegAllocBase</a>, <a href="#a96bb0f039016d0b9999a18a660a38f5b">llvm::RegisterRegAllocBase&lt; SubClass &gt;::setDefault</a>, <a href="#abcf5d142b905ed59d6bd8b68a5b29fcb">llvm::RegisterRegAllocBase&lt; SubClass &gt;::setListener</a> and <a href="#a7bfb8a4a416f7f5c78d7ff30966b6373">llvm::RegisterRegAllocBase&lt; SubClass &gt;::~RegisterRegAllocBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">RegAllocRegistry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
