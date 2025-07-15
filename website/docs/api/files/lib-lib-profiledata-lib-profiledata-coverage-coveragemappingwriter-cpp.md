---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CoverageMappingWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">llvm/ProfileData/Coverage/CoverageMappingWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">llvm/Support/Compression.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;limits&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-coveragemappingwriter-cpp-">anonymous{CoverageMappingWriter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-coveragemappingwriter-cpp-/counterexpressionsminimizer">CounterExpressionsMinimizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather only the expressions that are used by the mapping regions in this function. <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingwriter-cpp-/counterexpressionsminimizer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfaf2220ba561ed163a999bafa256178">encodeCounter</a> (ArrayRef&lt; CounterExpression &gt; Expressions, Counter C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode the counter. <a href="#abfaf2220ba561ed163a999bafa256178">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a338457350c63c707e699e315a98baae5">writeCounter</a> (ArrayRef&lt; CounterExpression &gt; Expressions, Counter C, raw_ostream &amp;OS)</td>
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

### encodeCounter() {#abfaf2220ba561ed163a999bafa256178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned encodeCounter (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt; Expressions, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> C)</td>
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

<p>Encode the counter.</p>


<p>The encoding uses the following format: Low 2 bits - Tag: <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca67a8514f4af2332820b159b681e49b1a">Counter::Zero(0)</a> - A <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> with kind <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca67a8514f4af2332820b159b681e49b1a">Counter::Zero</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca4d833352a08a316752f999f56e6bf06e">Counter::CounterValueReference(1)</a> - A counter with kind <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca4d833352a08a316752f999f56e6bf06e">Counter::CounterValueReference</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca3414aa40642d6bfd511e941d82ed1780">Counter::Expression(2)</a> + <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49cad1416de918b7a5b4457401a093632670">CounterExpression::Subtract(0)</a> - A counter with kind <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca3414aa40642d6bfd511e941d82ed1780">Counter::Expression</a> and an expression with kind <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49cad1416de918b7a5b4457401a093632670">CounterExpression::Subtract</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca3414aa40642d6bfd511e941d82ed1780">Counter::Expression(2)</a> + <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49ca455946e9fb6b90813a5b9480f4063e22">CounterExpression::Add(1)</a> - A counter with kind <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca3414aa40642d6bfd511e941d82ed1780">Counter::Expression</a> and an expression with kind <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49ca455946e9fb6b90813a5b9480f4063e22">CounterExpression::Add</a> Remaining bits - Counter/Expression <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingwriter-cpp">CoverageMappingWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a195beefec055a20e88e7fade73e9c32f">llvm::coverage::Counter::EncodingTagBits</a>.</p>


<p>Referenced by <a href="#a338457350c63c707e699e315a98baae5">writeCounter</a>.</p>

</div>
</div>

### writeCounter() {#a338457350c63c707e699e315a98baae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeCounter (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt; Expressions, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> C, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingwriter-cpp">CoverageMappingWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#abfaf2220ba561ed163a999bafa256178">encodeCounter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemappingwriter/#aeb6fdb4ef8ee00e2c8b013def460e864">llvm::coverage::CoverageMappingWriter::write</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
