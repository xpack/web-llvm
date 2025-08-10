---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/textapi/recordsslice-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `RecordsSlice.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">llvm/TextAPI/RecordsSlice.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">llvm/TextAPI/InterfaceFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">llvm/TextAPI/Record.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">llvm/TextAPI/Symbol.h</a>"
#include &lt;utility&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename R, typename C = RecordMap&lt;R&gt;, typename K = StringRef&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">R *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af60cd1eab7adb7cd85da1dfb85cbcf6e">findRecord</a> (K Key, const C &amp;Container)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00dbc6acb875da93238279fefb59d61a">createInterfaceFile</a> (const Records &amp;Slices, StringRef InstallName)</td>
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

### createInterfaceFile() {#a00dbc6acb875da93238279fefb59d61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; InterfaceFile &gt; createInterfaceFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab5b5510db9083f228e5929bf5ad0f717">Records</a> &amp; Slices, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InstallName)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a1791d8f2479498108806004349608d3c">Converter</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8a59001c151594d4ff93a12b10c8368f">llvm::MachO::convertToInterfaceFile</a>.</p>

</div>
</div>

### findRecord() {#af60cd1eab7adb7cd85da1dfb85cbcf6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename R, typename C = RecordMap&lt;R&gt;, typename K = StringRef&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R * findRecord (K Key, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a> &amp; Container)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice/#a5bbe48203c60ad199df294db71d6266b">llvm::MachO::RecordsSlice::findGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice/#a610e5bcdea09f9e1c7c7fe44586ab7d0">llvm::MachO::RecordsSlice::findObjCCategory</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice/#a982260c34d9834df05612c79c319dea4">llvm::MachO::RecordsSlice::findObjCInterface</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a9669b1c810efd98e1173f2b0ca56aa0d">llvm::MachO::ObjCContainerRecord::findObjCIVar</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
