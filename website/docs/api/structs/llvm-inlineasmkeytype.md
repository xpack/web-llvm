---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/inlineasmkeytype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InlineAsmKeyType` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::InlineAsmKeyType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">IR/ConstantsContext.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558ec1652109c42a87b3faf9152b0551">TypeClass</a> = <a href="/web-llvm/docs/api/structs/llvm/constantinfo">ConstantInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> &gt;::TypeClass</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a> (StringRef AsmString, StringRef Constraints, FunctionType *FTy, bool HasSideEffects, bool IsAlignStack, InlineAsm::AsmDialect AsmDialect, bool canThrow)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a> (const InlineAsm *Asm, SmallVectorImpl&lt; Constant * &gt; &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a> (const InlineAsmKeyType &amp;X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> (const InlineAsm *Asm) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a195d88878d374d6f43b84798853cd11d">getHash</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d02d69969b472643cf2089965f7b2cc">create</a> (TypeClass *Ty) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2173753b0c6c0003da02e073820261">AsmString</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7f88ea76609d88c7668bbd808119037">Constraints</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cd42e545336c6654bd78761d02397f">FTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5c60d81ce41cecda20c74a9b4a6181">HasSideEffects</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ada831477b641d9f4324775ae204e0c">IsAlignStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8">InlineAsm::AsmDialect</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb88a77d8baac4802696e76fe6d1eaa7">AsmDialect</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae86bb20309aae9f07788a38f979d54">CanThrow</a></td>
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


<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TypeClass {#a558ec1652109c42a87b3faf9152b0551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsmKeyType::TypeClass =  ConstantInfo&lt;InlineAsm&gt;::TypeClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InlineAsmKeyType() {#aeb20bae6e6098ff66476c0f9df1b681a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsmKeyType::InlineAsmKeyType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AsmString, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraints, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy, bool HasSideEffects, bool IsAlignStack, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8">InlineAsm::AsmDialect</a> AsmDialect, bool canThrow)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>References <a href="#aeb88a77d8baac4802696e76fe6d1eaa7">AsmDialect</a>, <a href="#a5c2173753b0c6c0003da02e073820261">AsmString</a>, <a href="#a3ae86bb20309aae9f07788a38f979d54">CanThrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a8f4bf9ef05ac2193b41802f2e8466f66">canThrow</a>, <a href="#ac7f88ea76609d88c7668bbd808119037">Constraints</a>, <a href="#af5cd42e545336c6654bd78761d02397f">FTy</a>, <a href="#a1a5c60d81ce41cecda20c74a9b4a6181">HasSideEffects</a> and <a href="#a2ada831477b641d9f4324775ae204e0c">IsAlignStack</a>.</p>


<p>Referenced by <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

### InlineAsmKeyType() {#ac4b8ba4fdeeb5daa6a524ff9418bfdc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsmKeyType::InlineAsmKeyType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> * Asm, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp;)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>References <a href="#aeb88a77d8baac4802696e76fe6d1eaa7">AsmDialect</a>, <a href="#a5c2173753b0c6c0003da02e073820261">AsmString</a>, <a href="#a3ae86bb20309aae9f07788a38f979d54">CanThrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a8f4bf9ef05ac2193b41802f2e8466f66">canThrow</a>, <a href="#ac7f88ea76609d88c7668bbd808119037">Constraints</a>, <a href="#af5cd42e545336c6654bd78761d02397f">FTy</a>, <a href="#a1a5c60d81ce41cecda20c74a9b4a6181">HasSideEffects</a> and <a href="#a2ada831477b641d9f4324775ae204e0c">IsAlignStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a23e0af3101b9d67dc71a4e06d6e416ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsmKeyType::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/inlineasmkeytype">InlineAsmKeyType</a> &amp; X)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>References <a href="#aeb88a77d8baac4802696e76fe6d1eaa7">AsmDialect</a>, <a href="#a5c2173753b0c6c0003da02e073820261">AsmString</a>, <a href="#a3ae86bb20309aae9f07788a38f979d54">CanThrow</a>, <a href="#ac7f88ea76609d88c7668bbd808119037">Constraints</a>, <a href="#af5cd42e545336c6654bd78761d02397f">FTy</a>, <a href="#a1a5c60d81ce41cecda20c74a9b4a6181">HasSideEffects</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#a2ada831477b641d9f4324775ae204e0c">IsAlignStack</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator==() {#aa0b0fd996e0184a2a66a1cfc397cbddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsmKeyType::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> * Asm)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>References <a href="#aeb88a77d8baac4802696e76fe6d1eaa7">AsmDialect</a>, <a href="#a5c2173753b0c6c0003da02e073820261">AsmString</a>, <a href="#a3ae86bb20309aae9f07788a38f979d54">CanThrow</a>, <a href="#ac7f88ea76609d88c7668bbd808119037">Constraints</a>, <a href="#af5cd42e545336c6654bd78761d02397f">FTy</a>, <a href="#a1a5c60d81ce41cecda20c74a9b4a6181">HasSideEffects</a> and <a href="#a2ada831477b641d9f4324775ae204e0c">IsAlignStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### create() {#a9d02d69969b472643cf2089965f7b2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm * llvm::InlineAsmKeyType::create (<a href="#a558ec1652109c42a87b3faf9152b0551">TypeClass</a> * Ty)</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>References <a href="#aeb88a77d8baac4802696e76fe6d1eaa7">AsmDialect</a>, <a href="#a5c2173753b0c6c0003da02e073820261">AsmString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3ae86bb20309aae9f07788a38f979d54">CanThrow</a>, <a href="#ac7f88ea76609d88c7668bbd808119037">Constraints</a>, <a href="#af5cd42e545336c6654bd78761d02397f">FTy</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a1a5c60d81ce41cecda20c74a9b4a6181">HasSideEffects</a> and <a href="#a2ada831477b641d9f4324775ae204e0c">IsAlignStack</a>.</p>

</div>
</div>

### getHash() {#a195d88878d374d6f43b84798853cd11d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InlineAsmKeyType::getHash ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>References <a href="#aeb88a77d8baac4802696e76fe6d1eaa7">AsmDialect</a>, <a href="#a5c2173753b0c6c0003da02e073820261">AsmString</a>, <a href="#a3ae86bb20309aae9f07788a38f979d54">CanThrow</a>, <a href="#ac7f88ea76609d88c7668bbd808119037">Constraints</a>, <a href="#af5cd42e545336c6654bd78761d02397f">FTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="#a1a5c60d81ce41cecda20c74a9b4a6181">HasSideEffects</a> and <a href="#a2ada831477b641d9f4324775ae204e0c">IsAlignStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AsmDialect {#aeb88a77d8baac4802696e76fe6d1eaa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::AsmDialect llvm::InlineAsmKeyType::AsmDialect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>Referenced by <a href="#a9d02d69969b472643cf2089965f7b2cc">create</a>, <a href="#a195d88878d374d6f43b84798853cd11d">getHash</a>, <a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> and <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

### AsmString {#a5c2173753b0c6c0003da02e073820261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InlineAsmKeyType::AsmString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>Referenced by <a href="#a9d02d69969b472643cf2089965f7b2cc">create</a>, <a href="#a195d88878d374d6f43b84798853cd11d">getHash</a>, <a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> and <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

### CanThrow {#a3ae86bb20309aae9f07788a38f979d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsmKeyType::CanThrow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>Referenced by <a href="#a9d02d69969b472643cf2089965f7b2cc">create</a>, <a href="#a195d88878d374d6f43b84798853cd11d">getHash</a>, <a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> and <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

### Constraints {#ac7f88ea76609d88c7668bbd808119037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InlineAsmKeyType::Constraints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>Referenced by <a href="#a9d02d69969b472643cf2089965f7b2cc">create</a>, <a href="#a195d88878d374d6f43b84798853cd11d">getHash</a>, <a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> and <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

### FTy {#af5cd42e545336c6654bd78761d02397f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* llvm::InlineAsmKeyType::FTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>Referenced by <a href="#a9d02d69969b472643cf2089965f7b2cc">create</a>, <a href="#a195d88878d374d6f43b84798853cd11d">getHash</a>, <a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> and <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

### HasSideEffects {#a1a5c60d81ce41cecda20c74a9b4a6181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsmKeyType::HasSideEffects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>Referenced by <a href="#a9d02d69969b472643cf2089965f7b2cc">create</a>, <a href="#a195d88878d374d6f43b84798853cd11d">getHash</a>, <a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> and <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

### IsAlignStack {#a2ada831477b641d9f4324775ae204e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsmKeyType::IsAlignStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a>.</p>


<p>Referenced by <a href="#a9d02d69969b472643cf2089965f7b2cc">create</a>, <a href="#a195d88878d374d6f43b84798853cd11d">getHash</a>, <a href="#ac4b8ba4fdeeb5daa6a524ff9418bfdc3">InlineAsmKeyType</a>, <a href="#aeb20bae6e6098ff66476c0f9df1b681a">InlineAsmKeyType</a>, <a href="#aa0b0fd996e0184a2a66a1cfc397cbddf">operator==</a> and <a href="#a23e0af3101b9d67dc71a4e06d6e416ad">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constantscontext-h">ConstantsContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
