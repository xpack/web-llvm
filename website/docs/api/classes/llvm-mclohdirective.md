---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mclohdirective
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCLOHDirective` Class

<p>Store <a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> Optimization Hint information (LOH). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCLOHDirective { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">llvm/MC/MCLinkerOptimizationHint.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc50bb84d1759704f64ca0f605b9b3e">LOHArgs</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be6cf5b698ea6d73e30a36fbcf60297">MCLOHDirective</a> (MCLOHType Kind, const LOHArgs &amp;Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc7ca284acde08b1c5ce6941701ff86">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#affc50bb84d1759704f64ca0f605b9b3e">LOHArgs</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec3d91a5e8ea12652b01b4780e9c751">getArgs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c388d4454133dfd0f5b26b0299f99d">emit</a> (const MCAssembler &amp;Asm, MachObjectWriter &amp;ObjWriter) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit this directive as: &lt;kind, numArgs, addr1, ..., addrN&gt; <a href="#a31c388d4454133dfd0f5b26b0299f99d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a019b9e388904b7a0096d467e84ae3c0e">getEmitSize</a> (const MCAssembler &amp;Asm, const MachObjectWriter &amp;ObjWriter) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size in bytes of this directive if emitted in <span class="doxyComputerOutput">ObjWriter</span> with the given <span class="doxyComputerOutput">Layout</span>. <a href="#a019b9e388904b7a0096d467e84ae3c0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33194d6f1e8a4eb30c5eb0c7d26fe92a">emit_impl</a> (const MCAssembler &amp;Asm, raw_ostream &amp;OutStream, const MachObjectWriter &amp;ObjWriter) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit this directive in <span class="doxyComputerOutput">OutStream</span> using the information available in the given <span class="doxyComputerOutput">ObjWriter</span> and <span class="doxyComputerOutput">Layout</span> to get the address of the arguments within the object file. <a href="#a33194d6f1e8a4eb30c5eb0c7d26fe92a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d9db42862a588dc481347c9aee4e8d5">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e44d68a414b6d637ccca5d7defc673">Args</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arguments of this directive. Order matters. <a href="#a38e44d68a414b6d637ccca5d7defc673">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Store <a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> Optimization Hint information (LOH).</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LOHArgs {#affc50bb84d1759704f64ca0f605b9b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCLOHDirective::LOHArgs =  SmallVectorImpl&lt;MCSymbol *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCLOHDirective() {#a8be6cf5b698ea6d73e30a36fbcf60297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCLOHDirective::MCLOHDirective (<a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#affc50bb84d1759704f64ca0f605b9b3e">LOHArgs</a> &amp; Args)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4cce006956b74a136aef7bd1fc3ccd5c">llvm::isValidMCLOHType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a31c388d4454133dfd0f5b26b0299f99d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCLOHDirective::emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter">MachObjectWriter</a> &amp; ObjWriter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit this directive as: &lt;kind, numArgs, addr1, ..., addrN&gt;</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mclinkeroptimizationhint-cpp">MCLinkerOptimizationHint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#aea6f1003a6933f07d06dbce84a8f26cb">llvm::support::endian::Writer::OS</a> and <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a57f7c781103b28d9511e2ddd5aa0eec6">llvm::MachObjectWriter::W</a>.</p>

</div>
</div>

### getArgs() {#a1ec3d91a5e8ea12652b01b4780e9c751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LOHArgs &amp; llvm::MCLOHDirective::getArgs ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>.</p>

</div>
</div>

### getEmitSize() {#a019b9e388904b7a0096d467e84ae3c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCLOHDirective::getEmitSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter">MachObjectWriter</a> &amp; ObjWriter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the size in bytes of this directive if emitted in <span class="doxyComputerOutput">ObjWriter</span> with the given <span class="doxyComputerOutput">Layout</span>.</p>

<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mclinkeroptimizationhint-cpp">MCLinkerOptimizationHint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

### getKind() {#a6bc7ca284acde08b1c5ce6941701ff86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCLOHType llvm::MCLOHDirective::getKind ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emit\_impl() {#a33194d6f1e8a4eb30c5eb0c7d26fe92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCLOHDirective::emit_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OutStream, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter">MachObjectWriter</a> &amp; ObjWriter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit this directive in <span class="doxyComputerOutput">OutStream</span> using the information available in the given <span class="doxyComputerOutput">ObjWriter</span> and <span class="doxyComputerOutput">Layout</span> to get the address of the arguments within the object file.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mclinkeroptimizationhint-cpp">MCLinkerOptimizationHint.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Args {#a38e44d68a414b6d637ccca5d7defc673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MCSymbol *, 3&gt; llvm::MCLOHDirective::Args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Arguments of this directive. Order matters.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>.</p>

</div>
</div>

### Kind {#a9d9db42862a588dc481347c9aee4e8d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCLOHType llvm::MCLOHDirective::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mclinkeroptimizationhint-h">MCLinkerOptimizationHint.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mclinkeroptimizationhint-cpp">MCLinkerOptimizationHint.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
