---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/irsymtab-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `IRSymtab.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">llvm/Object/IRSymtab.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">llvm/IR/Comdat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">llvm/IR/Mangler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/runtimelibcalls-h">llvm/IR/RuntimeLibcalls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">llvm/MC/StringTableBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">llvm/Object/ModuleSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">llvm/Object/SymbolicFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">llvm/Support/StringSaver.h</a>"
#include "llvm/Support/VCSRevision.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;cassert&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-irsymtab-cpp-">anonymous{IRSymtab.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder">Builder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the temporary state that is required to build an IR symbol table. <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsymtab/filecontents">FileContents</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a> (ArrayRef&lt; BitcodeModule &gt; BMs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5fada963c7ae3551af9b10456feed0a">DisableBitcodeVersionUpgrade</a>("disable-bitcode-version-upgrade", cl::Hidden, cl::desc("Disable automatic bitcode upgrade for version mismatch"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3148194a32572950fd9e753555a101">PreservedSymbols</a>[] = ...</td>
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

## Functions

### upgrade() {#acfa5e41a619b2f37966fdc043ca96c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; FileContents &gt; upgrade (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; BMs)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a8af0e7caf92ff2e049dc40eceafc15be">llvm::irsymtab::build</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a12ff7a5198a84bc90537e2f1007af9fd">llvm::StringTableBuilder::finalizeInOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#af48cff00887e58910f0074f00165b784">llvm::StringTableBuilder::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aa7276fc7b95014e9041e70e8d0bfcdc3d">llvm::StringTableBuilder::RAW</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae2469d919349b52e2d98dd09fed5d623">llvm::StringTableBuilder::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a7d852659ea6c0a8e12cf0c8d5e8d2e16">llvm::irsymtab::readBitcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableBitcodeVersionUpgrade {#aa5fada963c7ae3551af9b10456feed0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableBitcodeVersionUpgrade("disable-bitcode-version-upgrade", cl::Hidden, cl::desc("Disable automatic bitcode upgrade for version mismatch"))</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a7d852659ea6c0a8e12cf0c8d5e8d2e16">llvm::irsymtab::readBitcode</a>.</p>

</div>
</div>

### PreservedSymbols {#a5d3148194a32572950fd9e753555a101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* PreservedSymbols[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    "__ssp_canary_word",
    "__stack_chk_guard",
}
</div>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp">IRSymtab.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-irsymtab-cpp-/#a238e67c3c963aa81c512c6608a8d3900">anonymous{IRSymtab.cpp}::buildPreservedSymbolsSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#aac431323a9a7e840d80cb054493f6067">computeGUIDPreservedSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
