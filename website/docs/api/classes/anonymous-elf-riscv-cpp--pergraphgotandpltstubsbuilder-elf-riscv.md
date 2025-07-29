---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-elf-riscv-cpp-/pergraphgotandpltstubsbuilder-elf-riscv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PerGraphGOTAndPLTStubsBuilder_ELF_riscv` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder">PerGraphGOTAndPLTStubsBuilder&lt;BuilderImplT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-object GOT and PLT Stub builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab244e356b08ca77cd1ceaca5ec1ffb7c">isRV64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e86526adae966dab2df2302101ac97e">isGOTEdgeToFix</a> (Edge &amp;E) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bfeed35ddcbeb8cf6215a2ab33484bf">createGOTEntry</a> (Symbol &amp;Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dcd72966eb5609527df0900bfaaa006">createPLTStub</a> (Symbol &amp;Target)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5701c5ab1b82acc714683679a00d396">fixGOTEdge</a> (Edge &amp;E, Symbol &amp;GOTEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ae3b80ce448b6ac2160c33ef35ef43">fixPLTEdge</a> (Edge &amp;E, Symbol &amp;PLTStubs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53e2e4fc33141fdaeeb0f54653ba0945">isExternalBranchEdge</a> (Edge &amp;E) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4392859b7ec68df3887d5308103c178">getGOTSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838fb16a757ff1336df6f681f4a5f014">getStubsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9ffdfa5b0fd50955691537f7db7520">getGOTEntryBlockContent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1444fc617ac23be74c7ffccc08c0ecba">getStubBlockContent</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407db2295336b3f5cd52af3eafa96503">GOTSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac505114582b4e9b9bf88c3f94c6f361e">StubsSection</a> = nullptr</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cd47d3fcb56da95f5263a1aef4fc09">StubEntrySize</a> = 16</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5206ed12d4e299e06ac911274d94a6ee">NullGOTEntryContent</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6444490361394a7137ce733c83513b">RV64StubContent</a>[StubEntrySize] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9edf6412e3ffccead033ac789f1edc58">RV32StubContent</a>[StubEntrySize] = ...</td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### createGOTEntry() {#a9bfeed35ddcbeb8cf6215a2ab33484bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::createGOTEntry (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a79b0a1f4950543ff5e1ecb66962a3697">llvm::jitlink::Block::addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#acea2468fce08fcf5e4d9f99c6bf44090">llvm::jitlink::PerGraphGOTAndPLTStubsBuilder&lt; PerGraphGOTAndPLTStubsBuilder_ELF_riscv &gt;::G</a>, <a href="#ab244e356b08ca77cd1ceaca5ec1ffb7c">isRV64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a8ecf251fe8eb3fd8d3f4b136feaaec06">llvm::jitlink::riscv::R_RISCV_32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a9a66674bae2c0fac22e4070ab792b196">llvm::jitlink::riscv::R_RISCV_64</a>.</p>

</div>
</div>

### createPLTStub() {#a8dcd72966eb5609527df0900bfaaa006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::createPLTStub (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a79b0a1f4950543ff5e1ecb66962a3697">llvm::jitlink::Block::addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#acea2468fce08fcf5e4d9f99c6bf44090">llvm::jitlink::PerGraphGOTAndPLTStubsBuilder&lt; PerGraphGOTAndPLTStubsBuilder_ELF_riscv &gt;::G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#a2244b4880f35fd1d8a1d32996c9cd40b">llvm::jitlink::PerGraphGOTAndPLTStubsBuilder&lt; PerGraphGOTAndPLTStubsBuilder_ELF_riscv &gt;::getGOTEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a6bb3584479526a49e01e8c909072a467">llvm::jitlink::riscv::R_RISCV_CALL</a> and <a href="#a60cd47d3fcb56da95f5263a1aef4fc09">StubEntrySize</a>.</p>

</div>
</div>

### fixGOTEdge() {#af5701c5ab1b82acc714683679a00d396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::fixGOTEdge (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; GOTEntry)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7ada157a5fb3fa171970dcda67ba91e95c">llvm::jitlink::riscv::R_RISCV_PCREL_HI20</a>.</p>

</div>
</div>

### fixPLTEdge() {#ab8ae3b80ce448b6ac2160c33ef35ef43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::fixPLTEdge (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PLTStubs)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a71c292a54dd4ab86706ecc96fc124d9e">llvm::jitlink::riscv::CallRelaxable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a6bb3584479526a49e01e8c909072a467">llvm::jitlink::riscv::R_RISCV_CALL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a5e9772200453ea0af2a6e0e4016704a1">llvm::jitlink::riscv::R_RISCV_CALL_PLT</a>.</p>

</div>
</div>

### isExternalBranchEdge() {#a53e2e4fc33141fdaeeb0f54653ba0945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::isExternalBranchEdge (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a71c292a54dd4ab86706ecc96fc124d9e">llvm::jitlink::riscv::CallRelaxable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a6bb3584479526a49e01e8c909072a467">llvm::jitlink::riscv::R_RISCV_CALL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7a5e9772200453ea0af2a6e0e4016704a1">llvm::jitlink::riscv::R_RISCV_CALL_PLT</a>.</p>

</div>
</div>

### isGOTEdgeToFix() {#a1e86526adae966dab2df2302101ac97e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::isGOTEdgeToFix (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/riscv/#a7e8800193a803fbffb29c072afe09ab7af72744cd81f5b758df3c36303fc06a82">llvm::jitlink::riscv::R_RISCV_GOT_HI20</a>.</p>

</div>
</div>

### isRV64() {#ab244e356b08ca77cd1ceaca5ec1ffb7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::isRV64 ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#acea2468fce08fcf5e4d9f99c6bf44090">llvm::jitlink::PerGraphGOTAndPLTStubsBuilder&lt; PerGraphGOTAndPLTStubsBuilder_ELF_riscv &gt;::G</a>.</p>


<p>Referenced by <a href="#a9bfeed35ddcbeb8cf6215a2ab33484bf">createGOTEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getGOTEntryBlockContent() {#afa9ffdfa5b0fd50955691537f7db7520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::getGOTEntryBlockContent ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

### getGOTSection() {#aa4392859b7ec68df3887d5308103c178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::getGOTSection ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

### getStubBlockContent() {#a1444fc617ac23be74c7ffccc08c0ecba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::getStubBlockContent ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

### getStubsSection() {#a838fb16a757ff1336df6f681f4a5f014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::getStubsSection ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GOTSection {#a407db2295336b3f5cd52af3eafa96503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section* anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::GOTSection = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

### StubsSection {#ac505114582b4e9b9bf88c3f94c6f361e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section* anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::StubsSection = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NullGOTEntryContent {#a5206ed12d4e299e06ac911274d94a6ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::NullGOTEntryContent</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    {0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

### RV32StubContent {#a9edf6412e3ffccead033ac789f1edc58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::RV32StubContent</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
        0x17, 0x0e, 0x00, 0x00,  
        0x03, 0x2e, 0x0e, 0x00,  
        0x67, 0x00, 0x0e, 0x00,  
        0x13, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

### RV64StubContent {#a1d6444490361394a7137ce733c83513b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::RV64StubContent</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
        0x17, 0x0e, 0x00, 0x00,  
        0x03, 0x3e, 0x0e, 0x00,  
        0x67, 0x00, 0x0e, 0x00,  
        0x13, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>

</div>
</div>

### StubEntrySize {#a60cd47d3fcb56da95f5263a1aef4fc09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{ELF_riscv.cpp}::PerGraphGOTAndPLTStubsBuilder_ELF_riscv::StubEntrySize = 16</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a>.</p>


<p>Referenced by <a href="#a8dcd72966eb5609527df0900bfaaa006">createPLTStub</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-riscv-cpp">ELF_riscv.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
