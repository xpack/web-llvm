---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `NativeInlineSiteSymbol.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">llvm/DebugInfo/PDB/Native/NativeInlineSiteSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debuginlineelinessubsection-h">llvm/DebugInfo/CodeView/DebugInlineeLinesSubsection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">llvm/DebugInfo/CodeView/LazyRandomTypeCollection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedeserializer-h">llvm/DebugInfo/CodeView/TypeDeserializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/moduledebugstream-h">llvm/DebugInfo/PDB/Native/ModuleDebugStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeenumlinenumbers-h">llvm/DebugInfo/PDB/Native/NativeEnumLineNumbers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativelinenumber-h">llvm/DebugInfo/PDB/Native/NativeLineNumber.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">llvm/DebugInfo/PDB/Native/NativeSession.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/pdbfile-h">llvm/DebugInfo/PDB/Native/PDBFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/symbolcache-h">llvm/DebugInfo/PDB/Native/SymbolCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/tpistream-h">llvm/DebugInfo/PDB/Native/TpiStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbextras-h">llvm/DebugInfo/PDB/PDBExtras.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/inlineesourceline">InlineeSourceLine</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad619c46f308a2280d51080b4c0a40723">findInlineeByTypeIndex</a> (TypeIndex Id, ModuleDebugStreamRef &amp;ModS)</td>
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

### findInlineeByTypeIndex() {#ad619c46f308a2280d51080b4c0a40723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; InlineeSourceLine &gt; findInlineeByTypeIndex (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Id, <a href="/web-llvm/docs/api/classes/llvm/pdb/moduledebugstreamref">ModuleDebugStreamRef</a> &amp; ModS)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeinlinesitesymbol-cpp">NativeInlineSiteSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/moduledebugstreamref/#a8cb9153e420d5d318c3b8df868436852">llvm::pdb::ModuleDebugStreamRef::getSubsectionsArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa55754bcb413b06333e15211f66f05353">llvm::codeview::InlineeLines</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeinlinesitesymbol/#a2600af2572b1e6d73939dbb2c74e5822">llvm::pdb::NativeInlineSiteSymbol::findInlineeLinesByVA</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
