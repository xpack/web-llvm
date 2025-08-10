---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalartraits-21f54daa5a7f69d1f67ec087e8697447
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ScalarTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::ScalarTraits&lt;IFSBitWidthType&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f4d9cb0c78a06e16471f09993fded9">output</a> (const IFSBitWidthType &amp;Value, void *, llvm::raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b674d28ee553a4d9594696d639f01d7">input</a> (StringRef Scalar, void *, IFSBitWidthType &amp;Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757">QuotingType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae29646f9ce81cceab86823953b02e6e">mustQuote</a> (StringRef)</td>
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


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/ifshandler-cpp">IFSHandler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### input() {#a8b674d28ee553a4d9594696d639f01d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::ScalarTraits&lt; IFSBitWidthType &gt;::input (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Scalar, void *, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3517f5b90f1b05533d172d683533e90">IFSBitWidthType</a> &amp; Value)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/ifshandler-cpp">IFSHandler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3517f5b90f1b05533d172d683533e90a787e77ce2154c004ace6b22f14f53c2b">llvm::ifs::IFS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3517f5b90f1b05533d172d683533e90a6edad8914d3b05e4432315a0fc781bd8">llvm::ifs::IFS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a388c981224806a01d8de4172d5322d3daf60357a8d17e45793298323f1b372a74">llvm::yaml::Scalar</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3517f5b90f1b05533d172d683533e90a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::ifs::Unknown</a>.</p>

</div>
</div>

### mustQuote() {#aae29646f9ce81cceab86823953b02e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QuotingType llvm::yaml::ScalarTraits&lt; IFSBitWidthType &gt;::mustQuote (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/ifshandler-cpp">IFSHandler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757a6adf97f83acf6453d4a6a4b1070f3754">llvm::yaml::None</a>.</p>

</div>
</div>

### output() {#aa3f4d9cb0c78a06e16471f09993fded9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::ScalarTraits&lt; IFSBitWidthType &gt;::output (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3517f5b90f1b05533d172d683533e90">IFSBitWidthType</a> &amp; Value, void *, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/ifshandler-cpp">IFSHandler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3517f5b90f1b05533d172d683533e90a787e77ce2154c004ace6b22f14f53c2b">llvm::ifs::IFS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3517f5b90f1b05533d172d683533e90a6edad8914d3b05e4432315a0fc781bd8">llvm::ifs::IFS64</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/interfacestub/ifshandler-cpp">IFSHandler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
