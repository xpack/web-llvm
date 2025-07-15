---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-dlangdemangle-cpp-/demangler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Demangler` Struct Reference

<p>Demangle information structure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{DLangDemangle.cpp}::Demangler { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f75595aed256bafe1ddf8aa1afbb4c">Demangler</a> (std::string_view Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the information structure we use to pass around information. <a href="#a02f75595aed256bafe1ddf8aa1afbb4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1764c33072a40c40cc8c7c1e0e11c1ae">parseMangle</a> (OutputBuffer *Demangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle the mangled symbol and append it to the output string. <a href="#a1764c33072a40c40cc8c7c1e0e11c1ae">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee34f00434ffe02fe97b07dd48357f0">parseMangle</a> (OutputBuffer *Demangled, std::string_view &amp;Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle a given mangled symbol and append it to the output string. <a href="#a1ee34f00434ffe02fe97b07dd48357f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a74ff4043bfc5fb0bb9074e96e3c2aa">decodeNumber</a> (std::string_view &amp;Mangled, unsigned long &amp;Ret)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the number from a given string. <a href="#a5a74ff4043bfc5fb0bb9074e96e3c2aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade65df49919642697402baff96153216">decodeBackrefPos</a> (std::string_view &amp;Mangled, long &amp;Ret)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the back reference position from a given string. <a href="#ade65df49919642697402baff96153216">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ac358fa376b262f8d3e26752fe39af">decodeBackref</a> (std::string_view &amp;Mangled, std::string_view &amp;Ret)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the symbol pointed by the back reference form a given string. <a href="#a65ac358fa376b262f8d3e26752fe39af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00cb8a025556812b7051b12e02468f7">parseSymbolBackref</a> (OutputBuffer *Demangled, std::string_view &amp;Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle backreferenced symbol from a given mangled symbol and append it to the output string. <a href="#ae00cb8a025556812b7051b12e02468f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd8b2d6c29167b2def481bc397cbc29">parseTypeBackref</a> (std::string_view &amp;Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle backreferenced type from a given mangled symbol and append it to the output string. <a href="#a3fd8b2d6c29167b2def481bc397cbc29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04994d49f9e2ea2e08c0f7ecb6f0d8ba">isSymbolName</a> (std::string_view Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether it is the beginning of a symbol name. <a href="#a04994d49f9e2ea2e08c0f7ecb6f0d8ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9c1b5f47eb1b3c61a6480cfed957e1">parseIdentifier</a> (OutputBuffer *Demangled, std::string_view &amp;Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle an identifier from a given mangled symbol append it to the output string. <a href="#afe9c1b5f47eb1b3c61a6480cfed957e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7f6cb9238d505c37a179f0ab647ef26">parseLName</a> (OutputBuffer *Demangled, std::string_view &amp;Mangled, unsigned long Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle the plain identifier from a given mangled symbol and prepend/append it to the output string, with a special treatment for some magic compiler generated symbols. <a href="#ab7f6cb9238d505c37a179f0ab647ef26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd38d2b539b7be0e9f2a2ba8de28c5e">parseQualified</a> (OutputBuffer *Demangled, std::string_view &amp;Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle the qualified symbol from a given mangled symbol append it to the output string. <a href="#a9cd38d2b539b7be0e9f2a2ba8de28c5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4fea6a4cb4c4503791b450ac52ebb0d">parseType</a> (std::string_view &amp;Mangled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract and demangle a type from a given mangled symbol append it to the output string. <a href="#ae4fea6a4cb4c4503791b450ac52ebb0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab066da0afc3cd135453ffb9d5e1ee4f6">Str</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An immutable view of the string we are demangling. <a href="#ab066da0afc3cd135453ffb9d5e1ee4f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5b68ed927ebec7ce3cbedc89979665">LastBackref</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the last back reference. <a href="#a1e5b68ed927ebec7ce3cbedc89979665">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Demangle information structure.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Demangler() {#a02f75595aed256bafe1ddf8aa1afbb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Demangler::Demangler (std::string_view Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the information structure we use to pass around information.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>String to demangle.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseMangle() {#a1764c33072a40c40cc8c7c1e0e11c1ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * Demangler::parseMangle (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> * Demangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle the mangled symbol and append it to the output string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Demangled</td>
<td class="doxyParamItemDescription"><p>Output buffer to write the demangled name.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The remaining string on success or nullptr on failure.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#name_mangling">https://dlang.org/spec/abi.html#name_mangling</a> .</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#MangledName">https://dlang.org/spec/abi.html#MangledName</a> .</p></dd>
</dl>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>


<p>Reference <a href="#a1764c33072a40c40cc8c7c1e0e11c1ae">parseMangle</a>.</p>


<p>Referenced by <a href="#a1764c33072a40c40cc8c7c1e0e11c1ae">parseMangle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### decodeBackref() {#a65ac358fa376b262f8d3e26752fe39af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Demangler::decodeBackref (std::string_view &amp; Mangled, std::string_view &amp; Ret)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the symbol pointed by the back reference form a given string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>string to extract the back reference position.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ret</td>
<td class="doxyParamItemDescription"><p>assigned result value.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on success, false on error.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#back_ref">https://dlang.org/spec/abi.html#back_ref</a> .</p></dd>
</dl>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### decodeBackrefPos() {#ade65df49919642697402baff96153216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Demangler::decodeBackrefPos (std::string_view &amp; Mangled, long &amp; Ret)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the back reference position from a given string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>string to extract the back reference position.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ret</td>
<td class="doxyParamItemDescription"><p>assigned result value.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on success, false on error.</p></dd>
</dl>



:::info
<p>Ret is always &gt;= 0 on success, and unspecified on failure</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#back_ref">https://dlang.org/spec/abi.html#back_ref</a> .</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#NumberBackRef">https://dlang.org/spec/abi.html#NumberBackRef</a> .</p></dd>
</dl>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### decodeNumber() {#a5a74ff4043bfc5fb0bb9074e96e3c2aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::decodeNumber (std::string_view &amp; Mangled, unsigned long &amp; Ret)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the number from a given string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>string to extract the number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ret</td>
<td class="doxyParamItemDescription"><p>assigned result value.</p></td>
</tr>
</table>
</dd>
</dl>


:::info
<p>Ret larger than UINT_MAX is considered a failure.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#Number">https://dlang.org/spec/abi.html#Number</a> .</p></dd>
</dl>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### isSymbolName() {#a04994d49f9e2ea2e08c0f7ecb6f0d8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Demangler::isSymbolName (std::string_view Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether it is the beginning of a symbol name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>string to extract the symbol name.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on success, false otherwise.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#SymbolName">https://dlang.org/spec/abi.html#SymbolName</a> .</p></dd>
</dl>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### parseIdentifier() {#afe9c1b5f47eb1b3c61a6480cfed957e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::parseIdentifier (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> * Demangled, std::string_view &amp; Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle an identifier from a given mangled symbol append it to the output string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Demangled</td>
<td class="doxyParamItemDescription"><p>Output buffer to write the demangled name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>Mangled symbol to be demangled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#SymbolName">https://dlang.org/spec/abi.html#SymbolName</a> .</p></dd>
</dl>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### parseLName() {#ab7f6cb9238d505c37a179f0ab647ef26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::parseLName (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> * Demangled, std::string_view &amp; Mangled, unsigned long Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle the plain identifier from a given mangled symbol and prepend/append it to the output string, with a special treatment for some magic compiler generated symbols.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Demangled</td>
<td class="doxyParamItemDescription"><p>Output buffer to write the demangled name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>Mangled symbol to be demangled.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>Length of the mangled symbol name.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#LName">https://dlang.org/spec/abi.html#LName</a> .</p></dd>
</dl>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### parseMangle() {#a1ee34f00434ffe02fe97b07dd48357f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::parseMangle (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> * Demangled, std::string_view &amp; Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle a given mangled symbol and append it to the output string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Demangled</td>
<td class="doxyParamItemDescription"><p>output buffer to write the demangled name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>mangled symbol to be demangled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#name_mangling">https://dlang.org/spec/abi.html#name_mangling</a> .</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#MangledName">https://dlang.org/spec/abi.html#MangledName</a> .</p></dd>
</dl>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### parseQualified() {#a9cd38d2b539b7be0e9f2a2ba8de28c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::parseQualified (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> * Demangled, std::string_view &amp; Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle the qualified symbol from a given mangled symbol append it to the output string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Demangled</td>
<td class="doxyParamItemDescription"><p>Output buffer to write the demangled name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>Mangled symbol to be demangled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#QualifiedName">https://dlang.org/spec/abi.html#QualifiedName</a> .</p></dd>
</dl>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### parseSymbolBackref() {#ae00cb8a025556812b7051b12e02468f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::parseSymbolBackref (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> * Demangled, std::string_view &amp; Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle backreferenced symbol from a given mangled symbol and append it to the output string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Demangled</td>
<td class="doxyParamItemDescription"><p>output buffer to write the demangled name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>mangled symbol to be demangled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#back_ref">https://dlang.org/spec/abi.html#back_ref</a> .</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#IdentifierBackRef">https://dlang.org/spec/abi.html#IdentifierBackRef</a> .</p></dd>
</dl>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### parseType() {#ae4fea6a4cb4c4503791b450ac52ebb0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Demangler::parseType (std::string_view &amp; Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle a type from a given mangled symbol append it to the output string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>mangled symbol to be demangled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on success, false on error.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#Type">https://dlang.org/spec/abi.html#Type</a> .</p></dd>
</dl>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### parseTypeBackref() {#a3fd8b2d6c29167b2def481bc397cbc29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::parseTypeBackref (std::string_view &amp; Mangled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract and demangle backreferenced type from a given mangled symbol and append it to the output string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mangled</td>
<td class="doxyParamItemDescription"><p>mangled symbol to be demangled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#back_ref">https://dlang.org/spec/abi.html#back_ref</a> .</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="https://dlang.org/spec/abi.html#TypeBackRef">https://dlang.org/spec/abi.html#TypeBackRef</a> .</p></dd>
</dl>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LastBackref {#a1e5b68ed927ebec7ce3cbedc89979665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{DLangDemangle.cpp}::Demangler::LastBackref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the last back reference.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

### Str {#ab066da0afc3cd135453ffb9d5e1ee4f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string_view anonymous{DLangDemangle.cpp}::Demangler::Str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An immutable view of the string we are demangling.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/demangle/dlangdemangle-cpp">DLangDemangle.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
