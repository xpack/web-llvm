---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/formatutil-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `FormatUtil.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/formatutil-h">llvm/DebugInfo/PDB/Native/FormatUtil.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlforwardcompat-h">llvm/ADT/STLForwardCompat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">llvm/BinaryFormat/COFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/codeview-h">llvm/DebugInfo/CodeView/CodeView.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatadapters-h">llvm/Support/FormatAdapters.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "llvm/DebugInfo/CodeView/CodeViewSymbols.def"
#include "llvm/DebugInfo/CodeView/CodeViewTypes.def"
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ace201d14e8c0ccdc014c43ebc5e359">SYMBOL_RECORD</a>(EnumName, value, name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7087fb5ede351d41e454476fb23b74c9">CV_SYMBOL</a>(EnumName, value)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/codeview-h/#a867e55fc9dff8311dfaf572c75836e38">SYMBOL_RECORD</a>(<a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#acef8933dc7a42bfe29ce8c62e08fe2a8">EnumName</a>, value, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#acef8933dc7a42bfe29ce8c62e08fe2a8">EnumName</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7619ff56c3e842fc5ba839cd8d7ac991">TYPE_RECORD</a>(EnumName, value, name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5e6792f0e616e84538b51bedf42d15">PUSH_CHARACTERISTIC_FLAG</a>(Enum, TheOpt, Value, Style, Descriptive)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34d119de613abec26f6437963f0ab22">PUSH_MASKED_CHARACTERISTIC_FLAG</a>(Enum, Mask, TheOpt, Value, Style, Descriptive)&nbsp;&nbsp;&nbsp;...</td>
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

### CV\_SYMBOL {#a7087fb5ede351d41e454476fb23b74c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_SYMBOL(EnumName, value)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/codeview-h/#a867e55fc9dff8311dfaf572c75836e38">SYMBOL_RECORD</a>(<a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#acef8933dc7a42bfe29ce8c62e08fe2a8">EnumName</a>, value, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#acef8933dc7a42bfe29ce8c62e08fe2a8">EnumName</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/formatutil-cpp">FormatUtil.cpp</a>.</p>

</div>
</div>

### PUSH\_CHARACTERISTIC\_FLAG {#acf5e6792f0e616e84538b51bedf42d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PUSH_CHARACTERISTIC_FLAG(Enum, TheOpt, Value, Style, Descriptive)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/formatutil-h/#aee5373e8d2bad696e5fcd54ad634a041">PUSH_FLAG</a>(Enum, TheOpt, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>,                                               \
            ((Style == CharacteristicStyle::HeaderDefinition) ? #TheOpt        \
                                                              : Descriptive))
</div>
</dd>
</dl>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/formatutil-cpp">FormatUtil.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#acdab50aa4b126b5c497c1b9ab58e0223">llvm::pdb::formatSectionCharacteristics</a>.</p>

</div>
</div>

### PUSH\_MASKED\_CHARACTERISTIC\_FLAG {#ae34d119de613abec26f6437963f0ab22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PUSH_MASKED_CHARACTERISTIC_FLAG(Enum, Mask, TheOpt, Value, Style, Descriptive)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/formatutil-h/#a24fa9b16639c46cac7d271261d64dcc6">PUSH_MASKED_FLAG</a>(Enum, Mask, TheOpt, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>,                                  \
                   ((Style == CharacteristicStyle::HeaderDefinition)           \
                        ? #TheOpt                                              \
                        : Descriptive))
</div>
</dd>
</dl>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/formatutil-cpp">FormatUtil.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#acdab50aa4b126b5c497c1b9ab58e0223">llvm::pdb::formatSectionCharacteristics</a>.</p>

</div>
</div>

### SYMBOL\_RECORD {#a9ace201d14e8c0ccdc014c43ebc5e359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SYMBOL_RECORD(EnumName, value, name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case EnumName:                                                               \
    return #<a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#acef8933dc7a42bfe29ce8c62e08fe2a8">EnumName</a>;
</div>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/formatutil-cpp">FormatUtil.cpp</a>.</p>

</div>
</div>

### TYPE\_RECORD {#a7619ff56c3e842fc5ba839cd8d7ac991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TYPE_RECORD(EnumName, value, name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case EnumName:                                                               \
    return #<a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#acef8933dc7a42bfe29ce8c62e08fe2a8">EnumName</a>;
</div>
</dd>
</dl>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/formatutil-cpp">FormatUtil.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
