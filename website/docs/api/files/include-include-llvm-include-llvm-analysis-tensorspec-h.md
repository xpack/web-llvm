---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/analysis/tensorspec-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `TensorSpec.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/json">json</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tensorspec">TensorSpec</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcff852fdc585a91e56d2bcc03f81730">SUPPORTED_TENSOR_TYPES</a>(M)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TensorSpec encapsulates the specification of a tensor: its dimensions, or "shape" (row-major), its type (see TensorSpec::getDataType specializations for supported types), its name and port (see "TensorFlow: Large-Scale
Machine Learning on Heterogeneous Distributed Systems", section 4.2, para 2: <a href="https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45166.pdf">https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45166.pdf</a>) <a href="#afcff852fdc585a91e56d2bcc03f81730">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ed7d91826d8a6004f4c718c4f18e70">_TENSOR_TYPE_ENUM_MEMBERS</a>(_, Name)&nbsp;&nbsp;&nbsp;Name,</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639e6f844771f3600a1ee0e03d28d4fd">TFUTILS_GETDATATYPE_DEF</a>(T, Name)&nbsp;&nbsp;&nbsp;  template &lt;&gt; TensorType TensorSpec::getDataType&lt;T&gt;();</td>
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

## Macro Definitions

### \_TENSOR\_TYPE\_ENUM\_MEMBERS {#a21ed7d91826d8a6004f4c718c4f18e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _TENSOR_TYPE_ENUM_MEMBERS(_, Name)&nbsp;&nbsp;&nbsp;Name,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/tensorspec-h">TensorSpec.h</a>.</p>

</div>
</div>

### SUPPORTED\_TENSOR\_TYPES {#afcff852fdc585a91e56d2bcc03f81730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SUPPORTED_TENSOR_TYPES(M)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TensorSpec encapsulates the specification of a tensor: its dimensions, or "shape" (row-major), its type (see TensorSpec::getDataType specializations for supported types), its name and port (see "TensorFlow: Large-Scale
Machine Learning on Heterogeneous Distributed Systems", section 4.2, para 2: <a href="https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45166.pdf">https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45166.pdf</a>)</p>

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  M(float, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>)                                                              \
  M(double, Double)                                                            \
  M(int8_t, Int8)                                                              \
  M(uint8_t, UInt8)                                                            \
  M(int16_t, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a150558aeaa819431aeb9729d26b2ac9f">Int16</a>)                                                            \
  M(uint16_t, UInt16)                                                          \
  M(int32_t, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>)                                                            \
  M(uint32_t, UInt32)                                                          \
  M(int64_t, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>)                                                            \
  M(uint64_t, UInt64)
</div>
</dd>
</dl>


<p>Note that the design is motivated by Tensorflow, but it is not intended to be Tensorflow-specific.</p>


<p>Known tensor types. The left part is the C type, the right is a name we can use to identify the type (to implement TensorSpec equality checks), and to use, if needed, when mapping to an underlying evaluator's type system. The main requirement is that the C type we use has the same size and encoding (e.g. endian-ness) as the one used by the evaluator.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/tensorspec-h">TensorSpec.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41d8f43db23dac7e866bba97c9ab171d">llvm::getTensorSpecFromJSON</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af2b57e0937bcdc1b3e0ba67d06dca2b4">llvm::tensorValueToString</a>.</p>

</div>
</div>

### TFUTILS\_GETDATATYPE\_DEF {#a639e6f844771f3600a1ee0e03d28d4fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TFUTILS_GETDATATYPE_DEF(T, Name)&nbsp;&nbsp;&nbsp;  template &lt;&gt; TensorType TensorSpec::getDataType&lt;T&gt;();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/tensorspec-h">TensorSpec.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
