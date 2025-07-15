---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ThreadUnsafeDWARFContextState` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate">DWARFContextState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate">DWARFContextState</a> This structure contains all member variables for <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> that need to be protected in multi-threaded environments. <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate">ThreadSafeState</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec1a114492047a6d129804286951299f">ThreadUnsafeDWARFContextState</a> (DWARFContext &amp;DC, std::string &amp;DWP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09d62c07974b0102948172e96282db8">getNormalUnits</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf5ad189d1366bf9cc1d4c2d6be644e">getDWOUnits</a> (bool Lazy) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04426759b3da000ac6978dfcc0058cd4">getDebugAbbrevDWO</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad032d08aafabfc5c58827536e0b8e3a4">getCUIndex</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2494f7af81f725a1ca1cd7bb3f2f0d">getTUIndex</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfgdbindex">DWARFGdbIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d54016517fbbd3c357911beafffa1ea">getGdbIndex</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a522f51507f18c0124fd84fd85b06de5a">getDebugAbbrev</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc">DWARFDebugLoc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4451ac5951510e536480746dfc6ab786">getDebugLoc</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges">DWARFDebugAranges</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd9cf37b2152d0cab243ae6c4596d9b">getDebugAranges</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3dd834ea74cf44bbf7c9b9c16f6e56">getLineTableForUnit</a> (DWARFUnit *U, function_ref&lt; void(Error)&gt; RecoverableErrorHandler) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac51a5bd8917ab80869b88b6c7f66edb0">clearLineTableForUnit</a> (DWARFUnit *U) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa31bee239029c3abc70cd0b480cbdfd">getDebugFrame</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759c4a9026418f467ca84e2b0009a1f0">getEHFrame</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbcc1d37b98896d500cde4b3f1c6347">getDebugMacinfo</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45411f4341761736a1ab3429e8574de">getDebugMacinfoDWO</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2d3dfbdcefba19d666d23c7c3821a9">getDebugMacro</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad95e134993054181567b6ad197eb9180">getDebugMacroDWO</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames">DWARFDebugNames</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be087659bb12b2862f4b1975bf021aa">getDebugNames</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44311fbd55fbc785d3bdcfa5b532d296">getAppleNames</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6e436a25f8fd3fae8c26d941c6971b">getAppleTypes</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96f19aab275174b4e2968ad2375cf540">getAppleNamespaces</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656b58e082a146fe210b1f7c7ae68ffa">getAppleObjC</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54233894e754c548da87c0d21d69003d">getDWOContext</a> (StringRef AbsolutePath) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21012c229d97fdcd8481ca9e479ff66a">isThreadSafe</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DWARFTypeUnit</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea1a54b67e0e6c65d256264f641074b">getNormalTypeUnitMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DWARFTypeUnit</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb3cbaac4be1438f7c692b0c0d8158f">getDWOTypeUnitMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DWARFTypeUnit</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5006d4434f7f94cd614d08034212a8">getTypeUnitMap</a> (bool IsDWO) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a206812bfdd7a5fb260b894fda93096fe">NormalUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DWARFTypeUnit</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1828f838dae777e648c76f0cf779cfda">NormalTypeUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889b0f4e7dfffaffeecabb7c45788a4f">CUIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfgdbindex">DWARFGdbIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00dfe86cd2a873b29cabdd3688c165ed">GdbIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f5b5c21d2dda889e6fbcfbf18dfbcf">TUIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0012f3822c3b9df88c681603e46b1cc9">Abbrev</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc">DWARFDebugLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c39446a79f4cc851d697949e42a33a">Loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges">DWARFDebugAranges</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972bf0af4afd692a62ec774623bc5311">Aranges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugline">DWARFDebugLine</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8026a828e6e2df8f797a05c5f49c92e1">Line</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83eaeaa018e3b70e469eaf09bc2db5b">DebugFrame</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ce392c09ce5aaada6524f6589a63318">EHFrame</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a140371843243477f7f124ecfba8ad96f">Macro</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad929514e15cac0d67be5dfa7a7741f">Macinfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames">DWARFDebugNames</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab018c6dcf626f9640380610a9e883775">Names</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277a53cf365a13eb575b0763f29d2446">AppleNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab40ae32f2058b7cbb02bfd27e70657e">AppleTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70ab0b7c1b829ffa41874109ccb22e2">AppleNamespaces</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a70e13d8187303724bbc51f6cf5806">AppleObjC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4d9e24860ada149feceb86d3fff6fe">DWOUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DWARFTypeUnit</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55efc4f98571ee69d223cd45d2f2d032">DWOTypeUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96ea8e05b0ea5fd47b21fb1c83ff9b9">AbbrevDWO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5d6f03012385429034eb1682546dcc">MacinfoDWO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1442135577f452de67de94b0c4cd27a4">MacroDWO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::weak_ptr&lt; DWOFile &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9910b480c1c8f7784f1accdc5e838fc2">DWOFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::weak_ptr&lt; DWOFile &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c638f315fca48f21a72293b9341688">DWP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6ced08def6db46851b987f7001725f">CheckedForDWP</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d72c4d7f5daa71a19921960a564c0ac">DWPName</a></td>
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


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThreadUnsafeDWARFContextState() {#aec1a114492047a6d129804286951299f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::ThreadUnsafeDWARFContextState (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; DC, std::string &amp; DWP)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a9f94073361ae730535f2c039acdaf966">llvm::DWARFContext::DWARFContextState::DWARFContextState</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a4773c21f1df830fd7ddbea0cfb0e0cf1">anonymous{DWARFContext.cpp}::ThreadSafeState::ThreadSafeState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearLineTableForUnit() {#ac51a5bd8917ab80869b88b6c7f66edb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::clearLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a966c7097853fffeaf2746f5d58861f36">llvm::dwarf::toSectionOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a3cff273d8f3732631e66f8182a1347e0">anonymous{DWARFContext.cpp}::ThreadSafeState::clearLineTableForUnit</a>.</p>

</div>
</div>

### getAppleNames() {#a44311fbd55fbc785d3bdcfa5b532d296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleNames ()</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ab030efd905f06c216a1ab39286079498">getAccelTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a9635bb2d0bfe633129229d2208ec5073">llvm::DWARFObject::getAppleNamesSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afa1fd4842364f0c95e87d1968a4885fb">llvm::DWARFObject::getStrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a27c941abc93fe2a1b912edca262a6961">anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleNames</a>.</p>

</div>
</div>

### getAppleNamespaces() {#a96f19aab275174b4e2968ad2375cf540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleNamespaces ()</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ab030efd905f06c216a1ab39286079498">getAccelTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a39089ba1b0cecc6a69b6cddfc7562c31">llvm::DWARFObject::getAppleNamespacesSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afa1fd4842364f0c95e87d1968a4885fb">llvm::DWARFObject::getStrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#ac23eba14c19e460f03efe600a9061468">anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleNamespaces</a>.</p>

</div>
</div>

### getAppleObjC() {#a656b58e082a146fe210b1f7c7ae68ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleObjC ()</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ab030efd905f06c216a1ab39286079498">getAccelTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#ad5ce3bbfd24c7709b4a295237ce0e4af">llvm::DWARFObject::getAppleObjCSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afa1fd4842364f0c95e87d1968a4885fb">llvm::DWARFObject::getStrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a1a5fc38f8e6df2cedfebcfd8fd67bae2">anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleObjC</a>.</p>

</div>
</div>

### getAppleTypes() {#abb6e436a25f8fd3fae8c26d941c6971b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleTypes ()</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ab030efd905f06c216a1ab39286079498">getAccelTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a744f18e3f8a53ae99e2f408ac32fd949">llvm::DWARFObject::getAppleTypesSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afa1fd4842364f0c95e87d1968a4885fb">llvm::DWARFObject::getStrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a96aa31f1a1b3aed5d54e2c6741d6d7ed">anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleTypes</a>.</p>

</div>
</div>

### getCUIndex() {#ad032d08aafabfc5c58827536e0b8e3a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitIndex &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getCUIndex ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a88c5d7cb09ca2f6aaa6e12d91a3edeb7">fixupIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#ac60856f18883bf7af90ef318cf98b76a">anonymous{DWARFContext.cpp}::ThreadSafeState::getCUIndex</a>.</p>

</div>
</div>

### getDebugAbbrev() {#a522f51507f18c0124fd84fd85b06de5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAbbrev * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugAbbrev ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a937cea8ab92f207be8373537f9317b67">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugAbbrev</a>.</p>

</div>
</div>

### getDebugAbbrevDWO() {#a04426759b3da000ac6978dfcc0058cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAbbrev * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugAbbrevDWO ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a25f76b12c29c25b6be56a6053fa97205">llvm::DWARFObject::getAbbrevDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#aaffc663a86009125fcbafd62ddc2072c">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugAbbrevDWO</a>.</p>

</div>
</div>

### getDebugAranges() {#a6fd9cf37b2152d0cab243ae6c4596d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAranges * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugAranges ()</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a5c69465a34b32fb3f2d8e867b4cd71ca">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugAranges</a>.</p>

</div>
</div>

### getDebugFrame() {#afa31bee239029c3abc70cd0b480cbdfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugFrame * &gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugFrame ()</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#affecf20a5e4d1351ace92b2b76f8c8b7">llvm::DWARFObject::getAddressSize</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a28c711b52cb292791c9da24c5144dc79">llvm::DWARFObject::getFrameSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a270895457422212c73ce2dd71c8b6f6f">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugFrame</a>.</p>

</div>
</div>

### getDebugLoc() {#a4451ac5951510e536480746dfc6ab786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugLoc * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugLoc ()</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#ace84237f5d179253e3d0a958738f3dd9">llvm::DWARFObject::getLocSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a29d7d35d3b873bf10dca52b79844f6ec">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugLoc</a>.</p>

</div>
</div>

### getDebugMacinfo() {#a8bbcc1d37b98896d500cde4b3f1c6347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacinfo ()</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a36cd424a6641c094af13fc844d07a78ca226929e23aa0f08e529000fd37c0e975">llvm::DWARFContext::DWARFContextState::MacinfoSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a9850096a3506dc230ac4cdd1381821ec">llvm::DWARFContext::DWARFContextState::parseMacroOrMacinfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a24582ff542501a5b963de55526c9a9a2">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacinfo</a>.</p>

</div>
</div>

### getDebugMacinfoDWO() {#aa45411f4341761736a1ab3429e8574de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacinfoDWO ()</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a36cd424a6641c094af13fc844d07a78ca0e130fe3747429bf158129ead54e9eaf">llvm::DWARFContext::DWARFContextState::MacinfoDwoSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a9850096a3506dc230ac4cdd1381821ec">llvm::DWARFContext::DWARFContextState::parseMacroOrMacinfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#af8b6b1a03679be0e3f1b492bd26df233">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacinfoDWO</a>.</p>

</div>
</div>

### getDebugMacro() {#a7f2d3dfbdcefba19d666d23c7c3821a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacro ()</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a36cd424a6641c094af13fc844d07a78ca69ed45f06b0cd40a673664353c03193a">llvm::DWARFContext::DWARFContextState::MacroSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a9850096a3506dc230ac4cdd1381821ec">llvm::DWARFContext::DWARFContextState::parseMacroOrMacinfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a0cf7b0f880434a07fa31ad5b2edb05c1">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacro</a>.</p>

</div>
</div>

### getDebugMacroDWO() {#ad95e134993054181567b6ad197eb9180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacroDWO ()</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a36cd424a6641c094af13fc844d07a78ca9b221219c7ba7b9a03ba9a9168f91042">llvm::DWARFContext::DWARFContextState::MacroDwoSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a9850096a3506dc230ac4cdd1381821ec">llvm::DWARFContext::DWARFContextState::parseMacroOrMacinfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#af03cf10aa9dad2d0da6e15ddeb56be85">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacroDWO</a>.</p>

</div>
</div>

### getDebugNames() {#a4be087659bb12b2862f4b1975bf021aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugNames &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugNames ()</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ab030efd905f06c216a1ab39286079498">getAccelTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a35091ec9b4d81d8aec952d5e2eb6b159">llvm::DWARFObject::getNamesSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afa1fd4842364f0c95e87d1968a4885fb">llvm::DWARFObject::getStrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a0be279b1818d10f7cf968a221b77d33c">anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugNames</a>.</p>

</div>
</div>

### getDWOContext() {#a54233894e754c548da87c0d21d69003d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt; DWARFContext &gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AbsolutePath)</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ad6f9fa82bb8b6a5dae98b9d9d346d913">llvm::DWARFContext::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#aa125c88f5418a9e78bd9f1f20b774b08">llvm::WithColor::defaultErrorHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">llvm::WithColor::defaultWarningHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a15d7005fd6f90e6e9415f68094b43542">llvm::DWARFObject::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a6fbfbccaef05e07b2b1615224d5e20bdafd038fc7f319e48f3115d92bf5bdbef9">llvm::DWARFContext::Ignore</a>, <a href="#a21012c229d97fdcd8481ca9e479ff66a">isThreadSafe</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a7ac644d0d9a801eda9c691229f4b19c5">anonymous{DWARFContext.cpp}::ThreadSafeState::getDWOContext</a>.</p>

</div>
</div>

### getDWOTypeUnitMap() {#acfb3cbaac4be1438f7c692b0c0d8158f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt; uint64_t, DWARFTypeUnit * &gt; &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOTypeUnitMap ()</td>
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



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#aea5006d4434f7f94cd614d08034212a8">getTypeUnitMap</a>.</p>

</div>
</div>

### getDWOUnits() {#a2cf5ad189d1366bf9cc1d4c2d6be644e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitVector &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOUnits (bool Lazy)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52d529efd96454b48642563c5f78e242a635a63c1fbd498b75ee76603878154ca">llvm::DW_SECT_EXT_TYPES</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a733315e35580ca7f322216d7b2a405ee">llvm::DWARFObject::forEachInfoDWOSections</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#ae2f8b8150a7271c4c2af079c62bc28fa">llvm::DWARFObject::forEachTypesDWOSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#ad761a2b6ab159a6e4fb2db4a873cd296">anonymous{DWARFContext.cpp}::ThreadSafeState::getDWOUnits</a>.</p>

</div>
</div>

### getEHFrame() {#a759c4a9026418f467ca84e2b0009a1f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugFrame * &gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getEHFrame ()</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#affecf20a5e4d1351ace92b2b76f8c8b7">llvm::DWARFObject::getAddressSize</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a9a2b8ce873c8b5fac831e1eaba78913f">llvm::DWARFObject::getEHFrameSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#aeb3c7b81339ceddda135c50fc6f5cf26">anonymous{DWARFContext.cpp}::ThreadSafeState::getEHFrame</a>.</p>

</div>
</div>

### getGdbIndex() {#a7d54016517fbbd3c357911beafffa1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFGdbIndex &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getGdbIndex ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#acd511a6b37c049aa2528979d7af7194d">anonymous{DWARFContext.cpp}::ThreadSafeState::getGdbIndex</a>.</p>

</div>
</div>

### getLineTableForUnit() {#a7f3dd834ea74cf44bbf7c9b9c16f6e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugLine::LineTable * &gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a966c7097853fffeaf2746f5d58861f36">llvm::dwarf::toSectionOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#afa2f7e7368f8543ff89c16b88f280603">anonymous{DWARFContext.cpp}::ThreadSafeState::getLineTableForUnit</a>.</p>

</div>
</div>

### getNormalTypeUnitMap() {#a5ea1a54b67e0e6c65d256264f641074b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt; uint64_t, DWARFTypeUnit * &gt; &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getNormalTypeUnitMap ()</td>
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



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#aea5006d4434f7f94cd614d08034212a8">getTypeUnitMap</a>.</p>

</div>
</div>

### getNormalUnits() {#ad09d62c07974b0102948172e96282db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitVector &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getNormalUnits ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52d529efd96454b48642563c5f78e242a635a63c1fbd498b75ee76603878154ca">llvm::DW_SECT_EXT_TYPES</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a77a07541d39f2bbd17b86af2fad3d94d">llvm::DWARFObject::forEachInfoSections</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#aaffaa54a17cd523b80d37dd617e052bb">llvm::DWARFObject::forEachTypesSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a9a98c66372371312392e2e743e210484">anonymous{DWARFContext.cpp}::ThreadSafeState::getNormalUnits</a>.</p>

</div>
</div>

### getTUIndex() {#a5b2494f7af81f725a1ca1cd7bb3f2f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitIndex &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getTUIndex ()</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#ac4a1eacebeaa61791b61a29f64e499da">llvm::DWARFContext::DWARFContextState::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52d529efd96454b48642563c5f78e242a635a63c1fbd498b75ee76603878154ca">llvm::DW_SECT_EXT_TYPES</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a88c5d7cb09ca2f6aaa6e12d91a3edeb7">fixupIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a373675d7af9ec1b2312a6e9a13e02215">anonymous{DWARFContext.cpp}::ThreadSafeState::getTUIndex</a>.</p>

</div>
</div>

### getTypeUnitMap() {#aea5006d4434f7f94cd614d08034212a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt; uint64_t, DWARFTypeUnit * &gt; &amp; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getTypeUnitMap (bool IsDWO)</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="#acfb3cbaac4be1438f7c692b0c0d8158f">getDWOTypeUnitMap</a> and <a href="#a5ea1a54b67e0e6c65d256264f641074b">getNormalTypeUnitMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadsafestate/#a39b0b3332ae86991d319265f3e37947d">anonymous{DWARFContext.cpp}::ThreadSafeState::getTypeUnitMap</a>.</p>

</div>
</div>

### isThreadSafe() {#a21012c229d97fdcd8481ca9e479ff66a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::isThreadSafe ()</td>
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



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a54233894e754c548da87c0d21d69003d">getDWOContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Abbrev {#a0012f3822c3b9df88c681603e46b1cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugAbbrev&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::Abbrev</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### AbbrevDWO {#af96ea8e05b0ea5fd47b21fb1c83ff9b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugAbbrev&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::AbbrevDWO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### AppleNames {#a277a53cf365a13eb575b0763f29d2446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AppleAcceleratorTable&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::AppleNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### AppleNamespaces {#ab70ab0b7c1b829ffa41874109ccb22e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AppleAcceleratorTable&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::AppleNamespaces</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### AppleObjC {#a71a70e13d8187303724bbc51f6cf5806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AppleAcceleratorTable&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::AppleObjC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### AppleTypes {#aab40ae32f2058b7cbb02bfd27e70657e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AppleAcceleratorTable&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::AppleTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### Aranges {#a972bf0af4afd692a62ec774623bc5311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugAranges&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::Aranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### CheckedForDWP {#a6f6ced08def6db46851b987f7001725f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::CheckedForDWP = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### CUIndex {#a889b0f4e7dfffaffeecabb7c45788a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFUnitIndex&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::CUIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### DebugFrame {#ad83eaeaa018e3b70e469eaf09bc2db5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugFrame&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::DebugFrame</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### DWOFiles {#a9910b480c1c8f7784f1accdc5e838fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::weak_ptr&lt;DWOFile&gt; &gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::DWOFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### DWOTypeUnits {#a55efc4f98571ee69d223cd45d2f2d032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;DenseMap&lt;uint64_t, DWARFTypeUnit *&gt; &gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::DWOTypeUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### DWOUnits {#a1e4d9e24860ada149feceb86d3fff6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitVector anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::DWOUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### DWP {#aa4c638f315fca48f21a72293b9341688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::weak_ptr&lt;DWOFile&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::DWP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### DWPName {#a8d72c4d7f5daa71a19921960a564c0ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::DWPName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### EHFrame {#a5ce392c09ce5aaada6524f6589a63318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugFrame&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::EHFrame</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### GdbIndex {#a00dfe86cd2a873b29cabdd3688c165ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFGdbIndex&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::GdbIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### Line {#a8026a828e6e2df8f797a05c5f49c92e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugLine&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### Loc {#a58c39446a79f4cc851d697949e42a33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugLoc&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### Macinfo {#a6ad929514e15cac0d67be5dfa7a7741f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugMacro&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::Macinfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### MacinfoDWO {#aee5d6f03012385429034eb1682546dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugMacro&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::MacinfoDWO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### Macro {#a140371843243477f7f124ecfba8ad96f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugMacro&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::Macro</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### MacroDWO {#a1442135577f452de67de94b0c4cd27a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugMacro&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::MacroDWO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### Names {#ab018c6dcf626f9640380610a9e883775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFDebugNames&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::Names</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### NormalTypeUnits {#a1828f838dae777e648c76f0cf779cfda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;DenseMap&lt;uint64_t, DWARFTypeUnit *&gt; &gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::NormalTypeUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### NormalUnits {#a206812bfdd7a5fb260b894fda93096fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitVector anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::NormalUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### TUIndex {#a89f5b5c21d2dda889e6fbcfbf18dfbcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFUnitIndex&gt; anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::TUIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
