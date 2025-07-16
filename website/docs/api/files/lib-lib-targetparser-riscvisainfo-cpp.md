---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/targetparser/riscvisainfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVISAInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">llvm/TargetParser/RISCVISAInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;array&gt;
#include &lt;atomic&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;vector&gt;
#include "llvm/TargetParser/RISCVTargetParserDef.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-riscvisainfo-cpp-">anonymous{RISCVISAInfo.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvisainfo-cpp-/riscvsupportedextension">RISCVSupportedExtension</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvisainfo-cpp-/riscvprofile">RISCVProfile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvisainfo-cpp-/lessextname">LessExtName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/impliedextsentry">ImpliedExtsEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/riscvextbit">RISCVExtBit</a></td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d1bad65ec5894aa23d613e18a08e55">operator&lt;</a> (const ImpliedExtsEntry &amp;LHS, StringRef RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d7707da1597a9f9abc9decfa84c241f">operator&lt;</a> (StringRef LHS, const ImpliedExtsEntry &amp;RHS)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0063780933c83ab9a27e63c51772154f">verifyTables</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eeb6ab7ee4a2fd19e22f671d7ce32b2">PrintExtension</a> (StringRef Name, StringRef Version, StringRef Description)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977bc5a442868c797e853e7c6bc0b57a">stripExperimentalPrefix</a> (StringRef &amp;Ext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dba4372ba2b0183b65fcce9e61ca7bc">findLastNonVersionCharacter</a> (StringRef Ext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensionversion">RISCVISAUtils::ExtensionVersion</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca5acfa0e6648c73a5143bfc0aa2ee1">findDefaultVersion</a> (StringRef ExtName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114eafe1ddec6413592fe4c273012b48">getExtensionTypeDesc</a> (StringRef Ext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f19444c5002f0f7c4572fcab85299c">getExtensionType</a> (StringRef Ext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensionversion">RISCVISAUtils::ExtensionVersion</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a744bc5d762669b40be5e20a99ea60b">isExperimentalExtension</a> (StringRef Ext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73113c3c3a7bfb64703238645f6fc1e">getError</a> (const Twine &amp;Message)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85dc884f90867e8bd3fc2f4839de6fdc">getErrorForInvalidExt</a> (StringRef ExtName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a> (StringRef Ext, StringRef In, unsigned &amp;Major, unsigned &amp;Minor, unsigned &amp;ConsumeLength, bool EnableExperimentalExtension, bool ExperimentalExtensionVersionCheck)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad075e23f07c31b7829101bee5f0efaf8">getIncompatibleError</a> (StringRef Ext1, StringRef Ext2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d0aa9264f643f6f62b28ee6216ac6b">getExtensionRequiresError</a> (StringRef Ext, StringRef ReqExt)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2828e79caa1587939e856e8f684a0a">RISCVGImplications</a>[] = {"i", "m", "a", "f", "d"}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235f429dc68b7d26558f6d62634e96c9">RISCVGImplicationsZi</a>[] = {"zicsr", "zifencei"}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9550f3327841ef7fa358ecd02113416b">CombineIntoExts</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/riscvextbit">RISCVExtBit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ef39ddb5fba5c251f3192de7caa9c2">RISCVBitPositions</a>[] = ...</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003843d09a365ffd0110948450e76343">GET_SUPPORTED_EXTENSIONS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29b7dc02483180596ba34bcdf42b67b">GET_SUPPORTED_PROFILES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3442f84ebb5367e6c24623e83dd268d7">GET_IMPLIED_EXTENSIONS</a></td>
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


<div class="doxySectionDef">

## Operators

### operator&lt;() {#aa5d1bad65ec5894aa23d613e18a08e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/impliedextsentry">ImpliedExtsEntry</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#a2d7707da1597a9f9abc9decfa84c241f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt; (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/impliedextsentry">ImpliedExtsEntry</a> &amp; RHS)</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### findDefaultVersion() {#a3ca5acfa0e6648c73a5143bfc0aa2ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; RISCVISAUtils::ExtensionVersion &gt; findDefaultVersion (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExtName)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>


