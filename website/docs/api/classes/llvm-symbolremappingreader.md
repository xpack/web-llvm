---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolremappingreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolRemappingReader` Class Reference

<p>Reader for symbol remapping files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SymbolRemappingReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">llvm/ProfileData/SymbolRemappingReader.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927d799644c7df94d198980a02abcc14">Key</a> = uintptr_t</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="#a927d799644c7df94d198980a02abcc14">Key</a> represents an equivalence class of symbol names. <a href="#a927d799644c7df94d198980a02abcc14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b15e282ce11e66f93f7b1a22407547b">read</a> (MemoryBuffer &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read remappings from the given buffer, which must live as long as the remapper. <a href="#a6b15e282ce11e66f93f7b1a22407547b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a927d799644c7df94d198980a02abcc14">Key</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3924a053395823fb4030c3a9d237d015">insert</a> (StringRef FunctionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a key for the given symbol, or return an existing one if an equivalent name has already been inserted. <a href="#a3924a053395823fb4030c3a9d237d015">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a927d799644c7df94d198980a02abcc14">Key</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d84dad093a98d74c5d5c0e4821815c">lookup</a> (StringRef FunctionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map the given symbol name into the key for the corresponding equivalence class. <a href="#a44d84dad093a98d74c5d5c0e4821815c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/itaniummanglingcanonicalizer">ItaniumManglingCanonicalizer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f899ed42a83452b30abd73da2d7dd3a">Canonicalizer</a></td>
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

<p>Reader for symbol remapping files.</p>


<p>Remaps the symbol names in profile data to match those in the program according to a set of rules specified in a given file.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">SymbolRemappingReader.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Key {#a927d799644c7df94d198980a02abcc14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SymbolRemappingReader::Key =  uintptr_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="#a927d799644c7df94d198980a02abcc14">Key</a> represents an equivalence class of symbol names.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">SymbolRemappingReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### insert() {#a3924a053395823fb4030c3a9d237d015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Key llvm::SymbolRemappingReader::insert (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FunctionName)</td>
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

<p>Construct a key for the given symbol, or return an existing one if an equivalent name has already been inserted.</p>


<p>The symbol name must live as long as the remapper.</p>


<p>The result will be <a href="#a927d799644c7df94d198980a02abcc14">Key()</a> if the name cannot be remapped (typically because it is not a valid mangled name).</p>


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">SymbolRemappingReader.h</a>.</p>

</div>
</div>

### lookup() {#a44d84dad093a98d74c5d5c0e4821815c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Key llvm::SymbolRemappingReader::lookup (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FunctionName)</td>
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

<p>Map the given symbol name into the key for the corresponding equivalence class.</p>


<p>The result will typically be <a href="#a927d799644c7df94d198980a02abcc14">Key()</a> if no equivalent symbol has been inserted, but this is not guaranteed: a <a href="#a927d799644c7df94d198980a02abcc14">Key</a> different from all keys ever returned by <span class="doxyComputerOutput">insert</span> may be returned instead.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">SymbolRemappingReader.h</a>.</p>

</div>
</div>

### read() {#a6b15e282ce11e66f93f7b1a22407547b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SymbolRemappingReader::read (<a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read remappings from the given buffer, which must live as long as the remapper.</p>


<p>Load a set of name remappings from a text file.</p>


<p>See the documentation at the top of the file for an explanation of the expected format.</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">SymbolRemappingReader.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/symbolremappingreader-cpp">SymbolRemappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a617941704a472090ba3304c9daf1c37f">llvm::line_iterator::is_at_eof</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a51eb9a429555dd682d9b265cff7f869f">llvm::line_iterator::line_number</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Canonicalizer {#a3f899ed42a83452b30abd73da2d7dd3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItaniumManglingCanonicalizer llvm::SymbolRemappingReader::Canonicalizer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">SymbolRemappingReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/symbolremappingreader-h">SymbolRemappingReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/symbolremappingreader-cpp">SymbolRemappingReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
