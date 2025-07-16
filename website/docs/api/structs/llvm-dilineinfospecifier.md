---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dilineinfospecifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DILineInfoSpecifier` Struct Reference

<p>Controls which fields of <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> container should be filled with data. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DILineInfoSpecifier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">llvm/DebugInfo/DIContext.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb21199c7202d4e81277bb7c89d635b7">FunctionNameKind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870">DINameKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FileLineInfoKind { <a href="#a4d01b170267924ab4225e3c93ad666c3">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9022cff3f224aeb556a053c1c849834c">DILineInfoSpecifier</a> (FileLineInfoKind FLIKind=FileLineInfoKind::RawValue, FunctionNameKind FNKind=FunctionNameKind::None, bool ApproximateLine=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf177d7e45fa7344bbf8322dc9353df">operator==</a> (const DILineInfoSpecifier &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4d01b170267924ab4225e3c93ad666c3">FileLineInfoKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19da1042fbbfaa19fb78879702d9bb45">FLIKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870">FunctionNameKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af080957130b4d8a21d897fe7b809b4e6">FNKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091a76e292e65216b58b5b814ecd33e5">ApproximateLine</a></td>
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

<p>Controls which fields of <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> container should be filled with data.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FunctionNameKind {#adb21199c7202d4e81277bb7c89d635b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DILineInfoSpecifier::FunctionNameKind =  DINameKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### FileLineInfoKind {#a4d01b170267924ab4225e3c93ad666c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DILineInfoSpecifier::FileLineInfoKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">None<a id="a4d01b170267924ab4225e3c93ad666c3a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawValue<a id="a4d01b170267924ab4225e3c93ad666c3a420b00d155d9b18204d9a7afd76dabb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseNameOnly<a id="a4d01b170267924ab4225e3c93ad666c3a04146b047eda21e7fe49ebd5ea3ba0fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RelativeFilePath<a id="a4d01b170267924ab4225e3c93ad666c3a4223ba35e45813b985f7631a0f574c20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AbsoluteFilePath<a id="a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DILineInfoSpecifier() {#a9022cff3f224aeb556a053c1c849834c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DILineInfoSpecifier::DILineInfoSpecifier (<a href="#a4d01b170267924ab4225e3c93ad666c3">FileLineInfoKind</a> FLIKind=<a href="#a4d01b170267924ab4225e3c93ad666c3a420b00d155d9b18204d9a7afd76dabb5">FileLineInfoKind::RawValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870">FunctionNameKind</a> FNKind=FunctionNameKind::None, bool ApproximateLine=false)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#a091a76e292e65216b58b5b814ecd33e5">ApproximateLine</a>, <a href="#a19da1042fbbfaa19fb78879702d9bb45">FLIKind</a>, <a href="#af080957130b4d8a21d897fe7b809b4e6">FNKind</a> and <a href="#a4d01b170267924ab4225e3c93ad666c3a420b00d155d9b18204d9a7afd76dabb5">RawValue</a>.</p>


<p>Referenced by <a href="#aeaf177d7e45fa7344bbf8322dc9353df">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#aeaf177d7e45fa7344bbf8322dc9353df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILineInfoSpecifier::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> &amp; RHS)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#a9022cff3f224aeb556a053c1c849834c">DILineInfoSpecifier</a>, <a href="#a19da1042fbbfaa19fb78879702d9bb45">FLIKind</a>, <a href="#af080957130b4d8a21d897fe7b809b4e6">FNKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ApproximateLine {#a091a76e292e65216b58b5b814ecd33e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILineInfoSpecifier::ApproximateLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#a9022cff3f224aeb556a053c1c849834c">DILineInfoSpecifier</a>.</p>

</div>
</div>

### FLIKind {#a19da1042fbbfaa19fb78879702d9bb45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileLineInfoKind llvm::DILineInfoSpecifier::FLIKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#a9022cff3f224aeb556a053c1c849834c">DILineInfoSpecifier</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#a9690eb35ff7a9e7476c1f08ebe174e27">llvm::pdb::PDBContext::getInliningInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#adb7363772d7149160c8c6feafdcd6594">llvm::pdb::PDBContext::getLineInfoForAddress</a> and <a href="#aeaf177d7e45fa7344bbf8322dc9353df">operator==</a>.</p>

</div>
</div>

### FNKind {#af080957130b4d8a21d897fe7b809b4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionNameKind llvm::DILineInfoSpecifier::FNKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#a9022cff3f224aeb556a053c1c849834c">DILineInfoSpecifier</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#adb7363772d7149160c8c6feafdcd6594">llvm::pdb::PDBContext::getLineInfoForAddress</a>, <a href="#aeaf177d7e45fa7344bbf8322dc9353df">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a> and <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
