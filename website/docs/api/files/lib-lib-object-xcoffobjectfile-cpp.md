---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/xcoffobjectfile-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `XCOFFObjectFile.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">llvm/Object/XCOFFObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
#include &lt;cstddef&gt;
#include &lt;cstring&gt;
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object">object</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2987340f5bfdede1094a2719c29b1ed">ECASE</a>(Value, String)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a43b7de4ad549e67d08dc3204568631">GETVALUEWITHMASK</a>(X)&nbsp;&nbsp;&nbsp;(Data &amp; (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">TracebackTable::X</a>))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37943b0f1a4afe71b6844d00ffe45bc7">GETVALUEWITHMASKSHIFT</a>(X, S)&nbsp;&nbsp;&nbsp;  ((Data &amp; (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">TracebackTable::X</a>)) &gt;&gt; (TracebackTable::S))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7bbaa2557c1860f0dd8d0b49627571d">GETBITWITHMASK</a>(P, X)&nbsp;&nbsp;&nbsp;  (support::endian::read32be(TBPtr + (<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>)) &amp; (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">TracebackTable::X</a>))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d377e9ef962be567c3e56c57f2e391">GETBITWITHMASKSHIFT</a>(P, X, S)&nbsp;&nbsp;&nbsp;...</td>
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

### ECASE {#ad2987340f5bfdede1094a2719c29b1ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ECASE(Value, String)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case XCOFF::Value:                                                           \
    SectionName = String;                                                      \
    break
</div>
</dd>
</dl>

<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a68866f040b091698a4a3bf9c744e263e">llvm::object::XCOFFObjectFile::getSectionFileOffsetToRawData</a>.</p>

</div>
</div>

### GETBITWITHMASK {#aa7bbaa2557c1860f0dd8d0b49627571d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GETBITWITHMASK(P, X)&nbsp;&nbsp;&nbsp;  (support::endian::read32be(TBPtr + (<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>)) &amp; (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">TracebackTable::X</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1552 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#ab28c0ee429cafa247348f8203e885cb6">llvm::object::XCOFFTracebackTable::hasControlledStorage</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a2920e43413447f66eda427b078c6292b">llvm::object::XCOFFTracebackTable::hasExtensionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a2582f57ad756c02e4f6858fdc671522f">llvm::object::XCOFFTracebackTable::hasParmsOnStack</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a1e08791f6ec9452b9e23d91f24e1d66d">llvm::object::XCOFFTracebackTable::hasTraceBackTableOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#aff2daf99314413093594cb83a7e06968">llvm::object::XCOFFTracebackTable::hasVectorInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a85ccdcda7fd816b0267a5f06c19e50c1">llvm::object::XCOFFTracebackTable::isAllocaUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#aea8d99a3954bcaacd307dfc483d7e990">llvm::object::XCOFFTracebackTable::isBackChainStored</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#af7dfc233298521a6de5db9a89b657390">llvm::object::XCOFFTracebackTable::isCRSaved</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#ac76e934fdbae0dfa41423a4ac5b898d7">llvm::object::XCOFFTracebackTable::isFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a606c951be80a63496a28eb40bdd27077">llvm::object::XCOFFTracebackTable::isFloatingPointOperationLogOrAbortEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#acfbec53dab40e06a578fb802531bd6a7">llvm::object::XCOFFTracebackTable::isFloatingPointPresent</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a700e5fde35923aaad8fd23669f3cf6af">llvm::object::XCOFFTracebackTable::isFuncNamePresent</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a93847332036149ac6c0294a7ea285a12">llvm::object::XCOFFTracebackTable::isGlobalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#aad094610325c9dda4f52256d48ea301d">llvm::object::XCOFFTracebackTable::isInternalProcedure</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#ab83b1dadf0e6af5ad4638e3dab6e88bf">llvm::object::XCOFFTracebackTable::isInterruptHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a6b526fbc66024af90fedd9953c52c918">llvm::object::XCOFFTracebackTable::isLRSaved</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a008cdd5a16d9af4007291c30a2eb7196">llvm::object::XCOFFTracebackTable::isOutOfLineEpilogOrPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#afaa754fc5169e3aaaba6ce10a70613ea">llvm::object::XCOFFTracebackTable::isTOCless</a>.</p>

</div>
</div>

### GETBITWITHMASKSHIFT {#a86d377e9ef962be567c3e56c57f2e391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GETBITWITHMASKSHIFT(P, X, S)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  ((support::endian::read32be(TBPtr + (<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>)) &amp; (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">TracebackTable::X</a>)) &gt;&gt;           \
   (TracebackTable::S))
</div>
</dd>
</dl>

<p>Definition at line 1554 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a40d5a8a265e09321c22661c065244a73">llvm::object::XCOFFTracebackTable::getLanguageID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#aed80134da8f9539273705208a5136f22">llvm::object::XCOFFTracebackTable::getNumberOfFixedParms</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a6ddba05c64801cedb2799f034f3136e7">llvm::object::XCOFFTracebackTable::getNumberOfFPParms</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a58b959057f2b7ec6f6f9cd1a93dfaec3">llvm::object::XCOFFTracebackTable::getNumOfFPRsSaved</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a0e8ccec469606bd61be24283e55f408f">llvm::object::XCOFFTracebackTable::getNumOfGPRsSaved</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#a3e0c4370b27ef7385250a560aeb8c9d7">llvm::object::XCOFFTracebackTable::getOnConditionDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#ad1494379a4a3ba899ff895df558bfa89">llvm::object::XCOFFTracebackTable::getVersion</a>.</p>

</div>
</div>

### GETVALUEWITHMASK {#a6a43b7de4ad549e67d08dc3204568631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GETVALUEWITHMASK(X)&nbsp;&nbsp;&nbsp;(Data &amp; (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">TracebackTable::X</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1398 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/tbvectorext/#ae0d98557f1ca6f58bd22fdf3f4e4a9df">llvm::object::TBVectorExt::hasVarArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/object/tbvectorext/#ae7db0371612fb17a86165269f32c6f59">llvm::object::TBVectorExt::hasVMXInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/object/tbvectorext/#a3a3d21671d2b9507aff64c9bfd2e761c">llvm::object::TBVectorExt::isVRSavedOnStack</a>.</p>

</div>
</div>

### GETVALUEWITHMASKSHIFT {#a37943b0f1a4afe71b6844d00ffe45bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GETVALUEWITHMASKSHIFT(X, S)&nbsp;&nbsp;&nbsp;  ((Data &amp; (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">TracebackTable::X</a>)) &gt;&gt; (TracebackTable::S))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1399 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/tbvectorext/#a24aa8a2db4b79eea49cf293c46e1d2ab">llvm::object::TBVectorExt::getNumberOfVectorParms</a> and <a href="/web-llvm/docs/api/classes/llvm/object/tbvectorext/#aa30e6bf1c89df0a329062d86a750bd79">llvm::object::TBVectorExt::getNumberOfVRSaved</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
