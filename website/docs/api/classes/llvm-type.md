---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/type
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Type` Class

<p>The instances of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> class are immutable: once they are created, they are never changed. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Type { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent array types. <a href="/web-llvm/docs/api/classes/llvm/arraytype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent function types. <a href="/web-llvm/docs/api/classes/llvm/functiontype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent integer types. <a href="/web-llvm/docs/api/classes/llvm/integertype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent pointers. <a href="/web-llvm/docs/api/classes/llvm/pointertype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent struct types. <a href="/web-llvm/docs/api/classes/llvm/structtype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent target extensions types, which are generally unintrospectable from target-independent optimizations. <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typedpointertype">TypedPointerType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A few GPU targets, such as DXIL and SPIR-V, have typed pointers. <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class of all SIMD vector types. <a href="/web-llvm/docs/api/classes/llvm/vectortype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5325d504915a0e903f78cd39bbc59bb5">subtype_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2deb3b1de1d324eedf109b42790524">subtype_reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a5325d504915a0e903f78cd39bbc59bb5">subtype_iterator</a> &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TypeID { <a href="#a5e9e1c0dd93557be1b4ad72860f3cbda">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Definitions of all of the base types for the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> system. <a href="#a5e9e1c0dd93557be1b4ad72860f3cbda">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a> (LLVMContext &amp;C, TypeID tid)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09354645c72c44738278f80ca78f759f">~Type</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bbc1ac424839ba7e85d2d8542c288a">print</a> (raw_ostream &amp;O, bool IsForDebug=false, bool NoDetails=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the current type. <a href="#a91bbc1ac424839ba7e85d2d8542c288a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c89709fd5e5e1d96455aec8b0c3916">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909eca4ba9e5eefc203c8e3770bdab25">getContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> in which this type was uniqued. <a href="#a909eca4ba9e5eefc203c8e3770bdab25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5e9e1c0dd93557be1b4ad72860f3cbda">TypeID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type id for the type. <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8eaa0b4eeac52a2b2282cb1bfd981ae">isVoidTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'void'. <a href="#ae8eaa0b4eeac52a2b2282cb1bfd981ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf1f36cc41c466e66d6467e40554841">isHalfTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'half', a 16-bit IEEE fp type. <a href="#a8cf1f36cc41c466e66d6467e40554841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468e032827ddcd10a8608e08a61323aa">isBFloatTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'bfloat', a 16-bit bfloat type. <a href="#a468e032827ddcd10a8608e08a61323aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e097994740799690554ad4b76f0ccd">is16bitFPTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 16-bit float type. <a href="#a73e097994740799690554ad4b76f0ccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ffc75c3a4cb82ba307a3334483eb4ac">isFloatTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'float', a 32-bit IEEE fp type. <a href="#a3ffc75c3a4cb82ba307a3334483eb4ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0fd6bf3d33236279db7b707bba755f4">isDoubleTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'double', a 64-bit IEEE fp type. <a href="#aa0fd6bf3d33236279db7b707bba755f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f68c27188f1836737bf22a62c558354">isX86_FP80Ty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is x86 long double. <a href="#a1f68c27188f1836737bf22a62c558354">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f174fc924aa9cccf2abce5ef4b5ec9a">isFP128Ty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'fp128'. <a href="#a6f174fc924aa9cccf2abce5ef4b5ec9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670980c63f2e5ca39022baf96173eb9c">isPPC_FP128Ty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is powerpc long double. <a href="#a670980c63f2e5ca39022baf96173eb9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad696083ef7553304ab42e6d3667942e0">isIEEELikeFPTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a well-behaved IEEE-like type, which has a IEEE compatible layout as defined by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af3bec23b6e372e677f17151bfd6af8fc">APFloat::isIEEE()</a>, and does not have non-IEEE values, such as x86_fp80's unnormal values. <a href="#ad696083ef7553304ab42e6d3667942e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5759c83abd6a4af236401a7cfe7a0f">isFloatingPointTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is one of the floating-point types. <a href="#aac5759c83abd6a4af236401a7cfe7a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fcf2946847a73b99dc54ea4203d3eb7">isMultiUnitFPType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a floating-point type that is an unevaluated sum of multiple floating-point units. <a href="#a7fcf2946847a73b99dc54ea4203d3eb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc21598ac33ea9d50f3a939f26a28940">getFltSemantics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab549082d9dfb91ec9a8dc06601d54855">isX86_AMXTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> AMX. <a href="#ab549082d9dfb91ec9a8dc06601d54855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8536986ed6c44fce15dba30748428d2c">isTargetExtTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a target extension type. <a href="#a8536986ed6c44fce15dba30748428d2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb40ca82dbaafb00a8dd85d5f9feddc4">isScalableTargetExtTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a target extension type with a scalable layout. <a href="#aeb40ca82dbaafb00a8dd85d5f9feddc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff127c9924cd3337080c4445c324aea">isScalableTy</a> (SmallPtrSetImpl&lt; const Type * &gt; &amp;Visited) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a type whose size is a known multiple of vscale. <a href="#a2ff127c9924cd3337080c4445c324aea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3508a388e7f7545f2a4c745f087916">isScalableTy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e62ec586d4d045f4e0b7bfd1f04ce4">containsNonGlobalTargetExtType</a> (SmallPtrSetImpl&lt; const Type * &gt; &amp;Visited) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is or contains a target extension type that disallows being used as a global. <a href="#a23e62ec586d4d045f4e0b7bfd1f04ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b43432683c09a40d81b9b245a05565">containsNonGlobalTargetExtType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0388b8315300b55a8833caf090ef71">containsNonLocalTargetExtType</a> (SmallPtrSetImpl&lt; const Type * &gt; &amp;Visited) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is or contains a target extension type that disallows being used as a local. <a href="#a2f0388b8315300b55a8833caf090ef71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77d4c2d7f8556667a38ab71c72cb54f">containsNonLocalTargetExtType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0709baa705ae62c4e09cdd47fb4b420">isFPOrFPVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a FP type or a vector of FP. <a href="#ad0709baa705ae62c4e09cdd47fb4b420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332975f1fb88675058c22029696c991c">isLabelTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'label'. <a href="#a332975f1fb88675058c22029696c991c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3adb81d6f38168542fa408efa365d8">isMetadataTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'metadata'. <a href="#afb3adb81d6f38168542fa408efa365d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9542ee3a689ae9574b7807c96107d89">isTokenTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is 'token'. <a href="#ac9542ee3a689ae9574b7807c96107d89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6d28a9b11139182134a9618028a0d07">isIntegerTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>. <a href="#ac6d28a9b11139182134a9618028a0d07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1214af6bcd9ec53ed43c6ba74c1e9af7">isIntegerTy</a> (unsigned Bitwidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> of the given width. <a href="#a1214af6bcd9ec53ed43c6ba74c1e9af7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ee40bb2f4f5ece47ef19e5f1f57e3c">isIntOrIntVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer type or a vector of integer types. <a href="#a34ee40bb2f4f5ece47ef19e5f1f57e3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd5a11bf5ca1fba6c858d3d59ea6a35">isIntOrIntVectorTy</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer type or a vector of integer types of the given width. <a href="#a0cd5a11bf5ca1fba6c858d3d59ea6a35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf313eff420b7c6c8e322a2e9c53cd90">isIntOrPtrTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer type or a pointer type. <a href="#abf313eff420b7c6c8e322a2e9c53cd90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba930e0564c4207f112d9243eb2fc13a">isFunctionTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a>. <a href="#aba930e0564c4207f112d9243eb2fc13a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81eef9d7336f7ee43be79630d8e8ec86">isStructTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a>. <a href="#a81eef9d7336f7ee43be79630d8e8ec86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a394517076e7dd2bdcd7dde33dfcb7d">isArrayTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a>. <a href="#a2a394517076e7dd2bdcd7dde33dfcb7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b996fbf8458aafffc86cb98a68d0a47">isPointerTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a>. <a href="#a3b996fbf8458aafffc86cb98a68d0a47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab03652069eab17006c51f00c261a6a44">isPtrOrPtrVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a pointer type or a vector of pointer types. <a href="#ab03652069eab17006c51f00c261a6a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc022868b23918efa44df511f4d5b61">isVectorTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a>. <a href="#a1bc022868b23918efa44df511f4d5b61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826c21ba60337817422247c0e98120c9">isRISCVVectorTupleTy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651563a742c52504d1980955fe75b95d">canLosslesslyBitCastTo</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type could be converted with a lossless BitCast to type 'Ty'. <a href="#a651563a742c52504d1980955fe75b95d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5c23d3b941362c2fa195f4c0b99683">isEmptyTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is empty, that is, it has no elements or all of its elements are empty. <a href="#a0f5c23d3b941362c2fa195f4c0b99683">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a7e98c00f5bb12e2c5481fe0ab3f1a">isFirstClassType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type is "first class", meaning it is a valid type for a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a82a7e98c00f5bb12e2c5481fe0ab3f1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6edc5246188225b3f49bd5c974c759">isSingleValueType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type is a valid type for a register in codegen. <a href="#a5f6edc5246188225b3f49bd5c974c759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbe006c6c069502d37891c438847c23">isAggregateType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type is an aggregate type. <a href="#a8cbe006c6c069502d37891c438847c23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad67a33bae235fe3cca1c3e5a91ed2d">isSized</a> (SmallPtrSetImpl&lt; Type * &gt; *Visited=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it makes sense to take the size of this type. <a href="#a8ad67a33bae235fe3cca1c3e5a91ed2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833daf718a49c5cd637d8c9ddeaebe07">getPrimitiveSizeInBits</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the basic size of this type if it is a primitive type. <a href="#a833daf718a49c5cd637d8c9ddeaebe07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f382207d841377156d4c7868b66b9a5">getScalarSizeInBits</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a vector type, return the getPrimitiveSizeInBits value for the element type. <a href="#a9f382207d841377156d4c7868b66b9a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b99a13e459cb18bb386ddd610ecf8c">getFPMantissaWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the width of the mantissa of this type. <a href="#ad9b99a13e459cb18bb386ddd610ecf8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57dba37b1fb3b8feb6ad63f54c2e101">isIEEE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the type is IEEE compatible, as defined by the eponymous method in <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#ab57dba37b1fb3b8feb6ad63f54c2e101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a vector type, return the element type, otherwise return 'this'. <a href="#a7c742b32ebcd73d6dc851afac295b0f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5325d504915a0e903f78cd39bbc59bb5">subtype_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a6b4d55d33508391d708d15ac94241">subtype_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5325d504915a0e903f78cd39bbc59bb5">subtype_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ceb7d8f499a1052bec53ed1b588673">subtype_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea992fd3e9da95e4fff1dca95f873c3">subtypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9a2deb3b1de1d324eedf109b42790524">subtype_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a1e304cf35053589c10a80fa202672">subtype_rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9a2deb3b1de1d324eedf109b42790524">subtype_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0c4f5920877210db407ce6d11656ce">subtype_rend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d50278883f39969187bceabe068acf">getContainedType</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used to implement the type iterator (defined at the end of the file). <a href="#ad1d50278883f39969187bceabe068acf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d610d816ff0a14e8ac599dcaefd2c6">getNumContainedTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of types in the derived type. <a href="#a66d610d816ff0a14e8ac599dcaefd2c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e877ef779ba7a0688081079f4f9b03">getIntegerBitWidth</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c20e4a8194779750a20ce5caef81f7">getFunctionParamType</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7242fc7f3fcad5795e277521414c154">getFunctionNumParams</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfc626c3a806891f7adc829e290c097">isFunctionVarArg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0a50f63402f509e3f6c62a6c513fbf">getStructName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e54adaa7672bbf72091254a5391137">getStructNumElements</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d34f8dc07013df378e0fb3d0134c08">getStructElementType</a> (unsigned N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfdb1cd5ccaae5daa8e4b29b3bb6b82">getArrayNumElements</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb19a71e602dce8ff646c3ac2f4ca0f">getArrayElementType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757dc51e994d986d1b9f8211f6390b4d">getTargetExtName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa51d3da96615af400274e9cd272df4">getWithNewType</a> (Type *EltTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given vector type, change the element type, whilst keeping the old number of elements. <a href="#a8fa51d3da96615af400274e9cd272df4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83725435ece9bc12c40ceb34dbd1727c">getWithNewBitWidth</a> (unsigned NewBitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an integer or vector type, change the lane bitwidth to NewBitwidth, whilst keeping the old number of lanes. <a href="#a83725435ece9bc12c40ceb34dbd1727c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac59306eb826e349ac7429736b1506432">getExtendedType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given scalar/vector integer type, returns a type with elements twice as wide as in the original type. <a href="#ac59306eb826e349ac7429736b1506432">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ab2d0b0f0b8ceec3b907184e7567197">getPointerAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the address space of this pointer or pointer vector type. <a href="#a5ab2d0b0f0b8ceec3b907184e7567197">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc01a7457de85fc52a3bb860d7e1c6a4">getPointerTo</a> (unsigned AddrSpace=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the current type. <a href="#adc01a7457de85fc52a3bb860d7e1c6a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977023a135a15dc3aadcf1e8246631f8">getSubclassData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a764f2b0653b70a81656accf9dda7c">setSubclassData</a> (unsigned val)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1793581033b3e347ab37766779d8db1e">isSizedDerivedType</a> (SmallPtrSetImpl&lt; Type * &gt; *Visited=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Derived types like structures and arrays are sized iff all of the members of the type are sized as well. <a href="#a1793581033b3e347ab37766779d8db1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679d8ea00092eb9cd392643bb2d1b7f9">NumContainedTys</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of how many Type*'s there are in the ContainedTys list. <a href="#a679d8ea00092eb9cd392643bb2d1b7f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d2037eb473457f3222e5cbe7ea22b5">ContainedTys</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pointer to the array of Types contained by this <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a96d2037eb473457f3222e5cbe7ea22b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369d6666c49f7eb1bc92591361aca7e4">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This refers to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> in which this type was uniqued. <a href="#a369d6666c49f7eb1bc92591361aca7e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5e9e1c0dd93557be1b4ad72860f3cbda">TypeID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd0c2963251ea586af7e2ecd87ff4cf">ID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe943e0fe940c7e7859551d09733450">SubclassData</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afb3494f6f22e80508f1945a2466052">getPrimitiveType</a> (LLVMContext &amp;C, TypeID IDNumber)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a type based on an identifier. <a href="#a8afb3494f6f22e80508f1945a2466052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e20e76960d952de088354cbcd14c3ab">getVoidTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a17871a3bb12fd2b8e1e45454c3e1c3">getLabelTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae550f2e9436b395b614b4377ba27007f">getHalfTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3aa33c6054ec18e1d6bc6466d1b4103">getBFloatTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e0fe0efdd88f98a5b5eb512d5351c2">getFloatTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb145f988329d1d621f73abcafea21d8">getDoubleTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28fdf240b8220065bc60d6d1b1a2f174">getMetadataTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5611e40c0a2dbdc2c6cbc93bea180c">getX86_FP80Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f37835a410e050b960dd936a54dd05">getFP128Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489d14cb1d049f4bcc5e3e9cdaf9c54d">getPPC_FP128Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ceb864464bce07aed4387d665f6565">getX86_AMXTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b741dd02fbe0b1f02e589a785748639">getTokenTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf8e4c3e40e01e848c1fad5f05b81cd">getIntNTy</a> (LLVMContext &amp;C, unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75984a442f2379de0c66018201fa628">getInt1Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba5de75f50bb4a4ba920698edf39b28">getInt8Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87f56db834c58ca630624956ecf6972f">getInt16Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30dd396c5b40cd86c1591872e574ccdf">getInt32Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05186fa23e4d11b9855a9599ba87a4b7">getInt64Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ab2a65707a06849653fb5931411193">getInt128Ty</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ScalarTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab908d9ac4f123b5f676e1548c123820c">getScalarTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b425d59c7bc28a4a599cee0b9ed338">getFloatingPointTy</a> (LLVMContext &amp;C, const fltSemantics &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e4e0af5b02a410a87c9cdbcd1423b6">getWasm_ExternrefTy</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc56186d80974cb7f4928e9f0abf8904">getWasm_FuncrefTy</a> (LLVMContext &amp;C)</td>
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

<p>The instances of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> class are immutable: once they are created, they are never changed.</p>


<p>Also note that only one instance of a particular type is ever created. Thus seeing if two types are equal is a matter of doing a trivial pointer comparison. To enforce that no two equal instances are created, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> instances can only be created via static factory methods in class <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> and in derived classes. Once allocated, Types are never free'd.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### subtype\_iterator {#a5325d504915a0e903f78cd39bbc59bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Type::subtype_iterator =  Type * const *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>

</div>
</div>

### subtype\_reverse\_iterator {#a9a2deb3b1de1d324eedf109b42790524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Type::subtype_reverse_iterator =  std::reverse_iterator&lt;subtype_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### TypeID {#a5e9e1c0dd93557be1b4ad72860f3cbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Type::TypeID </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Definitions of all of the base types for the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> system.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HalfTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9"></a></td>
<td class="doxyEnumItemDescription">16-bit floating point type (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BFloatTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaaa889d8e26c8078095629a42d1f930fa7"></a></td>
<td class="doxyEnumItemDescription">16-bit floating point type (7-bit significand)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FloatTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15"></a></td>
<td class="doxyEnumItemDescription">32-bit floating point type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DoubleTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5"></a></td>
<td class="doxyEnumItemDescription">64-bit floating point type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_FP80TyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7"></a></td>
<td class="doxyEnumItemDescription">80-bit floating point type (X87)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP128TyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc"></a></td>
<td class="doxyEnumItemDescription">128-bit floating point type (112-bit significand)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC_FP128TyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48"></a></td>
<td class="doxyEnumItemDescription">128-bit floating point type (two 64-bits, PowerPC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VoidTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520"></a></td>
<td class="doxyEnumItemDescription">type with no size</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LabelTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa66db5616b8f6b2cfe991861905747783"></a></td>
<td class="doxyEnumItemDescription">Labels</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MetadataTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaad3b3756c598c8acc2d002f5f9a2c1d04"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_AMXTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa0abcabf751e05ec079d5907fc0733c65"></a></td>
<td class="doxyEnumItemDescription">AMX vectors (8192 bits, <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> specific)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TokenTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaae01900ccd0d696ce7ede9d710415f162"></a></td>
<td class="doxyEnumItemDescription">Tokens</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntegerTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249"></a></td>
<td class="doxyEnumItemDescription">Arbitrary bit width integers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FunctionTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa0ec130d9ce9883b3e9c6071ee19a4b16"></a></td>
<td class="doxyEnumItemDescription">Functions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PointerTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff"></a></td>
<td class="doxyEnumItemDescription">Pointers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StructTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156"></a></td>
<td class="doxyEnumItemDescription">Structures</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ArrayTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554"></a></td>
<td class="doxyEnumItemDescription">Arrays</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FixedVectorTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d"></a></td>
<td class="doxyEnumItemDescription">Fixed width SIMD vector type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ScalableVectorTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6"></a></td>
<td class="doxyEnumItemDescription">Scalable SIMD vector type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TypedPointerTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa2a07a6a681a242e8fee0431f13b8c845"></a></td>
<td class="doxyEnumItemDescription">Typed pointer used by some GPU targets</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetExtTyID<a id="a5e9e1c0dd93557be1b4ad72860f3cbdaa44ac2c71ce3db287c4e73aca9ad04e44"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> extension type</td>
</tr>

</table>
</dd>
</dl>


<p>Based on this value, you can cast to a class defined in <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>. Note: If you add an element to this, you need to add an element to the <a href="#a8afb3494f6f22e80508f1945a2466052">Type::getPrimitiveType</a> function, or else things will break! Also update <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ga2da643b0ebe215106a07c8e03f3ad8d8">LLVMTypeKind</a> and LLVMGetTypeKind () in the C binding.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>

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
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a> and <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Type() {#a817dfd76b27697e96a20f80f7bb68251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Type::Type (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbda">TypeID</a> tid)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arraytype/#adcb3a90e2a542325f4ac76f7154be648">llvm::ArrayType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/cbufferexttype/#aa12009bac27260efedf4b8d31ac606ad">llvm::dxil::CBufferExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/feedbacktextureexttype/#aec57149ebf60f4786e455f487fbf9d74">llvm::dxil::FeedbackTextureExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/mstextureexttype/#a9fba25bddfd1525c8453c447151d48ac">llvm::dxil::MSTextureExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/rawbufferexttype/#ab1af4553580523adcfc968efe5df6e3c">llvm::dxil::RawBufferExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/samplerexttype/#a5a72c5ec681aa96c3638557e116051af">llvm::dxil::SamplerExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/textureexttype/#aa850179f68c5cda3366295f9ed426f9f">llvm::dxil::TextureExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/typedbufferexttype/#af759590e017edc579b273895cad44f36">llvm::dxil::TypedBufferExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#acf77cff1502d60be9249bc6ad9211812">llvm::FunctionType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#ab59df261f996b1ba5db42c653da1b1a3">llvm::IntegerType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8ec3ee498cc15a71a684a86aaf377ae1">llvm::PointerType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a045d43b7a18aec2cec079a3bde8ce16d">llvm::StructType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#af9a9b8ca7bec44a5b6c81d2e4684a58f">llvm::TargetExtType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#a646a1ced54139d90cfe3054d654e76c0">llvm::TypedPointerType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a433e8d0e9a8db766b9a458f18b11b7c1">llvm::VectorType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#af4d4bfb09d6c352cfd4373d1e71ff8c8">llvm::object::MinidumpFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a0d4dbd83b976a1e591bd54c45ecbb3bf">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#af335143f4a0fb6ac98d6102219f9795a">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a9a937399ee5b5885ffc2d7355ae96eda">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#af2bc88fa949977374572b32de0224b03">llvm::VectorType::get</a>, <a href="#a3fb19a71e602dce8ff646c3ac2f4ca0f">getArrayElementType</a>, <a href="#ad1d50278883f39969187bceabe068acf">getContainedType</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#aed75da684d36221f1f7b9fbf5aa3aed8">llvm::ArrayType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aee3c78d73273cb8449cd10cc15edcb83">llvm::StructType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#acb6777058bb3f8b8cb5c58d71eef10cf">llvm::TypedPointerType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="#ac59306eb826e349ac7429736b1506432">getExtendedType</a>, <a href="#ac9c20e4a8194779750a20ce5caef81f7">getFunctionParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/cbufferexttype/#aca1124785cfee59093aa5672213e0e8a">llvm::dxil::CBufferExtType::getResourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/mstextureexttype/#a61d8e8d3387d0e3c12d212aab3e24109">llvm::dxil::MSTextureExtType::getResourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/rawbufferexttype/#ae2c7f42df3d45f02c13e1aa45f8d5917">llvm::dxil::RawBufferExtType::getResourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/textureexttype/#a3afd837eeffecf25b457144038c91242">llvm::dxil::TextureExtType::getResourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/typedbufferexttype/#a02f42a82e2970f1ca359aa86cae0a8fd">llvm::dxil::TypedBufferExtType::getResourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="#ab908d9ac4f123b5f676e1548c123820c">getScalarTy</a>, <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a>, <a href="#a15d34f8dc07013df378e0fb3d0134c08">getStructElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aa4a68dda48893ebd98fe7d4878ba0830">llvm::StructType::getTypeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4b50ac2e68c066aa61e2052a8c78aa37">llvm::TargetExtType::getTypeParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a83725435ece9bc12c40ceb34dbd1727c">getWithNewBitWidth</a>, <a href="#a8fa51d3da96615af400274e9cd272df4">getWithNewType</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#af746af1e4d44a9c48f3a1a69b804f73f">llvm::IntegerType::IntegerType</a>, <a href="#a2ff127c9924cd3337080c4445c324aea">isScalableTy</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/rawbufferexttype/#a3a7f8c574d915562235bc6750ebec816">llvm::dxil::RawBufferExtType::isStructured</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#a6a42316b1394fedfab01971ee1ea6ba8">llvm::TypedPointerType::isValidElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa6a2194fc011669faabe43322d7c6c5f">llvm::VectorType::isValidElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aa7ab521107c655d90b8cfac53b3170bf">llvm::StructType::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#aa9c4c07ef99ba2d1a627c98fdb4b7cf6">llvm::TypedPointerType::operator=</a>, <a href="#a91bbc1ac424839ba7e85d2d8542c288a">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp/#acc5b9e0eef6fe127531ff21cdf4a4320">skipModsAndTypedefs</a> and <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~Type() {#a09354645c72c44738278f80ca78f759f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Type::~Type ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canLosslesslyBitCastTo() {#a651563a742c52504d1980955fe75b95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::canLosslesslyBitCastTo (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this type could be converted with a lossless BitCast to type 'Ty'.</p>


<p>For example, i8* to i32*. BitCasts are valid for types of the same size only where no re-interpretation of the bits is done. Determine if this type could be losslessly bitcast to Ty</p>


<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a63540fe3243b44a62cb656c73274f8ac">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType</a>.</p>

</div>
</div>

### containsNonGlobalTargetExtType() {#a23e62ec586d4d045f4e0b7bfd1f04ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::containsNonGlobalTargetExtType (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this type is or contains a target extension type that disallows being used as a global.</p>

<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### containsNonGlobalTargetExtType() {#ae7b43432683c09a40d81b9b245a05565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::containsNonGlobalTargetExtType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>.</p>

</div>
</div>

### containsNonLocalTargetExtType() {#a2f0388b8315300b55a8833caf090ef71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::containsNonLocalTargetExtType (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this type is or contains a target extension type that disallows being used as a local.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#ae662f556252fe75768094c7976518409">llvm::sandboxir::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a62425c077bf32e483e2e041e26bce530">llvm::VectorType::getSubdividedVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a5d72c7051da5356cbfbfa16ecb7dca8a">llvm::sandboxir::Context::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a330bbaf89b90196df6960be4724513c6">llvm::sandboxir::Type::LLVMTy</a>.</p>

</div>
</div>

### containsNonLocalTargetExtType() {#ae77d4c2d7f8556667a38ab71c72cb54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::containsNonLocalTargetExtType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#ac423a4165a8f57cd2865ef33dd9be484">llvm::VectorType::getDoubleElementsVectorType</a>.</p>

</div>
</div>

### dump() {#a90c89709fd5e5e1d96455aec8b0c3916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Type::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 5319 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a90c89709fd5e5e1d96455aec8b0c3916">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="#a90c89709fd5e5e1d96455aec8b0c3916">dump</a>.</p>

</div>
</div>

### getArrayElementType() {#a3fb19a71e602dce8ff646c3ac2f4ca0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getArrayElementType ()</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">ArrayTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a96d2037eb473457f3222e5cbe7ea22b5">ContainedTys</a>, <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a27fa222a6e3552cda42becaf041aafec">llvm::ARMTTIImpl::getNumBytesToPadGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a711350a8af2fb95f4f1ca8cb7fa79374">llvm::WebAssembly::wasmSymbolSetType</a>.</p>

</div>
</div>

### getArrayNumElements() {#a5cfdb1cd5ccaae5daa8e4b29b3bb6b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::Type::getArrayNumElements ()</td>
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



<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>.</p>

</div>
</div>

### getContainedType() {#ad1d50278883f39969187bceabe068acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getContainedType (unsigned i)</td>
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

<p>This method is used to implement the type iterator (defined at the end of the file).</p>


<p>For derived types, this returns the types 'contained' in the derived type.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a96d2037eb473457f3222e5cbe7ea22b5">ContainedTys</a>, <a href="#a679d8ea00092eb9cd392643bb2d1b7f9">NumContainedTys</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a294b49713de411cd8aadad66d82f205b">anonymous{ConstantFolding.cpp}::ConstantFoldStructCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a>, <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4b50ac2e68c066aa61e2052a8c78aa37">llvm::TargetExtType::getTypeParameter</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aee075a4b7e853e004ad694f7ef959f28">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractValueInst</a>.</p>

</div>
</div>

### getContext() {#a909eca4ba9e5eefc203c8e3770bdab25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::Type::getContext ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> in which this type was uniqued.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a351251756a2dcf559089f626d9241131">llvm::VNCoercion::coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ad06dcf793a8b91871327c682d6f3f909">llvm::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a7ae16889db439f8fbb234fe3de672d11">llvm::VFABI::createFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ad035539cf7c551ab8d10af8a3a6c0f00">llvm::MatrixBuilder::CreateIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a78f018d0c5133b2d60d092d68f6b046b">llvm::orc::createIRTypedAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a08c03a4228af93098afb6ab60e7283f6">foldConstantCastPair</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#af335143f4a0fb6ac98d6102219f9795a">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0af04c89840d424b7b33ae71d7c8cd28">llvm::ConstantExpr::getAlignOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#aa4b66161f15587adee19725b89fec713">llvm::VNCoercion::getConstantMemInstValueForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a4910f3acf596de7348ca70c0b41b0040">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getExtendedReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a70eadaa7bf647a939fa6a673c7467fa3">llvm::IntegerType::getExtendedType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a6b72d403292d9dddd1ef1ce3e8bc394c">llvm::VNCoercion::getMemInstValueForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a712be2c47b7dea0b22073dde0cf48fdc">llvm::RISCVTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a16a2910025aeadfd52f381a78f92faf0">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getNumberOfParts</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a6b9321187f70bb8fc4c103af466f6c21">llvm::X86TTIImpl::getReplicationShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a05bf02ad372b0e58afd80f2378cfac94">getResRetType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#ae7c1fa2a94f420cac743955c3db73b28">getReturnAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3c16ae9b6c38652cd59f72eeecc4e176">getReturnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#aba994389c740a90705e8995aa61e609e">llvm::CallLowering::getReturnInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a005211a6c7f26317af98d088c06f0f64">llvm::AArch64TTIImpl::getSpliceCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a8980bac40df22db2e293fd48b13a3b76">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getStoreMinimumVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a43ab95f8d1cfe32b5c75a4d4d666d89c">llvm::VNCoercion::getStoreValueForLoadHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a75880fa01f2a6719716b1e3ac002f40e">llvm::ARMTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abc0c3e45d7d6be3fd7f5038a7e9e16de">llvm::RISCVTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a05cf907fc03e5b3f599a3dbd02c55803">llvm::RISCVTTIImpl::getVectorInstrCost</a>, <a href="#a83725435ece9bc12c40ceb34dbd1727c">getWithNewBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a7f7861a70cfa57999c2b47e570be2127">llvm::ValueAsMetadata::handleRAUW</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a78ca5c76a5ac76f5ad51ce5ced36fbb8">llvm::CallLowering::insertSRetIncomingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a852a45fa0766bf5cb65ea6010d32330a">llvm::CallLowering::insertSRetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a9780ca905174166ea524a30801e7e69b">IsIncrementNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a202c702ced6d0c47a226adf851aba6eb">IsIncrementNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a7fd9ee96f281dd94ed4119c2e45836bf">isIntegerWideningViable</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5a707ef219e51df6fbaff782ed1d44a6">llvm::X86TTIImpl::isLegalBroadcastLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#acdb094fc50fe7940c520020f9008aa2f">llvm::RISCVTargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6469b3ca28c7c2752a9370a1f6ff4fd5">llvm::isUntypedEquivalentToTyExt</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a525e9355bccd735cf648afbde45acfc5">llvm::SparcTargetLowering::LowerF128_LibCallArg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0206e74dec02d952d1b620a7b63f5694">llvm::CmpInst::makeCmpResultType</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a4055f1bab55c76c243c3bf42c1a7e45a">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::needToDelay</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a520d2b97d6b2eb0958cc182161938cd1">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a0b50be89487f7186a5eb7ff1bc82efc0">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapVector</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a9910dce4a3e020d503a0e4062d66646f">llvm::GCNTTIImpl::rewriteIntrinsicWithAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab32574e30e8d85eaa2f692d8fc3c6766">llvm::ARMTargetLowering::shouldConvertSplatType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8ef0473fe81ed643d4fe2e64c6a5b3e">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::shouldReplace</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/wasm/#af399440b56a4fd5fa0af52bdb1bc8243">anonymous{ExpandVariadics.cpp}::Wasm::slotInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af3d7a362fea3dd362c790529f2afcbfa">llvm::toScalarizedStructTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77e211e8fb596ed21bb29f80aeacc211">llvm::toVectorizedStructTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a> and <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#aa8f5b66c1e3e1c2f0740764818920442">llvm::MetadataAsValue::~MetadataAsValue</a>.</p>

</div>
</div>

### getExtendedType() {#ac59306eb826e349ac7429736b1506432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getExtendedType ()</td>
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

<p>Given scalar/vector integer type, returns a type with elements twice as wide as in the original type.</p>


<p>For vectors, preserves element count.</p>


<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a3b1f5f847d812d85eaaa8a19bd01bcf4">llvm::VectorType::getExtendedElementVectorType</a>, <a href="#a34ee40bb2f4f5ece47ef19e5f1f57e3c">isIntOrIntVectorTy</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a0182cdf55f9bfbdd904e3f5e6802316a">llvm::IndexedReference::computeRefCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>.</p>

</div>
</div>

### getFltSemantics() {#adc21598ac33ea9d50f3a939f26a28940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; Type::getFltSemantics ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a79061cbffefa2eccfe0d30d1c07eed78">FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>.</p>

</div>
</div>

### getFPMantissaWidth() {#ad9b99a13e459cb18bb386ddd610ecf8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Type::getFPMantissaWidth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the width of the mantissa of this type.</p>


<p>This is only valid on floating-point types. If the FP type does not have a stable mantissa (e.g. ppc long double), this method returns -1.</p>


<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aac5576a66149a9259706758d613ba555">isKnownExactCastIntToFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a2f20b406ad481a5f9d33949e4ccd9f05">shrinkFPConstantVector</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>.</p>

</div>
</div>

### getFunctionNumParams() {#ae7242fc7f3fcad5795e277521414c154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::getFunctionNumParams ()</td>
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



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>

</div>
</div>

### getFunctionParamType() {#ac9c20e4a8194779750a20ce5caef81f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getFunctionParamType (unsigned i)</td>
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



<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>

</div>
</div>

### getIntegerBitWidth() {#a13e877ef779ba7a0688081079f4f9b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::getIntegerBitWidth ()</td>
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



<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#ac9683831e3a4c794ca05bf81af366e5e">canBeCheaplyTransformed</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a6c2f0057515e3f4b8e14cfb9dcb789ae">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertToBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#a045f5491e24124a1ee6f454e5119c38c">generateSignedDivisionCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ab15480fad5e956eadbf7c6fa518c642e">generateSignedRemainderCode</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ad4522ba73eb89ae20c7ca46349303f3e">llvm::PPCTTIImpl::hasActiveVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ae965d93aa46ad834c21718eba4b5b78e">hasSameExtUse</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9e49f6fa199d88e91bf282cf91e34740">llvm::X86TTIImpl::isLegalMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4ae03ad8a100596487ddf6bd448090f0">llvm::X86TTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#ac685ec5a094330e0ce1e86c573a2e934">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::pushCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad96e48f13961854d2242e9462a920394">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a5e2b7ac5f48193117a340aa15b085719">llvm::OpenMPIRBuilder::unrollLoopPartial</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#af8fd85d6783b4f0fbb5f4a8d6bf40bdc">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithCastInst</a>.</p>

</div>
</div>

### getNumContainedTypes() {#a66d610d816ff0a14e8ac599dcaefd2c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::getNumContainedTypes ()</td>
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

<p>Return the number of types in the derived type.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a679d8ea00092eb9cd392643bb2d1b7f9">NumContainedTys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a5ebd93e1bf92a594083043a9180e9908">llvm::TargetExtType::getNumTypeParameters</a>.</p>

</div>
</div>

### getPointerAddressSpace() {#a5ab2d0b0f0b8ceec3b907184e7567197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::getPointerAddressSpace ()</td>
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

<p>Get the address space of this pointer or pointer vector type.</p>

<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuaaresult/#a268b9527fc2ecbb486822e53d18f90ca">llvm::AMDGPUAAResult::alias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aebd8fb1e50c14f4988226de940a067ed">annotateNonNullNoUndefBasedOnAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a81fe9e08548be6c5618ecc7213d285e3">aspaceWrapOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#af10eb6aece68a8127f273e6a2dc0fc79">llvm::VNCoercion::canCoerceMustAliasedValueToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a2fb1c078833c17e4c9529b0cf924385c">canConvertValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#ac6745cfa7af2beebe88a7d3609c7875d">classifyGlobalCtorPointerType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#aba29b35909e39c48517e7475412c776a">anonymous{PointerTypeAnalysis.cpp}::classifyPointerType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aaa5acf165c5a3bec2ff360c59f2f9448">llvm::orc::cloneGlobalAliasDecl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a38a01001593bf75700ee024b15bdf413">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialFromPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af169f594f2c9e8cd49a59b29373eb4de">convertValue</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a1536669cae3776862c9ed0a566595b7d">llvm::CastInst::CreatePointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35f13ead4222c0c45fb21f7e63025bbc">llvm::expandMemMoveAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7f4680b383ce7138bc2c12de282b14b4">getAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#a69434c1c574013fb2765bd2c5b27cc7b">llvm::IntToPtrInst::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#ac9234105b582bbe087981c231eb7b292">llvm::AddrSpaceCastInst::getDestAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a77912b33da00edf1cb4143f66890519b">llvm::RISCVTTIImpl::getIntImmCostInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a7159508155406ad5c350cc429980e09d">anonymous{AttributorAttributes.cpp}::getKnownNonNullAndDerefBytesForUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#acddb0d15dc6d53316188968e5acbefc7">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getNonKernelsWithLDSArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a2c33b15661e7fc5f6f1ae9bc1004744a">llvm::AtomicCmpXchgInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#af39e1cad69b6406376c47e4b111228dc">llvm::AtomicRMWInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#af6bfe9ceb9bb512348d3602935a747f2">llvm::GEPOperator::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#aff00c57a3501815064e3e2486f1abbdd">llvm::GetElementPtrInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a161c2db145827f4e181e7fe662b53a81">llvm::LoadInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#a378cf64c77de950ae67fc6e279e34620">llvm::PtrToIntInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#acc30ca5b0dba4e43b5a9dc65153fe573">llvm::StoreInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a1f469b1f703519ae25ce564c8704310f">llvm::ConstantExpr::getPointerCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#ab292fdaede434f81cf224662e9de7e35">llvm::AddrSpaceCastInst::getSrcAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastoperator/#a6239a1c5f8bc81d1d3b77b7f338a6342">llvm::AddrSpaceCastOperator::getSrcAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae2ebbbbc990e3d932da5d0d0ea255f42">HandleByValArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a047890dfe94355c41e98c0b8561b9f14">handleSpaceCheckIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#af001e6326d49bf139dfeee21772f01f0">inlineGetBaseAndOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af414e22c02fcc9ff3ce2d81ee8d3cfcb">llvm::AMDGPU::instrumentAddressImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1f2a3f39b7febd40285065a7ed05b71d">llvm::AA::isAssumedThreadLocalObject</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af7b88a2a7449e4edc75721e2ab686d9e">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::isDependenceDistanceOfOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4cacf18e8e9ecebd3f912ae0ad4e3817">llvm::AMDGPU::isDynamicLDS</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8b805c54dc1ead67b711a4b1cb72f492">llvm::CastInst::isEliminableCastPair</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoalias/#a0a95494aa0152eb057e6e9ca25572f87">llvm::AANoAlias::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad96e48bda36fb8540a3973cee993c5b3">isKnownNonZeroFromAssume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9a6f055381f5a946e37ab4d9e4a221d8">llvm::AMDGPU::isLDSVariableToLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a44232befb736ff8d861bd991a5a68239">isNoopPtrIntCastPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a66fb0770ddf5f596079ee32ca4b8b599">isUnsupportedAMDGPUAddrspace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#aa41b5e7a1b162b70c1b4ce419b0c0f25">anonymous{AttributorAttributes.cpp}::makeChange</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaddressspaceimpl/#a53cdd0197a337c06817844761012a6e0">anonymous{AttributorAttributes.cpp}::AAAddressSpaceImpl::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac46926a2483bd793432d5ca0f7879de3">maybePrintCallAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a13c72931678c2da267fc265c7a2afdfb">optimizeOnceStoredGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a9910dce4a3e020d503a0e4062d66646f">llvm::GCNTTIImpl::rewriteIntrinsicWithAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxttiimpl/#a2c490533c8b0e3198460793c9d739f5a">llvm::NVPTXTTIImpl::rewriteIntrinsicWithAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/threadsanitizer-cpp/#a0bb37c4d9d72e23c0da8cafdb59f466a">shouldInstrumentReadWriteFromAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a0fd3732392fdbdbc5a4436c0f1262999">anonymous{InlineCost.cpp}::CallAnalyzer::stripAndComputeInBoundsConstantOffsets</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5352cd5bd63b8038b094b324190f3a8a">llvm::UpgradeBitCastExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac20eb5c6ac0036298cbfb44d3b9cc82">llvm::UpgradeBitCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a900ef0957c31205735317d246eb68f7c">anonymous{MergeICmps.cpp}::visitICmpLoadOperand</a>.</p>

</div>
</div>

### getPointerTo() {#adc01a7457de85fc52a3bb860d7e1c6a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * Type::getPointerTo (unsigned AddrSpace=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pointer to the current type.</p>


<p>This is equivalent to PointerType::get(Ctx, AddrSpace). TODO: Remove this after opaque pointer transition is complete.</p>


<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### getPrimitiveSizeInBits() {#a833daf718a49c5cd637d8c9ddeaebe07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize Type::getPrimitiveSizeInBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the basic size of this type if it is a primitive type.</p>


<p>These are fixed by LLVM and are not target-dependent. This will return zero if the type does not have a size or is not a primitive type.</p>


<p>If this is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>Note that this may not reflect the size of memory allocated for an instance of the type or the number of bytes that are written when an instance of the type is stored to memory. The <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> class provides additional query functions to provide this information.</p>


<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adaf74e11d3b6f4feaee9dd7711e92202">llvm::ARMTargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a6b5e20840f3da6bd17be57947204f8c9">llvm::HexagonTargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9c91bde4107b00ee5520f121253437ef">llvm::X86TargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#af57aa964441f0796b3d49de878edaca5">areExtractShuffleVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad07ba9d946b424c9de4782f4ae7879bb">llvm::ARMTargetLowering::canCombineStoreAndExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a78d37997d6b920824dbdec1ec1213bc5">canWidenLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvegatherscatterlowering-cpp/#a7393bb18a6b67be8b26127bd4aab0cd4">CheckAndCreateOffsetAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a01395be91e03a1a4c5fd713885d8327f">collectInsertionElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a40a1fc4e57a69c562fb3d215eaa71280">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertBlendvToSelectMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aa49cf0e393f7067f09985cec1d4b7387">convertStrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a93b7c4ad8be280f28707e920e5f3a41e">createCmpXchgInstFun</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62d6d0e38b12746870f6996e60f42d3">llvm::DecodeVPERMIL2PMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae64455568f4dbe957082221523e72000">llvm::DecodeVPPERMMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a42c33c78c903c369b359db824b70cb1b">foldIdentityExtractShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5f05216ba8b34865b434e7fc8c96d9d4">llvm::ConstantDataSequential::getElementByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a04b3a69fabb49a792bdd785030325f89">llvm::HexagonTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a8d7f8a73873448dc2bae97e066450dba">llvm::NVPTXTargetLowering::getPrototype</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a17e35fd9a6e590c201fd05105589ce47">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a694f0a06fb32a28862ef184803eaadd8">llvm::SystemZTTIImpl::getVectorTruncCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aa2915714199e899f7766d49f87ec2ad6">llvm::CastInst::isBitCastable</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a21cc5fb76556bf28338074b4c40695db">llvm::ARMTTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a01cb590e9c05c3675fe75693d84b3120">llvm::AArch64TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a766bc050b0a294104d02f41e0047e0ba">llvm::ARMTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a5ac204c71b6c7eefceba4fdcbf6a4a79">llvm::MSP430TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a7da11befe36636d6aad466b8e0483311">llvm::NVPTXTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0c9601934baa227ce802de96110b47bc">llvm::PPCTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a1daa5bda35eacba5b0b1d532bcf0327f">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aa537392c1f43f9b471c6cb9dead13df7">llvm::SystemZTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aabf943e7fc68b0048d5278b5a35da3a9">llvm::X86TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a9140f89a634da6fe469d0faa0843a976">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a160d793aacc4ffadcdf86eddbf401c69">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Lower64ShadowExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a95f58fa5cb1c9a72e5ea815a5036a2e4">printConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a0dc93812c8d212376dd405df5f029d5c">rebuildSplatCst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a7688327ace78b50a63838075de9c2168">rebuildZeroUpperCst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a70a83c8d008bb40c08c02d3238a992a3">llvm::AArch64TargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac4b5d6d1333be49386e35e56c28647fe">llvm::ARMTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a2f3b0d090892cc5dd71222862723e231">llvm::LoongArchTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#acf15eefe45c9e2c4a90a40a7a9a779f3">llvm::PPCTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a9f599da93ccc12e05a0126cfdc57b885">llvm::RISCVTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a62ca2fe454c98ca30dd17d0b37ba3534">llvm::AArch64TargetLowering::shouldExpandAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0a17ad44231dd559dedb8ff61bcfe29e">llvm::ARMTargetLowering::shouldExpandAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a4623112d6a3de641f2af75604341bc64">llvm::HexagonTargetLowering::shouldExpandAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6ed1fafeaecc08fe13e54b080e259dd2">llvm::ARMTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a5916c5a40e28fd6b62ec267bfe57e43d">llvm::LoongArchTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5047a95accb91898b9135182491d547c">llvm::PPCTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a07b54d60a81306d5f8c4f12fe8d0cb">llvm::RISCVTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a29137845e271a0520a8f1c3c397faf50">llvm::SparcTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad9d7a82ba140ac920458705124372cd6">upgradeAVX512MaskToSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aa4e6667108e3ef2a76f536bd8f5e93e6">upgradeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#a5ed4aebc49d7a699dc40a248391f0ac1">anonymous{BasicAliasAnalysis.cpp}::CastedValue::withSExtOfValue</a> and <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#a096cb21b10c3d48f35a912947974c872">anonymous{BasicAliasAnalysis.cpp}::CastedValue::withZExtOfValue</a>.</p>

</div>
</div>

### getScalarSizeInBits() {#a9f382207d841377156d4c7868b66b9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Type::getScalarSizeInBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a vector type, return the getPrimitiveSizeInBits value for the element type.</p>


<p>Otherwise return the getPrimitiveSizeInBits value for this type.</p>


<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a379666f1f08149bf9e4dabcb430aee93">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::calculateConvertType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1347d52f024418efd43a77e0fcb57355">llvm::InstCombinerImpl::canonicalizeCondSignextOfHighBitExtractToSignextHighBitExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a61e3236cbe0cbc94e306beb52ae1093d">canScalarizeAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a7b6c32da7b6a47b962a5bdce5a3bbc75">canTryToConstantAddTwoShiftAmounts</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvegatherscatterlowering-cpp/#a7393bb18a6b67be8b26127bd4aab0cd4">CheckAndCreateOffsetAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a7805b21c1397d70002fd216481351f5e">llvm::VPWidenSelectRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45c454aff5d0478a70219bb15d369b3">llvm::ConstantFoldIntegerCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8f832cfa0e0121c6fd066c0f3b25f5f">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertToOptType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadb1772c1026a517d15c771ceb6a91ca">llvm::copyRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0e2de2c034e3083d006b92ddf14b8bcf">llvm::OpenMPIRBuilder::createAtomicWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a85da0abb1e43779210427c14a9bd9311">llvm::IRBuilderBase::CreateFPCast</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ad035539cf7c551ab8d10af8a3a6c0f00">llvm::MatrixBuilder::CreateIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#acc518623c0b37b3586bc69a967ec83bc">llvm::MatrixBuilder::CreateIndexAssumption</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aeff5766c114e19126ba79be81e93fcd1">llvm::CastInst::CreateSExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a526b09d26d2114c5fb83b459ceb2cd4a">llvm::IRBuilderBase::CreateSExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeb11a01107c6be1f52ba01902a165d71">llvm::IRBuilderBase::CreateSExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae934d6e99e0516d606ae8e65ff6aed63">llvm::IRBuilderBase::CreateStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aab3f4e42107a79ae5939cd350e77b834">llvm::CastInst::CreateTruncOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ade4ee38419ac3921c718b634571033e4">llvm::IRBuilderBase::CreateTruncOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ad120ee39de5a92d1581ba9a5e1072296">llvm::CastInst::CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0032ae544ae429aaf1053767da90426d">llvm::IRBuilderBase::CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a36742c35a8fff5f74bb3d76c9c19dd47">llvm::IRBuilderBase::CreateZExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#abe3945bfefe671a9a34f864d493d5fe7">decompose</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a79061cbffefa2eccfe0d30d1c07eed78">FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a5a46b94b8be40eba6d85169820f2a3a4">foldBitCeil</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a157d508026592d1fdb9c78a3c3d34a06">llvm::InstCombinerImpl::foldICmpTruncWithTruncOrExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7caf9cd5dff4734b8af500d6f0f07437">llvm::InstCombinerImpl::foldICmpWithTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78d5bb4c6437373debabeb3f816645cb">llvm::InstCombinerImpl::foldItoFPtoI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aa231edc47a3993eaf9c7aa2bb324e2f5">foldSelectFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a53cf44ef1c7130fc18add1138c045484">foldSelectICmpAndAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1f737dab05d29dca38561bc99b9ef5b5">llvm::InstCombinerImpl::foldSignBitTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a747cca8cf8e4c4e41b81bb1cbf146a11">foldTruncShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a54ea77d9e8070a1a18b224d984b12c1b">llvm::TargetLoweringBase::getBitWidthForCttzElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a5d6281f602a2d61050f8e8214c34b16e">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getDivNumBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a2f0f3c8ae1e70783849672eb85b035fc">getElSizeLog2Diff</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a90962d11b5a501962b1005faf5ab5a29">llvm::RISCVTTIImpl::getExtendedReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a70eadaa7bf647a939fa6a673c7467fa3">llvm::IntegerType::getExtendedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a8a65916cd3a5fe149b7cee7a978a80eb">getHistogramCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a9761430bcfb8f1f8317f6f91c6a160da">llvm::GCNTTIImpl::getLoadVectorFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a712be2c47b7dea0b22073dde0cf48fdc">llvm::RISCVTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a1fa63b37ad2ac06f289e9962a3703e9e">llvm::LoopVectorizationCostModel::getSmallestAndWidestTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a75880fa01f2a6719716b1e3ac002f40e">llvm::ARMTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#ac9187fccb0fa44ecfef081f99dd17029">llvm::SystemZTTIImpl::getVectorBitmaskConversionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a513e1873d7e7760f5e0241cc47a9aaca">llvm::PPCTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a05cf907fc03e5b3f599a3dbd02c55803">llvm::RISCVTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a694f0a06fb32a28862ef184803eaadd8">llvm::SystemZTTIImpl::getVectorTruncCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a091f96b1bcdc804092ddc7b24b2184">llvm::getWiderType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ac03d3c26f38bacbd611de31932ef80b4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorSadIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8b805c54dc1ead67b711a4b1cb72f492">llvm::CastInst::isEliminableCastPair</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a710fc966df72f9cae9f17ec7eb76f5e8">llvm::SystemZTTIImpl::isFoldableLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a36ca78229b46f9e53eb095d48647cdf3">llvm::AArch64TTIImpl::isLegalBroadcastLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a21cc5fb76556bf28338074b4c40695db">llvm::ARMTTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ace4c7b4bc6aba9506b1b60aac18881f3">llvm::CastInst::isNoopCast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a69fb974494d6177f9c3ab043222b7fdf">llvm::AMDGPUTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a84e23075cb31b3959abf7b6022a0884f">llvm::AMDGPUTargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a5d31f8dc135425bc0f938f13bcca4a0a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::loadMatrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a9e6840885acb4ffa3e94e81a70b392fc">matchOrConcat</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a6b456d582237b235a7f387d11e56c2bc">llvm::TargetTransformInfoImplBase::minRequiredElementSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8ef0473fe81ed643d4fe2e64c6a5b3e">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::shouldReplace</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a842c12e686e91a515dfd30a4bf70d740">simplifyRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a40bdb7ed86f1fdb139eb9fd73b05405a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::splitVectorElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ac9fae87b41835eff9f16de8aa6b11239">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::storeMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4af4fe6392d3860167eafedc817ed8b1">llvm::Constant::toConstantRange</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad9d7a82ba140ac920458705124372cd6">upgradeAVX512MaskToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9567d315d63f844326900f461f5b3d7a">llvm::InstCombinerImpl::visitIntToPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a180c318fe2fe1f2f7d4f4ca4dccfd2f1">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntToPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5b6ac7240be29b8a3a611a734a45d4a6">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### getScalarType() {#a7c742b32ebcd73d6dc851afac295b0f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getScalarType ()</td>
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

<p>If this is a vector type, return the element type, otherwise return 'this'.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ad1d50278883f39969187bceabe068acf">getContainedType</a>, <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a>, <a href="#a1bc022868b23918efa44df511f4d5b61">isVectorTy</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#ab7c3af18d8706c2d91fd7e2f88424336">llvm::VNCoercion::analyzeLoadFromClobberingMemInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#abe54f9c905611b1e6439acf843ea29e8">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::applyFractPat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#af10eb6aece68a8127f273e6a2dc0fc79">llvm::VNCoercion::canCoerceMustAliasedValueToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a2fb1c078833c17e4c9529b0cf924385c">canConvertValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6f4eef604ff06e2b83fabf52e828c709">anonymous{ConstantFolding.cpp}::CastGEPIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7032e1ab44275cf7331a7898a3713aad">llvm::slpvectorizer::BoUpSLP::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d58e0e9c2196e30a314dbc5d3431524">llvm::ConstantFoldLoadThroughBitcast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a294b49713de411cd8aadad66d82f205b">anonymous{ConstantFolding.cpp}::ConstantFoldStructCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae3a4c284255a153d29ddcbd05bcf5345">createExtractVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae934d6e99e0516d606ae8e65ff6aed63">llvm::IRBuilderBase::CreateStepVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#ab8ffe62be4273e6e7903125e60943b0d">createTypedBufferStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67aa349e8bb1aefc2a8a6ca18be9b87c">llvm::emitGEPOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a06358c30f3e98d9e57f4ae9162f33c72">evaluateInDifferentElementOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae34cc912a530c92d78f60d912ebf3fc1">expandFloatDotIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7d02bfd7df1433b9ff3e6e237aed1e00">expandIntegerDotIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a79061cbffefa2eccfe0d30d1c07eed78">FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24fb14e02fa8e4a261838b46074e42fa">llvm::AArch64TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a5e5d97b679ac5ed7ad7f5b4639c450d7">getCmpOpsType</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#aa55e1630a0d0f515bb43b6e9c04b8cd8">llvm::ARMTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#af41ea97386e5b3aab125935caf351bb5">llvm::ARMTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#af44a0d4c944c50fe30fad03d97e9f66f">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a1d270f02c1f9186ea7961768be1269a7">getOneFP</a>, <a href="#a5ab2d0b0f0b8ceec3b907184e7567197">getPointerAddressSpace</a>, <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#ae962144c6afe1f7ebe533f328722d59c">llvm::SystemZTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abc0c3e45d7d6be3fd7f5038a7e9e16de">llvm::RISCVTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a27bfcb3dd99fa7a7ca8dc24eeac6e8e6">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a513e1873d7e7760f5e0241cc47a9aaca">llvm::PPCTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a05cf907fc03e5b3f599a3dbd02c55803">llvm::RISCVTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a3bdf014154b31cd5813672cbcd3af604">getZeroFP</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ad4522ba73eb89ae20c7ca46349303f3e">llvm::PPCTTIImpl::hasActiveVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ae965d93aa46ad834c21718eba4b5b78e">hasSameExtUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a548c5b4779101e84af6a92e2548be083">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAMDGPUAddress</a>, <a href="#ad0709baa705ae62c4e09cdd47fb4b420">isFPOrFPVectorTy</a>, <a href="#a34ee40bb2f4f5ece47ef19e5f1f57e3c">isIntOrIntVectorTy</a>, <a href="#a0cd5a11bf5ca1fba6c858d3d59ea6a35">isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4ae03ad8a100596487ddf6bd448090f0">llvm::X86TTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="#ab03652069eab17006c51f00c261a6a44">isPtrOrPtrVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac04b69adb2b2657b80c8e86eb8e04099">llvm::HexagonSubtarget::isTypeForHVX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a66fb0770ddf5f596079ee32ca4b8b599">isUnsupportedAMDGPUAddrspace</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4275af81cdeb1801deeae02ea2a0fb3b">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerBufferStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a30b2570b289c65776a16666bd087c988">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerRawBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a70502c89919d53c74320c78b78d5c282">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerTypedBufferLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a5c59325f9c3c1526f4439392c892fd41">optimizeCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a97c8c57e973ff87b44455c5d47d41770">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::rescale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52cff5d33f36f7d74476e993b0118f58">rmwOpMayLowerToLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab32574e30e8d85eaa2f692d8fc3c6766">llvm::ARMTargetLowering::shouldConvertSplatType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/threadsanitizer-cpp/#a0bb37c4d9d72e23c0da8cafdb59f466a">shouldInstrumentReadWriteFromAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a77aac577d89abc9411adfdf918d7d539">shrinkInsertElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a86163cb169435641156cbc611072c931">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vbytes</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a09b9488bfc0aa55fe37ace2bb46745d5">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vlsb</a>.</p>

</div>
</div>

### getStructElementType() {#a15d34f8dc07013df378e0fb3d0134c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getStructElementType (unsigned N)</td>
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



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abc0c3e45d7d6be3fd7f5038a7e9e16de">llvm::RISCVTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a1ecff7a038229dccedd3fb1aba929059">simplifyX86addcarry</a>.</p>

</div>
</div>

### getStructName() {#a4d0a50f63402f509e3f6c62a6c513fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Type::getStructName ()</td>
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



<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aac0431719235a7ccda58a3df4894d130">llvm::SPIRV::lowerBuiltinType</a> and <a href="/web-llvm/docs/api/structs/false/gepnode/#a8702875a47c894f09fb5b7f502b0b1f4">false::GepNode::operator&lt;&lt;</a>.</p>

</div>
</div>

### getStructNumElements() {#a58e54adaa7672bbf72091254a5391137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::getStructNumElements ()</td>
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



<p>Declaration at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a>.</p>

</div>
</div>

### getTargetExtName() {#a757dc51e994d986d1b9f8211f6390b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Type::getTargetExtName ()</td>
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



<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>

</div>
</div>

### getTypeID() {#ac7b0ed5c6d30bad74769c6e87ab0edb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeID llvm::Type::getTypeID ()</td>
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

<p>Return the type id for the type.</p>


<p>This will return one of the <a href="#a5e9e1c0dd93557be1b4ad72860f3cbda">TypeID</a> enum elements defined above.</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a45ff90e525c3f3879a1a7f5297d8857d">llvm::VPReductionRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="#a3fb19a71e602dce8ff646c3ac2f4ca0f">getArrayElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a1d270f02c1f9186ea7961768be1269a7">getOneFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a8d7f8a73873448dc2bae97e066450dba">llvm::NVPTXTargetLowering::getPrototype</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a3bdf014154b31cd5813672cbcd3af604">getZeroFP</a>, <a href="#a73e097994740799690554ad4b76f0ccd">is16bitFPTy</a>, <a href="#a8cbe006c6c069502d37891c438847c23">isAggregateType</a>, <a href="#a2a394517076e7dd2bdcd7dde33dfcb7d">isArrayTy</a>, <a href="#a468e032827ddcd10a8608e08a61323aa">isBFloatTy</a>, <a href="#aa0fd6bf3d33236279db7b707bba755f4">isDoubleTy</a>, <a href="#a82a7e98c00f5bb12e2c5481fe0ab3f1a">isFirstClassType</a>, <a href="#aac5759c83abd6a4af236401a7cfe7a0f">isFloatingPointTy</a>, <a href="#a3ffc75c3a4cb82ba307a3334483eb4ac">isFloatTy</a>, <a href="#a6f174fc924aa9cccf2abce5ef4b5ec9a">isFP128Ty</a>, <a href="#aba930e0564c4207f112d9243eb2fc13a">isFunctionTy</a>, <a href="#a8cf1f36cc41c466e66d6467e40554841">isHalfTy</a>, <a href="#ad696083ef7553304ab42e6d3667942e0">isIEEELikeFPTy</a>, <a href="#ac6d28a9b11139182134a9618028a0d07">isIntegerTy</a>, <a href="#a332975f1fb88675058c22029696c991c">isLabelTy</a>, <a href="#afb3adb81d6f38168542fa408efa365d8">isMetadataTy</a>, <a href="#a7fcf2946847a73b99dc54ea4203d3eb7">isMultiUnitFPType</a>, <a href="#a3b996fbf8458aafffc86cb98a68d0a47">isPointerTy</a>, <a href="#a670980c63f2e5ca39022baf96173eb9c">isPPC_FP128Ty</a>, <a href="#a8ad67a33bae235fe3cca1c3e5a91ed2d">isSized</a>, <a href="#a81eef9d7336f7ee43be79630d8e8ec86">isStructTy</a>, <a href="#a8536986ed6c44fce15dba30748428d2c">isTargetExtTy</a>, <a href="#ac9542ee3a689ae9574b7807c96107d89">isTokenTy</a>, <a href="#a1bc022868b23918efa44df511f4d5b61">isVectorTy</a>, <a href="#ae8eaa0b4eeac52a2b2282cb1bfd981ae">isVoidTy</a>, <a href="#ab549082d9dfb91ec9a8dc06601d54855">isX86_AMXTy</a>, <a href="#a1f68c27188f1836737bf22a62c558354">isX86_FP80Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsos16-cpp/#a676538c00f189e19fdec0781ba253e5d">needsFPFromSig</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a279254df16490c792d92d94efb67da37">needsFPStubFromParams</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52cff5d33f36f7d74476e993b0118f58">rmwOpMayLowerToLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#aae5f020a66b7a61f16cf63e17fa31e56">anonymous{StructuralHash.cpp}::StructuralHashImpl::update</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a86b39d8533c9fd7c518a6ebc3456e6d1">llvm::Interpreter::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1023db1599beb0118dd1ffe91d85f172">llvm::Interpreter::visitShuffleVectorInst</a>.</p>

</div>
</div>

### getWithNewBitWidth() {#a83725435ece9bc12c40ceb34dbd1727c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getWithNewBitWidth (unsigned NewBitWidth)</td>
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

<p>Given an integer or vector type, change the lane bitwidth to NewBitwidth, whilst keeping the old number of lanes.</p>

<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a909eca4ba9e5eefc203c8e3770bdab25">getContext</a>, <a href="#acaf8e4c3e40e01e848c1fad5f05b81cd">getIntNTy</a>, <a href="#a8fa51d3da96615af400274e9cd272df4">getWithNewType</a>, <a href="#a34ee40bb2f4f5ece47ef19e5f1f57e3c">isIntOrIntVectorTy</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a940bbfdea38f2643d0b63c2cc5af4a82">extractIntPart</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a180c318fe2fe1f2f7d4f4ca4dccfd2f1">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntToPtrInst</a>.</p>

</div>
</div>

### getWithNewType() {#a8fa51d3da96615af400274e9cd272df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getWithNewType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * EltTy)</td>
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

<p>Given vector type, change the element type, whilst keeping the old number of elements.</p>


<p>For non-vectors simply returns <span class="doxyComputerOutput">EltTy</span>.</p>


<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="#a83725435ece9bc12c40ceb34dbd1727c">getWithNewBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9567d315d63f844326900f461f5b3d7a">llvm::InstCombinerImpl::visitIntToPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>.</p>

</div>
</div>

### is16bitFPTy() {#a73e097994740799690554ad4b76f0ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::is16bitFPTy ()</td>
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

<p>Return true if this is a 16-bit float type.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaaa889d8e26c8078095629a42d1f930fa7">BFloatTyID</a>, <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">HalfTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#ae0a656fd896bd17cb7c911a16ac2e4e4">rebuildConstant</a>.</p>

</div>
</div>

### isAggregateType() {#a8cbe006c6c069502d37891c438847c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isAggregateType ()</td>
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

<p>Return true if the type is an aggregate type.</p>


<p>This means it is valid as the first operand of an insertvalue or extractvalue instruction. This includes struct and array types, but does not include vector types.</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">ArrayTyID</a>, <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">StructTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ac45bdcc05a92d63f2249f476eeb17e77">advanceToNextLeafType</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>.</p>

</div>
</div>

### isArrayTy() {#a2a394517076e7dd2bdcd7dde33dfcb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isArrayTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a>.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">ArrayTyID</a> and <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a9534d3bff0727cc904e6bbc1064d2e2f">llvm::VNCoercion::analyzeLoadFromClobberingLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a27fa222a6e3552cda42becaf041aafec">llvm::ARMTTIImpl::getNumBytesToPadGlobalArray</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abab34b1cb73af8519772979270773492">llvm::SPIRVGlobalRegistry::getOrCreateConstIntArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7e06c0b653fcb0e20fbec6bee3d3d40d">isArray</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a>.</p>

</div>
</div>

### isBFloatTy() {#a468e032827ddcd10a8608e08a61323aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isBFloatTy ()</td>
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

<p>Return true if this is 'bfloat', a 16-bit bfloat type.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaaa889d8e26c8078095629a42d1f930fa7">BFloatTyID</a> and <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ac65e8fc0f385fe5eba1c9260f8f4c527">llvm::RISCVTTIImpl::getRegUsageForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a822917bc16eaefe906d8b1f968572a14">isV2BF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aee0985669f6ae78b531ff7bf2f9749d2">isV2F16OrV2BF16</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>.</p>

</div>
</div>

### isDoubleTy() {#aa0fd6bf3d33236279db7b707bba755f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isDoubleTy ()</td>
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

<p>Return true if this is 'double', a 64-bit IEEE fp type.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">DoubleTyID</a> and <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1e8b1f5460f1a0df33e86adb69e934c">anonymous{NumericalStabilitySanitizer.cpp}::ftValueTypeFromType</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchttiimpl/#a2959eb71a1354b9b668d7046e66357ab">llvm::LoongArchTTIImpl::getRegisterClassForType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#aeb31148b78d798ecf2ca6535dec448a3">llvm::RISCVTTIImpl::getRegisterClassForType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a685bfe474ca920468f17fc82cf4664e6">llvm::PPCTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a513e1873d7e7760f5e0241cc47a9aaca">llvm::PPCTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ad4522ba73eb89ae20c7ca46349303f3e">llvm::PPCTTIImpl::hasActiveVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9e49f6fa199d88e91bf282cf91e34740">llvm::X86TTIImpl::isLegalMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4ae03ad8a100596487ddf6bd448090f0">llvm::X86TTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#adec0e730f80de19f31127faedf39008c">llvm::ExecutionEngine::LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a95f58fa5cb1c9a72e5ea815a5036a2e4">printConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#ae0a656fd896bd17cb7c911a16ac2e4e4">rebuildConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>.</p>

</div>
</div>

### isEmptyTy() {#a0f5c23d3b941362c2fa195f4c0b99683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isEmptyTy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this type is empty, that is, it has no elements or all of its elements are empty.</p>

<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aac9cfeffe904936120849defcaa5afbc">llvm::slpvectorizer::BoUpSLP::canMapToVector</a>.</p>

</div>
</div>

### isFirstClassType() {#a82a7e98c00f5bb12e2c5481fe0ab3f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isFirstClassType ()</td>
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

<p>Return true if the type is "first class", meaning it is a valid type for a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa0ec130d9ce9883b3e9c6071ee19a4b16">FunctionTyID</a>, <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520">VoidTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aecc5ef45f49070634ddd53a04ed5548e">llvm::FunctionComparator::cmpConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a08c03a4228af93098afb6ab60e7283f6">foldConstantCastPair</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/castinst/#aa2915714199e899f7766d49f87ec2ad6">llvm::CastInst::isBitCastable</a>.</p>

</div>
</div>

### isFloatingPointTy() {#aac5759c83abd6a4af236401a7cfe7a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isFloatingPointTy ()</td>
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

<p>Return true if this is one of the floating-point types.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>, <a href="#ad696083ef7553304ab42e6d3667942e0">isIEEELikeFPTy</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">PPC_FP128TyID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">X86_FP80TyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a526b79da8f68813dfec82c6f3075a307">convertTo16Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6cc340cf5dc46cf45eb6f784577cadbd">llvm::OpenMPIRBuilder::createAtomicCapture</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae75c4b44f208011259ee93497c2cb411">llvm::OpenMPIRBuilder::createAtomicUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0e2de2c034e3083d006b92ddf14b8bcf">llvm::OpenMPIRBuilder::createAtomicWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a5662a5eb5436e4a9301827cca40b9b93">createBitOrPointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a93b7c4ad8be280f28707e920e5f3a41e">createCmpXchgInstFun</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a91b7eb2a05d10c788413bec7977f3474">emitImplicitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#adc12bf3c911b1e25c4a14ce8f4ad7634">expandAnyOrAllIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae34cc912a530c92d78f60d912ebf3fc1">expandFloatDotIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ad28c25a19888a3846117d94821e75042">expandSignIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#ab3f2b8802cc38cd06a851443f6412807">llvm::SystemZTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a04b3a69fabb49a792bdd785030325f89">llvm::HexagonTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea5285dbe63b422dcaf313ec0fe7473d">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a8d7f8a73873448dc2bae97e066450dba">llvm::NVPTXTargetLowering::getPrototype</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0f12063b62264c753e65abb8e9ff29d8">llvm::ARMTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a900def112d7e109823a5bb89a3c01dd8">llvm::SystemZTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="#ad0709baa705ae62c4e09cdd47fb4b420">isFPOrFPVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="#a5f6edc5246188225b3f49bd5c974c759">isSingleValueType</a>, <a href="#a8ad67a33bae235fe3cca1c3e5a91ed2d">isSized</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac04b69adb2b2657b80c8e86eb8e04099">llvm::HexagonSubtarget::isTypeForHVX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a83114915b4f7fec94a20efa3834a8250">maybeVectorizeType</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#ab4e7e0c4faafb1894a276accb6fd408c">llvm::MipsCCState::PreAnalyzeCallOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#af242a1e8e8ffad834f2e08e506bbe09d">llvm::MipsCCState::PreAnalyzeCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#ab7308ff84a93e55c54db394614a71a44">llvm::MipsCCState::PreAnalyzeFormalArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeece7dddae8cb49c379f7cd11a847217">llvm::TargetLoweringBase::shouldCastAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a93fa81ce3759c975472e23d85d14bec1">llvm::TargetLoweringBase::shouldCastAtomicRMWIInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af40372fc6c2f0c6fea698d32c6730166">llvm::TargetLoweringBase::shouldConvertPhiType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afd0d8328294b83ed79de0f73edb8d58c">supportedAddressingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### isFloatTy() {#a3ffc75c3a4cb82ba307a3334483eb4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isFloatTy ()</td>
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

<p>Return true if this is 'float', a 32-bit IEEE fp type.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">FloatTyID</a> and <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a472408c33fff86419b4ff8fb2e343a64">canContractSqrtToRsq</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1e8b1f5460f1a0df33e86adb69e934c">anonymous{NumericalStabilitySanitizer.cpp}::ftValueTypeFromType</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#af41ea97386e5b3aab125935caf351bb5">llvm::ARMTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchttiimpl/#a2959eb71a1354b9b668d7046e66357ab">llvm::LoongArchTTIImpl::getRegisterClassForType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#aeb31148b78d798ecf2ca6535dec448a3">llvm::RISCVTTIImpl::getRegisterClassForType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a685bfe474ca920468f17fc82cf4664e6">llvm::PPCTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ad4522ba73eb89ae20c7ca46349303f3e">llvm::PPCTTIImpl::hasActiveVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9e49f6fa199d88e91bf282cf91e34740">llvm::X86TTIImpl::isLegalMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4ae03ad8a100596487ddf6bd448090f0">llvm::X86TTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#adec0e730f80de19f31127faedf39008c">llvm::ExecutionEngine::LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a03dc80eab5eb9f0f1ae05d6c3360d988">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithFDivFast</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#af1f9568f6a2469baf6e85a9dc7b6c588">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRcp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae87e464933c41dbf0ad62bdf89905831">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRsq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a95f58fa5cb1c9a72e5ea815a5036a2e4">printConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#ae0a656fd896bd17cb7c911a16ac2e4e4">rebuildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab32574e30e8d85eaa2f692d8fc3c6766">llvm::ARMTargetLowering::shouldConvertSplatType</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>.</p>

</div>
</div>

### isFP128Ty() {#a6f174fc924aa9cccf2abce5ef4b5ec9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isFP128Ty ()</td>
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

<p>Return true if this is 'fp128'.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">FP128TyID</a> and <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#ae962144c6afe1f7ebe533f328722d59c">llvm::SystemZTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a525e9355bccd735cf648afbde45acfc5">llvm::SparcTargetLowering::LowerF128_LibCallArg</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>.</p>

</div>
</div>

### isFPOrFPVectorTy() {#ad0709baa705ae62c4e09cdd47fb4b420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isFPOrFPVectorTy ()</td>
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

<p>Return true if this is a FP type or a vector of FP.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a> and <a href="#aac5759c83abd6a4af236401a7cfe7a0f">isFloatingPointTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad07ba9d946b424c9de4782f4ae7879bb">llvm::ARMTargetLowering::canCombineStoreAndExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a79061cbffefa2eccfe0d30d1c07eed78">FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a2c93d37ad765182a1bc1e43f4b967b99">foldCopySignIdioms</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a094857314ef83a5c1a71e2941a00e795">llvm::HexagonTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a73170211689546daae2d8b0676c6d676">instCombineSVENoActiveZero</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9c9266376e710920a1bd7999ed9c8963">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::maybeHandleSimpleNomemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad9d7a82ba140ac920458705124372cd6">upgradeAVX512MaskToSelect</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>.</p>

</div>
</div>

### isFunctionTy() {#aba930e0564c4207f112d9243eb2fc13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isFunctionTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a>.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa0ec130d9ce9883b3e9c6071ee19a4b16">FunctionTyID</a> and <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a61b99558b55ac0e86169e5b7eb6ad193">llvm::AArch64Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af1ef95140ed897d441343e4a93d37726">isFunctionGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a2f9fee96328939e708e6c2a26a10e49d">llvm::SystemZSubtarget::isPC32DBLSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a27bb49c3656188aff4e75ebc6d4147d5">llvm::SITargetLowering::shouldEmitGOTReloc</a>.</p>

</div>
</div>

### isFunctionVarArg() {#a9cfc626c3a806891f7adc829e290c097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isFunctionVarArg ()</td>
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



<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>

</div>
</div>

### isHalfTy() {#a8cf1f36cc41c466e66d6467e40554841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isHalfTy ()</td>
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

<p>Return true if this is 'half', a 16-bit IEEE fp type.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">HalfTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a472408c33fff86419b4ff8fb2e343a64">canContractSqrtToRsq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab787227a6a978f146fcb2b2ed651642e">canSafelyConvertTo16Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#af41ea97386e5b3aab125935caf351bb5">llvm::ARMTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#aeb31148b78d798ecf2ca6535dec448a3">llvm::RISCVTTIImpl::getRegisterClassForType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ac65e8fc0f385fe5eba1c9260f8f4c527">llvm::RISCVTTIImpl::getRegUsageForType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ac0aa1501dfc0491eada935be1cefaf2a">llvm::X86TTIImpl::getStoreMinimumVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac9518b8cf085f38ae07134937ad85d31">llvm::ARMTargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#af48841917cf8f6f2ebf633b63cec48fb">isV2F16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aee0985669f6ae78b531ff7bf2f9749d2">isV2F16OrV2BF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a95f58fa5cb1c9a72e5ea815a5036a2e4">printConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab32574e30e8d85eaa2f692d8fc3c6766">llvm::ARMTargetLowering::shouldConvertSplatType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>.</p>

</div>
</div>

### isIEEE() {#ab57dba37b1fb3b8feb6ad63f54c2e101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isIEEE ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the type is IEEE compatible, as defined by the eponymous method in <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### isIEEELikeFPTy() {#ad696083ef7553304ab42e6d3667942e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isIEEELikeFPTy ()</td>
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

<p>Return true if this is a well-behaved IEEE-like type, which has a IEEE compatible layout as defined by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af3bec23b6e372e677f17151bfd6af8fc">APFloat::isIEEE()</a>, and does not have non-IEEE values, such as x86_fp80's unnormal values.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaaa889d8e26c8078095629a42d1f930fa7">BFloatTyID</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">DoubleTyID</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">FloatTyID</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">FP128TyID</a>, <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">HalfTyID</a>.</p>


<p>Referenced by <a href="#aac5759c83abd6a4af236401a7cfe7a0f">isFloatingPointTy</a>.</p>

</div>
</div>

### isIntegerTy() {#ac6d28a9b11139182134a9618028a0d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isIntegerTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a>.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">IntegerTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a4ef0843f4b374aae185be929453c9de5">llvm::GEPOperator::accumulateConstantOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adaf74e11d3b6f4feaee9dd7711e92202">llvm::ARMTargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a6b5e20840f3da6bd17be57947204f8c9">llvm::HexagonTargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9c91bde4107b00ee5520f121253437ef">llvm::X86TargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a2fb1c078833c17e4c9529b0cf924385c">canConvertValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab787227a6a978f146fcb2b2ed651642e">canSafelyConvertTo16Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a351251756a2dcf559089f626d9241131">llvm::VNCoercion::coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d58e0e9c2196e30a314dbc5d3431524">llvm::ConstantFoldLoadThroughBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a526b79da8f68813dfec82c6f3075a307">convertTo16Bit</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a6c2f0057515e3f4b8e14cfb9dcb789ae">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertToBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6cc340cf5dc46cf45eb6f784577cadbd">llvm::OpenMPIRBuilder::createAtomicCapture</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae75c4b44f208011259ee93497c2cb411">llvm::OpenMPIRBuilder::createAtomicUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0e2de2c034e3083d006b92ddf14b8bcf">llvm::OpenMPIRBuilder::createAtomicWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#acdb02479a44bbebcabf8b7b5e1baa921">llvm::CastInst::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a51c0653682103a713b0c3695aae3a1ff">createNodeForSelectViaUMinSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6e2bd6420d3d12339e32d4d1b3ba1394">llvm::OpenMPIRBuilder::createOrderedDepend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a39d5c919a484d17c9e12864d869c7f69">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::CreateShadowCast</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3f603d822817256077c95e6573f2b14a">llvm::OpenMPIRBuilder::createTeams</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a91b7eb2a05d10c788413bec7977f3474">emitImplicitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a687e754bf03f8d135bc899b49db74472">llvm::X86TargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7d02bfd7df1433b9ff3e6e237aed1e00">expandIntegerDotIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ad28c25a19888a3846117d94821e75042">expandSignIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesimpl/#a5701c4158af221ec50dcd7fcd971b67e">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesImpl::fillSetWithConstantValues</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#abd4502cb507e24663c9bcf9129eb4060">getAISize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1ffc644bb4865116b0a2f4db014e9bed">llvm::RISCVTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a8a65916cd3a5fe149b7cee7a978a80eb">getHistogramCost</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aec8bb28502320250bf2d4a55ab99e242">llvm::DataLayout::getIndexedOffsetInType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bab447a6422427e5fc92bbbc0c12fba">llvm::ScalarEvolution::getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a27fa222a6e3552cda42becaf041aafec">llvm::ARMTTIImpl::getNumBytesToPadGlobalArray</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abea0d5a07369a9502280335b276b3ccb">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a8d7f8a73873448dc2bae97e066450dba">llvm::NVPTXTargetLowering::getPrototype</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a0b43ef7c72a8cb10a0cb09154a3b3b2d">llvm::slpvectorizer::BoUpSLP::getRootNodeTypeWithNoCast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0f12063b62264c753e65abb8e9ff29d8">llvm::ARMTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a685bfe474ca920468f17fc82cf4664e6">llvm::PPCTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a900def112d7e109823a5bb89a3c01dd8">llvm::SystemZTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ac437e7230f2990fd60bf089f20ea2e78">llvm::X86TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a4cff27834b1fee34a6802d1f0a5b82f3">llvm::AArch64TTIImpl::getStoreMinimumVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a43ab95f8d1cfe32b5c75a4d4d666d89c">llvm::VNCoercion::getStoreValueForLoadHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a513e1873d7e7760f5e0241cc47a9aaca">llvm::PPCTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a05cf907fc03e5b3f599a3dbd02c55803">llvm::RISCVTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a2c90afd148f896bab791bdcad6b41dd0">anonymous{SimplifyIndVar.cpp}::WidenIV::getWideRecurrence</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a8ec2e744dff018b81c0eb2a7e9ea4e2b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorConvertIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ad4522ba73eb89ae20c7ca46349303f3e">llvm::PPCTTIImpl::hasActiveVectorLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac438183b3cdb70d2fa78265512238514">llvm::hasIterationCountInvariantInParent</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9f4e542bdcac1a2ab15b6e55991f07c8">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertWarningFn</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8b805c54dc1ead67b711a4b1cb72f492">llvm::CastInst::isEliminableCastPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade8f600187cb9c664701443e796111e7">llvm::isGEPBasedOnPointerToString</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aeb1b55a34e106493b57164146f40623b">llvm::CastInst::isIntegerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a08188d419e040050ef28ea516afebf98">isIntegerLoopHeaderPHI</a>, <a href="#a34ee40bb2f4f5ece47ef19e5f1f57e3c">isIntOrIntVectorTy</a>, <a href="#a0cd5a11bf5ca1fba6c858d3d59ea6a35">isIntOrIntVectorTy</a>, <a href="#abf313eff420b7c6c8e322a2e9c53cd90">isIntOrPtrTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9e49f6fa199d88e91bf282cf91e34740">llvm::X86TTIImpl::isLegalMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4ae03ad8a100596487ddf6bd448090f0">llvm::X86TTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a1098ae5256eef51d3c36449fab39b0ba">llvm::X86TTIImpl::isProfitableToSinkOperands</a>, <a href="#a5f6edc5246188225b3f49bd5c974c759">isSingleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a7d6c29a3f2cf33fdabaadeba33e47d78">llvm::ConstantDataSequential::isString</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a01cb590e9c05c3675fe75693d84b3120">llvm::AArch64TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a766bc050b0a294104d02f41e0047e0ba">llvm::ARMTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a5ac204c71b6c7eefceba4fdcbf6a4a79">llvm::MSP430TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a7da11befe36636d6aad466b8e0483311">llvm::NVPTXTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0c9601934baa227ce802de96110b47bc">llvm::PPCTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a1daa5bda35eacba5b0b1d532bcf0327f">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aa537392c1f43f9b471c6cb9dead13df7">llvm::SystemZTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aabf943e7fc68b0048d5278b5a35da3a9">llvm::X86TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac04b69adb2b2657b80c8e86eb8e04099">llvm::HexagonSubtarget::isTypeForHVX</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#af5da78fb4956605377823b84dc51cc8a">llvm::AAPotentialConstantValues::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a0db738999f015d26cefccb2a66eada25">llvm::AAValueConstantRange::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab4c31035e44c7bda618eb2eb81dcf314">isVectorPromotionViableForSlice</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a9140f89a634da6fe469d0faa0843a976">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#ad3932b93ad659cccdb5ba53ccc93d6d9">llvm::MSP430TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#acb13111bbf0c82193529692fd4017679">llvm::X86TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#adec0e730f80de19f31127faedf39008c">llvm::ExecutionEngine::LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a95f58fa5cb1c9a72e5ea815a5036a2e4">printConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a48d49b8df95d21ba931f3642c1f5a30d">shouldCanonicalizeGEPToPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af40372fc6c2f0c6fea698d32c6730166">llvm::TargetLoweringBase::shouldConvertPhiType</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a8f438755ea4e823390b7d3eef773bbd8">llvm::SystemZTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8ef0473fe81ed643d4fe2e64c6a5b3e">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::shouldReplace</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a808bb58d9e36f7e9c27b5606d6a9e7d0">llvm::LoongArchTargetLowering::signExtendConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a822fcc93f796cf246c48b13ef6ff05cd">llvm::RISCVTargetLowering::signExtendConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a1ecff7a038229dccedd3fb1aba929059">simplifyX86addcarry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3fb33a8a29e076405285e5282eba81fd">swapICmpOperandsToExposeCSEOpportunities</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad96e48f13961854d2242e9462a920394">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a93fb6df8473d53eee8879c55910f5425">upgradeX86IntrinsicsWith8BitMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#a6cde9aa5130a6fb02753799ff1cc6c93">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>.</p>

</div>
</div>

### isIntegerTy() {#a1214af6bcd9ec53ed43c6ba74c1e9af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isIntegerTy (unsigned Bitwidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> of the given width.</p>

<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isIntOrIntVectorTy() {#a34ee40bb2f4f5ece47ef19e5f1f57e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isIntOrIntVectorTy ()</td>
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

<p>Return true if this is an integer type or a vector of integer types.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a> and <a href="#ac6d28a9b11139182134a9618028a0d07">isIntegerTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a42662469b6d20c41b3ed64e9f215b041">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::add</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#ac9d11e9f66eb3617827801cb7f0f6619">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af169f594f2c9e8cd49a59b29373eb4de">convertValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a83cf0b7088dc0d66ca9f5ecac7350e4c">llvm::IRBuilderBase::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abb42f81be3350e8f94849e8e6aceabab">llvm::IRBuilderBase::CreateLogicalAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae1db5150fc798ca464de8923ba0b8e7f">llvm::IRBuilderBase::CreateLogicalOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeb11a01107c6be1f52ba01902a165d71">llvm::IRBuilderBase::CreateSExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a36742c35a8fff5f74bb3d76c9c19dd47">llvm::IRBuilderBase::CreateZExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45ec897890074179e7de73b934798976">foldAndOrOfICmpEqConstantAndICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a79061cbffefa2eccfe0d30d1c07eed78">FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab6b30eb5a835fd225bcd74248fa65693">llvm::InstCombinerImpl::foldSelectExtConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aebb0348d8efce5fbf0d73f96cfb1212e">llvm::InstCombinerImpl::foldSelectOfBools</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a747cca8cf8e4c4e41b81bb1cbf146a11">foldTruncShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab00c6dc5086df2a37cd2e78715968861">llvm::ConstantExpr::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#ae6c02f1cd1e346da82377714db2a5033">getBoolVecFromMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a3b1f5f847d812d85eaaa8a19bd01bcf4">llvm::VectorType::getExtendedElementVectorType</a>, <a href="#ac59306eb826e349ac7429736b1506432">getExtendedType</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#aa55e1630a0d0f515bb43b6e9c04b8cd8">llvm::ARMTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a652380f28d1a7011e05d0787b6024d48">llvm::ConstantExpr::getPtrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#ac926076ad2d59de82321e2924a4186bd">getSafeDivisor</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a056eabb719f475aa4c5a7e2ba11973b9">llvm::GetElementPtrInst::getTypeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a6c3e2976aaa70cee37a6a3f35fba2a24">llvm::SystemZTTIImpl::getVectorInstrCost</a>, <a href="#a83725435ece9bc12c40ceb34dbd1727c">getWithNewBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8b805c54dc1ead67b711a4b1cb72f492">llvm::CastInst::isEliminableCastPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a373d20116312d859aa88b46b48a8fd8c">isKnownNonEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#abdfa4615d4c528925ba6490398cc54af">llvm::DemandedBits::isUseDead</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9c9266376e710920a1bd7999ed9c8963">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::maybeHandleSimpleNomemIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3a8f0d83fd0c16251206c0d0f3e78174">simplifyAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a22aa6a5c92a8a6cbb5437123d7e069e6">simplifyICmpOfBools</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>.</p>

</div>
</div>

### isIntOrIntVectorTy() {#a0cd5a11bf5ca1fba6c858d3d59ea6a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isIntOrIntVectorTy (unsigned BitWidth)</td>
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

<p>Return true if this is an integer type or a vector of integer types of the given width.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a> and <a href="#ac6d28a9b11139182134a9618028a0d07">isIntegerTy</a>.</p>

</div>
</div>

### isIntOrPtrTy() {#abf313eff420b7c6c8e322a2e9c53cd90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isIntOrPtrTy ()</td>
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

<p>Return true if this is an integer type or a pointer type.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac6d28a9b11139182134a9618028a0d07">isIntegerTy</a> and <a href="#a3b996fbf8458aafffc86cb98a68d0a47">isPointerTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a1484fd35d5f2401ee532e8aea2aba44c">isBitCastSemanticsPreserving</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a83114915b4f7fec94a20efa3834a8250">maybeVectorizeType</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a69a4b725eeca6669bc2adb458eb5e08f">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::ptrToIntPtrType</a>.</p>

</div>
</div>

### isLabelTy() {#a332975f1fb88675058c22029696c991c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isLabelTy ()</td>
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

<p>Return true if this is 'label'.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa66db5616b8f6b2cfe991861905747783">LabelTyID</a>.</p>

</div>
</div>

### isMetadataTy() {#afb3adb81d6f38168542fa408efa365d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isMetadataTy ()</td>
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

<p>Return true if this is 'metadata'.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaad3b3756c598c8acc2d002f5f9a2c1d04">MetadataTyID</a>.</p>

</div>
</div>

### isMultiUnitFPType() {#a7fcf2946847a73b99dc54ea4203d3eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isMultiUnitFPType ()</td>
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

<p>Returns true if this is a floating-point type that is an unevaluated sum of multiple floating-point units.</p>


<p>An example of such a type is ppc_fp128, also known as double-double, which consists of two IEEE 754 doubles.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">PPC_FP128TyID</a>.</p>

</div>
</div>

### isPointerTy() {#a3b996fbf8458aafffc86cb98a68d0a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isPointerTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a>.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">PointerTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a28c431daa68824e2c7f8721bf495fc25">llvm::AliasSetTracker::add</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a032ee1ab74cd70ec3ff4801ec8a49f0f">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::addAccessedBytesForUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a03521060d257111b310d9da04dc20dee">addConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54c5a810b1d6fbe75255674e7e9c40ba">BuildConstantFromSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#ac9683831e3a4c794ca05bf81af366e5e">canBeCheaplyTransformed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a2fb1c078833c17e4c9529b0cf924385c">canConvertValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f5cd5733f1f4d2254248b60fb8a937f">llvm::canReplacePointersIfEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a6f589baf90476080f25dba3a4522d4">llvm::canReplacePointersInUseIfEqual</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#ac10c52fc6c6c8328779f3175fce68067">anonymous{PointerTypeAnalysis.cpp}::classifyFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#aba29b35909e39c48517e7475412c776a">anonymous{PointerTypeAnalysis.cpp}::classifyPointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d58e0e9c2196e30a314dbc5d3431524">llvm::ConstantFoldLoadThroughBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a7c67e5393efc9e53e1a841b70236bfcb">copyFunctionByValArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e44f52bb2b2c5d2273eccec70faae">llvm::copyMetadataForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6cc340cf5dc46cf45eb6f784577cadbd">llvm::OpenMPIRBuilder::createAtomicCapture</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae75c4b44f208011259ee93497c2cb411">llvm::OpenMPIRBuilder::createAtomicUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0e2de2c034e3083d006b92ddf14b8bcf">llvm::OpenMPIRBuilder::createAtomicWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#acdb02479a44bbebcabf8b7b5e1baa921">llvm::CastInst::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a5662a5eb5436e4a9301827cca40b9b93">createBitOrPointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a93b7c4ad8be280f28707e920e5f3a41e">createCmpXchgInstFun</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#aefdc5e2a3d0696ee5c5bf0b467e5f0c5">evaluateICmpRelation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ad57fd622877d2a50e1a312be6b4a409d">fixFunctionTypeIfPtrArgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/initializerbuilder/#abb4311f92fffab12cf33d0aa638f944e">anonymous{AArch64StackTagging.cpp}::InitializerBuilder::flatten</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#ac2f8a243eec640b2ebf8e022d57c9411">getFunctionPointerElemType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a8a65916cd3a5fe149b7cee7a978a80eb">getHistogramCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a7159508155406ad5c350cc429980e09d">anonymous{AttributorAttributes.cpp}::getKnownNonNullAndDerefBytesForUse</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bab447a6422427e5fc92bbbc0c12fba">llvm::ScalarEvolution::getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ab55d9da87838f5736581bfcd5b54afa1">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae94615351738e4ace274b61029700da9">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#acddb0d15dc6d53316188968e5acbefc7">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getNonKernelsWithLDSArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a4d28b0b4536be47a57ac82367c0b04a7">llvm::AMDGPULibFunc::getOrInsertFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a7480612cfe31fd07e5d1d5d45bf3c3b4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrKernel</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aac05ca292709f88f6ba0ae241e0e84bf">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrUserspace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a43ab95f8d1cfe32b5c75a4d4d666d89c">llvm::VNCoercion::getStoreValueForLoadHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aa78bfa47c700608c53890cc25cd44a5b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleNEONVectorStoreIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ad4522ba73eb89ae20c7ca46349303f3e">llvm::PPCTTIImpl::hasActiveVectorLength</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="#abf313eff420b7c6c8e322a2e9c53cd90">isIntOrPtrTy</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp/#a224fcde34a5a815347ca735f579e74dc">isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4ae03ad8a100596487ddf6bd448090f0">llvm::X86TTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d6c5795c1fbe672abaadd824bf08b76">llvm::isLibFreeFunction</a>, <a href="#ab03652069eab17006c51f00c261a6a44">isPtrOrPtrVectorTy</a>, <a href="#a5f6edc5246188225b3f49bd5c974c759">isSingleValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/aadereferenceable/#abc9713fe6e5299f52649a0213cf7f3d6">llvm::AADereferenceable::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a1d7efda60b9905c2287555f2e3e97e32">llvm::AAMemoryBehavior::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoalias/#acae0109819a6600fc6ddd106a82e2f45">llvm::AANoAlias::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#a0639b327e46a46c804bc64ef0c12a7e1">llvm::AANoCapture::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af6735614e085435a0f3bb90aab527213">isVectorPromotionViable</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a13c72931678c2da267fc265c7a2afdfb">optimizeOnceStoredGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a635463dc5e146744799163c2f820e51b">llvm::SCEVExpander::replaceCongruentIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroelide-cpp/#a211159fe60fc76cdea300e3532e60655">replaceWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a93fa81ce3759c975472e23d85d14bec1">llvm::TargetLoweringBase::shouldCastAtomicRMWIInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>.</p>

</div>
</div>

### isPPC\_FP128Ty() {#a670980c63f2e5ca39022baf96173eb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isPPC_FP128Ty ()</td>
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

<p>Return true if this is powerpc long double.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">PPC_FP128TyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a79061cbffefa2eccfe0d30d1c07eed78">FoldBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>.</p>

</div>
</div>

### isPtrOrPtrVectorTy() {#ab03652069eab17006c51f00c261a6a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isPtrOrPtrVectorTy ()</td>
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

<p>Return true if this is a pointer type or a vector of pointer types.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a> and <a href="#a3b996fbf8458aafffc86cb98a68d0a47">isPointerTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a58d962e3d29a81e1cdd18243bf6c71d3">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeArgumentPointerLocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a351251756a2dcf559089f626d9241131">llvm::VNCoercion::coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a20fc81c83f56078eb06e2db21611f58f">combineLoadToOperationType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af169f594f2c9e8cd49a59b29373eb4de">convertValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a83cf0b7088dc0d66ca9f5ecac7350e4c">llvm::IRBuilderBase::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a1536669cae3776862c9ed0a566595b7d">llvm::CastInst::CreatePointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ac120250caf531b58acce9d8cc34c7032">llvm::CastInst::CreatePointerCast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a02560cda155aaed54314383bed827d60">llvm::ConstantExpr::getIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a1f469b1f703519ae25ce564c8704310f">llvm::ConstantExpr::getPointerCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a43ab95f8d1cfe32b5c75a4d4d666d89c">llvm::VNCoercion::getStoreValueForLoadHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8b805c54dc1ead67b711a4b1cb72f492">llvm::CastInst::isEliminableCastPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/structs/llvm/aaaddressspace/#a63d0bb6e63c83c8a5c8c641c4c6aa630">llvm::AAAddressSpace::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaalign/#a46d88fcef3d7d691eb17d3eb537dedfe">llvm::AAAlign::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaallocationinfo/#a4640ec7a4d5d3d7b9cd3b0204f986077">llvm::AAAllocationInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ae548fb21c1de2eb3ad47389ae31488f3">llvm::AAMemoryLocation::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanofree/#a580b45bc8d796ba9773b3e1d0529072f">llvm::AANoFree::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#a4b39699a3bc4c4e6435157c180985c54">llvm::AANonNull::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a0f6906a85729db7eed4b3e39c310fa90">llvm::AANoSync::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a07bee2e824c483aa3d14d1d3aeacd7f3">llvm::AAPointerInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaprivatizableptr/#a1394737f4696b9d788c1f05ab1290034">llvm::AAPrivatizablePtr::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaunderlyingobjects/#a0ab6c751c4d0f19523dbcf38565b4a3d">llvm::AAUnderlyingObjects::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#abfcd971ce6ccafa5489dd3bf313219af">simplifyCastInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5352cd5bd63b8038b094b324190f3a8a">llvm::UpgradeBitCastExpr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac20eb5c6ac0036298cbfb44d3b9cc82">llvm::UpgradeBitCastInst</a>.</p>

</div>
</div>

### isRISCVVectorTupleTy() {#a826c21ba60337817422247c0e98120c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isRISCVVectorTupleTy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isScalableTargetExtTy() {#aeb40ca82dbaafb00a8dd85d5f9feddc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isScalableTargetExtTy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is a target extension type with a scalable layout.</p>

<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isScalableTy() {#a2ff127c9924cd3337080c4445c324aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isScalableTy (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is a type whose size is a known multiple of vscale.</p>

<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#af57aa964441f0796b3d49de878edaca5">areExtractShuffleVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a4380ad0de0940297354df2effeb021ad">canReplaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a790e9b70f12899a4cb2aefd33826ee7d">llvm::AArch64TargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6914b95d1fcf7a5aca24fe82bf4100c2">llvm::RISCVTargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#adcaea10733b9350e0f00307e44ef2b0b">llvm::memtag::StackInfoBuilder::getAllocaInterestingness</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a655cabf7c0f1a0d1e8312338e86abb84">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getGEPCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a3b08e9ad2a315e50f4b0189d9755deed">llvm::AArch64TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a7baf4632513de0fccabc65793c6b8dae">llvm::ConstantExpr::isSupportedGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a48d49b8df95d21ba931f3642c1f5a30d">shouldCanonicalizeGEPToPtrAdd</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a>.</p>

</div>
</div>

### isScalableTy() {#abc3508a388e7f7545f2a4c745f087916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isScalableTy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>.</p>

</div>
</div>

### isSingleValueType() {#a5f6edc5246188225b3f49bd5c974c759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isSingleValueType ()</td>
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

<p>Return true if the type is a valid type for a register in codegen.</p>


<p>This includes all first-class types except struct and array types.</p>


<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#aac5759c83abd6a4af236401a7cfe7a0f">isFloatingPointTy</a>, <a href="#ac6d28a9b11139182134a9618028a0d07">isIntegerTy</a>, <a href="#a3b996fbf8458aafffc86cb98a68d0a47">isPointerTy</a>, <a href="#a8536986ed6c44fce15dba30748428d2c">isTargetExtTy</a>, <a href="#a1bc022868b23918efa44df511f4d5b61">isVectorTy</a> and <a href="#ab549082d9dfb91ec9a8dc06601d54855">isX86_AMXTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a2fb1c078833c17e4c9529b0cf924385c">canConvertValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad7d5504ae0acaa8a22f450dceccae9b5">getAggregateSize</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a74dbf3215dd56f387425123cbff44a36">llvm::SCCPInstVisitor::trackValueOfGlobalVariable</a>.</p>

</div>
</div>

### isSized() {#a8ad67a33bae235fe3cca1c3e5a91ed2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isSized (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; * Visited=nullptr)</td>
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

<p>Return true if it makes sense to take the size of this type.</p>


<p>To get the actual size for a particular target, it is reasonable to use the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> subsystem to do this.</p>


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">ArrayTyID</a>, <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">IntegerTyID</a>, <a href="#aac5759c83abd6a4af236401a7cfe7a0f">isFloatingPointTy</a>, <a href="#a1bc022868b23918efa44df511f4d5b61">isVectorTy</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">PointerTyID</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">StructTyID</a>, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa44ac2c71ce3db287c4e73aca9ad04e44">TargetExtTyID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa0abcabf751e05ec079d5907fc0733c65">X86_AMXTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a4380ad0de0940297354df2effeb021ad">canReplaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#adcaea10733b9350e0f00307e44ef2b0b">llvm::memtag::StackInfoBuilder::getAllocaInterestingness</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a03dd63ac617c1242b7694a4b0ae4ed25">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a496a2f61ad3c4221c58805e32bc47e5c">IsSmallObject</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#afc576f8a8ddd42537a82e1cedc179ae1">tocDataChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a8535b262a19144f9ff988b6bd8c19f42">valueEscapes</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#ad2ed781ba4c19600badfccc2dff6de10">llvm::ObjectSizeOffsetVisitor::visitArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a29d90faf3dd7128f83eca30377481bfe">llvm::ObjectSizeOffsetVisitor::visitGlobalVariable</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a232a0fe878bb0a5a47219195daadca39">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitInstruction</a>.</p>

</div>
</div>

### isStructTy() {#a81eef9d7336f7ee43be79630d8e8ec86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isStructTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a>.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">StructTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a9534d3bff0727cc904e6bbc1064d2e2f">llvm::VNCoercion::analyzeLoadFromClobberingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a91b7eb2a05d10c788413bec7977f3474">emitImplicitCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abc0c3e45d7d6be3fd7f5038a7e9e16de">llvm::RISCVTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a73170211689546daae2d8b0676c6d676">instCombineSVENoActiveZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a226deca7d8508b6b646c8596d4c174a7">isStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab4c31035e44c7bda618eb2eb81dcf314">isVectorPromotionViableForSlice</a> and <a href="/web-llvm/docs/api/structs/false/gepnode/#a8702875a47c894f09fb5b7f502b0b1f4">false::GepNode::operator&lt;&lt;</a>.</p>

</div>
</div>

### isTargetExtTy() {#a8536986ed6c44fce15dba30748428d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isTargetExtTy ()</td>
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

<p>Return true if this is a target extension type.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa44ac2c71ce3db287c4e73aca9ad04e44">TargetExtTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ace5fc98ee60d145881306ef4ba8c6ef0">llvm::applyWrappers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#af10eb6aece68a8127f273e6a2dc0fc79">llvm::VNCoercion::canCoerceMustAliasedValueToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a2fb1c078833c17e4c9529b0cf924385c">canConvertValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abc0c3e45d7d6be3fd7f5038a7e9e16de">llvm::RISCVTargetLowering::getTgtMemIntrinsic</a> and <a href="#a5f6edc5246188225b3f49bd5c974c759">isSingleValueType</a>.</p>

</div>
</div>

### isTokenTy() {#ac9542ee3a689ae9574b7807c96107d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isTokenTy ()</td>
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

<p>Return true if this is 'token'.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaae01900ccd0d696ce7ede9d710415f162">TokenTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectinst/#abd9356b1c3a69a55b72df590c48f9738">llvm::SelectInst::areInvalidOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/compatiblesets/#a4ef2eab86cf6fefd01ef4607cc834432">anonymous{SimplifyCFG.cpp}::CompatibleSets::shouldBelongToSameSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>.</p>

</div>
</div>

### isVectorTy() {#a1bc022868b23918efa44df511f4d5b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isVectorTy ()</td>
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

<p>True if this is an instance of <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a>.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">FixedVectorTyID</a>, <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">ScalableVectorTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad07ba9d946b424c9de4782f4ae7879bb">llvm::ARMTargetLowering::canCombineStoreAndExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a95fd07ca61f35098e091aa2329f9c8a6">canEvaluateShuffled</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3e2793cc62829d80622b78cc681b25c2">canonicalizeBitCastExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a93b7c4ad8be280f28707e920e5f3a41e">createCmpXchgInstFun</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a291e8c83a8c02664076faa0896f1dbc4">createLogicFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2001dcf6278f9e7e10b895d060d15abb">llvm::IRBuilderBase::CreateMaskedCompressStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aad07e3e0fa03f6c780e13d924325d8d0">llvm::IRBuilderBase::CreateMaskedStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ac120250caf531b58acce9d8cc34c7032">llvm::CastInst::CreatePointerCast</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a39d5c919a484d17c9e12864d869c7f69">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::CreateShadowCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67aa349e8bb1aefc2a8a6ca18be9b87c">llvm::emitGEPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#af2ef259f4a63359fe35f05b8b67a911b">llvm::VPInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#acd93ffe413319e78d7c62688cc86eb6c">llvm::VPWidenCallRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae34cc912a530c92d78f60d912ebf3fc1">expandFloatDotIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7d02bfd7df1433b9ff3e6e237aed1e00">expandIntegerDotIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a5d0fa3868fb321fcd4b5d632028db897">foldBitCastSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0ad154d5668d4704cbe075765d342251">llvm::ARMTargetLowering::getABIAlignmentForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#afc893c905f006e49df4253ec300b3aee">llvm::MipsTargetLowering::getABIAlignmentForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a5e5d97b679ac5ed7ad7f5b4639c450d7">getCmpOpsType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1baed59fc0a242d63e6eac45f50f37dd">llvm::RISCVTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/mappingconfig/#aa4b25ffb1d9184be4a8694b940d27562">anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig::getExtendedFPType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a91b2338794e62fc6ce61482b9bc1cde9">llvm::ARMTTIImpl::getGatherScatterOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a767fc4c72294e9754b83fe1d325b0493">llvm::X86TTIImpl::getGatherScatterOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ad360c3b9cdfb92ab7dbbcb9552d786af">llvm::RISCVTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3dddf52f700258ac37fa137527588809">llvm::SPIRVGlobalRegistry::getOrCreateConsIntVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea5285dbe63b422dcaf313ec0fe7473d">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abea0d5a07369a9502280335b276b3ccb">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="#a7c742b32ebcd73d6dc851afac295b0f2">getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a16202d4c91b2fb1558ce682192ad7514">llvm::ARMTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a685bfe474ca920468f17fc82cf4664e6">llvm::PPCTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a900def112d7e109823a5bb89a3c01dd8">llvm::SystemZTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a798a85d56b9dc609e615130607563819">llvm::AArch64TargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a75880fa01f2a6719716b1e3ac002f40e">llvm::ARMTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a4a9e209a264c8bc0020eb0feb1d4a32b">getValueOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#ac9187fccb0fa44ecfef081f99dd17029">llvm::SystemZTTIImpl::getVectorBitmaskConversionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a7a66ba3c828edf70998d427ba626559e">llvm::HexagonTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a513e1873d7e7760f5e0241cc47a9aaca">llvm::PPCTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a05cf907fc03e5b3f599a3dbd02c55803">llvm::RISCVTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#adfc6ceaeff569884d1a3c38a812070b4">getVectorIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a694f0a06fb32a28862ef184803eaadd8">llvm::SystemZTTIImpl::getVectorTruncCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a8ec2e744dff018b81c0eb2a7e9ea4e2b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorConvertIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c42afd9259c6322e00383f27bca19b0">llvm::isImpliedCondition</a>, <a href="#a5f6edc5246188225b3f49bd5c974c759">isSingleValueType</a>, <a href="#a8ad67a33bae235fe3cca1c3e5a91ed2d">isSized</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac04b69adb2b2657b80c8e86eb8e04099">llvm::HexagonSubtarget::isTypeForHVX</a>, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst/#ae9b20825832b7718625e7db28ea29218">llvm::ExtractElementInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a94984d91c7ee37a076fa26d03a131c49">llvm::InsertElementInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a4679b8d3496374b0f0fead1b778f99a2">llvm::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a160d793aacc4ffadcdf86eddbf401c69">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Lower64ShadowExtend</a>, <a href="/web-llvm/docs/api/structs/llvm/scevpatternmatch/cst-pred-ty/#ab4dc630e0981601d51bf88cf21779d7e">llvm::SCEVPatternMatch::cst_pred_ty&lt; Predicate &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#ab4e7e0c4faafb1894a276accb6fd408c">llvm::MipsCCState::PreAnalyzeCallOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#ab7308ff84a93e55c54db394614a71a44">llvm::MipsCCState::PreAnalyzeFormalArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a580f44370be222c0b2be5a2a7fa3f048">processSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#af6a1350b26889cb5eebc75372ab4d3f5">shouldConvertImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afd0d8328294b83ed79de0f73edb8d58c">supportedAddressingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#abce78109fa7acac1ae7aa1b4ee1ce07f">transformToIndexedCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a40003c9aae5f4e1d9cf4b042db0b0c13">llvm::PPCTTIImpl::vectorCostAdjustmentFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>.</p>

</div>
</div>

### isVoidTy() {#ae8eaa0b4eeac52a2b2282cb1bfd981ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isVoidTy ()</td>
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

<p>Return true if this is 'void'.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520">VoidTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a101a4250b1fd5a230a766de2a14cb271">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildEntryThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#ac134215053dd186eca7bdd553eabc68c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildExitThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a1548d6cc07c1c5595817e73713d58a23">copyMustTailReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a792b08a6322bb539ee5ce2f754588c8c">llvm::IRBuilderBase::CreateMalloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#abdf3ba57973320bd702d3b12b0b8fa8c">createRetPHINode</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a155073ec24bee89eeab846ccc4e7108e">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getNumOutputArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp/#a0f3bc601438bcf1aae3e94056456fec1">getRetComponentType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a0a09a1144b3dbb1ddc00f0ced5030522">anonymous{VFABIDemangler.cpp}::getScalableECFromSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aefba9af2f61452f20f4c947b4c2e5f4e">llvm::objcarc::hasAttachedCallOpBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#a4813065b259c6f6a34961b286913f06c">llvm::coro::AnyRetconABI::init</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d6c5795c1fbe672abaadd824bf08b76">llvm::isLibFreeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp/#a7bd47d3b8ac5817cc34bad072b48cf7d">numRetVals</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a039c5bd63f390c0b66e2548b69a372c5">llvm::VPWidenCallRecipe::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>.</p>

</div>
</div>

### isX86\_AMXTy() {#ab549082d9dfb91ec9a8dc06601d54855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isX86_AMXTy ()</td>
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

<p>Return true if this is <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> AMX.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaa0abcabf751e05ec079d5907fc0733c65">X86_AMXTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a20fc81c83f56078eb06e2db21611f58f">combineLoadToOperationType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a26d326912ec9ff7ea15f2b356f5d31eb">createTileStore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a536899926439fa1336a6f8fd1e1c1d2c">getNumDefTiles</a>, <a href="#a5f6edc5246188225b3f49bd5c974c759">isSingleValueType</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a>.</p>

</div>
</div>

### isX86\_FP80Ty() {#a1f68c27188f1836737bf22a62c558354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Type::isX86_FP80Ty ()</td>
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

<p>Return true if this is x86 long double.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#ac7b0ed5c6d30bad74769c6e87ab0edb8">getTypeID</a> and <a href="#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">X86_FP80TyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1e8b1f5460f1a0df33e86adb69e934c">anonymous{NumericalStabilitySanitizer.cpp}::ftValueTypeFromType</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>.</p>

</div>
</div>

### print() {#a91bbc1ac424839ba7e85d2d8542c288a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Type::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool IsForDebug=false, bool NoDetails=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the current type.</p>


<p>Omit the type details if <span class="doxyComputerOutput">NoDetails</span> == true. E.g., let st = type { i32, i16 } When <span class="doxyComputerOutput">NoDetails</span> is true, we only print st. Put differently, <span class="doxyComputerOutput">NoDetails</span> prints the type as if inlined with the operands when printing an instruction.</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 4969 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a91bbc1ac424839ba7e85d2d8542c288a">print</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#af0e4d9315f1815020f42edec6a27ad1f">getBranchCondString</a>, <a href="#a91bbc1ac424839ba7e85d2d8542c288a">print</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/tracingfilesystem/#acb844eb6bc89340c1c01be7165e34d39">llvm::vfs::TracingFileSystem::printImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysisevaluator-cpp/#ad8a192a5cbfc0ba09e5ccfbf187a8934">PrintResults</a>.</p>

</div>
</div>

### subtype\_begin() {#ab0a6b4d55d33508391d708d15ac94241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">subtype_iterator llvm::Type::subtype_begin ()</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Reference <a href="#a96d2037eb473457f3222e5cbe7ea22b5">ContainedTys</a>.</p>


<p>Referenced by <a href="#aca0c4f5920877210db407ce6d11656ce">subtype_rend</a> and <a href="#a5ea992fd3e9da95e4fff1dca95f873c3">subtypes</a>.</p>

</div>
</div>

### subtype\_end() {#ad5ceb7d8f499a1052bec53ed1b588673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">subtype_iterator llvm::Type::subtype_end ()</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="#a96d2037eb473457f3222e5cbe7ea22b5">ContainedTys</a> and <a href="#a679d8ea00092eb9cd392643bb2d1b7f9">NumContainedTys</a>.</p>


<p>Referenced by <a href="#ad1a1e304cf35053589c10a80fa202672">subtype_rbegin</a> and <a href="#a5ea992fd3e9da95e4fff1dca95f873c3">subtypes</a>.</p>

</div>
</div>

### subtype\_rbegin() {#ad1a1e304cf35053589c10a80fa202672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">subtype_reverse_iterator llvm::Type::subtype_rbegin ()</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ad5ceb7d8f499a1052bec53ed1b588673">subtype_end</a>.</p>

</div>
</div>

### subtype\_rend() {#aca0c4f5920877210db407ce6d11656ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">subtype_reverse_iterator llvm::Type::subtype_rend ()</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Reference <a href="#ab0a6b4d55d33508391d708d15ac94241">subtype_begin</a>.</p>

</div>
</div>

### subtypes() {#a5ea992fd3e9da95e4fff1dca95f873c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Type * &gt; llvm::Type::subtypes ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ab0a6b4d55d33508391d708d15ac94241">subtype_begin</a> and <a href="#ad5ceb7d8f499a1052bec53ed1b588673">subtype_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getSubclassData() {#a977023a135a15dc3aadcf1e8246631f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::getSubclassData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad844544defb75e0971036db9672be3f0">llvm::TypedPointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a90b790ccb1af4ea5ccd69db4b8cd2d81">llvm::IntegerType::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a2fe4fb22e1495d40e187248120f5a7e2">llvm::TargetExtType::getNumIntParameters</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#ac96253748333192d7c1c05079d7d5446">llvm::StructType::isLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aec7c3cecd0559788b36c46df1b2181c1">llvm::StructType::isOpaque</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a84b61ef997688651dd4e06cb7567cfed">llvm::StructType::isPacked</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a> and <a href="#aa6a764f2b0653b70a81656accf9dda7c">setSubclassData</a>.</p>

</div>
</div>

### setSubclassData() {#aa6a764f2b0653b70a81656accf9dda7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Type::setSubclassData (unsigned val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a977023a135a15dc3aadcf1e8246631f8">getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/integertype/#af746af1e4d44a9c48f3a1a69b804f73f">llvm::IntegerType::IntegerType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isSizedDerivedType() {#a1793581033b3e347ab37766779d8db1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isSizedDerivedType (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; * Visited=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Derived types like structures and arrays are sized iff all of the members of the type are sized as well.</p>


<p>Since asking for their size is relatively uncommon, move this operation out-of-line.</p>


<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ContainedTys {#a96d2037eb473457f3222e5cbe7ea22b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* const* llvm::Type::ContainedTys = nullptr</td>
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

<p>A pointer to the array of Types contained by this <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>


<p>For example, this includes the arguments of a function type, the elements of a structure, the pointee of a pointer, the element type of an array, etc. This pointer may be 0 for types that don't contain other types (Integer, Double, Float).</p>


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/structtype/#a69c7da4aea6df614c83c075aa246261a">llvm::StructType::element_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a1d854d7ca4568e7840af5520a9012960">llvm::StructType::element_end</a>, <a href="#a3fb19a71e602dce8ff646c3ac2f4ca0f">getArrayElementType</a>, <a href="#ad1d50278883f39969187bceabe068acf">getContainedType</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aee3c78d73273cb8449cd10cc15edcb83">llvm::StructType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a05d5616e1422394b4d350c008b0cc5e0">llvm::FunctionType::param_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aeae69a459419ec0bb738cdc73f4fc2a1">llvm::FunctionType::param_end</a>, <a href="#ab0a6b4d55d33508391d708d15ac94241">subtype_begin</a>, <a href="#ad5ceb7d8f499a1052bec53ed1b588673">subtype_end</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a6136787c7b731e9b64995cd7344ed56e">llvm::TargetExtType::type_param_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4358f46b9bfecaddaa72356c6f6d9cd2">llvm::TargetExtType::type_param_end</a>.</p>

</div>
</div>

### NumContainedTys {#a679d8ea00092eb9cd392643bb2d1b7f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::NumContainedTys = 0</td>
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

<p>Keeps track of how many Type*'s there are in the ContainedTys list.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/structtype/#a1d854d7ca4568e7840af5520a9012960">llvm::StructType::element_end</a>, <a href="#ad1d50278883f39969187bceabe068acf">getContainedType</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aee3c78d73273cb8449cd10cc15edcb83">llvm::StructType::getElementType</a>, <a href="#a66d610d816ff0a14e8ac599dcaefd2c6">getNumContainedTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a858efd7b61654c0de28c56f9adafa13d">llvm::StructType::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aeae69a459419ec0bb738cdc73f4fc2a1">llvm::FunctionType::param_end</a>, <a href="#ad5ceb7d8f499a1052bec53ed1b588673">subtype_end</a> and <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4358f46b9bfecaddaa72356c6f6d9cd2">llvm::TargetExtType::type_param_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Context {#a369d6666c49f7eb1bc92591361aca7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::Type::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This refers to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> in which this type was uniqued.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>

</div>
</div>

### ID {#addd0c2963251ea586af7e2ecd87ff4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeID llvm::Type::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>

</div>
</div>

### SubclassData {#a5fe943e0fe940c7e7859551d09733450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Type::SubclassData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBFloatTy() {#ae3aa33c6054ec18e1d6bc6466d1b4103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getBFloatTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aebda2ae5419e82e341599938217b8f9f">llvm::IRBuilderBase::getBFloatTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypefloat/#ga3ede4791e05601ebbee425ecdef51eef">LLVMBFloatTypeInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### getDoubleTy() {#acb145f988329d1d621f73abcafea21d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getDoubleTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a7b104b582108e25271c32924224a20fb">convertImplicitDefToConstZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a79459acee890c44fac5c279584480b08">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a348a42aeece82f7e2631c7c2e084011e">llvm::IRBuilderBase::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a57e9061fb6d18ee131661f3c68a66eb2">llvm::sandboxir::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#af297fe5d0800d4319a7ca39cc7128f1a">getFloatTypeForLLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a11c2adb7d4fc89c31daa94b1f8ced5a2">getKeyFPValMD</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4b607e6993b349291749a0e177c52fbb">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVFloatType</a>, <a href="#ab908d9ac4f123b5f676e1548c123820c">getScalarTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5a707ef219e51df6fbaff782ed1d44a6">llvm::X86TTIImpl::isLegalBroadcastLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypefloat/#ga200527010747eab31b73d3e3f6d94935">LLVMDoubleTypeInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a34a6720f55cf4ef2114d657d9e14ff7a">makeDoubleDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#aa0c7ee5148fe48f9b0bba95da880df23">makeDoubleDoubleDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#ace45799dce23f34a9cedcef38cc282aa">makeDoubleDoubleDoubleDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#af1c79d13b3cabe136b1bfb07cce0b1d3">makeDoubleDoubleI32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#a1f97ca5ebffacffa92c87ce782a56708">anonymous{NumericalStabilitySanitizer.cpp}::typeFromFTValueType</a>.</p>

</div>
</div>

### getFloatingPointTy() {#a79b425d59c7bc28a4a599cee0b9ed338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getFloatingPointTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S)</td>
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



<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ac27bcb2dc1fa6aa905e8cc86af54de0f">llvm::ConstantFP::get</a>.</p>

</div>
</div>

### getFloatTy() {#ad5e0fe0efdd88f98a5b5eb512d5351c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getFloatTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a7b104b582108e25271c32924224a20fb">convertImplicitDefToConstZero</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a5e9594f698a6092e755b6ce7ee6905cd">llvm::MDBuilder::createFPMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a2b15feb32345af4916487fa3fa9d6227">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a6212e41633990ea795daea7917312bdf">llvm::RISCVTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aafb3bab3be2f6daaa1178de24492df05">llvm::IRBuilderBase::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#af4125c0ca2f91c4d506cfabc64fa4b20">llvm::sandboxir::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#af297fe5d0800d4319a7ca39cc7128f1a">getFloatTypeForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4b607e6993b349291749a0e177c52fbb">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVFloatType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ac65e8fc0f385fe5eba1c9260f8f4c527">llvm::RISCVTTIImpl::getRegUsageForType</a>, <a href="#ab908d9ac4f123b5f676e1548c123820c">getScalarTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypefloat/#ga529c83a8a5461e5beac19eb867216e3c">LLVMFloatTypeInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adaec1659649f46c52f32ad8caa493055">llvm::parseTypeString</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#a1f97ca5ebffacffa92c87ce782a56708">anonymous{NumericalStabilitySanitizer.cpp}::typeFromFTValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ac0a8da35200651179e36ea9764bfcc89">upgradePTESTIntrinsic</a>.</p>

</div>
</div>

### getFP128Ty() {#a49f37835a410e050b960dd936a54dd05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getFP128Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#af297fe5d0800d4319a7ca39cc7128f1a">getFloatTypeForLLT</a> and <a href="/web-llvm/docs/api/groups/llvmccoretypefloat/#ga1c02fb08f9ae12a719ed42099d42ccd8">LLVMFP128TypeInContext</a>.</p>

</div>
</div>

### getHalfTy() {#ae550f2e9436b395b614b4377ba27007f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getHalfTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a526b79da8f68813dfec82c6f3075a307">convertTo16Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#af297fe5d0800d4319a7ca39cc7128f1a">getFloatTypeForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a61f696480c9a4ac5ea8267d7e1b67eed">llvm::IRBuilderBase::getHalfTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4b607e6993b349291749a0e177c52fbb">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVFloatType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypefloat/#ga3a5332a1d075602bccad7576d1a8e36f">LLVMHalfTypeInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ae04610310004450abde7293643734104">matchFPExtFromF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adaec1659649f46c52f32ad8caa493055">llvm::parseTypeString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>.</p>

</div>
</div>

### getInt128Ty() {#a30ab2a65707a06849653fb5931411193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * Type::getInt128Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a8631130c37aa54ae6c9127abc5fe392a">llvm::AArch64TargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a91ff70f8bf2561f15894b8c5f8352d2f">llvm::IRBuilderBase::getInt128Ty</a> and <a href="/web-llvm/docs/api/groups/llvmccoretypeint/#ga5f3cfd960e39ae448213d45db5da229a">LLVMInt128TypeInContext</a>.</p>

</div>
</div>

### getInt16Ty() {#a87f56db834c58ca630624956ecf6972f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * Type::getInt16Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a526b79da8f68813dfec82c6f3075a307">convertTo16Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a277490f857b3fe53b950347a9148a447">llvm::createProfileSamplingVar</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a00df0d04b86c6d3d0d027c912afb7282">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitHiddenKernelArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0ad360dbce483cc0903211b623b9debd">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a6955657cb7867972e6b8f046e9cf5a02">llvm::offloading::getEntryTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7325c05ca5ad3b239d1e88b933324c01">llvm::IRBuilderBase::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#af9ef9c2652adaeee5bf72525dbd10677">llvm::sandboxir::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac8acdac12a8890cbfe798dc2c5fb2d24">llvm::GCNTTIImpl::getMemcpyLoopLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac976273389caab4360013b109184e0bb">llvm::GCNTTIImpl::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeint/#ga23a21172a069470b344a61672b299968">LLVMInt16TypeInContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#afcd344dd26b9b6b08fcb676d1c888bc8">anonymous{ConstantFolding.cpp}::ReadDataFromGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrshiftexpand-cpp-/avrshiftexpand/#a25192a5e79d3f5ef39a4b3d4a7da9fd9">anonymous{AVRShiftExpand.cpp}::AVRShiftExpand::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab32574e30e8d85eaa2f692d8fc3c6766">llvm::ARMTargetLowering::shouldConvertSplatType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>.</p>

</div>
</div>

### getInt1Ty() {#aa75984a442f2379de0c66018201fa628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * Type::getInt1Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#abd9356b1c3a69a55b72df590c48f9738">llvm::SelectInst::areInvalidOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0bfeadac5ccd4e56b4c5df9dc6bb8817">calcPredicateUsingBooleans</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a0cf81ee784fd5dea0b9353a51f4f4fee">llvm::VPBlendRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a6def10381cc09d92342a6846fe1174e0">llvm::VPHistogramRecipe::computeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a1d51e11adfffd05afe252d3398f50d4e">llvm::MDBuilder::createCallbackEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#a9495513e04a8f797cc8723887bdbd13c">llvm::sampleprofutil::createFSDiscriminatorVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a7ae16889db439f8fbb234fe3de672d11">llvm::VFABI::createFunctionType</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a18fdc21778e3249102bca86808f4ef78">createMemprofHistogramFlagVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#acd2295e6d5f183d1cad636c7a564660e">DisableAllLoopOptsOnLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a85687b0be992ef172b4228ed69f5146a">llvm::AtomicInfo::EmitAtomicCompareExchangeLibcall</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a35c9927607481d33c2093c2b7d643e80">fillCommonArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0af04c89840d424b7b33ae71d7c8cd28">llvm::ConstantExpr::getAlignOf</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a756d58f4b6672c5083895872285931f1">llvm::IRBuilderBase::getAllOnesMask</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a2c38e97ad1359c63dd44a0bbe5dcf3a3">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getBoolTy</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad8398a35cd187d6a75b460fcf54b5236">llvm::LoopVectorizationCostModel::getDivRemSpeculationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a4910f3acf596de7348ca70c0b41b0040">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getExtendedReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a75eedc5667cb22e709e89fef21c08ee5">llvm::sandboxir::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a8965f79b48ae37911f82bc71e1433131">llvm::RISCVTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a2c1b9368972e15e3602d4279f9988584">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTreeReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a54f30c8bea3912d1d0f347626c395be6">llvm::slpvectorizer::BoUpSLP::getVectorElementSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac42eef26cc4185a8932bc59a94dc5d16">llvm::SelectionDAGBuilder::handleKillDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfg/#a88fa969de8279bbac9d3718775723b50">anonymous{StructurizeCFG.cpp}::StructurizeCFG::init</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7915bab3089583402f61b46f7baea356">instCombineSVECmpNE</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeint/#ga390b4c486c780eed40002b07933d13df">LLVMInt1TypeInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a2f68fd99d1f5c6c8326be57c2963306d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0206e74dec02d952d1b620a7b63f5694">llvm::CmpInst::makeCmpResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a7b33bd9843f6f96a4f390a9314692657">llvm::sandboxir::CmpInst::makeCmpResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a43ccb9c1a5081a041efc8db46bbcf7a2">replaceWithTLIFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcboolrettoint-cpp-/ppcboolrettoint/#ab87e9dc6bfa51c511f6a13bac05927eb">anonymous{PPCBoolRetToInt.cpp}::PPCBoolRetToInt::runOnUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a07dca79c487ad44ed9f03cfde69c7747">setAssignmentTrackingModuleFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#a5c4090098e3eaedb61973431af4898b1">llvm::at::trackAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>.</p>

</div>
</div>

### getInt32Ty() {#a30dd396c5b40cd86c1591872e574ccdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * Type::getInt32Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#ae1b043855cc598a229a8389f9a116f74">anonymous{NVPTXCtorDtorLowering.cpp}::addKernelMetadata</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#ae700acd5d174922e475ea31fdb8fe51f">anonymous{AddressSanitizer.cpp}::AddressSanitizer::AddressSanitizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a490938b206738261d5984fe958a872ad">adjustInliningThresholdUsingCallee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a521a0263cd32258d251908a3b8ab2f78">llvm::annotateValueSite</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#af83167f66d93e94ff003e7a130b823f0">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a646829664451eb913bfa2f92920478ea">calcPredicateUsingInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aa5aa60eda03a6732ad5c06a8fc6bf97b">calculateVectorIndex</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#ad67fb96194cff11216803ad74dba5687">OutlinableGroup::collectGVNStoreSets</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a0cb38e302133457f235fdcc6723abeac">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bf95d0980fad19452f4c9aca445af3f">llvm::ConstantFoldInsertElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cdd63d012b1a1a470677a1b7a7bfcb4">llvm::convertPointerToIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ad06dcf793a8b91871327c682d6f3f909">llvm::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#af5f4af29cea0dae3f4a3cf633dbacaba">llvm::ARMConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a6f467de3ca984f069ee86b9558388294">anonymous{OffloadWrapper.cpp}::createBinDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#adff293fef41b4eb80fca7c47b2e2c99a">llvm::MDBuilder::createBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a5098d4bb22d4347dc55e1d08dcbe6708">llvm::ARMTargetLowering::createComplexDeinterleavingIR</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad36ec66444a025ac9f91b7f2e055f7e2">llvm::IRBuilderBase::CreateConstGEP2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5945995573939aabe8aa3ccea099b219">llvm::IRBuilderBase::CreateConstInBoundsGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa85037712ab4c5044582974769aa4b62">llvm::IRBuilderBase::CreateConstInBoundsGEP2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a643353cc59fa74e91cb3212e25475f58">llvm::dxil::ResourceTypeInfo::createElementStruct</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a251d6cd85b676ea4be1e4c2c263494db">anonymous{OffloadWrapper.cpp}::createFatbinDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ada8d44774af63e8cab5f9b2a088121fe">llvm::OpenMPIRBuilder::createGlobalFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8240180b602f60980be558e3cd44b460">llvm::IRBuilderBase::CreateGlobalStringPtr</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a3b3620fdf60408799b2d1957707a81d2">anonymous{InstrOrderFile.cpp}::InstrOrderFile::createOrderFileData</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeac445a66283c4e567ebd390c058e39d">llvm::IRBuilderBase::CreatePreserveArrayAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4804fd7127d8e249a628e93d6b8b3f2a">llvm::IRBuilderBase::CreatePreserveStructAccessIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a277490f857b3fe53b950347a9148a447">llvm::createProfileSamplingVar</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#afb5a26693a2aa4ccb54923bf6a6e86d6">anonymous{OffloadWrapper.cpp}::createRegisterFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1ca1f5b41c1408be83df43ab024cdd69">createRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#a58b3d504dac6f59b0c9bab0ca1084bf7">createRoundingModeDecoration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#af3cdb326ec386f27b1260b06225ae385">createSaturatedConversionDecoration</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#af36172c1f538b7305b44760997d5a3c2">llvm::OpenMPIRBuilder::createSections</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3e1a0b27abb4d57e2293c46802eee89d">llvm::OpenMPIRBuilder::createSingle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a6bfe058b12abe3443b07d4f4d55d863f">createStringMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a52c340457da98320b6872f2c0ccbae1b">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::CtxInstrumentationLowerer</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad46652b66427679d9c221df6915019ca">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::discardEVLParameter</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgcloweringimpl/#a285f4b41becdfd4385ddb237bfc744fc">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a00df0d04b86c6d3d0d027c912afb7282">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitHiddenKernelArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#aaa3dfbded3ebc8068ad825a039bfdfaf">llvm::HexagonTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo/#a4f4d5344fa41e237eb9a60c7b62975b8">llvm::AArch64SelectionDAGInfo::EmitStreamingCompatibleMemLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a55668c464aef1136badb1b58eeec19c6">emitThumb1LoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a8a9cca3d1c6515fbf780f033644ace85">emitThumb2LoadConstPool</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a017054a3231506db436fdd9e8ae20ca0">llvm::expandUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8b12ae89227758cb5684cc7cf25a7f43">findCostForOutputBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a0c8e1730578d5e4181a2bd1502328802">llvm::SanitizerStatReport::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a32adc549fbc7c20005aabb9406435ff4">anonymous{InstrOrderFile.cpp}::InstrOrderFile::generateCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ae5bc9cac664aeb67c181f9add7309cfa">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a6553e4e7f2cae85df3c310267a3797c9">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#abd4502cb507e24663c9bcf9129eb4060">getAISize</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0af04c89840d424b7b33ae71d7c8cd28">llvm::ConstantExpr::getAlignOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a36bdcdb68f8b041f4f5886de8da52bc1">getArgTypesFromOpParamTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a604c924e11ca5df4475086acc8db0f4e">anonymous{OffloadWrapper.cpp}::getBinDescTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/escapeenumerator-cpp/#a7bc16e748f040714b2a1e334af45ac4f">getDefaultPersonalityFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a6955657cb7867972e6b8f046e9cf5a02">llvm::offloading::getEntryTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#ad046f69ab8abe8d2605589e6daf42612">anonymous{OffloadWrapper.cpp}::getFatbinWrapperTy</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a8ba4ed00f8805b525fb7b4497a527876">llvm::sandboxir::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4cb54e7d62530f9e973ff35f6301de6a">llvm::X86TargetLowering::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a0fd41cd05155ed81f0ac16e8a478b860">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getLocalVarIdptr</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac8acdac12a8890cbfe798dc2c5fb2d24">llvm::GCNTTIImpl::getMemcpyLoopLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac976273389caab4360013b109184e0bb">llvm::GCNTTIImpl::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#a84ca5b0d9c7fce1c2cfcc14ee488713a">getOffsetFromIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#adfa93be20aafc0740ce9e4d48640406c">getPownType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a093be232e1de543da63b9f41e7d18f2f">getPromotedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#aff234d51ccd591da6c1332a3d52fbe1e">getResBindType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#af69be60078714a34c733e198b5aab9af">getResPropsType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a05bf02ad372b0e58afd80f2378cfac94">getResRetType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a778163e6ec80716a12ab3282cb97f0d9">llvm::ConstantExpr::getSizeOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a5f6846040fc48f21e5969492bbb88fdc">getSplitDoubleType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a7ed0896d98a0b530d38c48bdd0985e00">getTagValueAsMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/checkloc/#a1770adf45ff9ecddcde74db71a7dea96">anonymous{NumericalStabilitySanitizer.cpp}::CheckLoc::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a2155baa694ee1fb098bf0a5808f00734">anonymous{IndirectCallPromotion.cpp}::getVTableAddressPointOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a272cd16957d147ad113779617eeabf77">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::handleAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#ae545f4984db8486dce9ff7f2db45a829">llvm::HardwareLoopInfo::HardwareLoopInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#adee485b8d8a010d18877f5f41286b079">llvm::BPFCoreSharedInfo::insertPassThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7fcf73aaa1b218db266c0f9d4020ab3f">instCombineRDFFR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7915bab3089583402f61b46f7baea356">instCombineSVECmpNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae46906a076a2ec35cf6a38e433b48219">llvm::PPCTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#gaa2572582272b52c9f13d25787e2f6937">LLVMBuildArrayMalloc</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga4939c72c142cd9ff1d5e4fffaef32339">LLVMBuildMalloc</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeint/#ga5e69a2cc779db154a0b805ed6ad3c724">LLVMInt32TypeInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a3ca4c3ddc5d302c21716484fa8de528d">llvm::XCoreInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a4ca63570c656522c8e6a423ae926ba5e">llvm::XtensaInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af8cc1f957026a793e58fec505e47a7c5">llvm::X86TargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#adfa24b29ddb799607095546fa388954a">llvm::AMDGPUAsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a8f69a29bf679c53a8703f5497bba92b2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerDynamicLDSVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af92646d30b3f15471c866cd83fadfb62">llvm::SparcTargetLowering::LowerF128Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#aed95721a1abb7ab2af1b35f3f282b1fe">lowerLoadRelative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a5e5cf24df0a45159407988a98fe42700">lowerPtrAnnotation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#af1c79d13b3cabe136b1bfb07cce0b1d3">makeDoubleDoubleI32</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a528a5eb1adc41c313f4e35df8bf6e1d1">makeX86FP80X86FP80I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adaec1659649f46c52f32ad8caa493055">llvm::parseTypeString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a5761cea08563e881215f9511be699d06">populateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a657c17735f988deb12c8067e40be44d4">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::prescanForConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#afcd344dd26b9b6b08fcb676d1c888bc8">anonymous{ConstantFolding.cpp}::ReadDataFromGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ab753ecd3bbe05bc8ceb961ca8f2c6480">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::replaceUsesInInstructionsWithTableLookup</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a07714583aa2bea29cd0284d5340dd844">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::replaceUseWithTableLookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp/#a36be37a99f7cf2fdd84b942e5dafba1b">replaceWithGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuopenclenqueuedblocklowering-cpp-/amdgpuopenclenqueuedblocklowering/#ac3eeb5c96b81aa7ad07041b3c20eeb04">anonymous{AMDGPUOpenCLEnqueuedBlockLowering.cpp}::AMDGPUOpenCLEnqueuedBlockLowering::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmehpreparepass/#a2cbdc4bc7c2c1dc4c48d00376ab271a1">llvm::WasmEHPreparePass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxloweraggrcopies-cpp-/nvptxloweraggrcopies/#a1e7cbd0783ad9cbbfdf85b5dbaba57f8">anonymous{NVPTXLowerAggrCopies.cpp}::NVPTXLowerAggrCopies::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemztdc-cpp-/systemztdcpass/#a297c01ed88bcbeaac178adb0ff9e497f">anonymous{SystemZTDC.cpp}::SystemZTDCPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winehstate-cpp-/winehstatepass/#acbb400505dff72ce49663ae73e4d7399">anonymous{X86WinEHState.cpp}::WinEHStatePass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600openclimagetypeloweringpass-cpp-/r600openclimagetypeloweringpass/#acf970c313d62e284e7c40d5dfddb1ccb">anonymous{R600OpenCLImageTypeLoweringPass.cpp}::R600OpenCLImageTypeLoweringPass::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a984df453a762468ca683f6e83cf50e17">runPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af38c031cd1488ca8f80ada31b3df9eac">llvm::scaleProfData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#abdf7cd534c311883094a5534590f3bc1">SegmentOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#a4b1c5b30230a9be2aa310c91d8dccf20">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase/#ac98dfc76a69863c13ae587fa9521c808">llvm::InstrProfCntrInstBase::setIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3dadc94dc9df93690ba937226744797">llvm::setKCFIType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab32574e30e8d85eaa2f692d8fc3c6766">llvm::ARMTargetLowering::shouldConvertSplatType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2c78ae45454d731f51f0ce021a729816">simplifyRelativeLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a1616baf1b22efae9f17bb3d499ac8931">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::storePrimitiveShadowOrigin</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a5e2b7ac5f48193117a340aa15b085719">llvm::OpenMPIRBuilder::unrollLoopPartial</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a457f42a32df73079ac4526c572a2d7fd">updateNVPTXMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#acd02b84e30b7fa3fa475f938e522eb88">validExtractValueIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#ae2afbc4899c3d5a6034358e288eaa7c6">validInsertValueIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#a1fdfe91f1f9e82078936d0cde2af8a3f">validShuffleVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#ac4b6c0523efa46982b346b582dba83c5">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vlalignb</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#ae76242f445cf64cc9dac611ba3abc9c7">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vralignb</a>.</p>

</div>
</div>

### getInt64Ty() {#a05186fa23e4d11b9855a9599ba87a4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * Type::getInt64Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/cgprofile-cpp/#a6445e21ce50f407f94bac93afebf6c66">addModuleFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b7601463f25d7904fa9d060ba629a5a">llvm::GlobalObject::addTypeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a521a0263cd32258d251908a3b8ab2f78">llvm::annotateValueSite</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfpreserveditype-cpp-/#a72adf7d117af6ebe1a3aee68b6e3e782">anonymous{BPFPreserveDIType.cpp}::BPFPreserveDITypeImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aadca3692ce40afeb83b7765b2d7dfc9c">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::build</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a1b412464f78908112e627ee7bc54f99d">llvm::memprof::buildCallstackMetadata</a>, <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a1d51e11adfffd05afe252d3398f50d4e">llvm::MDBuilder::createCallbackEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0ac085386a38b408b6ac75b1255aeb22">llvm::IRBuilderBase::CreateConstGEP1_64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e329d0cf4b01beeb722cae4ed919a83">llvm::IRBuilderBase::CreateConstGEP2_64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abe7ccc68b743707443a07e60aedb2ba7">llvm::IRBuilderBase::CreateConstInBoundsGEP1_64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa8ee5dc4e4a1b26c4bdf1a574eefe2fc">llvm::IRBuilderBase::CreateConstInBoundsGEP2_64</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a208093b76ef0d541b5e0d09498be189d">llvm::MDBuilder::createFunctionEntryCount</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#a4e632566b9002891ab9f5a108f3bd803">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a083d4808926043b15fdd4acbccc863d1">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a7fb87fc21e00d45516f625f9dd4067eb">llvm::MDBuilder::createIrrLoopHeaderWeight</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a78f018d0c5133b2d60d092d68f6b046b">llvm::orc::createIRTypedAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ad3d7fcf79c6f64a51803f438fad104fb">llvm::MDBuilder::createLLVMStats</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a7cbecc17bbb64783431627bcf1f433c7">createMIBNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a3b3620fdf60408799b2d1957707a81d2">anonymous{InstrOrderFile.cpp}::InstrOrderFile::createOrderFileData</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a3c0f85e1d2ebeeddea5c58df5fca12f7">llvm::MDBuilder::createPseudoProbeDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a08252ccfac4481c88092435e56a0fb3b">llvm::IRBuilderBase::CreatePtrDiff</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a0dc11a237cde4f082d956d6c60af0113">llvm::MDBuilder::createTBAAAccessTag</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a61e4a8cfd0d268c67b6cc5c86861c18b">llvm::MDBuilder::createTBAANode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a7e8c8a5d3688506df87d627259578c06">llvm::MDBuilder::createTBAAScalarTypeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#abf39f615f0eef682e349ee230cec4fbf">llvm::MDBuilder::createTBAAStructNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ae8e9e63ea1324e1c2ac905f4b9b68bd6">llvm::MDBuilder::createTBAAStructTagNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a9f79697a0b629233029dab1823b23be8">llvm::MDBuilder::createTBAAStructTypeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#aecae3ba429df973662fc145e3347149b">llvm::MDBuilder::createTBAATypeNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a52c340457da98320b6872f2c0ccbae1b">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::CtxInstrumentationLowerer</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#ae25976638e06c5f87d1dd439602f1f8c">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitHiddenKernelArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a00df0d04b86c6d3d0d027c912afb7282">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitHiddenKernelArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a683761fbb11ed0969edf7eee08b08bf3">llvm::PPCTargetLowering::emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0e0d3c023e19c20fbf01b40d36aced80">llvm::PPCTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a1ef8e45df24dcf4222b48c8fe4077c3e">llvm::AlignmentFromAssumptionsPass::extractAlignmentInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#ac9784ca12ba090d5ab2924df8f535a86">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a08c03a4228af93098afb6ab60e7283f6">foldConstantCastPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a32adc549fbc7c20005aabb9406435ff4">anonymous{InstrOrderFile.cpp}::InstrOrderFile::generateCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a8ee97870547b76f8387091128a00e90c">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0af04c89840d424b7b33ae71d7c8cd28">llvm::ConstantExpr::getAlignOf</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a6955657cb7867972e6b8f046e9cf5a02">llvm::offloading::getEntryTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#aa3741ff4c00516153fc0d9285a1e4c9e">llvm::sandboxir::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4cb54e7d62530f9e973ff35f6301de6a">llvm::X86TargetLowering::getIRStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a95456b3a4f4b949345b6f7c3fac2d4c4">getKeyValMD</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac976273389caab4360013b109184e0bb">llvm::GCNTTIImpl::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#aaec462f93a64e27fa16d1416b1dbbb8b">llvm::DIBuilder::getOrCreateSubrange</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0488e45d72dfdd3c9f1b7780fc812675">llvm::DIBuilder::getOrCreateSubrange</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae19488d3493945579ed3987ce14c6ff2">llvm::OpenMPIRBuilder::getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a778163e6ec80716a12ab3282cb97f0d9">llvm::ConstantExpr::getSizeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofincrementinst/#afe7c16bf1ea59bb69a0e02f5d80aadda">llvm::InstrProfIncrementInst::getStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a7ed0896d98a0b530d38c48bdd0985e00">getTagValueAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargaarch64helper/#a2252a215cf90d91e6e98e77f42cf7954">anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::getVAField64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#ae3b43649c18ab9e63c1be61b93dd7031">insertLifetimeMarkersSurroundingCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aa6ab3fab9efb1a05c605f74d579db034">instCombineSVEDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ae2f9543c1954e97e2887aab7c33e18b4">instCombineSVELast</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/functioninstrumenter/#ad8a93caaba7e38b078b14a134f5f46f8">anonymous{PGOInstrumentation.cpp}::FunctionInstrumenter::instrument</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#abb10d6b403863597e459061c0d8e1dd7">anonymous{MemProfiler.cpp}::MemProfiler::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae46906a076a2ec35cf6a38e433b48219">llvm::PPCTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeint/#ga213ec0fe49543773320798d7cb619746">LLVMInt64TypeInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a2f68fd99d1f5c6c8326be57c2963306d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a0a4ed9d0b5d054ee811d2d8fecb35626">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::poisonRedzones</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#afcd344dd26b9b6b08fcb676d1c888bc8">anonymous{ConstantFolding.cpp}::ReadDataFromGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#aa1d94843d12c81b1eda3d646bb2ab38e">llvm::orc::ReOptimizeLayer::reoptimizeIfCallFrequent</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemztdc-cpp-/systemztdcpass/#a297c01ed88bcbeaac178adb0ff9e497f">anonymous{SystemZTDC.cpp}::SystemZTDCPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af38c031cd1488ca8f80ada31b3df9eac">llvm::scaleProfData</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#afc31bb8f3573226060a5c31480fa650e">llvm::GlobalObject::setVCallVisibilityMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a382dd57993076a5d1a545af2f69078ed">llvm::AArch64TTIImpl::shouldConsiderAddressTypePromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a87303462e710ef447ed4768ea29b3090">llvm::RISCVTTIImpl::shouldConsiderAddressTypePromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a6736ef281ad586fdc1601b22287ae9bc">anonymous{ExpandVariadics.cpp}::ExpandVariadics::sizeOfAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#acce887569ed105b612c33053a3264608">unpackStoreToAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5352cd5bd63b8038b094b324190f3a8a">llvm::UpgradeBitCastExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac20eb5c6ac0036298cbfb44d3b9cc82">llvm::UpgradeBitCastInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7ee47904c2a7f2c3af3824c90b5a2ec">llvm::UpgradeTBAANode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#ae76242f445cf64cc9dac611ba3abc9c7">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vralignb</a>.</p>

</div>
</div>

### getInt8Ty() {#a7ba5de75f50bb4a4ba920698edf39b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * Type::getInt8Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#acc2528429e7e0eb707ca49e72bb3ce49">llvm::memtag::alignAndPadAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#aefcb18d60b47720b919eb6b0ce98b05e">allocateFrameInCaller</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54c5a810b1d6fbe75255674e7e9c40ba">BuildConstantFromSCEV</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad6c0f52a75bef49176db797774e8dc2c">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildRepresentativeDynamicLDSInstance</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#a86d26a3e2f2b7996916c7040cd7b40b4">classifyConstantWithOpaquePtr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#ac10c52fc6c6c8328779f3175fce68067">anonymous{PointerTypeAnalysis.cpp}::classifyFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#aba29b35909e39c48517e7475412c776a">anonymous{PointerTypeAnalysis.cpp}::classifyPointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#a10d6da0e1f35c3d34f969bc596d61b19">createGlobalFwdRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a3b3620fdf60408799b2d1957707a81d2">anonymous{InstrOrderFile.cpp}::InstrOrderFile::createOrderFileData</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a52c340457da98320b6872f2c0ccbae1b">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::CtxInstrumentationLowerer</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a2039a88cc5cd331c4012e856dde33eed">llvm::coro::BaseCloner::deriveNewFramePointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#ad9c37680a58c2590f08d938aa1a44d6c">anonymous{CoroElide.cpp}::CoroIdElider::elideHeapAllocations</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a35c9927607481d33c2093c2b7d643e80">fillCommonArgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargaarch64helper/#a1984e3e4e68c3ba67dc3dd32b9dfed6c">anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#a86760d872237617ac5d36a58fd894bcc">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararggenerichelper/#a3d0c6a7511c4672829252c0ce65c58c3">anonymous{MemorySanitizer.cpp}::VarArgGenericHelper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a5442ec4868113ee36c2380a1b919e103">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a6a7c02af1eb9545e64bdf82e7f7d763e">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper/#aeff71653a760718fea2a9b166f8df1b4">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#abe0dacfb2237ff8fb43d5ad22ac45d5f">anonymous{CoroFrame.cpp}::FrameTypeBuilder::finish</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a222f3ff6cc88e36df2f31491a77c102a">foldGEPChainAsU8Access</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a32adc549fbc7c20005aabb9406435ff4">anonymous{InstrOrderFile.cpp}::InstrOrderFile::generateCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a6a243a4cdb6c27c0c4276793b5136a01">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getByteTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a53974d47ba590e4418c5952730fd9559">llvm::sandboxir::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab1577d309005660f819a91c8268ec001">llvm::X86TTIImpl::getMaskedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#ad131251b8b387ae1c9cefac79efb961a">llvm::TargetTransformInfoImplBase::getMemcpyLoopLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac976273389caab4360013b109184e0bb">llvm::GCNTTIImpl::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuperfhintanalysis-cpp-/#af38737fae00f7e84d27b82ca0954ef3b">anonymous{AMDGPUPerfHintAnalysis.cpp}::getMemoryInstrPtrAndType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a7712aacb3f4a1a860a15ca4de83e6a9f">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#a4334e601f712be7fd456cd1c5b26e96e">getPointeeTypeByCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a52c21a2bc9e5238472dabfd4183158e5">llvm::sandboxir::Utils::getPointerDiffInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp/#a3b9b774d938abd4c2836b47f52daa274">getPointerOperandAndType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#aa522833bf3162eb609d51cefb341314f">llvm::dxil::DXILOpBuilder::getResBind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#aff234d51ccd591da6c1332a3d52fbe1e">getResBindType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7c340cc26f0c6d27219747cac55a2dc2">getValueOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a2155baa694ee1fb098bf0a5808f00734">anonymous{IndirectCallPromotion.cpp}::getVTableAddressPointOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a424871cbef50e8414bb8bbed3a4068db">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::initialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#abb10d6b403863597e459061c0d8e1dd7">anonymous{MemProfiler.cpp}::MemProfiler::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a45baf076726e8a271aa9dc0a8baa2c76">isPointerAlwaysReplaceable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6469b3ca28c7c2752a9370a1f6ff4fd5">llvm::isUntypedEquivalentToTyExt</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeint/#ga7afaa9a2cb5dd3c5c06d65298ed195d4">LLVMInt8TypeInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a8f69a29bf679c53a8703f5497bba92b2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerDynamicLDSVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/lowererbase/#a8e44a67be75da70df132c8683575d772">llvm::coro::LowererBase::makeSubFnCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ac388d17329447d2fd72ceabf79fefeba">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/expandedcallframe/#aaf4615da5bb69a28fd2496f9248881bd">anonymous{ExpandVariadics.cpp}::ExpandVariadics::ExpandedCallFrame::padding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrshiftexpand-cpp-/avrshiftexpand/#a25192a5e79d3f5ef39a4b3d4a7da9fd9">anonymous{AVRShiftExpand.cpp}::AVRShiftExpand::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicmemintrinsic/#a91ecdf20aedd95b2052709963e7c9c7b">llvm::AtomicMemIntrinsic::setElementSizeInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79a682a8e3ef1ba361fb668ce902b6c3">llvm::toTypedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a1ae624f5747718933b1dabc6a03689aa">tryToOptimizeStoreOfAllocationToGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a97cbd12fcf61e3cf7db640c3661e66df">tryToShorten</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>.</p>

</div>
</div>

### getIntNTy() {#acaf8e4c3e40e01e848c1fad5f05b81cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * Type::getIntNTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned N)</td>
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



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#ae700acd5d174922e475ea31fdb8fe51f">anonymous{AddressSanitizer.cpp}::AddressSanitizer::AddressSanitizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a379666f1f08149bf9e4dabcb430aee93">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::calculateConvertType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af9b65d81d95d19757080cfae034e3d7e">checkVectorTypesForPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#af481dabda60939ffaa5c0da35892dc96">computeRecurrenceType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a5662a5eb5436e4a9301827cca40b9b93">createBitOrPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a0a1c9934f39747a96a2b6b42d0bec03e">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFloatingToFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a44f4e9b64d7a612f2b8236f0d147f591">createMaskInstrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a39d5c919a484d17c9e12864d869c7f69">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::CreateShadowCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#a046c6262fc6fc6743bf539c87761083f">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abee99e97f96cb26e6b8208e4d6c98fec">getConstantVector</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a70eadaa7bf647a939fa6a673c7467fa3">llvm::IntegerType::getExtendedType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acbc0ce9726d9e887c396c3d483e09899">llvm::DataLayout::getLargestLegalIntType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac8acdac12a8890cbfe798dc2c5fb2d24">llvm::GCNTTIImpl::getMemcpyLoopLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#ad131251b8b387ae1c9cefac79efb961a">llvm::TargetTransformInfoImplBase::getMemcpyLoopLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a7ee986b3ced1ba5562ed34c5e633bed2">llvm::TargetTransformInfoImplBase::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a712be2c47b7dea0b22073dde0cf48fdc">llvm::RISCVTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a6b9321187f70bb8fc4c103af466f6c21">llvm::X86TTIImpl::getReplicationShuffleCost</a>, <a href="#ab908d9ac4f123b5f676e1548c123820c">getScalarTy</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#ab478aed986ac4bf6d92e603694af9b2b">llvm::DataLayout::getSmallestLegalIntType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abc0c3e45d7d6be3fd7f5038a7e9e16de">llvm::RISCVTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3e3935d45c4b79b85a117b47cc1d2e61">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="#a83725435ece9bc12c40ceb34dbd1727c">getWithNewBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#af001e6326d49bf139dfeee21772f01f0">inlineGetBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a7fd9ee96f281dd94ed4119c2e45836bf">isIntegerWideningViable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#abb3e0c28998ff9684b75e9efa0697919">isValidProtoForSizeReturningNew</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab4c31035e44c7bda618eb2eb81dcf314">isVectorPromotionViableForSlice</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#a77802cf83b248213a74db75d5850ab4b">anonymous{MemProfiler.cpp}::MemProfiler::MemProfiler</a>, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/moduleaddresssanitizer/#aff0e7e435e8bbd930b71c32df8f2c421">anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::ModuleAddressSanitizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a4357c88d173a81e047c07756ff94ada0">processConstantStringArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>.</p>

</div>
</div>

### getLabelTy() {#a4a17871a3bb12fd2b8e1e45454c3e1c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getLabelTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoretypeother/#ga7b7c56bf8406c50205fdd410b351ad81">LLVMLabelTypeInContext</a>.</p>

</div>
</div>

### getMetadataTy() {#a28fdf240b8220065bc60d6d1b1a2f174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getMetadataTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeother/#ga59283de371ba6d44a2e2c8bd0db108e8">LLVMMetadataTypeInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/valueenumerator/#a462551b180e939bad5a404fc6cb38a9b">llvm::dxil::ValueEnumerator::ValueEnumerator</a> and <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a>.</p>

</div>
</div>

### getPPC\_FP128Ty() {#a489d14cb1d049f4bcc5e3e9cdaf9c54d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getPPC_FP128Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypefloat/#gac2491184fc3d8631c7b264c067f2f761">LLVMPPCFP128TypeInContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>.</p>

</div>
</div>

### getPrimitiveType() {#a8afb3494f6f22e80508f1945a2466052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getPrimitiveType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="#a5e9e1c0dd93557be1b4ad72860f3cbda">TypeID</a> IDNumber)</td>
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

<p>Return a type based on an identifier.</p>

<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### getScalarTy() {#ab908d9ac4f123b5f676e1548c123820c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ScalarTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Type::getScalarTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#acb145f988329d1d621f73abcafea21d8">getDoubleTy</a>, <a href="#ad5e0fe0efdd88f98a5b5eb512d5351c2">getFloatTy</a>, <a href="#acaf8e4c3e40e01e848c1fad5f05b81cd">getIntNTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a817dfd76b27697e96a20f80f7bb68251">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>.</p>

</div>
</div>

### getTokenTy() {#a2b741dd02fbe0b1f02e589a785748639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getTokenTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga9df7bb82a0ae5cc23bcc31453dda75b3">LLVMBuildCatchSwitch</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#gaf300f8d9fa5897746a54b15307388559">LLVMBuildCleanupPad</a> and <a href="/web-llvm/docs/api/groups/llvmccoretypeother/#ga5d3702e198e2373db7e31bb18879efc3">LLVMTokenTypeInContext</a>.</p>

</div>
</div>

### getVoidTy() {#a6e20e76960d952de088354cbcd14c3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getVoidTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a6def10381cc09d92342a6846fe1174e0">llvm::VPHistogramRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a2bd6903bee5451ebaffd790ccf869664">llvm::MIRParserImpl::createDummyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a826f32ce82e4b2605718fedddba8a055">CreateFailBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a83935060c1ded86b574493d5fbefeef9">llvm::IRBuilderBase::CreateFree</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a7ba6b711f3cab802b6e29a1595d223bb">llvm::RandomIRBuilder::createFunctionDefinition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#aa82200436735a7e7831e52db45ae4580">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a4f767db6edfa57ac38c654668e19b385">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#afb5a26693a2aa4ccb54923bf6a6e86d6">anonymous{OffloadWrapper.cpp}::createRegisterFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a7c9e3a3c2e449cbc1dfebc37503af252">llvm::orc::ReOptimizeLayer::createReoptimizeCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a256980e987af753b4c497757fad18000">llvm::createSanitizerCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a483af07ad9cee019751803fda2e04d1e">anonymous{OffloadWrapper.cpp}::createUnregisterFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a52c340457da98320b6872f2c0ccbae1b">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::CtxInstrumentationLowerer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d90c79914c0bdfadad630647f8843b">llvm::declareSanitizerInitFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a27b401b3a141c64a98a51bafa9c8efdc">anonymous{CFGuard.cpp}::CFGuardImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#aa22cef0c6abab1ef18f9e35efc2b537e">emitInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a0c8e1730578d5e4181a2bd1502328802">llvm::SanitizerStatReport::finish</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a0b7d633cf22c2f54d391f3f5c0a5ef56">fixupFPReturnAndCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#a7704ada0af8cb169e6cf9dd2dec6171c">anonymous{JMCInstrumenter.cpp}::getCheckFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a669fae0a15d7219ef3ca3f3b16e3f5a0">getFreshReductionFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a492e33f38ce495d0143f95092cfd0595">getFunctionTypeFromAsyncSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a717a199ea9514d956fa87fd23c13a228">llvm::getOrCreateSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer/#afbffb051116605acd820c965770ae5a0">anonymous{MemorySanitizer.cpp}::MemorySanitizer::getOrInsertMsanMetadataFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#acad385080d103af2e3c47f9d4124827a">getOrInsertValueProfilingCall</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a1a578073d9d2487a3806e8a51abb1b6e">llvm::coro::Shape::getResumeFunctionType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/memaccessty/#a153bbcee36817bcedb110f30d95b2368">anonymous{LoopStrengthReduce.cpp}::MemAccessTy::getUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a2571433d1b220fb84bfcb7584002cb02">anonymous{WholeProgramDevirt.cpp}::DevirtModule::importResolution</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a1a4145a18b32a1bc1030bf789e370963">InsertCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a05dd87a2da7ddff8ce97716e3b479b2e">InsertSafepointPoll</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a859081e342a8a97b3648873ae3df252d">llvm::AArch64TargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3f1fdc55e21406f8dd4612925fbe86a8">llvm::ARMTargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af30042e4c09138928b477e3834f0a13e">llvm::X86TargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6b7912ea5edc4563fe03afc57fa9b0c6">insertUseHolderAfter</a>, <a href="/web-llvm/docs/api/structs/anonymous-typesanitizer-cpp-/typesanitizer/#aa8094f0b4dd7316f56198f0e4760b9b4">anonymous{TypeSanitizer.cpp}::TypeSanitizer::instrumentGlobals</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeother/#gaf3821dfb45eccaf7317e39ed46456681">LLVMVoidTypeInContext</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a57ee991742a8027b5ef002c616a6b9fd">llvm::SelectionDAGBuilder::LowerCallSiteWithDeoptBundleImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a034082eea623803b4fa593f2e29f0d96">llvm::VETargetLowering::lowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a88f0e5db31eb88103b548f1bcce2da58">llvm::SelectionDAG::makeStateFunctionCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/insertfunctionstrategy/#a51a23cfe8db3e31fdc6eeb8547df0d33">llvm::InsertFunctionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/nsanmemopfn/#a85787eb1162b7d741f8f3b29601e7860">anonymous{NumericalStabilitySanitizer.cpp}::NsanMemOpFn::NsanMemOpFn</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adaec1659649f46c52f32ad8caa493055">llvm::parseTypeString</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a0a4ed9d0b5d054ee811d2d8fecb35626">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::poisonRedzones</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#aafb9808e3b375710c68b44c507cd9c3d">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a64cd5b79789610d81be5d0b2633868ae">anonymous{ThinLTOBitcodeWriter.cpp}::simplifyExternals</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a2c91ee4a2eb25c80ee8795a57afddf5e">llvm::Interpreter::visitReturnInst</a>.</p>

</div>
</div>

### getWasm\_ExternrefTy() {#a18e4e0af5b02a410a87c9cdbcd1423b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getWasm_ExternrefTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>.</p>

</div>
</div>

### getWasm\_FuncrefTy() {#adc56186d80974cb7f4928e9f0abf8904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getWasm_FuncrefTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>.</p>

</div>
</div>

### getX86\_AMXTy() {#a08ceb864464bce07aed4387d665f6565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getX86_AMXTy (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#af49d9ef5881a26b9bbbcd2a1002857bb">createAllocaInstAtEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypeother/#ga56b5f50c5d0e56e61d835039c8b6e653">LLVMX86AMXTypeInContext</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a79f47e97963f500c113eb9bfee2e5b47">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#aabc37fb487455e5268d389333bc5c890">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore</a>.</p>

</div>
</div>

### getX86\_FP80Ty() {#ace5611e40c0a2dbdc2c6cbc93bea180c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Type::getX86_FP80Ty (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#af297fe5d0800d4319a7ca39cc7128f1a">getFloatTypeForLLT</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypefloat/#ga24f77b84b625ed3dd516b52480606093">LLVMX86FP80TypeInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a496789388d8c1c5a81723b3e3adedf10">makeX86FP80X86FP80</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a528a5eb1adc41c313f4e35df8bf6e1d1">makeX86FP80X86FP80I32</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a76f9ac4919f0df94ddb092037bbc9e21">makeX86FP80X86FP80X86FP80</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a7a0bc2534f4e5813219d15c836636c8e">makeX86FP80X86FP80X86FP80X86FP80</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#a1f97ca5ebffacffa92c87ce782a56708">anonymous{NumericalStabilitySanitizer.cpp}::typeFromFTValueType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">Type.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
