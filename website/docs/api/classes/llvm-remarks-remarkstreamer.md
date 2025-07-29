---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/remarks/remarkstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RemarkStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::remarks::RemarkStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">llvm/Remarks/RemarkStreamer.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f86074dc309ee64587dc3658bfc8273">RemarkStreamer</a> (std::unique_ptr&lt; remarks::RemarkSerializer &gt; RemarkSerializer, std::optional&lt; StringRef &gt; Filename=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c419a2b2156482c3e8dafdac20d8a8">getFilename</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the filename that the remark diagnostics are emitted to. <a href="#a13c419a2b2156482c3e8dafdac20d8a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0babb05ddc0134c9293eebf14610b7a">getStream</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return stream that the remark diagnostics are emitted to. <a href="#aa0babb05ddc0134c9293eebf14610b7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">remarks::RemarkSerializer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69aaf30fd94054ce939c141a327094f4">getSerializer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the serializer used for this stream. <a href="#a69aaf30fd94054ce939c141a327094f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb29ff297a87c4e95d366750079f525">setFilter</a> (StringRef Filter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a pass filter based on a regex <span class="doxyComputerOutput">Filter</span>. <a href="#a1fb29ff297a87c4e95d366750079f525">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee23ff9437827d7926a120560a6b363">matchesFilter</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> wether the string matches the filter. <a href="#a9ee23ff9437827d7926a120560a6b363">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38f30618bb9d98cdc216018182ec1a22">needsSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the remarks also need to have associated metadata in a section. <a href="#a38f30618bb9d98cdc216018182ec1a22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d5368e08400ddbfc4558a65532bb01">PassFilter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The regex used to filter remarks based on the passes that emit them. <a href="#a72d5368e08400ddbfc4558a65532bb01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">remarks::RemarkSerializer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53accf9a6b3751916e36a46153582ae">RemarkSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The object used to serialize the remarks to a specific format. <a href="#af53accf9a6b3751916e36a46153582ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8b3f4a0e152a79060b3de6b97fdd1d">Filename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The filename that the remark diagnostics are emitted to. <a href="#aea8b3f4a0e152a79060b3de6b97fdd1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RemarkStreamer() {#a6f86074dc309ee64587dc3658bfc8273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RemarkStreamer::RemarkStreamer (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">remarks::RemarkSerializer</a> &gt; RemarkSerializer, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Filename=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstreamer-cpp">RemarkStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFilename() {#a13c419a2b2156482c3e8dafdac20d8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::remarks::RemarkStreamer::getFilename ()</td>
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

<p>Return the filename that the remark diagnostics are emitted to.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adf30b8e853482f81fa3fa77818e4d2f7">llvm::AsmPrinter::emitRemarksSection</a>.</p>

</div>
</div>

### getSerializer() {#a69aaf30fd94054ce939c141a327094f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">remarks::RemarkSerializer &amp; llvm::remarks::RemarkStreamer::getSerializer ()</td>
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

<p>Return the serializer used for this stream.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adf30b8e853482f81fa3fa77818e4d2f7">llvm::AsmPrinter::emitRemarksSection</a>.</p>

</div>
</div>

### getStream() {#aa0babb05ddc0134c9293eebf14610b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::remarks::RemarkStreamer::getStream ()</td>
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

<p>Return stream that the remark diagnostics are emitted to.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>.</p>

</div>
</div>

### matchesFilter() {#a9ee23ff9437827d7926a120560a6b363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RemarkStreamer::matchesFilter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> wether the string matches the filter.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstreamer-cpp">RemarkStreamer.cpp</a>.</p>

</div>
</div>

### needsSection() {#a38f30618bb9d98cdc216018182ec1a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RemarkStreamer::needsSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the remarks also need to have associated metadata in a section.</p>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstreamer-cpp">RemarkStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44a4e55599a5b5277382b14e6e8eb1f63ef">llvm::cl::BOU_FALSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44ad7c4bd83c337c86d34f6c2d8eba1e736">llvm::cl::BOU_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstreamer-cpp/#a81f84a0b9a32e2346032037d1a136c9d">EnableRemarksSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66a8244cf379b2a4a11d4706e53f510a5f6">llvm::remarks::Separate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea8bc4f729719767dd102c6ac3e55adf1d">llvm::remarks::YAMLStrTab</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adf30b8e853482f81fa3fa77818e4d2f7">llvm::AsmPrinter::emitRemarksSection</a>.</p>

</div>
</div>

### setFilter() {#a1fb29ff297a87c4e95d366750079f525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RemarkStreamer::setFilter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set a pass filter based on a regex <span class="doxyComputerOutput">Filter</span>.</p>


<p>Returns an error if the regex is invalid.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstreamer-cpp">RemarkStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaee5189b9c4db9ad666a88abaf1ee0c4ad7778d0c64b6ba21494c97f77a66885a">llvm::Filter</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Filename {#aea8b3f4a0e152a79060b3de6b97fdd1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt;std::string&gt; llvm::remarks::RemarkStreamer::Filename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The filename that the remark diagnostics are emitted to.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>.</p>

</div>
</div>

### PassFilter {#a72d5368e08400ddbfc4558a65532bb01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Regex&gt; llvm::remarks::RemarkStreamer::PassFilter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The regex used to filter remarks based on the passes that emit them.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>.</p>

</div>
</div>

### RemarkSerializer {#af53accf9a6b3751916e36a46153582ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;remarks::RemarkSerializer&gt; llvm::remarks::RemarkStreamer::RemarkSerializer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The object used to serialize the remarks to a specific format.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">RemarkStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstreamer-cpp">RemarkStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
