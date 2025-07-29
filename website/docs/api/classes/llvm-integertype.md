---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/integertype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IntegerType` Class

<p>Class to represent integer types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::IntegerType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instances of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> class are immutable: once they are created, they are never changed. <a href="/web-llvm/docs/api/classes/llvm/type/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a8bb58e9357b2f891f98fbbce353155ef">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This enum is just used to hold constants we need for <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>. <a href="#a8bb58e9357b2f891f98fbbce353155ef">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af746af1e4d44a9c48f3a1a69b804f73f">IntegerType</a> (LLVMContext &amp;C, unsigned NumBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70eadaa7bf647a939fa6a673c7467fa3">getExtendedType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns type twice as wide the input type. <a href="#a70eadaa7bf647a939fa6a673c7467fa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90b790ccb1af4ea5ccd69db4b8cd2d81">getBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of bits in this <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>. <a href="#a90b790ccb1af4ea5ccd69db4b8cd2d81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67042c8a1bb33ed24119bbc065709dc">getBitMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a bitmask with ones set for all of the bits that can be set by an unsigned version of this type. <a href="#aa67042c8a1bb33ed24119bbc065709dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36eedc9e574d8f1c7d1c12d0e27b93b3">getSignBit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a uint64_t with just the most significant bit set (the sign bit, if the value is treated as a signed number). <a href="#a36eedc9e574d8f1c7d1c12d0e27b93b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4afdaec43ad128c62a84c3bf1241e7dd">getMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, this is 0xFF for an 8 bit integer, 0xFFFF for i16, etc. <a href="#a4afdaec43ad128c62a84c3bf1241e7dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f7b4f1aed38192fb6b7772eb506bdb">get</a> (LLVMContext &amp;C, unsigned NumBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method is the primary way of constructing an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>. <a href="#a14f7b4f1aed38192fb6b7772eb506bdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59df261f996b1ba5db42c653da1b1a3">classof</a> (const Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast. <a href="#ab59df261f996b1ba5db42c653da1b1a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to represent integer types.</p>


<p>Note that this class is also used to represent the built-in integer types: Int1Ty, Int8Ty, Int16Ty, Int32Ty and Int64Ty. Integer representation type</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a8bb58e9357b2f891f98fbbce353155ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This enum is just used to hold constants we need for <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIN_INT_BITS<a id="a8bb58e9357b2f891f98fbbce353155efa03b0c213d98b3b6e73e3e0e4e0bdf1bf"></a></td>
<td class="doxyEnumItemDescription">Minimum number of bits that can be specified (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAX_INT_BITS<a id="a8bb58e9357b2f891f98fbbce353155efa1ccefdf8a7414a6829f888e5071e0379"></a></td>
<td class="doxyEnumItemDescription">Maximum number of bits that can be specified (= (1&lt;&lt;23))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LLVMContextImpl {#aa81f87de855d80e4275071841a7e0c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### IntegerType() {#af746af1e4d44a9c48f3a1a69b804f73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntegerType::IntegerType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned NumBits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa6a764f2b0653b70a81656accf9dda7c">llvm::Type::setSubclassData</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="#a70eadaa7bf647a939fa6a673c7467fa3">getExtendedType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBitMask() {#aa67042c8a1bb33ed24119bbc065709dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::IntegerType::getBitMask ()</td>
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

<p>Return a bitmask with ones set for all of the bits that can be set by an unsigned version of this type.</p>


<p>This is 0xFF for i8, 0xFFFF for i16, etc.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="#a90b790ccb1af4ea5ccd69db4b8cd2d81">getBitWidth</a>.</p>

</div>
</div>

### getBitWidth() {#a90b790ccb1af4ea5ccd69db4b8cd2d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntegerType::getBitWidth ()</td>
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

<p>Get the number of bits in this <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a977023a135a15dc3aadcf1e8246631f8">llvm::Type::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#aba3432b49d9f33e6eb7fbb4657b662b6">llvm::SanitizerStatReport::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/anonymous-bypassslowdivision-cpp-/fastdivinsertiontask/#ab953cd204338514e8d564c615763d13f">anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::FastDivInsertionTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a25781ba284c79cb93c65fd0c529ebf7c">findCommonType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="#aa67042c8a1bb33ed24119bbc065709dc">getBitMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a6b04886780c4fb4764f2b6dbc1d3d2d9">getOverloadKind</a>, <a href="#a36eedc9e574d8f1c7d1c12d0e27b93b3">getSignBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

### getExtendedType() {#a70eadaa7bf647a939fa6a673c7467fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * llvm::IntegerType::getExtendedType ()</td>
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

<p>Returns type twice as wide the input type.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a> and <a href="#af746af1e4d44a9c48f3a1a69b804f73f">IntegerType</a>.</p>

</div>
</div>

### getMask() {#a4afdaec43ad128c62a84c3bf1241e7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt IntegerType::getMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For example, this is 0xFF for an 8 bit integer, 0xFFFF for i16, etc.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a bit mask with ones set for all the bits of this type. Get a bit mask for this type.</p></dd>
</dl>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### getSignBit() {#a36eedc9e574d8f1c7d1c12d0e27b93b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::IntegerType::getSignBit ()</td>
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

<p>Return a uint64_t with just the most significant bit set (the sign bit, if the value is treated as a signed number).</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="#a90b790ccb1af4ea5ccd69db4b8cd2d81">getBitWidth</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ab59df261f996b1ba5db42c653da1b1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntegerType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### get() {#a14f7b4f1aed38192fb6b7772eb506bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * IntegerType::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned NumBits)</td>
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

<p>This static method is the primary way of constructing an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>.</p>


<p>If an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> with the same NumBits value was previously instantiated, that instance will be returned. Otherwise a new one will be created. Only one instance with a given NumBits value is ever created. Get or create an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> instance.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#afdce4b9880a0aed02fe487da6a613cbd">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9875dff9496a8c83bc0bcf749858c45b">buildIntrinsicArgTypes</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a41f4145f819d062ed7c74067ad334808">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::buildLookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a50ec87d072ddb08830486e9fb31ca6de">llvm::MachineIRBuilder::buildVScale</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a379666f1f08149bf9e4dabcb430aee93">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::calculateConvertType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp/#ab6ad9778a01cb685ae9a36e09ffedaab">CanShareConstantPoolEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a351251756a2dcf559089f626d9241131">llvm::VNCoercion::coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a01395be91e03a1a4c5fd713885d8327f">collectInsertionElements</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7032e1ab44275cf7331a7898a3713aad">llvm::slpvectorizer::BoUpSLP::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c89e0918b007ef2cf1d6b03c4b4948">llvm::ConstantFoldSelectInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c4fe17695dd008139cd08a7d460744e">llvm::ConstantFoldUnaryInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a48d6d1fbffc492921f07f8dc4fb3d875">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertShadowToScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp/#aa776b44397de40feb0455262dcd73f70">createAccessTag</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab84af206a9a08b9bf97eaadc87874c6c">llvm::OpenMPIRBuilder::createAtomicCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0e2de2c034e3083d006b92ddf14b8bcf">llvm::OpenMPIRBuilder::createAtomicWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0b8b82d8ef44a362f7be889d56121944">llvm::DIBuilder::createBitFieldMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ad035539cf7c551ab8d10af8a3a6c0f00">llvm::MatrixBuilder::CreateIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a2236a7be2d15db19f575591000670c9c">llvm::DIBuilder::createInheritance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ab6af8e6189a4d10f4a9c20daab0280b8">llvm::MDBuilder::createRange</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a7c9e3a3c2e449cbc1dfebc37503af252">llvm::orc::ReOptimizeLayer::createReoptimizeCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a85687b0be992ef172b4228ed69f5146a">llvm::AtomicInfo::EmitAtomicCompareExchangeLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a7a533a649b6b2b58c0705ba06f522598">llvm::AtomicInfo::EmitAtomicLoadOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ae9aaedbefa65f41bb54b62d9137f13dd">emitGlobalConstantVector</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bypassslowdivision-cpp-/fastdivinsertiontask/#ab953cd204338514e8d564c615763d13f">anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::FastDivInsertionTask</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ad7a01123cf8a0e7acd2b089c65957b26">llvm::FastISel::fastEmit_ri_</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/initializerbuilder/#abb4311f92fffab12cf33d0aa638f944e">anonymous{AArch64StackTagging.cpp}::InitializerBuilder::flatten</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a5a43eda4795549e941b4bacafdb956bb">foldConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a4757205dd7df6b811f16d2bec12c46d8">llvm::ConstantInt::get</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#af03ba86b5eeabd9ab0d8bb129933d9dc">llvm::AtomicInfo::getAtomicSizeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a6212e41633990ea795daea7917312bdf">llvm::RISCVTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a4910f3acf596de7348ca70c0b41b0040">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getExtendedReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a98477b82eae8654fb3e711d95ea127ec">llvm::DataLayout::getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#abbd9ed911d1d58b73f9571f300cc6a7b">llvm::DataLayout::getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a7a2619d0e489a4ba9c19a0d86a041d59">llvm::DataLayout::getIntPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a8bb1aa8811da861ad795a3125a9e5ce7">llvm::DataLayout::getIntPtrType</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#ab176ece61e636cb3c39919d309223786">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getIntTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a6b72d403292d9dddd1ef1ce3e8bc394c">llvm::VNCoercion::getMemInstValueForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9b1fee580716dee9404fc4e20c486392">llvm::X86TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#abe3f2bc12df17a7c061c315f7bfcf12e">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getMMXVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8bdd4c60453b10074293349820f8bdcf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3d6978ae20178c8f9414ff980fd4e3b2">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a18fd6615429a508c934bc1cff0f49319">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acdec96f14d81b2043e31f3452e440a4b">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVIntegerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#adac504434993ab1673128914746eef47">llvm::slpvectorizer::BoUpSLP::getReductionType</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a0b43ef7c72a8cb10a0cb09154a3b3b2d">llvm::slpvectorizer::BoUpSLP::getRootNodeTypeWithNoCast</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a03dd63ac617c1242b7694a4b0ae4ed25">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a643b61ddaf17331f3ff1d4f85c7c9a23">llvm::ScalarEvolution::getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#aae3e672e918b61abf32a5bb8a1aa7a08">llvm::TargetLibraryInfo::getSizeTType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a43ab95f8d1cfe32b5c75a4d4d666d89c">llvm::VNCoercion::getStoreValueForLoadHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a2c1b9368972e15e3602d4279f9988584">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTreeReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a0911ef4a610d70c5104c1932fec0e1">llvm::getTypeForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6c03d18ed744dc3b34829ec5485a68b0">llvm::ScalarEvolution::getUDivExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a13b9eb961d35ad9ecb3b633f5703253a">llvm::ScalarEvolution::getURemExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a05cf907fc03e5b3f599a3dbd02c55803">llvm::RISCVTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ac03d3c26f38bacbd611de31932ef80b4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorSadIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af414e22c02fcc9ff3ce2d81ee8d3cfcb">llvm::AMDGPU::instrumentAddressImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/irpromoter/#a1362a4e60126445f62475c3aae42bd2d">anonymous{TypePromotion.cpp}::IRPromoter::IRPromoter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9b6b892760677b9b11c517eb5a46557f">isAddRecSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1509f8a0c11e955037b00ce7542e24a7">isAddSExtable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab57dba37b1fb3b8feb6ad63f54c2e101">llvm::Type::isIEEE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a9780ca905174166ea524a30801e7e69b">IsIncrementNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a202c702ced6d0c47a226adf851aba6eb">IsIncrementNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0109582eb646d501101a7e6a059814fb">isLoadCombineCandidateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a32cdb4a97c185f1acbe11f45fcc70d12">isMulSExtable</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6bd6caf03c29de76c97c536f89349bd7">llvm::SPIRVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeint/#ga2e5db8cbc30daa156083f2c42989138d">LLVMIntTypeInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#aa78d689f88c58652639663f07a64ca41">lookThroughAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a9a1ec6b08304c2db10e687517bc4dd2c">optimizeMemCmpConstantSize</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a520d2b97d6b2eb0958cc182161938cd1">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a0b50be89487f7186a5eb7ff1bc82efc0">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapVector</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a7db2eee6dd2ea98d0ec3c05950be2915">simplifyX86pmulh</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#aabfea0675d601df03f2b2bda2bceb157">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::storeZeroPrimitiveShadow</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a3e077365cf48a773b0debd4a65499d1d">tryToFPToSat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a267fd27cb9e177fa5f48cbb8828339a1">llvm::ScalarEvolution::willNotOverflow</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
