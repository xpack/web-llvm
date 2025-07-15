---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/sequencetraits-86907747ebbd2cfef93622e3f0326e4e
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SequenceTraits` Struct Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> is not really compatible with the YAMLTraits. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::yaml::SequenceTraits&lt;ArrayRef&lt; T &gt;&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aedc44781c514c85cc4223334f2d3928a">size</a> (IO &amp;io, ArrayRef&lt; T &gt; &amp;seq)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11fec855b4f71be143610ae6e86a56fb">element</a> (IO &amp;io, ArrayRef&lt; T &gt; &amp;seq, size_t index)</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> is not really compatible with the YAMLTraits.</p>


<p>Everything should be immutable in an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>, while the <a href="/web-llvm/docs/api/structs/llvm/yaml/sequencetraits">SequenceTraits</a> expect a mutable version for inputting, but we're only using the outputting capabilities here. This is a hack, but still nicer than having to manually call the YAMLIO internal methods. Keep this in this file so that it doesn't get misused from <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### element() {#a11fec855b4f71be143610ae6e86a56fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument &amp; llvm::yaml::SequenceTraits&lt; ArrayRef&lt; T &gt; &gt;::element (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; io, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &amp; seq, size_t index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a3f9abe4cc7cc808cb6025ed882bcbb7d">llvm::yaml::IO::outputting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### size() {#aedc44781c514c85cc4223334f2d3928a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::yaml::SequenceTraits&lt; ArrayRef&lt; T &gt; &gt;::size (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; io, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &amp; seq)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
