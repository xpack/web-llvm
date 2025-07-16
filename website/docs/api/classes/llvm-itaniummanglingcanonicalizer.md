---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/itaniummanglingcanonicalizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ItaniumManglingCanonicalizer` Class Reference

<p>Canonicalizer for mangled names. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ItaniumManglingCanonicalizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">llvm/ProfileData/ItaniumManglingCanonicalizer.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830634afc3321cbb695156f050d16d8c">Key</a> = uintptr_t</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EquivalenceError { <a href="#aafe55e9568e103b706b17e200b60255b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FragmentKind { <a href="#a0106d0d768f5ea4c92b0700fb2e01c46">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6961d7ccbe52d290462b070723b28d8a">ItaniumManglingCanonicalizer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917ac4484a427960b5215d3c75b49ce3">ItaniumManglingCanonicalizer</a> (const ItaniumManglingCanonicalizer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ea84e7b98a9369f8f698dfb13ab9eb">~ItaniumManglingCanonicalizer</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9120acda61fc5a4db6497f264b5a5776">operator=</a> (const ItaniumManglingCanonicalizer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafe55e9568e103b706b17e200b60255b">EquivalenceError</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad45212f80f0a702ccdf863f2b03227b9">addEquivalence</a> (FragmentKind Kind, StringRef First, StringRef Second)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an equivalence between <span class="doxyComputerOutput">First</span> and <span class="doxyComputerOutput">Second</span>. <a href="#ad45212f80f0a702ccdf863f2b03227b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a830634afc3321cbb695156f050d16d8c">Key</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a118854573d453cd9d48aa4d47d467846">canonicalize</a> (StringRef Mangling)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Form a canonical key for the specified mangling. <a href="#a118854573d453cd9d48aa4d47d467846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a830634afc3321cbb695156f050d16d8c">Key</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a2031331b5fe01f7aeea8ea89be858a">lookup</a> (StringRef Mangling)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a canonical key for the specified mangling, if one has already been formed. <a href="#a0a2031331b5fe01f7aeea8ea89be858a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/itaniummanglingcanonicalizer/impl">Impl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72bcf549166b99e8ae8936d3eeec4343">P</a></td>
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

<p>Canonicalizer for mangled names.</p>


<p>This class allows specifying a list of "equivalent" manglings. For example, you can specify that Ss is equivalent to NSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE and then manglings that refer to libstdc++'s 'std::string' will be considered equivalent to manglings that are the same except that they refer to libc++'s 'std::string'.</p>


<p>This can be used when data (eg, profiling data) is available for a version of a program built in a different configuration, with correspondingly different manglings.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Key {#a830634afc3321cbb695156f050d16d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ItaniumManglingCanonicalizer::Key =  uintptr_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### EquivalenceError {#aafe55e9568e103b706b17e200b60255b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ItaniumManglingCanonicalizer::EquivalenceError </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Success<a id="aafe55e9568e103b706b17e200b60255ba505a83f220c02df2f85c3810cd9ceb38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ManglingAlreadyUsed<a id="aafe55e9568e103b706b17e200b60255bacfbb79d82c398072421c3364c40689e3"></a></td>
<td class="doxyEnumItemDescription">Both the equivalent manglings have already been used as components of some other mangling we've looked at</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InvalidFirstMangling<a id="aafe55e9568e103b706b17e200b60255ba027afea6f0d52ef16c3ae4a0850794e4"></a></td>
<td class="doxyEnumItemDescription">The first equivalent mangling is invalid</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InvalidSecondMangling<a id="aafe55e9568e103b706b17e200b60255bab8e14fea99e484abef493123dea6d9cd"></a></td>
<td class="doxyEnumItemDescription">The second equivalent mangling is invalid</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>.</p>

</div>
</div>

### FragmentKind {#a0106d0d768f5ea4c92b0700fb2e01c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ItaniumManglingCanonicalizer::FragmentKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Name<a id="a0106d0d768f5ea4c92b0700fb2e01c46a49ee3087348e8d44e1feda1917443987"></a></td>
<td class="doxyEnumItemDescription">The mangling fragment is a &lt;name&gt; (or a predefined &lt;substitution&gt;)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Type<a id="a0106d0d768f5ea4c92b0700fb2e01c46aa1fa27779242b4902f7ae3bdd5c6d508"></a></td>
<td class="doxyEnumItemDescription">The mangling fragment is a &lt;type&gt;</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Encoding<a id="a0106d0d768f5ea4c92b0700fb2e01c46a169a6f6b44766410bffebf76ff3dcf17"></a></td>
<td class="doxyEnumItemDescription">The mangling fragment is an &lt;encoding&gt;</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ItaniumManglingCanonicalizer() {#a6961d7ccbe52d290462b070723b28d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumManglingCanonicalizer::ItaniumManglingCanonicalizer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>Referenced by <a href="#a917ac4484a427960b5215d3c75b49ce3">ItaniumManglingCanonicalizer</a> and <a href="#a9120acda61fc5a4db6497f264b5a5776">operator=</a>.</p>

</div>
</div>

### ItaniumManglingCanonicalizer() {#a917ac4484a427960b5215d3c75b49ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ItaniumManglingCanonicalizer::ItaniumManglingCanonicalizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/itaniummanglingcanonicalizer">ItaniumManglingCanonicalizer</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>.</p>


<p>Reference <a href="#a6961d7ccbe52d290462b070723b28d8a">ItaniumManglingCanonicalizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ItaniumManglingCanonicalizer() {#af9ea84e7b98a9369f8f698dfb13ab9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumManglingCanonicalizer::~ItaniumManglingCanonicalizer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9120acda61fc5a4db6497f264b5a5776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ItaniumManglingCanonicalizer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/itaniummanglingcanonicalizer">ItaniumManglingCanonicalizer</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>.</p>


<p>Reference <a href="#a6961d7ccbe52d290462b070723b28d8a">ItaniumManglingCanonicalizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEquivalence() {#ad45212f80f0a702ccdf863f2b03227b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumManglingCanonicalizer::EquivalenceError ItaniumManglingCanonicalizer::addEquivalence (<a href="#a0106d0d768f5ea4c92b0700fb2e01c46">FragmentKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> First, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Second)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an equivalence between <span class="doxyComputerOutput">First</span> and <span class="doxyComputerOutput">Second</span>.</p>


<p>Both manglings must live at least as long as the canonicalizer.</p>


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="#a0106d0d768f5ea4c92b0700fb2e01c46a169a6f6b44766410bffebf76ff3dcf17">Encoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#aafe55e9568e103b706b17e200b60255ba027afea6f0d52ef16c3ae4a0850794e4">InvalidFirstMangling</a>, <a href="#aafe55e9568e103b706b17e200b60255bab8e14fea99e484abef493123dea6d9cd">InvalidSecondMangling</a>, <a href="#aafe55e9568e103b706b17e200b60255bacfbb79d82c398072421c3364c40689e3">ManglingAlreadyUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0106d0d768f5ea4c92b0700fb2e01c46a49ee3087348e8d44e1feda1917443987">Name</a>, <a href="#aafe55e9568e103b706b17e200b60255ba505a83f220c02df2f85c3810cd9ceb38">Success</a> and <a href="#a0106d0d768f5ea4c92b0700fb2e01c46aa1fa27779242b4902f7ae3bdd5c6d508">Type</a>.</p>

</div>
</div>

### canonicalize() {#a118854573d453cd9d48aa4d47d467846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumManglingCanonicalizer::Key ItaniumManglingCanonicalizer::canonicalize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mangling)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Form a canonical key for the specified mangling.</p>


<p>They key will be the same for all equivalent manglings, and different for any two non-equivalent manglings, but is otherwise unspecified.</p>


<p>Returns <a href="#a830634afc3321cbb695156f050d16d8c">Key()</a> if (and only if) the mangling is not a valid Itanium C++ ABI mangling.</p>


<p>The string denoted by Mangling must live as long as the canonicalizer.</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>.</p>

</div>
</div>

### lookup() {#a0a2031331b5fe01f7aeea8ea89be858a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumManglingCanonicalizer::Key ItaniumManglingCanonicalizer::lookup (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mangling)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a canonical key for the specified mangling, if one has already been formed.</p>


<p>Otherwise returns <a href="#a830634afc3321cbb695156f050d16d8c">Key()</a>.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### P {#a72bcf549166b99e8ae8936d3eeec4343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Impl* llvm::ItaniumManglingCanonicalizer::P</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/itaniummanglingcanonicalizer-h">ItaniumManglingCanonicalizer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
