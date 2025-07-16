---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/linecolumnextractor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LineColumnExtractor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::LineColumnExtractor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debuglinessubsection-h">llvm/DebugInfo/CodeView/DebugLinesSubsection.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac30e456e648c6aa3b5de74279adbb0d5">operator()</a> (BinaryStreamRef Stream, uint32_t &amp;Len, LineColumnEntry &amp;Item)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/linefragmentheader">LineFragmentHeader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3624581bbc00abc755dffe4f61261746">Header</a> = nullptr</td>
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


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debuglinessubsection-h">DebugLinesSubsection.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#ac30e456e648c6aa3b5de74279adbb0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LineColumnExtractor::operator() (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Stream, uint32_t &amp; Len, <a href="/web-llvm/docs/api/structs/llvm/codeview/linecolumnentry">LineColumnEntry</a> &amp; Item)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debuglinessubsection-h">DebugLinesSubsection.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debuglinessubsection-cpp">DebugLinesSubsection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/codeview/lineblockfragmentheader/#ae83e8b24e51eabf6e8038511ed144a8f">llvm::codeview::LineBlockFragmentHeader::BlockSize</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/linecolumnentry/#a4706dac27cfeb8283bf6a11a491f4660">llvm::codeview::LineColumnEntry::Columns</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0e494c491fad71e29cc10efce7c59f6ca7e4105e7f11aef8db54945155c4b3907">llvm::codeview::corrupt_record</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="#a3624581bbc00abc755dffe4f61261746">Header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3871bade894b1a946ca1e99876b79b26a2bd22ec907c4c8a5e437e96d426ee4e8">llvm::codeview::LF_HaveColumns</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/linecolumnentry/#aa6f8655f893492900b913be4648981a5">llvm::codeview::LineColumnEntry::LineNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/lineblockfragmentheader/#a2ade456cbf84fbfe12564a3351d4a12d">llvm::codeview::LineBlockFragmentHeader::NameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/linecolumnentry/#a766f4d99a28ae0c2c515a2d9664a08d5">llvm::codeview::LineColumnEntry::NameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/lineblockfragmentheader/#a4fad53ecebe9914a50869bb33275674b">llvm::codeview::LineBlockFragmentHeader::NumLines</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a07e25e055f92f545f94821c4a3cbded8">llvm::BinaryStreamReader::readObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Header {#a3624581bbc00abc755dffe4f61261746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LineFragmentHeader* llvm::codeview::LineColumnExtractor::Header = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debuglinessubsection-h">DebugLinesSubsection.h</a>.</p>


<p>Referenced by <a href="#ac30e456e648c6aa3b5de74279adbb0d5">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debuglinessubsection-h">DebugLinesSubsection.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debuglinessubsection-cpp">DebugLinesSubsection.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
