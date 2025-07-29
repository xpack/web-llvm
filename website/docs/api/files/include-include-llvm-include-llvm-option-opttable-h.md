---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/option/opttable-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `OptTable.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringtable-h">llvm/ADT/StringTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/optspecifier-h">llvm/Option/OptSpecifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">llvm/Support/StringSaver.h</a>"
#include &lt;cassert&gt;
#include &lt;string&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/opt">opt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for overload resolution while transitioning from FlagsToInclude/FlagsToExclude APIs to VisibilityMask APIs. <a href="/web-llvm/docs/api/classes/llvm/opt/visibility/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide access to the <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> info table. <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">Info</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Entry for a single option instance in the option data table. <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable">GenericOptTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a>. <a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/precomputedopttable">PrecomputedOptTable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a753cac1061caf8241fae30a7cdea6">LLVM_MAKE_OPT_ID_WITH_ID_PREFIX</a>(ID_PREFIX, PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;  ID_PREFIX##ID</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926eb4692221bf90c370931755b0dba8">LLVM_MAKE_OPT_ID</a>(PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad884d142cc6a33d1011a8581c91763bd">LLVM_CONSTRUCT_OPT_INFO_WITH_ID_PREFIX</a>(ID_PREFIX, PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d464550af0bb466b5a22350251776d4">LLVM_CONSTRUCT_OPT_INFO</a>(PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;...</td>
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

### LLVM\_CONSTRUCT\_OPT\_INFO {#a7d464550af0bb466b5a22350251776d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_CONSTRUCT_OPT_INFO(PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#ad884d142cc6a33d1011a8581c91763bd">LLVM_CONSTRUCT_OPT_INFO_WITH_ID_PREFIX</a>(                                      \
      OPT_, PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>, GROUP, ALIAS,     \
      ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS,     \
      METAVAR, VALUES)
</div>
</dd>
</dl>

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### LLVM\_CONSTRUCT\_OPT\_INFO\_WITH\_ID\_PREFIX {#ad884d142cc6a33d1011a8581c91763bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_CONSTRUCT_OPT_INFO_WITH_ID_PREFIX(ID_PREFIX, PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">llvm::opt::OptTable::Info</a> {                                                  \
    PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, HELPTEXT, HELPTEXTSFORVARIANTS,     \
        METAVAR, ID_PREFIX##ID, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">llvm::opt::Option::KIND</a>##Class, PARAM, FLAGS,  \
        VISIBILITY, ID_PREFIX##GROUP, ID_PREFIX##ALIAS, ALIASARGS, VALUES      \
  }
</div>
</dd>
</dl>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### LLVM\_MAKE\_OPT\_ID {#a926eb4692221bf90c370931755b0dba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_MAKE_OPT_ID(PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a02a753cac1061caf8241fae30a7cdea6">LLVM_MAKE_OPT_ID_WITH_ID_PREFIX</a>(OPT_, PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, \
                                  ID, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>, GROUP, ALIAS, ALIASARGS, FLAGS,    \
                                  VISIBILITY, PARAM, HELPTEXT,                 \
                                  HELPTEXTSFORVARIANTS, METAVAR, VALUES)
</div>
</dd>
</dl>

<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### LLVM\_MAKE\_OPT\_ID\_WITH\_ID\_PREFIX {#a02a753cac1061caf8241fae30a7cdea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_MAKE_OPT_ID_WITH_ID_PREFIX(ID_PREFIX, PREFIXES_OFFSET, PREFIXED_NAME_OFFSET, ID, KIND, GROUP, ALIAS, ALIASARGS, FLAGS, VISIBILITY, PARAM, HELPTEXT, HELPTEXTSFORVARIANTS, METAVAR, VALUES)&nbsp;&nbsp;&nbsp;  ID_PREFIX##ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
