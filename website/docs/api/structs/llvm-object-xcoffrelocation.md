---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/xcoffrelocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `XCOFFRelocation` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename AddressType&gt;
struct llvm::object::XCOFFRelocation&lt;AddressType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">llvm/Object/XCOFFObjectFile.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AddressType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af06e0a51137d2c98bd0e51566bd916f1">isRelocationSigned</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AddressType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a167d10a9af44b34748f357ae382a9d07">isFixupIndicated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AddressType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7628f9e0b10c3a71a88985030168481">getRelocatedLength</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AddressType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">AddressType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14314e546bfd49062e351b17e4d0964c">VirtualAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AddressType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a9351dc9ad74cfe9ab63829d6926db48c">support::ubig32_t</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7098c4b5d19f2fcb1a8a357db179ced">SymbolIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AddressType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af2161c34a6ba00c88f45c13215cf533a">Info</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AddressType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8a">XCOFF::RelocationType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09836107610612ad814c660e3415f9d6">Type</a></td>
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


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getRelocatedLength() {#ac7628f9e0b10c3a71a88985030168481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AddressType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::XCOFFRelocation&lt; AddressType &gt;::getRelocatedLength ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#af2161c34a6ba00c88f45c13215cf533a">llvm::object::XCOFFRelocation&lt; AddressType &gt;::Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0709edaad1f22f3b77a92004c31de7ac">llvm::XCOFF::XR_BIASED_LENGTH_MASK</a>.</p>

</div>
</div>

### isFixupIndicated() {#a167d10a9af44b34748f357ae382a9d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AddressType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFRelocation&lt; AddressType &gt;::isFixupIndicated ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#af2161c34a6ba00c88f45c13215cf533a">llvm::object::XCOFFRelocation&lt; AddressType &gt;::Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a27ca5b303eeec633f293f39e77aabdc6">llvm::XCOFF::XR_FIXUP_INDICATOR_MASK</a>.</p>

</div>
</div>

### isRelocationSigned() {#af06e0a51137d2c98bd0e51566bd916f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AddressType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFRelocation&lt; AddressType &gt;::isRelocationSigned ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#af2161c34a6ba00c88f45c13215cf533a">llvm::object::XCOFFRelocation&lt; AddressType &gt;::Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a4291ff459e43ef7efd865792a0ca68a3">llvm::XCOFF::XR_SIGN_INDICATOR_MASK</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Info {#af2161c34a6ba00c88f45c13215cf533a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AddressType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::XCOFFRelocation&lt; AddressType &gt;::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Referenced by <a href="#ac7628f9e0b10c3a71a88985030168481">llvm::object::XCOFFRelocation&lt; AddressType &gt;::getRelocatedLength</a>, <a href="#a167d10a9af44b34748f357ae382a9d07">llvm::object::XCOFFRelocation&lt; AddressType &gt;::isFixupIndicated</a> and <a href="#af06e0a51137d2c98bd0e51566bd916f1">llvm::object::XCOFFRelocation&lt; AddressType &gt;::isRelocationSigned</a>.</p>

</div>
</div>

### SymbolIndex {#ac7098c4b5d19f2fcb1a8a357db179ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AddressType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ubig32_t llvm::object::XCOFFRelocation&lt; AddressType &gt;::SymbolIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### Type {#a09836107610612ad814c660e3415f9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AddressType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::RelocationType llvm::object::XCOFFRelocation&lt; AddressType &gt;::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### VirtualAddress {#a14314e546bfd49062e351b17e4d0964c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AddressType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressType llvm::object::XCOFFRelocation&lt; AddressType &gt;::VirtualAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
