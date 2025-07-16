---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-pass-cpp-/getcfgonlypasses
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GetCFGOnlyPasses` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{Pass.cpp}::GetCFGOnlyPasses { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener">PassRegistrationListener</a> class - This class is meant to be derived from by clients that are interested in which passes get registered and unregistered at runtime (which can be because of the <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a> constructors being run as the program starts up, or may be because a shared object just got loaded). <a href="/web-llvm/docs/api/structs/llvm/passregistrationlistener/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c5cbf5e28621fceecd034eba43c0bf">VectorType</a> = <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#aca5945c84f7ab80d6fb87b09c633aff9">AnalysisUsage::VectorType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace634b316930b3a8b0d57576362ffe50">GetCFGOnlyPasses</a> (VectorType &amp;L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59b3f459b2e549e9f5e107c32ef7479">passEnumerate</a> (const PassInfo *P) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>passEnumerate - Callback function invoked when someone calls enumeratePasses on this PassRegistrationListener object. <a href="#ae59b3f459b2e549e9f5e107c32ef7479">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae5c5cbf5e28621fceecd034eba43c0bf">VectorType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cde1e2c659f28019892e7b5b828fb44">CFGOnlyList</a></td>
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


<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/pass-cpp">Pass.cpp</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### VectorType {#ae5c5cbf5e28621fceecd034eba43c0bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{Pass.cpp}::GetCFGOnlyPasses::VectorType =  AnalysisUsage::VectorType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file Pass.cpp, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GetCFGOnlyPasses() {#ace634b316930b3a8b0d57576362ffe50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{Pass.cpp}::GetCFGOnlyPasses::GetCFGOnlyPasses (<a href="#ae5c5cbf5e28621fceecd034eba43c0bf">VectorType</a> &amp; L)</td>
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



<p>Declaration at line 238 of file Pass.cpp, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### passEnumerate() {#ae59b3f459b2e549e9f5e107c32ef7479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{Pass.cpp}::GetCFGOnlyPasses::passEnumerate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *)</td>
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

<p>passEnumerate - Callback function invoked when someone calls enumeratePasses on this PassRegistrationListener object.</p>

<p>Declaration at line 240 of file Pass.cpp, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CFGOnlyList {#a9cde1e2c659f28019892e7b5b828fb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType&amp; anonymous{Pass.cpp}::GetCFGOnlyPasses::CFGOnlyList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file Pass.cpp, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li>Pass.cpp</li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
