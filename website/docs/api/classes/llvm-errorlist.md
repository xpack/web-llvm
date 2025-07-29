---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/errorlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ErrorList` Class

<p>Special <a href="/web-llvm/docs/api/classes/llvm/errorinfo">ErrorInfo</a> subclass representing a list of ErrorInfos. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ErrorList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/errorinfo">ErrorInfo&lt;ThisErrT, ParentErrT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for user error types. <a href="/web-llvm/docs/api/classes/llvm/errorinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... HandlerTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2c831eabfe62504c9cc0cc16e0799c44">handleErrors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> the ErrorInfo(s) contained in E to their respective handlers. <a href="#a2c831eabfe62504c9cc0cc16e0799c44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HandlerT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1eaa283b96012bf2a0f2e05d04a952a">visitErrors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit all the ErrorInfo(s) contained in E by passing them to the respective handler, without consuming the error. <a href="#ac1eaa283b96012bf2a0f2e05d04a952a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab08cc727c18c44d888f4dce4903c8741">joinErrors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concatenate errors. <a href="#ab08cc727c18c44d888f4dce4903c8741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573231b271abc73ceb6c7ea973cd3e99">ErrorList</a> (std::unique_ptr&lt; ErrorInfoBase &gt; Payload1, std::unique_ptr&lt; ErrorInfoBase &gt; Payload2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8790bbbccdcfe4d33d583c40fa89fa01">log</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print an error message to an output stream. <a href="#a8790bbbccdcfe4d33d583c40fa89fa01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272eaea42b8132712f7381976f09eb41">convertToErrorCode</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this error to a std::error_code. <a href="#a272eaea42b8132712f7381976f09eb41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f640d93a684064fcf898260d2106980">Payloads</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ebdf3c3d18bea7c68f789703a3a51a">join</a> (Error E1, Error E2)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cac4b6c688542b28efaa8360e552594">ID</a> = 0</td>
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

<p>Special <a href="/web-llvm/docs/api/classes/llvm/errorinfo">ErrorInfo</a> subclass representing a list of ErrorInfos.</p>


<p>Instances of this class are constructed by joinError.</p>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<div class="doxySectionDef">

## Friends

### handleErrors {#a2c831eabfe62504c9cc0cc16e0799c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> E, HandlerTs &amp;&amp;... Handlers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> the ErrorInfo(s) contained in E to their respective handlers.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> unhandled errors (or Errors returned by handlers) are re-concatenated and returned. Because this function returns an error, its result must also be checked or returned. If you intend to handle all errors use handleAllErrors (which returns void, and will abort() on unhandled errors) instead.</p>


<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### joinErrors {#ab08cc727c18c44d888f4dce4903c8741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> E1, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> E2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Concatenate errors.</p>


<p>The resulting <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> is unchecked, and contains the ErrorInfo(s), if any, contained in E1, followed by the ErrorInfo(s), if any, contained in E2.</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### visitErrors {#ac1eaa283b96012bf2a0f2e05d04a952a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; E, HandlerT H</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit all the ErrorInfo(s) contained in E by passing them to the respective handler, without consuming the error.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ErrorList() {#a573231b271abc73ceb6c7ea973cd3e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorList::ErrorList (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> &gt; Payload1, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> &gt; Payload2)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertToErrorCode() {#a272eaea42b8132712f7381976f09eb41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::ErrorList::convertToErrorCode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert this error to a std::error_code.</p>


<p>This is a temporary crutch to enable interaction with code still using std::error_code. It will be removed in the future.</p>


<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### log() {#a8790bbbccdcfe4d33d583c40fa89fa01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ErrorList::log (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print an error message to an output stream.</p>

<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Payloads {#a0f640d93a684064fcf898260d2106980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ErrorInfoBase&gt; &gt; llvm::ErrorList::Payloads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### join() {#ae5ebdf3c3d18bea7c68f789703a3a51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::ErrorList::join (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> E1, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> E2)</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a9cac4b6c688542b28efaa8360e552594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::ErrorList::ID = 0</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
