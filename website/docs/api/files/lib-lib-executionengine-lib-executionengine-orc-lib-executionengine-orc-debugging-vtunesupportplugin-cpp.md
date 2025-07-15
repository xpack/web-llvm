---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/vtunesupportplugin-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `VTuneSupportPlugin.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/debugging/vtunesupportplugin-h">llvm/ExecutionEngine/Orc/Debugging/VTuneSupportPlugin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">llvm/DebugInfo/DWARF/DWARFContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/debugging/debuginfosupport-h">llvm/ExecutionEngine/Orc/Debugging/DebugInfoSupport.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/vtunemethodbatch">VTuneMethodBatch</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa020804a705b3d1641b730840880ae12">getMethodBatch</a> (LinkGraph &amp;G, bool EmitDebugInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e9bfa797e648c0cee668ceef3f6fbf">RegisterVTuneImplName</a> = "llvm_orc_registerVTuneImpl"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e9984738e9101d52ed0c4fa92e91de5">UnregisterVTuneImplName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687a64c67b7b67987d7bce4ca8435487">RegisterTestVTuneImplName</a> = ...</td>
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

### getMethodBatch() {#aa020804a705b3d1641b730840880ae12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VTuneMethodBatch getMethodBatch (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, bool EmitDebugInfo)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/vtunesupportplugin-cpp">VTuneSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2">llvm::DILineInfoSpecifier::AbsoluteFilePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a9ecb3cb1036963ce01100bfddac5791f">llvm::orc::createDWARFContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section/#a46c35148a73ab51b69108948f0361d52">llvm::jitlink::Section::getOrdinal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/vtunemethodbatch/#aa63fd9436c42d31236324d97fc303d4b">llvm::orc::VTuneMethodBatch::Methods</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/vtunemethodbatch/#afa10d580670187d5e346eb9fc87ff5c9">llvm::orc::VTuneMethodBatch::Strings</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a853290f0b4ae904b8ab68e6a06f8bab9">llvm::orc::VTuneSupportPlugin::modifyPassConfig</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### RegisterTestVTuneImplName {#a687a64c67b7b67987d7bce4ca8435487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RegisterTestVTuneImplName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
<div class="doxyVerbatim">=
    "llvm_orc_test_registerVTuneImpl"
</div>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/vtunesupportplugin-cpp">VTuneSupportPlugin.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a384229b970be55d5cfaaf058b693bd73">llvm::orc::VTuneSupportPlugin::Create</a>.</p>

</div>
</div>

### RegisterVTuneImplName {#a62e9bfa797e648c0cee668ceef3f6fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RegisterVTuneImplName = "llvm_orc_registerVTuneImpl"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/vtunesupportplugin-cpp">VTuneSupportPlugin.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a384229b970be55d5cfaaf058b693bd73">llvm::orc::VTuneSupportPlugin::Create</a>.</p>

</div>
</div>

### UnregisterVTuneImplName {#a7e9984738e9101d52ed0c4fa92e91de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef UnregisterVTuneImplName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
<div class="doxyVerbatim">=
    "llvm_orc_unregisterVTuneImpl"
</div>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/vtunesupportplugin-cpp">VTuneSupportPlugin.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a384229b970be55d5cfaaf058b693bd73">llvm::orc::VTuneSupportPlugin::Create</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
