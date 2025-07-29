---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/profiledata/instrprof-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `InstrProf.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitmaskenum-h">llvm/ADT/BitmaskEnum.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">llvm/ADT/StringSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profilesummary-h">llvm/IR/ProfileSummary.h</a>"
#include "llvm/ProfileData/InstrProfData.inc"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">llvm/Support/BalancedPartitioning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;cstring&gt;
#include &lt;list&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;system_error&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof">IndexedInstrProf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rawinstrprof">RawInstrProf</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/temporalproftracety">TemporalProfTraceTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An ordered list of functions identified by their NameRef found in INSTR_PROF_DATA. <a href="/web-llvm/docs/api/structs/llvm/temporalproftracety/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrproferror">InstrProfError</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A symbol table used for function [IR]PGO name look-up with keys (such as pointers, md5hash values) to the function. <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/overlapfuncfilters">OverlapFuncFilters</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profiling information for a single function. <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valueprofdata">ValueProfData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function header/control data structure for value profiling data in indexed format. <a href="/web-llvm/docs/api/structs/llvm/valueprofdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valueprofrecordclosure">ValueProfRecordClosure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/header">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary">Summary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/entry">Entry</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rawinstrprof/profiledata">ProfileData&lt;IntPtrT&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rawinstrprof/vtableprofiledata">VTableProfileData&lt;IntPtrT&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rawinstrprof/header">Header</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a0a1c07b5e2873b5c3dc58e3596aba4">INSTR_PROF_SECT_ENTRY</a>(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;Kind,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a991a4b9fc0060d2c13c2609e8dbd5c48">INSTR_PROF_VISIBILITY</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a964fe748db42abb3035346a85f7aa3b9">INSTR_PROF_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fffbf1bcdf0b73994e7d71af9fda706">INSTR_PROF_VTABLE_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2039a5308a9a7aecdfc29f45d1a04fb7">INSTR_PROF_VALUE_NODE</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05e05e47a5f9945cf30597645458686">INSTR_PROF_RAW_HEADER</a>(Type, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b37e795b394a273b4adca2984d0c5c">VALUE_PROF_FUNC_PARAM</a>(ArgType, ArgName, ArgLLVMType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec3bc606baecfea5832789f9b4f998b">INSTR_PROF_COMMA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2558cb097460e2dfa5315ec18c38c24">VALUE_PROF_KIND</a>(Enumerator, Value, Descr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b82a7fc9ea6b68d597e54245e85f21b">COVMAP_FUNC_RECORD</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac825b81edfa1cf2df4102c9c34f821e4">COVMAP_HEADER</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0af632e6ce572cbccbe06f3cd5383e2">COVINIT_FUNC</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461567c719c6f8cd15517aec497c5ecf">INSTR_PROF_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806f28489e8f6c6c347485fbc3ef50a6">VALUE_PROF_KIND</a>(Enumerator, Value, Descr)&nbsp;&nbsp;&nbsp;Enumerator = Value,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61629fdb389d51542976cbea4c4ebd75">INSTR_PROF_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092a23d90c264232a2c4b67b64cf9f71">INSTR_PROF_VTABLE_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0cb095fe390c2e0d64636a856e5267">INSTR_PROF_VALUE_NODE</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a48c3c420871c8895aa03e069452a3a">INSTR_PROF_RAW_HEADER</a>(Type, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c1bbac0b84ba640670d7cfb8d46c62">VALUE_PROF_FUNC_PARAM</a>(ArgType, ArgName, ArgLLVMType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10b7a2548ea86ccc6388b280ead6912">INSTR_PROF_COMMA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa444dc102f83b1a9c40e12a256180b8b">INSTR_PROF_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6bb5475a20c78d558a590a9d1797598">COVMAP_FUNC_RECORD</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bfa8a0f94bdccd624802854edf75ab">COVMAP_HEADER</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a079591b91e1c043f39277a0049f5788c">COVINIT_FUNC</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ebad2bfaeb97c17b6b1e305674407bb">INSTR_PROF_VALUE_PROF_DATA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac698947e76449da7cb367a70c8a087cc">INSTR_PROF_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3be382e77e5696131d47257c2fab384">INSTR_PROF_VTABLE_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29eabb7ef345000d765ff485ee6ad388">INSTR_PROF_VALUE_NODE</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba41a4beec52b1d055ef71498417f70">INSTR_PROF_RAW_HEADER</a>(Type, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4151bff44f84562f25648869139d6c">VALUE_PROF_FUNC_PARAM</a>(ArgType, ArgName, ArgLLVMType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa5472cd38e53d2907a357a182c9912f">INSTR_PROF_COMMA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b35df8d700a0d1e3771733e0004225f">VALUE_PROF_KIND</a>(Enumerator, Value, Descr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86126f6eb3464c149331aa4dacbd5e62">COVMAP_FUNC_RECORD</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac543621b15e2b4f7caf1c209f12df037">COVMAP_HEADER</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948087c65e44128955faf1792ad4998d">COVINIT_FUNC</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9925a14052e5398066d02ca3ab5a953c">INSTR_PROF_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308dac27348f416d34602317b56297fb">INSTR_PROF_MAX_NUM_VAL_PER_SITE</a>&nbsp;&nbsp;&nbsp;255</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db10d049bc5dcb6f2150d273142d6e1">INSTR_PROF_DATA</a>(Type, LLVMType, Name, Init)&nbsp;&nbsp;&nbsp;Type Name;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320f1d593dd9c9f284580b62f804c6e0">INSTR_PROF_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae000e23960985f006f4c29c9c184f8ad">INSTR_PROF_VTABLE_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37201b1ce57b3816c9ac843b093bf59">INSTR_PROF_VALUE_NODE</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4171cb67d6ecb3d87c5a368fe674310">INSTR_PROF_RAW_HEADER</a>(Type, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf127a8a854f91a2e91a1552d7210efd">VALUE_PROF_FUNC_PARAM</a>(ArgType, ArgName, ArgLLVMType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1efd38656772fff14510cbd3e2269c30">INSTR_PROF_COMMA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac196c95ed70f103a82296da4407cd3c">VALUE_PROF_KIND</a>(Enumerator, Value, Descr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdc18d9b0562049012b74c71fff204d">COVMAP_FUNC_RECORD</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc459fa6f52bdab341d573b7f02fd5c">COVMAP_HEADER</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987e57ec8b087948754d561c3516a124">COVINIT_FUNC</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585406d8ad5767cf97f6c02d940dd6ce">INSTR_PROF_VTABLE_DATA</a>(Type, LLVMType, Name, Init)&nbsp;&nbsp;&nbsp;Type Name;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2095db5fd979c45144987d8acabd68">INSTR_PROF_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb4988e6ab720bd4891ed8a3715f783">INSTR_PROF_VTABLE_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae90b3987ac582c1488aff339b90962ba">INSTR_PROF_VALUE_NODE</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea1b566e92c744409abef66c108d544">INSTR_PROF_RAW_HEADER</a>(Type, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f8cf2b698873c1f35e763cbca693a8">VALUE_PROF_FUNC_PARAM</a>(ArgType, ArgName, ArgLLVMType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea1a0b95a3670b9b7007b14c12fc420">INSTR_PROF_COMMA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5464f194ae16017796a0ce5ba1519ec">VALUE_PROF_KIND</a>(Enumerator, Value, Descr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6307d41404928e71a26d35ad9eeada">COVMAP_FUNC_RECORD</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60133e8467d15be894ecb6a6943f7ab3">COVMAP_HEADER</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316cf82ac530cdde1e5181a10ae3fce1">COVINIT_FUNC</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec30d46849a9873cecc9436c2fd58c6f">INSTR_PROF_DATA_INC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7842121683c4da88e1192c09aa7749d4">INSTR_PROF_SIMPLE_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;#x</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;<a href="#a7842121683c4da88e1192c09aa7749d4">INSTR_PROF_SIMPLE_QUOTE</a>(x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0199322811bea5d491eb2ece207e11">INSTR_PROF_SIMPLE_CONCAT</a>(x, y)&nbsp;&nbsp;&nbsp;x ## y</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce14fffe2d2d1aa581b5042270db5f6">INSTR_PROF_CONCAT</a>(x, y)&nbsp;&nbsp;&nbsp;<a href="#a2c0199322811bea5d491eb2ece207e11">INSTR_PROF_SIMPLE_CONCAT</a>(x,y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fac074274678102c6d2d0f74a91244">INSTR_PROF_RAW_MAGIC_64</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db1add509b30bf5a5d5fc025e953a37">INSTR_PROF_RAW_MAGIC_32</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa38105767a2300e56a5dafe47812f2">INSTR_PROF_RAW_VERSION</a>&nbsp;&nbsp;&nbsp;10</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c9a38c72c2c5af054d8ee2bed7198b">INSTR_PROF_INDEX_VERSION</a>&nbsp;&nbsp;&nbsp;12</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f110febf9a90217129f57172bf97cd7">INSTR_PROF_COVMAP_VERSION</a>&nbsp;&nbsp;&nbsp;6</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14dbb4c1a9af5089daa922e3e1504612">VARIANT_MASKS_ALL</a>&nbsp;&nbsp;&nbsp;0xffffffff00000000ULL</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e5b9b99b987f70e5314b04bc906829">GET_VERSION</a>(V)&nbsp;&nbsp;&nbsp;((V) &amp; ~<a href="#a14dbb4c1a9af5089daa922e3e1504612">VARIANT_MASKS_ALL</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e6ec9799bfbd754407e059b8f6d8a0">VARIANT_MASK_INSTR_LOOP_ENTRIES</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 55)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8edec32c53530079cae58fd6a87c88f1">VARIANT_MASK_IR_PROF</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 56)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb6071af28dfeec0e3873d78d28a89d">VARIANT_MASK_CSIR_PROF</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 57)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3518185a104ae0c5edc3f275f44c2cc">VARIANT_MASK_INSTR_ENTRY</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 58)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f34e7c2249c8d7a3275fc79a550b1f">VARIANT_MASK_DBG_CORRELATE</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 59)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad08bc204d09f0078bfa7df7dc8b8267">VARIANT_MASK_BYTE_COVERAGE</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 60)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6d70d4d6499baf2c1c09fb731ebbd5">VARIANT_MASK_FUNCTION_ENTRY_ONLY</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 61)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c0381f171f0f3f7681c507ce2e5ca1">VARIANT_MASK_MEMPROF</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 62)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca449ff6fdaa3732e8c4e9f95c8a8db">VARIANT_MASK_TEMPORAL_PROF</a>&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 63)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4b02475c0c6b6484c4e5fe8d2bea0c">INSTR_PROF_RAW_VERSION_VAR</a>&nbsp;&nbsp;&nbsp;__llvm_profile_raw_version</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad253067596f3873c29c1160b6390f803">INSTR_PROF_PROFILE_RUNTIME_VAR</a>&nbsp;&nbsp;&nbsp;__llvm_profile_runtime</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3433d8c91a6b476f945e11bd4cccd3">INSTR_PROF_PROFILE_COUNTER_BIAS_VAR</a>&nbsp;&nbsp;&nbsp;__llvm_profile_counter_bias</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3ed65ef77f7a53d230980844678a36">INSTR_PROF_PROFILE_BITMAP_BIAS_VAR</a>&nbsp;&nbsp;&nbsp;__llvm_profile_bitmap_bias</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d8e72949df8a0e3733ebd4dcdadafd">INSTR_PROF_PROFILE_SET_TIMESTAMP</a>&nbsp;&nbsp;&nbsp;__llvm_profile_set_timestamp</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade433207aef82efb42a028ff4125614a">INSTR_PROF_PROFILE_SAMPLING_VAR</a>&nbsp;&nbsp;&nbsp;__llvm_profile_sampling</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c22544f2ad7a6167929fc958fcaaa6">INSTR_PROF_PROFILE_NAME_VAR</a>&nbsp;&nbsp;&nbsp;__llvm_profile_filename</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d83da216d8513f8de3faea16dbd5f75">INSTR_PROF_DATA_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_data</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92199f396deee0d69aae0d2cf8405b9">INSTR_PROF_NAME_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_names</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63294ff2923ea3c4463e5d2200561e3">INSTR_PROF_VNAME_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_vns</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4080da967a9c00399cf6ab1e07f6ce">INSTR_PROF_CNTS_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_cnts</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60877a1a84e5e233a777fae8b0a7ddbd">INSTR_PROF_BITS_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_bits</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c65409f0f299d36d13c3d30584d4e5f">INSTR_PROF_VALS_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_vals</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6975904d84885d8efee4439528b73c6f">INSTR_PROF_VNODES_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_vnds</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a492973856171f4d6643fa958f8ab5f36">INSTR_PROF_VTAB_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_prf_vtab</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aebb25f755aa14cbfcb5e912c7820c0">INSTR_PROF_COVMAP_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_covmap</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881377869fa86509b08a1e50b1eb0317">INSTR_PROF_COVFUN_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_covfun</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b1f67da0d3232fc054a4f87b56f93e0">INSTR_PROF_COVDATA_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_covdata</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5143e1269e32a2a06fceb8360fb7f1b">INSTR_PROF_COVNAME_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_covnames</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81466bc0bc8bfacb5c300bc903731ed">INSTR_PROF_ORDERFILE_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_orderfile</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3f72fd4256d80c803b35d4876e77192">INSTR_PROF_COVINIT_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_covinit</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf65daedb22b1bf144898fd8769191d">INSTR_PROF_DATA_COFF</a>&nbsp;&nbsp;&nbsp;".lprfd$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529ad9e250f345d18cf4f1423cd3a632">INSTR_PROF_NAME_COFF</a>&nbsp;&nbsp;&nbsp;".lprfn$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bcbca322817aa00ee10bc41d6dbfa2">INSTR_PROF_VNAME_COFF</a>&nbsp;&nbsp;&nbsp;".lprfvn$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2845657a9120c87875b7daaad8a06763">INSTR_PROF_CNTS_COFF</a>&nbsp;&nbsp;&nbsp;".lprfc$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde8f30e1fc7cc4d08fae71e2b83807b">INSTR_PROF_BITS_COFF</a>&nbsp;&nbsp;&nbsp;".lprfb$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59cc9ad1608899830d276c408fc8fca5">INSTR_PROF_VALS_COFF</a>&nbsp;&nbsp;&nbsp;".lprfv$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae089954658200985562ca213b07776fd">INSTR_PROF_VNODES_COFF</a>&nbsp;&nbsp;&nbsp;".lprfnd$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17de793eeb8443a28d9ced022de247f2">INSTR_PROF_VTAB_COFF</a>&nbsp;&nbsp;&nbsp;".lprfvt$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd140f873e62897c70f0cd1a962fffb">INSTR_PROF_COVMAP_COFF</a>&nbsp;&nbsp;&nbsp;".lcovmap$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d909334b112b873965e3d1a1cc70252">INSTR_PROF_COVFUN_COFF</a>&nbsp;&nbsp;&nbsp;".lcovfun$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad110ad89bcb6169e305cfe2931cc8185">INSTR_PROF_COVDATA_COFF</a>&nbsp;&nbsp;&nbsp;".lcovd"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c1dd7a31bf5f3f7580b1579e9784b">INSTR_PROF_COVNAME_COFF</a>&nbsp;&nbsp;&nbsp;".lcovn"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85fedbebd12df3291e28bced34bd5c07">INSTR_PROF_ORDERFILE_COFF</a>&nbsp;&nbsp;&nbsp;".lorderfile$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f90a9b17a562d6186516bdb053a606">INSTR_PROF_COVINIT_COFF</a>&nbsp;&nbsp;&nbsp;".lcovd$M"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec15aef15a79026951a5a56d3885d454">INSTR_PROF_DATA_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a7d83da216d8513f8de3faea16dbd5f75">INSTR_PROF_DATA_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9172d2b9367208f763ee06281548a22">INSTR_PROF_NAME_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#af92199f396deee0d69aae0d2cf8405b9">INSTR_PROF_NAME_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad4c07ee8e33b8dddbe4417bdfd9733">INSTR_PROF_CNTS_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#aff4080da967a9c00399cf6ab1e07f6ce">INSTR_PROF_CNTS_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768ed5919301042c083bfc04db479616">INSTR_PROF_BITS_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a60877a1a84e5e233a777fae8b0a7ddbd">INSTR_PROF_BITS_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383c816a244bc916456cb5601b9e9f12">INSTR_PROF_VTAB_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a492973856171f4d6643fa958f8ab5f36">INSTR_PROF_VTAB_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c532af29a428ce50bb2a2cc7693033">INSTR_PROF_VNAME_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#ad63294ff2923ea3c4463e5d2200561e3">INSTR_PROF_VNAME_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0804f853cb4a053b454d398e926558d">INSTR_PROF_VALS_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a3c65409f0f299d36d13c3d30584d4e5f">INSTR_PROF_VALS_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038e2330edc1ad4d2be228542c3bbb99">INSTR_PROF_VNODES_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a6975904d84885d8efee4439528b73c6f">INSTR_PROF_VNODES_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79a5bd5f1dd375e559e8b64aceafa80">INSTR_PROF_COVMAP_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a2aebb25f755aa14cbfcb5e912c7820c0">INSTR_PROF_COVMAP_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab502893e310d5da33ef473c915d456e5">INSTR_PROF_COVFUN_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a881377869fa86509b08a1e50b1eb0317">INSTR_PROF_COVFUN_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0300d9e4659364cf259974cf93298efc">INSTR_PROF_COVDATA_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a7b1f67da0d3232fc054a4f87b56f93e0">INSTR_PROF_COVDATA_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3bd2f3a56943b9dbaa650a15f4015c2">INSTR_PROF_COVNAME_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#ab5143e1269e32a2a06fceb8360fb7f1b">INSTR_PROF_COVNAME_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd03e2b4cd38e9bebe2cdd24854b2ce">INSTR_PROF_ORDERFILE_SECT_NAME</a>&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#af81466bc0bc8bfacb5c300bc903731ed">INSTR_PROF_ORDERFILE_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a338fdcb0ba375a152ebd97c2ce931a33">INSTR_PROF_COVINIT_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#ae3f72fd4256d80c803b35d4876e77192">INSTR_PROF_COVINIT_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272ce09414d17f0712da1ebd8db99261">INSTR_PROF_ORDERFILE_BUFFER_NAME</a>&nbsp;&nbsp;&nbsp;_llvm_order_file_buffer</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f0426c8796635ca089439f54d1978b">INSTR_PROF_ORDERFILE_BUFFER_NAME_STR</a>&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a272ce09414d17f0712da1ebd8db99261">INSTR_PROF_ORDERFILE_BUFFER_NAME</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa689c3008c5d54f79ceb3b17f8f483e4">INSTR_PROF_ORDERFILE_BUFFER_IDX_NAME</a>&nbsp;&nbsp;&nbsp;_llvm_order_file_buffer_idx</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c5ff5815aa4113a87c59383aa6d441">INSTR_PROF_ORDERFILE_BUFFER_IDX_NAME_STR</a>&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#aa689c3008c5d54f79ceb3b17f8f483e4">INSTR_PROF_ORDERFILE_BUFFER_IDX_NAME</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56d8956c6a4eed2ef437e82fce4f79a">INSTR_PROF_SECT_START</a>(Sect)&nbsp;&nbsp;&nbsp;        <a href="#afce14fffe2d2d1aa581b5042270db5f6">INSTR_PROF_CONCAT</a>(__start_,Sect)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8978d53b72e33abb95422f299fe5b8">INSTR_PROF_SECT_STOP</a>(Sect)&nbsp;&nbsp;&nbsp;        <a href="#afce14fffe2d2d1aa581b5042270db5f6">INSTR_PROF_CONCAT</a>(__stop_,Sect)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17518e9e2554f387d7f7a5149235d8db">INSTR_PROF_VALUE_PROF_FUNC</a>&nbsp;&nbsp;&nbsp;__llvm_profile_instrument_target</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aee9b019d8ff5387f4362a90e93039b">INSTR_PROF_VALUE_PROF_FUNC_STR</a>&nbsp;&nbsp;&nbsp;        <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a17518e9e2554f387d7f7a5149235d8db">INSTR_PROF_VALUE_PROF_FUNC</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc07f1b05fc77e700872e8a1f780a6e">INSTR_PROF_VALUE_PROF_MEMOP_FUNC</a>&nbsp;&nbsp;&nbsp;__llvm_profile_instrument_memop</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a859f462cd6212d458af22c521849c">INSTR_PROF_VALUE_PROF_MEMOP_FUNC_STR</a>&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a6bc07f1b05fc77e700872e8a1f780a6e">INSTR_PROF_VALUE_PROF_MEMOP_FUNC</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b002afc9e4577467ec8159aca72f248">INSTR_PROF_DATA_ALIGNMENT</a>&nbsp;&nbsp;&nbsp;8</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ca2f48862bac7256192749b9edd8d8">INSTR_ORDER_FILE_BUFFER_SIZE</a>&nbsp;&nbsp;&nbsp;131072</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd1e083bcd7808d07d12afdf3efcf0d">INSTR_ORDER_FILE_BUFFER_BITS</a>&nbsp;&nbsp;&nbsp;17</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f2c0a3a2d77b9d174d841b185f3e40">INSTR_ORDER_FILE_BUFFER_MASK</a>&nbsp;&nbsp;&nbsp;131071</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ad194615b0aad7b7cb1388f42b9de6">INSTR_PROF_RAW_HEADER</a>(Type, Name, Init)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Type Name;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f40b5a0e18a3e44c6b30490e3669517">INSTR_PROF_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5c60aad8384f8fc83961d6f57658af">INSTR_PROF_VTABLE_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cef2549172caaaf145369be707fb901">INSTR_PROF_VALUE_NODE</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3156676b9f44d00166e9482e18fba75f">INSTR_PROF_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8402adede8f049254f25874e3a6f321b">VALUE_PROF_FUNC_PARAM</a>(ArgType, ArgName, ArgLLVMType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a737462bacbec549cb1d59c50314037e4">INSTR_PROF_COMMA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a032f66821c7b2a252e2ff6938f5c7be5">VALUE_PROF_KIND</a>(Enumerator, Value, Descr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb638f68277a5a99d64ce2ff3b7c222">COVMAP_FUNC_RECORD</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0441411dc4e934faa67278dd141c6a50">COVMAP_HEADER</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7716f624be4f362c35870911fb8f107">COVINIT_FUNC</a>(Type, LLVMType, Name, Initializer)</td>
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

### COVINIT\_FUNC {#ae0af632e6ce572cbccbe06f3cd5383e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVINIT_FUNC(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file InstrProfData.inc.</p>

</div>
</div>

### COVINIT\_FUNC {#a079591b91e1c043f39277a0049f5788c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVINIT_FUNC(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file InstrProfData.inc.</p>

</div>
</div>

### COVINIT\_FUNC {#a948087c65e44128955faf1792ad4998d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVINIT_FUNC(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file InstrProfData.inc.</p>

</div>
</div>

### COVINIT\_FUNC {#a987e57ec8b087948754d561c3516a124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVINIT_FUNC(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file InstrProfData.inc.</p>

</div>
</div>

### COVINIT\_FUNC {#a316cf82ac530cdde1e5181a10ae3fce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVINIT_FUNC(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file InstrProfData.inc.</p>

</div>
</div>

### COVINIT\_FUNC {#ad7716f624be4f362c35870911fb8f107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVINIT_FUNC(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_FUNC\_RECORD {#a4b82a7fc9ea6b68d597e54245e85f21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_FUNC_RECORD(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_FUNC\_RECORD {#ad6bb5475a20c78d558a590a9d1797598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_FUNC_RECORD(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_FUNC\_RECORD {#a86126f6eb3464c149331aa4dacbd5e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_FUNC_RECORD(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_FUNC\_RECORD {#a5cdc18d9b0562049012b74c71fff204d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_FUNC_RECORD(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_FUNC\_RECORD {#abb6307d41404928e71a26d35ad9eeada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_FUNC_RECORD(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_FUNC\_RECORD {#adeb638f68277a5a99d64ce2ff3b7c222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_FUNC_RECORD(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_HEADER {#ac825b81edfa1cf2df4102c9c34f821e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_HEADER(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_HEADER {#a16bfa8a0f94bdccd624802854edf75ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_HEADER(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_HEADER {#ac543621b15e2b4f7caf1c209f12df037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_HEADER(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_HEADER {#a2cc459fa6f52bdab341d573b7f02fd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_HEADER(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_HEADER {#a60133e8467d15be894ecb6a6943f7ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_HEADER(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_HEADER {#a0441411dc4e934faa67278dd141c6a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_HEADER(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file InstrProfData.inc.</p>

</div>
</div>

### GET\_VERSION {#a15e5b9b99b987f70e5314b04bc906829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_VERSION(V)&nbsp;&nbsp;&nbsp;((V) &amp; ~<a href="#a14dbb4c1a9af5089daa922e3e1504612">VARIANT_MASKS_ALL</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 746 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/header/#a471b50de7053136d1fca5acd7531db82">llvm::IndexedInstrProf::Header::getIndexedProfileVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#aba568f9966047a539da681c7a590c8e2">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::getVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/instrproflookuptrait/#ab68d7f02ae82dffc7ab698204d1e7d57">llvm::InstrProfLookupTrait::ReadData</a>.</p>

</div>
</div>

### INSTR\_ORDER\_FILE\_BUFFER\_BITS {#a9fd1e083bcd7808d07d12afdf3efcf0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_ORDER_FILE_BUFFER_BITS&nbsp;&nbsp;&nbsp;17</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 895 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_ORDER\_FILE\_BUFFER\_MASK {#a19f2c0a3a2d77b9d174d841b185f3e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_ORDER_FILE_BUFFER_MASK&nbsp;&nbsp;&nbsp;131071</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 896 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a32adc549fbc7c20005aabb9406435ff4">anonymous{InstrOrderFile.cpp}::InstrOrderFile::generateCodeSequence</a>.</p>

</div>
</div>

### INSTR\_ORDER\_FILE\_BUFFER\_SIZE {#ac6ca2f48862bac7256192749b9edd8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_ORDER_FILE_BUFFER_SIZE&nbsp;&nbsp;&nbsp;131072</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 894 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a3b3620fdf60408799b2d1957707a81d2">anonymous{InstrOrderFile.cpp}::InstrOrderFile::createOrderFileData</a>.</p>

</div>
</div>

### INSTR\_PROF\_BITS\_COFF {#afde8f30e1fc7cc4d08fae71e2b83807b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_BITS_COFF&nbsp;&nbsp;&nbsp;".lprfb$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 791 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_BITS\_COMMON {#a60877a1a84e5e233a777fae8b0a7ddbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_BITS_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_bits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 773 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_BITS\_SECT\_NAME {#a768ed5919301042c083bfc04db479616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_BITS_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a60877a1a84e5e233a777fae8b0a7ddbd">INSTR_PROF_BITS_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_CNTS\_COFF {#a2845657a9120c87875b7daaad8a06763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_CNTS_COFF&nbsp;&nbsp;&nbsp;".lprfc$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 790 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_CNTS\_COMMON {#aff4080da967a9c00399cf6ab1e07f6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_CNTS_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_cnts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_CNTS\_SECT\_NAME {#a4ad4c07ee8e33b8dddbe4417bdfd9733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_CNTS_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#aff4080da967a9c00399cf6ab1e07f6ce">INSTR_PROF_CNTS_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 832 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COMMA {#a9ec3bc606baecfea5832789f9b4f998b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COMMA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COMMA {#ad10b7a2548ea86ccc6388b280ead6912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COMMA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COMMA {#afa5472cd38e53d2907a357a182c9912f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COMMA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COMMA {#a1efd38656772fff14510cbd3e2269c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COMMA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COMMA {#afea1a0b95a3670b9b7007b14c12fc420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COMMA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COMMA {#a737462bacbec549cb1d59c50314037e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COMMA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_CONCAT {#afce14fffe2d2d1aa581b5042270db5f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_CONCAT(x, y)&nbsp;&nbsp;&nbsp;<a href="#a2c0199322811bea5d491eb2ece207e11">INSTR_PROF_SIMPLE_CONCAT</a>(x,y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVDATA\_COFF {#ad110ad89bcb6169e305cfe2931cc8185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVDATA_COFF&nbsp;&nbsp;&nbsp;".lcovd"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 800 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVDATA\_COMMON {#a7b1f67da0d3232fc054a4f87b56f93e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVDATA_COMMON&nbsp;&nbsp;&nbsp;__llvm_covdata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 779 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVDATA\_SECT\_NAME {#a0300d9e4659364cf259974cf93298efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVDATA_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a7b1f67da0d3232fc054a4f87b56f93e0">INSTR_PROF_COVDATA_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 844 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVFUN\_COFF {#a1d909334b112b873965e3d1a1cc70252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVFUN_COFF&nbsp;&nbsp;&nbsp;".lcovfun$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 796 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVFUN\_COMMON {#a881377869fa86509b08a1e50b1eb0317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVFUN_COMMON&nbsp;&nbsp;&nbsp;__llvm_covfun</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 778 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVFUN\_SECT\_NAME {#ab502893e310d5da33ef473c915d456e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVFUN_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a881377869fa86509b08a1e50b1eb0317">INSTR_PROF_COVFUN_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 843 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVINIT\_COFF {#a14f90a9b17a562d6186516bdb053a606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVINIT_COFF&nbsp;&nbsp;&nbsp;".lcovd$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 806 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVINIT\_COMMON {#ae3f72fd4256d80c803b35d4876e77192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVINIT_COMMON&nbsp;&nbsp;&nbsp;__llvm_covinit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 782 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVINIT\_SECT\_NAME {#a338fdcb0ba375a152ebd97c2ce931a33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVINIT_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#ae3f72fd4256d80c803b35d4876e77192">INSTR_PROF_COVINIT_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 849 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVMAP\_COFF {#a5cd140f873e62897c70f0cd1a962fffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVMAP_COFF&nbsp;&nbsp;&nbsp;".lcovmap$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 795 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVMAP\_COMMON {#a2aebb25f755aa14cbfcb5e912c7820c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVMAP_COMMON&nbsp;&nbsp;&nbsp;__llvm_covmap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 777 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVMAP\_SECT\_NAME {#ab79a5bd5f1dd375e559e8b64aceafa80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVMAP_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a2aebb25f755aa14cbfcb5e912c7820c0">INSTR_PROF_COVMAP_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 842 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVMAP\_VERSION {#a0f110febf9a90217129f57172bf97cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVMAP_VERSION&nbsp;&nbsp;&nbsp;6</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 730 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVNAME\_COFF {#a4a1c1dd7a31bf5f3f7580b1579e9784b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVNAME_COFF&nbsp;&nbsp;&nbsp;".lcovn"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 801 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVNAME\_COMMON {#ab5143e1269e32a2a06fceb8360fb7f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVNAME_COMMON&nbsp;&nbsp;&nbsp;__llvm_covnames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COVNAME\_SECT\_NAME {#ac3bd2f3a56943b9dbaa650a15f4015c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COVNAME_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#ab5143e1269e32a2a06fceb8360fb7f1b">INSTR_PROF_COVNAME_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 845 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA {#a964fe748db42abb3035346a85f7aa3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file InstrProfData.inc, definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_DATA {#a61629fdb389d51542976cbea4c4ebd75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file InstrProfData.inc, definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_DATA {#ac698947e76449da7cb367a70c8a087cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file InstrProfData.inc, definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_DATA {#a9db10d049bc5dcb6f2150d273142d6e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA(Type, LLVMType, Name, Init)&nbsp;&nbsp;&nbsp;Type Name;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_DATA {#aed2095db5fd979c45144987d8acabd68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file InstrProfData.inc, definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_DATA {#a0f40b5a0e18a3e44c6b30490e3669517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file InstrProfData.inc, definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_ALIGNMENT {#a5b002afc9e4577467ec8159aca72f248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_ALIGNMENT&nbsp;&nbsp;&nbsp;8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 878 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_COFF {#afcf65daedb22b1bf144898fd8769191d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_COFF&nbsp;&nbsp;&nbsp;".lprfd$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 787 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_COMMON {#a7d83da216d8513f8de3faea16dbd5f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 769 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_DEFINED {#a461567c719c6f8cd15517aec497c5ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_DEFINED {#aa444dc102f83b1a9c40e12a256180b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_DEFINED {#a9925a14052e5398066d02ca3ab5a953c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_DEFINED {#a320f1d593dd9c9f284580b62f804c6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_DEFINED {#a3156676b9f44d00166e9482e18fba75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_INC {#aec30d46849a9873cecc9436c2fd58c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_INC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_SECT\_NAME {#aec15aef15a79026951a5a56d3885d454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a7d83da216d8513f8de3faea16dbd5f75">INSTR_PROF_DATA_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 830 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_INDEX\_VERSION {#a89c9a38c72c2c5af054d8ee2bed7198b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_INDEX_VERSION&nbsp;&nbsp;&nbsp;12</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 728 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_MAX\_NUM\_VAL\_PER\_SITE {#a308dac27348f416d34602317b56297fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_MAX_NUM_VAL_PER_SITE&nbsp;&nbsp;&nbsp;255</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord/#a1ada73e7701e1a244045e42ac76e4ddc">llvm::InstrProfValueSiteRecord::sortByCount</a>.</p>

</div>
</div>

### INSTR\_PROF\_NAME\_COFF {#a529ad9e250f345d18cf4f1423cd3a632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_NAME_COFF&nbsp;&nbsp;&nbsp;".lprfn$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 788 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_NAME\_COMMON {#af92199f396deee0d69aae0d2cf8405b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_NAME_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_names</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_NAME\_SECT\_NAME {#aa9172d2b9367208f763ee06281548a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_NAME_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#af92199f396deee0d69aae0d2cf8405b9">INSTR_PROF_NAME_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 831 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_ORDERFILE\_BUFFER\_IDX\_NAME {#aa689c3008c5d54f79ceb3b17f8f483e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_ORDERFILE_BUFFER_IDX_NAME&nbsp;&nbsp;&nbsp;_llvm_order_file_buffer_idx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 855 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_ORDERFILE\_BUFFER\_IDX\_NAME\_STR {#aa3c5ff5815aa4113a87c59383aa6d441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_ORDERFILE_BUFFER_IDX_NAME_STR&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#aa689c3008c5d54f79ceb3b17f8f483e4">INSTR_PROF_ORDERFILE_BUFFER_IDX_NAME</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 856 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a3b3620fdf60408799b2d1957707a81d2">anonymous{InstrOrderFile.cpp}::InstrOrderFile::createOrderFileData</a>.</p>

</div>
</div>

### INSTR\_PROF\_ORDERFILE\_BUFFER\_NAME {#a272ce09414d17f0712da1ebd8db99261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_ORDERFILE_BUFFER_NAME&nbsp;&nbsp;&nbsp;_llvm_order_file_buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 852 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_ORDERFILE\_BUFFER\_NAME\_STR {#ad1f0426c8796635ca089439f54d1978b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_ORDERFILE_BUFFER_NAME_STR&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a272ce09414d17f0712da1ebd8db99261">INSTR_PROF_ORDERFILE_BUFFER_NAME</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 853 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a3b3620fdf60408799b2d1957707a81d2">anonymous{InstrOrderFile.cpp}::InstrOrderFile::createOrderFileData</a>.</p>

</div>
</div>

### INSTR\_PROF\_ORDERFILE\_COFF {#a85fedbebd12df3291e28bced34bd5c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_ORDERFILE_COFF&nbsp;&nbsp;&nbsp;".lorderfile$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 802 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_ORDERFILE\_COMMON {#af81466bc0bc8bfacb5c300bc903731ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_ORDERFILE_COMMON&nbsp;&nbsp;&nbsp;__llvm_orderfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_ORDERFILE\_SECT\_NAME {#abdd03e2b4cd38e9bebe2cdd24854b2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_ORDERFILE_SECT_NAME&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#af81466bc0bc8bfacb5c300bc903731ed">INSTR_PROF_ORDERFILE_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 847 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_PROFILE\_BITMAP\_BIAS\_VAR {#a5d3ed65ef77f7a53d230980844678a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_PROFILE_BITMAP_BIAS_VAR&nbsp;&nbsp;&nbsp;__llvm_profile_bitmap_bias</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a86d68e805ca036d8f04008e325b91501">llvm::getInstrProfBitmapBiasVarName</a>.</p>

</div>
</div>

### INSTR\_PROF\_PROFILE\_COUNTER\_BIAS\_VAR {#a8d3433d8c91a6b476f945e11bd4cccd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_PROFILE_COUNTER_BIAS_VAR&nbsp;&nbsp;&nbsp;__llvm_profile_counter_bias</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 758 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a62e221646506147afeb0bf76d8e3366a">llvm::getInstrProfCounterBiasVarName</a>.</p>

</div>
</div>

### INSTR\_PROF\_PROFILE\_NAME\_VAR {#a41c22544f2ad7a6167929fc958fcaaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_PROFILE_NAME_VAR&nbsp;&nbsp;&nbsp;__llvm_profile_filename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>.</p>

</div>
</div>

### INSTR\_PROF\_PROFILE\_RUNTIME\_VAR {#ad253067596f3873c29c1160b6390f803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_PROFILE_RUNTIME_VAR&nbsp;&nbsp;&nbsp;__llvm_profile_runtime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 757 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a18189242c2cc6362a03ab3d073578529">llvm::getInstrProfRuntimeHookVarName</a>.</p>

</div>
</div>

### INSTR\_PROF\_PROFILE\_SAMPLING\_VAR {#ade433207aef82efb42a028ff4125614a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_PROFILE_SAMPLING_VAR&nbsp;&nbsp;&nbsp;__llvm_profile_sampling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a277490f857b3fe53b950347a9148a447">llvm::createProfileSamplingVar</a>.</p>

</div>
</div>

### INSTR\_PROF\_PROFILE\_SET\_TIMESTAMP {#a93d8e72949df8a0e3733ebd4dcdadafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_PROFILE_SET_TIMESTAMP&nbsp;&nbsp;&nbsp;__llvm_profile_set_timestamp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_QUOTE {#a07e221f576fdc8eeff45d6c1bd688e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_QUOTE(x)&nbsp;&nbsp;&nbsp;<a href="#a7842121683c4da88e1192c09aa7749d4">INSTR_PROF_SIMPLE_QUOTE</a>(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 707 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a277490f857b3fe53b950347a9148a447">llvm::createProfileSamplingVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a86d68e805ca036d8f04008e325b91501">llvm::getInstrProfBitmapBiasVarName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62e221646506147afeb0bf76d8e3366a">llvm::getInstrProfCounterBiasVarName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18189242c2cc6362a03ab3d073578529">llvm::getInstrProfRuntimeHookVarName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_HEADER {#af05e05e47a5f9945cf30597645458686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_HEADER(Type, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file InstrProfData.inc, definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_HEADER {#a7a48c3c420871c8895aa03e069452a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_HEADER(Type, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file InstrProfData.inc, definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_HEADER {#a7ba41a4beec52b1d055ef71498417f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_HEADER(Type, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file InstrProfData.inc, definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_HEADER {#ad4171cb67d6ecb3d87c5a368fe674310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_HEADER(Type, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file InstrProfData.inc, definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_HEADER {#a2ea1b566e92c744409abef66c108d544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_HEADER(Type, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file InstrProfData.inc, definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_HEADER {#a80ad194615b0aad7b7cb1388f42b9de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_HEADER(Type, Name, Init)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Type Name;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_MAGIC\_32 {#a2db1add509b30bf5a5d5fc025e953a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_MAGIC_32&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">       (uint64_t)255 &lt;&lt; 56 | (uint64_t)'l' &lt;&lt; 48 | \
       (uint64_t)'p' &lt;&lt; 40 | (uint64_t)'r' &lt;&lt; 32 | (uint64_t)'o' &lt;&lt; 24 |  \
        (uint64_t)'f' &lt;&lt; 16 | (uint64_t)'R' &lt;&lt; 8 | (uint64_t)129
</div>
</dd>
</dl>

<p>Definition at line 721 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/rawinstrprof/#add0db2151e77ad7506acddbe9306136d">llvm::RawInstrProf::getMagic&lt; uint32_t &gt;</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_MAGIC\_64 {#ac2fac074274678102c6d2d0f74a91244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_MAGIC_64&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">       (uint64_t)255 &lt;&lt; 56 | (uint64_t)'l' &lt;&lt; 48 | \
       (uint64_t)'p' &lt;&lt; 40 | (uint64_t)'r' &lt;&lt; 32 | (uint64_t)'o' &lt;&lt; 24 |  \
        (uint64_t)'f' &lt;&lt; 16 | (uint64_t)'r' &lt;&lt; 8 | (uint64_t)129
</div>
</dd>
</dl>

<p>Definition at line 718 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/rawinstrprof/#af0fc51166ee77ddc9bac744decf6da54">llvm::RawInstrProf::getMagic&lt; uint64_t &gt;</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_VERSION {#a4aa38105767a2300e56a5dafe47812f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_VERSION&nbsp;&nbsp;&nbsp;10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 726 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_VERSION\_VAR {#a5e4b02475c0c6b6484c4e5fe8d2bea0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_VERSION_VAR&nbsp;&nbsp;&nbsp;__llvm_profile_raw_version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 756 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>.</p>

</div>
</div>

### INSTR\_PROF\_SECT\_ENTRY {#a6a0a1c07b5e2873b5c3dc58e3596aba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_SECT_ENTRY(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;Kind,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_SECT\_START {#ad56d8956c6a4eed2ef437e82fce4f79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_SECT_START(Sect)&nbsp;&nbsp;&nbsp;        <a href="#afce14fffe2d2d1aa581b5042270db5f6">INSTR_PROF_CONCAT</a>(__start_,Sect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 864 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_SECT\_STOP {#add8978d53b72e33abb95422f299fe5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_SECT_STOP(Sect)&nbsp;&nbsp;&nbsp;        <a href="#afce14fffe2d2d1aa581b5042270db5f6">INSTR_PROF_CONCAT</a>(__stop_,Sect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 866 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_SIMPLE\_CONCAT {#a2c0199322811bea5d491eb2ece207e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_SIMPLE_CONCAT(x, y)&nbsp;&nbsp;&nbsp;x ## y</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 708 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_SIMPLE\_QUOTE {#a7842121683c4da88e1192c09aa7749d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_SIMPLE_QUOTE(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 706 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALS\_COFF {#a59cc9ad1608899830d276c408fc8fca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALS_COFF&nbsp;&nbsp;&nbsp;".lprfv$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 792 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALS\_COMMON {#a3c65409f0f299d36d13c3d30584d4e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALS_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_vals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 774 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALS\_SECT\_NAME {#ab0804f853cb4a053b454d398e926558d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALS_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a3c65409f0f299d36d13c3d30584d4e5f">INSTR_PROF_VALS_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 839 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_NODE {#a2039a5308a9a7aecdfc29f45d1a04fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_NODE(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_NODE {#a0d0cb095fe390c2e0d64636a856e5267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_NODE(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_NODE {#a29eabb7ef345000d765ff485ee6ad388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_NODE(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_NODE {#af37201b1ce57b3816c9ac843b093bf59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_NODE(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_NODE {#ae90b3987ac582c1488aff339b90962ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_NODE(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_NODE {#a6cef2549172caaaf145369be707fb901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_NODE(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_PROF\_DATA {#a1ebad2bfaeb97c17b6b1e305674407bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_PROF_DATA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_PROF\_FUNC {#a17518e9e2554f387d7f7a5149235d8db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_PROF_FUNC&nbsp;&nbsp;&nbsp;__llvm_profile_instrument_target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_PROF\_FUNC\_STR {#a9aee9b019d8ff5387f4362a90e93039b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_PROF_FUNC_STR&nbsp;&nbsp;&nbsp;        <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a17518e9e2554f387d7f7a5149235d8db">INSTR_PROF_VALUE_PROF_FUNC</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acbf6b95a912f653f2e224154413cf534">llvm::getInstrProfValueProfFuncName</a>.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_PROF\_MEMOP\_FUNC {#a6bc07f1b05fc77e700872e8a1f780a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_PROF_MEMOP_FUNC&nbsp;&nbsp;&nbsp;__llvm_profile_instrument_memop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 873 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_PROF\_MEMOP\_FUNC\_STR {#ad4a859f462cd6212d458af22c521849c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_PROF_MEMOP_FUNC_STR&nbsp;&nbsp;&nbsp;  <a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a6bc07f1b05fc77e700872e8a1f780a6e">INSTR_PROF_VALUE_PROF_MEMOP_FUNC</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 874 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VISIBILITY {#a991a4b9fc0060d2c13c2609e8dbd5c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VISIBILITY</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file InstrProfData.inc, definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VNAME\_COFF {#ad1bcbca322817aa00ee10bc41d6dbfa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VNAME_COFF&nbsp;&nbsp;&nbsp;".lprfvn$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 789 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VNAME\_COMMON {#ad63294ff2923ea3c4463e5d2200561e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VNAME_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_vns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 771 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VNAME\_SECT\_NAME {#ab9c532af29a428ce50bb2a2cc7693033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VNAME_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#ad63294ff2923ea3c4463e5d2200561e3">INSTR_PROF_VNAME_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 835 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VNODES\_COFF {#ae089954658200985562ca213b07776fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VNODES_COFF&nbsp;&nbsp;&nbsp;".lprfnd$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VNODES\_COMMON {#a6975904d84885d8efee4439528b73c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VNODES_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_vnds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 775 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VNODES\_SECT\_NAME {#a038e2330edc1ad4d2be228542c3bbb99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VNODES_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a6975904d84885d8efee4439528b73c6f">INSTR_PROF_VNODES_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 841 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VTAB\_COFF {#a17de793eeb8443a28d9ced022de247f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTAB_COFF&nbsp;&nbsp;&nbsp;".lprfvt$M"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 794 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VTAB\_COMMON {#a492973856171f4d6643fa958f8ab5f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTAB_COMMON&nbsp;&nbsp;&nbsp;__llvm_prf_vtab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 776 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VTAB\_SECT\_NAME {#a383c816a244bc916456cb5601b9e9f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTAB_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="#a07e221f576fdc8eeff45d6c1bd688e9e">INSTR_PROF_QUOTE</a>(<a href="#a492973856171f4d6643fa958f8ab5f36">INSTR_PROF_VTAB_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 834 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA {#a9fffbf1bcdf0b73994e7d71af9fda706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file InstrProfData.inc, definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA {#a092a23d90c264232a2c4b67b64cf9f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file InstrProfData.inc, definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA {#ad3be382e77e5696131d47257c2fab384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file InstrProfData.inc, definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA {#ae000e23960985f006f4c29c9c184f8ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file InstrProfData.inc, definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA {#a585406d8ad5767cf97f6c02d940dd6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA(Type, LLVMType, Name, Init)&nbsp;&nbsp;&nbsp;Type Name;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA {#a0f5c60aad8384f8fc83961d6f57658af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file InstrProfData.inc, definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA\_DEFINED {#a4fb4988e6ab720bd4891ed8a3715f783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_FUNC\_PARAM {#ad7b37e795b394a273b4adca2984d0c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_FUNC_PARAM(ArgType, ArgName, ArgLLVMType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_FUNC\_PARAM {#a87c1bbac0b84ba640670d7cfb8d46c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_FUNC_PARAM(ArgType, ArgName, ArgLLVMType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_FUNC\_PARAM {#acd4151bff44f84562f25648869139d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_FUNC_PARAM(ArgType, ArgName, ArgLLVMType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_FUNC\_PARAM {#aaf127a8a854f91a2e91a1552d7210efd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_FUNC_PARAM(ArgType, ArgName, ArgLLVMType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_FUNC\_PARAM {#a44f8cf2b698873c1f35e763cbca693a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_FUNC_PARAM(ArgType, ArgName, ArgLLVMType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_FUNC\_PARAM {#a8402adede8f049254f25874e3a6f321b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_FUNC_PARAM(ArgType, ArgName, ArgLLVMType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_KIND {#ae2558cb097460e2dfa5315ec18c38c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_KIND(Enumerator, Value, Descr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file InstrProfData.inc, definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VALUE\_PROF\_KIND {#a806f28489e8f6c6c347485fbc3ef50a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_KIND(Enumerator, Value, Descr)&nbsp;&nbsp;&nbsp;Enumerator = Value,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VALUE\_PROF\_KIND {#a5b35df8d700a0d1e3771733e0004225f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_KIND(Enumerator, Value, Descr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file InstrProfData.inc, definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VALUE\_PROF\_KIND {#aac196c95ed70f103a82296da4407cd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_KIND(Enumerator, Value, Descr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file InstrProfData.inc, definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VALUE\_PROF\_KIND {#ad5464f194ae16017796a0ce5ba1519ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_KIND(Enumerator, Value, Descr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file InstrProfData.inc, definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VALUE\_PROF\_KIND {#a032f66821c7b2a252e2ff6938f5c7be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_KIND(Enumerator, Value, Descr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file InstrProfData.inc, definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VARIANT\_MASK\_BYTE\_COVERAGE {#aad08bc204d09f0078bfa7df7dc8b8267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_BYTE_COVERAGE&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 60)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 752 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#a39647ac94175c3a8d8ac7d729ad02314">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::hasSingleByteCoverage</a> and <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a38a8b5fcdd6ca1203ff4985b04dc424d">llvm::RawInstrProfReader&lt; uint32_t &gt;::hasSingleByteCoverage</a>.</p>

</div>
</div>

### VARIANT\_MASK\_CSIR\_PROF {#a1cb6071af28dfeec0e3873d78d28a89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_CSIR_PROF&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 57)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 749 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#a78468911a5885da2fda70a42b3c6dc5f">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::hasCSIRLevelProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#af045c383763fa73f2d96c30767634d03">llvm::RawInstrProfReader&lt; uint32_t &gt;::hasCSIRLevelProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a172a26066ad6417d3ee4b506f7b441e8">llvm::IndexedInstrProfReader::readHeader</a>.</p>

</div>
</div>

### VARIANT\_MASK\_DBG\_CORRELATE {#a48f34e7c2249c8d7a3275fc79a550b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_DBG_CORRELATE&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 59)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 751 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>.</p>

</div>
</div>

### VARIANT\_MASK\_FUNCTION\_ENTRY\_ONLY {#acc6d70d4d6499baf2c1c09fb731ebbd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_FUNCTION_ENTRY_ONLY&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 61)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 753 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#aab81b954245928eed0df823681b6ec20">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::functionEntryOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a02cb2b9d9625853fed92f6725bcdca6f">llvm::RawInstrProfReader&lt; uint32_t &gt;::functionEntryOnly</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>.</p>

</div>
</div>

### VARIANT\_MASK\_INSTR\_ENTRY {#ac3518185a104ae0c5edc3f275f44c2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_INSTR_ENTRY&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 58)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 750 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#abf7b81dc1b9c4f325030606252ca979d">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::instrEntryBBEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#ab058a350d9cc97025e259b801bf73fa6">llvm::RawInstrProfReader&lt; uint32_t &gt;::instrEntryBBEnabled</a>.</p>

</div>
</div>

### VARIANT\_MASK\_INSTR\_LOOP\_ENTRIES {#ad7e6ec9799bfbd754407e059b8f6d8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_INSTR_LOOP_ENTRIES&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 55)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 747 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#ab7e4e898ac78e7bc6596f3a816ac3204">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::instrLoopEntriesEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a8a051208f2074ffc67a163b4f69faa29">llvm::RawInstrProfReader&lt; uint32_t &gt;::instrLoopEntriesEnabled</a>.</p>

</div>
</div>

### VARIANT\_MASK\_IR\_PROF {#a8edec32c53530079cae58fd6a87c88f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_IR_PROF&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 56)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 748 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#abb349a56c05f6eabb51b2aa3fa259a90">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::isIRLevelProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a5ca3d97ffbf8fc922a8255c5163853c8">llvm::RawInstrProfReader&lt; uint32_t &gt;::isIRLevelProfile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>.</p>

</div>
</div>

### VARIANT\_MASK\_MEMPROF {#a30c0381f171f0f3f7681c507ce2e5ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_MEMPROF&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 62)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 754 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#abc0da114006b66f6df7c46b0b6ecde36">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::hasMemoryProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a7f974f894e1dce5201cd62c9bd3c5dbd">llvm::RawInstrProfReader&lt; uint32_t &gt;::hasMemoryProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a172a26066ad6417d3ee4b506f7b441e8">llvm::IndexedInstrProfReader::readHeader</a>.</p>

</div>
</div>

### VARIANT\_MASK\_TEMPORAL\_PROF {#a8ca449ff6fdaa3732e8c4e9f95c8a8db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASK_TEMPORAL_PROF&nbsp;&nbsp;&nbsp;(0x1ULL &lt;&lt; 63)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 755 of file InstrProfData.inc.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a083c19a1c9c7ef9cc7530480295f763e">createIRLevelProfileFlagVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae1da690dcaeb854da273d7bc8eecc18d">getProfileKindFromVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#abe719bc0ebc89acf61d53a711e0d3355">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::hasTemporalProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#aa809b1f65027eeffaa2f622c45ceae4d">llvm::RawInstrProfReader&lt; uint32_t &gt;::hasTemporalProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a172a26066ad6417d3ee4b506f7b441e8">llvm::IndexedInstrProfReader::readHeader</a>.</p>

</div>
</div>

### VARIANT\_MASKS\_ALL {#a14dbb4c1a9af5089daa922e3e1504612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARIANT_MASKS_ALL&nbsp;&nbsp;&nbsp;0xffffffff00000000ULL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 745 of file InstrProfData.inc.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
