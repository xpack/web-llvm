---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DemangleConfig.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cassert&gt;
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af989845e24678c452b9222afdac95e7f">__has_feature</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed0a618f017e128a5d8654754f792db">__has_cpp_attribute</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d2d7742701f3f112afbcd8d4f9ccdb">__has_attribute</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447121dcab4275b7839a56082b7a1ab8">__has_builtin</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b2026ea9e750b69b9a9eb3238e9b26">DEMANGLE_GNUC_PREREQ</a>(maj, min, patch)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89bf5498ef5e9915f38a0da6adb156a3">DEMANGLE_ATTRIBUTE_USED</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a4b6b609be6808e094304ae8d981f7">DEMANGLE_UNREACHABLE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31d66b34b38535cb9d5abde8c3c3582">DEMANGLE_ATTRIBUTE_NOINLINE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29995d06ac1017b383bd56ca6b624661">DEMANGLE_DUMP_METHOD</a>&nbsp;&nbsp;&nbsp;<a href="#ae31d66b34b38535cb9d5abde8c3c3582">DEMANGLE_ATTRIBUTE_NOINLINE</a> <a href="#a89bf5498ef5e9915f38a0da6adb156a3">DEMANGLE_ATTRIBUTE_USED</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2ab89559cfa9c7fbfd635bec59e42d">DEMANGLE_FALLTHROUGH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71d1b2a381f0070e426cf362f0ef7e2">DEMANGLE_ASSERT</a>(__expr, __msg)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>((__expr) &amp;&amp; (__msg))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad82d307eb10a0e447f4b254f0af7dde7">DEMANGLE_NAMESPACE_BEGIN</a>&nbsp;&nbsp;&nbsp;namespace llvm { namespace itanium_demangle {</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd584e2ac8072e41efbd2f3c2e439ca">DEMANGLE_NAMESPACE_END</a>&nbsp;&nbsp;&nbsp;} }</td>
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


<div class="doxySectionDef">

## Macro Definitions

### \_\_has\_attribute {#a54d2d7742701f3f112afbcd8d4f9ccdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_attribute(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### \_\_has\_builtin {#a447121dcab4275b7839a56082b7a1ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_builtin(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### \_\_has\_cpp\_attribute {#aeed0a618f017e128a5d8654754f792db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_cpp_attribute(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### \_\_has\_feature {#af989845e24678c452b9222afdac95e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_feature(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### DEMANGLE\_ASSERT {#ac71d1b2a381f0070e426cf362f0ef7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_ASSERT(__expr, __msg)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>((__expr) &amp;&amp; (__msg))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/outputbuffer/#a7b0573aee384e0abdba1e452639a1f43">OutputBuffer::back</a>, <a href="/web-llvm/docs/api/classes/podsmallvector/#aaf1bb2c5847721bd75a7e94d4e93d8b1">PODSmallVector&lt; Node *, 8 &gt;::back</a>, <a href="/web-llvm/docs/api/classes/explicitobjectparameter/#a67e89282b522c55859032b6ccb410da9">ExplicitObjectParameter::ExplicitObjectParameter</a>, <a href="/web-llvm/docs/api/classes/specialsubstitution/#a806f152c432d118d8063a6825a0e009e">SpecialSubstitution::getBaseName</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aeed1fbd4f82f1bc9c4ada7ce9835edb7">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getSymbol</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#ae8f0bd74643fb4035d3992af214b44a3">OutputBuffer::insert</a>, <a href="/web-llvm/docs/api/classes/podsmallvector/#ad210ba29415e8c12059b2496e2853ac5">PODSmallVector&lt; Node *, 8 &gt;::operator[]</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a5163ef18f80446740383bc2b0a438346">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedName</a>, <a href="/web-llvm/docs/api/classes/podsmallvector/#a8e28eb74c8be25f5a32e9e79db5377e6">PODSmallVector&lt; Node *, 8 &gt;::pop_back</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>, <a href="/web-llvm/docs/api/classes/podsmallvector/#ac5d6d7c223fa5a61d5e21517eece4f4d">PODSmallVector&lt; Node *, 8 &gt;::shrinkToSize</a>, <a href="/web-llvm/docs/api/classes/node/#a1b7da8e0db78730757d05b4580e5fe23">Node::visit</a> and <a href="/web-llvm/docs/api/classes/abstractmanglingparser/scopedtemplateparamlist/#a40750fd12dcee5b7d22f3bfe67d69744">AbstractManglingParser&lt; Derived, Alloc &gt;::ScopedTemplateParamList::~ScopedTemplateParamList</a>.</p>

</div>
</div>

### DEMANGLE\_ATTRIBUTE\_NOINLINE {#ae31d66b34b38535cb9d5abde8c3c3582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_ATTRIBUTE_NOINLINE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### DEMANGLE\_ATTRIBUTE\_USED {#a89bf5498ef5e9915f38a0da6adb156a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_ATTRIBUTE_USED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### DEMANGLE\_DUMP\_METHOD {#a29995d06ac1017b383bd56ca6b624661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_DUMP_METHOD&nbsp;&nbsp;&nbsp;<a href="#ae31d66b34b38535cb9d5abde8c3c3582">DEMANGLE_ATTRIBUTE_NOINLINE</a> <a href="#a89bf5498ef5e9915f38a0da6adb156a3">DEMANGLE_ATTRIBUTE_USED</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/node/#a3a50a546aa28bc9ebd20afd6aff7588d">Node::dump</a>.</p>

</div>
</div>

### DEMANGLE\_FALLTHROUGH {#a5b2ab89559cfa9c7fbfd635bec59e42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_FALLTHROUGH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>.</p>

</div>
</div>

### DEMANGLE\_GNUC\_PREREQ {#a42b2026ea9e750b69b9a9eb3238e9b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_GNUC_PREREQ(maj, min, patch)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### DEMANGLE\_NAMESPACE\_BEGIN {#ad82d307eb10a0e447f4b254f0af7dde7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_NAMESPACE_BEGIN&nbsp;&nbsp;&nbsp;namespace llvm { namespace itanium_demangle {</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### DEMANGLE\_NAMESPACE\_END {#aacd584e2ac8072e41efbd2f3c2e439ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_NAMESPACE_END&nbsp;&nbsp;&nbsp;} }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>

</div>
</div>

### DEMANGLE\_UNREACHABLE {#ae4a4b6b609be6808e094304ae8d981f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEMANGLE_UNREACHABLE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp/#a7156a5e97f96a62c5eb20e59020dd645">demanglePointerCVQualifiers</a>, <a href="/web-llvm/docs/api/classes/expandedspecialsubstitution/#a02a32aa61c5e17a8ca1d46cd9d95287f">ExpandedSpecialSubstitution::getBaseName</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp/#a84f55b36df4657b04741a7e100eb46f2">isMemberPointer</a> and <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
