---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TypeDumpVisitor.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">llvm/DebugInfo/CodeView/TypeDumpVisitor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvtypevisitor-h">llvm/DebugInfo/CodeView/CVTypeVisitor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/recordserialization-h">llvm/DebugInfo/CodeView/RecordSerialization.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typecollection-h">llvm/DebugInfo/CodeView/TypeCollection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typeindex-h">llvm/DebugInfo/CodeView/TypeIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">llvm/DebugInfo/CodeView/TypeRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scopedprinter-h">llvm/Support/ScopedPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "llvm/DebugInfo/CodeView/CodeViewTypes.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b7c4ad3b2bd0c43c8f004ab549476d">getLeafTypeName</a> (TypeLeafKind LT)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad635b4c1cbff12fbcc5bd82bccc5e4f3">LeafTypeNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad22c7410f833f9a848caaf84224a1e53">ClassOptionNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74aae1e96161927c4073061b9fc649b8">MemberAccessNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48fea6294159d40601395c4be1dc2ded">MethodOptionNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bed3f089488e4a011ed0459deb0605d">MemberKindNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae43848a93fe171b520dd2a4e239d3479">PtrKindNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace23ff51e7c9871b192d0c09c1d7904f">PtrModeNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2ea3f0dcca76c5ef3acf264fe68682">PtrMemberRepNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b16e18e0e2ad28cde442bd89b68f27b">TypeModifierNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e63047cdccdfbce88e43c2ef24feb2d">CallingConventions</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5a47ee70b92917ed65aaae4f5015ea">FunctionOptionEnum</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3916e57d26701405b0c277e66551643c">LabelTypeEnum</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad48b9f13746c3a1fbf24114e73bc68c">CV_TYPE</a>(enum, val)&nbsp;&nbsp;&nbsp;{#enum, enum},</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79cfedd2c383af694a381edd740890e7">ENUM_ENTRY</a>(enum_class, enum)&nbsp;&nbsp;&nbsp;  { #enum, std::underlying_type_t&lt;enum_class&gt;(enum_class::enum) }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b05d3547e7db708b50399e317f1c256">TYPE_RECORD</a>(ename, value, name)&nbsp;&nbsp;&nbsp;...</td>
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

### getLeafTypeName() {#a80b7c4ad3b2bd0c43c8f004ab549476d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getLeafTypeName (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a> LT)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#afa470e9dab06e163ce2b08a65ad83fc2">llvm::codeview::TypeDumpVisitor::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a17748af8672ec69e3715d19c6f1d21c8">llvm::codeview::TypeRecordMapping::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a418b79f4288d791e538fa1cf1c4a6960">llvm::codeview::TypeDumpVisitor::visitTypeBegin</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#acf1507b6abe0cb0d10cf17e976fd908d">llvm::codeview::TypeRecordMapping::visitTypeBegin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CallingConventions {#a1e63047cdccdfbce88e43c2ef24feb2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint8_t&gt; CallingConventions[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, NearC),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, FarC),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, NearPascal),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, FarPascal),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, NearFast),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, FarFast),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, NearStdCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, FarStdCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, NearSysCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, FarSysCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, ThisCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, MipsCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcasminfo-cpp/#ad9974102ac4ab550bae0600eca728899a9683fc965be285edded4502f972f9d19">Generic</a>),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, AlphaCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, PpcCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, SHCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, ArmCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, AM33Call),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, TriCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, SH5Call),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, M32RCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, ClrCall),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, Inline),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, NearVector),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5ccb3a995186bdab13527baaee7e4f64">CallingConvention</a>, Swift),
}
</div>
</dd>
</dl>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### ClassOptionNames {#ad22c7410f833f9a848caaf84224a1e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint16_t&gt; ClassOptionNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, Packed),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, HasConstructorOrDestructor),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, HasOverloadedOperator),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, Nested),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, ContainsNestedClass),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, HasOverloadedAssignmentOperator),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, HasConversionOperator),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, ForwardReference),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, Scoped),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, HasUniqueName),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, Sealed),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a>, Intrinsic),
}
</div>
</dd>
</dl>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### FunctionOptionEnum {#a2e5a47ee70b92917ed65aaae4f5015ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint8_t&gt; FunctionOptionEnum[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a819edb1b54a1cf56e9a04ddbb6285947">FunctionOptions</a>, CxxReturnUdt),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a819edb1b54a1cf56e9a04ddbb6285947">FunctionOptions</a>, Constructor),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a819edb1b54a1cf56e9a04ddbb6285947">FunctionOptions</a>, ConstructorWithVirtualBases),
}
</div>
</dd>
</dl>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### LabelTypeEnum {#a3916e57d26701405b0c277e66551643c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint16_t&gt; LabelTypeEnum[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aed2e29ac9478aebf676ae99db3744dd9">LabelType</a>, Near), <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aed2e29ac9478aebf676ae99db3744dd9">LabelType</a>, Far),
}
</div>
</dd>
</dl>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### LeafTypeNames {#ad635b4c1cbff12fbcc5bd82bccc5e4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;TypeLeafKind&gt; LeafTypeNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
#define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/codeview-h/#a79a4fda330142eb38053485494f034e4">CV_TYPE</a>(enum, val)               
}
</div>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#afa470e9dab06e163ce2b08a65ad83fc2">llvm::codeview::TypeDumpVisitor::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a17748af8672ec69e3715d19c6f1d21c8">llvm::codeview::TypeRecordMapping::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a418b79f4288d791e538fa1cf1c4a6960">llvm::codeview::TypeDumpVisitor::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a0b455766e2cade6732d4d6680e4512e4">llvm::codeview::TypeRecordMapping::visitTypeBegin</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a67c74870b34ef151a36efc97cddfaa03">llvm::codeview::TypeDumpVisitor::visitUnknownType</a>.</p>

