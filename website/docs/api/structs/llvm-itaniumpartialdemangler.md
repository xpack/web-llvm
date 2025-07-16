---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/itaniumpartialdemangler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ItaniumPartialDemangler` Struct Reference

<p>"Partial" demangler. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ItaniumPartialDemangler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">llvm/Demangle/Demangle.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc277b74c8ecf948b70a35b9901baeb7">ItaniumPartialDemangler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51bb4f2ef8151569828c7969f315baee">ItaniumPartialDemangler</a> (ItaniumPartialDemangler &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf11f9d944c474801ebf8c495abd64d">~ItaniumPartialDemangler</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler">ItaniumPartialDemangler</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6dbeb658a7eb20abfff23674a46a6a6">operator=</a> (ItaniumPartialDemangler &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4640950196e4ad668076b70aa142ab91">partialDemangle</a> (const char *MangledName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Demangle into an AST. <a href="#a4640950196e4ad668076b70aa142ab91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a735b9eda5aeca00a01465c6fddd48c72">finishDemangle</a> (char *Buf, size_t *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Just print the entire mangled name into Buf. <a href="#a735b9eda5aeca00a01465c6fddd48c72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2effd15853bfffbeec4d08451f1fa81c">getFunctionBaseName</a> (char *Buf, size_t *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the base name of a function. <a href="#a2effd15853bfffbeec4d08451f1fa81c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea51879b3b2822d1c0f74c71cff9bc2e">getFunctionDeclContextName</a> (char *Buf, size_t *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the context name for a function. <a href="#aea51879b3b2822d1c0f74c71cff9bc2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483d97b0a650319638b62209a03b1dea">getFunctionName</a> (char *Buf, size_t *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the entire name of this function. <a href="#a483d97b0a650319638b62209a03b1dea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d6bd09c85fc634502b4914843860a2">getFunctionParameters</a> (char *Buf, size_t *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parameters for this function. <a href="#a06d6bd09c85fc634502b4914843860a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb17886e8b7123e706c1a207402c179f">getFunctionReturnType</a> (char *Buf, size_t *N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61172626613e0d99b722a256e80cf7d8">hasFunctionQualifiers</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function has any cv or reference qualifiers. <a href="#a61172626613e0d99b722a256e80cf7d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2764e156977abc23c40ce1344427ed">isCtorOrDtor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this symbol describes a constructor or destructor. <a href="#adc2764e156977abc23c40ce1344427ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a155d3af87843268af33d983850fee">isFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this symbol describes a function. <a href="#a28a155d3af87843268af33d983850fee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef23df9c7fc8984bf27fe237a8358a0f">isData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this symbol describes a variable. <a href="#aef23df9c7fc8984bf27fe237a8358a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb99cf7917e8a1486764cd8d5114a96">isSpecialName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this symbol is a &lt;special-name&gt;. <a href="#a3eb99cf7917e8a1486764cd8d5114a96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1899600ffe5e8e3441acab36738b7a8">RootNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4f580e2c3e1db140126b9479d5da75">Context</a></td>
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

<p>"Partial" demangler.</p>


<p>This supports demangling a string into an AST (typically an intermediate stage in itaniumDemangle) and querying certain properties or partially printing the demangled name.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ItaniumPartialDemangler() {#abc277b74c8ecf948b70a35b9901baeb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumPartialDemangler::ItaniumPartialDemangler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Referenced by <a href="#a51bb4f2ef8151569828c7969f315baee">ItaniumPartialDemangler</a> and <a href="#ad6dbeb658a7eb20abfff23674a46a6a6">operator=</a>.</p>

</div>
</div>

### ItaniumPartialDemangler() {#a51bb4f2ef8151569828c7969f315baee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumPartialDemangler::ItaniumPartialDemangler (<a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler">ItaniumPartialDemangler</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#abc277b74c8ecf948b70a35b9901baeb7">ItaniumPartialDemangler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ItaniumPartialDemangler() {#addf11f9d944c474801ebf8c495abd64d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumPartialDemangler::~ItaniumPartialDemangler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ad6dbeb658a7eb20abfff23674a46a6a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumPartialDemangler &amp; ItaniumPartialDemangler::operator= (<a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler">ItaniumPartialDemangler</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#abc277b74c8ecf948b70a35b9901baeb7">ItaniumPartialDemangler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finishDemangle() {#a735b9eda5aeca00a01465c6fddd48c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * ItaniumPartialDemangler::finishDemangle (char * Buf, size_t * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Just print the entire mangled name into Buf.</p>


<p>Buf and N behave like the second and third parameters to __cxa_demangle.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#a43bfa5ae5bc262dd53cb668fa64764dc">printNode</a>.</p>

</div>
</div>

### getFunctionBaseName() {#a2effd15853bfffbeec4d08451f1fa81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * ItaniumPartialDemangler::getFunctionBaseName (char * Buf, size_t * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the base name of a function.</p>


<p>This doesn't include trailing template arguments, ie for "a::b&lt;int&gt;" this function returns "b".</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="#a28a155d3af87843268af33d983850fee">isFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#a43bfa5ae5bc262dd53cb668fa64764dc">printNode</a>.</p>

</div>
</div>

### getFunctionDeclContextName() {#aea51879b3b2822d1c0f74c71cff9bc2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * ItaniumPartialDemangler::getFunctionDeclContextName (char * Buf, size_t * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the context name for a function.</p>


<p>For "a::b::c", this function returns "a::b".</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/structs/localname/#a5f485fe5a03816fa136fae3845c199fc">LocalName::Encoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="#a28a155d3af87843268af33d983850fee">isFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/node/#a05779201e7fa0913e5b50fdbc5c49135">Node::print</a>.</p>

</div>
</div>

### getFunctionName() {#a483d97b0a650319638b62209a03b1dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * ItaniumPartialDemangler::getFunctionName (char * Buf, size_t * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the entire name of this function.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="#a28a155d3af87843268af33d983850fee">isFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#a43bfa5ae5bc262dd53cb668fa64764dc">printNode</a>.</p>

</div>
</div>

### getFunctionParameters() {#a06d6bd09c85fc634502b4914843860a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * ItaniumPartialDemangler::getFunctionParameters (char * Buf, size_t * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the parameters for this function.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#a28a155d3af87843268af33d983850fee">isFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/nodearray/#a743195b677aacb78f4556ffb2ce464aa">NodeArray::printWithComma</a>.</p>

</div>
</div>

### getFunctionReturnType() {#abb17886e8b7123e706c1a207402c179f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * ItaniumPartialDemangler::getFunctionReturnType (char * Buf, size_t * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#a28a155d3af87843268af33d983850fee">isFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### hasFunctionQualifiers() {#a61172626613e0d99b722a256e80cf7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ItaniumPartialDemangler::hasFunctionQualifiers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this function has any cv or reference qualifiers.</p>


<p>These imply that the function is a non-static member function.</p>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda74a742e365bc15a3ee3b9a2a4b0e79f3">FrefQualNone</a>, <a href="/web-llvm/docs/api/classes/functionencoding/#a131b1ac36d5deed3e1cdd32b8133052f">FunctionEncoding::getCVQuals</a>, <a href="#a28a155d3af87843268af33d983850fee">isFunction</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7adc7b331ccab83e31a327816731dc82f2">QualNone</a>.</p>

</div>
</div>

### isCtorOrDtor() {#adc2764e156977abc23c40ce1344427ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ItaniumPartialDemangler::isCtorOrDtor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this symbol describes a constructor or destructor.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isData() {#aef23df9c7fc8984bf27fe237a8358a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ItaniumPartialDemangler::isData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this symbol describes a variable.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>References <a href="#a28a155d3af87843268af33d983850fee">isFunction</a> and <a href="#a3eb99cf7917e8a1486764cd8d5114a96">isSpecialName</a>.</p>

</div>
</div>

### isFunction() {#a28a155d3af87843268af33d983850fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ItaniumPartialDemangler::isFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this symbol describes a function.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a2effd15853bfffbeec4d08451f1fa81c">getFunctionBaseName</a>, <a href="#aea51879b3b2822d1c0f74c71cff9bc2e">getFunctionDeclContextName</a>, <a href="#a483d97b0a650319638b62209a03b1dea">getFunctionName</a>, <a href="#a06d6bd09c85fc634502b4914843860a2">getFunctionParameters</a>, <a href="#abb17886e8b7123e706c1a207402c179f">getFunctionReturnType</a>, <a href="#a61172626613e0d99b722a256e80cf7d8">hasFunctionQualifiers</a> and <a href="#aef23df9c7fc8984bf27fe237a8358a0f">isData</a>.</p>

</div>
</div>

### isSpecialName() {#a3eb99cf7917e8a1486764cd8d5114a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ItaniumPartialDemangler::isSpecialName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this symbol is a &lt;special-name&gt;.</p>


<p>These are generally implicitly generated by the implementation, such as vtables and typeinfo names.</p>


<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#aef23df9c7fc8984bf27fe237a8358a0f">isData</a>.</p>

</div>
</div>

### partialDemangle() {#a4640950196e4ad668076b70aa142ab91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ItaniumPartialDemangler::partialDemangle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Demangle into an AST.</p>


<p>Subsequent calls to the rest of the member functions implicitly operate on the AST this produces.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on error, false otherwise</p></dd>
</dl>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Context {#aab4f580e2c3e1db140126b9479d5da75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::ItaniumPartialDemangler::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>.</p>

</div>
</div>

### RootNode {#ae1899600ffe5e8e3441acab36738b7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::ItaniumPartialDemangler::RootNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">Demangle.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp">ItaniumDemangle.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
