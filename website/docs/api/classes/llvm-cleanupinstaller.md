---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cleanupinstaller
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CleanupInstaller` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::CleanupInstaller { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">llvm/Support/ToolOutputFile.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c9dd60a97ff0a5fde60f97e99e4315">CleanupInstaller</a> (StringRef Filename)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aea26b563a856642fa6d4e8e4e2aaf9">~CleanupInstaller</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6828eb4575f3b2ee2a39447aaf87ebd5">getFilename</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafac6ba91ba40d309e7aa3f14c04cee7">Filename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name of the file. <a href="#aafac6ba91ba40d309e7aa3f14c04cee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa9482c3523a6c8d5918d32347da49d">Keep</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The flag which indicates whether we should not delete the file. <a href="#abaa9482c3523a6c8d5918d32347da49d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CleanupInstaller() {#a91c9dd60a97ff0a5fde60f97e99e4315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CleanupInstaller::CleanupInstaller (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp">ToolOutputFile.cpp</a>.</p>


<p>References <a href="#aafac6ba91ba40d309e7aa3f14c04cee7">Filename</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp/#a718b79f3760a7f4b55a872176f9ee8d8">isStdout</a>, <a href="#abaa9482c3523a6c8d5918d32347da49d">Keep</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aee27cc5336ecd3f21eeda4ad2826b915">llvm::sys::RemoveFileOnSignal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CleanupInstaller() {#a0aea26b563a856642fa6d4e8e4e2aaf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CleanupInstaller::~CleanupInstaller ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp">ToolOutputFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7936dae925973eb8b0921c01b70b16d8">llvm::sys::DontRemoveFileOnSignal</a>, <a href="#aafac6ba91ba40d309e7aa3f14c04cee7">Filename</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp/#a718b79f3760a7f4b55a872176f9ee8d8">isStdout</a>, <a href="#abaa9482c3523a6c8d5918d32347da49d">Keep</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFilename() {#a6828eb4575f3b2ee2a39447aaf87ebd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::CleanupInstaller::getFilename ()</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>


<p>Reference <a href="#aafac6ba91ba40d309e7aa3f14c04cee7">Filename</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Filename {#aafac6ba91ba40d309e7aa3f14c04cee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::CleanupInstaller::Filename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name of the file.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>


<p>Referenced by <a href="#a91c9dd60a97ff0a5fde60f97e99e4315">CleanupInstaller</a>, <a href="#a6828eb4575f3b2ee2a39447aaf87ebd5">getFilename</a> and <a href="#a0aea26b563a856642fa6d4e8e4e2aaf9">~CleanupInstaller</a>.</p>

</div>
</div>

### Keep {#abaa9482c3523a6c8d5918d32347da49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CleanupInstaller::Keep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The flag which indicates whether we should not delete the file.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>


<p>Referenced by <a href="#a91c9dd60a97ff0a5fde60f97e99e4315">CleanupInstaller</a> and <a href="#a0aea26b563a856642fa6d4e8e4e2aaf9">~CleanupInstaller</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp">ToolOutputFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