<p>Referenced by <a href="#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>.</p>

</div>
</div>

### findLastNonVersionCharacter() {#a3dba4372ba2b0183b65fcce9e61ca7bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t findLastNonVersionCharacter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a24074750f6a79cbc564c654612b773ec">llvm::RISCVISAInfo::getTargetFeatureForExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#afcd8b4904b4e18e880c419386dfe4d85">llvm::RISCVISAInfo::isSupportedExtensionWithVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>.</p>

</div>
</div>

### getError() {#ad73113c3c3a7bfb64703238645f6fc1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error getError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>.</p>


<p>Referenced by <a href="#a85dc884f90867e8bd3fc2f4839de6fdc">getErrorForInvalidExt</a>, <a href="#a45d0aa9264f643f6f62b28ee6216ac6b">getExtensionRequiresError</a>, <a href="#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="#ad075e23f07c31b7829101bee5f0efaf8">getIncompatibleError</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>.</p>

</div>
</div>

### getErrorForInvalidExt() {#a85dc884f90867e8bd3fc2f4839de6fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error getErrorForInvalidExt (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExtName)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="#ad73113c3c3a7bfb64703238645f6fc1e">getError</a>, <a href="#a114eafe1ddec6413592fe4c273012b48">getExtensionTypeDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>.</p>

</div>
</div>

### getExtensionRequiresError() {#a45d0aa9264f643f6f62b28ee6216ac6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error getExtensionRequiresError (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ReqExt)</td>
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



<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Reference <a href="#ad73113c3c3a7bfb64703238645f6fc1e">getError</a>.</p>

</div>
</div>

### getExtensionType() {#a81f19444c5002f0f7c4572fcab85299c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getExtensionType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>.</p>

</div>
</div>

### getExtensionTypeDesc() {#a114eafe1ddec6413592fe4c273012b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getExtensionTypeDesc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Referenced by <a href="#a85dc884f90867e8bd3fc2f4839de6fdc">getErrorForInvalidExt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>.</p>

</div>
</div>

### getExtensionVersion() {#ac69e7d445bf4af727118416d0ea36250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error getExtensionVersion (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> In, unsigned &amp; Major, unsigned &amp; Minor, unsigned &amp; ConsumeLength, bool EnableExperimentalExtension, bool ExperimentalExtensionVersionCheck)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a3ca5acfa0e6648c73a5143bfc0aa2ee1">findDefaultVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="#ad73113c3c3a7bfb64703238645f6fc1e">getError</a>, <a href="#a85dc884f90867e8bd3fc2f4839de6fdc">getErrorForInvalidExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>, <a href="#a9a744bc5d762669b40be5e20a99ea60b">isExperimentalExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aafe02ccc1e3c410eac85a36f70878f18">llvm::RISCVISAInfo::isSupportedExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#afcd8b4904b4e18e880c419386dfe4d85">llvm::RISCVISAInfo::isSupportedExtensionWithVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>.</p>

</div>
</div>

### getIncompatibleError() {#ad075e23f07c31b7829101bee5f0efaf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error getIncompatibleError (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext1, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext2)</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Reference <a href="#ad73113c3c3a7bfb64703238645f6fc1e">getError</a>.</p>

</div>
</div>

### isExperimentalExtension() {#a9a744bc5d762669b40be5e20a99ea60b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; RISCVISAUtils::ExtensionVersion &gt; isExperimentalExtension (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>


<p>Referenced by <a href="#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a24074750f6a79cbc564c654612b773ec">llvm::RISCVISAInfo::getTargetFeatureForExtension</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#af4ef065f1b58988c5bb0b6ec76846366">llvm::RISCVISAInfo::toFeatures</a>.</p>

</div>
</div>

### PrintExtension() {#a9eeb6ab7ee4a2fd19e22f671d7ce32b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintExtension (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Version, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Description)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5b1b4e94f62050dd1bccb48141ef4b9">llvm::left_justify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ab74c03e7b0136fcbc7195e1243e7a401">llvm::RISCVISAInfo::printEnabledExtensions</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ac192fe2b2eb30e2900fb5a9277432f72">llvm::RISCVISAInfo::printSupportedExtensions</a>.</p>

