---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aanocapture
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AANoCapture` Struct Reference

<p>An abstract interface for all nocapture attributes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AANoCapture { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irattribute">IRAttribute&lt;AK, BaseType, AAType&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class that provides common functionality to manifest IR attributes. <a href="/web-llvm/docs/api/structs/llvm/irattribute/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl">AANoCaptureImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A class to hold the state of for no-capture attributes. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a0b4fb5399b000ba05e553a4d96305964">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State encoding bits. <a href="#a0b4fb5399b000ba05e553a4d96305964">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562d4a5f9290857ba956f97d33deff78">AANoCapture</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad25601c85e7e4e805df4f29bbac93e08">isKnownNoCapture</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value is not captured in its respective scope. <a href="#ad25601c85e7e4e805df4f29bbac93e08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a139955deae8f1ee31554caa8e1589">isAssumedNoCapture</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value is not captured in its respective scope. <a href="#ae6a139955deae8f1ee31554caa8e1589">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a9bf8d9969c5ccbe446c698ee0f294">isKnownNoCaptureMaybeReturned</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value is not captured in its respective scope but we allow it to escape through a "return". <a href="#ad8a9bf8d9969c5ccbe446c698ee0f294">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17d753e610e5fa8be4fec8287d3e309">isAssumedNoCaptureMaybeReturned</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value is not captured in its respective scope but we allow it to escape through a "return". <a href="#ac17d753e610e5fa8be4fec8287d3e309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bc2955de89c92ba3584337f8133105">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a> <a href="#a80bc2955de89c92ba3584337f8133105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f5fe31282bd7c9faf0460d0195bedb">getIdAddr</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a> <a href="#a14f5fe31282bd7c9faf0460d0195bedb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7886272a3ab071ecd4a576d865dc21">isImpliedByIR</a> (Attributor &amp;A, const IRPosition &amp;IRP, Attribute::AttrKind ImpliedAttributeKind, bool IgnoreSubsumingPositions=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/irattribute/#ac283e789a1c5ae7c595bdd1fde85cbaa">IRAttribute::isImpliedByIR</a>. <a href="#adb7886272a3ab071ecd4a576d865dc21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9efb4b2e9c757aaa9d2fada609eaee8">determineFunctionCaptureCapabilities</a> (const IRPosition &amp;IRP, const Function &amp;F, BitIntegerState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">State</span> according to the capture capabilities of <span class="doxyComputerOutput">F</span> for position <span class="doxyComputerOutput">IRP</span>. <a href="#af9efb4b2e9c757aaa9d2fada609eaee8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0639b327e46a46c804bc64ef0c12a7e1">isValidIRPositionForInit</a> (Attributor &amp;A, const IRPosition &amp;IRP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>. <a href="#a0639b327e46a46c804bc64ef0c12a7e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/aanocapture">AANoCapture</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ddfc843195b9ecd7ffec8405c521396">createForPosition</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>. <a href="#a5ddfc843195b9ecd7ffec8405c521396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b02641949e3535b987149182c901c1">classof</a> (const AbstractAttribute *AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aanocapture">AANoCapture</a>. <a href="#ad3b02641949e3535b987149182c901c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb470ec04114d55381446066944b973">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique ID (due to the unique address) <a href="#a8bb470ec04114d55381446066944b973">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An abstract interface for all nocapture attributes.</p>

<p>Definition at line 4356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a0b4fb5399b000ba05e553a4d96305964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State encoding bits.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOT_CAPTURED_IN_MEM<a id="a0b4fb5399b000ba05e553a4d96305964a886cd7d160324cd20be6c43de7d24d93"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOT_CAPTURED_IN_INT<a id="a0b4fb5399b000ba05e553a4d96305964a61acb0318e67130328c895c9cc404220"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOT_CAPTURED_IN_RET<a id="a0b4fb5399b000ba05e553a4d96305964a23b11d729b9274a206bf4e7a3e51482e"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_CAPTURE_MAYBE_RETURNED<a id="a0b4fb5399b000ba05e553a4d96305964a4f93ae6fded858c376d12d0d3e3a27e8"></a></td>
<td class="doxyEnumItemDescription">If we do not capture the value in memory or through integers we can only communicate it back as a derived pointer (= NOT_CAPTURED_IN_MEM | NOT_CAPTURED_IN_INT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_CAPTURE<a id="a0b4fb5399b000ba05e553a4d96305964a8464120a9bdc56bba45e3f099b783e93"></a></td>
<td class="doxyEnumItemDescription">
If we do not capture the value in memory, through integers, or as a derived pointer we know it is not captured (=
        NOT_CAPTURED_IN_MEM | NOT_CAPTURED_IN_INT | NOT_CAPTURED_IN_RET)
</td>
</tr>

</table>
</dd>
</dl>


<p>A set bit in the state means the property holds. NO_CAPTURE is the best possible state, 0 the worst possible state.</p>


<p>Definition at line 4383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AANoCapture() {#a562d4a5f9290857ba956f97d33deff78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AANoCapture::AANoCapture (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 4361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/irattribute/#ac3333cdcba76a6af382bcb7acd0d8419">llvm::IRAttribute&lt; Attribute::NoCapture, StateWrapper&lt; BitIntegerState&lt; uint16_t, 7, 0 &gt;, AbstractAttribute &gt;, AANoCapture &gt;::IRAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a31e0b685378db0718fa5138ba5e5bc68">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::AANoCaptureImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a9e78a16876b18d86097c67afa39bc090">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::checkUse</a>, <a href="#a5ddfc843195b9ecd7ffec8405c521396">createForPosition</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocapturecallsiteargument/#af8af50bbe36f25d0fd0d35c5d6e973fa">anonymous{AttributorAttributes.cpp}::AANoCaptureCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIdAddr() {#a14f5fe31282bd7c9faf0460d0195bedb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AANoCapture::getIdAddr ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a></p>

<p>Definition at line 4425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a8bb470ec04114d55381446066944b973">ID</a>.</p>

</div>
</div>

### getName() {#a80bc2955de89c92ba3584337f8133105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::AANoCapture::getName ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a></p>

<p>Definition at line 4422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isAssumedNoCapture() {#ae6a139955deae8f1ee31554caa8e1589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AANoCapture::isAssumedNoCapture ()</td>
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

<p>Return true if we assume that the underlying value is not captured in its respective scope.</p>

<p>Definition at line 4404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint16_t, 7, 0 &gt;::isAssumed</a> and <a href="#a0b4fb5399b000ba05e553a4d96305964a8464120a9bdc56bba45e3f099b783e93">NO_CAPTURE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#ab08fbb318e10194c1875082eb0c28e41">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getAsStr</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a051fd4ce3d6dd22954dc588c14b9ced1">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getDeducedAttributes</a>.</p>

</div>
</div>

### isAssumedNoCaptureMaybeReturned() {#ac17d753e610e5fa8be4fec8287d3e309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AANoCapture::isAssumedNoCaptureMaybeReturned ()</td>
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

<p>Return true if we assume that the underlying value is not captured in its respective scope but we allow it to escape through a "return".</p>

<p>Definition at line 4414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint16_t, 7, 0 &gt;::isAssumed</a> and <a href="#a0b4fb5399b000ba05e553a4d96305964a4f93ae6fded858c376d12d0d3e3a27e8">NO_CAPTURE_MAYBE_RETURNED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a9e78a16876b18d86097c67afa39bc090">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::checkUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#ab08fbb318e10194c1875082eb0c28e41">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a051fd4ce3d6dd22954dc588c14b9ced1">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliasreturned/#a58add1c5be55c8da55788e7cc412a877">anonymous{AttributorAttributes.cpp}::AANoAliasReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocapturecallsiteargument/#af8af50bbe36f25d0fd0d35c5d6e973fa">anonymous{AttributorAttributes.cpp}::AANoCaptureCallSiteArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>.</p>

</div>
</div>

### isKnownNoCapture() {#ad25601c85e7e4e805df4f29bbac93e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AANoCapture::isKnownNoCapture ()</td>
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

<p>Return true if we know that the underlying value is not captured in its respective scope.</p>

<p>Definition at line 4400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint16_t, 7, 0 &gt;::isKnown</a> and <a href="#a0b4fb5399b000ba05e553a4d96305964a8464120a9bdc56bba45e3f099b783e93">NO_CAPTURE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#ab08fbb318e10194c1875082eb0c28e41">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getAsStr</a>.</p>

</div>
</div>

### isKnownNoCaptureMaybeReturned() {#ad8a9bf8d9969c5ccbe446c698ee0f294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AANoCapture::isKnownNoCaptureMaybeReturned ()</td>
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

<p>Return true if we know that the underlying value is not captured in its respective scope but we allow it to escape through a "return".</p>

<p>Definition at line 4408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint16_t, 7, 0 &gt;::isKnown</a> and <a href="#a0b4fb5399b000ba05e553a4d96305964a4f93ae6fded858c376d12d0d3e3a27e8">NO_CAPTURE_MAYBE_RETURNED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#ab08fbb318e10194c1875082eb0c28e41">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getAsStr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad3b02641949e3535b987149182c901c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AANoCapture::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * AA)</td>
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

<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aanocapture">AANoCapture</a>.</p>

<p>Definition at line 4428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a8bb470ec04114d55381446066944b973">ID</a>.</p>

</div>
</div>

### createForPosition() {#a5ddfc843195b9ecd7ffec8405c521396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AANoCapture &amp; llvm::AANoCapture::createForPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>.</p>

<p>Definition at line 4419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a562d4a5f9290857ba956f97d33deff78">AANoCapture</a>.</p>

</div>
</div>

### determineFunctionCaptureCapabilities() {#af9efb4b2e9c757aaa9d2fada609eaee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AANoCapture::determineFunctionCaptureCapabilities (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a> &amp; State)</td>
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

<p>Update <span class="doxyComputerOutput">State</span> according to the capture capabilities of <span class="doxyComputerOutput">F</span> for position <span class="doxyComputerOutput">IRP</span>.</p>


<p>Set the NOT_CAPTURED_IN_MEM and NOT_CAPTURED_IN_RET bits in <span class="doxyComputerOutput">Known</span> depending on the ability of the function associated with <span class="doxyComputerOutput">IRP</span> to capture state in memory and through "returning/throwing", respectively.</p>


<p>Declaration at line 4370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 5776 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4930f70e8a125f3d0a45a777adc3b305">llvm::IRPosition::getCalleeArgNo</a>, <a href="#a0b4fb5399b000ba05e553a4d96305964a8464120a9bdc56bba45e3f099b783e93">NO_CAPTURE</a>, <a href="#a0b4fb5399b000ba05e553a4d96305964a886cd7d160324cd20be6c43de7d24d93">NOT_CAPTURED_IN_MEM</a> and <a href="#a0b4fb5399b000ba05e553a4d96305964a23b11d729b9274a206bf4e7a3e51482e">NOT_CAPTURED_IN_RET</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocapturecallsitereturned/#abf28dca4e7e8f438ff9600a463057881">anonymous{AttributorAttributes.cpp}::AANoCaptureCallSiteReturned::initialize</a> and <a href="#adb7886272a3ab071ecd4a576d865dc21">isImpliedByIR</a>.</p>

</div>
</div>

### isImpliedByIR() {#adb7886272a3ab071ecd4a576d865dc21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AANoCapture::isImpliedByIR (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> ImpliedAttributeKind, bool IgnoreSubsumingPositions=false)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/irattribute/#ac283e789a1c5ae7c595bdd1fde85cbaa">IRAttribute::isImpliedByIR</a>.</p>


<p>--------------------— Variable Capturing ------------------------------—</p>


<p>Declaration at line 4364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 5727 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a67ee5b213c199841ee5f2d0a338e466e">llvm::IRPosition::argument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af9efb4b2e9c757aaa9d2fada609eaee8">determineFunctionCaptureCapabilities</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a054de50dbf11b87063f6a32f3bccee80">llvm::IRPosition::getAssociatedFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aea16db681aa18f4eded0015e284fdfe5">llvm::IRPosition::getPositionKind</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a53f576f97e0dfa8314afb16bd74a76d0af5dba641c6a961375aee403f7cde7b31">llvm::IRPosition::IRP_CALL_SITE_ARGUMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aec15d884ee42b3559536c100446d54a7">llvm::IRPosition::isArgumentPosition</a>, <a href="#a0b4fb5399b000ba05e553a4d96305964a8464120a9bdc56bba45e3f099b783e93">NO_CAPTURE</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>

</div>
</div>

### isValidIRPositionForInit() {#a0639b327e46a46c804bc64ef0c12a7e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AANoCapture::isValidIRPositionForInit (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>.</p>

<p>Definition at line 4375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a8bb470ec04114d55381446066944b973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char AANoCapture::ID = 0</td>
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

<p>Unique ID (due to the unique address)</p>

<p>Definition at line 4433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#ad3b02641949e3535b987149182c901c1">classof</a>, <a href="#a14f5fe31282bd7c9faf0460d0195bedb">getIdAddr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a6c7a8371c75641e29a5259c131fd8408">runAttributorLightOnFunctions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
