---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/filecheck
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FileCheck` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> class takes the request and exposes various methods that use information from the request. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FileCheck { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">llvm/FileCheck/FileCheck.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75eaf8382d066e70396a9f9d1eefaa62">FileCheck</a> (FileCheckRequest Req)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59983180509d717048479774e529cec">~FileCheck</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20fa01b6cdae5b207cf5dcdda4fced04">readCheckFile</a> (SourceMgr &amp;SM, StringRef Buffer, std::pair&lt; unsigned, unsigned &gt; *ImpPatBufferIDRange=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads the check file from <span class="doxyComputerOutput">Buffer</span> and records the expected strings it contains. <a href="#a20fa01b6cdae5b207cf5dcdda4fced04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5e24a0f2fd2cbea147c73975624359">ValidateCheckPrefixes</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236b08c46b974292f9ecf297704a06bb">CanonicalizeFile</a> (MemoryBuffer &amp;MB, SmallVectorImpl&lt; char &gt; &amp;OutputBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonicalizes whitespaces in the file. <a href="#a236b08c46b974292f9ecf297704a06bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a7a7f317661b984c86d196fa44dff9">checkInput</a> (SourceMgr &amp;SM, StringRef Buffer, std::vector&lt; FileCheckDiag &gt; *Diags=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks the input to <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> provided in the <span class="doxyComputerOutput">Buffer</span> against the expected strings read from the check file and record diagnostics emitted in <span class="doxyComputerOutput">Diags</span>. <a href="#a95a7a7f317661b984c86d196fa44dff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ac788504091f259095969f8f962992">Req</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e5e82039819dc65c7ac72ea396a6137">PatternContext</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckstring">FileCheckString</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba655dbec99dea50bab52d402149029">CheckStrings</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> class takes the request and exposes various methods that use information from the request.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FileCheck() {#a75eaf8382d066e70396a9f9d1eefaa62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheck::FileCheck (<a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> Req)</td>
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



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 1768 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FileCheck() {#aa59983180509d717048479774e529cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheck::~FileCheck ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CanonicalizeFile() {#a236b08c46b974292f9ecf297704a06bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef FileCheck::CanonicalizeFile (<a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; MB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; OutputBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Canonicalizes whitespaces in the file.</p>


<p>Line endings are replaced with UNIX-style '
<br/>
'.</p>


<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### checkInput() {#a95a7a7f317661b984c86d196fa44dff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FileCheck::checkInput (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks the input to <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> provided in the <span class="doxyComputerOutput">Buffer</span> against the expected strings read from the check file and record diagnostics emitted in <span class="doxyComputerOutput">Diags</span>.</p>


<p>Errors are recorded against <span class="doxyComputerOutput">SM</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if the input fails to satisfy the checks.</p></dd>
</dl>


<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 2674 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ae337924e2723d7d8255011f1ac5624cf">llvm::FileCheckString::Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccad88307ccd9067d72cfb0e62d19daa77d">llvm::Check::CheckLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ac112adffc4bcc18c146110a4c648b683">llvm::Pattern::getCheckTy</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a3b71a36a299b4598e79edc8cd2fce259">llvm::FileCheckString::Pat</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>

</div>
</div>

### readCheckFile() {#a20fa01b6cdae5b207cf5dcdda4fced04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FileCheck::readCheckFile (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, std::pair&lt; unsigned, unsigned &gt; * ImpPatBufferIDRange=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads the check file from <span class="doxyComputerOutput">Buffer</span> and records the expected strings it contains.</p>


<p>Errors are reported against <span class="doxyComputerOutput">SM</span>.</p>


<p>If <span class="doxyComputerOutput">ImpPatBufferIDRange</span>, then the range (inclusive start, exclusive end) of IDs for source buffers added to <span class="doxyComputerOutput">SM</span> for implicit patterns are recorded in it. The range is empty if there are none.</p>


<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 1773 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#aed4199779f05c32f4716378090f22472">addDefaultPrefixes</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#afe70aa1105a855036bdeb6426cac27db">llvm::SourceMgr::AddNewSourceBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccab74df0ffb39a8f2c0918324e23a899f2">llvm::Check::CheckBadCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca8b26e2b469fdd62f96446d3299b4189e">llvm::Check::CheckBadNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaf16a622382af4f7939c473b436c8f2ca">llvm::Check::CheckComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca6e00b905236376d8aec56ad3351a45b0">llvm::Check::CheckDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca80e33945f521f203f2a632bc0f2041e5">llvm::Check::CheckEmpty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaba2d525032487e7def52c8154b19e29c">llvm::Check::CheckEOF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccad88307ccd9067d72cfb0e62d19daa77d">llvm::Check::CheckLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccabced3746e039f44b8e662be748fd4e17">llvm::Check::CheckMisspelled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca49f3a249a76b57b5659baae2c45dfb75">llvm::Check::CheckNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca4f9655da5198915aff91bd25115d22fa">llvm::Check::CheckNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaf738504ab1341813c0cda15fa68a6310">llvm::Check::CheckSame</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae851887270f35d2a2670a79b9833d45b">llvm::StringRef::find_first_not_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>

</div>
</div>

### ValidateCheckPrefixes() {#adf5e24a0f2fd2cbea147c73975624359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FileCheck::ValidateCheckPrefixes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 2492 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a87fef1fd90a9f814f1b62f4346895419">DefaultCheckPrefixes</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a8c6721cddb52eb652ee858b650f696fc">DefaultCommentPrefixes</a>, <a href="/web-llvm/docs/api/classes/llvm/stringset/#add93efa62e06c599f1734f3b206232a0">llvm::StringSet&lt; AllocatorTy &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ae1863db0091c416836ecbf151ea73c90">ValidatePrefixes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CheckStrings {#a6ba655dbec99dea50bab52d402149029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FileCheckString&gt; llvm::FileCheck::CheckStrings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

### PatternContext {#a5e5e82039819dc65c7ac72ea396a6137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;FileCheckPatternContext&gt; llvm::FileCheck::PatternContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

### Req {#a37ac788504091f259095969f8f962992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheckRequest llvm::FileCheck::Req</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
