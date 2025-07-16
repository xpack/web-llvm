---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/overlapstats
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OverlapStats` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::OverlapStats { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OverlapStatsLevel { <a href="#a75e2dad8742984e6380161b39eadfa69">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae912765494ab922586fba5bb2770e335">OverlapStats</a> (OverlapStatsLevel L=ProgramLevel)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a> (raw_fd_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a962f236949ed0b41bb0f25d1612114d5">setFuncInfo</a> (StringRef Name, uint64_t Hash)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc444c0141edfa6f0c92e71fa3d3dda">accumulateCounts</a> (const std::string &amp;BaseFilename, const std::string &amp;TestFilename, bool IsCS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0890bbfe709e212efce84003c8fb9469">addOneMismatch</a> (const CountSumOrPercent &amp;MismatchFunc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813dbcd2d37d971f1962238891728d87">addOneUnique</a> (const CountSumOrPercent &amp;UniqueFunc)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439f69d2f637d33a29889fef95c7f0ec">Base</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeacf37b436c25b1af9f22712417fef6c">Test</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3427e5f987ace470105d11ad6c7a89a1">Overlap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26429a78c9a61bd1ff215e9dda0d230">Mismatch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9a61696494497ae37dc9ddb2789827">Unique</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a75e2dad8742984e6380161b39eadfa69">OverlapStatsLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade7811ae498db61d41b0cbed81a3850b">Level</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a174893b534aff6c783df5340fee28">BaseFilename</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9436e25f0c28ff125cd713cc0d22108a">TestFilename</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67710ce70df6041d5b9f2ed5e961201">FuncName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2a4ca946b34035eeacb05c1a3fc14f">FuncHash</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c54b81c583e348f8a4f01f3396537f1">Valid</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e9a9f58836064e628e42236939edbeb">score</a> (uint64_t Val1, uint64_t Val2, double Sum1, double Sum2)</td>
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


<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OverlapStatsLevel {#a75e2dad8742984e6380161b39eadfa69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OverlapStats::OverlapStatsLevel </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProgramLevel<a id="a75e2dad8742984e6380161b39eadfa69addf5b761ac11fe486b6aafed5a84358d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FunctionLevel<a id="a75e2dad8742984e6380161b39eadfa69a65c1ec6c93567bd51f69ac98c000b589"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OverlapStats() {#ae912765494ab922586fba5bb2770e335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OverlapStats::OverlapStats (<a href="#a75e2dad8742984e6380161b39eadfa69">OverlapStatsLevel</a> L=<a href="#a75e2dad8742984e6380161b39eadfa69addf5b761ac11fe486b6aafed5a84358d">ProgramLevel</a>)</td>
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



<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#ade7811ae498db61d41b0cbed81a3850b">Level</a> and <a href="#a75e2dad8742984e6380161b39eadfa69addf5b761ac11fe486b6aafed5a84358d">ProgramLevel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accumulateCounts() {#a1cc444c0141edfa6f0c92e71fa3d3dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::OverlapStats::accumulateCounts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; BaseFilename, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; TestFilename, bool IsCS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 1523 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="#a439f69d2f637d33a29889fef95c7f0ec">Base</a>, <a href="#a85a174893b534aff6c783df5340fee28">BaseFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#af9b6bc8513f2e320ab04eba79fc01491">llvm::InstrProfReader::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfs/#a9878c6a5a53d24e17c7c1002be31364c">llvm::vfs::getRealFileSystem</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#aeacf37b436c25b1af9f22712417fef6c">Test</a>, <a href="#a9436e25f0c28ff125cd713cc0d22108a">TestFilename</a> and <a href="#a4c54b81c583e348f8a4f01f3396537f1">Valid</a>.</p>

</div>
</div>

### addOneMismatch() {#a0890bbfe709e212efce84003c8fb9469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OverlapStats::addOneMismatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a> &amp; MismatchFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 1551 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa86b18bf848839782dee252ea6871d00">llvm::CountSumOrPercent::CountSum</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad26429a78c9a61bd1ff215e9dda0d230">Mismatch</a>, <a href="#aeacf37b436c25b1af9f22712417fef6c">Test</a> and <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa65910538ca9fe224414a15b68bdcf33">llvm::CountSumOrPercent::ValueCounts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2882c6d2a257083c160385fe493c0cf2">llvm::InstrProfWriter::overlapRecord</a>.</p>

</div>
</div>

### addOneUnique() {#a813dbcd2d37d971f1962238891728d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OverlapStats::addOneUnique (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a> &amp; UniqueFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa86b18bf848839782dee252ea6871d00">llvm::CountSumOrPercent::CountSum</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aeacf37b436c25b1af9f22712417fef6c">Test</a>, <a href="#acf9a61696494497ae37dc9ddb2789827">Unique</a> and <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa65910538ca9fe224414a15b68bdcf33">llvm::CountSumOrPercent::ValueCounts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2882c6d2a257083c160385fe493c0cf2">llvm::InstrProfWriter::overlapRecord</a>.</p>

</div>
</div>

### dump() {#a325e879d8f73b4cbda612ded9d47d936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OverlapStats::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 1570 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="#a439f69d2f637d33a29889fef95c7f0ec">Base</a>, <a href="#a85a174893b534aff6c783df5340fee28">BaseFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a5b2a4ca946b34035eeacb05c1a3fc14f">FuncHash</a>, <a href="#ad67710ce70df6041d5b9f2ed5e961201">FuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ade7811ae498db61d41b0cbed81a3850b">Level</a>, <a href="#ad26429a78c9a61bd1ff215e9dda0d230">Mismatch</a>, <a href="#a3427e5f987ace470105d11ad6c7a89a1">Overlap</a>, <a href="#a75e2dad8742984e6380161b39eadfa69addf5b761ac11fe486b6aafed5a84358d">ProgramLevel</a>, <a href="#aeacf37b436c25b1af9f22712417fef6c">Test</a>, <a href="#a9436e25f0c28ff125cd713cc0d22108a">TestFilename</a>, <a href="#acf9a61696494497ae37dc9ddb2789827">Unique</a> and <a href="#a4c54b81c583e348f8a4f01f3396537f1">Valid</a>.</p>

</div>
</div>

### setFuncInfo() {#a962f236949ed0b41bb0f25d1612114d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OverlapStats::setFuncInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Hash)</td>
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



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#a5b2a4ca946b34035eeacb05c1a3fc14f">FuncHash</a> and <a href="#ad67710ce70df6041d5b9f2ed5e961201">FuncName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Base {#a439f69d2f637d33a29889fef95c7f0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountSumOrPercent llvm::OverlapStats::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a1cc444c0141edfa6f0c92e71fa3d3dda">accumulateCounts</a>, <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a> and <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord/#abb70319c5b094f62ab7ad31eb00cec10">llvm::InstrProfValueSiteRecord::overlap</a>.</p>

</div>
</div>

### BaseFilename {#a85a174893b534aff6c783df5340fee28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string* llvm::OverlapStats::BaseFilename = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a1cc444c0141edfa6f0c92e71fa3d3dda">accumulateCounts</a> and <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a>.</p>

</div>
</div>

### FuncHash {#a5b2a4ca946b34035eeacb05c1a3fc14f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::OverlapStats::FuncHash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a> and <a href="#a962f236949ed0b41bb0f25d1612114d5">setFuncInfo</a>.</p>

</div>
</div>

### FuncName {#ad67710ce70df6041d5b9f2ed5e961201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::OverlapStats::FuncName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a> and <a href="#a962f236949ed0b41bb0f25d1612114d5">setFuncInfo</a>.</p>

</div>
</div>

### Level {#ade7811ae498db61d41b0cbed81a3850b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverlapStatsLevel llvm::OverlapStats::Level</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a> and <a href="#ae912765494ab922586fba5bb2770e335">OverlapStats</a>.</p>

</div>
</div>

### Mismatch {#ad26429a78c9a61bd1ff215e9dda0d230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountSumOrPercent llvm::OverlapStats::Mismatch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a0890bbfe709e212efce84003c8fb9469">addOneMismatch</a> and <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a>.</p>

</div>
</div>

### Overlap {#a3427e5f987ace470105d11ad6c7a89a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountSumOrPercent llvm::OverlapStats::Overlap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord/#abb70319c5b094f62ab7ad31eb00cec10">llvm::InstrProfValueSiteRecord::overlap</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2882c6d2a257083c160385fe493c0cf2">llvm::InstrProfWriter::overlapRecord</a>.</p>

</div>
</div>

### Test {#aeacf37b436c25b1af9f22712417fef6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountSumOrPercent llvm::OverlapStats::Test</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a1cc444c0141edfa6f0c92e71fa3d3dda">accumulateCounts</a>, <a href="#a0890bbfe709e212efce84003c8fb9469">addOneMismatch</a>, <a href="#a813dbcd2d37d971f1962238891728d87">addOneUnique</a>, <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord/#abb70319c5b094f62ab7ad31eb00cec10">llvm::InstrProfValueSiteRecord::overlap</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2882c6d2a257083c160385fe493c0cf2">llvm::InstrProfWriter::overlapRecord</a>.</p>

</div>
</div>

### TestFilename {#a9436e25f0c28ff125cd713cc0d22108a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string* llvm::OverlapStats::TestFilename = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a1cc444c0141edfa6f0c92e71fa3d3dda">accumulateCounts</a> and <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a>.</p>

</div>
</div>

### Unique {#acf9a61696494497ae37dc9ddb2789827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountSumOrPercent llvm::OverlapStats::Unique</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a813dbcd2d37d971f1962238891728d87">addOneUnique</a> and <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a>.</p>

</div>
</div>

### Valid {#a4c54b81c583e348f8a4f01f3396537f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OverlapStats::Valid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a1cc444c0141edfa6f0c92e71fa3d3dda">accumulateCounts</a>, <a href="#a325e879d8f73b4cbda612ded9d47d936">dump</a> and <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### score() {#a0e9a9f58836064e628e42236939edbeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::OverlapStats::score (uint64_t Val1, uint64_t Val2, double Sum1, double Sum2)</td>
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



<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a> and <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord/#abb70319c5b094f62ab7ad31eb00cec10">llvm::InstrProfValueSiteRecord::overlap</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
