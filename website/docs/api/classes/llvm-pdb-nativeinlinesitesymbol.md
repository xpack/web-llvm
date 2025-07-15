---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativeinlinesitesymbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NativeInlineSiteSymbol` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeInlineSiteSymbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">llvm/DebugInfo/PDB/Native/NativeInlineSiteSymbol.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol">NativeRawSymbol</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84760bb2bdb4eb4bf9e2612086896d92">NativeInlineSiteSymbol</a> (NativeSession &amp;Session, SymIndexId Id, const codeview::InlineSiteSym &amp;Sym, uint64_t ParentAddr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe92e709ce019821c1df6d88ec9f0ba">~NativeInlineSiteSymbol</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad199735d010db77e62f5cf12f388b3e2">dump</a> (raw_ostream &amp;OS, int Indent, PdbSymbolIdField ShowIdFields, PdbSymbolIdField RecurseIdFields) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1db1fcd4aca7e9b22abd894f4716696">getName</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a217f1bfdff572ea30e762481e0049ebf">IPDBEnumLineNumbers</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2600af2572b1e6d73939dbb2c74e5822">findInlineeLinesByVA</a> (uint64_t VA, uint32_t Length) const override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda5f67f6acfc1a285a7ee176024b18f">getLineOffset</a> (uint32_t OffsetInFunc, uint32_t &amp;LineOffset, uint32_t &amp;FileOffset) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/inlinesitesym">codeview::InlineSiteSym</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8716630dae1858034ab758c14a8e79">Sym</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b645450d273620ad7bdc8fc0529b81">ParentAddr</a></td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NativeInlineSiteSymbol() {#a84760bb2bdb4eb4bf9e2612086896d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeInlineSiteSymbol::NativeInlineSiteSymbol (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/inlinesitesym">codeview::InlineSiteSym</a> &amp; Sym, uint64_t ParentAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp">NativeInlineSiteSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba44f5db7cd81aa82d512c75293c434b8b">llvm::pdb::InlineSite</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeInlineSiteSymbol() {#adbe92e709ce019821c1df6d88ec9f0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeInlineSiteSymbol::~NativeInlineSiteSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ad199735d010db77e62f5cf12f388b3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeInlineSiteSymbol::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowIdFields, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseIdFields)</td>
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



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp">NativeInlineSiteSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#aeeda1eb1da6fda8318d0a3093caa3ea2">llvm::pdb::NativeRawSymbol::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a> and <a href="#aa1db1fcd4aca7e9b22abd894f4716696">getName</a>.</p>

</div>
</div>

### findInlineeLinesByVA() {#a2600af2572b1e6d73939dbb2c74e5822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumLineNumbers &gt; NativeInlineSiteSymbol::findInlineeLinesByVA (uint64_t VA, uint32_t Length)</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp">NativeInlineSiteSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp/#ad619c46f308a2280d51080b4c0a40723">findInlineeByTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bac8f84e0707e79d30fc535a72b9f4d4d2">llvm::pdb::Inlinee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afaa0b0293a2db49f5f93c15a62e095c819">llvm::codeview::Lines</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getName() {#aa1db1fcd4aca7e9b22abd894f4716696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string NativeInlineSiteSymbol::getName ()</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp">NativeInlineSiteSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfuncidrecord/#a37bc1805db772bafc4c67eccb5df699c">llvm::codeview::MemberFuncIdRecord::getClassType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/funcidrecord/#afbcc54d9672a8361e2f08545a2e49e7b">llvm::codeview::FuncIdRecord::getParentScope</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection/#a4c9f32907d1d49ee8974b2f68ce2cdf6">llvm::codeview::LazyRandomTypeCollection::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection/#ab41c72c1487d92d9beb6b4bfd325b1b1">llvm::codeview::LazyRandomTypeCollection::getTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#acb1db28679177b959c08481c98cafa29">llvm::codeview::TypeIndex::isNoneType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aaeef9f2a2d0dc09ec00ec9b38242c706">llvm::codeview::CVRecord&lt; Kind &gt;::kind</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>.</p>


<p>Referenced by <a href="#ad199735d010db77e62f5cf12f388b3e2">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getLineOffset() {#afda5f67f6acfc1a285a7ee176024b18f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeInlineSiteSymbol::getLineOffset (uint32_t OffsetInFunc, uint32_t &amp; LineOffset, uint32_t &amp; FileOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp">NativeInlineSiteSymbol.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ParentAddr {#a99b645450d273620ad7bdc8fc0529b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::pdb::NativeInlineSiteSymbol::ParentAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>.</p>

</div>
</div>

### Sym {#a6a8716630dae1858034ab758c14a8e79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const codeview::InlineSiteSym llvm::pdb::NativeInlineSiteSymbol::Sym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">NativeInlineSiteSymbol.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp">NativeInlineSiteSymbol.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
