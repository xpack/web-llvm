---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarftypeprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DWARFTypePrinter` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename DieType&gt;
struct llvm::DWARFTypePrinter&lt;DieType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">llvm/DebugInfo/DWARF/DWARFTypePrinter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8a6ba261d1cca78325d5a642435c59b0">DWARFTypePrinter</a> (raw_ostream &amp;OS)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09f85524dd190f2649d7f584a2edcce3">appendTypeTagName</a> (dwarf::Tag T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the name encoded in the type tag. <a href="#a09f85524dd190f2649d7f584a2edcce3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3835a080f718461efd839bc1b856c89b">appendArrayType</a> (const DieType &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DieType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a55527b7757dcebab2e38fbd45bf655bf">skipQualifiers</a> (DieType D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2562cc2a382fcd930afda3a6b75fa22b">needsParens</a> (DieType D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add6ceb903c623e57ca78ec00ab7d7a08">appendPointerLikeTypeBefore</a> (DieType D, DieType Inner, StringRef Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DieType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4910906a25183ed3ea2984c5b423582">appendUnqualifiedNameBefore</a> (DieType D, std::string *OriginalFullName=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae18a539636ce8c8644caedf1fa21f041">appendUnqualifiedNameAfter</a> (DieType D, DieType Inner, bool SkipFirstParamIfArtificial=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ff71a14b903ade718fa244e2762daaa">appendQualifiedName</a> (DieType D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DieType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3998337d3fd6fdd5a5c358a56e0a7d5d">appendQualifiedNameBefore</a> (DieType D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab2bf71aa33f172d69cb90abfeb10695f">appendTemplateParameters</a> (DieType D, bool *FirstParameter=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac707ceca2d4a993e39b72a224814bc1a">appendAndTerminateTemplateParameters</a> (DieType D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ffc1f6f44d6f01f289108370a0fbf21">decomposeConstVolatile</a> (DieType &amp;N, DieType &amp;T, DieType &amp;C, DieType &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abcb3596d8a38517290a40f2fa529876a">appendConstVolatileQualifierAfter</a> (DieType N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b109c547db47dc708d9585c485237ee">appendConstVolatileQualifierBefore</a> (DieType N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5985e698626fb7c2f63ee98d0bab122a">appendUnqualifiedName</a> (DieType D, std::string *OriginalFullName=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively append the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> type name when applicable. <a href="#a5985e698626fb7c2f63ee98d0bab122a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f62eedabc99865b72dc43f7883f31a6">appendSubroutineNameAfter</a> (DieType D, DieType Inner, bool SkipFirstParamIfArtificial, bool Const, bool Volatile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ba541b95a40e65f1e21feeedb1b945e">appendScopes</a> (DieType D)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51ed52f10b37a50cdfdadff972b96ef1">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a208bb17462bd5325b49054e0a9dc30ba">Word</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0dad0e7451ff5528c8455678b96955e0">EndedWithTemplate</a> = false</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DieType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bd0ac5fed870890107155d898a0ceb9">scopedTAGs</a> (dwarf::Tag Tag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> TAG is one of the ones that is scopped. <a href="#a8bd0ac5fed870890107155d898a0ceb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFTypePrinter() {#a8a6ba261d1cca78325d5a642435c59b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFTypePrinter&lt; DieType &gt;::DWARFTypePrinter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>Reference <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendAndTerminateTemplateParameters() {#ac707ceca2d4a993e39b72a224814bc1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendAndTerminateTemplateParameters (DieType D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a0dad0e7451ff5528c8455678b96955e0">llvm::DWARFTypePrinter&lt; DieType &gt;::EndedWithTemplate</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a> and <a href="#a208bb17462bd5325b49054e0a9dc30ba">llvm::DWARFTypePrinter&lt; DieType &gt;::Word</a>.</p>

</div>
</div>

### appendArrayType() {#a3835a080f718461efd839bc1b856c89b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendArrayType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DieType &amp; D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a0dad0e7451ff5528c8455678b96955e0">llvm::DWARFTypePrinter&lt; DieType &gt;::EndedWithTemplate</a> and <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>.</p>


<p>Referenced by <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>.</p>

</div>
</div>

### appendConstVolatileQualifierAfter() {#abcb3596d8a38517290a40f2fa529876a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierAfter (DieType N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a9f62eedabc99865b72dc43f7883f31a6">llvm::DWARFTypePrinter&lt; DieType &gt;::appendSubroutineNameAfter</a>, <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a3ffc1f6f44d6f01f289108370a0fbf21">llvm::DWARFTypePrinter&lt; DieType &gt;::decomposeConstVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>.</p>

</div>
</div>

### appendConstVolatileQualifierBefore() {#a6b109c547db47dc708d9585c485237ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierBefore (DieType N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a3998337d3fd6fdd5a5c358a56e0a7d5d">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedNameBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a3ffc1f6f44d6f01f289108370a0fbf21">llvm::DWARFTypePrinter&lt; DieType &gt;::decomposeConstVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a208bb17462bd5325b49054e0a9dc30ba">llvm::DWARFTypePrinter&lt; DieType &gt;::Word</a>.</p>


<p>Referenced by <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

### appendPointerLikeTypeBefore() {#add6ceb903c623e57ca78ec00ab7d7a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendPointerLikeTypeBefore (DieType D, DieType Inner, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a3998337d3fd6fdd5a5c358a56e0a7d5d">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedNameBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a0dad0e7451ff5528c8455678b96955e0">llvm::DWARFTypePrinter&lt; DieType &gt;::EndedWithTemplate</a>, <a href="#a2562cc2a382fcd930afda3a6b75fa22b">llvm::DWARFTypePrinter&lt; DieType &gt;::needsParens</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#a208bb17462bd5325b49054e0a9dc30ba">llvm::DWARFTypePrinter&lt; DieType &gt;::Word</a>.</p>


<p>Referenced by <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

### appendQualifiedName() {#a3ff71a14b903ade718fa244e2762daaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedName (DieType D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a6ba541b95a40e65f1e21feeedb1b945e">llvm::DWARFTypePrinter&lt; DieType &gt;::appendScopes</a>, <a href="#a5985e698626fb7c2f63ee98d0bab122a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedName</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="#a9f62eedabc99865b72dc43f7883f31a6">llvm::DWARFTypePrinter&lt; DieType &gt;::appendSubroutineNameAfter</a>, <a href="#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a>, <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9d0e8c22e295e665838a1f8fdff8676d">llvm::dumpTypeQualifiedName</a>.</p>

</div>
</div>

### appendQualifiedNameBefore() {#a3998337d3fd6fdd5a5c358a56e0a7d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DieType llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedNameBefore (DieType D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a6ba541b95a40e65f1e21feeedb1b945e">llvm::DWARFTypePrinter&lt; DieType &gt;::appendScopes</a>, <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="#a6b109c547db47dc708d9585c485237ee">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierBefore</a>, <a href="#add6ceb903c623e57ca78ec00ab7d7a08">llvm::DWARFTypePrinter&lt; DieType &gt;::appendPointerLikeTypeBefore</a> and <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

### appendScopes() {#a6ba541b95a40e65f1e21feeedb1b945e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendScopes (DieType D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a6ba541b95a40e65f1e21feeedb1b945e">llvm::DWARFTypePrinter&lt; DieType &gt;::appendScopes</a>, <a href="#a5985e698626fb7c2f63ee98d0bab122a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a3ff71a14b903ade718fa244e2762daaa">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedName</a>, <a href="#a3998337d3fd6fdd5a5c358a56e0a7d5d">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedNameBefore</a> and <a href="#a6ba541b95a40e65f1e21feeedb1b945e">llvm::DWARFTypePrinter&lt; DieType &gt;::appendScopes</a>.</p>

</div>
</div>

### appendSubroutineNameAfter() {#a9f62eedabc99865b72dc43f7883f31a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendSubroutineNameAfter (DieType D, DieType Inner, bool SkipFirstParamIfArtificial, bool Const, bool Volatile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a3ff71a14b903ade718fa244e2762daaa">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedName</a>, <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a0dad0e7451ff5528c8455678b96955e0">llvm::DWARFTypePrinter&lt; DieType &gt;::EndedWithTemplate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#abcb3596d8a38517290a40f2fa529876a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierAfter</a> and <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>.</p>

</div>
</div>

### appendTemplateParameters() {#ab2bf71aa33f172d69cb90abfeb10695f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters (DieType D, bool * FirstParameter=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a3ff71a14b903ade718fa244e2762daaa">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedName</a>, <a href="#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a0dad0e7451ff5528c8455678b96955e0">llvm::DWARFTypePrinter&lt; DieType &gt;::EndedWithTemplate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a4427489f872210c554e05e29c220bdb2">llvm::detail::toString</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a83f43087fac32b05f47dcd3c89fc7bbd">TypeAttr</a>.</p>


<p>Referenced by <a href="#ac707ceca2d4a993e39b72a224814bc1a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendAndTerminateTemplateParameters</a>, <a href="#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a> and <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

### appendTypeTagName() {#a09f85524dd190f2649d7f584a2edcce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendTypeTagName (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the name encoded in the type tag.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

### appendUnqualifiedName() {#a5985e698626fb7c2f63ee98d0bab122a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedName (DieType D, std::string * OriginalFullName=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively append the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> type name when applicable.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>, <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="#a3ff71a14b903ade718fa244e2762daaa">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedName</a>, <a href="#a6ba541b95a40e65f1e21feeedb1b945e">llvm::DWARFTypePrinter&lt; DieType &gt;::appendScopes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae64c48fcdefcf075717364cfa4201a18">llvm::dumpTypeUnqualifiedName</a>.</p>

</div>
</div>

### appendUnqualifiedNameAfter() {#ae18a539636ce8c8644caedf1fa21f041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter (DieType D, DieType Inner, bool SkipFirstParamIfArtificial=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a3835a080f718461efd839bc1b856c89b">llvm::DWARFTypePrinter&lt; DieType &gt;::appendArrayType</a>, <a href="#abcb3596d8a38517290a40f2fa529876a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierAfter</a>, <a href="#a9f62eedabc99865b72dc43f7883f31a6">llvm::DWARFTypePrinter&lt; DieType &gt;::appendSubroutineNameAfter</a>, <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a2562cc2a382fcd930afda3a6b75fa22b">llvm::DWARFTypePrinter&lt; DieType &gt;::needsParens</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="#abcb3596d8a38517290a40f2fa529876a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierAfter</a>, <a href="#a9f62eedabc99865b72dc43f7883f31a6">llvm::DWARFTypePrinter&lt; DieType &gt;::appendSubroutineNameAfter</a>, <a href="#a5985e698626fb7c2f63ee98d0bab122a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedName</a> and <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>.</p>

</div>
</div>

### appendUnqualifiedNameBefore() {#af4910906a25183ed3ea2984c5b423582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DieType llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore (DieType D, std::string * OriginalFullName=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="#a6b109c547db47dc708d9585c485237ee">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierBefore</a>, <a href="#add6ceb903c623e57ca78ec00ab7d7a08">llvm::DWARFTypePrinter&lt; DieType &gt;::appendPointerLikeTypeBefore</a>, <a href="#a3ff71a14b903ade718fa244e2762daaa">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedName</a>, <a href="#a3998337d3fd6fdd5a5c358a56e0a7d5d">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedNameBefore</a>, <a href="#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a>, <a href="#a09f85524dd190f2649d7f584a2edcce3">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTypeTagName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a0dad0e7451ff5528c8455678b96955e0">llvm::DWARFTypePrinter&lt; DieType &gt;::EndedWithTemplate</a>, <a href="#a2562cc2a382fcd930afda3a6b75fa22b">llvm::DWARFTypePrinter&lt; DieType &gt;::needsParens</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="#a51ed52f10b37a50cdfdadff972b96ef1">llvm::DWARFTypePrinter&lt; DieType &gt;::OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a4427489f872210c554e05e29c220bdb2">llvm::detail::toString</a> and <a href="#a208bb17462bd5325b49054e0a9dc30ba">llvm::DWARFTypePrinter&lt; DieType &gt;::Word</a>.</p>


<p>Referenced by <a href="#a3998337d3fd6fdd5a5c358a56e0a7d5d">llvm::DWARFTypePrinter&lt; DieType &gt;::appendQualifiedNameBefore</a> and <a href="#a5985e698626fb7c2f63ee98d0bab122a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedName</a>.</p>

</div>
</div>

### decomposeConstVolatile() {#a3ffc1f6f44d6f01f289108370a0fbf21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFTypePrinter&lt; DieType &gt;::decomposeConstVolatile (DieType &amp; N, DieType &amp; T, DieType &amp; C, DieType &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="#abcb3596d8a38517290a40f2fa529876a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierAfter</a> and <a href="#a6b109c547db47dc708d9585c485237ee">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierBefore</a>.</p>

</div>
</div>

### needsParens() {#a2562cc2a382fcd930afda3a6b75fa22b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFTypePrinter&lt; DieType &gt;::needsParens (DieType D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#a55527b7757dcebab2e38fbd45bf655bf">llvm::DWARFTypePrinter&lt; DieType &gt;::skipQualifiers</a>.</p>


<p>Referenced by <a href="#add6ceb903c623e57ca78ec00ab7d7a08">llvm::DWARFTypePrinter&lt; DieType &gt;::appendPointerLikeTypeBefore</a>, <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a> and <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

### skipQualifiers() {#a55527b7757dcebab2e38fbd45bf655bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DieType llvm::DWARFTypePrinter&lt; DieType &gt;::skipQualifiers (DieType D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#acb16672c3246802c7a263c607b978678">llvm::detail::resolveReferencedType</a>.</p>


<p>Referenced by <a href="#a2562cc2a382fcd930afda3a6b75fa22b">llvm::DWARFTypePrinter&lt; DieType &gt;::needsParens</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EndedWithTemplate {#a0dad0e7451ff5528c8455678b96955e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFTypePrinter&lt; DieType &gt;::EndedWithTemplate = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>Referenced by <a href="#ac707ceca2d4a993e39b72a224814bc1a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendAndTerminateTemplateParameters</a>, <a href="#a3835a080f718461efd839bc1b856c89b">llvm::DWARFTypePrinter&lt; DieType &gt;::appendArrayType</a>, <a href="#add6ceb903c623e57ca78ec00ab7d7a08">llvm::DWARFTypePrinter&lt; DieType &gt;::appendPointerLikeTypeBefore</a>, <a href="#a9f62eedabc99865b72dc43f7883f31a6">llvm::DWARFTypePrinter&lt; DieType &gt;::appendSubroutineNameAfter</a>, <a href="#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a> and <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

### OS {#a51ed52f10b37a50cdfdadff972b96ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::DWARFTypePrinter&lt; DieType &gt;::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>Referenced by <a href="#ac707ceca2d4a993e39b72a224814bc1a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendAndTerminateTemplateParameters</a>, <a href="#a3835a080f718461efd839bc1b856c89b">llvm::DWARFTypePrinter&lt; DieType &gt;::appendArrayType</a>, <a href="#a6b109c547db47dc708d9585c485237ee">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierBefore</a>, <a href="#add6ceb903c623e57ca78ec00ab7d7a08">llvm::DWARFTypePrinter&lt; DieType &gt;::appendPointerLikeTypeBefore</a>, <a href="#a6ba541b95a40e65f1e21feeedb1b945e">llvm::DWARFTypePrinter&lt; DieType &gt;::appendScopes</a>, <a href="#a9f62eedabc99865b72dc43f7883f31a6">llvm::DWARFTypePrinter&lt; DieType &gt;::appendSubroutineNameAfter</a>, <a href="#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a>, <a href="#a09f85524dd190f2649d7f584a2edcce3">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTypeTagName</a>, <a href="#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>, <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a> and <a href="#a8a6ba261d1cca78325d5a642435c59b0">llvm::DWARFTypePrinter&lt; DieType &gt;::DWARFTypePrinter</a>.</p>

</div>
</div>

### Word {#a208bb17462bd5325b49054e0a9dc30ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFTypePrinter&lt; DieType &gt;::Word = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>


<p>Referenced by <a href="#ac707ceca2d4a993e39b72a224814bc1a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendAndTerminateTemplateParameters</a>, <a href="#a6b109c547db47dc708d9585c485237ee">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierBefore</a>, <a href="#add6ceb903c623e57ca78ec00ab7d7a08">llvm::DWARFTypePrinter&lt; DieType &gt;::appendPointerLikeTypeBefore</a> and <a href="#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### scopedTAGs() {#a8bd0ac5fed870890107155d898a0ceb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DieType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFTypePrinter&lt; DieType &gt;::scopedTAGs (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
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

<p>Returns True if the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> TAG is one of the ones that is scopped.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">DWARFTypePrinter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
