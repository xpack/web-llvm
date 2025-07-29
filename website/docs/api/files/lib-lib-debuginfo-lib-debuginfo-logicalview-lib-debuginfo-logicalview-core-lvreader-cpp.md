---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LVReader.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">llvm/DebugInfo/LogicalView/Core/LVReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">llvm/DebugInfo/LogicalView/Core/LVScope.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatadapters-h">llvm/Support/FormatAdapters.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include &lt;tuple&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a4be4c21b1fd5b45a71fd7218bdae50">checkIntegrityScopesTree</a> (LVScope *Root)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e17b013ab2110ffddcd384661f95de">CurrentReader</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"Reader"</td>
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

### checkIntegrityScopesTree() {#a4a4be4c21b1fd5b45a71fd7218bdae50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkIntegrityScopesTree (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa0b410adc9d388e4b57d36f90ed136ad">llvm::fmt_repeat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ab9b372fe51a0c6c8ef2e0565f28c5b4f">llvm::logicalview::LVObject::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a0f19e485d0c49a007d820b8d37bd6578">llvm::logicalview::LVScope::getLines</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a37fc81a3671c77ca160274dfa7a6d9fb">llvm::logicalview::LVScope::getScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a50bf7e1dad623fab3b0d3f1673d10090">llvm::logicalview::LVScope::getSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a8800edbf399aa751c03f610600b6e424">llvm::logicalview::LVScope::getTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a45d9cf6ff4c3deab0bcbe25c75d27826af3f97de67c80480904f958df15b8a57b">llvm::logicalview::Integrity</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a1a089d5c3ae5d6ed73718b9168061f53">llvm::logicalview::LVObject::kind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38ba48b26d57c14af0500090800c2cdd0d58">llvm::logicalview::Scopes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a8a15ec2eff468d1dc1137a8a8f20f525">llvm::logicalview::LVReader::doLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CurrentReader {#a08e17b013ab2110ffddcd384661f95de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVReader* CurrentReader = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aa7f00af39c0390ab78b03370eb251266">llvm::logicalview::LVReader::getInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ab170f24e5d76fee6ae66e469f43564f3">llvm::logicalview::LVReader::setInstance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"Reader"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
