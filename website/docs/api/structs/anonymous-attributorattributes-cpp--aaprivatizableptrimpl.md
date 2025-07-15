---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAPrivatizablePtrImpl` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aaprivatizableptr">AAPrivatizablePtr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract interface for privatizability. <a href="/web-llvm/docs/api/structs/llvm/aaprivatizableptr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument">AAPrivatizablePtrArgument</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrfloating">AAPrivatizablePtrFloating</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab10cbc08fbfcbe3107641d2601aace78">AAPrivatizablePtrImpl</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a49ff3aab8396d192f5432d7803dedc">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that the abstract state should converge to the pessimistic state. <a href="#a2a49ff3aab8396d192f5432d7803dedc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476df5c2a2112ea7d6f7697b0b7be55a">identifyPrivatizableType</a> (Attributor &amp;A)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify the type we can chose for a private copy of the underlying argument. <a href="#a476df5c2a2112ea7d6f7697b0b7be55a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaebb3ce3a40f31a266360afc621a1eb3">combineTypes</a> (std::optional&lt; Type * &gt; T0, std::optional&lt; Type * &gt; T1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a privatizable type that encloses both T0 and T1. <a href="#aaebb3ce3a40f31a266360afc621a1eb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bccec3b37731ec1b657619b6bb27cef">getPrivatizableType</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type we can choose for a private copy of the underlying value. <a href="#a6bccec3b37731ec1b657619b6bb27cef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae956748a20e0e01e88b290b17b04f8d">getAsStr</a> (Attributor *A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return the "summarized" assumed state as string. <a href="#aae956748a20e0e01e88b290b17b04f8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35dd1e53b0ddedfaabeb2bd0a4ea27e7">PrivatizableType</a></td>
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


<p>Definition at line 7193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAPrivatizablePtrImpl() {#ab10cbc08fbfcbe3107641d2601aace78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl::AAPrivatizablePtrImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 7194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aaprivatizableptr/#a6ff32147668a17581a27eb59262c26e4">llvm::AAPrivatizablePtr::AAPrivatizablePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a> and <a href="#a35dd1e53b0ddedfaabeb2bd0a4ea27e7">PrivatizableType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a6cf9b23edc25779ec0536c660bda3b5e">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::AAPrivatizablePtrArgument</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrfloating/#a249d882968515b8784160e1f90ea769b">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrFloating::AAPrivatizablePtrFloating</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### combineTypes() {#aaebb3ce3a40f31a266360afc621a1eb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Type * &gt; anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl::combineTypes (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; T0, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; T1)</td>
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

<p>Return a privatizable type that encloses both T0 and T1.</p>


<p>TODO: This is merely a stub for now as we should manage a mapping as well.</p>


<p>Definition at line 7210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ad49bf673f21e06478f2be1990749ee37">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::identifyPrivatizableType</a>.</p>

</div>
</div>

### getAsStr() {#aae956748a20e0e01e88b290b17b04f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
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

<p>This function should return the "summarized" assumed state as string.</p>

<p>Definition at line 7225 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a> and <a href="/web-llvm/docs/api/structs/llvm/aaprivatizableptr/#a191bd40fa68e4e0b249ca21e4ad5ae07">llvm::AAPrivatizablePtr::isAssumedPrivatizablePtr</a>.</p>

</div>
</div>

### getPrivatizableType() {#a6bccec3b37731ec1b657619b6bb27cef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Type * &gt; anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl::getPrivatizableType ()</td>
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

<p>Return the type we can choose for a private copy of the underlying value.</p>


<p>std::nullopt means it is not clear yet, nullptr means there is none.</p>


<p>Definition at line 7221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#a35dd1e53b0ddedfaabeb2bd0a4ea27e7">PrivatizableType</a>.</p>

</div>
</div>

### identifyPrivatizableType() {#a476df5c2a2112ea7d6f7697b0b7be55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; Type * &gt; anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl::identifyPrivatizableType (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify the type we can chose for a private copy of the underlying argument.</p>


<p>std::nullopt means it is not clear yet, nullptr means there is none.</p>


<p>Definition at line 7206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#a2a49ff3aab8396d192f5432d7803dedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl::indicatePessimisticFixpoint ()</td>
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

<p>Indicate that the abstract state should converge to the pessimistic state.</p>


<p>This will usually revert the optimistically assumed state to the known to be true state.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>ChangeStatus::CHANGED as the assumed value may change.</p></dd>
</dl>


<p>Definition at line 7197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ac61c038186769d32f4f8c10168367965">llvm::AbstractState::indicatePessimisticFixpoint</a> and <a href="#a35dd1e53b0ddedfaabeb2bd0a4ea27e7">PrivatizableType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrcallsitereturned/#ac6c404fc18d0c438fcee19927197c211">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrfloating/#a2b5fd40a456d421cc1592f53bd9d253f">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrreturned/#a2a3a927a5400af239fb57b3762a85f45">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrcallsiteargument/#ab15ea1d1102ef77ffab18c2e35cada55">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### PrivatizableType {#a35dd1e53b0ddedfaabeb2bd0a4ea27e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Type *&gt; anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrImpl::PrivatizableType</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#ab10cbc08fbfcbe3107641d2601aace78">AAPrivatizablePtrImpl</a>, <a href="#a6bccec3b37731ec1b657619b6bb27cef">getPrivatizableType</a>, <a href="#a2a49ff3aab8396d192f5432d7803dedc">indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrcallsiteargument/#ab15ea1d1102ef77ffab18c2e35cada55">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
