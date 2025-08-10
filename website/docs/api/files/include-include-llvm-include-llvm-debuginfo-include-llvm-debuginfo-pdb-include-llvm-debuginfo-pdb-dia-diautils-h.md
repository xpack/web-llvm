---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diautils-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DIAUtils.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diasupport-h">llvm/DebugInfo/PDB/DIA/DIASupport.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">llvm/Support/ConvertUTF.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Obj&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad6c60a50832554e59decc8a64f4d6051">invokeBstrMethod</a> (Obj &amp;Object, HRESULT(__stdcall Obj::*Func)(BSTR *))</td>
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

### invokeBstrMethod() {#ad6c60a50832554e59decc8a64f4d6051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Obj&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string invokeBstrMethod (Obj &amp; Object, HRESULT(__stdcall Obj::*)(BSTR *) Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diautils-h">DIAUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/diainjectedsource/#a77c5cc13da317c6218b7511a2c5613e1">llvm::pdb::DIAInjectedSource::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diasourcefile/#a3cb933296a6c147816f6ad92189ee27e">llvm::pdb::DIASourceFile::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diadatastream/#a677ef0fdcdc0d41ac86c67f298e95021">llvm::pdb::DIADataStream::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diatable/#a7c9ce8ff0b715ef26786f629986f27df">llvm::pdb::DIATable::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diainjectedsource/#a4eb62c6b4cfad7ff9931e81aba11b077">llvm::pdb::DIAInjectedSource::getObjectFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diaframedata/#ac69f209c7294cf704c9d103815ccff21">llvm::pdb::DIAFrameData::getProgram</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diainjectedsource/#a0752a69d3b31348cad0770d35e1f7bf4">llvm::pdb::DIAInjectedSource::getVirtualFileName</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-diarawsymbol-cpp-/#a5f98bb827bcc26d5dd09c53134e7f4ed">anonymous{DIARawSymbol.cpp}::PrivateGetDIAValue</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
