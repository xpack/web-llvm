---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/httpclient
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HTTPClient` Class

<p>A reusable client that can perform HTTPRequests through a network socket. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::HTTPClient { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">llvm/Debuginfod/HTTPClient.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23a15a8f27ac926a86c2ef7bc7bfebcb">HTTPClient</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97467b9bd9469200fb5266ae3622acc2">~HTTPClient</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f7a940d825d8d2e2bca0aff20d771f">setTimeout</a> (std::chrono::milliseconds Timeout)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the timeout for the entire request, in milliseconds. <a href="#ad8f7a940d825d8d2e2bca0aff20d771f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e83d694bc912421b6c95985adf01d9">perform</a> (const HTTPRequest &amp;Request, HTTPResponseHandler &amp;Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs the Request, passing response data to the Handler. <a href="#a99e83d694bc912421b6c95985adf01d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d0ac3cb0735adf78a0d1d0b2252eb4">responseCode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the last received response code or zero if none. <a href="#a49d0ac3cb0735adf78a0d1d0b2252eb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0303f2e7844f319270e783e3ecc59274">isAvailable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true only if LLVM has been compiled with a working <a href="/web-llvm/docs/api/classes/llvm/httpclient">HTTPClient</a>. <a href="#a0303f2e7844f319270e783e3ecc59274">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5901772ab222be136d7dabcd349a89a9">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Must be called at the beginning of a program, while it is a single thread. <a href="#a5901772ab222be136d7dabcd349a89a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae76bcc6bd253ea113bc9dbe1ae3f029d">cleanup</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Must be called at the end of a program, while it is a single thread. <a href="#ae76bcc6bd253ea113bc9dbe1ae3f029d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed9872a019597bc9572d382a26b24ec">IsInitialized</a> = false</td>
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

<p>A reusable client that can perform HTTPRequests through a network socket.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HTTPClient() {#a23a15a8f27ac926a86c2ef7bc7bfebcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HTTPClient::HTTPClient ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~HTTPClient() {#a97467b9bd9469200fb5266ae3622acc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HTTPClient::~HTTPClient ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### perform() {#a99e83d694bc912421b6c95985adf01d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error HTTPClient::perform (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/httprequest">HTTPRequest</a> &amp; Request, <a href="/web-llvm/docs/api/classes/llvm/httpresponsehandler">HTTPResponseHandler</a> &amp; Handler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Performs the Request, passing response data to the Handler.</p>


<p>Returns all errors which occur during the request. Aborts if an error is returned by a Handler method.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp">HTTPClient.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42f631dfb82c9318a72f2c1bdab57ad4">llvm::getCachedOrDownloadArtifact</a>.</p>

</div>
</div>

### responseCode() {#a49d0ac3cb0735adf78a0d1d0b2252eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HTTPClient::responseCode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the last received response code or zero if none.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp">HTTPClient.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42f631dfb82c9318a72f2c1bdab57ad4">llvm::getCachedOrDownloadArtifact</a>.</p>

</div>
</div>

### setTimeout() {#ad8f7a940d825d8d2e2bca0aff20d771f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HTTPClient::setTimeout (std::chrono::milliseconds Timeout)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the timeout for the entire request, in milliseconds.</p>


<p>A zero or negative value means the request never times out.</p>


<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp">HTTPClient.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42f631dfb82c9318a72f2c1bdab57ad4">llvm::getCachedOrDownloadArtifact</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### cleanup() {#ae76bcc6bd253ea113bc9dbe1ae3f029d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HTTPClient::cleanup ()</td>
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

<p>Must be called at the end of a program, while it is a single thread.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp">HTTPClient.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/httpclientcleanup/#a5ba27ef3472813a6a6ea4c6e2e8acc69">HTTPClientCleanup::~HTTPClientCleanup</a>.</p>

</div>
</div>

### initialize() {#a5901772ab222be136d7dabcd349a89a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HTTPClient::initialize ()</td>
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

<p>Must be called at the beginning of a program, while it is a single thread.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp">HTTPClient.cpp</a>.</p>

</div>
</div>

### isAvailable() {#a0303f2e7844f319270e783e3ecc59274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HTTPClient::isAvailable ()</td>
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

<p>Returns true only if LLVM has been compiled with a working <a href="/web-llvm/docs/api/classes/llvm/httpclient">HTTPClient</a>.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp">HTTPClient.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af96e5af52e7fe106cf27c6c84ed7d934">llvm::canUseDebuginfod</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a42f631dfb82c9318a72f2c1bdab57ad4">llvm::getCachedOrDownloadArtifact</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### IsInitialized {#a0ed9872a019597bc9572d382a26b24ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HTTPClient::IsInitialized = false</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42f631dfb82c9318a72f2c1bdab57ad4">llvm::getCachedOrDownloadArtifact</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">HTTPClient.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp">HTTPClient.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
