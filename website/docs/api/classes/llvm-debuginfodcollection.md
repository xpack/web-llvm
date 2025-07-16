---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/debuginfodcollection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DebuginfodCollection` Class Reference

<p>Tracks a collection of debuginfod artifacts on the local filesystem. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DebuginfodCollection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">llvm/Debuginfod/Debuginfod.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a653b254320ed5ac8fec48830363d9e">DebuginfodCollection</a> (ArrayRef&lt; StringRef &gt; Paths, DebuginfodLog &amp;Log, ThreadPoolInterface &amp;Pool, double MinInterval)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a1fb7af3be229df5d6fa47b5ded6f5">update</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a658e5ec09f37dd9bc0bb13e8aa57b8d0">updateForever</a> (std::chrono::milliseconds Interval)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada228a8f1796b1bb98030dc0bd3cc7c">findDebugBinaryPath</a> (object::BuildIDRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c512cc4358cdcd16d9c633a4bb1a4ef">findBinaryPath</a> (object::BuildIDRef)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b868c79d8cab6327bc832ddb7a66d69">findBinaries</a> (StringRef Path)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df7e09474e478da82d1b0e937290d0b">getDebugBinaryPath</a> (object::BuildIDRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5c74e57dc30557339d22b435d90d89">getBinaryPath</a> (object::BuildIDRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760d9076f35165f46a06046411143523">updateIfStale</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::string, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95163891a407684f2486e9aa79b1777d">Paths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#aa3f166e8bb27e1c9a1e5cbb439e9749b">sys::RWMutex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c7fc135296930e95c993e3d0724ccc">BinariesMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130d6f09f0b49b02e98bc363926a6bbe">Binaries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#aa3f166e8bb27e1c9a1e5cbb439e9749b">sys::RWMutex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3aa410fd94d16cead0bc7113238c550">DebugBinariesMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2d75e7b302eb9aa00dad8fd8087eba">DebugBinaries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debuginfodlog">DebuginfodLog</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dac62b13cae982fceeab178690fef5a">Log</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface">ThreadPoolInterface</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5350d1e7d0032c818b78bef3736625a2">Pool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timer">Timer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac92a39f48beb905c246904400ac6cbb0">UpdateTimer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52d48084c5b60251870b6118e4670fee">sys::Mutex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8522921f04ee56d72c8e339e4e4a72">UpdateMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec07e7d601c2e3b326712b4a7f97b50b">MinInterval</a></td>
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

<p>Tracks a collection of debuginfod artifacts on the local filesystem.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebuginfodCollection() {#a1a653b254320ed5ac8fec48830363d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebuginfodCollection::DebuginfodCollection (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Paths, <a href="/web-llvm/docs/api/classes/llvm/debuginfodlog">DebuginfodLog</a> &amp; Log, <a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface">ThreadPoolInterface</a> &amp; Pool, double MinInterval)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findBinaryPath() {#a5c512cc4358cdcd16d9c633a4bb1a4ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; llvm::DebuginfodCollection::findBinaryPath (<a href="/web-llvm/docs/api/namespaces/llvm/object/#ac1078293d640738282058eba178e9472">object::BuildIDRef</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#aada228a8f1796b1bb98030dc0bd3cc7c">findDebugBinaryPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a4d726c1a5c0e5542fce1bed7a02b43">llvm::getCachedOrDownloadExecutable</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### findDebugBinaryPath() {#aada228a8f1796b1bb98030dc0bd3cc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; llvm::DebuginfodCollection::findDebugBinaryPath (<a href="/web-llvm/docs/api/namespaces/llvm/object/#ac1078293d640738282058eba178e9472">object::BuildIDRef</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a385acc5407544454df091d3c3f7f6ad0">llvm::getCachedOrDownloadDebuginfo</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a5c512cc4358cdcd16d9c633a4bb1a4ef">findBinaryPath</a>.</p>

</div>
</div>

### update() {#a68a1fb7af3be229df5d6fa47b5ded6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DebuginfodCollection::update ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a658e5ec09f37dd9bc0bb13e8aa57b8d0">updateForever</a>.</p>

</div>
</div>

### updateForever() {#a658e5ec09f37dd9bc0bb13e8aa57b8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DebuginfodCollection::updateForever (std::chrono::milliseconds Interval)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a68a1fb7af3be229df5d6fa47b5ded6f5">update</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findBinaries() {#a2b868c79d8cab6327bc832ddb7a66d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DebuginfodCollection::findBinaries (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>

</div>
</div>

### getBinaryPath() {#aaf5c74e57dc30557339d22b435d90d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; std::string &gt; &gt; llvm::DebuginfodCollection::getBinaryPath (<a href="/web-llvm/docs/api/namespaces/llvm/object/#ac1078293d640738282058eba178e9472">object::BuildIDRef</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>

</div>
</div>

### getDebugBinaryPath() {#a3df7e09474e478da82d1b0e937290d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; std::string &gt; &gt; llvm::DebuginfodCollection::getDebugBinaryPath (<a href="/web-llvm/docs/api/namespaces/llvm/object/#ac1078293d640738282058eba178e9472">object::BuildIDRef</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>

</div>
</div>

### updateIfStale() {#a760d9076f35165f46a06046411143523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; llvm::DebuginfodCollection::updateIfStale ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Binaries {#a130d6f09f0b49b02e98bc363926a6bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::string&gt; llvm::DebuginfodCollection::Binaries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### BinariesMutex {#a41c7fc135296930e95c993e3d0724ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::RWMutex llvm::DebuginfodCollection::BinariesMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### DebugBinaries {#a9f2d75e7b302eb9aa00dad8fd8087eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::string&gt; llvm::DebuginfodCollection::DebugBinaries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### DebugBinariesMutex {#ae3aa410fd94d16cead0bc7113238c550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::RWMutex llvm::DebuginfodCollection::DebugBinariesMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### Log {#a3dac62b13cae982fceeab178690fef5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebuginfodLog&amp; llvm::DebuginfodCollection::Log</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### MinInterval {#aec07e7d601c2e3b326712b4a7f97b50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::DebuginfodCollection::MinInterval</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### Paths {#a95163891a407684f2486e9aa79b1777d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::string, 1&gt; llvm::DebuginfodCollection::Paths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### Pool {#a5350d1e7d0032c818b78bef3736625a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPoolInterface&amp; llvm::DebuginfodCollection::Pool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### UpdateMutex {#abf8522921f04ee56d72c8e339e4e4a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::Mutex llvm::DebuginfodCollection::UpdateMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

### UpdateTimer {#ac92a39f48beb905c246904400ac6cbb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Timer llvm::DebuginfodCollection::UpdateTimer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
