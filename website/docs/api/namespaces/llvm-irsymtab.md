---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/irsymtab
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `irsymtab` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::irsymtab { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/storage">storage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsymtab/symbol">Symbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a symbol that has been read from a <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol">storage::Symbol</a> and possibly a <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/uncommon">storage::Uncommon</a>. <a href="/web-llvm/docs/api/structs/llvm/irsymtab/symbol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader">Reader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class can be used to read a Symtab and Strtab produced by <a href="#a8af0e7caf92ff2e049dc40eceafc15be">irsymtab::build</a>. <a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsymtab/filecontents">FileContents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The contents of the irsymtab in a bitcode file. <a href="/web-llvm/docs/api/structs/llvm/irsymtab/filecontents/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8af0e7caf92ff2e049dc40eceafc15be">build</a> (ArrayRef&lt; Module * &gt; Mods, SmallVector&lt; char, 0 &gt; &amp;Symtab, StringTableBuilder &amp;StrtabBuilder, BumpPtrAllocator &amp;Alloc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fills in Symtab and StrtabBuilder with a valid symbol and string table for Mods. <a href="#a8af0e7caf92ff2e049dc40eceafc15be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsymtab/filecontents">FileContents</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d852659ea6c0a8e12cf0c8d5e8d2e16">readBitcode</a> (const BitcodeFileContents &amp;BFC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads the contents of a bitcode file, creating its irsymtab if necessary. <a href="#a7d852659ea6c0a8e12cf0c8d5e8d2e16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### build() {#a8af0e7caf92ff2e049dc40eceafc15be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::irsymtab::build (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * &gt; Mods, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 0 &gt; &amp; Symtab, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fills in Symtab and StrtabBuilder with a valid symbol and string table for Mods.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a> and <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a0e0c562a961438c5436a261418363e99">anonymous{IRSymtab.cpp}::Builder::Builder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter/#aaaca861df948bd93da0afb6891e9d662">llvm::BitcodeWriter::writeSymtab</a>.</p>

</div>
</div>

### readBitcode() {#a7d852659ea6c0a8e12cf0c8d5e8d2e16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; FileContents &gt; llvm::irsymtab::readBitcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bitcodefilecontents">BitcodeFileContents</a> &amp; BFC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads the contents of a bitcode file, creating its irsymtab if necessary.</p>

<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#aa5fada963c7ae3551af9b10456feed0a">DisableBitcodeVersionUpgrade</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a44972a05552d8f94667bb337d8a19d1da0adf4127f038b70609b3c0b176a3b4ee">llvm::irsymtab::storage::Header::kCurrentVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-irsymtab-cpp-/#a331976112aa5c16cfe46764bc97c0dfb">anonymous{IRSymtab.cpp}::kExpectedProducerName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/bitcodefilecontents/#a9f7b8378090f16464d9c5b8d0e6b1ae9">llvm::BitcodeFileContents::Mods</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/structs/llvm/bitcodefilecontents/#a7e8871abb4c99185981e4b2dd60a203a">llvm::BitcodeFileContents::StrtabForSymtab</a>, <a href="/web-llvm/docs/api/structs/llvm/bitcodefilecontents/#a87fd3c1677a59a7642d240caae6d0b7d">llvm::BitcodeFileContents::Symtab</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#a01155893a99bd03c0b13bb52d2f7083e">llvm::object::readIRSymtab</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
