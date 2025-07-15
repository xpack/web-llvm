---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/process-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Process.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "llvm/Config/config.h"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">llvm/Support/CrashRecoveryContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include &lt;optional&gt;
#include &lt;stdlib.h&gt;
#include "Unix/Process.inc"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99dc017fec75afe10928b651c570c3e8">colorcodes</a>[2][2][16][11] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1976a70072c9f199a4b9ab049faf4b">coreFilesPrevented</a> = !LLVM_ENABLE_CRASH_DUMPS</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, CODE, BOLD)&nbsp;&nbsp;&nbsp;"\033[0;" BOLD FGBG CODE "m"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81335dabba2add50bce294ac90785c88">ALLCOLORS</a>(FGBG, BRIGHT, BOLD)&nbsp;&nbsp;&nbsp;...</td>
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

## Variables

### colorcodes {#a99dc017fec75afe10928b651c570c3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char colorcodes[2][2][16][11]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    { <a href="#a81335dabba2add50bce294ac90785c88">ALLCOLORS</a>("3", "9", ""), <a href="#a81335dabba2add50bce294ac90785c88">ALLCOLORS</a>("3", "9", "1;"),},
    { <a href="#a81335dabba2add50bce294ac90785c88">ALLCOLORS</a>("4", "10", ""), <a href="#a81335dabba2add50bce294ac90785c88">ALLCOLORS</a>("4", "10", "1;")}
}
</div>
</dd>
</dl>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>

</div>
</div>

### coreFilesPrevented {#a3e1976a70072c9f199a4b9ab049faf4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool coreFilesPrevented = !LLVM_ENABLE_CRASH_DUMPS</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a92a5bd75c81ada9ad86716daac4a4fdc">llvm::sys::Process::AreCoreFilesPrevented</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ALLCOLORS {#a81335dabba2add50bce294ac90785c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ALLCOLORS(FGBG, BRIGHT, BOLD)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                           \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "0", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "1", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "2", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "3", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "4", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "5", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "6", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(FGBG, "7", BOLD),   \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "0", BOLD), \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "1", BOLD), \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "2", BOLD), \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "3", BOLD), \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "4", BOLD), \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "5", BOLD), \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "6", BOLD), \
    <a href="#a0c423f7dfd73eddee70e281430e337b4">COLOR</a>(BRIGHT, "7", BOLD), \
  }
</div>
</dd>
</dl>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>

</div>
</div>

### COLOR {#a0c423f7dfd73eddee70e281430e337b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COLOR(FGBG, CODE, BOLD)&nbsp;&nbsp;&nbsp;"\033[0;" BOLD FGBG CODE "m"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
