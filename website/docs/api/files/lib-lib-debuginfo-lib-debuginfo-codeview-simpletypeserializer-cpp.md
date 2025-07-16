---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SimpleTypeSerializer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/simpletypeserializer-h">llvm/DebugInfo/CodeView/SimpleTypeSerializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">llvm/DebugInfo/CodeView/CVRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/recordserialization-h">llvm/DebugInfo/CodeView/RecordSerialization.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecordmapping-h">llvm/DebugInfo/CodeView/TypeRecordMapping.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">llvm/Support/BinaryStreamWriter.h</a>"
#include "llvm/DebugInfo/CodeView/CodeViewTypes.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9446f182f86fd8c4dca65264de68235">addPadding</a> (BinaryStreamWriter &amp;Writer)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d11e871152d859e7fb222dc85062939">TYPE_RECORD</a>(EnumName, EnumVal, Name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20667bfca00228293401f73e44819dd">TYPE_RECORD_ALIAS</a>(EnumName, EnumVal, Name, AliasName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b16f4dbbd88785710796e29d4f4743d">MEMBER_RECORD</a>(EnumName, EnumVal, Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8db34f7d2a98cf7abe667fd517b62a">MEMBER_RECORD_ALIAS</a>(EnumName, EnumVal, Name, AliasName)</td>
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

## Functions

### addPadding() {#ae9446f182f86fd8c4dca65264de68235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addPadding (<a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a> &amp; Writer)</td>
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



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp">SimpleTypeSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a2d1fbfecba0a643a1db961c9f9313b6e">llvm::BinaryStreamWriter::getOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a344647bc1c4a4b53334296eba145d408">llvm::BinaryStreamWriter::writeInteger</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### MEMBER\_RECORD {#a9b16f4dbbd88785710796e29d4f4743d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MEMBER_RECORD(EnumName, EnumVal, Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp">SimpleTypeSerializer.cpp</a>.</p>

</div>
</div>

### MEMBER\_RECORD\_ALIAS {#a3e8db34f7d2a98cf7abe667fd517b62a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MEMBER_RECORD_ALIAS(EnumName, EnumVal, Name, AliasName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp">SimpleTypeSerializer.cpp</a>.</p>

</div>
</div>

### TYPE\_RECORD {#a4d11e871152d859e7fb222dc85062939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TYPE_RECORD(EnumName, EnumVal, Name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  template <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt; <a href="/web-llvm/docs/api/classes/llvm/codeview/simpletypeserializer/#ae10015a36f68325417d06aa9ab5bce62">llvm::codeview::SimpleTypeSerializer::serialize</a>(  \
      Name##<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> &amp;<a href="/web-llvm/docs/api/classes/llvm/record">Record</a>);
</div>
</dd>
</dl>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp">SimpleTypeSerializer.cpp</a>.</p>

</div>
</div>

### TYPE\_RECORD\_ALIAS {#ae20667bfca00228293401f73e44819dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TYPE_RECORD_ALIAS(EnumName, EnumVal, Name, AliasName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp">SimpleTypeSerializer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
