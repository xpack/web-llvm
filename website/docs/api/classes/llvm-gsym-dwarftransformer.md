---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/dwarftransformer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DwarfTransformer` Class Reference

<p>A class that transforms the DWARF in a <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> into GSYM information by populating the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> object that it is constructed with. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::gsym::DwarfTransformer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">llvm/DebugInfo/GSYM/DwarfTransformer.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c91050d5c6fc3d6384728949932aacf">DwarfTransformerTest</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add01e9e41d4622cb1f41339d9b61b0ca">DwarfTransformer</a> (DWARFContext &amp;D, GsymCreator &amp;G, bool LDCS=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DWARF transformer. <a href="#add01e9e41d4622cb1f41339d9b61b0ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab014307b03ade42770de6ed2f827630b">convert</a> (uint32_t NumThreads, OutputAggregator &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the DWARF from the supplied object file and convert it into the Gsym format in the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> object that is passed in. <a href="#ab014307b03ade42770de6ed2f827630b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40e6efe1caf07771eb6713f41db076b">verify</a> (StringRef GsymPath, OutputAggregator &amp;OS)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e42a812914e009c88b73bfb871c34d">parse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the DWARF in the object file and convert it into the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>. <a href="#a67e42a812914e009c88b73bfb871c34d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d43ff9554a810dc5a639325f75b6bc">handleDie</a> (OutputAggregator &amp;Strm, CUInfo &amp;CUI, DWARFDie Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle any <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (debug info entry) from the DWARF. <a href="#ac5d43ff9554a810dc5a639325f75b6bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a195b43736cb7d969aac6514f87769a9b">parseCallSiteInfoFromDwarf</a> (CUInfo &amp;CUI, DWARFDie Die, FunctionInfo &amp;FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse call site information from DWARF. <a href="#a195b43736cb7d969aac6514f87769a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb79bec4f9bb4f4e253f021bcb52217f">DICtx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc806330c7d4faebe6f0e47fda863a8">Gsym</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d87ba24f759d4af0ad0d664829ed9c">LoadDwarfCallSites</a></td>
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

## Description {#details}

<p>A class that transforms the DWARF in a <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> into GSYM information by populating the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> object that it is constructed with.</p>


<p>This class supports converting all DW_TAG_subprogram DIEs into <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">gsym::FunctionInfo</a> objects that includes line table information and inline function information. Creating a separate class to transform this data allows this class to be unit tested.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>.</p>


<div class="doxySectionDef">

## Friends

### DwarfTransformerTest {#a5c91050d5c6fc3d6384728949932aacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class DwarfTransformerTest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>.</p>


<p>Reference <a href="#a5c91050d5c6fc3d6384728949932aacf">DwarfTransformerTest</a>.</p>


<p>Referenced by <a href="#a5c91050d5c6fc3d6384728949932aacf">DwarfTransformerTest</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfTransformer() {#add01e9e41d4622cb1f41339d9b61b0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::DwarfTransformer::DwarfTransformer (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; D, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; G, bool LDCS=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a DWARF transformer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">D</td>
<td class="doxyParamItemDescription"><p>The DWARF to use when converting to GSYM.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">G</td>
<td class="doxyParamItemDescription"><p>The GSYM creator to populate with the function information from the debug info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LDCS</td>
<td class="doxyParamItemDescription"><p>Flag to indicate whether we should load the call site information from DWARF <span class="doxyComputerOutput">DW_TAG_call_site</span> entries</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convert() {#ab014307b03ade42770de6ed2f827630b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfTransformer::convert (uint32_t NumThreads, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the DWARF from the supplied object file and convert it into the Gsym format in the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> object that is passed in.</p>


<p>Returns an error if something fatal is encountered.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumThreads</td>
<td class="doxyParamItemDescription"><p>The number of threads that the conversion process can use.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The stream to log warnings and non fatal issues to. If NULL then don't log.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error indicating any fatal issues that happen when parsing the DWARF, or <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a> if all goes well.</p></dd>
</dl>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface/#ad43d0052f680e6ac08426d8821df178d">llvm::ThreadPoolInterface::async</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#ac1be2c7a42ac407e8eac9396768207dc">llvm::gsym::OutputAggregator::GetOS</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">llvm::DWARFUnit::getUnitDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00440f10281348fd9f7be52e23c7c874">llvm::hardware_concurrency</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afd5def6886f14df2575567385872bd04">llvm::DWARFUnit::isDWOUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#af65bf7475eed416d9de9a4a5e5e5ad2f">llvm::gsym::OutputAggregator::Merge</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#a051eee638f618d1ebe54f433350b7c1d">llvm::gsym::OutputAggregator::Report</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a> and <a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor/#a4a9fc38bb7d9ff3f944e25971330cb42">llvm::SingleThreadExecutor::wait</a>.</p>

</div>
</div>

### verify() {#ac40e6efe1caf07771eb6713f41db076b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error DwarfTransformer::verify (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GsymPath, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2">llvm::DILineInfoSpecifier::AbsoluteFilePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#ac1be2c7a42ac407e8eac9396768207dc">llvm::gsym::OutputAggregator::GetOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#abedaa94d52e9958ad4a0d3790d0e4451">HEX64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a3cc6f8b4a312834f3683fa1a90bda0ed">llvm::gsym::GsymReader::openFile</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5965d701dc0010fd1a664b306c42dab5">llvm::gsym::FunctionInfo::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handleDie() {#ac5d43ff9554a810dc5a639325f75b6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfTransformer::handleDie (<a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; Strm, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo">CUInfo</a> &amp; CUI, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle any <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (debug info entry) from the DWARF.</p>


<p>This function will find all DW_TAG_subprogram DIEs that convert them into GSYM FuntionInfo objects and add them to the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> supplied during construction. The <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and all its children will be recursively parsed with calls to this function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Strm</td>
<td class="doxyParamItemDescription"><p>The thread specific log stream for any non fatal errors and warnings. Once a thread has finished parsing an entire compile unit, all information in this temporary stream will be forwarded to the member variable log. This keeps logging thread safe. If the value is NULL, then don't log.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CUI</td>
<td class="doxyParamItemDescription"><p>The compile unit specific information that contains the DWARF line table, cached file list, and other compile unit specific information.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>The DWARF debug info entry to parse.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>

</div>
</div>

### parse() {#a67e42a812914e009c88b73bfb871c34d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::gsym::DwarfTransformer::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the DWARF in the object file and convert it into the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>.</p>

</div>
</div>

### parseCallSiteInfoFromDwarf() {#a195b43736cb7d969aac6514f87769a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfTransformer::parseCallSiteInfoFromDwarf (<a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo">CUInfo</a> &amp; CUI, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse call site information from DWARF.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CUI</td>
<td class="doxyParamItemDescription"><p>The compile unit info for the current <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> for the function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FI</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> for the function being populated.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>, definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DICtx {#adb79bec4f9bb4f4e253f021bcb52217f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext&amp; llvm::gsym::DwarfTransformer::DICtx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>.</p>

</div>
</div>

### Gsym {#a9dc806330c7d4faebe6f0e47fda863a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GsymCreator&amp; llvm::gsym::DwarfTransformer::Gsym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>.</p>

</div>
</div>

### LoadDwarfCallSites {#aa7d87ba24f759d4af0ad0d664829ed9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::DwarfTransformer::LoadDwarfCallSites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">DwarfTransformer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
