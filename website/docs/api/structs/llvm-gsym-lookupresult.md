---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/lookupresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LookupResult` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::LookupResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">llvm/DebugInfo/GSYM/LookupResult.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf35524898c34b917e813177d64d735">getSourceFile</a> (uint32_t Index) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2d38a017ea83399938350483968ae1">LookupAddr</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The address that this lookup pertains to. <a href="#a2c2d38a017ea83399938350483968ae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addressrange">AddressRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aea1cf15f8a7f3f908ac755883139f3">FuncRange</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The concrete function address range. <a href="#a5aea1cf15f8a7f3f908ac755883139f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d91d0e18eade33e855b488992f550e">FuncName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The concrete function name that contains LookupAddr. <a href="#a75d91d0e18eade33e855b488992f550e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/gsym/#af56cdce2bbbfcdafb057bce7c90bf419">SourceLocations</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0145407164f660bd71c3189087006f">Locations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The source locations that match this address. <a href="#a8b0145407164f660bd71c3189087006f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e530bef09b9dc59f44888c60bdd82a0">CallSiteFuncRegex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> name regex patterns associated with a call site at the lookup address. <a href="#a5e530bef09b9dc59f44888c60bdd82a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getSourceFile() {#a4bf35524898c34b917e813177d64d735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LookupResult::getSourceFile (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/lookupresult-cpp">LookupResult.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a> and <a href="#a8b0145407164f660bd71c3189087006f">Locations</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CallSiteFuncRegex {#a5e530bef09b9dc59f44888c60bdd82a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StringRef&gt; llvm::gsym::LookupResult::CallSiteFuncRegex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> name regex patterns associated with a call site at the lookup address.</p>


<p>This vector will be populated when:</p>


<ol class="doxyList" type="1">
<li>The lookup address matches a call site's return address in a function</li>
<li>The call site has associated regex patterns that describe what functions can be called from that location</li>
</ol>

<p>The regex patterns can be used to validate function calls during runtime checking or symbolication. For example:</p>


<ul class="doxyList ">
<li>Patterns like "^foo$" indicate the call site can only call function "foo"</li>
<li>Patterns like "^std::" indicate the call site can call any function in the std namespace</li>
<li>Multiple patterns allow matching against a set of allowed functions</li>
</ul>

<p>The patterns are stored as string references into the GSYM string table. This information is typically loaded from:</p>


<ul class="doxyList ">
<li>DWARF debug info call site entries</li>
<li>External YAML files specifying call site patterns</li>
<li>Other debug info formats that encode call site constraints</li>
</ul>

<p>The patterns will be empty if:</p>


<ul class="doxyList ">
<li>The lookup address is not at the return address of a call site</li>
<li>The call site has no associated function name constraints</li>
<li>Call site info was not included when creating the GSYM file</li>
</ul>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a01f9d864a1818825ffb00bbfa4b846c6">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### FuncName {#a75d91d0e18eade33e855b488992f550e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::gsym::LookupResult::FuncName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The concrete function name that contains LookupAddr.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>.</p>

</div>
</div>

### FuncRange {#a5aea1cf15f8a7f3f908ac755883139f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressRange llvm::gsym::LookupResult::FuncRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The concrete function address range.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>.</p>

</div>
</div>

### Locations {#a8b0145407164f660bd71c3189087006f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceLocations llvm::gsym::LookupResult::Locations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The source locations that match this address.</p>


<p>This information will only be filled in if the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> contains a line table. If an address is for a concrete function with no inlined functions, this array will have one entry. If an address points to an inline function, there will be one <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation">SourceLocation</a> for each inlined function with the last entry pointing to the concrete function itself. This allows one address to generate multiple locations and allows unwinding of inline call stacks. The deepest inline function will appear at index zero in the source locations array, and the concrete function will appear at the end of the array.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="#a4bf35524898c34b917e813177d64d735">getSourceFile</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a01f9d864a1818825ffb00bbfa4b846c6">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### LookupAddr {#a2c2d38a017ea83399938350483968ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::LookupResult::LookupAddr = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The address that this lookup pertains to.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a01f9d864a1818825ffb00bbfa4b846c6">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/lookupresult-cpp">LookupResult.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
