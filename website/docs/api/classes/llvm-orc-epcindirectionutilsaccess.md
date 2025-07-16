---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcindirectionutilsaccess
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EPCIndirectionUtilsAccess` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCIndirectionUtilsAccess { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-epcindirectionutils-cpp-/epcindirectstubsmanager">EPCIndirectStubsManager</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04570231559936d47595b1b4375a1879">IndirectStubInfo</a> = EPCIndirectionUtils::IndirectStubInfo</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c16c35ac2ab1caf1015c6a1cdddb45f">IndirectStubInfoVector</a> = EPCIndirectionUtils::IndirectStubInfoVector</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a9c16c35ac2ab1caf1015c6a1cdddb45f">IndirectStubInfoVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149dbb627bef5934546b4d8cade41078">getIndirectStubs</a> (EPCIndirectionUtils &amp;EPCIU, unsigned NumStubs)</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### IndirectStubInfo {#a04570231559936d47595b1b4375a1879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCIndirectionUtilsAccess::IndirectStubInfo =  EPCIndirectionUtils::IndirectStubInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

### IndirectStubInfoVector {#a9c16c35ac2ab1caf1015c6a1cdddb45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCIndirectionUtilsAccess::IndirectStubInfoVector =  EPCIndirectionUtils::IndirectStubInfoVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getIndirectStubs() {#a149dbb627bef5934546b4d8cade41078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; IndirectStubInfoVector &gt; llvm::orc::EPCIndirectionUtilsAccess::getIndirectStubs (<a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &amp; EPCIU, unsigned NumStubs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-epcindirectionutils-cpp-/epcindirectstubsmanager/#a199b61ddf7d2eb6a93f8a41d61e41647">anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::createStubs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
