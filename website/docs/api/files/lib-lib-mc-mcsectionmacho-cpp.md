---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mcsectionmacho-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MCSectionMachO.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">llvm/MC/MCSectionMachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">llvm/MC/SectionKind.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fc2a7c27ca977660fbf4c84aee3da7">AssemblerName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acef8933dc7a42bfe29ce8c62e08fe2a8">EnumName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b6520d99fc98f9e19785696dc7ae4f1">SectionTypeDescriptors</a>[MachO::LAST_KNOWN_SECTION_TYPE+1]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SectionTypeDescriptors - These are strings that describe the various section types. <a href="#a5b6520d99fc98f9e19785696dc7ae4f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ff3c3a24eb70dad710bab309549b283">AttrFlag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8040205b8d0f2b27405bdd5606f7f3c0">SectionAttrDescriptors</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SectionAttrDescriptors - This is an array of descriptors for section attributes. <a href="#a8040205b8d0f2b27405bdd5606f7f3c0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(ASMNAME, ENUM)&nbsp;&nbsp;&nbsp;  { <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">MachO::ENUM</a>, <a href="/web-llvm/docs/api/classes/stringliteral">StringLiteral</a>(ASMNAME), <a href="/web-llvm/docs/api/classes/stringliteral">StringLiteral</a>(#<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>) },</td>
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

### AssemblerName {#ad2fc2a7c27ca977660fbf4c84aee3da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral AssemblerName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#adaebfb20a6b5145fda04f26aa65a47ae">llvm::MCSectionMachO::printSwitchToSection</a>.</p>

</div>
</div>

### AttrFlag {#a1ff3c3a24eb70dad710bab309549b283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AttrFlag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#adaebfb20a6b5145fda04f26aa65a47ae">llvm::MCSectionMachO::printSwitchToSection</a>.</p>

</div>
</div>

### EnumName {#acef8933dc7a42bfe29ce8c62e08fe2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral EnumName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>

</div>
</div>

### SectionAttrDescriptors {#a8040205b8d0f2b27405bdd5606f7f3c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct  SectionAttrDescriptors[]</td>
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

<p>SectionAttrDescriptors - This is an array of descriptors for section attributes.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
#define <a href="#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(ASMNAME, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>) \
  { 0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a>("none"), <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a>("") }, 
}
</div>
</dd>
</dl>


<p>Unlike the SectionTypeDescriptors, this is not directly indexed by attribute, instead it is searched.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a1ea0b527a25e96bb74c8217704b22a07">llvm::MCSectionMachO::ParseSectionSpecifier</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#adaebfb20a6b5145fda04f26aa65a47ae">llvm::MCSectionMachO::printSwitchToSection</a>.</p>

</div>
</div>

### SectionTypeDescriptors {#a5b6520d99fc98f9e19785696dc7ae4f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct  SectionTypeDescriptors[MachO::LAST_KNOWN_SECTION_TYPE + 1]</td>
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

<p>SectionTypeDescriptors - These are strings that describe the various section types.</p>


<p>This <em>must</em> be kept in order with and stay synchronized with the section type list.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a1ea0b527a25e96bb74c8217704b22a07">llvm::MCSectionMachO::ParseSectionSpecifier</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#adaebfb20a6b5145fda04f26aa65a47ae">llvm::MCSectionMachO::printSwitchToSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ENTRY {#ac87f60246b2a01df58ca032da8463a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(ASMNAME, ENUM)&nbsp;&nbsp;&nbsp;  { <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">MachO::ENUM</a>, <a href="/web-llvm/docs/api/classes/stringliteral">StringLiteral</a>(ASMNAME), <a href="/web-llvm/docs/api/classes/stringliteral">StringLiteral</a>(#<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/clauset-h/#a9f45f010de76e982a57b1b875fcb44e3">ENUM</a>) },</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp">MCSectionMachO.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
