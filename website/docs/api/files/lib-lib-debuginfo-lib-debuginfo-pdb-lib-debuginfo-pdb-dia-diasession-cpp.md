---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diasession-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DIASession.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diasession-h">llvm/DebugInfo/PDB/DIA/DIASession.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumdebugstreams-h">llvm/DebugInfo/PDB/DIA/DIAEnumDebugStreams.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumframedata-h">llvm/DebugInfo/PDB/DIA/DIAEnumFrameData.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenuminjectedsources-h">llvm/DebugInfo/PDB/DIA/DIAEnumInjectedSources.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumlinenumbers-h">llvm/DebugInfo/PDB/DIA/DIAEnumLineNumbers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumsectioncontribs-h">llvm/DebugInfo/PDB/DIA/DIAEnumSectionContribs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumsourcefiles-h">llvm/DebugInfo/PDB/DIA/DIAEnumSourceFiles.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumtables-h">llvm/DebugInfo/PDB/DIA/DIAEnumTables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaerror-h">llvm/DebugInfo/PDB/DIA/DIAError.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diarawsymbol-h">llvm/DebugInfo/PDB/DIA/DIARawSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diasourcefile-h">llvm/DebugInfo/PDB/DIA/DIASourceFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diasupport-h">llvm/DebugInfo/PDB/DIA/DIASupport.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/genericerror-h">llvm/DebugInfo/PDB/GenericError.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdb-h">llvm/DebugInfo/PDB/PDB.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">llvm/DebugInfo/PDB/PDBSymbolCompiland.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">llvm/DebugInfo/PDB/PDBSymbolExe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">llvm/Support/ConvertUTF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a07bfb89b80e6e5f6236d958d2b463d2a">ErrorFromHResult</a> (HRESULT Result, const char *Str, Ts &amp;&amp;... Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79fc10fcf921644e9160676b6cbb6e81">LoadDIA</a> (CComPtr&lt; IDiaDataSource &gt; &amp;DiaDataSource)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a255f6f033bc001670067725a827e27fb">getTableEnumerator</a> (IDiaSession &amp;Session) -&gt; CComPtr&lt; T &gt;</td>
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

### ErrorFromHResult() {#a07bfb89b80e6e5f6236d958d2b463d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ErrorFromHResult (HRESULT Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diasession-cpp">DIASession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ade7b9821d9857277506650ed1499c9d8a87eaad3e236d82261f86e38af8e5e724">llvm::pdb::already_loaded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ade7b9821d9857277506650ed1499c9d8a26e75e0e662303271ba764b8ee596b39">llvm::pdb::debug_info_mismatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ade7b9821d9857277506650ed1499c9d8a60a552d6b3bf838addf140d7af11b43d">llvm::pdb::invalid_file_format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ade7b9821d9857277506650ed1499c9d8ad251e6fb723481cde9cc592fa724dd10">llvm::pdb::invalid_parameter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ade7b9821d9857277506650ed1499c9d8ad415f0e30c471dfdd9bc4f827329ef48">llvm::pdb::unspecified</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a2219741a985be587beb5e75fee1417f7">llvm::pdb::DIASession::createFromExe</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a7861193fc9b9776bd882bc12d58cb356">llvm::pdb::DIASession::createFromPdb</a> and <a href="#a79fc10fcf921644e9160676b6cbb6e81">LoadDIA</a>.</p>

</div>
</div>

### getTableEnumerator() {#a255f6f033bc001670067725a827e27fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CComPtr&lt; T &gt; getTableEnumerator (IDiaSession &amp; Session)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diasession-cpp">DIASession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a30309b565fa53a27f30668e22f7cf058">llvm::Enumerator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#abdc957eca6163eecb78c7a4ed35370cc">llvm::pdb::DIASession::getFrameData</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a4e409b80d018d65022d91c49c4cc448a">llvm::pdb::DIASession::getInjectedSources</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#afcae123e5fa168f3a4c02bd3128e8a9b">llvm::pdb::DIASession::getSectionContribs</a>.</p>

</div>
</div>

### LoadDIA() {#a79fc10fcf921644e9160676b6cbb6e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LoadDIA (CComPtr&lt; IDiaDataSource &gt; &amp; DiaDataSource)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diasession-cpp">DIASession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aef1d501dfe72c1eac4158fc2bcbe53e7a0dd27af0aeccac00157ef6768de27e76">llvm::pdb::dia_failed_loading</a>, <a href="#a07bfb89b80e6e5f6236d958d2b463d2a">ErrorFromHResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a2219741a985be587beb5e75fee1417f7">llvm::pdb::DIASession::createFromExe</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a7861193fc9b9776bd882bc12d58cb356">llvm::pdb::DIASession::createFromPdb</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
