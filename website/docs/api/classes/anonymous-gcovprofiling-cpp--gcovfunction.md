---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-gcovprofiling-cpp-/gcovfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCOVFunction` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GCOVProfiling.cpp}::GCOVFunction { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovrecord">GCOVRecord</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a> (GCOVProfiler *P, Function *F, const DISubprogram *SP, unsigned EndLine, uint32_t Ident, int Version)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock">GCOVBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5aae71e74e19b8640e88cffd05af09c">getBlock</a> (const BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock">GCOVBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434c532e2946b1d369090a7b6405b42b">getEntryBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock">GCOVBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615d5381c2c4406f7f9e979ef517d5ad">getReturnBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e22bcc60a5f0b17fd330fada87df4b">getFuncChecksum</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9141ca1168edd7cd985be48a52bd218f">writeOut</a> (uint32_t CfgChecksum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c0fb0016878ed002e8a935e0f259db">SP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5323df013382660bd6196b7824274b3">EndLine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0356f4d1428dd799ddd51f8d8f48517f">Ident</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb2fd36238077dd0f2254b871f663e4">FuncChecksum</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af398a4c1a6f0b19eb5d5f16325f3aa54">Version</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock">GCOVBlock</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4e4dec3b861935e3bd7c0fae2f75db">Blocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock">GCOVBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06bf05cea43b72182c03aefb92abf31e">EntryBlock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock">GCOVBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76bb4052b672824a1dbf5fe386a2267">ReturnBlock</a></td>
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


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCOVFunction() {#aa843f97b9cc03fe72d109c21eea6c15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GCOVProfiling.cpp}::GCOVFunction::GCOVFunction (<a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovprofiler">GCOVProfiler</a> * P, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, unsigned EndLine, uint32_t Ident, int Version)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>References <a href="#a2b4e4dec3b861935e3bd7c0fae2f75db">Blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa5323df013382660bd6196b7824274b3">EndLine</a>, <a href="#a06bf05cea43b72182c03aefb92abf31e">EntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#acfb2fd36238077dd0f2254b871f663e4">FuncChecksum</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovrecord/#ac00184608e51488222ea733f0d31d2c4">anonymous{GCOVProfiling.cpp}::GCOVRecord::GCOVRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#ad161260264efb4fb92ab56f92f7dcd1f">getFunctionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>, <a href="#a0356f4d1428dd799ddd51f8d8f48517f">Ident</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovrecord/#a642d495294e1f95a74c02a8046b23298">anonymous{GCOVProfiling.cpp}::GCOVRecord::P</a>, <a href="#ac76bb4052b672824a1dbf5fe386a2267">ReturnBlock</a>, <a href="#ab6c0fb0016878ed002e8a935e0f259db">SP</a> and <a href="#af398a4c1a6f0b19eb5d5f16325f3aa54">Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBlock() {#ad5aae71e74e19b8640e88cffd05af09c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVBlock &amp; anonymous{GCOVProfiling.cpp}::GCOVFunction::getBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Reference <a href="#a2b4e4dec3b861935e3bd7c0fae2f75db">Blocks</a>.</p>

</div>
</div>

### getEntryBlock() {#a434c532e2946b1d369090a7b6405b42b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVBlock &amp; anonymous{GCOVProfiling.cpp}::GCOVFunction::getEntryBlock ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Reference <a href="#a06bf05cea43b72182c03aefb92abf31e">EntryBlock</a>.</p>

</div>
</div>

### getFuncChecksum() {#ae5e22bcc60a5f0b17fd330fada87df4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{GCOVProfiling.cpp}::GCOVFunction::getFuncChecksum ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Reference <a href="#acfb2fd36238077dd0f2254b871f663e4">FuncChecksum</a>.</p>

</div>
</div>

### getReturnBlock() {#a615d5381c2c4406f7f9e979ef517d5ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVBlock &amp; anonymous{GCOVProfiling.cpp}::GCOVFunction::getReturnBlock ()</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Reference <a href="#ac76bb4052b672824a1dbf5fe386a2267">ReturnBlock</a>.</p>

</div>
</div>

### writeOut() {#a9141ca1168edd7cd985be48a52bd218f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCOVProfiling.cpp}::GCOVFunction::writeOut (uint32_t CfgChecksum)</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#a2b4e4dec3b861935e3bd7c0fae2f75db">Blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa5323df013382660bd6196b7824274b3">EndLine</a>, <a href="#a06bf05cea43b72182c03aefb92abf31e">EntryBlock</a>, <a href="#acfb2fd36238077dd0f2254b871f663e4">FuncChecksum</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45dabbbde587f0008e3ec00bbb36188dc3ee">GCOV_TAG_ARCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45daf15ae30d047358de4cc540bc97d2dd0d">GCOV_TAG_BLOCKS</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45dac178d86a1ec0f8b12bc6988fef315383">GCOV_TAG_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a958ded96222c13408529a306519cfae4">llvm::GCOVFunction::getFilename</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#ad161260264efb4fb92ab56f92f7dcd1f">getFunctionName</a>, <a href="#a0356f4d1428dd799ddd51f8d8f48517f">Ident</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ab6c0fb0016878ed002e8a935e0f259db">SP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#a07eccafe60da5abc8c63d630c9dcb28f">wordsOfString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovrecord/#aa49cafc4b1e700289da51762c5680da1">anonymous{GCOVProfiling.cpp}::GCOVRecord::writeString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Blocks {#a2b4e4dec3b861935e3bd7c0fae2f75db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;BasicBlock *, GCOVBlock&gt; anonymous{GCOVProfiling.cpp}::GCOVFunction::Blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a>, <a href="#ad5aae71e74e19b8640e88cffd05af09c">getBlock</a> and <a href="#a9141ca1168edd7cd985be48a52bd218f">writeOut</a>.</p>

</div>
</div>

### EndLine {#aa5323df013382660bd6196b7824274b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{GCOVProfiling.cpp}::GCOVFunction::EndLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a> and <a href="#a9141ca1168edd7cd985be48a52bd218f">writeOut</a>.</p>

</div>
</div>

### EntryBlock {#a06bf05cea43b72182c03aefb92abf31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVBlock anonymous{GCOVProfiling.cpp}::GCOVFunction::EntryBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a>, <a href="#a434c532e2946b1d369090a7b6405b42b">getEntryBlock</a> and <a href="#a9141ca1168edd7cd985be48a52bd218f">writeOut</a>.</p>

</div>
</div>

### FuncChecksum {#acfb2fd36238077dd0f2254b871f663e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{GCOVProfiling.cpp}::GCOVFunction::FuncChecksum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a>, <a href="#ae5e22bcc60a5f0b17fd330fada87df4b">getFuncChecksum</a> and <a href="#a9141ca1168edd7cd985be48a52bd218f">writeOut</a>.</p>

</div>
</div>

### Ident {#a0356f4d1428dd799ddd51f8d8f48517f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{GCOVProfiling.cpp}::GCOVFunction::Ident</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a> and <a href="#a9141ca1168edd7cd985be48a52bd218f">writeOut</a>.</p>

</div>
</div>

### ReturnBlock {#ac76bb4052b672824a1dbf5fe386a2267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVBlock anonymous{GCOVProfiling.cpp}::GCOVFunction::ReturnBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a> and <a href="#a615d5381c2c4406f7f9e979ef517d5ad">getReturnBlock</a>.</p>

</div>
</div>

### SP {#ab6c0fb0016878ed002e8a935e0f259db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DISubprogram* anonymous{GCOVProfiling.cpp}::GCOVFunction::SP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a> and <a href="#a9141ca1168edd7cd985be48a52bd218f">writeOut</a>.</p>

</div>
</div>

### Version {#af398a4c1a6f0b19eb5d5f16325f3aa54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{GCOVProfiling.cpp}::GCOVFunction::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="#aa843f97b9cc03fe72d109c21eea6c15a">GCOVFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
