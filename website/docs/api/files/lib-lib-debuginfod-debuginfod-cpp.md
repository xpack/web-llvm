---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfod/debuginfod-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Debuginfod.cpp` File Reference

<p>This file contains several definitions for the debuginfod client and server. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">llvm/Debuginfod/Debuginfod.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">llvm/BinaryFormat/Magic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">llvm/DebugInfo/DWARF/DWARFContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">llvm/DebugInfo/Symbolize/Symbolize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/httpclient-h">llvm/Debuginfod/HTTPClient.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/buildid-h">llvm/Object/BuildID.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">llvm/Object/ELFObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">llvm/Support/CachePruning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/caching-h">llvm/Support/Caching.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">llvm/Support/FileUtilities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">llvm/Support/ThreadPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">llvm/Support/xxhash.h</a>"
#include &lt;atomic&gt;
#include &lt;optional&gt;
#include &lt;thread&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/anonymous-debuginfod-cpp-">anonymous{Debuginfod.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-debuginfod-cpp-/streamedhttpresponsehandler">StreamedHTTPResponseHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A simple handler which streams the returned data to a cache file. <a href="/web-llvm/docs/api/classes/llvm/anonymous-debuginfod-cpp-/streamedhttpresponsehandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file contains several definitions for the debuginfod client and server.</p>


<p>For the client, this file defines the fetchInfo function. For the server, this file defines the DebuginfodLogEntry and DebuginfodServer structs, as well as the DebuginfodLog, DebuginfodCollection classes. The fetchInfo function retrieves any of the three supported artifact types: (executable, debuginfo, source file) associated with a build-id from debuginfod servers. If a source file is to be fetched, its absolute path must be specified in the Description argument to fetchInfo. The DebuginfodLogEntry, DebuginfodLog, and DebuginfodCollection are used by the DebuginfodServer to scan the local filesystem for binaries and serve the debuginfod protocol.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
