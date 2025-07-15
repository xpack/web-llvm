---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/valid
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ValID` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a> - Represents a reference of a definition of some sort with no type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ValID { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">llvm/AsmParser/LLParser.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a0b9231b1356c3e914bcf6fdd8ef8253d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2dc7a8150e4605ef9e8a42d794ea43">ValID</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a> (const ValID &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd72ac4363e6f7b12b36ecf9c328f09">operator&lt;</a> (const ValID &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/structs/llvm/valid">llvm::ValID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d3199eae6b0dfa17adfe9a2cf0e761">Kind</a> = <a href="#a0b9231b1356c3e914bcf6fdd8ef8253daf9810598ef8c64f97b37bbef7b7ef547">t_LocalID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lllexer/#a8ba87c44f4d51a249fbf317476e120dd">LLLexer::LocTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1ce89a2b59958f00610f23072f4a02">Loc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2872d67ad1d0d9d6132232cdb65cbd5c">UIntVal</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6caeac2a805eb45cc6062eb4c42a102">FTy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee96284dbc8bf16589b98c2fed0d9b7">StrVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c07cf46c749fe15dacc0ef4206c069">StrVal2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ff634da8357e2381a00a01b7da85f2">APSIntVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c99eb56d025b85e44757b3f132de4cc">APFloatVal</a> {0.0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b75b050fa2c74e8aa48d2b01c554fb1">ConstantVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab84dbfb9a9540bfeaa68105dca533448">ConstantStructElts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231643d74123f7ba85788236935175e3">NoCFI</a> = false</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a> - Represents a reference of a definition of some sort with no type.</p>


<p>There are several cases where we have to parse the value but where the type can depend on later context. This may either be a numeric reference or a symbolic (var) reference. This is just a discriminated union.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a0b9231b1356c3e914bcf6fdd8ef8253d}

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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_LocalID<a id="a0b9231b1356c3e914bcf6fdd8ef8253daf9810598ef8c64f97b37bbef7b7ef547"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_GlobalID<a id="a0b9231b1356c3e914bcf6fdd8ef8253da353c551d64c75cee5d77b71fd732d356"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_LocalName<a id="a0b9231b1356c3e914bcf6fdd8ef8253daa816aa1a333ed4bcda6680386db64314"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_GlobalName<a id="a0b9231b1356c3e914bcf6fdd8ef8253da43e8d1cc4a3ad66d905727199b86284d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_APSInt<a id="a0b9231b1356c3e914bcf6fdd8ef8253da0a31e3baf782a7d2755e4db2e744bf6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_APFloat<a id="a0b9231b1356c3e914bcf6fdd8ef8253dab48d985361ecb39c1c2414e428e3d42e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_Null<a id="a0b9231b1356c3e914bcf6fdd8ef8253dab3ea701ea0ffacc09773f33f6d7d9d51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_Undef<a id="a0b9231b1356c3e914bcf6fdd8ef8253da58406825e006551a9b719d1c907f3389"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_Zero<a id="a0b9231b1356c3e914bcf6fdd8ef8253dabefca713647f54b64f5cb7f56817bd02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_None<a id="a0b9231b1356c3e914bcf6fdd8ef8253da94d772e3912b524af7790b1d0bcfe9b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_Poison<a id="a0b9231b1356c3e914bcf6fdd8ef8253daa3ebcff8401d40a74f97a3c6af5b35c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_EmptyArray<a id="a0b9231b1356c3e914bcf6fdd8ef8253da3eb7bdecfe9e5c7c0ffce83c0c84478a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_Constant<a id="a0b9231b1356c3e914bcf6fdd8ef8253da02471580f042c7345a249903e35c890f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_ConstantSplat<a id="a0b9231b1356c3e914bcf6fdd8ef8253dac1712c3a90a5fa63d1280015a98ae807"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_InlineAsm<a id="a0b9231b1356c3e914bcf6fdd8ef8253daf829af9a7837f566ddded19861930551"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_ConstantStruct<a id="a0b9231b1356c3e914bcf6fdd8ef8253da80a448e21c006f19888acc34c5f0056d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t_PackedConstantStruct<a id="a0b9231b1356c3e914bcf6fdd8ef8253da0ca8d3f1fd4c2371ce8489eee6f02293"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ValID() {#aec2dc7a8150e4605ef9e8a42d794ea43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValID::ValID ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#abbd72ac4363e6f7b12b36ecf9c328f09">operator&lt;</a> and <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### ValID() {#a88e6b20c534836fab8bdfd02516e809b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValID::ValID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a> &amp; RHS)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>References <a href="#a2c99eb56d025b85e44757b3f132de4cc">APFloatVal</a>, <a href="#ac3ff634da8357e2381a00a01b7da85f2">APSIntVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8b75b050fa2c74e8aa48d2b01c554fb1">ConstantVal</a>, <a href="#ab6caeac2a805eb45cc6062eb4c42a102">FTy</a>, <a href="#a10d3199eae6b0dfa17adfe9a2cf0e761">Kind</a>, <a href="#aca1ce89a2b59958f00610f23072f4a02">Loc</a>, <a href="#a231643d74123f7ba85788236935175e3">NoCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aeee96284dbc8bf16589b98c2fed0d9b7">StrVal</a>, <a href="#af0c07cf46c749fe15dacc0ef4206c069">StrVal2</a>, <a href="#a2872d67ad1d0d9d6132232cdb65cbd5c">UIntVal</a> and <a href="#aec2dc7a8150e4605ef9e8a42d794ea43">ValID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#abbd72ac4363e6f7b12b36ecf9c328f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValID::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a> &amp; RHS)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a10d3199eae6b0dfa17adfe9a2cf0e761">Kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aeee96284dbc8bf16589b98c2fed0d9b7">StrVal</a>, <a href="#a0b9231b1356c3e914bcf6fdd8ef8253da353c551d64c75cee5d77b71fd732d356">t_GlobalID</a>, <a href="#a0b9231b1356c3e914bcf6fdd8ef8253da43e8d1cc4a3ad66d905727199b86284d">t_GlobalName</a>, <a href="#a0b9231b1356c3e914bcf6fdd8ef8253daf9810598ef8c64f97b37bbef7b7ef547">t_LocalID</a>, <a href="#a0b9231b1356c3e914bcf6fdd8ef8253daa816aa1a333ed4bcda6680386db64314">t_LocalName</a>, <a href="#a2872d67ad1d0d9d6132232cdb65cbd5c">UIntVal</a> and <a href="#aec2dc7a8150e4605ef9e8a42d794ea43">ValID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### APFloatVal {#a2c99eb56d025b85e44757b3f132de4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::ValID::APFloatVal {0.0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### APSIntVal {#ac3ff634da8357e2381a00a01b7da85f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::ValID::APSIntVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### ConstantStructElts {#ab84dbfb9a9540bfeaa68105dca533448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Constant *[]&gt; llvm::ValID::ConstantStructElts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ConstantVal {#a8b75b050fa2c74e8aa48d2b01c554fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* llvm::ValID::ConstantVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### FTy {#ab6caeac2a805eb45cc6062eb4c42a102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* llvm::ValID::FTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### Kind {#a10d3199eae6b0dfa17adfe9a2cf0e761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ValID llvm::ValID::Kind = <a href="#a0b9231b1356c3e914bcf6fdd8ef8253daf9810598ef8c64f97b37bbef7b7ef547">t_LocalID</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#abbd72ac4363e6f7b12b36ecf9c328f09">operator&lt;</a> and <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### Loc {#aca1ce89a2b59958f00610f23072f4a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLLexer::LocTy llvm::ValID::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### NoCFI {#a231643d74123f7ba85788236935175e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValID::NoCFI = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### StrVal {#aeee96284dbc8bf16589b98c2fed0d9b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ValID::StrVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#abbd72ac4363e6f7b12b36ecf9c328f09">operator&lt;</a> and <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### StrVal2 {#af0c07cf46c749fe15dacc0ef4206c069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ValID::StrVal2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

### UIntVal {#a2872d67ad1d0d9d6132232cdb65cbd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ValID::UIntVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Referenced by <a href="#abbd72ac4363e6f7b12b36ecf9c328f09">operator&lt;</a> and <a href="#a88e6b20c534836fab8bdfd02516e809b">ValID</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