</div>
</div>

### stripExperimentalPrefix() {#a977bc5a442868c797e853e7c6bc0b57a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool stripExperimentalPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Ext)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a34c522e755437c93c44bbd75b768b663">llvm::RISCVISAInfo::hasExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a06632f7f66681098316a7cbf42927d09">llvm::RISCVISAInfo::isSupportedExtensionFeature</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ac44851c2ceedf8a3136d31773e0f20e2">llvm::RISCVISAInfo::parseFeatures</a>.</p>

</div>
</div>

### verifyTables() {#a0063780933c83ab9a27e63c51772154f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void verifyTables ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CombineIntoExts {#a9550f3327841ef7fa358ecd02113416b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral CombineIntoExts[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {"zk"},    {"zkn"},  {"zks"},   {"zvkn"},  {"zvknc"},
    {"zvkng"}, {"zvks"}, {"zvksc"}, {"zvksg"},
}
</div>
</dd>
</dl>

<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

### RISCVBitPositions {#a71ef39ddb5fba5c251f3192de7caa9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVExtBit RISCVBitPositions[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {"a", 0, 0},          {"c", 0, 2},
    {"d", 0, 3},          {"f", 0, 5},
    {"i", 0, 8},          {"m", 0, 12},
    {"v", 0, 21},         {"zacas", 0, 26},
    {"zba", 0, 27},       {"zbb", 0, 28},
    {"zbc", 0, 29},       {"zbkb", 0, 30},
    {"zbkc", 0, 31},      {"zbkx", 0, 32},
    {"zbs", 0, 33},       {"zfa", 0, 34},
    {"zfh", 0, 35},       {"zfhmin", 0, 36},
    {"zicboz", 0, 37},    {"zicond", 0, 38},
    {"zihintntl", 0, 39}, {"zihintpause", 0, 40},
    {"zknd", 0, 41},      {"zkne", 0, 42},
    {"zknh", 0, 43},      {"zksed", 0, 44},
    {"zksh", 0, 45},      {"zkt", 0, 46},
    {"ztso", 0, 47},      {"zvbb", 0, 48},
    {"zvbc", 0, 49},      {"zvfh", 0, 50},
    {"zvfhmin", 0, 51},   {"zvkb", 0, 52},
    {"zvkg", 0, 53},      {"zvkned", 0, 54},
    {"zvknha", 0, 55},    {"zvknhb", 0, 56},
    {"zvksed", 0, 57},    {"zvksh", 0, 58},
    {"zvkt", 0, 59},      {"zve32x", 0, 60},
    {"zve32f", 0, 61},    {"zve64x", 0, 62},
    {"zve64f", 0, 63},    {"zve64d", 1, 0},
    {"zimop", 1, 1},      {"zca", 1, 2},
    {"zcb", 1, 3},        {"zcd", 1, 4},
    {"zcf", 1, 5},        {"zcmop", 1, 6},
    {"zawrs", 1, 7}}
</div>
</dd>
</dl>

<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ad5a40242a319096c3a2f6b36801d9774">llvm::RISCVISAInfo::getRISCVFeaturesBitsInfo</a>.</p>

</div>
</div>

### RISCVGImplications {#aec2828e79caa1587939e856e8f684a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* RISCVGImplications[] = {"i", "m", "a", "f", "d"}</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>.</p>

</div>
</div>

### RISCVGImplicationsZi {#a235f429dc68b7d26558f6d62634e96c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* RISCVGImplicationsZi[] = {"zicsr", "zifencei"}</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### GET\_IMPLIED\_EXTENSIONS {#a3442f84ebb5367e6c24623e83dd268d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_IMPLIED_EXTENSIONS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

### GET\_SUPPORTED\_EXTENSIONS {#a003843d09a365ffd0110948450e76343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUPPORTED_EXTENSIONS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

### GET\_SUPPORTED\_PROFILES {#ae29b7dc02483180596ba34bcdf42b67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUPPORTED_PROFILES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