</div>
</div>

### MemberAccessNames {#a74aae1e96161927c4073061b9fc649b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint8_t&gt; MemberAccessNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac9d3e887722f2bc482bcca9d41c512af">None</a>), <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a>, Private),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a>, Protected), <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a>, Public),
}
</div>
</dd>
</dl>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### MemberKindNames {#a0bed3f089488e4a011ed0459deb0605d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint16_t&gt; MemberKindNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a>, Vanilla),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a>, Virtual),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a>, Static),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a>, Friend),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a>, IntroducingVirtual),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a>, PureVirtual),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a>, PureIntroducingVirtual),
}
</div>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### MethodOptionNames {#a48fea6294159d40601395c4be1dc2ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint16_t&gt; MethodOptionNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a>, Pseudo),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a>, NoInherit),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a>, NoConstruct),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a>, CompilerGenerated),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a>, Sealed),
}
</div>
</dd>
</dl>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### PtrKindNames {#ae43848a93fe171b520dd2a4e239d3479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint8_t&gt; PtrKindNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, Near16),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, Far16),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, Huge16),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, BasedOnSegment),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, BasedOnValue),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, BasedOnSegmentValue),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, BasedOnAddress),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, BasedOnSegmentAddress),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, BasedOnType),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, BasedOnSelf),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, Near32),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, Far32),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38961178be5c492f779ec9ff5929080a">PointerKind</a>, Near64),
}
</div>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### PtrMemberRepNames {#a1e2ea3f0dcca76c5ef3acf264fe68682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint16_t&gt; PtrMemberRepNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fa4e81c184ac3ad48a389cd4454c4a05bb">Unknown</a>),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, SingleInheritanceData),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, MultipleInheritanceData),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, VirtualInheritanceData),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, GeneralData),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, SingleInheritanceFunction),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, MultipleInheritanceFunction),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, VirtualInheritanceFunction),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dd">PointerToMemberRepresentation</a>, GeneralFunction),
}
</div>
</dd>
</dl>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### PtrModeNames {#ace23ff51e7c9871b192d0c09c1d7904f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint8_t&gt; PtrModeNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbc">PointerMode</a>, Pointer),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbc">PointerMode</a>, LValueReference),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbc">PointerMode</a>, PointerToDataMember),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbc">PointerMode</a>, PointerToMemberFunction),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbc">PointerMode</a>, RValueReference),
}
</div>
</dd>
</dl>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### TypeModifierNames {#a1b16e18e0e2ad28cde442bd89b68f27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint16_t&gt; TypeModifierNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6">ModifierOptions</a>, Const), <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6">ModifierOptions</a>, Volatile),
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6">ModifierOptions</a>, Unaligned),
}
</div>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CV\_TYPE {#aad48b9f13746c3a1fbf24114e73bc68c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CV_TYPE(enum, val)&nbsp;&nbsp;&nbsp;{#enum, enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### ENUM\_ENTRY {#a79cfedd2c383af694a381edd740890e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENUM_ENTRY(enum_class, enum)&nbsp;&nbsp;&nbsp;  { #enum, std::underlying_type_t&lt;enum_class&gt;(enum_class::enum) }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### TYPE\_RECORD {#a5b05d3547e7db708b50399e317f1c256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TYPE_RECORD(ename, value, name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case ename:                                                                  \
    return #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;
</div>
</dd>
</dl>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
