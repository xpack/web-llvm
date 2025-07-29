---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantdataarray
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConstantDataArray` Class

<p>An array constant whose element type is a simple 1/2/4/8-byte integer or float/double, and whose elements are just simple data values (i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantDataArray { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> - A vector or array constant whose element type is a simple 1/2/4/8-byte integer or half/bfloat/float/double, and whose elements are just simple data values (i.e. <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74958cbd34e1860b1a7c946af159cbb4">ConstantDataSequential</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45b5ebaf6175e624d2ff6aaf72eaf07">ConstantDataArray</a> (const ConstantDataArray &amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad338d7ff45c71662c4ec72412c3a400">ConstantDataArray</a> (Type *ty, const char *Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25529592c7a7bbffe7acbc752d513c0">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialize the <a href="#af25529592c7a7bbffe7acbc752d513c0">getType()</a> method to always return an <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a>, which reduces the amount of casting needed in parts of the compiler. <a href="#af25529592c7a7bbffe7acbc752d513c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ElementTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a1000e5803e731e9dcc572042a98a0b">get</a> (LLVMContext &amp;Context, ArrayRef&lt; ElementTy &gt; Elts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a4a1000e5803e731e9dcc572042a98a0b">get()</a> constructor - Return a constant with array type with an element count and element type matching the <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> passed in. <a href="#a4a1000e5803e731e9dcc572042a98a0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ArrayTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a7c0ddf7f8e222e0fabf305430c7c0b">get</a> (LLVMContext &amp;Context, ArrayTy &amp;Elts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a4a1000e5803e731e9dcc572042a98a0b">get()</a> constructor - ArrayTy needs to be compatible with <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ElementTy&gt;</a>. <a href="#a7a7c0ddf7f8e222e0fabf305430c7c0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86e02b5bee8ad12233bbf1719d1312f">getRaw</a> (StringRef Data, uint64_t NumElements, Type *ElementTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ad86e02b5bee8ad12233bbf1719d1312f">getRaw()</a> constructor - Return a constant with array type with an element count and element type matching the NumElements and ElementTy parameters passed in. <a href="#ad86e02b5bee8ad12233bbf1719d1312f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eec77c77aa76611db6766a3f205570c">getFP</a> (Type *ElementType, ArrayRef&lt; uint16_t &gt; Elts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a6eec77c77aa76611db6766a3f205570c">getFP()</a> constructors - Return a constant of array type with a float element type taken from argument ‘ElementType`, and count taken from argument ‘Elts`. <a href="#a6eec77c77aa76611db6766a3f205570c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e552ee615150b4efe5195ac45d4389">getFP</a> (Type *ElementType, ArrayRef&lt; uint32_t &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4228cf6f5c478449deca90c6ce2255">getFP</a> (Type *ElementType, ArrayRef&lt; uint64_t &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3edef3fa47c611d3d10606591213e57b">getString</a> (LLVMContext &amp;Context, StringRef Initializer, bool AddNull=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method constructs a CDS and initializes it with a text string. <a href="#a3edef3fa47c611d3d10606591213e57b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0875ea2e7029f9b8b327990d0a426763">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a0875ea2e7029f9b8b327990d0a426763">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An array constant whose element type is a simple 1/2/4/8-byte integer or float/double, and whose elements are just simple data values (i.e.</p>


<p>ConstantInt/ConstantFP). This <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> node has no operands because it stores all of the elements of the constant as densely packed data, instead of as Value*'s.</p>


<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ConstantDataSequential {#a74958cbd34e1860b1a7c946af159cbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="#a74958cbd34e1860b1a7c946af159cbb4">ConstantDataSequential</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#a74958cbd34e1860b1a7c946af159cbb4">ConstantDataSequential</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConstantDataArray() {#ac45b5ebaf6175e624d2ff6aaf72eaf07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantDataArray::ConstantDataArray (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ConstantDataArray() {#aad338d7ff45c71662c4ec72412c3a400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantDataArray::ConstantDataArray (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data)</td>
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



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getType() {#af25529592c7a7bbffe7acbc752d513c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType * llvm::ConstantDataArray::getType ()</td>
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

<p>Specialize the <a href="#af25529592c7a7bbffe7acbc752d513c0">getType()</a> method to always return an <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a>, which reduces the amount of casting needed in parts of the compiler.</p>

<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0875ea2e7029f9b8b327990d0a426763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantDataArray::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### get() {#a4a1000e5803e731e9dcc572042a98a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ElementTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ConstantDataArray::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; ElementTy &gt; Elts)</td>
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

<p><a href="#a4a1000e5803e731e9dcc572042a98a0b">get()</a> constructor - Return a constant with array type with an element count and element type matching the <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> passed in.</p>


<p>Note that this can return a <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> object.</p>


<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="#ad86e02b5bee8ad12233bbf1719d1312f">getRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab908d9ac4f123b5f676e1548c123820c">llvm::Type::getScalarTy</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a6f467de3ca984f069ee86b9558388294">anonymous{OffloadWrapper.cpp}::createBinDesc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a251d6cd85b676ea4be1e4c2c263494db">anonymous{OffloadWrapper.cpp}::createFatbinDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ad56f71598b251a0f66e590c94d01c67b">llvm::OpenMPIRBuilder::createOffloadMaptypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="#a7a7c0ddf7f8e222e0fabf305430c7c0b">get</a>, <a href="#a3edef3fa47c611d3d10606591213e57b">getString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a12cea94e94a75a84e5e5c0a649d1ef78">anonymous{WholeProgramDevirt.cpp}::DevirtModule::rebuildGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilwriterpass-cpp-/embeddxilpass/#a40185bab20927a719a78e3747d96430d">anonymous{DXILWriterPass.cpp}::EmbedDXILPass::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a52e0d03acf3c67fcf1c68887dca291a7">tagGlobalDefinition</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>.</p>

</div>
</div>

### get() {#a7a7c0ddf7f8e222e0fabf305430c7c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ArrayTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ConstantDataArray::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, ArrayTy &amp; Elts)</td>
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

<p><a href="#a4a1000e5803e731e9dcc572042a98a0b">get()</a> constructor - ArrayTy needs to be compatible with <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ElementTy&gt;</a>.</p>


<p>Calls get(LLVMContext, ArrayRef&lt;ElementTy&gt;).</p>


<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a> and <a href="#a4a1000e5803e731e9dcc572042a98a0b">get</a>.</p>

</div>
</div>

### getFP() {#a6eec77c77aa76611db6766a3f205570c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataArray::getFP (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint16_t &gt; Elts)</td>
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

<p><a href="#a6eec77c77aa76611db6766a3f205570c">getFP()</a> constructors - Return a constant of array type with a float element type taken from argument ‘ElementType`, and count taken from argument ‘Elts`.</p>


<p>The amount of bits of the contained type must match the number of bits of the type contained in the passed in <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>. (i.e. half or bfloat for 16bits, float for 32bits, double for 64bits) Note that this can return a <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> object.</p>


<p>Declaration at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2970 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getFP() {#a54e552ee615150b4efe5195ac45d4389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataArray::getFP (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; Elts)</td>
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



<p>Declaration at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2977 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getFP() {#a3d4228cf6f5c478449deca90c6ce2255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataArray::getFP (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Elts)</td>
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



<p>Declaration at line 742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2983 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getRaw() {#ad86e02b5bee8ad12233bbf1719d1312f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ConstantDataArray::getRaw (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, uint64_t NumElements, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementTy)</td>
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

<p><a href="#ad86e02b5bee8ad12233bbf1719d1312f">getRaw()</a> constructor - Return a constant with array type with an element count and element type matching the NumElements and ElementTy parameters passed in.</p>


<p>Note that this can return a <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> object. ElementTy must be one of i8/i16/i32/i64/half/bfloat/float/double. Data is the buffer containing the elements. Be careful to make sure Data uses the right endianness, the buffer will be used as-is.</p>


<p>Definition at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a>.</p>


<p>Referenced by <a href="#a4a1000e5803e731e9dcc572042a98a0b">get</a>.</p>

</div>
</div>

### getString() {#a3edef3fa47c611d3d10606591213e57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataArray::getString (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Initializer, bool AddNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>This method constructs a CDS and initializes it with a text string.</p>


<p>The default behavior (AddNull==true) causes a null terminator to be placed at the end of the array (increasing the length of the string by one more than the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> would normally indicate. <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> AddNull=false to disable this behavior.</p>


<p>Declaration at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2991 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a4a1000e5803e731e9dcc572042a98a0b">get</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af377188a476a2d71184b0498a136fd1d">llvm::IRBuilderBase::CreateGlobalString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a61a95dc82ae09814a35f56fcc56cad5b">createMemprofDefaultOptionsVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affc1b0222446287a4297e23855a5e18e">llvm::createPGOFuncNameVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#aa4ec1be5a80593697012bc67e2410e11">createPrivateConstGlobalForString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15889f1df360601e4f92325b39882a34">llvm::createPrivateGlobalForString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#adced657ead8595f4da252cea6e2f3dd8">createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a55a39962245dd2e0938194dd3b4438e5">llvm::OpenMPIRBuilder::getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantcomposite/#ga4c03790f184b6e406105551341a8a39c">LLVMConstStringInContext</a> and <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantcomposite/#gac0701df6a157035a987295dfda6c78dd">LLVMConstStringInContext2</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
