---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/exponentialbackoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExponentialBackoff` Class Reference

<p>A class to help implement exponential backoff. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ExponentialBackoff { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">llvm/Support/ExponentialBackoff.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2c6943b41cbbf75a554c1b43a92d25">duration</a> = std::chrono::steady_clock::duration</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae628d41d81aaa7c963bd14d75a3452e9">time_point</a> = std::chrono::steady_clock::time_point</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a72825a12a5f0edde2b4483124b190">ExponentialBackoff</a> (duration Timeout, duration MinWait=std::chrono::milliseconds(10), duration MaxWait=std::chrono::milliseconds(500))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e8404047337057e4fff7e416f28ce3b">waitForNextAttempt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocks while waiting for the next attempt. <a href="#a2e8404047337057e4fff7e416f28ce3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4d2c6943b41cbbf75a554c1b43a92d25">duration</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2bea2509c7c98f5747072e4ee12f82">MinWait</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4d2c6943b41cbbf75a554c1b43a92d25">duration</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58fde044ad9b62a267bd895c9e5c5d5c">MaxWait</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae628d41d81aaa7c963bd14d75a3452e9">time_point</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0850165b7001b7514c78b56f2066751e">EndTime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::random_device</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a8ce9588b35c7b1dc491352a6ecbaa">RandDev</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a381b2fed148153fedda8c1a0e5934386">CurrentMultiplier</a> = 1</td>
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

<p>A class to help implement exponential backoff.</p>


<p>Example usage:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ac3a72825a12a5f0edde2b4483124b190">ExponentialBackoff</a> Backoff(10s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">do</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tryToDoSomething())</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ItWorked;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">} </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (Backoff.waitForNextAttempt());</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> Timeout;</span></span></div>

</div>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### duration {#a4d2c6943b41cbbf75a554c1b43a92d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ExponentialBackoff::duration =  std::chrono::steady_clock::duration</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>

</div>
</div>

### time\_point {#ae628d41d81aaa7c963bd14d75a3452e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ExponentialBackoff::time_point =  std::chrono::steady_clock::time_point</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExponentialBackoff() {#ac3a72825a12a5f0edde2b4483124b190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ExponentialBackoff::ExponentialBackoff (<a href="#a4d2c6943b41cbbf75a554c1b43a92d25">duration</a> Timeout, <a href="#a4d2c6943b41cbbf75a554c1b43a92d25">duration</a> MinWait=std::chrono::milliseconds(10), <a href="#a4d2c6943b41cbbf75a554c1b43a92d25">duration</a> MaxWait=std::chrono::milliseconds(500))</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Timeout</td>
<td class="doxyParamItemDescription"><p>the maximum wall time this should run for starting when this object is constructed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MinWait</td>
<td class="doxyParamItemDescription"><p>the minimum amount of time <span class="doxyComputerOutput">waitForNextAttempt</span> will sleep for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxWait</td>
<td class="doxyParamItemDescription"><p>the maximum amount of time <span class="doxyComputerOutput">waitForNextAttempt</span> will sleep for.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a0edd35207e47a9fb4d484238d3172e82">now</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### waitForNextAttempt() {#a2e8404047337057e4fff7e416f28ce3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ExponentialBackoff::waitForNextAttempt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocks while waiting for the next attempt.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if you should try again, false if the timeout has been reached.</p></dd>
</dl>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/support/exponentialbackoff-cpp">ExponentialBackoff.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#a8a975a4bfeea746f3269211bd72a02e2">llvm::LockFileManager::waitForUnlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentMultiplier {#a381b2fed148153fedda8c1a0e5934386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::ExponentialBackoff::CurrentMultiplier = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>

</div>
</div>

### EndTime {#a0850165b7001b7514c78b56f2066751e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">time_point llvm::ExponentialBackoff::EndTime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>

</div>
</div>

### MaxWait {#a58fde044ad9b62a267bd895c9e5c5d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">duration llvm::ExponentialBackoff::MaxWait</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>

</div>
</div>

### MinWait {#a7f2bea2509c7c98f5747072e4ee12f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">duration llvm::ExponentialBackoff::MinWait</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>

</div>
</div>

### RandDev {#aa1a8ce9588b35c7b1dc491352a6ecbaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::random_device llvm::ExponentialBackoff::RandDev</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exponentialbackoff-h">ExponentialBackoff.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/exponentialbackoff-cpp">ExponentialBackoff.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
