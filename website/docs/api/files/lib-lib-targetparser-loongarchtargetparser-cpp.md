---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/targetparser/loongarchtargetparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LoongArchTargetParser.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">llvm/TargetParser/LoongArchTargetParser.h</a>"
#include "llvm/TargetParser/LoongArchTargetParser.def"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/loongarch/featureinfo">FeatureInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacf0aaeeb21e1630ab574012e090e8c0">AllFeatures</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/loongarch/archinfo">ArchInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78bd80a2904c84003183a2a34356a60">AllArchs</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad735198fd3bde837d28a14903a5c60ad">LOONGARCH_FEATURE</a>(NAME, KIND)&nbsp;&nbsp;&nbsp;{NAME, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>},</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a319f7388e74a5ee4237e06d095ba1d76">LOONGARCH_ARCH</a>(NAME, KIND, FEATURES)&nbsp;&nbsp;&nbsp;  {NAME, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">LoongArch::ArchKind::KIND</a>, FEATURES},</td>
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

## Variables

### AllArchs {#ad78bd80a2904c84003183a2a34356a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArchInfo AllArchs[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
#define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h/#a319f7388e74a5ee4237e06d095ba1d76">LOONGARCH_ARCH</a>(NAME, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>, FEATURES)                                   \
}
</div>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#af7c8d1932dbd377676019145bc7efa80">llvm::LoongArch::fillValidCPUList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a409838e230dbdf71fd3a268819adf0fc">llvm::LoongArch::getArchFeatures</a> and <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a9ed55f5a0ac555b889c11ff633ae1eba">llvm::LoongArch::isValidArchName</a>.</p>

</div>
</div>

### AllFeatures {#aacf0aaeeb21e1630ab574012e090e8c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FeatureInfo AllFeatures[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
#define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h/#ad735198fd3bde837d28a14903a5c60ad">LOONGARCH_FEATURE</a>(NAME, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>)              
}
</div>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a409838e230dbdf71fd3a268819adf0fc">llvm::LoongArch::getArchFeatures</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a07c54e53e4d7a7ec84aa30d37f888f62">getBBAddrMapFeature</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LOONGARCH\_ARCH {#a319f7388e74a5ee4237e06d095ba1d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOONGARCH_ARCH(NAME, KIND, FEATURES)&nbsp;&nbsp;&nbsp;  {NAME, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">LoongArch::ArchKind::KIND</a>, FEATURES},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>

</div>
</div>

### LOONGARCH\_FEATURE {#ad735198fd3bde837d28a14903a5c60ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOONGARCH_FEATURE(NAME, KIND)&nbsp;&nbsp;&nbsp;{NAME, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
