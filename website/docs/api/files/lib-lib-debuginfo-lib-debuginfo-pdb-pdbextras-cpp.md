---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PDBExtras.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbextras-h">llvm/DebugInfo/PDB/PDBExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "llvm/DebugInfo/CodeView/CodeViewRegisters.def"
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec95b8ea23a4368890d912be4df14966">CASE_OUTPUT_ENUM_CLASS_STR</a>(Class, Value, Str, Stream)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab472b4a9ebd411959cadb807f98f43aa">CASE_OUTPUT_ENUM_CLASS_NAME</a>(Class, Value, Stream)&nbsp;&nbsp;&nbsp;  <a href="#aec95b8ea23a4368890d912be4df14966">CASE_OUTPUT_ENUM_CLASS_STR</a>(Class, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, #<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf65606b945f0eea3bf6e7c6feab0db">CV_REGISTERS_ARM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a1cb1ef009501bd19178fbb688059eb">CV_REGISTER</a>(name, val)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2309a310b8c7faa5fc48303f7f8b94e4">CV_REGISTERS_ARM64</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af355f45cd619cefa3fe593733d729067">CV_REGISTER</a>(name, val)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae16e28a1116e73952916b766d2cf5bdd">CV_REGISTERS_X86</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a262f56481a9f97eb34dbf85556ee6375">CV_REGISTER</a>(name, val)&nbsp;&nbsp;&nbsp;...</td>
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

### CASE\_OUTPUT\_ENUM\_CLASS\_NAME {#ab472b4a9ebd411959cadb807f98f43aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_OUTPUT_ENUM_CLASS_NAME(Class, Value, Stream)&nbsp;&nbsp;&nbsp;  <a href="#aec95b8ea23a4368890d912be4df14966">CASE_OUTPUT_ENUM_CLASS_STR</a>(Class, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, #<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ab1a71866c0d31546354a1ea154ce9706">llvm::pdb::dumpPDBSourceCompression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a76cbde541b043012058162c42f442554">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a642ea31acb6fcfb819f51a324f8f113d">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac500159f2d917a7b7750d0c6b35863e7">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1001f60a26865481fd643fa191551996">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a3d857a172454acee51c2ee46b613ab26">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a26a09a63541163eb221552ecfb253acc">llvm::pdb::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a9301eea291e2de0d20436922f8b78cea">llvm::pdb::operator&lt;&lt;</a>.</p>

</div>
</div>

### CASE\_OUTPUT\_ENUM\_CLASS\_STR {#aec95b8ea23a4368890d912be4df14966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_OUTPUT_ENUM_CLASS_STR(Class, Value, Str, Stream)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Class::Value:                                                           \
    Stream &lt;&lt; Str;                                                             \
    break;
</div>
</dd>
</dl>

<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ab1a71866c0d31546354a1ea154ce9706">llvm::pdb::dumpPDBSourceCompression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a387d9c1513d728300277f7675be8b657">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a3bf9d5bf0a24de98ea446bea2fafdda7">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1001f60a26865481fd643fa191551996">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a686961db1872047c7429a3f94924fafe">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#af813ac1290df3ad2f9c1e5640d79cf07">llvm::pdb::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a85bc7efc443921725de056bc2a31de9d">llvm::pdb::operator&lt;&lt;</a>.</p>

</div>
</div>

### CV\_REGISTER {#a1a1cb1ef009501bd19178fbb688059eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_REGISTER(name, val)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case codeview::RegisterId::name:                                             \
    OS &lt;&lt; #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;                                                               \
    return OS;
</div>
</dd>
</dl>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>

</div>
</div>

### CV\_REGISTER {#af355f45cd619cefa3fe593733d729067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_REGISTER(name, val)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case codeview::RegisterId::name:                                             \
    OS &lt;&lt; #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;                                                               \
    return OS;
</div>
</dd>
</dl>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>

</div>
</div>

### CV\_REGISTER {#a262f56481a9f97eb34dbf85556ee6375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_REGISTER(name, val)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case codeview::RegisterId::name:                                             \
    OS &lt;&lt; #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;                                                               \
    return OS;
</div>
</dd>
</dl>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>

</div>
</div>

### CV\_REGISTERS\_ARM {#afaf65606b945f0eea3bf6e7c6feab0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_REGISTERS_ARM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>

</div>
</div>

### CV\_REGISTERS\_ARM64 {#a2309a310b8c7faa5fc48303f7f8b94e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_REGISTERS_ARM64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>

</div>
</div>

### CV\_REGISTERS\_X86 {#ae16e28a1116e73952916b766d2cf5bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_REGISTERS_X86</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbextras-cpp">PDBExtras.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
