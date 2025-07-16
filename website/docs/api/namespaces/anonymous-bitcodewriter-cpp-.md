---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-bitcodewriter-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{BitcodeWriter.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{BitcodeWriter.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase">BitcodeWriterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class to manage the bitcode writing, subclassed for each bitcode file type. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase">ModuleBitcodeWriterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class to manage the module bitcode writing, currently subclassed for <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a>. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a module. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter">IndexBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a combined index. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a thin link bitcode file. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a077be6494d3f8a3512b3bb1503b8a049">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are manifest constants used by the bitcode writer. <a href="#a077be6494d3f8a3512b3bb1503b8a049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a077be6494d3f8a3512b3bb1503b8a049}

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

<p>These are manifest constants used by the bitcode writer.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_ENTRY_8_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049ab36acd6378d77b2f109e14b97b0f019c"></a></td>
<td class="doxyEnumItemDescription"> (= bitc::FIRST_APPLICATION_ABBREV)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_ENTRY_7_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049adb7ee3f02052ca12237e6fa5ff373819"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_ENTRY_6_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049af6daf204701e6ffb9bd97bd82c4cd120"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_BBENTRY_6_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049a1533cec62309bb1df0064a62c0b0e4a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_SETTYPE_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049abbc28cc9acd9908cb8d5d84c6cb973bb"></a></td>
<td class="doxyEnumItemDescription"> (= bitc::FIRST_APPLICATION_ABBREV)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_INTEGER_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049a86e371ca7ce2470cfd2e66d9dfb33193"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_CE_CAST_Abbrev<a id="a077be6494d3f8a3512b3bb1503b8a049a6a1ec59918427d2b04be3652501269a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_NULL_Abbrev<a id="a077be6494d3f8a3512b3bb1503b8a049a59e0ff93e366d44b02cda7a18b9d6bc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_LOAD_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049abf8d6451510d55ea0ad88c779f267a73"></a></td>
<td class="doxyEnumItemDescription"> (= bitc::FIRST_APPLICATION_ABBREV)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_UNOP_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049a550113a914e526368d8a8dffbafbad56"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_UNOP_FLAGS_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049a077d4ea88c7b92c094fb5d8233c73cb2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_BINOP_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049a87bd535bcd7300aa81090617ffb34acc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_BINOP_FLAGS_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049ac532429d0887aef8f3b4aad8e742be75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_CAST_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049abfaabe62f3666d52aa5400b599fe1891"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_CAST_FLAGS_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049acca0b3190cf1030abb8bf58b755d8390"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_RET_VOID_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049ac8526d9e2caeb051e9cab7f237898669"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_RET_VAL_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049a1484d19ff82543cbae634727c42fca3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_UNREACHABLE_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049ac9fde7b67527ffa0318e6de06572cca9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_GEP_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049a983a7a1e3f3a06f60d6679c0619fcf36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_DEBUG_RECORD_VALUE_ABBREV<a id="a077be6494d3f8a3512b3bb1503b8a049aa785d5744ba960381b977854faab7c65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>They do not need to be kept in sync with the reader, but need to be consistent within this file.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
